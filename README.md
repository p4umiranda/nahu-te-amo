# <!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>San Valentín 💓</title>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Pacifico&family=Poppins:wght@300;400;600&display=swap');

        body {
            text-align: center;
            font-family: 'Poppins', sans-serif;
            background: linear-gradient(to right, #ff9a9e, #fad0c4);
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
        }
        .container {
            background: white;
            padding: 25px;
            border-radius: 20px;
            box-shadow: 0px 6px 15px rgba(0, 0, 0, 0.2);
            max-width: 90%;
            width: 350px;
            animation: fadeIn 1s ease-in-out;
        }
        @keyframes fadeIn {
            from { opacity: 0; transform: scale(0.9); }
            to { opacity: 1; transform: scale(1); }
        }
        h1 {
            font-size: 26px;
            color: #ff4d6d;
            font-family: 'Pacifico', cursive;
        }
        .heart {
            font-size: 30px;
            color: red;
        }
        .question {
            font-size: 18px;
            margin-top: 10px;
            font-weight: 600;
        }
        .buttons {
            margin-top: 20px;
        }
        button {
            font-size: 18px;
            padding: 12px 20px;
            margin: 8px;
            border: none;
            cursor: pointer;
            border-radius: 15px;
            transition: 0.3s;
            font-weight: 600;
            width: 100px;
        }
        .yes {
            background-color: #ff66b2;
            color: white;
            box-shadow: 0px 4px 10px rgba(255, 102, 178, 0.5);
        }
        .no {
            background-color: #ff4d4d;
            color: white;
            box-shadow: 0px 4px 10px rgba(255, 77, 77, 0.5);
        }
        .yes:hover, .no:hover {
            transform: scale(1.1);
        }
    </style>
</head>
<body>

    <div class="container">
        <h1>Nahuel Ávila <span class="heart">💓</span></h1>
        <p class="question">¿Te gustaría ser mi San Valentín?</p>
        <div class="buttons">
            <button class="yes" onclick="goToNextPage()">Siii 💖</button>
            <button class="no" onclick="showCry()">No 😢</button>
        </div>
    </div>

    <script src="script.js"></script> <!-- Enlace al JavaScript -->
</body>
</html>
