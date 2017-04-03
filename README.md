This repo created for testing work and performance Box previewer on iPad

## In Web folder you can find web version

Before running please specify correct id and token in `index.html`

Install
```
cd web/
npm install
```
Start:
```
npm start
```

## In Cordova folder you can find cordova version

Install
```
npm i -g cordova

cd cordova/
cordova platform add ios
```

Start
```
cordova emulate ios --target="iPad-Air" // for start in the emulator
cordova run ios // for deploy to the connected device
```
