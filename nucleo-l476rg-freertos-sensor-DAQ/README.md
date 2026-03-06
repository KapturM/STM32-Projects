# FreeRTOS Sensor DAQ and CLI
*PROJECT WORK IN PROGRESS*

## TO DO LIST
[x] Setup and install freeRTOS\
[x] Setup a simple Blink Task\
[x] Add [freeRTOS_PLUS_CLI](https://www.freertos.org/Documentation/03-Libraries/02-FreeRTOS-plus/03-FreeRTOS-plus-CLI/01-FreeRTOS-plus-CLI)\
[x] Add and test a simple command
[] Implement linux console style communication\
    &nbsp;&nbsp;&nbsp;&nbsp;[x] Echo a sent character\
    &nbsp;&nbsp;&nbsp;&nbsp;[x] Echo a new line\
    &nbsp;&nbsp;&nbsp;&nbsp;[x] Add a symbol to the left like '$ some_command' in Linux\
    &nbsp;&nbsp;&nbsp;&nbsp;[] Handle buffer overflow

[] Add and modify my BME280 driver\
    &nbsp;&nbsp;&nbsp;&nbsp;[] Create task for data gathering

[] Add MPU6050 Sensor Support\
    &nbsp;&nbsp;&nbsp;&nbsp;[] Create I2C driver\
    &nbsp;&nbsp;&nbsp;&nbsp;[] Task


## *README WORK IN PROGRESS*

1. 
Include .c and .h files in Core
FreeRTOS_CLI

2. 
modify FreeRTOSConfig.h
```
#define configCOMMAND_INT_MAX_OUTPUT_SIZE 500
```


# References
FreeRTOS+CLI - https://www.freertos.org/Documentation/03-Libraries/02-FreeRTOS-plus/03-FreeRTOS-plus-CLI/01-FreeRTOS-plus-CLI