# threejs-boilerplate
- threejs
- ES6 with polyfill for async await
- Webpack
- Dev server with hot-module-reloading

## Install
```
git clone https://github.com/nickagliano-st/threejs-boilerplate.git your-app # change your-app to the name of your project
cd your-app
git remote remove origin
# edit the package.json (name and author fields, whatever else you want to edit), then continue on
npm install
npm run dev
```

## Build for prod
```
npm run build
```

# Directory structure

- `/app` holds app code
  - `/app/index.js` is the entrypoint
  - `/app/api/` holds api things
  - `/app/components` holds javascript objects, classes, etc.
