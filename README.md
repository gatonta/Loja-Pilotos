
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Loja</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }
        .container {
            margin-top: 20vh;
        }
        button {
            padding: 10px 20px;
            font-size: 16px;
            background-color: #007bff;
            color: white;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }
        button:hover {
            background-color: #0056b3;
        }
        .content {
            display: none;
            margin-top: 20px;
        }
        .content h2 {
            font-size: 24px;
            color: #333;
        }
        .content p {
            font-size: 18px;
            color: #555;
        }
    </style>
</head>
<body>
    <div class="container">
        <button onclick="showContent()">Entrar</button>
        <div class="content" id="content">
            <p>Pilotos Roleplay</p>
            <h2>O site está sendo programado</h2>
        </div>
    </div>

    <script>
        function showContent() {
            document.getElementById('content').style.display = 'block';
        }
    </script>
</body>
</html>
