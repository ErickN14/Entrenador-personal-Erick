# Entrenador-personal-Erick
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Erick Paz - Entrenador Personal</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <h1>Erick Paz - Entrenador Personal Especializado en Fisicoculturismo</h1>
        <nav>
            <ul>
                <li><a href="#services">Servicios</a></li>
                <li><a href="#news">Noticias</a></li>
                <li><a href="#store">Tienda de Suplementos</a></li>
                <li><a href="#contact">Contacto</a></li>
            </ul>
        </nav>
    </header>

    <section id="services">
        <h2>Servicios</h2>
        <p>Ofrecemos asesoría online, entrenamiento personal, y preparación para competencias de fisicoculturismo.</p>
        <button onclick="showServiceForm()">Contratar un Servicio</button>
        <div id="service-form" class="hidden">
            <form id="serviceForm">
                <label for="serviceType">Selecciona un servicio:</label>
                <select id="serviceType" name="serviceType">
                    <option value="online">Asesoría Online</option>
                    <option value="personal">Entrenamiento Personal</option>
                    <option value="competition">Preparación para Competencia</option>
                </select>
                <input type="submit" value="Enviar">
            </form>
        </div>
    </section>

    <section id="news">
        <h2>Noticias de Fisicoculturismo</h2>
        <div id="newsContainer">
            <!-- Aquí se mostrarán las noticias -->
        </div>
        <button onclick="addNews()">Subir una noticia</button>
    </section>

    <section id="store">
        <h2>Tienda de Suplementos</h2>
        <div id="storeContainer">
            <!-- Aquí se mostrarán los productos de la tienda -->
        </div>
    </section>

    <section id="contact">
        <h2>Contacto</h2>
        <p>Para más información, contáctanos en: <a href="mailto:erickpaz@fitness.com">erickpaz@fitness.com</a></p>
    </section>

    <script src="app.js"></script>
</body>
</html>
