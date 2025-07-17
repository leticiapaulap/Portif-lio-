# Portifolio





<!DOCTYPE html>
<html lang="pt-br">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="icon" href="./assets/Avatar-Lucas.png" type="image/x-icon">
    <link rel="stylesheet" href="style.css">
    <title>Lucas Albuquerque - Portifólio</title>
</head>

<body>

    <nav class="navegacao">
        <ul class="menu">
            <li>
                <a href="#inicio">Inicio</a>
            </li>
            <li>
                <a href="#sobre">Sobre</a>
            </li>
            <li>
                <a href="#Tecnologias">Tecnologias</a>
            </li>
            <li>
                <a href="#projetos">Projetos</a>
            </li>
            <li>
                <a href="#contatos">Contato</a>
            </li>
        </ul>
    </nav>

    <main id="inicio" class="header">

        <div>
            <img src="./assets/Avatar-Lucas.png" alt="Avatar do Lucas" class="foto-perfil">
            <h1>Lucas Albuquerque</h1>
            <p>Programador Front-End</p>
        </div>

    </main>

    <section id="sobre" class="sobre">
        <h2 class="sobre-titulo">Sobre Mim</h2>
        <div class="sobre-caixa">
            <p class="sobre-paragrafo">Olá! Eu sou Lucas Albuquerque, um desenvolvedor front-end apaixonado por
                tecnologia e inovação. Meu
                principal objetivo é aprofundar ainda mais meus conhecimentos, trazendo minha paixão e habilidades para
                contribuir com projetos dinâmicos e inovadores. Minha experiência anterior como gestor de tráfego pago
                me proporcionou uma visão analítica aguçada, essencial para a análise de dados e tomada de decisões
                baseadas em métricas. Essa experiência complementa minhas habilidades técnicas e me permite abordar
                problemas com um olhar estratégico.</p>
        </div>
    </section>

    <section id="tecnologias" class="tecnologias">
        <h2 class="tecnologias-titulo">Tecnologias & Ferramentas</h2>
        <p class="tecnologias-descricao">Principais tecnologias que utilizo no desenvolvimento</p>

        <div class="tecnologias-container">
            <div class="tech-card" style="--delay: 0.2s;">
                <img src="./assets/logo-html-5.png" alt="Logo HTML5">
                <h3>HTML5</h3>
                <p>Estruturação semântica e moderna</p>
            </div>

            <div class="tech-card" style="--delay: 0.4s;">
                <img src="./assets/logo-css-3.png" alt="Logo CSS">
                <h3>CSS3</h3>
                <p>Estilização avançada e responsiva</p>
            </div>

            <div class="tech-card" style="--delay: 0.6s;">
                <img src="./assets/logo-javascript.png" alt="Logo JavaScript">
                <h3>JavaScript</h3>
                <p>Linguagem dinâmica para web</p>
            </div>

            <div class="tech-card" style="--delay: 1.4s;">
                <img src="./assets/github-2.png" alt="Logo GitHub">
                <h3>GitHub</h3>
                <p>Repositórios e projetos open source</p>
            </div>

            <div class="tech-card" style="--delay: 1.8s;">
                <img src="./assets/chat-gpt.png" alt="Logo ChatGPT">
                <h3>ChatGPT</h3>
                <p>Integração com inteligência artificial</p>
            </div>
        </div>
    </section>

    <section id="projetos" class="projetos">
        <h2 class="projetos-titulo">Principais Projetos</h2>
        <div class="projetos-caixa">

            <!-- <div class="projetos-card">
                <img src="./assets/Animacoes-CSS.png" alt="Foto Site IA que cria animações para o CSS"
                    class="projetos-imagem">
                <h3 class="info-projetos">Gerador de Animações CSS com IA</h3>
                <p class="paragrafo-projetos">Workflow automatizado criado com n8n + Inteligência Artificial para gerar
                    códigos de animações CSS
                    prontos para uso em interfaces modernas.</p>  
                    cod acima caso eu adicione algum card de projetos que realizei
                    -->
            

        </div>
    </section>

    <section id="contatos" class="contatos">
        <h2 class="contato-titulos">Entre em Contato</h2>
        <form class="formulario-contato" id="formulario" onsubmit="enviarWhats(event)">
            <div class="nome-form">
                <input placeholder="Nome" class="campo-form" id="nome">
            </div>

            <div class="grupo form">
                <textarea placeholder="Digite sua Mensagem..." class="campo-form" id="mensagem" rows="6"></textarea>
            </div>
            <button type="submit" class="botao-form">Enviar WhatsApp</button>
        </form>
    </section>

</body>

<script src="./script.js"></script>

</html>
