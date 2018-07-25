# Grav CMS Development starter Package

## Info
Grav is a modern open source flat-file CMS.

https://getgrav.org/


This is a perfect ready to run Dev environment to build fast and flexible your Grave CMS Homepage.

## Requirements

### Windows
- nodejs
- unzip http://stahlworks.com/dev/unzip.exe
- Docker
- docker-compose
- git

### Linux / Mac
- nodejs
- unzip 
- Docker
- docker-compose
- git


## Installation

`npm install`

`npm run dev:install`

After `npm run dev:install` your website is up and running on http://localhost:8080 or your defined port at package.json

## Start dev Environment

Our container is running and our local dev environment is accessable but it feels a bit clunky to make changes and refresh page and again and again...

So to prevent this we have installed a nice tool called browser-sync we can run this tool with

`npm run dev`

after this command our website is opening and after changes in the user directory our browser reload automatically and save us from annoying tasks.

## Grav commands

**Install Plugins**

For example Admin-Plugin
`npm run grav:install admin`

**Install Themes**

`npm run grav:install bootstrap4`

**Clear cache**

`npm run grav:cmd clearcache`

**Upgrade Grav CMS**

`npm run grav:gpm self-upgrade`

## Structure

data -> Storage for shared stuff 

docker -> Build Script to change Grav Version easily

*to run different Grav Versions you need to uninstall your environment and change the version in package.json and install it again* 

user -> Grav user dir mounted to the docker container. This is the main directory of all code changes.

tmp -> Downloads and temp stuff to store
