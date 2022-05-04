# workshop 6
Brayan David Acosta Gomez
Valentina Osorio Lopez

## Identificación del modelo basico IOT
### Sensor 
El BME280 es un sensor digital combinado de humedad, presión y temperatura basado en pruebas principios sensoriales.
El BME280 logra un alto rendimiento en todas las aplicaciones que requieren humedad y presión medición. Estas aplicaciones emergentes de control domótico, navegación interior, fitness como así como el refinamiento del GPS requieren una alta precisión y un TCO bajo al mismo tiempo.
![enter image description here](https://tienda.bricogeek.com/6722-thickbox_default/sensor-de-temperatura-humedad-y-presion-bme280.jpg)

### Embedded System 

#### Hardware
Para el sistema iot básico que se utiliza en la simulación se evidencian ciertos componentes físicos necesarios para el desarrollo del ejercicio de lectura de humedad y presión por parte de un sensor. Dichos elementos constan de:

 - Raspberry pi
 - Protoboard
 - Sensor BME 280
 - Diodo Led
 - cables de conexión
#### Software
Una vez identificado el hardware que se está utilizando para la simulación, es necesario conocer el software utilizado y necesario para hacer la programación de los dispositivos físicos mencionados anteriormente y más impórtate, como recolectar los datos y enviarlos a un servicio externo para su manipulación. Dicho software es:
- lenguaje de programación Nodejs
- Librería wiring-pi (Manejo de pines Raspberry pi)
- Librería de conexión a azure IOT
- librería para el manejo del protocolo MQTT
- libreria bme280 (lectura del sensor)
- Plataforma cloud Azure

### Conectivity
### Data analytic

## Simulación del modelo
Para el proceso de simulación IOT, se hizo uso de la plataforma de simulación de raspberry pi que ofrece la nube de azure. Dicho simulador, está diseñado para capturar información de un sensor, enviarla hacia la plataforma de azue IOT y encender un actuador led dependiendo de las condiciones especificadas en el código.  

Para realizar este proceso fueron necesarios una serie de pasos para hacer la conexión y envio de datos entre el simulador y la plataforma de IOT.

 1. Crear un centro de IoT en Azure
 2. Registrar un nuevo dispositivo en el centro de IoT
 3. Ejecutar la aplicación de prueba con el simulador
 4. Lea los mensajes recibidos por el servicio

Una vez realizados los pasos pertinentes se obtuvo el siguiente resultado en el simulado.