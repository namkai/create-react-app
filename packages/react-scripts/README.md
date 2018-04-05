# elm-scripts


This package includes scripts and configuration used by [Create React App](https://github.com/facebookincubator/create-react-app).<br>
Please refer to its documentation:

* Configuration  - This is exceptionally easy to integrate into an exisiting application. In your package.json simply replace react-scripts with elm-scripts and everything should work. Good luck!

```diff
 {
   "name": "my-react-app",
   "version": "0.1.0",
   "private": true,
   "dependencies": {
     "react": "^16.3.1",
     "react-dom": "^16.3.1",
-    "react-scripts": "1.1.4"
+    "elm-scripts": "1.1.4-elm.0"
   },
   "scripts": {
     "start": "react-scripts start",
     "build": "react-scripts build",
     "test": "react-scripts test --env=jsdom",
     "eject": "react-scripts eject"
   }
 }
```


* [Getting Started](https://github.com/facebookincubator/create-react-app/blob/master/README.md#getting-started) – How to create a new app.
* [User Guide](https://github.com/facebookincubator/create-react-app/blob/master/packages/react-scripts/template/README.md) – How to develop apps bootstrapped with Create React App.
