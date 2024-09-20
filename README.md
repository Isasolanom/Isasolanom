<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Protección por Contraseña</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
            background-color: #f0f0f0;
        }
        .login-container {
            background-color: #fff;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0,0,0,0.1);
            text-align: center;
        }
        label {
            display: block;
            margin-bottom: 5px;
        }
        input {
            width: 100%;
            padding: 8px;
            margin-bottom: 10px;
            border: 1px solid #ccc;
            border-radius: 4px;
        }
        button {
            padding: 10px;
            border: none;
            background-color: #28a745;
            color: #fff;
            border-radius: 4px;
            cursor: pointer;
        }
        button:hover {
            background-color: #218838;
        }
        #error-message {
            color: red;
        }
        #protected-content {
            display: none;
        }
    </style>
</head>
<body>
    <div class="login-container" id="login-container">
        <h2>Iniciar Sesión</h2>
        <form id="login-form">
            <label for="password">Contraseña:</label>
            <input type="password" id="password" required>
            <button type="submit">Acceder</button>
        </form>
        <p id="error-message"></p>
    </div>
    <div id="protected-content">
        <h1>Contenido Protegido</h1>
        <p>Bienvenido a la sección protegida.

	</p>
	<a href="https://66e3a052a4d2977f1788f8f2--enchanting-yeot-1efe9b.netlify.app/" 
        <a href="https://66e3a0c2dfff057b4dea9ce6--effulgent-strudel-153f15.netlify.app/" 
        <a href="https://66e3a18c79760582d4013842--comforting-starburst-4b8335.netlify.app/"  
        <a href="https://66e3a202a788ca864349080d--dynamic-bavarois-2fb8fc.netlify.app/" 
	<a href="https://66e3a38cfc0ec682c04fef25--lighthearted-cranachan-a39e4c.netlify.app/"
        <p>


    </div>
    <script>
        document.getElementById('login-form').addEventListener('submit', function(event) {
            event.preventDefault();

            const password = document.getElementById('password').value;
            const correctPassword = '200807 // Cambia esto por la contraseña que desees

            if (password === correctPassword) {
                document.getElementById('login-container').style.display = 'none';
                document.getElementById('protected-content').style.display = 'block';
            } else {
                document.getElementById('error-message').textContent = 'Contraseña incorrecta';
            }
        });
    </script>
</body>
</html>
