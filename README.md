<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Meu Site Pessoal</title>
    <style>
        body {
            font-family: 'Vogue', sans-serif;
            background-color: #fff;
            color: #333;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #ff9900;
            color: white;
            text-align: center;
            padding: 1em 0;
        }
        nav {
            display: flex;
            justify-content: center;
            gap: 1em;
            background-color: #333;
            padding: 1em 0;
        }
        nav a {
            color: white;
            text-decoration: none;
        }
        section {
            padding: 2em;
            max-width: 800px;
            margin: auto;
        }
        h1, h2 {
            color: #ff9900;
        }
        .photo, .video {
            text-align: center;
            margin: 2em 0;
        }
        .photo img, .video iframe {
            max-width: 100%;
            height: auto;
        }
        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 1em 0;
            margin-top: 2em;
        }
        .social-links a {
            margin: 0 1em;
            color: #ff9900;
            text-decoration: none;
        }
    </style>
</head>
<body>
    <header>
        <h1>Meu Site Pessoal</h1>
    </header>
    <nav>
        <a href="#experiencia">Experiência Profissional</a>
        <a href="#projetos">Projetos</a>
    </nav>
    <section id="experiencia">
        <h2>Experiência Profissional</h2>
        <p>Aqui você pode listar sua experiência profissional, incluindo detalhes sobre suas responsabilidades, realizações e os cargos que ocupou.</p>
    </section>
    <section id="projetos">
        <h2>Projetos</h2>
        <p>Aqui você pode descrever alguns dos seus projetos mais importantes, incluindo o que foi feito, as tecnologias usadas e os resultados alcançados.</p>
    </section>
    <div class="photo">
        <h2>Fotos</h2>
        <img src="sua_foto.jpg" alt="Uma foto sua">
    </div>
    <div class="video">
        <h2>Vídeo</h2>
        <iframe width="560" height="315" src="https://www.youtube.com/embed/seu_video_id" frameborder="0" allow="accelerometer; autoplay;
