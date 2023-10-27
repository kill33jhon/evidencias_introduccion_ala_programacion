<!-- No borrar o modificar -->
[Inicio](./index.md)

## Sesión 9 


<!-- Su documentación aquí -->




# Actividad:


### Propiedades de espaciado y unidades de medida Objetivo:



### Practicar el uso de las propiedades de espaciado margin, padding, border y border-radius, con diferentes unidades de medida.

Crea un nuevo archivo HTML y CSS.
En el archivo HTML, agrega el siguiente código:

```html

<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <title>Propiedades de espaciado</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <div class="contenedor">
    <div class="elemento"></div>
  </div>
</body>
</html>
```

```java
En el archivo CSS, agrega el siguiente código:
.contenedor {
  width: 200px;
  height: 200px;
}

.elemento {
  width: 100px;
  height: 100px;
}

Abre el archivo HTML en tu navegador. Verás un cuadrado de 100x100 píxeles.

Practicar el uso de las propiedades de espaciado.

Margin: Agrega un margen de 10 píxeles a todos los lados del elemento.
.elemento {
  margin: 10px;
  width: 100px;
  height: 100px;
}

Padding: Agrega un relleno de 20 píxeles a todos los lados del elemento.
.elemento {
  padding: 20px;
  margin: 10px;
  width: 100px;
  height: 100px;
}

Border: Agrega un borde de 5 píxeles de color rojo.
.elemento {
  border: 5px solid red;
  padding: 20px;
  margin: 10px;
  width: 100px;
  height: 100px;
}

Border-radius: Agrega un radio de esquina de 10 píxeles.
.elemento {
  border-radius: 10px;
  border: 5px solid red;
  padding: 20px;
  margin: 10px;
  width: 100px;
  height: 100px;
}

Unidades de medida: Prueba diferentes unidades de medida para las propiedades de espaciado. Por ejemplo, puedes usar unidades porcentuales (%) para establecer un margen o relleno del 50%.
.elemento {
  border-radius: 10px;
  border: 5px solid red;
  margin: 50%;
  padding: 50%;
  width: 100px;
  height: 100px;
}

```


# Preguntas:
- ¿Qué es la propiedad margin?
- ¿Qué es la propiedad padding?
- ¿Qué es la propiedad border?
- ¿Qué es la propiedad border-radius?
- ¿Qué unidades de medida se pueden utilizar para las propiedades de espaciado?


# SOLUCION


1. La propiedad margin es una propiedad CSS que se utiliza para controlar el espacio alrededor de un elemento HTML. Los márgenes se aplican fuera del borde del elemento y ayudan a crear espacios en blanco entre elementos adyacentes en una página web. La propiedad margin se utiliza para establecer los márgenes superior, derecho, inferior e izquierdo de un elemento y puede tomar varios valores.

2. La propiedad padding es una propiedad CSS que se utiliza para controlar el espacio entre el contenido de un elemento HTML y su borde. A diferencia de la propiedad margin, que controla el espacio fuera del borde de un elemento, la propiedad padding controla el espacio dentro del borde del elemento. Es decir, el padding afecta al espacio entre el contenido y el borde del elemento en sí.

3. La propiedad border en CSS se utiliza para definir y controlar el borde de un elemento HTML, como un div, una imagen, un botón u otro elemento. El borde es una línea que rodea el contenido de un elemento y puede tener diferentes estilos, grosores y colores. La propiedad border se combina con otras propiedades para especificar cómo se verá el borde de un elemento. 

4. La propiedad border-radius en CSS se utiliza para controlar la curvatura de las esquinas de un elemento con bordes, como un div, una caja, una imagen u otro elemento HTML. Permite redondear o suavizar las esquinas del elemento, creando esquinas redondeadas en lugar de esquinas puntiagudas.

5. En CSS, puedes utilizar diversas unidades de medida para especificar las propiedades de espaciado, como márgenes (margin), relleno (padding), tamaño de fuente (font-size) y más. Las unidades de medida más comunes incluyen:

Píxeles (px): Esta es la unidad de medida más común y es una unidad fija. Un píxel es la unidad más pequeña de una pantalla de ordenador. Por ejemplo, 10px significa 10 píxeles de tamaño.

Porcentaje (%): Las unidades de porcentaje se basan en el tamaño del elemento contenedor. Por ejemplo, si defines un margen de 10%, este será el 10% del ancho del contenedor.

Em (em): La unidad "em" se basa en el tamaño de la fuente del elemento contenedor. Por ejemplo, si el tamaño de fuente del elemento contenedor es de 16px, un margen de 2em sería igual a 32px (2 veces el tamaño de fuente).

Rem (root em): Similar a "em," pero se basa en el tamaño de fuente del elemento raíz (normalmente el tamaño de fuente del elemento <html>). Esto garantiza una mayor consistencia en toda la página, ya que no depende del tamaño de fuente del elemento contenedor.

Viewport Width (vw) y Viewport Height (vh): Estas unidades se basan en el tamaño de la ventana gráfica del navegador. 1vw representa el 1% del ancho de la ventana gráfica, y 1vh representa el 1% de la altura de la ventana gráfica. Son útiles para diseñar elementos que se escalan en función del tamaño de la ventana.

Centímetros (cm), Milímetros (mm), Pulgadas (in), Picas (pc) y Puntos (pt): Estas unidades son absolutas y están relacionadas con medidas físicas reales. Por ejemplo, 1cm es igual a 1 centímetro en la pantalla.

Fracciones (fr): Esta unidad se utiliza en el diseño de cuadrículas CSS. Permite especificar fracciones de espacio disponible en una cuadrícula.

Unidades de medida relativas a la raíz (ex y ch): Estas unidades se basan en el ancho de un carácter 'x' y '0' en la fuente del elemento raíz, respectivamente.

Las unidades de medida permiten un alto grado de flexibilidad en el diseño web, ya que te permiten adaptar el espaciado y el tamaño de los elementos a diferentes pantallas y contextos. La elección de la unidad de medida depende de tus necesidades de diseño y de la forma en que deseas que los elementos respondan a diferentes condiciones de visualización.

