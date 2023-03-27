# text-editor
```
AS A developer
I WANT to create notes or code snippets with or without an internet connection
SO THAT I can reliably retrieve them for later use
```

## Acceptance Criteria 
```
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

## Table of Contents

* [Technologies](#technologies)
* [Link to Repo](#link-to-repo)
* [Deployed Application](#deployed-application)
* [Example GIF's](#example-gifs)
* [Summary](#summary)
* [Challenge Help](#challenge-help)

## Technologies 
* IndexedDB
* JavaScript
* Express.js
* Webpack
* Babel

## Link to Repo
[GitHub](https://github.com/sarahlang9800/text-editor)

## Deployed Application
[Heroku]()

## Example GIF's 
![Example Animations](/Assets/00-demo.gif)
![Example Animations](/Assets/01-manifest.png)
![Example Animations](/Assets/02-service-worker.png)
![Example Animations](/Assets/03-idb-storage.png)

## Summary
* This text editor uses IndexedDB to create an object store and includes both GET and PUT methods
* Application works without an internet connection
* Automatically saves content inside the text editor when the DOM window is unfocused
* Bundled with webpack
* Created a service worker with workbox that Caches static assets
* Application uses babel in order to use async / await
* Application has a generated `manifest.json` using the `WebpackPwaManifest` plug-in
* Can be installed as a Progressive Web Application

### Challenge Help
* AskBCS Learning Assistants