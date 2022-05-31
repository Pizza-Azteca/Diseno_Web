Agrega aqui el código de la página de Octavio Paz en HTML Y CSS

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Poemas Octavio Paz</title>
</head>
<body>
    <h1>5 poemas de Octavio Paz</h1>
    <a href="https://web.whatsapp.com/" target="_blank"><img src="ws.png" width="30" alt=""></a>
    <a href="https://www.facebook.com/" target="_blank"><img src="fb.png" width="30" alt=""></a>
    <a href="https://www.google.com/intl/es-419/gmail/about/" target="_blank"><img src="correo.png" width="30" alt=""></a>
    <a href="https://twitter.com/?lang=es" target="_blank"><img src="twitter.png" width="30" alt=""></a>
    <img src="mas.png" width="45" alt=""><br>
    <img src="octavio paz.jpg" width="600" alt="octpaz">
    <p>Poeta y ensayista mexicano, recibió el Premio Nobel de literatura en 1990 <br> como reconocimiento a su obra literaria. Aquí te ofrecemos 5 poemas de <br> Octavio Paz.</p>
    <p><b>Decir, hacer</b></p>
    <p>A Roman Jakobson</p>
    <p>Entre lo que veo y digo, <br>
        Entre lo que digo y callo,<br>
        Entre lo que callo y sueño,<br>
        Entre lo que sueño y olvido <br>
        La poesía.</p>
        <p><b>La calle</b></p>
        <p>Es una calle larga y silenciosa. <br>
            Ando en tinieblas y tropiezo y caigo <br>
            y me levanto y piso con pies ciegos <br>
            las piedras mudas y las hojas secas <br>
            y alguien detrás de mí también las pisa: <br>
            si me detengo, se detiene; <br>
            si corro, corre. Vuelvo el rostro: nadie.</p>
</body>
</html>


            <!DOCTYPE html>
            <html lang="en">
            <head>
                <meta charset="UTF-8">
                <meta http-equiv="X-UA-Compatible" content="IE=edge">
                <meta name="viewport" content="width=device-width, initial-scale=1.0">
                <title>Evaluacion html</title>
                <link rel="stylesheet" href="css/estilos.css">
                <link rel="preconnect" href="https://fonts.googleapis.com">
            <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
            <link href="https://fonts.googleapis.com/css2?family=Indie+Flower&display=swap" rel="stylesheet">
            </head>
            <body>
                <header>
                    <h1>Encabezado nivel 1</h1>
                    <nav>
                        <ul>
                            <li><a href="">Enlace 1</a></li>
                            <li><a href="">Enlace 2</a></li>
                            <li><a href="">Enlace 3</a></li>
                            <li><a href="">Enlace 4</a></li>
                        </ul>
                    </nav>
                </header>
                <main>
                    <section>
                        <h2>Encabezado nivel 2</h2>
                        <p class="rojo">Aqui va texto del primer <b>parrafo</b></p>
                        <p class="rojo">Aqui va texto del degundo parrafo</p>
                        <aside>
                            <h2>Apartado</h2>
                            <p>Elije una opcion</p>
                            <input type="radio" id="1" name="opc">
                            <label for="1">Opcion 1</label><br>
                            <input type="radio" id="2" name="opc">
                            <label for="2">Opcion 2</label><br>
                            <input type="radio" id="3" name="opc">
                            <label for="3">Opcion 3</label><br><br>
                            <input type="submit" name="enviar" id="env">
                        </aside>
                    </section>
                </main>
                <footer>
                    <p class="rojo">Seccion de informacion de contacto, derechos de autor, etc</p>
                </footer>
            </body>
            </html>


            *{
                margin: 0;
                padding: 0;
            }
            header{
                background: #25171A;
            }
            h1{
                color: #AEDCC0;
                text-align: center;
                font-size: 90px;
                padding: 30px;
                margin-top: 20px;
                margin-left: 50px;
                margin-right: 50px;
                margin-bottom: 20px;
                border: outset 3px orange;
            }
            nav{
                background: #AEDCC0;
            }
            nav a{
                text-decoration: none;
                text-transform: uppercase;
            }
            body{
                background: #518F93;
                font-family: 'Indie Flower', cursive;
            }
            section{
                background: #3091B5;
                text-align: center;
            }
            section h2{
                text-transform: uppercase;
            }
            h2{
                font-size: 3em;
            }
            aside{
                background: #EC2A68;
                text-align: center;
            }
            footer{
                background: #EAD94C;
                text-align: center;
            }
            aside p{
                word-spacing: 10px;
                letter-spacing: 20px;
            }
            .rojo{
                color: red;
                background-color: rgb(85, 77, 77);
            }
