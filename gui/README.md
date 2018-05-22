# No Framework with parcel and lit-html

This is a simple but powerful starter kit for a javascript web project. 

 - No framework
 - Parcel for development (Simple replacement for webpack)
 - HMR just works, no configuration necessary
 - Template rendering with lit-html. 

## Install

After checkout, it is assumed that node/npm is already installed:

```
sudo npm install -g yarn
yarn install
```

Yarn cli: https://yarnpkg.com/lang/en/docs/cli/install/

## `Parcel` with HMR

https://parceljs.org/

To start a local dev server with HMR: 

    parcel index.html

## Templates with `lit-html`

https://github.com/Polymer/lit-html

When a template is repeatedly rendered, only the changed content in the
dom is replaced. Quick demo video: https://github.com/miebach/lit-html-parcel/blob/master/doc/demo.mp4

Good introduction: https://alligator.io/web-components/lit-html/

## How to build this project from scratch

1. Install node system wide
2. Install yarn with node system wide 
3. Go to the empty folder for the new project
4. Start a new parcel project following the parcel instructions (uses yarn) https://parceljs.org/getting_started.html

   The package ´parcel-bundle´ should be installed globally, and not be added locally into the project as a dev dependency, otherwise parcel HMR might not work
   
5. Add lit-html with yarn to the project
