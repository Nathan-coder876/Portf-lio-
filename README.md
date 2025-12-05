# Portf-lio-
<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portfólio de Desenvolvedor de Jogos</title>
    <style>
        :root {
            --bg-color: #121212;
            --card-bg: #1e1e1e;
            --text-color: #e0e0e0;
            --accent-color: #00ff88; /* Verde Neon */
            --secondary-color: #bb86fc;
        }

        body {
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
            background-color: var(--bg-color);
            color: var(--text-color);
            margin: 0;
            line-height: 1.6;
        }

        header {
            background: linear-gradient(180deg, rgba(0,0,0,0.8) 0%, rgba(18,18,18,1) 100%);
            padding: 4rem 2rem;
            text-align: center;
            border-bottom: 2px solid var(--accent-color);
        }

        h1 { margin: 0; font-size: 2.5rem; color: var(--accent-color); text-transform: uppercase; letter-spacing: 2px; }
        h2 { border-left: 4px solid var(--accent-color); padding-left: 10px; margin-top: 3rem; }
        p.subtitle { font-size: 1.2rem; color: #a0a0a0; }

        .container { max-width: 1000px; margin: 0 auto; padding: 20px; }

        /* Grid de Projetos */
        .projects-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 20px;
        }

        .project-card {
            background-color: var(--card-bg);
            border-radius: 8px;
            overflow: hidden;
            transition: transform 0.3s ease;
            box-shadow: 0 4px 6px rgba(0,0,0,0.3);
        }

        .project-card:hover { transform: translateY(-5px); border: 1px solid var(--accent-color); }

        .project-img {
            width: 100%;
            height: 180px;
            background-color: #333;
            display: flex;
            align-items: center;
            justify-content: center;
            color: #555;
        }

        .card-content { padding: 15px; }
        .card-title { font-size: 1.4rem; color: var(--accent-color); margin-bottom: 0.5rem; display: block; text-decoration: none; }
        .tech-stack { font-size: 0.85rem; color: var(--secondary-color); margin-bottom: 10px; font-weight: bold; }

        .btn {
            display: inline-block;
            padding: 8px 16px;
            background-color: transparent;
            border: 1px solid var(--accent-color);
            color: var(--accent-color);
            text-decoration: none;
            border-radius: 4px;
            margin-top: 10px;
            transition: background 0.3s;
        }

        .btn:hover { background-color: var(--accent-color); color: #000; }

        footer { text-align: center; padding: 2rem; margin-top: 3rem; font-size: 0.9rem; color: #666; }
    </style>
</head>
<body>

<header>
    <h1>[Seu Nome Aqui]</h1>
    <p class="subtitle">Desenvolvedor de Jogos | Estudante de ADS</p>
    <p>Unity / C# / Godot / C++</p> </header>

<div class="container">

    <section id="sobre">
        <h2>Sobre Mim</h2>
        <p>Olá! Sou estudante de Análise e Desenvolvimento de Sistemas apaixonado por criar mundos virtuais. Meu foco é em programação de gameplay e inteligência artificial para jogos. Estou sempre buscando aprender novas engines e otimização de código.</p>
    </section>

    <section id="portfolio">
        <h2>Meus Projetos</h2>
        <div class="projects-grid">
            
            <div class="project-card">
                <div class="project-img">[Print do Jogo]</div>
                <div class="card-content">
                    <a href="#" class="card-title">Nome do Jogo 1</a>
                    <div class="tech-stack">Unity • C# • Pixel Art</div>
                    <p>Um jogo de plataforma 2D onde o tempo só se move quando você se move. Foco em mecânicas de física.</p>
                    <a href="#" class="btn">Ver no GitHub</a>
                    <a href="#" class="btn">Jogar no Itch.io</a>
                </div>
            </div>

            <div class="project-card">
                <div class="project-img">[Print do Jogo]</div>
                <div class="card-content">
                    <a href="#" class="card-title">Clone do Pong</a>
                    <div class="tech-stack">Godot • GDScript</div>
                    <p>Recriação do clássico Pong para estudo de vetores, input de usuário e colisão básica.</p>
                    <a href="#" class="btn">Ver no GitHub</a>
                </div>
            </div>

            <div class="project-card">
                <div class="project-img">[Print do Jogo]</div>
                <div class="card-content">
                    <a href="#" class="card-title">Endless Runner</a>
                    <div class="tech-stack">C++ • SDL2</div>
                    <p>Jogo de corrida infinita criado do zero sem engine, para entender como funciona um Game Loop.</p>
                    <a href="#" class="btn">Ver no GitHub</a>
                </div>
            </div>

        </div>
    </section>

    <section id="contato">
        <h2>Contato</h2>
        <p>Vamos trabalhar juntos? Entre em contato:</p>
        <p>Email: seu.email@exemplo.com | <a href="#" style="color:var(--accent-color)">LinkedIn</a> | <a href="#" style="color:var(--accent-color)">GitHub</a></p>
    </section>

</div>

<footer>
    &copy; 2024 [Seu Nome]. Feito com código e café.
</footer>

</body>
</html>
