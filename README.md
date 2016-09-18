# AngularJS Demo with steps


## _Step-1_


## Initializing package.json


Create package.json to initailize project details and project dependencies

### Steps to initialize package.json
- **npm init** (For adding project details, and node modules)
- **npm install http-server** (For installing node module http-server)


## Creating .bowerrc


Creating the bowerrc file with the bower_component paths


## Initializing bower.json


Create bower.json to initialize project frameworks and libraries dependencies


### Steps to initialize bower.json
- **bower init --config.interactive** (For adding the frameworks and library dependencies)
- **bower install angular**
- **bower install angular-animate**
- **bower install angular-mocks**
- **bower install angular-resource**
- **bower install angular-route**
- **bower install bootstrap**
- **bower install jquery**


## _Step-2_


## Starting http-server with node
- Add "start": "http-server ./app -a localhost -p 8000 -c-1", in dependency.json
- **npm start** to start http-server with node
- Create **index.html** to initialize the static template


## _Step-3_


## Creating angular template
- Create **app.js** to create module and controller
- Create angular module **angular.module('moduleName',[])** with module name **phonecatApp**, attach module name to **ng-app="phonecatApp"**
- Create controller **PhoneListController**, attach controller name to body tag **ng-controller="PhoneListController"**
- Inject **$scope** in the cotroller to create **phones** object to create dynamic template
- Add **app.js** to the scripts tag in the **index.html**