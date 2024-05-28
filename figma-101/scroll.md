# Scroll

¿Qué ocurre si el contenido que queremos representar no cabe en todo el frame?

![Si desactivamos la casilla "Clip content" podemos ver el contenido que no cabe en el frame](../.gitbook/assets/clip\_content.png)

En primer lugar, debemos especificar el orden de profundidad de los elementos, ya que podemos observar que existe un problema de solapamiento. Para ello, podemos modificar el orden en "Z" haciendo click derecho sobre el elemento y seleccionando "Bring to front" o "Send to back":

![Podemos modificar el orden de dibujado en "Z"](../.gitbook/assets/send\_front.png)

![](../.gitbook/assets/HomeSolapes.png)

Ahora, seleccionamos todo el frame "Home" y en el panel _Prototype_ modificamos la opción de _Overflow scrolling_:

![Habilitamos el scroll vertical en el frame cuando hay contenido que no cabe en el frame](../.gitbook/assets/scroll\_vertical\_frame.png)

Sin embargo, si ejecutamos el prototipo interactivo, todo el contenido se desplazará. Por ello, debemos especificar qué elementos se ven afectados por el scroll y cuáles no. Por ello, es conveniente generar grupos.

![Esta casilla previene el scroll en elementoss dentro de un frame con scroll](../.gitbook/assets/fixed\_scrolling.png)

{% hint style="info" %}
Esta propiedad de fijar la posición del elemento frente a un scroll se ha movido al menú Prototype <img src="../.gitbook/assets/Captura de Pantalla 2023-05-22 a las 17.47.22.png" alt="" data-size="line">
{% endhint %}

Deberás aplicar esta opción a los siguientes elementos:

* Barra de estado
* Barra inferior
* Menú home flotante

![](../.gitbook/assets/proto\_scroll\_fixed.png)
