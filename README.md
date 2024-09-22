#

[![Netlify Status](https://api.netlify.com/api/v1/badges/630cf576-cf1f-4678-8ac3-8666a53ab0e5/deploy-status)](https://app.netlify.com/sites/mfz1mc-registry/deploys)

## Pre-requisite

- [packwiz](https://github.com/packwiz/packwiz)

## How to add mod

### Mod from curseforge

1. Go to project folder `cd <project>`
2. Run `packwiz curseforge add <curseforge-url-page|slug|id>`

## How to add modpack

1. Download modpack zip file and extract it
2. Go to project folder `cd <project>`
3. Copy mods, config, defaultconfigs, scripts and resources from the extracted folder to the project folder
4. Run `packwiz curseforge detect` to convert .jar file to metafile
5. Run `packwiz refresh` to add other file to index
