![image](https://user-images.githubusercontent.com/91554777/170103427-2b681a6e-05b6-49f3-834b-c188ebf12fbb.png)

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <h1>Formato de registro</h1>
    <form action="https://formspree.io/f/xrgjjerz" method="post">
        <fieldset>
            <legend>Informacion personal del usuario</legend>
            Introduce tu nombre completo <br>
            <input type="text" name="nombre"><br>
            Introduce tu email <br>
            <input type="email" name="correo"><br>
            introduce tu contraseña <br>
            <input type="password" name="pass"><br><br>
            Genero <br>
            <input type="radio" name="genero" id="gen" value="mas">
            <label for="gen">Masculino</label><br>
            <input type="radio" name="genero" id="gen" value="fem">
            <label for="gen">Femenino</label><br>
            <input type="radio" name="genero" id="gen" value="otro">
            <label for="gen">Otro</label><br><br>
            Introduce tu direccion <br>
            <textarea name="direccion" id="dir" cols="30" rows="5"></textarea><br>
            <input type="submit" name="enviar" id="rg" value="Registrarse">
        </fieldset>
    </form>
</body>
</html>
