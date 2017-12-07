# Vuejs Parcel Example

A minimum viable Vue app with [Parcel Bundler](https://parceljs.org).

## Getting started

Clone and install deps
```
git clone git@github.com:zhiephie/vue-parcel-example.git
cd vue-parcel-example
yarn 
yarn start
```

Then open `http://localhost:1234` and edit `index.js` and press save. Parcel will automagically hot reload you files whenever you make changes.


## Building for Production

```
npm run build
```

This will compile your JS and copy your `index.html` to the `dist` folder which you can deploy whereever as as a good ol' webpage.

> Note: [There is a bug in Parcel right now messing up minified builds with uglifyjs](https://github.com/parcel-bundler/parcel/issues/8)




