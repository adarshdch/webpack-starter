# webpack-stater
Start learning webpack from scratch

## Steps to use webpack

### Initialize package.json with default values
```npm init```

### Install webpack globally
```npm install -g webpack```

### Create a bundle.js file from entry.js file
```webpack entry.js bundle.js```

#### -w flag checks for any modification in source js files and creates the bundle.js file for any change continuously.
```webpack -w entry.js bundle.js```

### Install moment libray which is used to manipulate date and time. Supports localization as well.
```npm i -S moment```

### create displayTime.js file

### Use --devtool source-map  to be able to debug the code
```webpack -w --devtool source-map entry.js bundle.js```

### Create style.css and use in entry.js file


### Install css-loader and style-loader as dev dependencies
```npm i css-loader style-loader -D```

