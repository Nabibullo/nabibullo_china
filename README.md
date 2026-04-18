<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Набибулло | Преподаватель китайского языка | HSK | Онлайн уроки</title>
    <meta name="description" content="Изучайте китайский язык с Набибулло. Подготовка к HSK, онлайн уроки, структурированное обучение. Будущий архитектор делится опытом.">
    <meta name="keywords" content="китайский язык, HSK, уроки китайского, онлайн преподаватель, Набибулло">
    <link rel="canonical" href="https://yourdomain.com">
    <link rel="icon" href="data:image/svg+xml,<svg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 100 100'><text y='.9em' font-size='90'>🇨🇳</text></svg>">
    
    <!-- Font Awesome for icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    
    <style>
        :root {
            --bg-primary: #0a0a0a;
            --bg-secondary: #1a1a1a;
            --text-primary: #ffffff;
            --text-secondary: #d4af37;
            --gold: #d4af37;
            --gold-light: #ffd700;
            --glass-bg: rgba(255, 255, 255, 0.1);
            --blur: blur(20px);
        }
        
        * { margin: 0; padding: 0; box-sizing: border-box; }
        body {
            font-family: 'Inter', -apple-system, BlinkMacSystemFont, sans-serif;
            background: var(--bg-primary);
            color: var(--text-primary);
            overflow-x: hidden;
            line-height: 1.6;
        }
        
        /* Animated Gradient Background */
        .bg-gradient {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: linear-gradient(-45deg, #0a0a0a, #1a1a1a, #2a2a2a, #0a0a0a);
            background-size: 400% 400%;
            animation: gradientShift 15s ease infinite;
            z-index: -2;
        }
        @keyframes gradientShift {
            0% { background-position: 0% 50%; }
            50% { background-position: 100% 50%; }
            100% { background-position: 0% 50%; }
        }
        
        /* Particles Canvas */
        #particles {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            z-index: -1;
            pointer-events: none;
        }
        
        /* Glassmorphism Cards */
        .glass-card {
            background: var(--glass-bg);
            backdrop-filter: var(--blur);
            border: 1px solid rgba(255, 255, 255, 0.2);
            border-radius: 20px;
            padding: 2rem;
            box-shadow: 0 25px 45px rgba(0,0,0,0.3), 0 0 0 1px rgba(255,255,255,0.05);
            transition: all 0.4s cubic-bezier(0.175, 0.885, 0.32, 1.275);
            transform: translateZ(0);
        }
        .glass-card:hover {
            transform: translateY(-10px) scale(1.02);
            box-shadow: 0 35px 60px rgba(212, 175, 55, 0.2), 0 0 20px rgba(212, 175, 55, 0.3);
        }
        
        /* Scroll Animations */
        .fade-in { opacity: 0; transform: translateY(50px); transition: all 1s ease; }
        .fade-in.visible { opacity: 1; transform: translateY(0); }
        .float { animation: float 6s ease-in-out infinite; }
        @keyframes float { 0%, 100% { transform: translateY(0px); } 50% { transform: translateY(-20px); } }
        
        /* Header/Nav */
        header { position: fixed; top: 0; width: 100%; background: rgba(10,10,10,0.9); backdrop-filter: blur(10px); z-index: 100; padding: 1rem 0; transition: all 0.3s; }
        nav ul { display: flex; justify-content: center; list-style: none; gap: 2rem; flex-wrap: wrap; }
        nav a { color: var(--text-primary); text-decoration: none; font-weight: 500; transition: color 0.3s; }
        nav a:hover { color: var(--gold); }
        
        /* Sections */
        section { padding: 5rem 2rem; max-width: 1200px; margin: 0 auto; position: relative; }
        h1 { font-size: clamp(2.5rem, 5vw, 4rem); font-weight: 800; margin-bottom: 1rem; background: linear-gradient(45deg, var(--gold), var(--text-primary)); -webkit-background-clip: text; -webkit-text-fill-color: transparent; text-align: center; }
        h2 { font-size: clamp(1.8rem, 4vw, 2.5rem); color: var(--gold); margin-bottom: 2rem; text-align: center; position: relative; }
        h2::after { content: ''; position: absolute; bottom: -10px; left: 50%; transform: translateX(-50%); width: 80px; height: 3px; background: var(--gold); border-radius: 2px; }
        
        /* Hero */
        #hero { height: 100vh; display: flex; flex-direction: column; justify-content: center; align-items: center; text-align: center; }
        #hero p { font-size: 1.3rem; margin: 1rem 0 2rem; max-width: 600px; }
        .cta-btn { 
            display: inline-block; padding: 1rem 2rem; margin: 0.5rem; background: linear-gradient(45deg, var(--gold), var(--gold-light)); 
            color: var(--bg-primary); font-weight: bold; text-decoration: none; border-radius: 50px; 
            transition: all 0.3s; box-shadow: 0 10px 30px rgba(212,175,55,0.4);
        }
        .cta-btn:hover { transform: scale(1.05); box-shadow: 0 15px 40px rgba(212,175,55,0.6); }
        
        /* Grid */
        .grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(300px, 1fr)); gap: 2rem; margin-top: 3rem; }
        
        /* Services/Problem-Solution */
        .feature { text-align: center; }
        .feature i { font-size: 4rem; color: var(--gold); margin-bottom: 1rem; }
        
        /* Reviews */
        .reviews .grid { grid-template-columns: repeat(auto-fit, minmax(250px, 1fr)); }
        .review { font-style: italic; text-align: center; }
        
        /* Contacts */
        .social-grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(200px, 1fr)); gap: 1.5rem; margin-top: 2rem; }
        .social-btn { 
            display: flex; align-items: center; gap: 1rem; padding: 1.5rem; background: var(--glass-bg); 
            backdrop-filter: var(--blur); border: 1px solid rgba(255,255,255,0.2); border-radius: 15px; 
            text-decoration: none; color: var(--text-primary); font-weight: 500; transition: all 0.3s;
        }
        .social-btn:hover { background: rgba(212,175,55,0.2); border-color: var(--gold); transform: translateY(-5px); }
        .social-btn i { font-size: 2rem; color: var(--gold); }
        
        /* CTA */
        .cta-section { background: linear-gradient(135deg, var(--gold), var(--gold-light)); color: var(--bg-primary); text-align: center; }
        .cta-section h2 { color: var(--bg-primary); }
        .cta-section .cta-btn { background: var(--bg-primary); color: var(--gold); }
        
        /* Responsive */
        @media (max-width: 768px) {
            header { padding: 0.5rem 0; }
            nav ul { gap: 1rem; font-size: 0.9rem; }
            section { padding: 3rem 1rem; }
            .social-grid { grid-template-columns: 1fr; }
        }
        
        /* 3D Floating Elements */
        .floating { position: absolute; opacity: 0.1; animation: float 20s infinite linear; }
        .floating:nth-child(1) { top: 10%; left: 10%; font-size: 3rem; animation-duration: 25s; }
        .floating:nth-child(2) { top: 70%; right: 10%; font-size: 2rem; animation-duration: 30s; animation-direction: reverse; }
    </style>
</head>
<body>
    <!-- Animated Background -->
    <div class="bg-gradient"></div>
    <canvas id="particles"></canvas>
    
    <!-- Floating 3D Elements -->
    <div class="floating" style="animation-delay: 0s;">🇨🇳</div>
    <div class="floating" style="animation-delay: 10s;">🏛️</div>
    
    <header>
        <nav>
            <ul>
                <li><a href="#hero">Главная</a></li>
                <li><a href="#about">Обо мне</a></li>
                <li><a href="#services">Услуги</a></li>
                <li><a href="#problem">Проблема/Решение</a></li>
                <li><a href="#reviews">Отзывы</a></li>
                <li><a href="#contact">Контакты</a></li>
            </ul>
        </nav>
    </header>

    <section id="hero" class="fade-in">
        <h1>Изучай китайский язык со мной</h1>
        <p>Я — преподаватель китайского и будущий архитектор. Помогаю достичь результата быстрее.</p>
        <div>
            <a href="#services" class="cta-btn">Начать обучение</a>
            <a href="#contact" class="cta-btn">Связаться</a>
        </div>
    </section>

    <section id="about" class="fade-in">
        <h2>Обо мне</h2>
        <div class="glass-card" style="max-width: 800px; margin: 0 auto 3rem;">
            <p>Привет! Меня зовут Набибулло. Я изучаю китайский язык, преподаю его онлайн и готовлюсь к экзаменам HSK. Одновременно учусь на архитектора — это помогает развивать системное мышление для эффективного обучения.</p>
            <p>Делюсь своим опытом: от базовых тонов до сложной грамматики. Моя цель — сделать китайский доступным и интересным.</p>
        </div>
    </section>

    <section id="services" class="fade-in">
        <h2>Услуги / Уроки</h2>
        <div class="grid">
            <div class="glass-card feature">
                <i class="fas fa-globe-asia"></i>
                <h3>Онлайн уроки китайского</h3>
                <p>Индивидуальные занятия в удобное время.</p>
            </div>
            <div class="glass-card feature">
                <i class="fas fa-trophy"></i>
                <h3>Подготовка к HSK</h3>
                <p>Полный курс для сдачи экзаменов любого уровня.</p>
            </div>
            <div class="glass-card feature">
                <i class="fas fa-brain"></i>
                <h3>Простое объяснение сложного</h3>
                <p>Грамматика, иероглифы и разговорная практика.</p>
            </div>
        </div>
    </section>

    <section id="problem" class="fade-in">
        <h2>Проблема и решение</h2>
        <div class="grid">
            <div class="glass-card">
                <h3>Проблемы учеников</h3>
                <ul style="text-align: left;">
                    <li>Учат долго без результата</li>
                    <li>Не понимают грамматику</li>
                    <li>Теряют мотивацию</li>
                </ul>
            </div>
            <div class="glass-card">
                <h3>Моё решение</h3>
                <ul style="text-align: left;">
                    <li>Структурированное обучение</li>
                    <li>Практика и разговор</li>
                    <li>Быстрый прогресс + мотивация</li>
                </ul>
            </div>
        </div>
    </section>

    <section id="reviews" class="fade-in">
        <h2>Отзывы</h2>
        <div class="grid reviews">
            <div class="glass-card review">
                <p>"Набибулло объясняет просто и эффективно! Сдал HSK 4 за 3 месяца."</p>
                <cite>— Ученик А.</cite>
            </div>
            <div class="glass-card review">
                <p>"Мотивация на высоте, практика каждый урок. Рекомендую!"</p>
                <cite>— Ученица Б.</cite>
            </div>
            <div class="glass-card review">
                <p>"От нуля до разговора — супер метод!"</p>
                <cite>— Ученик В.</cite>
            </div>
        </div>
    </section>

    <section id="contact" class="fade-in">
        <h2>Контакты и соцсети</h2>
        <div class="glass-card" style="max-width: 600px; margin: 0 auto;">
            <p>Запишись на пробный урок! Пиши в удобный мессенджер.</p>
        </div>
        <div class="social-grid">
            <a href="https://www.instagram.com/nabibullo_china?igsh=MTh6cDN4dnlvcDM2eg==" class="social-btn" target="_blank">
                <i class="fab fa-instagram"></i>
                Instagram
            </a>
            <a href="https://t.me/nabibullochina" class="social-btn" target="_blank">
                <i class="fab fa-telegram"></i>
                Telegram
            </a>
            <a href="https://wa.me/992908802800" class="social-btn" target="_blank">
                <i class="fab fa-whatsapp"></i>
                WhatsApp
            </a>
        </div>
    </section>

    <section class="cta-section fade-in">
        <h2>Запишись на урок прямо сейчас</h2>
        <p>Начни путь к свободному китайскому!</p>
        <a href="https://wa.me/992908802800" class="cta-btn" target="_blank">Записаться в WhatsApp</a>
    </section>

    <script>
        // Particles System (Gold particles)
        const canvas = document.getElementById('particles');
        const ctx = canvas.getContext('2d');
        canvas.width = window.innerWidth;
        canvas.height = window.innerHeight;
        
        const particles = [];
        for (let i = 0; i < 100; i++) {
            particles.push({
                x: Math.random() * canvas.width,
                y: Math.random() * canvas.height,
                vx: (Math.random() - 0.5) * 0.5,
                vy: (Math.random() - 0.5) * 0.5,
                radius: Math.random() * 2 + 1,
                glow: Math.random() * 0.5 + 0.2
            });
        }
        
        function animateParticles() {
            ctx.clearRect(0, 0, canvas.width, canvas.height);
            particles.forEach(p => {
                ctx.beginPath();
                ctx.arc(p.x, p.y, p.radius, 0, Math.PI * 2);
                ctx.fillStyle = `rgba(212, 175, 55, ${p.glow})`;
                ctx.shadowBlur = 10;
                ctx.shadowColor = '#d4af37';
                ctx.fill();
                
                p.x += p.vx;
                p.y += p.vy;
                if (p.x < 0 || p.x > canvas.width) p.vx *= -1;
                if (p.y < 0 || p.y > canvas.height) p.vy *= -1;
            });
            requestAnimationFrame(animateParticles);
        }
        animateParticles();
        
        window.addEventListener('resize', () => {
            canvas.width = window.innerWidth;
            canvas.height = window.innerHeight;
        });
        
        // Scroll Animations
        const observer = new IntersectionObserver(entries => {
            entries.forEach(entry => {
                if (entry.isIntersecting) {
                    entry.target.classList.add('visible');
                }
            });
        });
        document.querySelectorAll('.fade-in').forEach(el => observer.observe(el));
        
        // Smooth Scroll
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', e => {
                e.preventDefault();
                const target = document.querySelector(anchor.getAttribute('href'));
                target.scrollIntoView({ behavior: 'smooth' });
            });
        });
        
        // Header Scroll Effect
        window.addEventListener('scroll', () => {
            document.querySelector('header').style.background = scrollY > 100 ? 'rgba(10,10,10,0.95)' : 'rgba(10,10,10,0.9)';
        });
    </script>
</body>
</html>
