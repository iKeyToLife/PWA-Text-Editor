# PWA-Text-Editor

## Table of Contents
- [Description](#description)
- [User Story](#user-story)
- [Acceptance Criteria](#acceptance-criteria)
- [Mock-Up](#mock-up)
- [Installation](#installation)
- [Usage](#usage)
- [Key Features](#key-features)
- [Technologies](#technologies)
- [Repository Link](#repository-link)
- [Deployment Link](#deployment-link)

## Description
I need to create a text editor that works in the browser and adheres to PWA (Progressive Web Application) standards. This will be a single-page application that supports data persistence using various technologies to ensure it remains reliable even without an internet connection. The app should be fully functional offline. I will start with an existing application and add methods for storing data in IndexedDB using the idb package to simplify working with the IndexedDB API and ensure data is saved properly.

## User Story

```md
AS A developer,
I WANT to create notes or code snippets with or without an internet connection,
SO THAT I can reliably retrieve them later.
```

## Acceptance Criteria

```md
GIVEN a text editor web application,
WHEN I open my application in the editor,
THEN I see client and server code files.
WHEN I run `npm run start` from the root directory,
THEN I find that my application should start the backend and serve the client.
WHEN I run the text editor from the terminal,
THEN I find that my JavaScript files have been bundled using webpack.
WHEN I run webpack plugins,
THEN I find that a generated HTML file, service worker, and manifest file are created.
WHEN I use next-gen JavaScript in my application,
THEN the text editor functions in the browser without errors.
WHEN I open the text editor,
THEN IndexedDB has immediately created a database storage.
WHEN I enter content and close the window,
THEN the content in the text editor is saved with IndexedDB.
WHEN I reopen the text editor after closing it,
THEN I find that the content in the text editor has been retrieved from IndexedDB.
WHEN I click on the Install button,
THEN the web application is downloaded as an icon on my desktop.
WHEN I load my web application,
THEN I have a registered service worker using Workbox for caching static assets.
WHEN I deploy to Render,
THEN I have proper build scripts for a webpack application.
```

## Mock-Up

Below are screenshots demonstrating the application’s functionality:

![Application Demo.](./assets/images/00-demo.gif)

![Manifest file](./assets/images/01-manifest.png)

![Service worker registered](./assets/images/02-service-worker.png)

![IndexedDB storage](./assets/images/03-idb-storage.png)

## Installation

To install the application, follow these steps:

1. Clone the repository:
   ```bash
   git clone <repository-url>
2. Navigate to the project directory:
   ```bash
   cd <project-directory>
3. Install the dependencies:
   ```bash
   npm install
4. Start the server:
   ```bash
   npm start

## Usage

1. To build and run the application, use the command:
   ```bash
   npm run start
2. Use the browser to test the application, creating and saving text notes online and offline.

## Key Features

- A text editor that works as a PWA.
- Supports saving data in IndexedDB using the `idb` package.
- Can be installed as a desktop web application.
- Works offline, saving content for future retrieval.

## Technologies

- Node.js - runtime environment.
- Express.js - web framework for Node.js.
- IndexedDB – for local data storage.
- Workbox – for resource caching and service worker registration.
- Webpack – for bundling JavaScript files.

## Repository Link
[PWA Text Editor Repository](https://github.com/iKeyToLife/PWA-Text-Editor)

## Deployment Link
[PWA Text Editor Deployment Link]()