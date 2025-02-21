<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Buzón de Sugerencias - Dulce Lettas</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            background-color: #f8d8e8;
            color: #333;
            text-align: center;
            padding: 20px;
        }
        h1 {
            font-size: 2.5em;
            color: #d64e9c;
        }
        .logo {
            width: 200px;
        }
        .suggestion-box {
            background-color: #ffffff;
            border-radius: 10px;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
            padding: 20px;
            margin: 20px auto;
            width: 90%;
            max-width: 400px;
        }
        input, textarea {
            width: 100%;
            padding: 10px;
            margin: 10px 0;
            border: 1px solid #d64e9c;
            border-radius: 5px;
        }
        button {
            background-color: #d64e9c;
            color: white;
            padding: 10px;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }
        button:hover {
            background-color: #c43d7a;
        }
    </style>
</head>
<body>

    <h1>Dulce Lettas</h1>
    <img src="https://pfst.cf2.poecdn.net/base/image/899ba8535a1a8fcbcc8eb98183de423d4148ea239b613653ca770c7cc590b0e1?w=1024&h=768&pmaid=294866906" alt="Logo Dulce Lettas" class="logo">

    <div class="suggestion-box">
        <h2>Sugerencias</h2>
        <form>
            <input type="text" name="name" placeholder="Nombre" required>
            <input type="email" name="email" placeholder="Email" required>
            <textarea name="message" placeholder="Tu sugerencia..." rows="4" required></textarea>
            <button type="submit">Enviar Sugerencia</button>
        </form>
    </div>

</body>
</html>
