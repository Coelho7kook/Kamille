# Kamille


<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Para Kamille</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            background-color: #f7e8e8;
            color: #333;
            margin: 0;
            padding: 0;
            text-align: center;
        }
        header {
            background-color: #ffcccc;
            padding: 20px;
            border-bottom: 2px solid #ff9999;
        }
        header h1 {
            font-size: 3em;
            margin: 0;
            color: #ff6666;
        }
        .content {
            padding: 20px;
        }
        .content p {
            font-size: 1.2em;
            margin: 20px 0;
        }
        .poem {
            font-size: 1.4em;
            margin: 30px 0;
            color: #b30000;
            font-style: italic;
        }
        .content img {
            max-width: 100%;
            height: auto;
            border-radius: 10px;
        }
        .footer {
            background-color: #ffcccc;
            padding: 10px;
            border-top: 2px solid #ff9999;
        }
        .footer p {
            margin: 0;
            color: #ff6666;
            font-weight: bold;
        }
        .heart {
            color: #ff6666;
            font-size: 1.5em;
        }
        .hidden-video {
            display: none;
        }
    </style>
</head>
<body>
    <header>
        <h1>Para Kamille</h1>
    </header>
    <div class="content">
        <p>Kamille, minha amada, você é a pessoa mais especial e incrível da minha vida. Te amo mais do que palavras podem expressar!</p>
        <div class="poem">
            <p>Na escuridão da noite, o brilho do seu olhar,</p>
            <p>Uma chama intensa que me faz sonhar.</p>
            <p>No silêncio do meu quarto, sinto seu desejo,</p>
            <p>Um amor que atravessa telas, cheio de ensejo.</p>
            <p>Seus suspiros virtuais, um convite ao prazer,</p>
            <p>Em cada mensagem, o desejo de te ter.</p>
            <p>Seu toque invisível, arrepio digital,</p>
            <p>Em cada palavra, um desejo carnal.</p>
            <p>Nos encontros secretos, na tela de um celular,</p>
            <p>Sinto seu corpo, sua alma a me tocar.</p>
            <p>Um amor sem limites, além do que posso ver,</p>
            <p>Você é meu desejo, minha vontade de viver.</p>
            <p>Em noites solitárias, sua presença me aquece,</p>
            <p>Nos sonhos, nossos corpos, em um só, se entrelaçam.</p>
            <p>Melancolia e paixão, misturam-se em meu ser,</p>
            <p>Kamille, minha amada, quero eternamente te ter.</p>
            <p>Seu sorriso, seu olhar, sua voz a me chamar,</p>
            <p>Um amor virtual, mas real ao me tocar.</p>
            <p>Seu cheiro, seu gosto, ainda que na mente,</p>
            <p>Me levam a loucura, um prazer sempre crescente.</p>
            <p>Kamille, minha musa, meu desejo insaciável,</p>
            <p>Em seus braços virtuais, encontro o inefável.</p>
            <p>Nosso amor é um segredo, um desejo a se revelar,</p>
            <p>Na melancolia da espera, meu coração a pulsar.</p>
            <p>Te amo, Kamille, além do que palavras podem dizer,</p>
            <p>Em um mundo virtual, meu desejo é te ter.</p>
        </div>
        <img src="image.jpg" alt="Imagem romântica">
        <p>Kamille, você é meu sonho, minha realidade. Te amo imensamente!</p>
        <p class="heart">❤</p>
    </div>
    <div class="footer">
        <p>Com todo meu amor, [Seu Nome]</p>
    </div>
    <div id="player" class="hidden-video"></div>

    <script>
        var tag = document.createElement('script');
        tag.src = "https://www.youtube.com/iframe_api";
        var firstScriptTag = document.getElementsByTagName('script')[0];
        firstScriptTag.parentNode.insertBefore(tag, firstScriptTag);

        var player;
        function onYouTubeIframeAPIReady() {
            player = new YT.Player('player', {
                height: '0',
                width: '0',
                videoId: 'TJ5XsyPOv0o',
                playerVars: {
                    'autoplay': 1,
                    'loop': 1,
                    'playlist': 'TJ5XsyPOv0o'
                },
                events: {
                    'onReady': onPlayerReady
                }
            });
        }

        function onPlayerReady(event) {
            event.target.playVideo();
        }
    </script>
</body>
</html>
