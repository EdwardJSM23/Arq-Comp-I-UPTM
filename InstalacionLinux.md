---
title: Instalar Linux
layout: template
filename: InstalacionLinux
--- 

## Instalación Linux 
***
De la misma forma, es fundamental evaluar los componentes del equipo al que se le va a instalar el sistema operativo, para así poder usar la versión más adecuada al ordenador o en su defecto, que la versión que deseemos instalar esté acorde a los requerimientos.
Por lo tanto vamos a ver los requerimientos de los SO más comunes en la actualidad de Linux:

***
### Requisitos del sistema de Ubuntu 20.04 
-	Procesador: De doble núcleo a 2 GHz o Superior
-	RAM: 4 GB (pero con 1 GB puede funcionar)
-	Disco Duro: 25 GB libres serán necesarios
-	Pantalla: 9″ con resolución HD (720p) o superior.
-	Conexión a Internet: Para actualizaciones durante la instalación
-	Accesorio de CD o DVD para la instalación

***
### Requisitos del sistema OpenSuse
- Cualquier procesador AMD64/Intel* EM64T (los procesadores de 32 bits no son compatibles).
- 1 GB de RAM física (4 GB o más recomendados).
- 10 GB de espacio disponible en disco para una instalación mínima, 16 GB para un escritorio gráfico (se recomienda más). En caso de que planee usar instantáneas Btrfs, se recomienda un mínimo de 40 GB para la partición raíz.
- Admite la mayoría de las tarjetas gráficas y de sonido modernas, resolución de pantalla de 1024 x 768 (se recomienda una más alta).

***
### Requisitos del sistema de Linux Mint
-	512MB de RAM. Se recomienda 1GB para un uso más fluido.
-	9GB de RAM. Se recomiendan 20GB si se quieren guardar archivos.
-	Resolución 1024×768.
-	La versión de 64-bits puede funcionar en modo BIOS o UEFI, mientras que la de 32-bits sólo iniciará en modo BIOS.

**Basaremos el proceso de instalación en el sistema operativo de Linux Mint.**

Linux Mint está disponible en 4 versiones:

#### Cinnamon
- Cinnamon es el entorno gráfico propio de Linux Mint y es un fork de GNOME.
-	Es elegante y funcional.

#### MATE
-	MATE es otro fork de GNOME y tiene una imagen casi exacta a la que usaba Ubuntu hasta la llegada de Unity.
-	Es ligero, o debería serlo al usar un entorno gráfico que Ubuntu dejó en 2010.
-	Especialmente indicado para los que prefieren un entorno gráfico clásico.

#### Xfce
-	Xfce es aún más ligero que MATE. En Linux Mint es muy elegante.
-	Es la mejor opción para los PCs de bajos recursos.

#### KDE
-	KDE es uno de los entornos gráficos más completos.
-	Ofrece muchas opciones y tiene una imagen muy atractiva.
-	Está más indicado para ordenadores más modernos. Personalmente diría que me encanta KDE, pero que no suelo usarlo en mi portátil porque suelo ver más avisos de errores de los que me gustaría ver.

### Pasos a seguir para instalar Linux Mint desde un USB
1.	Vamos a la web oficial y descargamos la imagen ISO del sistema operativo. Podemos elegir entre descargarlo directo de la web o hacerlo usando un cliente para descargar archivos .torrent. 
2.	A continuación tenemos que crear el USB bootable. Hay muchísimas herramientas disponibles para cualquier sistema operativo, pero podemos usar UNetbootin porque es libre y está disponible para Linux, Mac y Windows. Además, su uso es muy sencillo:
+	Si no lo tenemos instalado, lo instalamos. En Linux podemos hacerlo usando el comando «sudo apt install unetbootin» sin las comillas.
+	Abrimos UNetbootin.
+	Buscamos la imagen ISO que hemos descargado en el paso 1 haciendo clic en los 3 puntos (…).
+	Elegimos la unidad en donde se creará el USB bootable. Es recomendable asegurarse de que hemos hecho una copia de seguridad de los datos importantes que hay en ese USB.
+	Hacemos clic en Aceptar y esperamos a que finalice el proceso.
3.	Iniciamos desde el USB que acabamos de crear.
4.	Ahora tenemos que instalar Linux Mint como lo haríamos con cualquier otro sistema operativo basado en Ubuntu:
+	En el primer paso yo recomendaría conectar el PC a una toma de corriente y a Internet, bien sea por cable o Wi-Fi.
+	Hacemos doble clic sobre el icono que pone «Install Linux Mint».
5.	Elegimos el idioma y hacemos clic en «Continuar».
6.	En el siguiente paso elegiremos cómo queremos realizar la instalación. De todas las opciones, yo destacaría tres:
+	Instalar el sistema junto a otro (dualboot).
+	Eliminar todo el disco e instalar Linux Mint de 0.
3.	Más, desde donde podemos realizar particiones como la raíz, la personal y swap. Esta es la opción que suelo elegir yo.
7.	Ahora empezará la instalación de verdad. En el primer paso, elegimos nuestra zona horaria y hacemos clic en «Continuar».
8.	Seleccionamos la distribución de nuestro teclado. Para el español de España sólo tenemos que elegir «Español», pero podemos asegurarnos si hacemos clic en «Detectar distribución del teclado», lo que nos pedirá que pulsemos algunas teclas y lo configurará automáticamente. Hacemos clic en «Continuar».
9.	Creamos nuestra cuenta de usuario. Tenemos que introducir:
+	Nuestro nombre.
+	Nombre del equipo.
+	Nombre de usuario.
+	Introducir contraseña.
+	Confirmar contraseña.
10.	Hacemos clic en «Continuar».
11.	Ahora ya nos toca esperar a que se realice la instalación. Cuando el proceso haya terminado, hacemos clic en «Reiniciar ahora» y ya entraríamos a Linux Mint.



