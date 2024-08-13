<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mi Currículum</title>
    <style>
        body {
            font-family: Negrita, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #ffebcd;
        }
        .container {
            width: 80%;
            margin: auto;
            overflow: hidden;
        }
        header {
            background: #aaaa;
            color: #fff;
            padding-top: 30px;
            min-height: 70px;
            border-bottom: #ff6347 3px solid;
            transition: background 0.5s;
        }
        header:hover {
            background: #444;
        }
        header h1 {
            text-align: center;
            text-transform: uppercase;
            margin: 0;
        }
        .photo {
            text-align: left;
            margin-top: 20px;
        }
        .photo img {
            border-radius: 50%;
            width: 150px;
            height: 150px;
            transition: transform 0.5s;
        }
        .photo img:hover {
            transform: scale(1.1);
        }
        section {
            padding: 20px;
            background: #fff;
            margin-top: 20px;
            transition: background 0.5s;
        }
        section:hover {
            background: #e0e0e0;
        }
        h2 {
            color: #333;
        }
        .course-box {
            background: #ffebcd;
            padding: 15px;
            margin: 10px;
            border-left: #aa6300 5px solid;
            transition: background 0.5s, transform 0.5s;
            display: inline-block;
            width: calc(33% - 40px);
            box-sizing: border-box;
            height: 150px;
            vertical-align: top;
        }
        .course-box:hover {
            background: #ffe4b5;
            transform: scale(1.05);
        }
    </style>
</head>
<body>
    <header>
        <h1>Fernando Mendez</h1>
    </header>
    <div class="container">
        <div class="photo">
            <img src="ruta/a/tu/foto.jpg" alt="Foto Personal">
        </div>
        <section>
            <h2>Administrador de Redes</h2>
            <p>Sistemas Informaticos</p>
        </section>
        <section>
            <h2>Experiencia Laboral</h2>
            <ul>
                <li>Trabajo 1: Descripción breve</li>
                <li>Trabajo 2: Descripción breve</li>
               
            </ul>
        </section>
        <section>
            <h2>Cursos Aprobados en la Universidad</h2>
            <div class="course-box">
                <p>Curso 1: Base de datos 1</p>
            </div>
            <div class="course-box">
                <p>Curso 2: Analisis de Sistemas</p>
            </div>
            <div class="course-box">
                <p>Curso 3: Administracion 3</p>
            </div>
            <div class="course-box">
                <p>Curso 4: </p>
            </div>
            <div class="course-box">
                <p>Curso 5: Descripción breve</p>
            </div>
            </div>
        </section>
    </div>
</body>
</html>

        
