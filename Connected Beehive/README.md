# Connected beehive dashboard

## How to use it ?
* Download the .json file
* Open your NodeRED application
* Click on Import button
* Choose the .json file previously downloaded

## Nodes to setup before use
* Setup "MQTTin" node according to your MQTT brocker settings.
* Setup the "Influxdb (Write)" and "Influxdb (read)" nodes with your own InfluxDb database settings.
* Setup the "Time scale" nodes with the influxdb query that fits your database configuration.
* The "Query result handling" nodes shape the data into a readable array for nodeRED chart. Change them if needed.

## WARNING
* In order to ensure a proper display of graphics, it is highly recommended to limit the number of point a nodeRED chart has to display. A maximum of ~1000 points seems reasonable.
