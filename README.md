# Ag-grid bug

Created this repo for providing a reproducible environment to Ag-grid team.
Issue reported here: [https://github.com/ag-grid/ag-grid/issues/6853](https://github.com/ag-grid/ag-grid/issues/7803).

## Error message I'm seeing when running the app in local or building the app

```
Module not found: Error: Can't resolve 'react-dom/server' in '/[REDACTED]/ag-grid-bug/node_modules/ag-grid-react/dist/package'
Did you mean 'server.browser.js'?
BREAKING CHANGE: The request 'react-dom/server' failed to resolve only because it was resolved as fully specified
(probably because the origin is strict EcmaScript Module, e. g. a module with javascript mimetype, a '*.mjs' file, or a '*.js' file where the package.json contains '"type": "module"').
The extension in the request is mandatory for it to be fully specified.
Add the extension to the request.
ERROR in ./node_modules/ag-grid-react/dist/package/index.esm.mjs 73:0-56
Module not found: Error: Can't resolve 'react-dom/server' in '/[REDACTED]/ag-grid-bug/node_modules/ag-grid-react/dist/package'
Did you mean 'server.browser.js'?
BREAKING CHANGE: The request 'react-dom/server' failed to resolve only because it was resolved as fully specified
(probably because the origin is strict EcmaScript Module, e. g. a module with javascript mimetype, a '*.mjs' file, or a '*.js' file where the package.json contains '"type": "module"').
The extension in the request is mandatory for it to be fully specified.
Add the extension to the request.

webpack compiled with 1 error
```


## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.

### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.
