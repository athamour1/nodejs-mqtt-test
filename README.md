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

[![asciicast](https://asciinema.org/a/432904.svg)](https://asciinema.org/a/432904)

## More to read
- https://github.com/mqttjs/MQTT.js/
- https://nodejs.org/en/docs/guides/getting-started-guide/
- https://www.ibm.com/docs/en/ibm-mq/8.0?topic=telemetry-publishsubscribe
- http://www.steves-internet-guide.com/mqtt-publish-subscribe/
- https://www.hivemq.com/blog/mqtt-essentials-part2-publish-subscribe/

## Music to listen along
**[sci-fi-ambient](https://www.youtube.com/watch?v=C4MpzSMkinw)**
