# esp8266 and RGB WS2812, WS2811 (Arduino)

- U1 	1 	ESP8266 (beta) 	ESP8266
- R2 	1 	Resistor Resist the flow of electrical energy in a circuit, changing the voltage and current as a result. 	0617/17 	1 kohm
- P1 	1 	Power Supply This is the component used to represent the power supply in the Electronics Workbench (the breadboard simulator). There are multiple footprints so if you are designing a PCB be sure to choose which footprint works best for your design. 	Power Header 0.1" through hole 2 	12 , 5
- U2 	1 	3.3V Regulator [LD1117V33] 	TO220
- LED1 	1 	NeoPixel 	WS2812, WS2811 breadboard

## Build Upload spiffs
```
platformio run --target buildfs && platformio run --target uploadfs
```

##Схемы

###breadboard

![alt](https://raw.githubusercontent.com/renat2985/rgb/master/tutorial/breadboard.gif)

###schematic
![alt](https://raw.githubusercontent.com/renat2985/rgb/master/tutorial/schematic.gif)
![](https://easyeda.com/normal/esp8266_WS2811b-892ba108698e4d12ae6df39420fb124a)
## Bugs
- captive
- список сетей
- после после подключения нет информации о полученном ip
  не понятно подключился?
- установить пароль на wifi ap
- Время?

## TODO

## Done
+ нарисовал схему в EASYEDA
+ не подключается с паролем в котором (-)
