💘💘💘
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mi página de San Valentín</title>
    <style>
        body {
            font-family: 'Poppins', sans-serif;
            background: linear-gradient(to right, #ff9a9e, #fad0c4);
            height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;
            text-align: center;
        }

        .yes, .no {
            padding: 10px 20px;
            margin: 10px;
            font-size: 20px;
            cursor: pointer;
            border: none;
            border-radius: 5px;
            background-color: #ff66b2;
            color: white;
            transition: transform 0.3s;
        }

        .yes:hover, .no:hover {
            transform: scale(1.1);
        }

        h1 {
            font-family: 'Pacifico', cursive;
            color: #ff3399;
        }

        .yes {
            background-color: #66ff66;
        }

        .no {
            background-color: #ff6666;
        }
    </style>
</head>
<body>
    <div>
        <h1>¿Te gustaría ser mi San Valentín? 💓</h1>
        <button class="yes" onclick="goToNextPage()">Síii</button>
        <button class="no" onclick="showCry()">No</button>
    </div>

    <script>
        function showCry() {
            alert("😭");
            document.querySelector(".yes").style.transform = "scale(1.4)";
        }

        function goToNextPage() {
            document.body.innerHTML = `
                <div style="text-align:center; font-family: 'Poppins', sans-serif; background: linear-gradient(to right, #ff9a9e, #fad0c4); height:100vh; display:flex; flex-direction:column; justify-content:center; align-items:center;">
                    <h1 style="font-size: 40px; color: #ff3399; font-family: 'Pacifico', cursive; animation: fadeIn 1s ease-in-out;">Gracias Amor 💕</h1>
                    <p style="font-size: 22px; color: #ff66b2;">Va a ser el mejor San Valentín, te amooo muchoo 💘</p>
                </div>`;
        }
    </script>
</body>
</html>
