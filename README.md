# Grav CMS Development starter Package

## Requirements

### Windows
- unzip http://stahlworks.com/dev/unzip.exe
- Docker
- git

### Linux / Mac
- unzip 
- Docker
- git


## Installation

`npm run dev:install`


## Grav commands

**Install Plugins**

For example Admin Plugin
`npm run grav:install admin`

**Install Themes**

`npm run grav:install bootstrap4`

## Strukture

data -> Storage for shared stuff 
user -> Grav User dir mounted to the docker container. This is the main directory.
tmp -> Downloads and temp stuff to store

## Running

After `npm run dev:install` is your website Running and up on http://localhost:8080