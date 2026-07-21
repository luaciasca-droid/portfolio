<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Lua Ciasca — Motion Designer & Video Editor</title>
    
    <!-- Tipografia Estilo Spencer Gabor + Editorial -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600&family=Outfit:wght@700;900&display=swap" rel="stylesheet">
    
    <!-- Biblioteca AOS para Animações no Scroll -->
    <link href="https://unpkg.com/aos@2.3.1/dist/aos.css" rel="stylesheet">

    <style>
        :root {
            /* Cores extraídas da sua marca / Wix */
            --bg: #0d0d0e;
            --card-bg: #161618;
            --text: #ffffff;
            --text-muted: #a1a1aa;
            --accent: #ff5500; /* Seu Laranja Vibrante */
            --border: #27272a;
        }

        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
        }

        body {
            background-color: var(--bg);
            color: var(--text);
            font-family: 'Inter', sans-serif;
            padding: 0 4vw;
            overflow-x: hidden;
        }

        /* Granulação Retrô Fina no Fundo */
        body::before {
            content: "";
            position: fixed;
            top: 0; left: 0; width: 100vw; height: 100vh;
            background: url('https://raw.githubusercontent.com/danielmendes/noise-generator/master/img/noise.png');
            opacity: 0.03;
            pointer-events: none;
            z-index: 999;
        }

        /* Topo Fixo */
        header {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 2rem 0;
            position: sticky;
            top: 0;
            background: rgba(13, 13, 14, 0.85);
            backdrop-filter: blur(12px);
            z-index: 100;
            border-bottom: 1px solid var(--border);
        }

        .logo {
            font-family: 'Outfit', sans-serif;
            font-weight: 900;
            font-size: 1.5rem;
            letter-spacing: -0.5px;
            color: var(--text);
            text-decoration: none;
        }

        nav a {
            color: var(--text-muted);
            text-decoration: none;
            font-weight: 500;
            margin-left: 2rem;
            transition: color 0.2s;
        }

        nav a:hover {
            color: var(--accent);
        }

        /* HERO COM ELEMENTOS INTERATIVOS ESTILO SPENCER GABOR */
        .hero-container {
            position: relative;
            padding: 8vw 0 6vw 0;
            max-width: 1100px;
            margin: 0 auto;
        }

        .hero-text {
            position: relative;
            z-index: 2;
        }

        .hero-text h1 {
            font-family: 'Outfit', sans-serif;
            font-size: clamp(3rem, 7.5vw, 6.5rem);
            font-weight: 900;
            line-height: 1.05;
            letter-spacing: -2px;
            margin-bottom: 2rem;
        }

        .hero-text h1 span {
            color: var(--accent);
        }

        .hero-manifesto {
            color: var(--text-muted);
            font-size: clamp(1.1rem, 2vw, 1.4rem);
            max-width: 700px;
            line-height: 1.6;
            margin-bottom: 2.5rem;
        }

        /* Cards Flutuantes Interativos (Efeito Spencer Gabor) */
        .floating-card {
            position: absolute;
            border-radius: 16px;
            overflow: hidden;
            border: 2px solid var(--accent);
            box-shadow: 0 20px 40px rgba(0,0,0,0.5);
            transition: transform 0.1s ease-out, box-shadow 0.3s ease;
            cursor: pointer;
            z-index: 1;
        }

        .floating-card:hover {
            box-shadow: 0 30px 60px rgba(255, 85, 0, 0.3);
            z-index: 10;
        }

        .floating-card video, .floating-card img {
            width: 100%;
            height: 100%;
            object-fit: cover;
            display: block;
        }

        /* Posicionamento dos cards flutuantes na tela */
        .card-1 {
            width: 220px;
            height: 140px;
            top: 5%;
            right: -2%;
            transform: rotate(6deg);
        }

        .card-2 {
            width: 180px;
            height: 220px;
            bottom: 5%;
            right: 15%;
            transform: rotate(-8deg);
        }

        /* Seção Meu Processo (Do seu Wix) */
        .process-section {
            padding: 6vw 0;
            border-top: 1px solid var(--border);
            border-bottom: 1px solid var(--border);
            margin-bottom: 8vw;
        }

        .section-title {
            font-family: 'Outfit', sans-serif;
            font-size: clamp(2rem, 4vw, 3.5rem);
            font-weight: 900;
            margin-bottom: 3rem;
            color: var(--text);
        }

        .process-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
            gap: 2rem;
        }

        .process-card {
            background: var(--card-bg);
            border: 1px solid var(--border);
            padding: 2.5rem 2rem;
            border-radius: 16px;
            transition: border-color 0.3s;
        }

        .process-card:hover {
            border-color: var(--accent);
        }

        .process-num {
            font-family: 'Outfit', sans-serif;
            font-size: 2.5rem;
            font-weight: 900;
            color: var(--accent);
            margin-bottom: 1rem;
        }

        .process-card h3 {
            font-size: 1.3rem;
            margin-bottom: 0.8rem;
        }

        .process-card p {
            color: var(--text-muted);
            font-size: 0.95rem;
            line-height: 1.5;
        }

        /* Grade de Projetos (Selected Works) */
        .portfolio-grid {
            display: grid;
            grid-template-columns: repeat(2, 1fr);
            gap: 2.5rem;
            margin-bottom: 10vw;
        }

        .project-card {
            background: var(--card-bg);
            border: 1px solid var(--border);
            border-radius: 20px;
            overflow: hidden;
            text-decoration: none;
            color: var(--text);
            transition: transform 0.4s cubic-bezier(0.16, 1, 0.3, 1), border-color 0.3s;
            display: flex;
            flex-direction: column;
        }

        .project-card:hover {
            transform: translateY(-8px);
            border-color: var(--accent);
        }

        .card-media {
            width: 100%;
            aspect-ratio: 16 / 9;
            background: #000;
        }

        .card-media iframe {
            width: 100%;
            height: 100%;
            border: none;
        }

        .card-info {
            padding: 1.8rem;
            display: flex;
            justify-content: space-between;
            align-items: center;
        }

        .card-title {
            font-family: 'Outfit', sans-serif;
            font-size: 1.5rem;
            font-weight: 700;
            margin-bottom: 0.3rem;
        }

        .card-category {
            color: var(--text-muted);
            font-size: 0.9rem;
        }

        .featured-reel {
            grid-column: 1 / -1;
        }

        /* Footer */
        footer {
            border-top: 1px solid var(--border);
            padding: 8vw 0 4vw 0;
            display: flex;
            flex-direction: column;
            gap: 3rem;
        }

        footer h2 {
            font-family: 'Outfit', sans-serif;
            font-size: clamp(2.5rem, 6vw, 5rem);
            font-weight: 900;
        }

        .footer-links {
            display: flex;
            gap: 2rem;
        }

        .footer-links a {
            color: var(--text);
            font-size: 1.2rem;
            text-decoration: none;
            border-bottom: 2px solid var(--accent);
            padding-bottom: 4px;
        }

        /* Ajustes para Telas Menores */
        @media (max-width: 900px) {
            .floating-card { display: none; } /* Esconde flutuantes em celulares para não cobrir texto */
            .portfolio-grid { grid-template-columns: 1fr; }
        }
    </style>
</head>
<body>

    <header>
        <a href="#" class="logo">LUA CIASCA</a>
        <nav>
            <a href="#process">Process</a>
            <a href="#work">Work</a>
            <a href="mailto:luaciasca@gmail.com">Contact</a>
        </nav>
    </header>

    <!-- INTRODUÇÃO INTERATIVA COM MOUSE (SPENCER GABOR VIBE) -->
    <div class="hero-container" id="hero">
        
        <!-- Elemento Interativo 1 (Vídeo/Card Flutuante que reage ao mouse) -->
        <div class="floating-card card-1" data-speed="3">
            <iframe src="https://player.vimeo.com/video/76979871?background=1&autoplay=1&loop=1&byline=0&title=0" allow="autoplay; fullscreen"></iframe>
        </div>

        <!-- Elemento Interativo 2 (Foto/Thumbnail Flutuante) -->
        <div class="floating-card card-2" data-speed="-2">
            <img src="https://static.wixstatic.com/media/95162c_7b1579ccc87b4a9eb26563a32acd3c12f002.jpg/v1/fill/w_533,h_300,enc_auto/file.jpeg" alt="Motion Graphic Preview">
        </div>

        <div class="hero-text">
            <h1 data-aos="fade-up">
                Motion Designer &<br><span>Video Editor</span>
            </h1>
            <p class="hero-manifesto" data-aos="fade-up" data-aos-delay="100">
                "I make videos because I believe everyone has a story worth telling, and I want people to feel seen when they watch."
            </p>
        </div>
    </div>

    <!-- SEÇÃO: MEU PROCESSO (Extraído do seu Wix) -->
    <section class="process-section" id="process">
        <h2 class="section-title" data-aos="fade-up">My Process, Explained</h2>
        <div class="process-grid">
            
            <div class="process-card" data-aos="fade-up" data-aos-delay="100">
                <div class="process-num">01</div>
                <h3>The Conversation</h3>
                <p>Before anything else, I want to understand what you need to say and who you're saying it to. The brief is the starting point—the conversation defines the path.</p>
            </div>

            <div class="process-card" data-aos="fade-up" data-aos-delay="200">
                <div class="process-num">02</div>
                <h3>The Production</h3>
                <p>Filming, design, editing, and animation. I handle every step while keeping you in the loop throughout for feedback and approvals.</p>
            </div>

            <div class="process-card" data-aos="fade-up" data-aos-delay="300">
                <div class="process-num">03</div>
                <h3>The Delivery</h3>
                <p>Files delivered in all required formats, revisions completed, project closed. Ready to engage and move your audience.</p>
            </div>

        </div>
    </section>

    <!-- GRADE DE PROJETOS -->
    <main id="work">
        <h2 class="section-title" data-aos="fade-up">Selected Works</h2>
        <div class="portfolio-grid">

            <!-- 01. Showreel Destaque -->
            <div class="project-card featured-reel" data-aos="fade-up">
                <div class="card-media">
                    <iframe src="https://player.vimeo.com/video/76979871" allow="autoplay; fullscreen" allowfullscreen></iframe>
                </div>
                <div class="card-info">
                    <div>
                        <div class="card-title">Motion & Reel Highlight</div>
                        <div class="card-category">Showreel 2026</div>
                    </div>
                </div>
            </div>

            <!-- 02. Projeto 1 -->
            <div class="project-card" data-aos="fade-up">
                <div class="card-media">
                    <iframe src="https://player.vimeo.com/video/76979871" allowfullscreen></iframe>
                </div>
                <div class="card-info">
                    <div>
                        <div class="card-title">Motion Design for Social Media</div>
                        <div class="card-category">Social Strategy & Animation</div>
                    </div>
                </div>
            </div>

            <!-- 03. Projeto 2 -->
            <div class="project-card" data-aos="fade-up" data-aos-delay="100">
                <div class="card-media">
                    <iframe src="https://player.vimeo.com/video/76979871" allowfullscreen></iframe>
                </div>
                <div class="card-info">
                    <div>
                        <div class="card-title">Motion Design for Brands</div>
                        <div class="card-category">Brand Identity & Commercials</div>
                    </div>
                </div>
            </div>

        </div>
    </main>

    <!-- FOOTER -->
    <footer>
        <div data-aos="fade-up">
            <h2>Let's build something<br>great together.</h2>
        </div>
        <div class="footer-links" data-aos="fade-up">
            <a href="mailto:luaciasca@gmail.com">luaciasca@gmail.com</a>
            <a href="https://www.linkedin.com/in/lua-ciasca-barbi-bb5a55184/" target="_blank">LinkedIn</a>
        </div>
    </footer>

    <!-- Scripts de Interatividade do Mouse + Animações -->
    <script src="https://unpkg.com/aos@2.3.1/dist/aos.js"></script>
    <script>
        // Inicializa animação no Scroll
        AOS.init({ duration: 800, once: true });

        // Efeito Parallax / Mouse Mover nos Cards Flutuantes (Spencer Gabor Style)
        const hero = document.getElementById('hero');
        const cards = document.querySelectorAll('.floating-card');

        hero.addEventListener('mousemove', (e) => {
            const { clientX, clientY } = e;
            const centerX = window.innerWidth / 2;
            const centerY = window.innerHeight / 2;

            cards.forEach(card => {
                const speed = card.getAttribute('data-speed');
                const x = (clientX - centerX) * speed / 100;
                const y = (clientY - centerY) * speed / 100;
                
                card.style.transform = `translate(${x}px, ${y}px) rotate(${speed * 2}deg)`;
            });
        });
    </script>
</body>
</html>
