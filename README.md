<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <title>Página Interativa do Projeto</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f0f0f0;
        }

        header {
            background-color: #333;
            color: white;
            padding: 15px;
            text-align: center;
        }

        nav ul {
            list-style-type: none;
            padding: 0;
        }

        nav ul li {
            display: inline;
            margin: 0 10px;
        }

        nav ul li a {
            color: white;
            text-decoration: none;
        }

        main {
            padding: 20px;
        }

        .card {
            background-color: white;
            border-radius: 5px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            margin: 10px;
            padding: 15px;
        }

        .card:hover {
            background-color: #f9f9f9;
        }

        footer {
            background-color: #333;
            color: white;
            text-align: center;
            padding: 10px;
            position: fixed;
            bottom: 0;
            width: 100%;
        }

        .button {
            display: inline-block;
            background-color: #333;
            color: white;
            padding: 10px 20px;
            text-align: center;
            text-decoration: none;
            border-radius: 5px;
            margin-top: 10px;
        }

        .button:hover {
            background-color: #555;
        }
    </style>
</head>
<body>

    <header>
        <h1>Página Interativa do Projeto</h1>
        <nav>
            <ul>
                <li><a href="#services">Serviços</a></li>
                <li><a href="#team">Equipe</a></li>
                <li><a href="#contact">Contato</a></li>
            </ul>
        </nav>
    </header>

    <main>
        <section id="services">
            <h2>Nossos Serviços</h2>
            <div class="card">
                <h3>Serviço 1</h3>
                <p>Descrição detalhada do serviço 1. Explicando como ele pode ajudar os usuários.</p>
                <a href="#" class="button">Saiba mais</a>
            </div>

            <div class="card">
                <h3>Serviço 2</h3>
                <p>Descrição detalhada do serviço 2. Inclua informações que atraiam a atenção dos visitantes.</p>
                <a href="#" class="button">Saiba mais</a>
            </div>

            <div class="card">
                <h3>Serviço 3</h3>
                <p>Descrição detalhada do serviço 3. Destaque seus benefícios e características.</p>
                <a href="#" class="button">Saiba mais</a>
            </div>
        </section>

        <section id="team">
            <h2>Conheça Nossa Equipe</h2>
            <div class="card">
                <h3>Nome do Membro</h3>
                <p>Cargo e uma breve descrição do que este membro faz na equipe.</p>
            </div>

            <div class="card">
                <h3>Nome do Membro 2</h3>
                <p>Cargo e descrição do papel deste membro na equipe.</p>
            </div>
        </section>
    </main>

    <footer id="contact">
        <p>Entre em contato: <a href="mailto:seu-email@exemplo.com">seu-email@exemplo.com</a></p>
        <p>&copy; 2024 Seu Projeto</p>
    </footer>

</body>
</html>
