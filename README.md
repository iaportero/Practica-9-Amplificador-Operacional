# Practica-9-Amplificador-Operacional
Integrantes: Bryan Santiago Torres Reyes , Roger Steveen Armas Simbaña , Israel Alejandro Portero Cazares

NRC: 4877

1. Objetivo

Objetivo general

*  Analizar y comparar las diferentes  señales senoidales  generadas por un amplificador operacional basico.

Objetivo  especifico

*  Verificar el principio de funcionamiento de un amplificador operacional.

*  Analizar algunas aplicaciones básicas con el amplificador operacional.

2.Marco Teorico /  Diagramas

AMPLIFICADOR OPERACIONAL

Un amplificador operacional (también conocido como OPAMP) es un circuito integrado que permite realizar una gran variedad de circuitos electrónicos útiles. Desde un comparador de voltaje, un amplificador de señal, hacer operaciones aritméticas y filtrar señales. Los amplificadores operacionales están compuestos por una gran cantidad de transistores internamente, que permiten controlar corrientes y tensiones, para darle sus características eléctricas.


![](https://github.com/iaportero/Practica-9-Amplificador-Operacional/blob/main/Imagenes/ima%201.png)


![](https://github.com/iaportero/Practica-9-Amplificador-Operacional/blob/main/Imagenes/ima%202.png)


3. Lista de componentes


![](https://github.com/iaportero/Practica-9-Amplificador-Operacional/blob/main/Imagenes/ima%203.png)

4. Explicacion

1.- Construya en el protoboard cada uno de los circuitos de la figura 1. Muestre
simultáneamente las señales de entrada y salida en un osciloscopio. Capture las formas de onda.

2.- Determine y analice la relación entre las señales de entrada y salida en cada uno de los
circuitos indicados en la figura 1.

3.- En todos los casos emplee un amplificados LM741.

![](https://github.com/iaportero/Practica-9-Amplificador-Operacional/blob/main/Imagenes/ima%204.png)


4.1  Análisis de resultados


1.- Analice y compare las formas de onda obtenidas en la práctica con los resultados obtenidos
en el trabajo preparatorio. Comente dicha comparación.

![](https://github.com/iaportero/Practica-9-Amplificador-Operacional/blob/main/Imagenes/ima%205.png)

![](https://github.com/iaportero/Practica-9-Amplificador-Operacional/blob/main/Imagenes/ima%206.png)

Analisis:

Las ondas tanto de salida como las de entrada son senoidales en los dos casos, y se pueden observar
que están amplificadas analizando las señales de salida y entrada, se puede destacar que utilizamos
un amplificador operacional sirve para aumentar una señal de entrada, por ejemplo, la señal de
voltaje que tiene un micrófono para que salga por un altavoz

![](https://github.com/iaportero/Practica-9-Amplificador-Operacional/blob/main/Imagenes/ima%207.png)

![](https://github.com/iaportero/Practica-9-Amplificador-Operacional/blob/main/Imagenes/ima%208.png)

Analisis:

Las ondas de salida y de entrada, al ser simuladas en los dos casos poseen cierta inclinación que
puede ser interpretada como una onda triangular no formada, ya que los capacitores poseen 1uF.
Gracias a estas ondas se pudimos darnos cuenta que el amplificador utilizado es un integrador
inversor, ya que ingresando una onda tipo cuadrada obtenemos una onda tipo cuadrada mismo, pero
con cierto desfase


![](https://github.com/iaportero/Practica-9-Amplificador-Operacional/blob/main/Imagenes/ima%209.png)

Analisis:

En el circuito se pueden observar que ambas ondas son senoidales. La obtención de estas ondas nos
permite identificar que el amplificador es sumador inversor. Este amplificador permite añadir
algebraicamente dos (o más) señales o voltajes para formar la suma de dichas señales en este caso
en la señal de salida.


4.2 Preguntas 

1. Anote parámetros técnicos importantes de un amplificador operacional que deben ser
tomados en cuenta al momento de utilizarlos en un proyecto.

Tensión de alimentación (V+ y V-):

Es la tensión de alimentación máxima permitida que puede aplicarse con seguridad al amplificador.
Aunque se designa como estándar 15 V de alimentación, la mayoría de los AO integrados operan
sobre un amplio rango de potenciales, algunos van desde valores tan bajos como 1 V, y otros hasta
40 V

Rango de Temperatura de operación (Tor):

Es el rango de temperatura dentro del cual el dispositivo funcionar con las especificaciones
mostradas.


Tensión de entrada diferencial (Vid):

Es la tensión máxima que puede aplicarse con seguridad entre los terminales de entrada diferencial
sin flujo excesivo de corriente. Estos valores son variables, los AO con entrada cascodo pn p/n pn
soportan hasta 30 V, similares a los AO con entrada FET.


Voltaje de entrada en modo común (Vcm):

Es el rango de voltaje que se puede aplicar en ambas entradas respecto a tierra

Consumo de potencia (Pc):

Es la potencia requerida para operar el AO o la potencia consumida por el AO con propósitos de
polarización. Se especifica para 15 V.

Disipación de potencia (PD):

Es la potencia que un dispositivo particular es capaz de disipar con seguridad en forma continua
mientras opera dentro de un rango de temperatura específico. Esta característica varía de acuerdo al
tipo de encapsulado. Por ejemplo, los encapsulados cerámicos permiten una alta disipación de
potencia, los metálicos permiten la siguiente más alta disipación, en cambio los de plásticos tienen
la más baja. Un valor típico es de 500 mW


2. Investigue las características de amplificadores operacionales distintos a los utilizados
en esta práctica

Amplificador Operacional No Inversor;

Este circuito es muy parecido al inversor, la diferencia es que la señal se introduce
por el terminal no inversor, lo cual va a significar que la señal de salida estará en fase con la
señal de entrada y amplificada. El análisis matemático será igual que en el montaje
inversor. la ganancia de éste amplificador no puede ser menor que 1. la corriente de
entrada al operacional es cero, por lo tanto I1 es igual a I2. tiene una ganancia en tensión
Av = 1 + R1 / R2 . Esto quiere decir que la salida será Av veces la entrada, sin invertirse la
señal ya que Av es positiva.

Amplificador Operacional Diferencial;

Este dispositivo nos permite obtener la derivada de la señal de entrada. En el caso
general la tensión de entrada variará con el tiempo Vi= Vi(t). La principal diferencia que se
observa en este circuito es la presencia de un condensador de capacidad constante C. Como
se sabe la carga Q que almacena un condensador es proporcional a su capacidad C y a la
diferencia de potencial V a la que estén sometidos las armaduras de éste (Q=CV). Es fácil
entender que si la tensión varía con el tiempo y la capacidad del condensador es constante,
la carga que éste almacena también variará con el tiempo, Q= Q(t).
Amplificador Sumador No inversor;
Tiene múltiples entradas en el pin no inversor. Al igual que en un sumador inversor
cada entrada tiene su propia impedancia de entrada que esta por el orden de 100 Mega
Ohmios o más y solo hay una impedancia de salida que esta por el orden de mili Ohmios o
menos.

Amplificador Operacional Seguidor de Voltaje;

Este amplificador hace que la salida siga a la entrada, es decir el voltaje de salida es
el mismo voltaje de entrada. Al presentar una alta impedancia de entrada (por el orden de
Megas de Ohm o más), se garantiza una baja potencia de entrada, que a su vez garantiza
que la señal de entrada no se distorsionara al conectarse al pin no inversor, y además que la
señal de entrada quedara en su totalidad en la impedancia de entrada. Al presentar una muy
baja impedancia de salida (por el orden de milis de Ohm) se garantiza que haya una
transferencia total de potencia a la RL de salida. Por esta razón al Opamp seguidor también
se le conoce como buffer y se usa para acoplar impedancias.

3. Investigue otras aplicaciones con circuitos más complejos que utilizan amplificadores
operacionales.


Amplificador de instrumentación;

Este es un amplificador diferencial que consta de dos etapas, una etapa de entrada formada por dos
amplificadores inversores, y una etapa de salida que es un amplificador diferencial. Resuelve todos
los inconvenientes que se presenta en el amplificador diferencial.


![](https://github.com/iaportero/Practica-9-Amplificador-Operacional/blob/main/Imagenes/ima%2010.png)


5.Manual de usuario simulador Multisim

http://electronica.ugr.es/~amroldan/asignaturas/curso04-05/ftc/pdf/manual.pdf

http://blogmultisim.blogspot.com/2012/11/como-instalar-multisim-12-en-espanol.html

6. Descripcion de prerrequsitos y configuracion

Paso 1 : Instalar Multisim

Primero que nada es necesario contar con una instalación previa de Multisim, si no cuentas con una licencia puedes descargar una evaluación por 30 dias

Paso 2. Descargar los archivos de soporte.

Visita NI Labs y descarga los archivos necesarios para instalar el idioma Español

Paso 3. Descomprime el archivo y cópialo al directorio de instalación.

Descomprime el archivo multisim_espanol_12.zip, el resultado será una carpeta de nombre Spanish:

Paso 4. Revisa el directorio de instalación.

Copia la carpeta Spanish y localiza el siguiente directorio en tu PC:

Paso 5. Selecciona el idioma Español en Multisim.

Abre Multisim, selecciona el menú Options»Global preferences. Después ve a la pestaña General y localiza el campo de Language. En la lista desplegable selecciona Spanish


7. Conclusiones

*  Las ondas tanto de salida como las de entrada de la figura 4 muestran ondas senoidales en los dos casos, y se pueden observar
que están amplificadas analizando las señales de salida y entrada, se puede destacar que utilizamos
un amplificador operacional sirve para aumentar una señal de entrada

*  Las ondas de salida y de entrada de la figura 7  al ser simuladas en los dos casos poseen cierta inclinación que
puede ser interpretada como una onda triangular no formada, ya que los capacitores poseen 1uF

*  En la figura 11  se pueden observar que ambas ondas son senoidales. La obtención de estas ondas nos
permite identificar que el amplificador es sumador inversor. Este amplificador permite añadir
algebraicamente dos (o más) señales o voltajes para formar la suma de dichas señales en este caso
en la señal de salida

Bibliografia 

Boylestad, R. (2010). Análisis de circuitos eléctricos. México: Prentice Hall.


García, M. F. (2015). Recurso TIC para el área de Física y Química. Recuperado  : 31-3-2021  de El circuito eléctrico:
http://www.quimicaweb.net/grupo_trabajo_fyq3/tema8/index8.htm


Tecnológica, Á. (2017). Amperímetro. Recuperado 1-04-2021 . de
http://www.areatecnologia.com/electricidad/amperimetro.html



9. Anexos 

Link del video

https://youtu.be/22qwpg_AbfE


Link de archivos generados

https://github.com/iaportero/Practica-9-Amplificador-Operacional/blob/main/Codigo%20Fuente/Guia9F.pdf




