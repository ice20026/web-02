# web-02

<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Imagen de Fondo</title>
    <style>
        body {
            background-image: url('fondo n1.jpg'); /* Imagen de fondo */
            background-size: cover; /* Ajusta la imagen para cubrir toda la pantalla */
            background-position: center; /* Centra la imagen */
            background-repeat: no-repeat; /* Evita que la imagen se repita */
            margin: 0;
            font-family: Arial, sans-serif;
        }
    </style>
</head>
<body>
    <h1></h1>
    <p></p>
</body>
</html>



<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mensaje a WhatsApp</title>
    <style>
        .whatsapp-link {
            display: inline-block;
            font-size: 16px;
            padding: 10px 20px;
            color: white;
            background-color: #25D366; /* Color de WhatsApp */
            border: none;
            border-radius: 5px;
            text-decoration: none; /* Quitar subrayado del enlace */
            text-align: center;
            cursor: pointer;
        }
        .whatsapp-link:hover {
            background-color: #1EBE51; /* Color al pasar el ratón */
        }
    </style>
</head>
<body>
    <a href="https://wa.me/88034121?text=Hola%20¿cómo%20estás?" class="whatsapp-link" target="_blank">Enviar Mensaje</a>
</body>
</html>
