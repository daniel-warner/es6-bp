# BP: ES6, SCSS
This boilerplate contains a webpack and webpack-dev-server setup that contains loaders and plugins to handle the generation of the index.html file, the loading of image files, the conversion of ES6 JavaScript to ES5, the conversion of SCSS/SASS to CSS, and the extraction plus optimization of the CSS.


## CLI Scripts:

#### Development: 
```
npm run start
```

#### Production: 
```
npm run prod
```


## Loaders & Features:

webpack-dev-server with hot reloading

babel-preset-env to convert ES6 JavaScript to ES5

sass-loader to convert SCSS/SASS

mini-css-extract-plugin to extract one CSS file per JS file that contains CSS 

optimize-css-assets-webpack-plugin to optimize the CSS output

postcss-loader for auto-prefixing the CSS output

html-webpack-plugin for the index.html

file-loader to search for and load image files of formats: "jpg|png|gif|jpeg"
