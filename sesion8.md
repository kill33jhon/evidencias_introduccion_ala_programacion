<!-- No borrar o modificar -->
[Inicio](./index.md)

## Sesión 8 


<!-- Su documentación aquí -->



# Actividad:

 Aplicando estilos con selectores CSS

El objetivo de esta actividad es crear la estructura HTML básica de una página web y aplicar diferentes selectores CSS para modificar su presentación.

### Pasos:

Crea el esqueleto de una página web simple con la siguiente estructura:

- Encabezado <header>
- Tres párrafos <p>
- Una imagen <img>
- Un pie de página <footer>

### Aplica los siguientes estilos usando selectores de etiqueta:

- Color rojo a los encabezados <h1>
- Color azul a los párrafos <p>
- Borde grueso negro a la imagen <img>

### Aplica los siguientes estilos usando seleccionadores de clase:

Color verde a los elementos con la clase ".destacado"
Tamaño de fuente grande a los elementos con la clase ".grande"

### Aplica los siguientes estilos usando seleccionadores de ID:

- Color amarillo al elemento con ID "#principal"
- Sombra al elemento con ID "#sombras"

### Aplica los siguientes estilos usando seleccionadores descendientes:

Color gris a los párrafos dentro de un <div>
Centrar el contenido de la sección <section>





# SOLUCION



```html

<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <title>Título de tu página</title>
</head>
<body>
    <header>
        <h1>Encabezado de tu página</h1>
        <nav>
            <ul>
                <li><a href="#">Inicio</a></li>
                <li><a href="#">Acerca de</a></li>
                <li><a href="#">Servicios</a></li>
                <li><a href="#">Contacto</a></li>
            </ul>
        </nav>
    </header>
    
    <main>
        <h2>Contenido Principal</h2>
        <p>Este es el contenido principal de tu página.</p>
    </main>

    <footer>
        <p>Pie de página - © 2023 Tu Empresa</p>
    </footer>
</body>
</html>


```
