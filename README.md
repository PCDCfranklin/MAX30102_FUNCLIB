# MAX30102_FUNCLIB

Functional Arduino Library modified for use MAX30102 sensor. IPC17

You can find original library on https://github.com/MaximIntegratedRefDesTeam/RD117_ARDUINO 

Library was tested with ARDUINO IDE 1.8.4 and is enabled to work with MEGA, MICRO and UNO ARDUINO BOARD. If you want to work with another board, only add another IFCASE on SoftI2CMaster.h with I2C pinout of AVR controller that you can find on schematics or pin mapping of board.

#ifdef ARDUINO_AVR_XXXXXX(NAME OF BOARD UNO, MEGA, MICRO, ETC)
#define SDA_PORT PORTD
#define SDA_PIN 1
#define SCL_PORT PORTD  
#define SCL_PIN 0
#endif



Librería modificada funcional Arduino para el sensor MAX30102. IPC17

Puede encontrar la biblioteca original en https://github.com/MaximIntegratedRefDesTeam/RD117_ARDUINO

La biblioteca fue probada con ARDUINO IDE 1.8.4 y está habilitada para trabajar con ARDUINO MEGA, MICRO y UNO . Si desea trabajar con otra placa, sólo agregue otra IFCASE en SoftI2CMaster.h con el pinout I2C del controlador AVR que puede encontrar en los diagramas esquematicos o en la asignación de pines de la placa.

#ifdef ARDUINO_AVR_XXXXXX(NAME OF BOARD UNO, MEGA, MICRO, ETC)
#define SDA_PORT PORTD
#define SDA_PIN 1
#define SCL_PORT PORTD  
#define SCL_PIN 0
#endif
