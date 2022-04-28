# SmartPlug NKE + STM32 humidity sensor

## What does the device (STM32 humidity sensor) do ?
* The device is programmed to send humidity (%). 1-byte payload. 

## What does the Smart Plug do ?
* It measures the consumption in W and sends a report
(default: 0W for any power < 10W)
* It can receive commands: ON or OFF
* it sends status reports (ON/OFF status) after each received command

## What does the NodeRED dashboard offer ?
* A humidity chart (from STM32)
* A consumption chart (from Smart Plug)
* A ON/OFF button (to start/stop the Plug)
* A Plug Status analyzer (status: ON or OFF)

## Needed actions before use
* Setup the MQTT settings in the MQTT nodes
* Change (if needed) the function node to make them working for your own application 



