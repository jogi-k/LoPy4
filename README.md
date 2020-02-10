# LoRaWan mit LoPy 4

## Update des Environments

* siehe : https://docs.pycom.io/pytrackpysense/installation/firmware/
* sudo pamac install dfu-util
* download pysense-software from above site
* Taste drücken , USB-Kabel stecken, 1 sek Tase loslassen
* innerhalb von ca 7 sek : ''' dfu-util -D pysense-0.0.8.dfu '''

## Zusammenbau

* Siehe : https://docs.pycom.io/gettingstarted/connection/lopy4/
* LoPy4-Module in den PySense stecken, Reset - Taster in Richtung USB-Connector
* Antenne anschliessen, je nach Frequenz !
* Firmware updaten , das ist die Firmware der eigentlichen Boards !
* Download von hier : 	https://software.pycom.io/downloads/linux-1.16.2.html

## Micro-Python

* VS-Code installieren
* pymakr Extension installieren
* Simple programme direkt in der REPL-Console eintippen 
    ''' pycom.rgbled(0xff00)    # make the LED light up in green color '''
*

## The Things Network

* Registrieren bei TTN 
    ** User
    ** Application
    ** Device
* Und hier sollte es weiter gehen...



