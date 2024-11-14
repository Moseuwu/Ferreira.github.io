<!DOCTYPE html>
<html lang="pt">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Apresentação de Jhuan - Programador</title>
    <style>
        /* Reset básico */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        /* Corpo da página */
        body {
            font-family: 'Arial', sans-serif;
            background-color: #f4f4f4;
            color: #333;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            padding: 20px;
        }

        /* Container principal */
        .container {
            background-color: #fff;
            max-width: 800px;
            width: 100%;
            padding: 30px;
            border-radius: 15px;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
        }

        /* Cabeçalho */
        header {
            text-align: center;
            margin-bottom: 30px;
        }

        header h1 {
            font-size: 36px;
            color: #007bff;
        }

        header p {
            font-size: 18px;
            color: #555;
        }

        /* Seção de introdução */
        .intro {
            display: flex;
            align-items: center;
            gap: 20px;
            flex-wrap: wrap;
        }

        /* Imagem do Jhuan */
        .image img {
            border-radius: 50%;
            width: 150px;
            height: 150px;
            object-fit: cover;
        }

        /* Bio do programador */
        .bio {
            flex: 1;
            text-align: justify;
        }

        .bio p {
            font-size: 16px;
            line-height: 1.6;
        }

        /* Footer */
        footer {
            text-align: center;
            margin-top: 30px;
            font-size: 14px;
            color: #777;
        }
    </style>
</head>
<body>

    <div class="container">
        <!-- Cabeçalho -->
        <header>
            <h1>Olá, Eu Sou Jhuan!</h1>
            <p>Programador apaixonado por tecnologia e inovação.</p>
        </header>

        <!-- Seção de Introdução -->
        <section class="intro">
            <!-- Imagem de Jhuan -->
            <div class="image">
                <img src="https://via.placeholder.com/150" alt="Jhuan - Programador">
            </div>
            <!-- Biografia de Jhuan -->
            <div class="bio">
                <p>Meu nome é Jhuan, sou um programador full-stack com foco em soluções inovadoras. Tenho experiência em diversas linguagens, como <strong>JavaScript</strong>, <strong>Python</strong>, <strong>HTML</strong> e <strong>CSS</strong>.</p>
                <p>Desde jovem, sou fascinado pelo mundo da tecnologia e, com o tempo, encontrei na programação uma forma de transformar ideias em realidade. Trabalhei em diversos projetos, sempre buscando aprender e aprimorar minhas habilidades.</p>
                <p>Estou sempre em busca de novos desafios e oportunidades para crescer como desenvolvedor e impactar positivamente o mundo por meio da tecnologia.</p>
            </div>
        </section>

        <!-- Rodapé -->
        <footer>
            <p>&copy; 2024 Jhuan - Todos os direitos reservados.</p>
        </footer>
    </div>

</body>
</html>
