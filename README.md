## Ionic App Demo
This is a sample Ionic 2 App with Angular 2 that consumes the Node API from here https://github.com/Funkygeek/profileapp

## Run the app
Make sure you have [nodejs](https://nodejs.org/en/) installed.

Install typecript and typings
```bash
$ npm install -g typescript
$ npm install -g typings
```

Install Ionic 2
```bash
$ npm install -g ionic@beta 
```

Install Cordova
```bash
$ npm install -g cordova
```

Clone this repo
```bash
$ git clone https://github.com/bhavikkabaria23/ionicApp-demo
```

cd into the "ionicApp-demo" folder run npm install
```bash
$ npm install
```
install typings
```bash
$ typings install
```
### Target Node API
Find [resources.ts](https://github.com/bhavikkabaria23/ionicApp-demo/blob/master/app/resources.ts) file and change "apiUrl" as you want.

Serve the app
```bash
$ ionic serve
```

Head to http://localhost:8100 in your browser and you'll see the app running
