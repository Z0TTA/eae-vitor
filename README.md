<!DOCTYPE html>
<html lang="pt-br">
<head>
    <title>ola, mundo!</title>
    <!-- Google Fonts para títulos e textos -->
    <link href="https://fonts.googleapis.com/css?family=Montserrat:700|Roboto:400&display=swap" rel="stylesheet">
    <style>
        body {
            margin: 0;
            padding: 0;
            min-height: 100vh;
            background: linear-gradient(135deg, #a8edea, #fed6e3);
            display: flex;
            justify-content: center;
            align-items: center;
        }
        .container {
            background: rgb(255, 255, 255);
            padding: 40px 30px;
            border-radius: 30px;
            box-shadow: 0 25px 22px 0 rgba(70, 80, 228, 0.37);
            text-align: center;
            max-width: 400px;
        }
        .profile-img {
            width: 120px;
            height: 120px;
            object-fit: cover;
            border-radius: 50%;
            border: 4px solid #00aeff;
            margin-bottom: 20px;
        }
        h1 {
            color: rgb(0, 89, 255);
            font-size: 30pt;
            font-family: 'Montserrat', Arial, sans-serif;
            text-shadow: 2px 2px 3px black;
            position: relative;
            overflow: hidden;
        }
        h1::after {
            content: '';
            position: absolute;
            top: 0; left: -75%;
            width: 50%;
            height: 100%;
            background: linear-gradient(120deg, transparent, rgba(255,255,255,0.6), transparent);
            animation: brilho 2s infinite;
        }
        @keyframes brilho {
            0% { left: -75%; }
            100% { left: 125%; }
        }
        h2 {
            color: rgb(0, 174, 255);
            font-size: 18pt;
            font-family: 'Montserrat', Arial, sans-serif;
            text-shadow: 1px 1px 2px black;
        }
        p {
            color: rgb(1, 7, 7);
            font-size: 12pt;        
            font-family: 'Roboto', Arial, sans-serif;
        }
        .citacao {
            font-style: italic;
            color: #0074d9;
            background: #e3f6fd;
            border-left: 5px solid #00aeff;
            margin: 20px 0;
            padding: 10px 20px;
            border-radius: 10px;
        }
        .btn-homenagem {
            background: linear-gradient(90deg, #00aeff, #a8edea);
            color: #fff;
            border: none;
            padding: 12px 30px;
            border-radius: 30px;
            font-size: 16px;
            font-family: 'Montserrat', Arial, sans-serif;
            cursor: pointer;
            box-shadow: 0 4px 14px rgba(0,174,255,0.2);
            transition: transform 0.2s, box-shadow 0.2s;
            margin-top: 20px;
        }
        .btn-homenagem:hover {
            transform: scale(1.05);
            box-shadow: 0 8px 24px rgba(0,174,255,0.3);
        }
        .rodape {
            margin-top: 30px;
            text-align: center;
            color: #fff;
            font-size: 14px;
            text-shadow: 1px 1px 2px #0074d9;
        }
    </style>
</head>
<body>
    <div class="container">
        <img src="foto do viado.jpg" alt="Foto do Vitor" class="profile-img">
        <h1>EAE BIXA, ME ABANDONOU NO VALORANT</h1>
        <h2>BIXA DO PLATINA</h2>
        <blockquote class="citacao">"mlk se vc n pegar platina 2 ate sabado, te mando 5 therians na sua casa"</blockquote>
        <p>leumedeu</p>
        <p>ASS: MATHEUSPIKADASGALAXIAS</p>
        <button class="btn-homenagem">clique para receber o gorro rs</button>
    </div>
    <footer class="rodape">
        Feito com ❤️ para o meu therian favorito!
    </footer>
</body>
</html>
