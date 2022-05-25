# homeassistant-config



#### Hardware

| DEVICE    |                 USO               | COMENTARIO                                                                                          |
|----------------------------------------------------------------------------------------------------------------------------------------------------------------------|:-------------------------------------------------------------------------------------------------------------------------:|------------------------------------------------------------------------------------------------|
| Thinkpad T420 i3-2350M / 6GB RAM   / 120GB SAMSUNG SSD 830 Series | Proxmox 7.0.2   | Rescatado de la Basura AC/RA |
| Cisco AP 1601 | WIFI AP 5 y 2.4 | configuracion Autonoma |
| Ubiquit 8GX POE | Network POE | Regalo |
| WIFI: SONOFF BASIC | Baño | ESPHOME |
| WIFI: SONOFF BASIC | Bodega | ESPHOME |
| WIFI: SONOFF T1         | Dormitorio Pato | ESPHOME |
| WIFI: SONOFF T1         | Dormitorio Principal | ESPHOME |
| WIFI: SONOFF BRIDGE 433 RF | LIVING | TASMOTA |
| WIFI: Agua PCHAN | LIVING | TUYALOCAL , dispensador de Agua PCHAN |
| WIFI: Dispensador Comida PCHAN | LIVING | TUYALOCAL |
| ZIGBEE: OZOM E27 | Cocina | Z2M |
| ZIGBEE: Aqara Presencia | Cocina | Z2M |
| ZIGBEE: Sonoff Presencia | Cocina | Z2M |
| ZIGBEE: Aqara Presencia | Baño | Z2M |
| ZIGBEE: Aqara Presencia | Dormitorio Principal | Z2M , no lo uso realmente|
| ZIGBEE: Aqara Presencia | Living | Z2M |
| ZIGBEE: Aqare Presencia | Bodega | Z2M |
| ZIGBEE: Aqara Contact   | Ventanal Living | Z2M |
| ZIGBEE: OZOM Contac     | Puerta Entrada | Z2M |
| ZIGBEE: Xiaomi Button Switch | Dormitorio Pato | encendido T1 Dormitorio Pato |
| ZIGBEE: Aqara Sensor Temp/HUM | BODEGA | Saber humedad PLA |
| RF: BOTONERA | Dormitorio Principal | Encendido SONOFF T1 Dormitorio |

#### HARDWARE NO INTEGRADO
* Robot Aspirador Xiaomi
* Google home
* Alexa

#### AUTOMATIZACIONES

* Encendido/Apagado Luz Cocina mediante un grupo de sensores de presencia, al tener un aqara que reporta estado cada 120 Segundos y un sonoff cada 60 segundos, casi no existen falsos positivos
* Encendido/Apagado Luz Baño
* Encendico Apagado Luz Bodega

###### OZOM

Es una Marca de Dispotivos de Domotica que son vendidos en chile y algunos paises de latino america, algunos de sus dispotivos son soportados ( zigbee ) por smarthings y Zigbee2mqtt y por su puesto por su Ozom Box.

Por Suerte Tengo Muchas dispotivos Ozom.... Luces Gu10 E27 Enchufes / Sensores de Humo / Sensores de CO2

