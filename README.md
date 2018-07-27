# MAX30102_FUNCLIB
ENG:


Functional Arduino Library modified for use MAX30102 sensor. IPC17

You can find original library on https://github.com/MaximIntegratedRefDesTeam/RD117_ARDUINO 

Library was tested with ARDUINO IDE 1.8.4 and is enabled to work with MEGA, MICRO and UNO ARDUINO BOARD. If you want to work with another board, only add another IFCASE on SoftI2CMaster.h with I2C pinout of AVR controller that you can find on schematics or pin mapping of board.

#ifdef ARDUINO_AVR_XXXXXX(NAME OF BOARD UNO, MEGA, MICRO, ETC)
#define SDA_PORT PORTD
#define SDA_PIN 1
#define SCL_PORT PORTD  
#define SCL_PIN 0
#endif

Steps to install library:
1) Download library as ZIP file
2) Unzip ZIP file content on arduino/libraries folder
3) Restart Arduino IDE
4) Find it on examples MAX30102_FUNCIONAL

ESP:

Librería modificada funcional Arduino para el sensor MAX30102. IPC17

Puede encontrar la biblioteca original en https://github.com/MaximIntegratedRefDesTeam/RD117_ARDUINO

La biblioteca fue probada con ARDUINO IDE 1.8.4 y está habilitada para trabajar con ARDUINO MEGA, MICRO y UNO . Si desea trabajar con otra placa, sólo agregue otra IFCASE en SoftI2CMaster.h con el pinout I2C del controlador AVR que puede encontrar en los diagramas esquematicos o en la asignación de pines de la placa.

#ifdef ARDUINO_AVR_XXXXXX(NAME OF BOARD UNO, MEGA, MICRO, ETC)
#define SDA_PORT PORTD
#define SDA_PIN 1
#define SCL_PORT PORTD  
#define SCL_PIN 0
#endif

Pasos para instalar la libreria:
1) Descargar la biblioteca como archivo ZIP
2) Descomprima el contenido del archivo ZIP en la carpeta arduino/libraries
3) Reiniciar Arduino IDE
4) Encuéntrelo en ejemplos MAX30102_FUNCIONAL
