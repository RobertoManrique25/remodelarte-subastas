<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>RemodelArte y Subastas</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }
        header {
            background-color: #333;
            color: #fff;
            padding: 1em 0;
            text-align: center;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: #444;
        }
        nav a {
            color: #fff;
            padding: 1em;
            text-decoration: none;
        }
        nav a:hover {
            background-color: #555;
        }
        .container {
            padding: 2em;
        }
        .section {
            margin-bottom: 2em;
        }
        .section h2 {
            color: #333;
        }
        .card {
            background-color: #fff;
            padding: 1em;
            margin: 1em 0;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        footer {
            text-align: center;
            padding: 1em 0;
            background-color: #333;
            color: #fff;
            position: absolute;
            width: 100%;
            bottom: 0;
        }
    </style>
</head>
<body>
    <header>
        <h1>RemodelArte y Subastas</h1>
        <p>Tendencias en Remodelaciones y Subastas de Interiores</p>
    </header>
    <nav>
        <a href="#about">Sobre Nosotros</a>
        <a href="#trends">Tendencias</a>
        <a href="#auction">Subastas</a>
        <a href="#contact">Contacto</a>
    </nav>
    <div class="container">
        <section id="about" class="section">
            <h2>Sobre Nosotros</h2>
            <div class="card">
                <p>Bienvenido a RemodelArte y Subastas, tu destino definitivo para las tendencias en remodelaciones y una plataforma innovadora para la compra y venta de artículos de interiores a través de subastas. Nos especializamos en transformar espacios y ofrecerte las mejores oportunidades para adquirir piezas únicas.</p>
            </div>
        </section>
        <section id="trends" class="section">
            <h2>Tendencias</h2>
            <div class="card">
                <p>Mantente al día con las últimas tendencias en diseño de interiores y remodelaciones. Desde estilos modernos y minimalistas hasta clásicos y elegantes, aquí encontrarás inspiración y consejos para transformar tu hogar.</p>
            </div>
        </section>
        <section id="auction" class="section">
            <h2>Subastas</h2>
            <div class="card">
                <p>Participa en nuestras subastas para comprar y vender artículos de interiores. Descubre piezas únicas y exclusivas que pueden ser tuyas a precios increíbles. ¿Tienes algo que vender? Súbelo a nuestra plataforma y encuentra el mejor postor.</p>
            </div>
        </section>
        <section id="contact" class="section">
            <h2>Contacto</h2>
            <div class="card">
                <p>¿Tienes alguna pregunta o necesitas más información? Contáctanos a través del siguiente formulario:</p>
                <form>
                    <label for="name">Nombre:</label><br>
                    <input type="text" id="name" name="name" required><br><br>
                    <label for="email">Correo Electrónico:</label><br>
                    <input type="email" id="email" name="email" required><br><br>
                    <label for="message">Mensaje:</label><br>
                    <textarea id="message" name="message" rows="4" required></textarea><br><br>
                    <button type="submit">Enviar</button>
                </form>
            </div>
        </section>
    </div>
    <footer>
        <p>&copy; 2024 RemodelArte y Subastas. Todos los derechos reservados.</p>
    </footer>
</body>
</html>
