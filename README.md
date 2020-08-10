# Sapper Firebase Demo
This repository is companion code to
[Build an SSR web app with Firebase functions, hosting, and Svelte Sapper](https://blog.logrocket.com/build-an-ssr-web-app-with-firebase-functions-hosting-and-svelte-sapper/)

To get this up and running for your own firebase project, make sure you do the following:
1. Have Firebase functions install globally with `npm i -g firebase-tools`
1. Change the project name in `.firebaserc` to match your own Google Cloud Project
1. install your functions node packages with `cd functions` then `npm i`
1. build your sapper project with `npm run build` (you can use `npm run dev` while you are building your sapper app without needing to run firebase in the background.)
1. test it locally with `firebase serve`
1. deploy with `firebase deploy`

