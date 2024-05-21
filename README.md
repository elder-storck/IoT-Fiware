# IoT-Fiware

## Criando Agente IoT 

``` bash
git clone https://github.com/FIWARE/tutorials.IoT-Sensors.git
cd tutorials.IoT-Sensors
git checkout NGSI-LD

./services start;
```

**Device Monitor**

[Device Monitor](http://localhost:3000/device/monitor)

``` bash
curl -iX POST 'localhost:3001/iot/water001' \
-H 'Content-Type: text/plain' \
--data-raw 'urn:ngsi-ld:Device:water001@on'
```
