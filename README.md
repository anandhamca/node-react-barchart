### NODE-REACT-BARCHART
### Barchart Client application using Reactjs ,displayed on server using Nodejs.

D3 Basic Barchart using Reactjs and Nodejs. A few examples of the available charts can be seen below, the others can be [viewed here](https://reactiva.github.io/react-d3-website/).

![react-d3 chart images](https://raw.githubusercontent.com/esbullington/react-d3-website/gh-pages/img/multiseries.png)

**Caution:**  alpha state software. Chart APIs will change. Breaking changes will occur at each minor (0.x) release, until we reach version 1.0.  At that point, we'll closely follow the [semver](http://semver.org/) specification.

[![Build Status](https://travis-ci.org/esbullington/react-d3.svg?branch=master)](http://blog.scottlogic.com/2015/09/03/d3-without-d3.html)

### Version
![npm version](https://badge.fury.io/js/npm.svg)


### Basic usage

## Before work on this project check the following:
  install nodejs and verify by using $node -v or $node --version ,if the node is installed it shows the version of installed node.Check [here](https://nodejs.org/en/download/package-manager) for how to install nodejs .Same for npm check [here](https://docs.npmjs.com/cli/install).
    

First, install via `npm`:

`npm install node-react-barchart`

  Then, import into your project.
  
 Otherwise, go to project path and do:
 
 `npm install`
 
  This will create node_modules.
  
  Second, use $`grunt` to build client task:
    
  Before use grunt code install grunt on locally.Check [here](http://gruntjs.com/getting-started) for install grunt.If grunt need permission access ,install grunt using as root login .Check [here](http://askubuntu.com/questions/91598/how-do-i-login-as-root) root login .
    
    Then, use $`grunt`.This will show:
    
    Running "browserify:all" (browserify) task
    >> Bundle app/built.js created.
    
  Finally, run `node server.js`
    
    Before run this use,`$ npm install connect serve-static`
    
  
    
  Check on your browser `127.0.0.1:8989`
    
  Barchart will display on server.
     
  [reference](http://blog.scottlogic.com/2015/09/03/d3-without-d3.html)

