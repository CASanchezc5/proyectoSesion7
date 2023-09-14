"# proyectoSesion7" 
En esta sesion se creo un ´proyecto web, el cual se creo en el repositorio de GitHub y luego se hicieron cambion en en Git local. A continuacion envio el link del repositorio, donde se encuentran los respectivos commit y todo lo que se hizo a este repositorio, el repositorio tiene por nombre "proyectoSesion7".
contiene un index.html y un registro.html, al igual que una carpeta con sus respectivas imagenes

index.html
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Proyecto Web Git</title>
</head>
<body>
    <header>
        <h1>Química Farmaceútica</h1>
        <img src="/img/farmacia.png" alt="logo" width="100px">
        <nav>
            <a href="registro.html">Registro</a>
        </nav>
    </header>


    <p>La <strong>química medicinal, farmacoquímica o química farmacéutica</strong> es una de las consideradas ciencias farmacéuticas, con profundas raíces en la química. Sus objetivos son la identificación, la síntesis y el desarrollo de nuevos compuestos químicos que sean adecuados para el uso terapéutico. Esto incluye el estudio de los fármacos existentes, sus propiedades biológicas y su relación estructura-actividad cuantitativa. También estudia las interacciones cuantitativas entre estas moléculas y sus efectos biológicos</p>

    <p>Los químicos farmacéuticos son indispensables en las fases preclínicas del desarrollo de fármacos, y también como químicos farmacéuticos en el control de calidad de los mismos. Las etapas del desarrollo de un fármaco comprenden desde el éxito hasta el candidato preclínico, pasando por la sustancia farmacológica.</p>

    <iframe width="560" height="315" src="https://www.youtube.com/embed/D2fiiaBJvUk?si=QD17D330O_TrGPq-" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

    <hr>

    <img src="/img/qcafarmaceutica.png" alt="Quimico farmaceuta">
    <br>


    <h2>Tabla de Quimicas en Química Farmaceútica</h2>
    <table border="1">
        <thead>
            <tr>
                <th colspan="2">Tipos de Químicas que se estudia en Química Farmaceútica</th>
            </tr>
            <tr>
                <th>Tipo</th>
                <th>Descripción</th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>Química Inorganica</td>
                <td> se encarga del estudio integrado de la formación, composición, estructura y reacciones químicas de los elementos y compuestos inorgánicos; es decir, los que no poseen enlaces carbono-hidrógeno</td>
            </tr>
            <tr>
                <td>Química Organica</td>
                <td>es la rama de la química que estudia una clase numerosa de moléculas, que, en su mayoría contienen carbono formando enlaces covalentes: carbono-carbono o carbono-hidrógeno y otros heteroátomos, también conocidos como compuestos orgánicos</td>
            </tr>
            <tr>
                <td>Química Analitica</td>
                <td>estudia y utiliza instrumentos y métodos para separar, identificar y cuantificar la materia.​ En la práctica, la separación, identificación o cuantificación puede constituir el análisis completo o combinarse con otro método. La separación aísla los analitos.</td>
            </tr>
            <tr>
                <td>Bioquimica</td>
                <td>es una rama de la ciencia que estudia la composición química de los seres vivos, especialmente las proteínas, carbohidratos, lípidos y ácidos nucleicos, además de otras pequeñas moléculas</td>
            </tr>
            <tr>
                <td>Fitoquimica</td>
                <td>se encarga del estudio de los compuestos químicos presentes en las plantas, particularmente de los llamados metabolitos secundarios o productos naturales, que son aquellos característicos de una especie, de un género y/o de una familia vegetal.</td>
            </tr>
            <tr>
                <td>Biotecnologia</td>
                <td>es un conjunto de técnicas que utiliza células vivas, cultivo de tejidos o moléculas derivadas de un organismo, por ejemplo, enzimas, para obtener o modificar un producto, mejorar una planta o un animal o desarrollar un microorganismo para utilizarlo con un propósito específico.</td>
            </tr>
            <tr>
                <td>Fisicoquimica</td>
                <td>también llamada química física, es una subdisciplina de la química que estudia la materia empleando conceptos físicos y químicos.</td>
            </tr>
        </tbody>
    </table>

</body>
</html>
```
registro.html
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Registro</title>
</head>
<body>
    <header>
       <h1>Formulario de Registro</h1> 
       <img src="/img/registro.png" alt="registro" width="200px">
    </header>

    <label for="idnombre">Nombre</label>
    <input type="text" id="idnombre" placeholder="Ingrese su nombre" required>
    <br>

    <label for="idapellidos">Apellidos</label>
    <input type="text" id="idapellidos" placeholder="Ingrese sus apellidos" required>
    <br>

    <label for="idedad">Edad</label>
    <input type="number" id="idedad" >
    <br>

    <label for="idemail">Correo Electronico</label>
    <input type="email" id="idemail" placeholder="Ingrese su correo electronico" required>
    <br>

    <label for="idgenero">Genero</label>
    <select name="genero" id="idgenero">
        <option value="masculino">Masculino</option>
        <option value="femenino">Femenino</option>
        <option value="otro">otro</option>
    </select>
    <br><br>

    <input type="submit" value="Enviar">
    <input type="reset" value="Borrar">
    <br><br>

    <a href="index.html" >Ir a inicio</a>

</body>
</html>
```
