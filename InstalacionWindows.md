## Instalación de Windows
Es fundamental evaluar los componentes del equipo al que se le va a instalar el sistema operativo, para así poder usar la versión más adecuada al ordenador o en su defecto, que la versión que deseemos instalar esté acorde a los requerimientos.
Por lo tanto vamos a ver los requerimientos de los SO más comunes en la actualidad de Windows:

***
### Requisitos de Windows 7:

-	Procesador de 1 gigahercio (GHz) o más rápido de 32 bits (x86) o de 64 bits (x64)*
-	1 GB de RAM (32 bits) o 2 GB de RAM (64 bits)
-	16 GB de espacio disponible en el disco duro (32 bits) o 20 GB (64 bits)
-	Tarjeta gráfica DirectX 9 con controlador WDDM 1.0 o superior
  Requisitos adicionales para usar algunas características:
- Acceso a Internet (pueden aplicarse tarifas adicionales)
-	Según la resolución, la reproducción de vídeo podría requerir memoria adicional y hardware gráfico avanzado
-	Algunos juegos y programas pueden requerir una tarjeta gráfica compatible con DirectX 10 o versiones posteriores para obtener un rendimiento óptimo
-	Algunas funciones de Windows Media Center pueden requerir un sintonizador de TV y hardware adicional.
-	Los equipos Windows Touch y Tablet PC requieren hardware específico
-	Grupo hogar requiere una red y equipos PC conWindows 7 
-	La creación de DVDs o CDs requiere una unidad óptica compatible
-	BitLocker requiere Módulo de plataforma segura (TPM) 1.2
-	BitLocker To Go requiere una unidad flash USB
-	Windows XP Mode requiere un 1 GB de RAM adicional y 15 GB adicionales de espacio en disco duro disponible.
-	La música y el sonido requieren salida de audio

***

### Requisitos de Windows 8: 

Con carácter general, cualquier equipo capaz de ejecutar Windows Vista puede ejecutar Windows 8.
-	Procesador: Intel o AMD de 1 GHz o superior y compatibilidad PAE, NX y SSE2. Microsoft brinda una herramienta en línea de comandos denominada Coreinfo que os puede ayudar a determinar si vuestro procesador es compatible con Windows 8.
-	Memoria: 1 GB de RAM para arquitecturas de 32 bits y 2 GB de RAM para las de 64 bits.
-	Espacio libre en el disco duro: 16 GB para la edición de 32 bits y 20 GB para la de 64 bits.
-	Resolución de la pantalla: 1024x768 píxel para ejecutar aplicaciones Modern UI y 1366x768 píxel para visualizar dos aplicaciones Modern UI de forma simultánea.
-	Hardware gráfico: compatible con controlador WDDM y Direct X versión 9.
-	Para arranque seguro se necesita un firmware compatible con UEFI v2.3.1 Errata B
-	Conexión a Internet para determinadas funciones, como las cuentas en línea.

***

### Requisitos de Windows 10:

Los requisitos mínimos para poder instalar y ejecutar sin problemas Windows 10 eran, en sus primeras versiones, los mismos que Windows 7:
-	Procesador 1 GHz.
-	1 GB de memoria RAM para 32 bits, o 2 GB de memoria RAM para 64 bits.
-	16 GB de espacio en el disco duro para 32 bits y 20 GB de espacio para la versión de 64 bits.
-	Tarjeta gráfica compatible con DirectX 9.0.
-	Pantalla con resolución mínima de 800×600.

Sin embargo, desde la versión 2004 del sistema operativo (lanzada en primavera de 2020), Microsoft aumentó algunos de estos requisitos para garantizar que el SO funcionaba mejor en todo tipo de PCs. En concreto, se aumentó hasta los 32 GB el espacio disponible en el disco duro o SSD para instalar la versión de 64 bits.
**Basaremos el proceso de instalación en el sistema operativo de Windows 10.**
Podemos escoger entre las siguientes versiones del sistema operativo:
- Home: Es la edición estándar, pensada para todos aquellos usuarios que, sin necesidades especiales, vayan a usar el PC en casa. Es más barata y cuenta con todo lo necesario para trabajar en el día a día y jugar.
- Pro: La edición más completa pensada para entornos domésticos. Esta edición es más cara y está pensada para aquellos que van a usar el ordenador tanto para uso personal como para uso profesional. Tiene todas las funciones de la edición Home, además de otras herramientas avanzadas como Bitlocker, para el cifrado de discos, Windows Information Protection y el cliente de Escritorio Remoto para conectarnos a otros PCs.
- Enterprise / Education Workstation: Estas son las ediciones pensadas para entornos de trabajo y entornos educativos. No solo son más caras que las dos anteriores, sino que solo se pueden comprar por lotes, y no están pensadas para usarlas en casa.
También podemos encontrar otro tipo de conceptos que nos pueden llamar la atención, como:
-	S. Un modo especial de seguridad y rendimiento en el que solo se permite la instalación de programas de la Microsoft Store.
-	N/KN. Ediciones destinadas especialmente para la Unión Europea, Suiza y Corea del Sur donde no se incluyen algunos programas de Microsoft, como Windows Media Player o la app de Cámara.
-	LTSC. Versiones para empresa de soporte extendido. Eliminan aplicaciones que se instalan por defecto, y reciben actualizaciones durante mucho más tiempo que las versiones estándar.

#### Proceso de instalación:
Si tenemos instalado en nuestro ordenador Windows 7 o Windows 8.1, podemos actualizar al nuevo Windows 10 sin perder los datos y los programas instalados en nuestro ordenador a través de Windows Update. Sin embargo, el proceso de actualización no siempre sale bien y, en ocasiones, puede dejarnos el ordenador inservible e incluso hacer que nuestro Windows no funcione como es debido.
**Por ello, siempre es recomendable realizar una instalación limpia, desde cero.**

#### Descargando Windows 10 y creando el USB:
Para instalar Windows 10 desde cero, lo primero que debemos hacer es descargar Windows 10. Microsoft nos permitirá descargar directamente desde sus servidores una imagen ISO de la última versión del sistema operativo.
Una vez descargada la imagen ISO de Windows 10, el siguiente paso será grabarla a un DVD o a una memoria USB. Para grabarla a un DVD, lo único que haremos será introducir el disco vacío en nuestro ordenador y pulsaremos sobre la imagen ISO de Windows 10 con el botón derecho para elegir la opción de grabar imagen.
Microsoft también nos da la opción de descargar y grabar a un DVD directamente la imagen con la herramienta Media Creation Tool. Esta aplicación es gratuita y podemos descargarla desde la página web de Microsoft pulsando sobre **«Descargar ahora la herramienta«**.

1.	Aceptamos los términos de licencia y continuamos. El programa se preparará para la creación del medio de instalación.
2.	Tras unos segundos, el programa nos preguntará qué queremos hacer, si actualizar nuestro equipo (si no tenemos la última versión de Windows 10 instalada) o crear un medio de instalación para otro equipo. En nuestro caso seleccionamos esta segunda opción para continuar.
3.	En el siguiente paso podemos personalizar el medio de instalación de nuestro Windows. Podemos, por ejemplo, cambiar el idioma, la edición o la arquitectura del Windows que vamos a instalar. Por defecto nos cargará la configuración actual de nuestro sistema.

4.	En el siguiente paso podemos personalizar el medio de instalación de nuestro Windows. Podemos, por ejemplo, cambiar el idioma, la edición o la arquitectura del Windows que vamos a instalar. Por defecto nos cargará la configuración actual de nuestro sistema.
5.	Continuamos con el asistente y, en el siguiente paso, nos preguntará qué tipo de medio vamos a usar. Desde aquí podemos también descargar la ISO, igual que hemos visto antes, desde los servidores de Microsoft o crear una unidad Flash USB para instalar Windows 10 desde ella.
6.	Seleccionamos esta primera opción y pulsamos Siguiente para continuar. En el siguiente paso, el asistente buscará las unidades USB conectadas a nuestro ordenador y nos las mostrará en la lista. Elegiremos la que corresponda a la memoria USB donde copiaremos Windows 10 (con cuidado, ya que el proceso borrará todos los datos ya existentes) y pulsaremos sobre «Siguiente» para comenzar con el proceso.
7.	El asistente descargará la última versión de Windows 10 desde los servidores de Microsoft y la copiará a la memoria USB escogida para convertirla en una memoria de instalación. Este proceso puede tardar varios minutos, por lo que esperamos con calma a que finalice.
8.	Una vez finalice todo el proceso, ya tendremos nuestra memoria USB lista para poder instalar Windows 10 desde ella en nuestro ordenador. La extraemos del ordenador y nos preparamos para continuar.

#### Preparar el PC y configurar la BIOS
Una vez que ya tenemos la memoria USB con Windows 10 instalada en nuestro ordenador, el siguiente paso será preparar el ordenador para arrancar desde ella. Cada placa base y cada modelo de ordenador es un mundo, por lo que no hay una forma universal de hacerlo.
Para entrar la BIOS o UEFI de un ordenador lo que debemos hacer es encenderlo y, durante el arranque, pulsar las teclas F para poder entrar a este menú. También puede ser que nuestro PC entre a este menú con la tecla SUPR, depende de modelos.
Una vez dentro, debemos buscar el apartado de boot y asegurarnos de que la memoria USB con Windows 10 está configurada como arranque principal.
Ya que estamos en la BIOS y vamos a instalar Windows 10 desde cero, podemos aprovechar y activar el Secure Boot y asegurarnos de que está configurado el PC en modo UEFI. De esta manera podremos aprovechar al máximo el PC y asegurarnos de que todo nuestro PC se ejecuta de forma segura. Este paso no es obligatorio (ya que Windows 10 funciona bien en modo Legacy Bios), pero es recomendable para tener mayor seguridad, menos problemas al actualizar, y poder dar el salto a Windows 11.
Estas opciones no se pueden (o, mejor dicho, no se deben) cambiar una vez Windows está instalado. De ser así, no servirían de nada.

### Para instalar Windows 10 desde cero en un ordenador:
Lo siguiente que debemos hacer es introducir la memoria USB en el ordenador apagado y encenderlo. Salvo que tengamos la BIOS/UEFI de nuestro ordenador configurada para arrancar primero desde dispositivos extraíbles como memorias USB, debemos pulsar durante el arranque la tecla F8 repetidas veces (o equivalente, según modelos de placas base) para que nos aparezca el menú de Boot y seleccionar en él nuestro USB con Windows 10 para instalar.
Cuando el sistema intente arrancar desde la memoria USB, lo primero que veremos será un mensaje que nos pedirá que pulsemos una tecla cualquiera para empezar con la instalación de Windows 10.
1.	Pulsamos cualquier tecla, y empezará una ventana de carga durante la cual se cargará en la memoria todo lo necesario para arrancar el asistente de instalación.
2.	Tras esta ventana de carga, que dura unos segundos, veremos la ventana inicial del asistente de instalación de Windows 10.
3.	En esta ventana debemos configurar el idioma de nuestro sistema operativo, el formato de hora y moneda y el tipo de teclado que vamos a utilizar. Pulsamos sobre «Siguiente» y en la nueva ventana que aparece pulsaremos sobre «Instalar ahora«.
4.	El siguiente paso que nos pedirá el asistente será introducir el número de licencia de nuestro Windows. Si la licencia se encuentra grabada en la BIOS/UEFI de nuestro ordenador, esta ventana no la veremos. De lo contrario, si la tenemos a mano podemos introducirla o, si no, pulsamos sobre «No tengo clave de producto» para continuar sin dicha licencia.
5.	A continuación, el asistente nos preguntará por la versión de Windows 10 que queremos instalar. Debemos elegir la que corresponda a nuestra licencia para evitar problemas.
6.	Pulsamos de nuevo sobre Siguiente y aparecerán los términos de licencia, los cuales aceptaremos para continuar.
7.	La siguiente ventana es una de las más importantes. En ella elegiremos el tipo de instalación que queremos:
+	Si queremos actualizar Windows y no perder los datos ni aplicaciones, elegiremos «Actualización».
+	Para una instalación limpia, elegiremos «Personalizada».
8.	Seleccionamos la segunda opción, personalizada, y veremos un nuevo paso en el asistente donde elegir la partición del disco duro donde instalaremos Windows.
9.	Si queremos crear particiones, pulsaremos sobre «Nuevo» y configuraremos el espacio que queremos utilizar para nuestro Windows. Si no hacemos nada, el asistente utilizará automáticamente todo el espacio para instalar Windows (y crear la partición de recuperación de 500 MB). En la segunda imagen podemos ver las particiones que crea por defecto Windows para poder arrancar y funcionar.
10.	Después de formatear para instalar Windows 10, pulsamos sobre «Siguiente» y comenzará el proceso de instalación. Durante este proceso se llevarán a cabo una serie de tareas: 
+	Copia de todos los archivos de instalación al disco duro.
+	Preparar los archivos para la instalación.
+	Instalar características de Windows.
+	Instalar actualizaciones incluidas en el medio se instalación.
+	Finalizar instalación.
+
11. Debemos esperar a que finalice el proceso de instalación. Durante el cual, el ordenador se reiniciará varias veces y, además, veremos distintas fases, tanto del asistente de instalación como de la configuración inicial de nuestro Windows 10

Al finalizar con los procesos de configuración del ordenador procederemos a instalar los drivers pertinentes para su funcionamiento.









