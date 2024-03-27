<!DOCTYPE html>
<html lang="pt-br">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Carta de Aniversário de Namoro</title>
<style>
    body {
        font-family: Arial, sans-serif;
        text-align: center;
        background-color: #f8f8f8;
    }
    .card {
        margin: 50px auto;
        padding: 20px;
        max-width: 80%;
        border-radius: 15px;
        background: linear-gradient(45deg, #ff9999, #ff6666);
        box-shadow: 0px 0px 15px rgba(0, 0, 0, 0.1);
    }
    .hearts {
        font-size: 10vw;
        color: red;
        margin-bottom: 20px;
        display: flex;
        justify-content: center;
        animation: pulseHearts 2s infinite alternate;
    }
    .heart {
        font-size: 5vw;
        color: white;
        background-color: red;
        padding: 10px;
        border-radius: 50%;
        display: inline-block;
        margin-top: 20px;
        animation: pulseHeart 2s infinite alternate;
    }
    .heart:nth-child(2) {
        animation-delay: 0.5s;
    }
    .heart:nth-child(3) {
        animation-delay: 1s;
    }
    #revealButton {
        background-color: #ff6666;
        color: white;
        font-size: 2vw;
        padding: 10px 20px;
        border: none;
        border-radius: 5px;
        cursor: pointer;
        transition: background-color 0.3s ease;
    }
    #revealButton:hover {
        background-color: #ff4d4d;
    }
    #message {
        display: none;
        margin-top: 20px;
        color: #333;
    }
    #message p {
        font-size: 3vw;
        margin-bottom: 10px;
    }
    #thankYouMessage {
        display: none;
        font-size: 3vw;
        color: darkred;
        margin-top: 20px;
    }
    @keyframes pulseHearts {
        from {
            transform: scale(1);
        }
        to {
            transform: scale(1.1);
        }
    }
    @keyframes pulseHeart {
        from {
            transform: scale(1);
        }
        to {
            transform: scale(1.2);
        }
    }
</style>
</head>
<body>
    <div class="card">
        <div class="hearts">
            <div class="heart">&#10084;&#65039;</div>
            <div class="heart">&#10084;&#65039;</div>
            <div class="heart">&#10084;&#65039;</div>
        </div>
        <div>
            <span style="font-size: 3vw; color: white; margin-top: 10px;">&#10084;&#65039;<span style="font-weight: bold; color: #ff0000;">BRENDA</span>&#10084;&#65039;</span>
        </div>
        <button id="revealButton">Clique aqui</button>
        <div id="message">
            <p>Oi meu amor,</p>
            <!-- Conteúdo da carta aqui -->
        </div>
        <div id="thankYouMessage">Hoje celebramos dois anos incríveis juntos! É incrível como o tempo voou desde o nosso primeiro encontro, todo aquele frio na barriga e nervosismo para o primeiro encontro, vivendo tudo que há um ano atrás ficava sonhando em fazer contigo, mas sempre soube que realmente era você. Cada momento ao seu lado tem sido especial e cheio de amor, sentindo e vivendo coisas que jamais imaginei viver um dia.
        
</p>

        <div>Você é a minha felicidade, minha paz e toda minha motivação para cada dia passado, é um prazer enorme ter alguém como você ao meu lado e poder compartilhar de tudo em todos os momentos.
        
</p>

        <div>Que este seja apenas o começo de uma jornada ainda mais bonita e cheia de momentos inesquecíveis, que papai do céu nos abençoe cada vez mais e faça durar nossa relação por toda vida, pois você é a pessoa que quero comigo para sempre. Estou muito feliz por ter você ao meu lado.
        
</p>

        <div>❤️EU TE AMOOOOOO XUXUUUU!!! ❤️
      
  </p>

        <div>Com todo o meu amor,</p>

        <div>Brayan, ou melhor, BRIANNNN</p>
    </div>

    <script>
        const revealButton = document.getElementById('revealButton');
        const message = document.getElementById('message');
        const thankYouMessage = document.getElementById('thankYouMessage');

        revealButton.addEventListener('click', function() {
            message.style.display = 'block';
            thankYouMessage.style.display = 'block';
            revealButton.style.display = 'none';
        });
    </script>
</body>
</html>
