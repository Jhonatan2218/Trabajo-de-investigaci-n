# Trabajo-de-investigación
Tema: Explicar el funcionamiento de Collapse OS. La arquitectura del microprocesador z80 y simular ejemplos para z80.

1) PLANTEAMIENTO DEL PROBLEMA.

El sistema operativo Collapse OS es un peculiar proyecto de sistema operativo de código abierto concebido para usarlo en los momentos que la humanidad lo necesite, en un mundo postapocalíptico donde la era de la electrónica y tecnología que hoy conocemos ya no exista. El microprocesador Z80 de 8 bits será el encargado de ejecutar este sistema operativo, ya que son muy antiguos, se podrían encontrar masivamente en cualquier parte del mundo y otra característica importante es que tan solo cuenta con 9.000 transistores, por lo que sería mucho más sencillo de reprogramar que un procesador moderno con miles de millones de transistores. En la historia de la tecnología los microcontroladores poseen una gran importancia, ya que son usados para todo tipo de aplicaciones, computadoras, cajas registradoras, instrumentos musicales, calculadoras gráficas y centenares de productos electrónicos hasta aplicaciones mucho más avanzadas, y complejas, por lo tanto, aprender a utilizar correctamente estos dispositivos es importante para las personas en carreras técnicas. Una de las mayores dificultades a la hora de aprender a implementar estos dispositivos, no es como se podría pensar la construcción del circuito, sino aprender a programarlos.

Los microcontroladores se han constituido en un elemento primordial para el avance de las nuevas tecnologías, de ahí parte la necesidad de no solo conocerlos en sus usos también como emplearlos, la programación se convierte en algo apremiante de conocer, las herramientas con las cuales se pueda adquirir conocimiento son muy importantes.

2) OBJETIVOS

Objetivo General

Conocer el sistema operativo Collapse OS junto con la estructura del microprocesador Z80 y encontrar la relación entre ellos posteriormente realizar un ejemplo del microprocesador Z80

Objetivos Especificos

    •	Investigar el funcionamiento del sistema operativo Collapse O.S y como es que Funcionará con microprocesadores Z80 de 8 bits.
    •	Investigar la arquitectura del microprocesador Zilog Z80 para realizar algoritmos que nos permitan hacer simulaciones y comprender mejor su funcionamiento.
    •	Comprender y explicar el funcionamiento de Collapse Os.
    •	Conocer la arquitectura del microprocesador Z80.
    •	Simular ejemplos del z80.

3) ESTADO DEL ARTE

1.Collaspe OS

El investigador, desarrollador Virgil Dupras es creador de 'Collapse OS', un sistema operativo de código abierto que, afirma, está diseñado para funcionar en aquellos componentes electrónicos fáciles de reciclar. Es decir, es una plataforma que serviría para aprovechar la basura electrónica cuando ya no existan nuevos dispositivos electrónicos. Está pensado para ser usado en los momentos de un mundo postapocalíptico donde la tecnología ya no existe.

En el año 2019 se lanza el sistema operativo de código abierto diseñado para poder ejecutarlo desde cualquier dispositivo sin necesidad de ningún recurso externo. Se trata de un software, llamado Collapse OS, que tiene como objetivo suavizar las consecuencias tecnológicas de un posible colapso mundial que posiblemente llegue en el 2030. Collapse aún no ha sido terminado en su totalidad ya que su invertor (Virgil Dupras) ha decidido publicar su proyecto en la plataforma GitHub para que más desarrolladores que estén interesados en aportar con el desarrollo y las pruebas correspondientes.  Originalmente está pensado para que pueda funcionar en microprocesadores Z80, su creador ha programado tanto el núcleo del sistema operativo como algunos programas y herramientas. 


Un sistema operativo que, afirma, está diseñado para funcionar en aquellos componentes electrónicos fáciles de reciclar. Es decir, una plataforma que serviría para aprovechar la basura electrónica cuando ya no existan nuevos dispositivos electrónicos.
Así lo explicó Dupras a Vice: "Hago esto para mitigar un riesgo que creo que es real. No es inevitable, pero probablemente lo suficiente para justificar un esfuerzo modesto"(Virgil Dupras).


Microprocesador Z80


El Intel 8080, lanzado en 1974, fue el primer microprocesador de 8 bits que tuvo éxito entre la comunidad de programadores, teniendo como principal exponente al MITS Altair 8800. Dos años después y con la intención de hacerse con el mercado, Zilog lanzó el Z80, que atrajo a los programadores de la época al ser totalmente compatible con la arquitectura del Intel 8080 y añadir nuevas e interesantes funcionalidades, como un set de instrucciones extendido.
El Z80 tuvo tanto éxito que es posible encontrarlo en gran cantidad de máquinas de principios de los ochenta, como el Osborne 1, el ZX Spectrum o el Commodore 128. Podría decirse, por tanto, que el Zilog Z80 es una versión mejorada del Intel 8080.

Hoy en día, el Z80 se sigue utilizando, en una de sus últimas evoluciones (el Zilog eZ80) como microprocesador de algunas calculadoras gráficas y como microprocesador de algunos sistemas embebidos, lo cual da una idea de su versatilidad si tenemos en cuenta que se lanzó al mercado en 1976. 

El Z80 tenía ocho mejoras fundamentales 

    •	Un conjunto de instrucciones mejorado, incluyendo los nuevos registros índice IX e IY y las instrucciones necesarias para manejarlos.
    •	Dos bancos de registros que podían ser cambiados de forma rápida para acelerar la respuesta a interrupciones.
    •	Instrucciones de movimiento de bloques, E/S de bloques y búsqueda de bytes.
    •	Instrucciones de manipulación de bits.
    •	Un contador de direcciones para el refresco de la DRAM integrado, que en el 8080 tenía que ser proporcionado por el conjunto de circuitos de soporte.
    •	Alimentación única de 5 voltios.
    •	Necesidad de menos circuitos auxiliares, tanto para la generación de la señal de reloj como para el enlace con la memoria y la E/S.
    •	Más barato que el Intel 8080.
    •	Un tipo especial de reset que sólo reinicia el contador de programa de modo que el Z80 se puede usar en un sistema de desarrollo ICE


A fines de 1975, incluso antes de anunciar el Z80, Faggin tuvo claro que la compañía necesitaba un sucesor de 16 bits para el Z80. Sintió que los procesadores de 16 bits eran el futuro y que el futuro era inminente. En ese momento, Zilog tenía todos los 11 empleados. Sin embargo, Faggin no quería crear una versión ampliada de 16 bits del Z80, un "super Z80". Además, no se sentía calificado para desarrollar una nueva arquitectura de microprocesador de 16 bits a partir de todo el tejido, por lo que buscó un arquitecto de procesadores experto. Encontró al Dr. Peuto, que había estado trabajando en la arquitectura mainframe 470 / V6 compatible con IBM de Amdahl desde 1973. Peuto se convirtió rápidamente en el duodécimo empleado de Zilog. (Leibson, 2019).

4)MARCO TEORICO

Microprocesadores.

Intel Corporation.

Intel fue fundada el 18 de julio de 1968 como Integrated Electronics Corporation son los pioneros en semiconductores Robert Noyce y Gordon Moore, y muchas veces asociados con la dirección ejecutiva y la visión de Andrew Grove.
Pero Intel no siempre tuvo la visión de futuro acertada. Moore recuerda como a mediados de los 70 le propusieron comercializar el 8080 equipado con un teclado 37 y un monitor orientado al mercado doméstico. Es decir, le estaban proponiendo ser los pioneros en el mundo de las computadoras personales. Pero no vieron la utilidad de esos aparatos, y descartaron la idea.
(JOHN HANNER MARQUEZ ORTIZ, 2013)
En el año 1969, un equipo de ingenieros japoneses de la compañía BUSICOM llegó a Estados Unidos con una idea, ellos deseaban usar para sus proyectos pocos circuitos integrados de los que se usaban en las calculadoras. La proposición se hizo a INTEL (JOHN HANNER MARQUEZ ORTIZ, 2013). El Intel 4004 fue el primer microprocesador de la historia y, tras éste, Intel desarrolló otro procesador más del cual se encargó Federico Faggin, responsable del Intel 4004, al que se le encargó el desarrollo de un procesador de 8 bits, el Intel 8080 que también gozó de un gran éxito en el mercado.

Al finalizar este proyecto en 1974, Faggin pensó que era hora de volar en solitario y afrontar nuevos proyectos y decidió fundar su propia compañía, Zilog, en la que se desarrollaría otro mítico procesador: el Zilog Z80.

 Microprocesador Zilog Z80

Faggin decidió afrontar el desarrollo de un nuevo procesador que, desde el punto de vista práctico, fuese totalmente compatible con el Intel 8080 pero que, en prestaciones, fuese mejor.

Tras dos años de trabajo, en los que Faggin diseñó la arquitectura del procesador y supervisó la fabricación, el Zilog Z80 fue lanzado al mercado en julio de 1976.De ahí que el Intel 8080 tenga su parecido con el Z80, pero añadiendo nuevos registros y un juego de instrucciones ampliado para trabajar en ello, los registros del microprocesador permiten almacenar valores en memoria y realizar diferentes operaciones con ellos. Este microprocesador cuenta con registros de 8 bits, que pueden juntarse en grupos de dos para realizar operaciones de 16 bits, muy lejos de los 64 bits que utilizan los microprocesadores actuales.
Un año después sale al mercado el primer computador que hace uso del Z80, el Tandy TRS-80 Model 1 con un Z80 a 1,77 MHz y 4 KB de RAM. Acaba desplazando al 8080 del mercado por su menor precio y mayores prestaciones.

Fue muy popular durante los años 80 debido principalmente a dos razones: ser compatible con el Intel 8080 ya que fue el mismo Faggin quien lo diseño, y ser popularizado por varias videoconsolas (Amstrad CPC, Sinclair ZX Spectrum). Posteriormente ha sido utilizado por tras videoconsolas (Sega Master System, Nitendo Game Boy Advance y chip dedicado de audio en la Sega MegaDrive). 
Tras del Z80 Zilog introduce varios procesadores de 16 bits y 32 bits, pero sin mucho éxito, por lo que la compañía se orienta al mercado de microcontroladores, produciendo CPUs básicas y Circuitos Integrados para Aplicaciones Específicas (ASICs/ASSPs) construidos alrededor del núcleo de sus procesadores.

CARACTERÍSTICAS: 

•	El set de instrucciones contiene 158 instrucciones. Están incluidas las 78 instrucciones del 8080 y se mantiene la compatibilidad de software con el 8080. 

•	Reloj de 8, 6, 4 y 2.5 MHz. Para el Z80H, Z80B, Z80A y Z80 CPU, resultando una rápida ejecución de instrucciones con la consecuente transferencia elevada de datos. 

•	El extenso set de instrucciones incluye operaciones con palabras, bit, byte y cadena de caracteres. Búsqueda y transferencias de bloques a la vez mediante indexado y direccionamiento relativo, resultando el más competente y poderoso procesador de datos en la industria de los microcomputadores. 

•	El microprocesador Z80 y la familia asociada de periféricos controladores pueden ser enlazados por un sistema vectorizado de interrupciones. Este sistema podría ser DaisyChained que permita la implementación de un esquema de interrupciones prioritario, se requiere poca lógica adicional para el acoplamiento. 

•	Set duplicado de registros de banderas y de propósito general. 

•	Dos registros índices de 16 bits. 

•	Contador de refresco de memoria dinámica.

El Z80 resulta ser un microprocesador más rápido y sencillo en el desarrollo de sistemas ya que solo usa una fuente de alimentación de +5 Volts, contiene íntegramente todo el conjunto de instrucciones del 8080, lo cual le permite ejecutar todos los programas escritos para el CPU 8080, contiene el Z80 una expansión adicional de 80 instrucciones de ahí se deriva su nombre, su repertorio suma un totaL DE 158 Instrucciones. 


