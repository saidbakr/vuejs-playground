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

After cloning the repo. and from the project's root `vuejs-playground` folder do the following:

 1. `npm install vue`
 2. `npm install webpack`
 3. `npm install babel-core babel-loader`
 4. `npm install babel-cli babel-preset-es2015`
 5. `npm install vue-template-compiler`
 6. `npm install css-loader`
 7. `npm run build`

 If you would like to run it locally. i.e from the local filessystem, you have to rmove the prefixed slash of the src attribute of the script tag in `index.html` to be `build/main.js` instead of `/build/main.js`.

 However, if you have any way to host it via any http server, doing that is better. One suggested way to do that if you have PHP installed on your system is to run `php -S localhost:8000` from the project's root folder.

