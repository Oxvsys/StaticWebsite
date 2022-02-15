# Static File to deploy on firebase

1. Download Node JS
    https://nodejs.org/en/
2. Check If Node Is Installed
    node -v
    npm -v
3. npm i -g firebase
4. firebase login
5. firebase init
6. ? Are you ready to proceed? (Y/n) y
7. 
``` ? Which Firebase features do you want to set up for this directory? Press Space to select features, then Enter to confir
m your choices. 
e
 ( ) Firestore: Configure security rules and indexes files for Firestore
 ( ) Functions: Configure a Cloud Functions directory and its files
>(*) Hosting: Configure files for Firebase Hosting and (optionally) set up GitHub Action deploys
 ( ) Hosting: Set up GitHub Action deploys
 ( ) Storage: Configure a security rules file for Cloud Storage
 ( ) Emulators: Set up local emulators for Firebase products ```
8.

 ? Please select an option: 
  Use an existing project 
> Create a new project 
  Add Firebase to an existing Google Cloud Platform project 
  Don't set up a default project 

  9.
  ? Please specify a unique project id (warning: cannot be modified afterward) [6-30 characters]:
 () sample112

 10
 What would you like to call your project? (defaults to your project ID)
 11
 What do you want to use as your public directory? src

 Configure as a single-page app (rewrite all urls to /index.html)? No

 ? Set up automatic builds and deploys with GitHub? (y/N) 

 File src/index.html already exists. Overwrite? (y/N) N

 firebase deploy