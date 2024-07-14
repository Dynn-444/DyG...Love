<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Felices 3 Meses, Mi Cielo</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #fce4ec;
            color: #880e4f;
            margin: 0;
            padding: 0;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            flex-direction: column;
        }
        .message, .question, .content {
            text-align: center;
            margin: 20px;
        }
        .buttons button {
            background-color: #880e4f;
            color: #fff;
            border: none;
            padding: 10px 20px;
            margin: 10px;
            font-size: 1.2em;
            cursor: pointer;
            border-radius: 5px;
        }
        .buttons button:disabled {
            background-color: #ccc;
            cursor: not-allowed;
        }
        .hidden {
            display: none;
        }
        .photo-gallery {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
        }
        .photo-gallery img {
            margin: 10px;
            width: 200px;
            height: 200px;
            object-fit: cover;
            border-radius: 10px;
        }
        .message-text {
            font-size: 1.2em;
            margin: 20px auto;
            max-width: 600px;
            line-height: 1.6em;
        }
        .footer {
            text-align: center;
            padding: 20px;
            background-color: #f8bbd0;
        }
    </style>
</head>
<body>
    <div class="message">
        <h1>Felices 3 Meses, Mi Cielo</h1>
        <button onclick="showQuestion()">Toca aquí</button>
    </div>
    <div class="question hidden">
        <h2>¿Me amas?</h2>
        <div class="buttons">
            <button onclick="showRomanticPage()">Sí</button>
            <button disabled>No</button>
        </div>
    </div>

    <div class="content hidden">
        <div class="header">
            <h1>Feliz Tercer Mes, Genesis</h1>
            <p>Cada día contigo es un regalo</p>
        </div>
        <div class="message-text">
           <p> Eres la persona más especial para mi, eres mi persona favorita. Estos tres meses han sido los más maravillosos de mi vida, y no puedo esperar para ver lo que nos depara el futuro. Ame tanto irte a ver, es nuestra primer foto solo de las 2, mi foto favorita con mi persona favorita, hay una cartita tmb que hice para ti, vita mia.</p>
        </div>
        <div class="photo-gallery">
            <img src=""C:\Users\Admin2022\Downloads\449411175_496757002787787_5888737376841214261_n.jpg"" alt="My favorite photo">
            <img src=""C:\Users\Admin2022\Downloads\loveee.jpeg"" alt="For my love">
        </div>
        <div class="message-text">
            <p>Te amo con todo mi corazón, Genesis. Eres mi inspiración, mi confidente y mi amor eterno. Feliz tercer mes, mi vida.</p>
        </div>
        <div class="footer">
            <p>Con amor, Dayanna</p>
        </div>
    </div>

    <script>
        function showQuestion() {
            document.querySelector('.message').style.display = 'none';
            document.querySelector('.question').classList.remove('hidden');
        }

        function showRomanticPage() {
            document.querySelector('.question').style.display = 'none';
            document.querySelector('.content').classList.remove('hidden');
        }
    </script>
</body>
</html>

            
           
        
