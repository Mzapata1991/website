<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Servicios de Marketing Digital</title>
    <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@300;400;700&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.4/css/all.min.css">
    
    
    <style>
        body {
            font-family: 'Montserrat', sans-serif;
            margin: 0;
            padding: 0;
            background: url('assets//background-banner.gif') no-repeat center center/cover;
            color: #000000;
        }
    
        body::before {
            content: "";
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: url('assets/background-banner.png/') no-repeat center center/cover;
            opacity: 0.8;
            z-index: -1;
        }
        header {
            background: #20227e;
            padding: 40px 20px;
            text-align: center;
            font-size: 32px;
            font-weight: 700;
            position: relative;
            text-transform: uppercase;
            letter-spacing: 2px;
            color: #fff;
        }
        header img {
            width: 100px;
            height: 100px;
            position: relative;
            display: block;
            margin: 0 auto 10px auto;
        }
        nav {
            display: flex;
            justify-content: center;
            flex-wrap: wrap;
            background: #007acc;
            padding: 15px;
        }
        nav a {
            color: #fff;
            text-decoration: none;
            margin: 10px 15px;
            font-weight: 700;
            font-size: 18px;
            transition: color 0.3s ease;
        }
        nav a:hover {
            color: #000000;
        }
        .hero {
            text-align: center;
            padding: 60px 20px;
            background: rgb(230, 242, 255);
        }
        .hero h1 {
            color: #000000;
            font-size: 36px;
        }
        .hero p {
            font-size: 18px;
        }
        .section {
            padding: 40px 20px;
            text-align: center;
            background: rgba(255, 255, 255, 0.671);

        }
        .portfolio {
            display: flex;
            overflow-x: auto;
            padding: 10px;
            white-space: nowrap;
        }
        .portfolio-item {
            flex: 0 0 auto;
            margin: 10px;
            text-align: center;
        }
        .portfolio img {
            width: 300px;
            border-radius: 20px;
            transition: transform 0.3s ease, box-shadow 0.3s ease;
        }
        .portfolio img:hover {
            transform: scale(1.05);
            box-shadow: 0 8px 20px rgba(0, 0, 0, 0.8);
        }
        .portfolio-button {
            display: block;
            background: #000000;
            color: #fff;
            padding: 10px 20px;
            border-radius: 20px;
            font-weight: 700;
            text-decoration: none;
            margin: 10px auto;
            transition: background 0.3s ease;
            width: fit-content;
        }
        .portfolio-button:hover {
            background: #fdfdfd;
            color: #000;
        }
        footer {
            background: #003366;
            text-align: center;
            padding: 20px;
            color: #fff;
        }
        footer img {
            width: 80px;
            height: 80px;
            display: block;
            margin: 0 auto;
        }
        .social-icons a {
            margin: 10px 10px;
            color: #fff;
            font-size: 24px;
            text-decoration: none;
        }
        .whatsapp-float {
            position: fixed;
            bottom: 20px;
            background-color: #009118;
            border-radius: 50%;
            padding-left: 8px;
            padding-right: 8px;
            right: 20px;
            color: #ffffff;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
            font-size: 50px;
            text-decoration: none;
        }

    </style>
</head>
<body>
    <header>
        <img src="assets/logo.png" alt="Logo">
        Servicios de Marketing Digital
    </header>
    <nav>
        <a href="#home">Home</a>
        <a href="#about">Sobre Nosotros</a>
        <a href="#portfolio">Portfolio</a>
        <a href="#contact">Contacto</a>
    </nav>
    <section id="home" class="hero">
        <h1>Impulsa tu Negocio con Estrategias Digitales</h1>
        <p>Diseño Web, Advertising y SEO, Email Marketing y Cursos.</p>
    </section>
    <section id="about" class="section">
        <h2>Sobre Nosotros</h2>
        <p>Somos expertos en marketing digital con años de experiencia optimizando negocios online.</p>
    </section>
    <section id="portfolio" class="section">
        <h2>Portfolio</h2>
        <div class="portfolio">
            <div class="portfolio-item"><a href="#"><img src="assets/Divino_case.png" alt="Proyecto 1"></a><a href="#" class="portfolio-button">Ver Proyecto</a></div>
            <div class="portfolio-item"><a href="#"><img src="assets/Schinca_case.png" alt="Proyecto 2"></a><a href="#" class="portfolio-button">Ver Proyecto</a></div>
            <div class="portfolio-item"><a href="#"><img src="assets/Districad case.png" alt="Proyecto 3"></a><a href="#" class="portfolio-button">Ver Proyecto</a></div>
            <div class="portfolio-item"><a href="#"><img src="assets/WiseData case.png" alt="Proyecto 4"></a><a href="#" class="portfolio-button">Ver Proyecto</a></div>
            <div class="portfolio-item"><a href="#"><img src="assets/Noe study case.jpg" alt="Proyecto 5"></a><a href="#" class="portfolio-button">Ver Proyecto</a></div>
        </div>
    </section>
    <footer>
        <img src="assets/logo.png" alt="Logo">
        <br>
        &copy; 2025 Servicios de Marketing Digital - Todos los derechos reservados.
        <br>
        <br>
        <div class="social-icons">
            <a href="https://instagram.com" target="_blank"><i class="fab fa-instagram"></i></a>
            <a href="https://facebook.com" target="_blank"><i class="fab fa-facebook-f"></i></a>
            <a href="https://linkedin.com" target="_blank"><i class="fab fa-linkedin-in"></i></a>
            <a href="https://youtube.com" target="_blank"><i class="fab fa-youtube"></i></a>
        </div>
        
        </div>
    </footer>
    <a href="#" class="whatsapp-float"><i class="fab fa-whatsapp"></a>
</body>
</html>
