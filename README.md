# PRODUCTO-UNIDAD1
***PLACAS RASPBERRY, MICROBIT Y ARDUINO**



***OBJETIVO GENERAL:***
<p>Investigar los usos y estructuras principales de las tarjetas de desarrollo Raspberry Pi, Arduino y Micro Bit  por medio de la abstracción de información, para así poder conocer los componentes físicos que estos tienen, y el software que emplean.</p>

***OBJETIVOS ESPECÍFICOS***
<p><li> Identificar documentos recientes que tengan información acerca las tarjetas de desarrollo Raspberry Pi, Arduino y Micro Bit, para de esta manera conocer el objeto a investigar y las distintas aplicaciones en las que se encuentran. </li></p> 
<p><li> Comprender los usos y funcionalidades de las tarjetas. </li></p> 
<p><li>Desarrollar ejemplos básicos donde se evidencie el  funcionamiento de las tarjetas ya antes mencionadas. </li></p> 


***ESTADO DEL ARTE***
**Educación de alta calidad y bajo costo con la Raspberry Pi**
<p>Narasimha Saii Yamanoor, Srihari Yamanoor</p>
<p>En la investigación, lo que se busca es describir los componentes de una Single Board Computadora (SBC) como es Raspberry Pi,  a mas de informar que esta tiene mucha rentabilidad si lo que se busca es aprender, de este modo se puede estudiar informática,  programación, computación, entre otras ramas tecnológicas.</p>
<p>Cada vez la raspberry ha ido evolucionando y obteniendo ciertas mejoras, es así que la primera generación de esta computadora tenía una ranura para tarjeta SD para permitir la instalación y uso de una versión adecuada de Linux.  La segunda y tercera generación de computadoras, en cambio tienen una ranura para tarjeta MicroSD.</p> 
<p>En cuanto a su sus componentes del hardware, la computadora Raspberry Pi posee un diseño donde una sola placa transporta todos los circuitos esenciales, como la Unidad Central de Procesamiento (CPU), Unidad de procesamiento (GPU), y varias entradas, salidas y circuitos de procesamiento. La disponibilidad de funciones como los pines de entrada y salida de uso general (GPIO) hacen que la computadora sea apta para para conducir circuitos electrónicos y recopilar datos a través de diversos medios.Además se añaden accesorios como el sombrero (HAT), que no es otra cosa que “hardware que se coloca encima de la Pi”, este permite la adaptación del GPIO, o el uso de una placa de pruebas y  proporciona otras mejoras exclusivas que amplían la utilidad de Raspberry Pi Computer.</p>
<p>Con la Raspberry se pueden crear distintas aplicaciones a partir de esta pequeña computadora , las cuales van desde simples y didácticas hasta grandes aplicaciones. Raspberry ofrece varias posibilidades de creación. Es así que se convirtió en la tercera computadora más vendida en la historia.</p>

**Una comparación experimental de plataformas compatibles con Arduino IDE para aplicaciones de control digital y adquisición de datos**

<p>O. E. Amestica, P. E. Melin, C. R. Duran-Faundez and G. R. Lagos</p>
 <p>A partir del año 2005 empiezan a surgir  varias plataformas de desarrollo denominadas Hardware Libre, mismas que incluían un dispositivo microcontrolador,basado en un procesador de 8 bits, conocido inicialmente como ATmega168 y como ATmega328 en la actualidad, estos cuentan con un software de fácil desarrollo y uso para cualquier persona con conocimiento en lenguaje C, disponen de una gran cantidad de librerías y documentación. Todos estas características permitieron que una gran cantidad de personas pudieran integrar dispositivos embebidos en sus proyectos sin la necesidad de poseer conocimientos profundos en la utilización de sistemas embebidos o conocimiento en electrónica. Hoy en día es común que alumnos de pregrado, o incluso de enseñanza escolar, sepan utilizar estos dispositivos.</p>
<p>Por otra parte tenemos la plataforma de desarrollo Arduino IDE la cual ha tenido gran popularidad siendo por ello utilizada por otros dispositivos como: el nodeMCU y otras tarjetas de desarrollo para hardware libre que  se encuentran en el mercado. Este trabajo estudió diferentes plataformas digitales, las cuales se pueden programar utilizando el software Arduino IDE y que se pueden utilizar para aplicaciones de control digital y adquisición de datos. Es así que se evalúan tres tipos de placas Arduino (Arduino UNO, Arduino Mega y Arduino Due) y dos placas basadas en ESP (ESP 8622 y ESP32).Las tres placas Arduino UNO, Arduino Mega y Arduino Due son comúnmente conocidas como Arduinos, sin embargo, entre ellas existen diferencias importantes, por ejemplo los 8 bits de los procesadores de Arduino UNO y MEGA, frente a  los 32 bits de Arduino DUE .Aun así en los tres casos se conserva la disposición física de pines en la tarjeta.</p>
 <p>Además el estudio trata de responder a la siguiente interrogante: ¿cuál es la diferencia entre los tiempos de ejecución entre una tarjeta de desarrollo y otra? para esto la comparación se basa en el tiempo de ejecución de operaciones matemáticas y una función requerida para la adquisición de datos o el control digital e incluye: escritura de puertos digitales, adquisición de señal analógica, ejecución de operación matemática en formato entero y flotante y la ejecución del código de procesamiento de datos. Para realizar esto se valió de un método que consiste medir los tiempos de cada acción haciendo uso de  las puertas digitales de cada dispositivo utilizando un osciloscopio.</p>
<p>Tras varias pruebas se perciben pocas diferencias en los tiempos de ejecución de Arduino UNO y MEGA, cabe recalcar que ambos están basados en procesadores de 8 bits, obstante a esto se visualiza un mejor desempeño por parte de la tarjeta Arduino DUE la cual emplea un reloj más rápido y también  utiliza un procesador de 32 bits. Por otro lado, en dispositivos EPSxe, la tarjeta basada en ESP32 con un procesador de 32 bits y que utiliza 240 MHz, supera considerablemente en capacidades de procesamiento tanto a la ESP 8622 como a sus pares Arduino. </p>

<p>Fecha de la conferencia: 13-27 de noviembre de 2019</p>
<p>Lugar de la conferencia: Valparaíso, Chile, Chile</p>

<p>La presente investigación permite conocer de manera anticipada , que la plataforma Arduino IDE  es factible  de usar ya que se basa en el lenguaje C,  es así que los códigos desarrollados en el software de arduino pueden ser simplemente copiados en  la plataforma usada para la realización de los programas TinkerCad .Además en este estudio se evidencian los tiempos de ejecución de un arduino uno en la realización de operaciones matemáticas o en programas que incluyen números de punto flotante,por lo que así tendremos una noción muy básica  de cuanto tardará un programa en ejecutarse  ,al ser  comparado con otras placas de la familia arduino se establece que en el tiempo de ejecución es similar al arduino MEGA,sin embargo,el arduino DUE es mucho más rápido por lo que para ciertos proyectos es mucho más favorable utilizar este último. </p>






***MARCO TEÓRICO***









**ARDUINO**
**¿Qué es Arduino?**
<p>Arduino es una plataforma de desarrollo basada en una placa electrónica de hardware, una placa electrónica es una PCB (“Printed Circuit Board”, “Placa de Circuito Impreso” en español). Las PCBs superficies planas fabricadas en un material no conductor, la cual consta de distintas capas de material conductor. Una PCB es la forma más compacta y estable de construir un circuito electrónico.</p>






