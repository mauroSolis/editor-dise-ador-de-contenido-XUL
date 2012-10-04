# Editor de Gráficas Estadísticas #

Mauro Solís Hernández 200628965

Alexa Morales Céspedes 200842276


## Introducción ##

La aplicación carga y despliegua datos fue implementada mediante el ambiente Mozilla XUL y utilizado el lenguaje CoffeeScript junto con D3.js. Además se utiliza la biblioteca de gráficos RGraph.

RGraph, es una biblioteca para generar gráficos utilizando el elemento <canvas> de HTML5. Al igual que muchas bibliotecas (librerías) gráficas, RGraph soporta una amplia variedad de tipos de gráficos incluyendo barras, pies, radar, etc. Además ofrece una calidad gráfica muy buena a pesar de estar utilizando HTML5.
RGraph es gratuito para uso no comercial, utilizando un link a la página web RGraph y hay licencias comerciales disponibles para uso comercial y gubernamental.


## Descripción del Contenido a Desplegar ##

El contenido que despliega la aplicación son gráficos estadísticos. Actualmente se despliegan los siguientes gráficos:

	- Gráficos de Línea
	- Gráficos de Barras
	- Gráficos Circulares o Pastel


## Definición de estructuras de datos ##

Las estructuras de datos utilizadas son en su mayoría, arreglos de datos. Pero además se utiliza archivos CSV para la lectura de los datos a la aplicación.

Para la lectura de datos se podrian utilizar formatos CSV, JSON o XML. Sin embargo elegimos el formato CSV ya que es con el que nos encontramos mas familiarizados. 


## Forma de Compilación, ejecución y utilización de la aplicación ##

**Compilación de archivo coffee**

Para compilar el archivo main.coffee es necesario contar con el compilador de este lenguaje. Generalmente se puede obtener el ejecutable de dicho compilador llamado coffee.exe (bajo ambiente windows) y la compilación puede ser ejecutada de la siguiente forma:

			coffee -c main.coffee

**Ejecución de la aplicación**

Para ejecutar la aplicación se puede utilizar XulRunner o Firefox. El ambiente XulRunner debe ser descargado e instalado, mientras que Firefox generalmente reside ya en la máquina. Para ejecutar esta aplicación utilizando Firefox (bajo windows) se puede ejecutar la siguiente instrucción:

   			"C:\Program Files (x86)\Mozilla Firefox\firefox.exe" -app "C:\Users\amorale4 \Desktop\interfaces proyecto1\application.ini"


## Ejemplos de Datos a utilizar como Pruebas ##

Los datos usados como pruebas fueron alambrados dentro de la aplicación, esto debido a que se complicó la lectura y separación de datos en el archivoel cual es de formato csv. 

Así los datos son variados y son almacenados en estructuras de arreglos en formato de cadena de caracteres y de numeros enteros.

## Limitaciones observadas y posibles mejoras ##

Una de las mejoras que podria tener es modificar el tipo de ejecución de la aplicación para que sea un archivo ejecutable. Esto facilitaría el uso de la aplicación.

Entre las limitaciones encontradas, es la tecnologiía o herramientas utilizadas debido a que la documentación de la misma, es escasa. 

Además la busqueda de una librería que sea compatible con xul fue bastante difícil, pues la mayoria de librerías incluso las mas utilizadas, tienen tags de html5 que no son compatibles con xul o gecko.





