<!-- No borrar o modificar -->
[Inicio](./index.md)

## Sesión 3 


<!-- Su documentación aquí -->


# Actividad:


- Adición de contenido multimedia en un sitio web utilizando etiquetas HTML5
Completa el siguiente código HTML añadiendo el contenido multimedia correspondiente en cada sección:

- 4 Imagenes
- 2 Videos
- 4 Audios
- 2 Inline Frame
- Utiliza encabezados para títulos en cada elemento (<h1>...<h6>).

### Crea una descripción para cada elemento utilizando párrafos (<p>).

Además, puedes emplear las siguientes etiquetas para mejorar la estructura y estilo de tu contenido:

- Usa <strong> para resaltar texto importante.
- Utiliza <br> para insertar saltos de línea si es necesario.
- Agrega <span> para aplicar estilos específicos a porciones de texto.
- Emplea <i> para enfatizar o dar énfasis a palabras o frases.
- Utiliza <u> para subrayar texto cuando sea necesario.
- Considera el uso de <div> para crear secciones o contenedores para tu contenido, lo que puede facilitar la organización y el diseño de la página.

#  SOLUCION
```html

<!DOCTYPE html>
<html>

<head>
    <title>Etiquetas Multimedia HTML5</title>
    <style>
        body {
            font-family: Arial, sans-serif;
        }

        header {
            background-color: #f2f7db;
            color: rgb(12, 9, 9);
            padding: 20px;
            text-align: center;
        }

        section {
            border: 1px solid #b41010;
            padding: 20px;
            margin-bottom: 20px;
        }

        h2 {
            color: rgb(223, 26, 26);
        }

        footer {
            background-color: #e2f0bb;
            color: rgb(12, 6, 6);
            padding: 20px;
            text-align: center;
        }
    </style>
</head>

<body>

    <header>
        <h1>Etiquetas Multimedia HTML5</h1>
        <h3>paisajes y paramos</h3>
    </header>

    <section>
        <h2>Imágenes</h2>
        <p>diversidad</p>
        <img src="imagen1.jpg"  width="300" height="300"> <img src="imagen2.jpg" width="300" height="300"> <img src="imagen3.jpg" width="300" height="300"> <img src="" width="300" height="300">
    </section>

    <section>
        <h2>Videos</h2>
        <p>algunos ejemplos</p>
        <video src="video1.mp4" width="300" height="300" autoplay loop controls></video> <video src="video2.mp4" width="300" height="300" autoplay controls></video>
    </section>

    <section>
        <h2>Audios</h2>
        <p>algunos audios</p>
        <audio src="audio1.mp3" controls  autoplay></audio> 
        <audio src="audio2.mp3" controls autoplay></audio>
        <audio src="audio3.mp3" controls autoplay></audio>
        <audio src="audio4.mp3" controls autoplay></audio>

    </section>

    <section>
        <h2>iFrames</h2>
        <p>otras secciones</p>
        <iframe src="https://www.youtube.com/embed/v64KOxKVLVg%22" frameborder="0" width="500" height="300"> </iframe>
    </section>

    <footer>
        jhonny alejandro perez santana
        <br>
        <br>
        CESDE
        <br>
        <br>
        &copy;2023
    </footer>

</body>

</html>
```


