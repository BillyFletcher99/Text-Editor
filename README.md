# Text-Editor

## Summary

Users can create notes or code snippets with or without an internet connection and then retrieve them reliably for later use in this web text editor. Through the integrated service worker and cache API, the application remains fully functional even when no internet connection is available. Offline access to visited pages is possible even with this application.

## Table of Contents

- [Usage](#Usage)
- [Built With](#Built-With)
- [Demonstrations](#Demonstrations)

## Demonstrations

It will be necessary to install Node.js and various npm packages in order to run this application. All of which can be found in the "Built-with" section.
A package.json file contains the required modules, which are then installed via the CLI or integrated terminal by typing npm run install.

### Usage

Below is a screenshot of the folder layout


![screenshot of client-server](https://user-images.githubusercontent.com/105595889/194714709-f4d82b5c-a9f5-4e11-a51b-29fda45065ba.png)


Screenshot of "NPM run start"

![snippet of run start](https://user-images.githubusercontent.com/105595889/194714775-effa277c-6d61-475c-8aa7-5f8473d0a511.png)

screenshot of text-editor JATE

![screenshot of JATE](https://user-images.githubusercontent.com/105595889/194715275-4aa7d106-0df6-42ba-9a09-4eaf8cf457f4.png)

after install, app comes up, and you can see it running sucessfully in the bar below as well (last to the right) 

![after install](https://user-images.githubusercontent.com/105595889/194716585-e0f9b32f-952e-4cb0-a4ee-69c12c0986cc.png)

This screenshot is of content that has been retrieved from IndexedDB in the text editor

![last screenshot](https://user-images.githubusercontent.com/105595889/194729955-ef62cae6-aeaf-4a82-b1ca-7afab2ff7e0e.png)


![Another screenshot](https://user-images.githubusercontent.com/105595889/194730086-964d1fb5-01bf-4e0b-848a-81a9c5bda5f2.png)




### Built-With

  * IndexedDB
  * webpack
  * Babel
  * WebpackPwaManifest
  * webpack-dev-server
  * CSS-loader
  * Concurrently
  * express
