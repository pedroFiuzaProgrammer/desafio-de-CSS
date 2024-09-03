<!DOCTYPE html>
<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Landing Page</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <!-- Cabeçalho -->
    <header>
        <div class="container">
            <h1>CreativeWebWorks</h1>
            <nav>
                <ul>
                    <li><a href="#home">Início</a></li>
                    <li><a href="#servicos">Serviços</a></li>
                    <li><a href="#sobre">Sobre</a></li>
                    <li><a href="#contato">Contato</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <!-- Seção Hero -->
    <section id="home" class="hero">
        <img src="https://media.istockphoto.com/id/1504173168/pt/foto/futuristic-energy-sphere-on-black-background-representing-ai-and-future-technologies-3d-design.jpg?s=1024x1024&w=is&k=20&c=jqMy5INfqXTalOdPp0D_2jbd0gpMsVWh4SCGNNsO31g=" alt="Energia Futurista">
        <div class="hero-text">
            <h2>Transforme Seu Negócio com Nossa Ajuda</h2>
            <p>Crie um futuro brilhante com nossos serviços inovadores e expertise em tecnologia.</p>
            <a href="#contato" class="cta-button">Entre em Contato</a>
        </div>
    </section>

    <!-- Seção de Serviços -->
    <section id="servicos">
        <div class="container">
            <h2>Nossos Serviços</h2>
            <div class="services">
                <div class="service">
                    <img src="https://media.istockphoto.com/id/1494206975/pt/foto/close-up-of-a-mans-hands-on-a-laptop-keyboard-concept-of-the-development-applications-of.jpg?s=1024x1024&w=is&k=20&c=B9vlr8se_VOAG31SecX2yn4ybZL6StvU-kBb8GSZdLA=" alt="Desenvolvimento de Aplicações">
                    <h3>Desenvolvimento Web</h3>
                    <p>Criação de sites responsivos e personalizados.</p>
                </div>
                <div class="service">
                    <img src="https://img.freepik.com/fotos-premium/arranque-o-conceito-de-tela-do-laptop-em-fundo-preto_1021632-424.jpg?w=740" alt="Tela de Laptop">
                    <h3>Design Gráfico</h3>
                    <p>Design visual que destaca a identidade da sua marca.</p>
                </div>
                <div class="service">
                    <img src="https://images.pexels.com/photos/4344860/pexels-photo-4344860.jpeg?auto=compress&cs=tinysrgb&w=1260&h=750&dpr=1" alt="Consultoria">
                    <h3>Consultoria</h3>
                    <p>Consultoria especializada para melhorar a presença digital.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Seção Sobre -->
    <section id="sobre">
        <div class="container">
            <h2>Sobre Nós</h2>
            <p>Somos uma empresa especializada em desenvolvimento web e design, oferecendo soluções completas para transformar sua presença online.</p>
            <img src="https://img.freepik.com/premium-photo/people-conference-room-with-blue-screen-that-says-no_984237-30752.jpg?w=360" alt="Reunião em Sala de Conferência">
        </div>
    </section>

    <!-- Seção de Contato -->
    <section id="contato">
        <div class="container">
            <h2>Contato</h2>
            <form action="#">
                <label for="nome">Nome:</label>
                <input type="text" id="nome" name="nome" required>
                
                <label for="email">Email:</label>
                <input type="email" id="email" name="email" required>
                
                <label for="mensagem">Mensagem:</label>
                <textarea id="mensagem" name="mensagem" required></textarea>
                
                <button type="submit">Enviar</button>
            </form>
        </div>
    </section>

    <!-- Rodapé -->
    <footer>
        <div class="container">
            <p>&copy; 2024 Minha Empresa. Todos os direitos reservados.</p>
        </div>
    </footer>
</body>
</html>
-------------------------------------//---------------------------------------------------//----------------------------------------------------------//---------------------

