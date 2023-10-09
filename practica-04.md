Practica 4. Descarga y preprocesa fuentes de elevación
================
<b>José-Ramón Martínez-Batlle</b> (<jmartinez19@uasd.edu.do>) <br>
Facultad de Ciencias, Universidad Autónoma de Santo Domingo (UASD) <br>
Santo Domingo, República Dominicana

<!-- Este archivo se genera a partir de otro del mismo nombre con extensión .Rmd. Por favor, edita ese archivo. -->

> Fecha límite de entrega: 15 de octubre, 23:59 horas.

> Entregable: documento. Entrega tu archivo vía correo electrónico en
> formato nativo. En el caso de usar software de interfaz gráfica, como
> Microsoft Word o LibreOffice Writer, entrega tanto el archivo nativo
> .docx o .odt como el PDF. En el caso de usar procesadores de texto
> como LaTeX, Overleaf, RMmarkdown, entrega tanto el PDF como la carpeta
> (comprimida en ZIP) conteniendo los archivos necesarios para compilar
> el PDF.

## EJERCICIO 1: Descarga un modelo digital de elevaciones

> En lo adelante, usaré las siglas DEM, de *digital elevation model*,
> para referirme al modelo digital de elevaciones.

Basándote en el SRTM-DEM de 1 arcosegundo, construye un DEM para tu área
asignada.

<table class="table table-hover table-condensed" style="margin-left: auto; margin-right: auto;">
<caption>
</caption>
<thead>
<tr>
<th style="text-align:left;">
Nombre
</th>
<th style="text-align:left;">
Poligono
</th>
</tr>
</thead>
<tbody>
<tr>
<td style="text-align:left;">
Debora Ayala Nolasco
</td>
<td style="text-align:left;">
data/practica-04/poligono_7.kml
</td>
</tr>
<tr>
<td style="text-align:left;">
Ernesto Vladimir Santana Martinez
</td>
<td style="text-align:left;">
data/practica-04/poligono_6.kml
</td>
</tr>
<tr>
<td style="text-align:left;">
Frank Félix De la Cruz Díaz
</td>
<td style="text-align:left;">
data/practica-04/poligono_1.kml
</td>
</tr>
<tr>
<td style="text-align:left;">
Gregorio Rivas V
</td>
<td style="text-align:left;">
data/practica-04/poligono_11.kml
</td>
</tr>
<tr>
<td style="text-align:left;">
Iliana Santiago
</td>
<td style="text-align:left;">
data/practica-04/poligono_4.kml
</td>
</tr>
<tr>
<td style="text-align:left;">
Joel Benjamin Perez Garcia
</td>
<td style="text-align:left;">
data/practica-04/poligono_3.kml
</td>
</tr>
<tr>
<td style="text-align:left;">
José Ramón Martínez Batlle
</td>
<td style="text-align:left;">
data/practica-04/poligono_2.kml
</td>
</tr>
<tr>
<td style="text-align:left;">
Maria Dolores Alvarado Florimon
</td>
<td style="text-align:left;">
data/practica-04/poligono_5.kml
</td>
</tr>
<tr>
<td style="text-align:left;">
Mayki Morel
</td>
<td style="text-align:left;">
data/practica-04/poligono_9.kml
</td>
</tr>
<tr>
<td style="text-align:left;">
Reynaldo Rafael Espaillat Santos
</td>
<td style="text-align:left;">
data/practica-04/poligono_10.kml
</td>
</tr>
</tbody>
</table>

Sigue estos pasos:

1.  Desde el [EarthExplorer](https://earthexplorer.usgs.gov/), descarga
    los dos cuadros del SRTM-DEM de 1 arcosegundo que abarquen, como
    mínimo, tu polígono asignado. Los cuadros abarcarán un área mucho
    mayor inicialmente, pero luego lo recortarás. Para descargar, no
    uses el complemento SRTM Downloader, pues necesitarás los cuadros
    independientes para cumplir el mandato. Muestra, en una captura de
    pantalla dentro de tu entregable, tus dos DEM independientes de
    forma independiente, simbolizados como prefieras.

2.  Construye un mosaico mediante ráster virtual (`.vrt`).

3.  Muestra, en una captura de pantalla dentro de tu entregable, tu
    mosaico de DEM, simbolizado como prefieras.

## Ejercicio 2. Representa tu DEM

Representa tu DEM de forma que tengas la imagen de sombras y la
hipsometría coloreada mezcladas en una visualización, colocando algún
tipo de rótulo que te ayude a reconocer el área en cuestión.

Captura la pantalla e insértala en tu entregable.

## Ejercicio 3. Aplica la herramienta *FeaturePreserveSmoothing*, de Whitebox Tools

La herramienta *FeaturePreservingSmoothing* de Whitebox Tools, reduce la
rugosidad generada por el ruido en el DEM.

Para aplicar esta herramienta, instala primero el complemento Whitebox
Tools de QGIS, descarga el ejecutable de Whitebox Tools (*Open Core*) y
especifícale a QGIS dónde se encuentra dicho ejecutable. Si lo logras
configurar bien, podrás ejecutar la herramienta
*FeaturePreservingSmoothing*.

Tanto para instalar como para aplicar la herramienta, sigue las
instrucciones que facilitaré en el aula, sugerencias de tu tutor de IA,
o tutoriales en línea.

## Criterios de evaluación y escala de valoración

## Referencias
