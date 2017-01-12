# todo_with_vue

> A simple TODO using Vue.js and Firebase

## Live Demo

You can see [LIVE DEMO](https://leop0ld-3d0a2.firebaseapp.com/).

## Using skill set
- [Vue.js](https://vuejs.org/)

- [Vuefire](https://github.com/vuejs/vuefire)

- [Firebase](https://firebase.google.com)


And I am helped a lot here -> [VueFire6Pack-Demo](https://github.com/kangsLee/VueFire6Pack-Demo)

## Build Setup

``` bash
# install dependencies
npm install

# serve with hot reload at localhost:8080
npm run dev

# build for production with minification
npm run build

# run unit tests
npm run unit

# run e2e tests
npm run e2e

# run all tests
npm test
```

For detailed explanation on how things work, checkout the [guide](http://vuejs-templates.github.io/webpack/) and [docs for vue-loader](http://vuejs.github.io/vue-loader).

## Deploy using firebase

```bash
# Install Firebase cli
$ npm install -g firebase-tools

# and init firebase project
$ firebase init

# 1. Select Real time database
# 2. then select your project or create it
# 3. Select using database.rules.json
# 4. Select public directory -> dist
# 5. /index.html -> Yes
# 6. index.html Overwrite? -> No
# 7. Complete!

# Do this command if everything is complete
$ firbase deploy

# Success!
```
