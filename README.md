# node-red-bachelorproef
JSON code node-red
deze code moet geïmporteerd worden in node-red. dit zou 4 flows moeten weergeven: opstelling afhalen, vermogen metingen, webserver en KNX koppeling.
enkele templates moeten ook nog gedownload worden.
voor KNX is dit node-red-contrib-knx-easy.
tijdsinterval voor de vermogensmeters:node-red-contrib-interval-length.
voor influxdb:node-red-contrib-influxdb.
indien dit op een computer gebruikt wordt kunnen de pinnen bij vermogen niet gebruikt worden. dit kan gesimuleerd worden met een simpele inject die als payload "1" heeft.

voor de python code moet flask geïnstalleerd zijn op de raspberry pi. ook moeten er enkele settings van de Raspberry Pi zelf aangepast worden. deze settings zijn terug te vinden op de KIWIelectronics website onder extra informatie:https://www.kiwi-electronics.nl/Waterproof-DS18B20-Digital-temperature-sensor-plus-resistor.
