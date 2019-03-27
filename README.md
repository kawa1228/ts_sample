# ts_sample

> My groovy Nuxt.js project
https://tocca-project-9f4fc.firebaseio.com

## Build Setup

``` bash
# install dependencies
$ npm install

# serve with hot reload at localhost:3000
$ npm run dev

# build for production and launch server
$ npm run build
$ npm start

# generate static project
$ npm run generate
```

For detailed explanation on how things work, checkout [Nuxt.js docs](https://nuxtjs.org).

# .env

for [direnv/direnv](https://github.com/direnv/direnv)

```
$ touch .envrc
```

```
export FIREBASE_API_KEY=<API KEY>
```

```
$ direnv allow
```

# firebase

```
$ firebase login
$ firebase init
```

| to use as your public directory ? **dist**

# deploy

```
$ npm npm run-script build
$ firebase deploy
```
