# Text Editor
Deployed Heroku:  https://immense-refuge-61088.herokuapp.com/

## Description
This app is to build a text editor that runs in the browser. The app will be a single-page application that meets the PWA criteria. The application will also able to be downloaded onto your computer or mobile device to be used outside of the browser.
The application will be invoked with the following command:
``` 
npm start
``` 
## Table of Contents
- [Author info.](#autor-info) 
- [User Story](#user-story)
- [Acceptance Criteria](#acceptance-criteria)
- [Technologies](#technologies)
- [Mockup](#mock-up)
- [Licencia](#licencia)

## Autor info:
```
 Eder Rodrigo Ramirez Contreras 
 Gitgub: https://github.com/kdher/
 mail: edher.fca@gmail.com
```
## User Story

```md
AS A developer
I WANT to create notes or code snippets with or without an internet connection
SO THAT I can reliably retrieve them for later use
```

## Acceptance Criteria

```md
GIVEN a text editor web application
WHEN I open my application in my editor
THEN I should see a client server folder structure
WHEN I run `npm run start` from the root directory
THEN I find that my application should start up the backend and serve the client
WHEN I run the text editor application from my terminal
THEN I find that my JavaScript files have been bundled using webpack
WHEN I run my webpack plugins
THEN I find that I have a generated HTML file, service worker, and a manifest file
WHEN I use next-gen JavaScript in my application
THEN I find that the text editor still functions in the browser without errors
WHEN I open the text editor
THEN I find that IndexedDB has immediately created a database storage
WHEN I enter content and subsequently click off of the DOM window
THEN I find that the content in the text editor has been saved with IndexedDB
WHEN I reopen the text editor after closing it
THEN I find that the content in the text editor has been retrieved from our IndexedDB
WHEN I click on the Install button
THEN I download my web application as an icon on my desktop
WHEN I load my web application
THEN I should have a registered service worker using workbox
WHEN I register a service worker
THEN I should have my static assets pre cached upon loading along with subsequent pages and static assets
WHEN I deploy to Heroku
THEN I should have proper build scripts for a webpack application
```

## Technologies 
* Express.js
* Node js
* JavaScript
* Webpack


## Mock-Up
The following animation demonstrates the application functionality:

![image](./Assets/imagenes.png)

## Licencia
[![license](https://img.shields.io/badge/license-MIT-blue)](https://shields.io)


