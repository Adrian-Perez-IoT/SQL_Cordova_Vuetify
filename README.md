# vue-csv-sample-dos

## Project setup
```
npm install
```
## Probar en el celular (prerequisito: tener siempre conexion adb )
Modo development
```
npm run cordova-serve-android
```

## Modo produccion
Genera los ficheros necesarios en src-cordova/wwww/
```
npm run cordova-build-only-www-android
```
Instala y ejecutar el .apk final (modo producción)
```
cd src-cordova
cordova run android
```













### Compiles and hot-reloads for development
```
npm run serve
```

### Compiles and minifies for production
```
npm run build
```

### Lints and fixes files
```
npm run lint
```

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).
