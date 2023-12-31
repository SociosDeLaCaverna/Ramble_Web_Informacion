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

**TODOS LOS VALORES DE LAS PROPIEDADES DE LOS ARTÍCULOS DEBEN ESTAN ENCERRADOS ENTRE COMILLAS**

# Vale. ¿Pero como agrego o actualizo artículos?
Eso depende de si tienes permisos para escribir archivos en este repositorio o no. 

## Si tienes permisos..
+ Vas a la carpeta correspondiente según el artículo que quieras agregar. Si quieres agregar un artículo de evento vas a /eventos/articulos, si quieras agregar una guía vas a /guias/articulos...
+ Das clic en el botón 'Add file'
  
![Imagen de guía para crear artículos si se tiene permisos](https://github.com/SociosDeLaCaverna/Ramble_Web_Informacion/blob/08eadb76d8102cefd0946b4f4df323f2a839957b/imagenes/imagenes%20de%20guias%20de%20creacion%20de%20articulos/Screenshot_221.png)
+ En el menu que se despliega al darle clic a ese botón, haz clic en el botón que dice 'Create new file'
  
+ En la nueva página que te aparecera, copia y pega la plantilla de artículos y cambia los valores de las propiedades según corresponda

+ Haz clic en el botón 'Commit changes'
  
![Imagen de guía para crear artículos si se tienen permisos](https://github.com/SociosDeLaCaverna/Ramble_Web_Informacion/blob/aba668cfb1b25402841554aa52cbcab790e15d23/imagenes/imagenes%20de%20guias%20de%20creacion%20de%20articulos/Screenshot_222.png)

+ Haz clic en el botón indicado en la captura
  
![Imagen de guía para crear artículos si se tienen permisos](https://github.com/SociosDeLaCaverna/Ramble_Web_Informacion/blob/aba668cfb1b25402841554aa52cbcab790e15d23/imagenes/imagenes%20de%20guias%20de%20creacion%20de%20articulos/Screenshot_223.png)

+ Listo. El artículo ha sido subido. Avisa a algún administrador para que actualice el sitio web.

## Si no tienes permisos..
+ Vas a la carpeta correspondiente según el artículo que quieras agregar. Si quieres agregar un artículo de evento vas a /eventos/articulos, si quieras agregar una guía vas a /guias/articulos...
+ Das clic en el botón 'Add file'
+ Te saldra algo como lo mostrado en la captura. Haz clic en el botón verde.
  
![Imagen de guía para crear artículos si se tiene permisos](https://github.com/SociosDeLaCaverna/Ramble_Web_Informacion/blob/ecc02ce4ad8d5c534f092f27e7c91130b7be0a03/imagenes/imagenes%20de%20guias%20de%20creacion%20de%20articulos/Screenshot_217.png)

+ En la nueva página que te aparecera, copia y pega la plantilla de artículos y cambia los valores de las propiedades según corresponda.
+ Haz clic en el botón 'Commit changes'

![Imagen de guía para crear artículos si se tiene permisos](https://github.com/SociosDeLaCaverna/Ramble_Web_Informacion/blob/ecc02ce4ad8d5c534f092f27e7c91130b7be0a03/imagenes/imagenes%20de%20guias%20de%20creacion%20de%20articulos/Screenshot_218.png)

+ Te saldra una página como esta. Haz clic en el botón señalado.

![Imagen de guía para crear artículos si se tiene permisos](https://github.com/SociosDeLaCaverna/Ramble_Web_Informacion/blob/ecc02ce4ad8d5c534f092f27e7c91130b7be0a03/imagenes/imagenes%20de%20guias%20de%20creacion%20de%20articulos/Screenshot_219.png)

+ Listo. La petición de la actualización o el agregado de un artículo se ha mandado. Avisa a un administrador para que la acepte | revise.

# ¿Quien puede dar permisos en este repositorio?
Solo los administradores pueden dar permisos para agregar o actualizar artículos sin necesidad de realizar los pasos mostrados en la anterior sección. 

# Guía basica para escribir artículos
Los contenidos artículos se escriben, como ya explicado anteriormente, debajo de las tres ultimas lineas despues de las propiedades de los artículos. 

### Como hacer listas
```
Enumerando los elementos y separando los elementos de los numeros por un espacio, ejemplo:
1. primer elemento
2. segundo elemento
3. tercer elemento
4. cuarto elemento

Poniendo un signo de + y separando los elementos de los signos por un espacio, ejemplo:
+ primer elemento
+ segundo elemento
+ tercer elemento
+ cuarto elemento
```

### Como hacer encabezados
```
El sitio web toma todos los encabezados y los pone del mismo tamaño. Los encabezados se escriben poniendo '#' y separandolos del título en sí por un espacio. Ejemplo:

# Este es mi título
```

### Como poner links
```
Los links se ponen de la siguiente manera:
[Texto a mostrar al poner el link](https://github.com/user/repo/blob/branch/other_file.md)
```
[Texto a mostrar al poner el link](https://github.com)

### Como poner imagenes
```
Para poner imagenes, haz esto:
![Aquí puedes poner lo que quieras](Link de la imagen (tiene que acabar en .png, .svg, .webp, .jpg o algún otro formato de imagen) )
```
