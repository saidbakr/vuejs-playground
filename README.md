# vuejs playground

This is my playground for learning hands on experience with vuejs

# Idea

Simple vuejs Application to get info for given github username

# Input

Github username

# Output

- name
- email
- avatar
- company
- location
- number of repos
- number of public gists
- number of followers
- number of following

# How to install?

After cloning the repo. and from the project's root folder, `vuejs-playground` folder do the following:

 1. `npm install` to install all dependencies in `package.json`
 2. `npm run start` to automatically open the default browser on local http server. Checkout [live-server](https://www.npmjs.com/package/live-server#usage-from-command-line) documenation in order to know some customization features of it in `package.json` for example, to start it on port 8888:

 ```
 ...
 "scripts": {
    "start": "live-server --port=8888",
    ... 
 ```

<<<<<<< HEAD
 If you would like to run it locally. i.e from the local filesystem, you have to rmove the prefixed slash of the src attribute of the script tag in `index.html` to be `build/main.js` instead of `/build/main.js`.

 
=======
 However, if you have any way to host it via any http server, doing that is better. One suggested way to do that if you have PHP installed on your system is to run `php -S localhost:8000` from the project's root folder.

>>>>>>> 6cd4242d1fb65f1af4a89589033945a0c53a2424
