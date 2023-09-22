<!-- No borrar o modificar -->
[Inicio](./index.md)

## Sesión 2


<!-- Su documentación aquí -->


# Actividad:

- Creando mi primer sitio web
- Crea un sitio web compuesto por 3 páginas HTML utilizando la estructura y los elementos que has aprendido.
- personaliza el sitio y utiliza diferentes etiquetas HTML.

 ### Las páginas del sitio serán:

- Index o página de inicio
- Acerca
- Contacto

# SOLUCION 

### opcion 1

```html

<!DOCTYPE html>
<html>

<head>
    <title>creditos mairony</title>
</head>

<body>

    <header>
        <h1>mi sitio web</h1>
    </header>

    <nav>
        <a href="acerca.html">acerca</a>
        <a href="contacto.html">contacto</a>

    </nav>


    <main>
        <p>bienvenidos ami sitio sobre la empresa creditos mairony</p>
        <p>aqui encuentras informacion sobre nuestros pruductos</p>
    </main>

    <footer>
        <p>copyring 2023 - jhonnyperez</p>
        <p>jhonkill2025@gmail.com</p>

    </footer>




</body>

<html>
```
### opcion 2

```html

<!DOCTYPE html>
<html>

<head>
    <title>contacto</title>
</head>

<body>

    <header>
        <h1>contactos</h1>
    </header>
    <nav>
        <a href="index.html">inicio</a>
        <a href="acerca.html">acerca</a>
    </nav>

    <main>
        <form>
            <label for="nombre">jhonnyperez</label>
            <input type="text" id="nombre"><br>

            <label for="email">jhonkill2025</label>
            <input type="email" id="email"><br>

            <label for="mensaje">dispuestos a ayudar</label><br>
            <textarea id="mensaje"></textarea><br>

            <input type="submit" value="enviar">
        </form>
        <aside>
            <h3>ubicacion</h3>
            <p>calle 64d 92 22</p>
        </aside>

    </main>
    <footer>
        <p>copyright 2023 - jhonnyperez</p>
    </footer>

</body>

</html>
```

### opcion 3

```html

<!DOCTYPE html>
                 <html>

                 <head>
                    <title>somos fabricantes de buenos productos</title>
                 </head>

                 <body>

                    <header>
                        <h1>empresa dedicada a fabricacion y inovacion para el usuario</h1>
                    </header>

                    <nav>
                        <a href="index.html">inicio</a>
                        <a href="contacto.html">contacto</a>
                        <a href="acerca.html">acerca de</a>
                    </nav>

                    <section>
                        <h2>historia</h2>
                        <p>fundada en 2000</p>
                        <article>
                            <h3>mision y vision</h3>
                            <p>nuestra mision es ser efectivos en el mercado</p>
                        </article>

                    </section>

                    <footer>
                        <p>copyright - jhonnyperez</p>
                    </footer>
                    
                 </body>
                 </html>
```




