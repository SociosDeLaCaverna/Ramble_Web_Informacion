Este es el repositorio de Github del cual el sitio web oficial del servidor de Minecraft, Ramble, saca informaciones para el sitio web. Si eres staff de Ramble y vienes aquí para agregar o actualizar artículos de la web, estas en el lugar correcto. Por favor, lee todo lo escrito aquí para que puedas entender bien y que no cometas ningún error.

# ¿Comó agrego artículos a la web? ¿Como la actualizo?
El deber de actualizar la web queda a cargo de los administradores de Ramble, que ya tienen una guía proporcionada por el programador de la web para saber como actualizarla con los artículos agregados por el staff. Para agregar artículos, ya sean de guías, eventos o noticias, se deben seguir los siguientes pasos:

# Cosas a tener en cuenta antes de agregar | actualizar artículos
**SE DEBE** seguir la plantilla de artículos correctamente. es deber de los admininistradores y del staff creador del artículo revisar que todo este bien. La plantilla esta guardada en este repositorio, en el archivo **plantilla_articulo.md** de la **carpeta plantillas**;

**SE DEBE** poner el nombre del artículo igual que el nombre del archivo. Se profundizara mas en la siguiente sección.

# Plantilla de artículos explicada
![Imagen de la plantilla de los articulos](https://github.com/SociosDeLaCaverna/Ramble_Web_Informacion/blob/ac03cc32594048588d2eeab24d075f433a4ae0ac/imagenes/Screenshot_220.png)
Las **tres primeras lineas** deben estar pegadas **si o si** a la linea numero uno del archivo del artículo, para que en la web se muestre correctamente, **siempre** tengalo en cuenta. 

Ahora, explicando lo que aparece entre las tres lineas, la de la linea numero uno del archivo y la que esta mas abajo, estas son las propiedades del artículo que la web toma para representarlos. Lo que proporcionan estas propiedades son:

**name**: es el nombre del artículo. Es **importante** que sea igual, o al menos, muy parecido al nombre del archivo .md del artículo. Asi se facilita el trabajo a todo el staff de Ramble encargado de los artículos en general.


**date**: la fecha del artículo, puedes poner la fecha como quieras. Recomiendo a los administradores crear un estandar para esto.

**dateToSort**: esto es lo interesante. La propiedad de los artículos **dateToSort** es la fecha que se utiliza para ordenar los artículos en la web, del mas reciente al mas viejo. Esta propiedad debe indicar la fecha de una manera **MUY** especifica. Debe especificarse así:

```
dateToSort: (año)-(mes)-(dia)
```
Es importante que al mes, le descuentes **UNO**, por como funciona el lenguaje de programación con el que fue hecho la web. Es decir, los meses, deben indicarse así:

+ 0 - enero
+ 1 - febrero
+ 2 - marzo
+ 3 - abril
+ 4 - mayo
+ 5 - junio
+ 6 - julio
+ 7 - agosto
+ 8 - septiembre
+ 9 - octubre
+ 10 - noviembre
+ 11 - diciembre

Por ejemplo, el día 13 de febrero de 2023, en la propiedad **dateToSort**, **SE DEBE** mostrar así: **2023-1-13**

**description**: es la descripción del artículo.

**img**: es el link de la imagen usada para representar el artículo en la web. Debe ser un link, y debe ser una imagen de, por ejemplo, imgur.com o cualquier oro sitio web que permita alojar imagenes. **SIEMPRE Y CUANDO** el link termine en .png, en .jpg, .webp, .svg o algún otro formato de imagen.

# Vale. ¿Pero como agrego o actualizo artículos?
Eso depende de si tienes permisos para escribir archivos en este repositorio o no. 

## Si tienes permisos..
+ Dirigirte a la carpeta correspondiente al articulo que quieras agregar. Por ejemplo, si quieres agregar un artículo de eventos, deberas irte a la carpeta de eventos de este repositorio.
+ Una vez en la carpeta correspondiente al artículo a agregar, deberas ir a su sub-carpeta 'articulos'. No puedes agregar artículos, por ejemplo, a /eventos, si no, que lo tienes que agregar a /eventos/articulos.
+ Ahí mismo, debes crear un archivo, que, importante, debes seguir la plantilla proporcionada, siguiendo cada una de sus indicaciones, para que el sitio web funcione bien. **Es labor del creador del artículo y del administrador verificar que todo este bien**. Además, el archivo tiene que ser un archivo.md.
+ Una vez terminado de crear el artículo

# ¿Como veo como va quedando mi artículo?
