# Formas

Dado que el primer prototipo que realizaremos será un _wireframe_, necesitaremos generar formas que, en un futuro, deberían ser sustituidas por textos, imágenes o iconos.

Para crear una forma, seleccionamos la herramienta de forma, elegimos la forma que queramos generar y la "dibujamos" (click+drag) dentro del _frame_:

![Figma nos permite seleccionar múltiples formas y sus propiedades](../.gitbook/assets/shape\_tool.png)

Independientemente de la forma que arrastremos, al seleccionarla, podremos modificar sus propiedades. En el ejemplo, hemos añadido un rectángulo, una elipse y una estrella:

![Según el elemento seleccionado, las propiedades pueden variar](../.gitbook/assets/shape\_props.png)

Las siguientes propiedades suelen ser comunes a todos los elementos seleccionables:

* **Alignment**: Alineación de los elementos seleccionados; e.g., seleccionarlos todos y alinear sus centros de manera horizontal
* **x y**: Posición
* **w h**: Tamaño
* **Rotación**: En grados
* **Corner radius**: Permite definir esquinas redondeadas
* **Constraints**: Deberemos utilizarla si quisiéramos que un elemento quede anclado a un borde o se expanda conforme el tamaño del _frame_ varía (_responsiveness_)
* **Fill**: Relleno de la forma
* **Stroke**: Borde de la forma
* **Export**: Figma nos permite exportar los elementos como imágenes para facilitar el desarrollo

![Estrella con una configuración particular](../.gitbook/assets/star.png)

Finalmente, Figma permite exportar una misma imagen con diferentes tamaños. Esto es habitual cuando desarrollamos aplicaciones móviles, donde podemos encontrar dispositivos con diferentes resoluciones, y, según la resolución del mismo, la aplicación mostraría una imagen u otra:

![Podemos añadir diferentes tamaños de exportación pulsando en '+'](../.gitbook/assets/export1.png)

Como las formas de Figma están vectorizadas, no tendremos problemas de "pixelación" al generar diferentes tamaños de la misma:

![1x](<../.gitbook/assets/Star 1.png>)

![2x](<../.gitbook/assets/Star 1@2x.png>)

![3x](<../.gitbook/assets/Star 1@3x.png>)

