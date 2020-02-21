# IMDBDASH
Dashboard IMDB DATABASE
Dashboard IMDB Database 
Los datos extraídos de la pagina https://www.imdb.com/interfaces/ fueron utilizados para la creación de un dashboard llamado “IMDB” donde se elaboraron los siguientes pasos en la pagina llamada: 
“Movie Report”
1.	Extraer los datos de la página y descargarlos en formato TSV
2.	Abrir un archivo de PowerBI desktop para conectarme a los datos para poder hacer el proceso de ETL , ya cargado en powerquery se procedió a hacer los cambios en algunas columnas para poder procesar mejor la información al final se cargaron al modelo los datos ya listos.
3.	En el modelo se hizo el ER para poder trabajar con datos de diferentes tablas y así poder consolidar la información.
4.	Luego se hizo una medida dax para poder obtener el numero de estrellas por el promedio de rating.
5.	se crearon los siguientes gráficos:
a.	TOP 10 películas por categoría / Grafico de barras 
b.	TOP 10 películas por tipo / Grafico de árbol
c.	TOP 5 Titulo por región / Grafico de árbol / Grafico de áreas 
d.	Una tabla donde se encuentra el título de la película, el número de votos que obtuvo y el promedio de rating.
e.	Se utilizo un filtro para buscar la película por nombre, lenguaje, región y si es un título original o no. / Grafico tipo segmentador y se importo de la tienda una visualización  llamada text filter utilizada para buscar dentro de la tabla por el título de la película 
f.	Una imagen de la compañía 

Los siguientes cambios fueron hechos en la página llamada: “Movie Person”
1.	se crearon los siguientes gráficos:
a.	TOP 10 total de filmes por nombre / Grafico de barras 
b.	TOP 10 películas por tipo / Grafico de árbol
c.	TOP 5 Titulo por región / Grafico de árbol / Grafico de áreas 
d.	Una tabla donde se encuentra el título de la película, el número de votos que obtuvo y el promedio de rating.
e.	Se utilizo un filtro para buscar la película por nombre, lenguaje, región y si es un título original o no. / Grafico tipo segmentador y se importo de la tienda una visualización  llamada text filter utilizada para buscar dentro de la tabla por el título de la película 
f.	Una imagen de la compañía 

El reporte se público en https://powerbi.microsoft.com/es-es/ donde se genero un dashboard a partir de las 2 hojas que se encontraban en el informe donde se pueden generar alertas si fuera necesario , también se creó una vista móvil tanto como para el informe como para el dashboard se puede ingresar para poder verlo con las siguientes credenciales de prueba :
Username : frank@bicontoso.space  
Password  : TESTgt58
De igual manera se subió al repositorio una presentación de Microsoft powerpoint con el reporte final descargado desde el servicio de powerbi y un código QR donde se puede acceder al reporte sin necesidad de un usuario (recomendación verlo en horizontal).

Nota: aún se podría automatizar de muchas maneras utilizando un gateway de power bi para una actualización automática , creando grupos de trabajo colaborativo , podría mejorarse utilizando el lenguaje natural escribiendo sinónimos a las tablas que cargamos al modelo de datos para luego filtar los datos con QA.
