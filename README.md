<html lang="pt-br">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ruany | Account Manager Vivo Empresas</title>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700&display=swap" rel="stylesheet">
    <style>
        :root {
            /* Cores com tendência feminina e profissional */
            --primary: #ff00cc; /* Magenta Vivo */
            --secondary: #6600ff; /* Violeta Profundo */
            --accent: #ffb7c5; /* Rose Gold */
            --dark: #0f0a14;
            --glass: rgba(255, 255, 255, 0.03);
            --border: rgba(255, 255, 255, 0.1);
        }

        * {
            margin: 0; padding: 0; box-sizing: border-box;
            font-family: 'Poppins', sans-serif;
            scroll-behavior: smooth;
        }

        body {
            background-color: var(--dark);
            color: white;
            overflow-x: hidden;
        }

        /* Fundo com efeito de névoa colorida */
        body::before {
            content: "";
            position: fixed;
            top: 0; left: 0; width: 100%; height: 100%;
            background: radial-gradient(circle at 80% 20%, #2a1b3d 0%, #0f0a14 100%);
            z-index: -1;
        }

        .glow-effect {
            position: absolute;
            width: 400px; height: 400px;
            background: var(--primary);
            filter: blur(180px);
            border-radius: 50%;
            opacity: 0.15;
            top: -100px; left: -100px;
            animation: pulse 8s infinite alternate;
        }

        @keyframes pulse {
            to { transform: scale(1.2); opacity: 0.2; }
        }

        header {
            height: 100vh;
            display: flex;
            align-items: center;
            justify-content: center;
            padding: 0 8%;
        }

        .container {
            max-width: 1200px;
            width: 100%;
            display: flex;
            align-items: center;
            justify-content: space-between;
            gap: 40px;
        }

        /* Foto com borda orgânica e suave */
        .profile-wrapper {
            position: relative;
        }

        .profile-img {
            width: 380px;
            height: 480px;
            object-fit: cover;
            border-radius: 60% 40% 30% 70% / 60% 30% 70% 40%;
            border: 2px solid var(--border);
            box-shadow: 0 0 50px rgba(255, 0, 204, 0.2);
            animation: morph 10s ease-in-out infinite;
        }

        @keyframes morph {
            0%, 100% { border-radius: 60% 40% 30% 70% / 60% 30% 70% 40%; }
            50% { border-radius: 30% 60% 70% 40% / 50% 60% 30% 60%; }
        }

        .content h2 {
            color: var(--primary);
            text-transform: uppercase;
            letter-spacing: 3px;
            font-size: 0.9rem;
            margin-bottom: 10px;
        }

        .content h1 {
            font-size: 4rem;
            line-height: 1;
            margin-bottom: 20px;
        }

        .content h1 span {
            background: linear-gradient(to right, var(--primary), var(--accent));
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
        }

        .description {
            font-size: 1.1rem;
            color: #ccc;
            max-width: 500px;
            margin-bottom: 35px;
        }

        .cta-button {
            padding: 18px 45px;
            background: linear-gradient(45deg, var(--primary), var(--secondary));
            color: white;
            text-decoration: none;
            font-weight: 600;
            border-radius: 15px;
            transition: 0.3s;
            display: inline-block;
            box-shadow: 0 10px 30px rgba(255, 0, 204, 0.3);
        }

        .cta-button:hover {
            transform: translateY(-5px);
            box-shadow: 0 15px 40px rgba(255, 0, 204, 0.5);
        }

        /* Seção de Excelência */
        .excellence-section {
            padding: 100px 8%;
            text-align: center;
        }

        .grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 25px;
            margin-top: 50px;
        }

        .glass-card {
            background: var(--glass);
            backdrop-filter: blur(20px);
            border: 1px solid var(--border);
            padding: 45px;
            border-radius: 30px;
            transition: 0.5s;
        }

        .glass-card:hover {
            background: rgba(255, 255, 255, 0.07);
            border-color: var(--primary);
            transform: scale(1.03);
        }

        .glass-card h3 {
            margin-bottom: 15px;
            color: var(--accent);
        }

        @media (max-width: 900px) {
            .container { flex-direction: column-reverse; text-align: center; }
            .profile-img { width: 300px; height: 350px; }
            .content h1 { font-size: 2.8rem; }
        }
    </style>
</head>
<body>
    <div class="glow-effect"></div>

    <header>
        <div class="container">
            <div class="content">
                <h2>Vivo Empresas</h2>
                <h1>Olá, eu sou <span>Ruany</span></h1>
                <p class="description">Gerente de Contas B2B focada em transformar a conectividade do seu negócio com <b>eficiência máxima</b> e <b>qualidade de serviço surreal</b>.</p>
                <a href="tel:2730619962" class="cta-button">Solicitar Consultoria</a>
            </div>
            <div class="profile-wrapper">
                <img src="ruany.jpg" alt="Ruany" class="profile-img">
            </div>
        </div>
    </header>

    <section class="excellence-section">
        <h1>Opções de <span>Excelência</span></h1>
        <div class="grid">
            <div class="glass-card">
                <h3>Atendimento Prime</h3>
                <p>Gestão personalizada de contas corporativas, garantindo que cada solução seja moldada para o crescimento da sua empresa.</p>
            </div>
            <div class="glass-card">
                <h3>Eficiência Operacional</h3>
                <p>Otimização de custos e implementação ágil de serviços de dados, voz e nuvem com o padrão Vivo de qualidade.</p>
            </div>
            <div class="glass-card">
                <h3>Suporte Dedicado</h3>
                <p>Acompanhamento ponta a ponta para garantir que a tecnologia trabalhe a favor da sua produtividade, sem interrupções.</p>
            </div>
        </div>
    </section>

    <section class="excellence-section">
        <h1> SOBRE <span>MIM</span></h1>
        <p class="description" style="margin: 0 auto;">
            Sou especialista em soluções corporativas na Vivo Empresas, onde atuo como ponte entre a tecnologia de ponta e o sucesso dos meus clientes. Minha missão é entregar excelência através de um olhar estratégico, garantindo que cada empresa parceira tenha a melhor performance do mercado.
        </p>
    </section>

</body>
</html>
