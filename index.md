## Antígenos y receptores, ¿Cuáles son más compatibles?
Nuestro proyecto consiste en hacer una investigación de las proteínas pertenecientes a un virus,  en este caso el virus de Nipah, con el fin de analizar la unión que puede tener con algunos receptores tipo TOLL, mediante varios servidores e interpretar  la información que nos generan

![](murcielagos.png)


**Los murciélagos sobrevuelan el mercado de Battambang, Camboya orinando y defecando en cualquier sitio.**

## Introducción


Hasta la fecha no existe una cura o un tratamiento específico, es por ello que el virus del Nipah se encuentra en la lista de enfermedades prioritarias del plan de investigación y desarrollo de la OMS.

![](6EB9.png)

**Estructura de la proteína 6EB9 del virus del Nipah**

# Métodología

1.   Se realizó una investigación a cerca de las proteínas pertenecientes al virus de Nipah, estas podrían ser proteínas de la cubierta del virus o de su interior, la finalidad de esto es utilizarlas como posibles antígeno y mediante una base de datos y varios software’s comprobar su afinidad con diferentes receptores tipo TOLL.

2.   Una vez seleccionadas las proteínas propias del virus de Nipah se tomaron en cuenta ciertas características como su estructura, función y ubicación, para posteriormente emparejarlas con un receptor de tipo TOLL. Las estructuras tridimensionales de las proteínas fueron obtenidas de la página de PDB (Protein Data Bank)

3.   Para tener una mejor visualización de la estructura de las proteínas y llevar a cabo un análisis más detallado se utilizó el programa “UCSF Chimera”, cada proteína tiene un código de identificación  PDB (obtenido en la página Protein Data Bank) que se puede ingresar y gracias a la base de datos con la que cuenta el programa se genera la imagen tridimensional de la proteína, las funciones con las que cuenta Chimera van desde una visualización interactiva de la estructura, su análisis molecular y datos relacionados como mapas de densidad, ensamblajes moleculares, secuencias de aminoácidos, acoplamientos y trayectorias.

4.   Una vez que se tuvo la proteína en el programa Chimera, se eliminaron todos los residuos que rodeaban a la estructura mediante las funciones del programa, se seleccionan las cadenas específicas de los residuos y se borran, dejando únicamente la proteína de interés

5.   Se le asignó un nombre a cada cadena para que sirviera como identificador para el software que se utilizaría más adelante y se coloreó la estructura del antígeno. Se realizó el mismo procedimiento para los receptores de tipo TOLL, se limpian de todos los residuos y también se le asignan un nombre a cada cadena diferente de los antígenos.

6.   Cada estructura se guardó como un documento .pdb y con el nombre que identificará a cada molécula. Se llevó a cabo el docking molecular con ayuda del servidor web “HDOCK”, la página utiliza un algoritmo de acoplamiento híbrido de modelado basado en plantillas y acoplamiento gratuito. 

7. Una vez que la página generó una imagen del acoplamiento entre la proteína del virus (antígeno) y el receptor tipo TOLL, se descargó el modelo considerando la predicción con mayor afinidad. En la parte inferior de la página de HDOCK se muestra una tabla con los diversos modelos posibles, cada uno tiene los datos aproximados de la energía de atraque, donde menor sea el número más posibilidad hay de unión

8. Para tener un dato más preciso de la afinidad entre las moléculas del modelo generado por HDOCK se utilizó Prodigy Webserver (PROtein binDIng enerGY prediction) que genera una predicción de la afinidad de unión en complejos biológicos, así como la identificación de interfaces biológicas a partir de una cristalografía.

9. Se analizaron las uniones entre las moléculas mediante la página de PDBsum, este servidor web proporciona información estructural más detallada sobre las proteínas del Protein Data Bank, los análisis que el algoritmo genera se basan principalmente en imágenes e incluyen estructura secundaria de proteínas, interacciones proteína-ligando, que es lo que se busca en el proyecto, también trabaja con complejos proteína-DNA y análisis PROCHECK de calidad estructura, entre otras funciones

10.  Finalmente, se interpretaron los resultados obtenidos de cada uno de los servidores a los que se introdujo los modelos de las proteínas con los receptores 



### Resultados

Este es el momento en que nos compartas los resultados obtenidos en tu proyecto. Asegurate de incluir material visual (gráficas, fotos, diagramas, tablas). 

Puedes inster imagenes utilizando Markdown `![](Logo_CdeCMx.png)`.

![](Logo_CdeCMx.png)

O utilizando codigo html `<img src="Logo_CdeCMx.png" width=200>`, la ventaja de utilizar html es que le puedes modificar el tamaño utilizando **width**.
<img src="Logo_CdeCMx.png" width=200>


### Conclusiones

Comparte tus observaciones, lo aprendedido, limitaciones y siguientes pasos. 

### Video
 1. Para insertar un video de YouTube, en la página de YouTube del video selecciona compartir y selecciona el código de html.
 <iframe width="560" height="315" src="https://www.youtube.com/embed/PLj1-CMNERM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
 
 2. Insertar el link de tu video en YouTube, [nuestro video](https://youtu.be/rmXvlBPq24Q).
 4. Puedes subir el archivo de tu video directamente a Github [instrucciones aquí](https://stackoverflow.com/questions/4279611/how-to-embed-a-video-into-github-readme-md)
 
### Equipo

* Ana Guadalupe Méndez Hernández
* Angel Ramirez Angeles
* Ana Rosa de la Cruz Nicolás
* Andrea Melissa Mollineda Oregón 

