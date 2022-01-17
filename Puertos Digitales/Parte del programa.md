### Arduino

- Definicion de Arduino:

Es una aplicación  que permite programar diversas placas de desarrollo Arduino: Arduino UNO, Arduino MEGA, Arduino DUO, además, este software tiene plugins (módulos adicionales) que permiten programar otro tipo de placas de desarrollo. 

![Image text](https://www.ticarte.com/sites/su/styles/large/public/users/380/teaser/arduino-logosvg.png?itok=OemPVURn)

### Partes de Arduino 

![Image text](https://aprendiendoarduino.files.wordpress.com/2015/03/instalacion6.png?w=625&h=526)

1.	Barra de Navegación=> Permite al usuario acceder a Programas.
2.	Cuadro de Trabajo=>	Donde programa Arduino.
3.	Cuadro de Compilación=>	Proceso de compilación y ubicación del archivo .hex
4.	Barra de acceso=>	Permite compilar y cargar el código.
5.	Barra de Ubicación=>	Tipo de Arduino conectado y el puerto de comunicación.

### Bibliotecas de Arduino


* pinMode() 

Al hacer una llama a la rutina pinMode se le deja saber a Arduino si una terminal será utilizada como entrada o salida.

Sintaxis: pinMode(pin, MODO) 

MODO: INPUT o OUTPUT.

* digitalWrite() 

Una vez que se a especificado que una terminal de Arduino será utilizada como salida, se usa esta función para escribir un valor digital alto o bajo a dicha terminal.

 Sintaxis: digitalWrite(pin, ESTADO) 

ESTADO: HIGH o LOW.

* delay()

 Rutina de retardo universal, detiene el flujo de ejecución del sketch actual. 

Sintaxis: delay(ms) 

ms: numero de milisegundos a esperar. (1000 ms = 1 ).


* digitalRead() 

Después de especificar que una terminal se usará como entrada, se emplea esta función para leer un valor digital alto o bajo presente en dicha terminal. 

Sintaxis: digitalRead(pin)                                 pin -> Número de terminal a leer

* pullUP pullDown

Se consideran entradas digitales en el momento que nosotros recibimos 0 lógico o 1 lógico del exterior, sea desde un sensor, un switch, un botón, etc. 0 lógico : 0 voltios y 1,8 voltios 1 lógico: 2,1 voltios y 5 voltios


![Image text](https://www.arduino.cc/en/uploads/Guide/mkrfox_board.jpg)