<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Guia Calouro SI IFAL Arapiraca</title>
    <link href="https://fonts.googleapis.com/css2?family=Press+Start+2P&family=Roboto:wght@300;400;700&family=Aldrich&display=swap" rel="stylesheet">
    <style>
        :root {
            --cor-fundo-dark: #12121F;
            --cor-container-dark: #1A1A2E;
            --cor-texto-principal: #E0E0E0;
            --cor-texto-secundario: #A0A0B0;
            --cor-destaque-neon-ciano: #00FFFF;
            --cor-destaque-neon-magenta: #FF00FF;
            --cor-destaque-neon-verde: #39FF14;
            --cor-ifal-azul-adapt: #2D68A2;
            --cor-ifal-verde-adapt: #38A34A;
            --sombra-neon-suave: 0 0 8px rgba(var(--rgb-destaque-neon-ciano), 0.5), 0 0 12px rgba(var(--rgb-destaque-neon-ciano), 0.3);
            --rgb-destaque-neon-ciano: 0, 255, 255;
            --fonte-pixel: 'Press Start 2P', cursive;
            --fonte-tech: 'Aldrich', sans-serif;
            --fonte-corpo: 'Roboto', sans-serif;
        }

        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
        }

        body {
            font-family: var(--fonte-corpo);
            line-height: 1.7;
            color: var(--cor-texto-principal);
            background-color: var(--cor-fundo-dark);
            overflow-x: hidden;
        }

        h1, h2, h3, h4 {
            font-family: var(--fonte-tech);
            font-weight: 700;
            margin-bottom: 18px;
        }

        h1 { font-size: 2.6em; color: var(--cor-destaque-neon-ciano); text-align: center; text-shadow: 0 0 10px var(--cor-destaque-neon-ciano), 0 0 5px #fff; }
        h2 { font-size: 2em; color: var(--cor-destaque-neon-magenta); border-bottom: 2px solid var(--cor-destaque-neon-magenta); padding-bottom: 10px; margin-top: 50px; }
        h3 { font-size: 1.5em; color: var(--cor-destaque-neon-verde); }
        h4 { font-size: 1.2em; color: var(--cor-destaque-neon-ciano); }

        p { margin-bottom: 15px; font-size: 1em; color: var(--cor-texto-secundario); }
        strong { color: var(--cor-texto-principal); font-weight: 700; }

        a { color: var(--cor-destaque-neon-ciano); text-decoration: none; transition: color 0.3s ease, text-shadow 0.3s ease; }
        a:hover { color: #fff; text-shadow: 0 0 8px var(--cor-destaque-neon-ciano); }

        .container {
            width: 90%;
            max-width: 1200px;
            margin: 0 auto;
            padding: 25px 0;
        }

        header {
            background-color: rgba(26, 26, 46, 0.85);
            backdrop-filter: blur(10px);
            padding: 15px 0;
            position: sticky;
            top: 0;
            z-index: 1000;
            border-bottom: 2px solid var(--cor-destaque-neon-ciano);
            box-shadow: 0 2px 15px rgba(var(--rgb-destaque-neon-ciano), 0.3);
        }

        header .container-header {
            display: flex;
            justify-content: space-between;
            align-items: center;
            width: 90%;
            max-width: 1200px;
            margin: 0 auto;
        }

        header .logo {
            font-family: var(--fonte-pixel);
            font-size: 1.1em;
            color: var(--cor-destaque-neon-verde);
            text-shadow: 0 0 5px var(--cor-destaque-neon-verde);
        }

        header .logo span { color: var(--cor-texto-principal); font-size: 0.9em;}

        nav ul { list-style: none; display: flex; }
        nav ul li { margin-left: 20px; }
        nav ul li a {
            font-family: var(--fonte-tech);
            color: var(--cor-texto-principal);
            font-size: 0.9em;
            padding: 8px 12px;
            border-radius: 4px;
            border: 1px solid transparent;
            transition: all 0.3s ease;
        }

        nav ul li a:hover, nav ul li a.active {
            color: var(--cor-fundo-dark);
            background-color: var(--cor-destaque-neon-ciano);
            border-color: var(--cor-destaque-neon-ciano);
            box-shadow: var(--sombra-neon-suave);
            text-shadow: none;
        }

    </style>
</head>
<body>
    <header>
        <div class="container-header">
            <div class="logo">GUIA SI <span>IFAL ARAPIRACA</span></div>
            <nav>
                <ul>
                    <li><a href="#boas-vindas" class="active">START</a></li>
                    <li><a href="#sobre">SOBRE</a></li>
                    <li><a href="#disciplinas">DISCIPLINAS</a></li>
                    <li><a href="#horario">HORÁRIO</a></li>
                    <li><a href="#dicas">DICAS</a></li>
                </ul>
            </nav>
        </div>
    </header>
</body>
</html>
