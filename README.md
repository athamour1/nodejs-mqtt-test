# nodejs-mqtt-test

## Dependacies
- Mosquitto brocker
- Node JS
## install packages
```bash
$ npm install 
```
or
```bash
$ yarn install 
```
## Run
```bash
$ mosquitto 
```
and 
```bash
$ node node app.js 
```
and at last to send an mqtt signal run
```bash
$ mosquitto_pub -h localhost -p 1883 -t test -m "Hello mqtt from terminal"
```