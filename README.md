# entrega1_ironhack
Mi dirección de GitHub para este repositorio es la siguiente: [GitHub](https://github.com/lauralardies/entrega1_ironhack)
https://github.com/lauralardies/entrega1_ironhack

## Tarea
<img src="https://github.com/lauralardies/entrega1_ironhack/blob/main/images/mockup.png" width="600" alt="Mockup">

Convert this mockup into an html and css page without using flexbox. Try to create a faithful copy of the mockup.
- Enter at least one image.
- Use at least 3 different colors for the elements.
- Put an H1 in all caps.
- Add underlined phrases or CSS line effects.
- Use span to achieve a “highlighting” effect.

## Archivos
Todos los archivos de esta tarea están guardados en la carpeta `Entrega`, donde nos encontraremos:
- Documento de HTML llamado `index.html` en el cual desarrollamos la estructura de nuestro programa.
- Carpeta llamada `styles`, donde se encuentra un archivo de CSS, `style.css`, que se usa para modificar la vista del HTML que ya hemos estructurado anteriormente.

Además contamos con otra carpeta llamada `images` que almacena las imágenes que usamos en este archivo `README.md`.

## Código
### Código `index.html`
```
<html>
    <head>
        <title>Entrega</title>
        <link rel="stylesheet" href="./styles/style.css">
    </head>

    <body>
        <div id = "col-1" >
            <div class = "right-border space-down" id = "div0">
                header
            </div>
            <div class = "line-bottom bottom-border" id = "div1">
                sidebar
            </div>
            <div class = "top-border" id = "div2">
                sidebar
            </div>
        </div>

        <div id = "col-2">
            <div class = "left-border space-down" id = "div0" style = "width: 800px;">
                header
            </div>
            <div class = "space-down" id = "div3">
                <h1>contenido</h1>
                <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. <span>Aliquam</span> ut ligula lectus. Aliquam quis erat gravida, vestibulum diam et, lacinia nisl. Etiam mattis posuere augue. Sed quam purus, blandit non nibh vitae, sagittis mattis mi. <span>Vestibulum</span> nec felis vitae diam condimentum mollis vitae sed purus. Aenean ornare vel purus id scelerisque. Aenean semper bibendum molestie.</p>
                <img src="https://us.123rf.com/450wm/jabkitticha/jabkitticha1607/jabkitticha160700270/60102905-foto-icono.jpg" alt="imagen" width="50">
            </div>
            <div id = "div4">
                footer
            </div>
        </div>
    </body>
</html>
```
### Código `style.css`
```
* {
    font-weight: bold;
    font-family:'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;  
}

body {
    color: #313130;
}

h1 {
    font-size: 16px;
    text-transform: uppercase;
}

div {
    width: 300px;
    float: left;
    border-radius: 3.5%;
}

span {
    background-color: #79b177;
    text-decoration: underline;
}

/* Clase que añade un espacio debajo */
.space-down {
    margin-bottom: 20px;
}

/* Clase que agrega el borde de abajo */
.line-bottom{
    border-bottom: 1px solid #000;
}

/* Clase que elimina la propiedad border-radius de los bordes de abajo */
.bottom-border {
    border-bottom-left-radius: 0%;
    border-bottom-right-radius: 0%;
}

/* Clase que elimina la propiedad border-radius de los bordes de arriba */
.top-border {
    border-top-left-radius: 0%;
    border-top-right-radius: 0%;
}

/* Clase que elimina la propiedad border-radius de los bordes de la izquierda */
.left-border {
    border-top-left-radius: 0%;
    border-bottom-left-radius: 0%;
}

/* Clase que elimina la propiedad border-radius de los bordes de la derecha */
.right-border {
    border-top-right-radius: 0%;
    border-bottom-right-radius: 0%;
}

#div0 {
    background-color: #f3f1a2;
    padding: 10px 0;
    text-align: center;
}

#div1, #div2 {
    background-color: #ee8a8a;
    width: 280px;
    padding: 110px 0;
    text-align: center;
}

#div3 {
    background-color: #b2eeb0;
    width: 800px;
    padding: 100px 0;
    text-align: center;
}

#div4 {
    background-color: #a7c9eb;
    width: 800px;
    padding: 20px 0;
    text-align: center;
}
```

## Output
Lo que se muestra al ejecutar el HTML, es lo siguiente:

<img src="https://github.com/lauralardies/entrega1_ironhack/blob/main/images/output.png" width="600" alt="Output">
