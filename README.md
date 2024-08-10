 # Descripción
- El ADC tiene una resolución de 10 bits.
- Es de aproximaciones sucesivas.

![](https://cdn.sparkfun.com/assets/d/d/5/c/4/5114013ece395f527e000000.jpg)

# Instrucciones: Contestar las siguientes preguntas y enviar el archivo en PDF en TEAMS, donde vendrá una carpeta llamada INSTITUCIONAL, fecha límite jueves 8 de agosto antes de las 23:59.
# Sección 1
- ¿Cuántos puertos tiene el microcontrolador ATMEGA328P?
  
  TIene 3
- ¿Cuál es la diferencia entre el microcontrolador y la tarjeta de desarrollo Arduino?
  
  El microcontrolador es el circuito integrado que puede tener la memoria o cpu y la tarjeta
  arduino es la placa donde se pone el microcontrolador junto con otros componentes y
  tiene la ranura usb para implementarle programacion.
- ¿Cuántos volts entrega cada pin de los puertos?
     
  5V
- ¿Cuánta corriente entrega cada uno de los pines de los puertos del microcontrolador?
  
  La maxima coreiente que pueden entregar es de 40mA
- Se necesita conectar dos LEDs, para lo cual se van a utilizar los pines 0 (cero) y 7 (siete) del microcontrolador (PUERTO D), escribe el numero en binario y hexadecimal que se le tiene
que escribir al puerto para encenderlos.

  Binario: 10000001
  hexadecimal: 0x81
- ¿Qué es una localidad de memoria en el microcontrolador?
  
  Es el lugar especifico en la memoria del micro donde se puede guardar datos o acciones.
- ¿Cuál es la capacidad del microcontrolador para la memoria de programa?
  
  32kb
- ¿Cuál es la capacidad del microcontrolador para la memoria de datos?
  
  Es de 2KB (SRAM) y 1KB (EEPROM).
- ¿Cuál es la diferencia entre la arquitectura Harvard y Von Newmann?
  
  La arquitectura de Harvard separa la memoria del programa y de datos y la otra de Von
  utiliza un mismo espacio de memoria para los dos.
-¿De cuantos bits es el microcontrolador ATMEGA328P?

  8 bits
- ¿De cuantos bits es el ADC del microcontrolador?
  
  10 bits
# Sección 2
## Responde cierto o falso.
- Se requiere controlar un motor DC, para lo cual se debe conectar directamente el motor a
la tarjeta Arduino UNO para hacerlo funcionar.

  Respuesta: FALSO
- Necesito conectar un LED a la tarjeta Arduino UNO, ¿es necesario forzosamente poner una
resistencia a tierra?

  Respuesta: No, pero lo preferible es que si
- Describe los comandos del git flow básico para subir archivos al repositorio de GIT.
  
  Te ubicas en la carpeta donde este el archivo, pones el comando “git add (nombre del
  archivo), despues agregas el comentario: “git commit – m (comentario), y al ultimo: “git
  push origin master”.
  
# Sección 3
## Reflexiona y responde las siguientes preguntas.
- Que es una señal.
  
  Es algo que puede ser en voltake corriente o luz que varia en el tiempo y es fisica.
- ¿Sería posible procesar una señal sin recurrir al muestreo?

  No porque se ocupa convertir la senal analogica a digital para que puesa se procesada.
-¿Porque se debe muestrear una señal?

  Para convertirla de analogica a digital y que esta ya pueda ser procesada y capturar la
  informacion por una computadora o microcontrolador
¿Cómo relacionas el tamaño de paso del microcontrolador con los números binarios?
  Por la cantidad de tiempo y de datos que pueden se procesados o almacenados al mismo
  tiempo.
5. ¿Cuál crees que sea la diferencia entre lo análogo y lo digital?
Los valores analogos suelen ser infinitos y los digitales no y usan binario.
