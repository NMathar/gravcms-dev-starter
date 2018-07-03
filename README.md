# Grav CMS Development starter Package

##Info
Grav is a modern open source flat-file CMS.

https://getgrav.org/

## Requirements

### Windows
- nodejs
- unzip http://stahlworks.com/dev/unzip.exe
- Docker
- git

### Linux / Mac
- nodejs
- unzip 
- Docker
- git


## Installation

`npm run dev:install`

## Start dev Environment

`npm run dev`

## Grav commands

**Install Plugins**

For example Admin Plugin
`npm run grav:install admin`

**Install Themes**

`npm run grav:install bootstrap4`

**Clear cache**

`npm run grav:cmd clearcache`

## Strukture

data -> Storage for shared stuff 

user -> Grav User dir mounted to the docker container. This is the main directory.

tmp -> Downloads and temp stuff to store

## Running

After `npm run dev:install` is your website Running and up on http://localhost:8080