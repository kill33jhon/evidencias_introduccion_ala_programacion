<!-- No borrar o modificar -->
[Inicio](./index.md)

## Sesión 5 


<!-- Su documentación aquí -->


# Actividad:

### Diseñar un formulario de pedido de un producto

## Objetivo:

Aplicar los conocimientos sobre los tipos de etiquetas HTML para diseñar un formulario de pedido de un producto.

### Instrucciones:

- Crear un nuevo documento HTML.
- Crear un formulario con los siguientes campos:
- Nombre del producto
- Cantidad
- Precio unitario
- Precio total
- Dirección de envío
- Información de contacto (nombre, correo electrónico, número de teléfono)
- Agregar los siguientes campos relacionados al formulario:
- Método de pago
- Fecha de entrega
- Comentarios
- Utilizar las etiquetas HTML apropiados para cada campo.


# SOLUCION

```html

<!DOCTYPE html>
<html lang="es">

<head>
    <meta charset="UTF-8">
    <title>FORMULARIO </title>
</head>

<body>
    <h1>FORMULARIO HTML5</h1>

    <!-- Ejemplo de campo de texto con placeholder -->
    <div>
        <label for="nombre">Nombre del producto</label>
        <input type="text" name="nombre" id="nombre">
    </div>

    <!-- Ejemplo de campo de contraseña con placeholder -->
    <div>
        <label for="cantidad">Cantidad</label>
        <input type="cantidad" name="cantidad" id="cantidad">

    </div>
    <div>
        <label for="precio">precio unitario</label>
        <input type="text" name="precio unitario">

    </div>
    <div>
        <label for="precio total">precio total</label>
        <input type="text" name="precio total">

    </div>
    <div>
        <label for="dirrecion de envio">dirreccion de envio</label>
        <input type="text" name="dirreccion de envio">
    </div>
    <div>
        <h1>informacion del contacto</h1>
    </div>
    <div>
        <label for="Nombre">Nombre</label>
        <input type="text" name="nombre del contacto">
    </div>
    <div>
        <label for="correo electronico">correo electronico</label>
        <input type="text" name="correo electronico">
    </div>
    <div>
        <label for="numero de telefono">numero de telefono</label>
        <input type="text" name="numero de telefono">
    </div>
    <div>

    </div>

    <!-- Ejemplo de botones de radio -->
    <div>
        <label for="metodo de pago">metodo de pago</label>
        <div>

        </div>
        <input type="radio" name="sexo" value="hombre" id="hombre">
        <label for="hombre">efectivo</label>
        <input type="radio" name="sexo" value="mujer" id="mujer">
        <label for="mujer">pago en linea</label>
    </div>
    <div>
        <input type="datetime-local" name="fecha_hora" id="fecha_hora">
        <label for="fecha_hora">Fecha y hora</label>
    </div>
    <div>
        <label for="comentarios">comentarios</label>
        <input contextmenu="100">
    </div>
    <div>
        <input type="submit" value="Enviar" id="enviar">
    </div>



</body>

</html>
```



