# LoRaWAN Clock Synchronization dashboard

## How to use it ?
* Download the .json file
* Open your NodeRED application
* Click on Import button
* Choose the .json file previously downloaded

## Needed modifications berfore use
- Add YOUR MQTT broker settings in the MQTT nodes.
- Set YOUR topic (to publish on) in the "JSON downlink setup" node.
- Set YOUR topic (to subscribe to) in the "Topic to subscribe" node.
- In the function nodes, there is JS code. Pay attention to the lines with the ** //!\\ ** symbol.

## In order to use this tool effectively...
- ... check the video demonstrations. Available here: [https://www.youtube.com/watch?v=i_WMjN9jRvk]
- ... check the **_LoRaWAN Advanced Features_** book. Available here: [https://www.univ-smb.fr/lorawan/en/free-book/]
