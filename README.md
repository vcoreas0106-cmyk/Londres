# Londres[index.html.html](https://github.com/user-attachments/files/33087598/index.html.html)
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Londres - TECNOFES 2026</title>
    <style>
        /* Estilos Generales */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }

        body {
            background-color: #f4f6f9;
            color: #333;
            line-height: 1.6;
        }

        /* Encabezado / Hero */
        header {
            background: linear-gradient(rgba(0, 0, 0, 0.6), rgba(0, 0, 0, 0.6)), url('https://unsplash.com') no-repeat center center/cover;
            color: white;
            text-align: center;
            padding: 100px 20px;
        }

        header h1 {
            font-size: 3rem;
            margin-bottom: 10px;
            letter-spacing: 2px;
        }

        header p {
            font-size: 1.2rem;
            font-style: italic;
        }

        /* Barra de Navegación */
        nav {
            background-color: #0b2240; /* Azul clásico londinense */
            position: sticky;
            top: 0;
            z-index: 1000;
            text-align: center;
        }

        nav a {
            display: inline-block;
            color: white;
            text-decoration: none;
            padding: 15px 20px;
            font-weight: bold;
            transition: background 0.3s;
        }

        nav a:hover {
            background-color: #ca1f26; /* Rojo cabina telefónica */
        }

        /* Contenedor Principal */
        .container {
            max-width: 1100px;
            margin: 20px auto;
            padding: 0 20px;
        }

        /* Secciones */
        section {
            background: white;
            padding: 30px;
            margin-bottom: 20px;
            border-radius: 8px;
            box-shadow: 0 4px 6px rgba(0,0,0,0.05);
        }

        section h2 {
            color: #0b2240;
            margin-bottom: 15px;
            border-bottom: 3px solid #ca1f26;
            display: inline-block;
            padding-bottom: 5px;
        }

        /* Cuadrícula de Lugares Turísticos */
        .grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
            gap: 20px;
            margin-top: 20px;
        }

        .card {
            background: #f9f9f9;
            border: 1px solid #ddd;
            border-radius: 6px;
            padding: 15px;
            text-align: center;
        }

        .card h3 {
            color: #ca1f26;
            margin-bottom: 10px;
        }

        /* Pie de página */
        footer {
            background-color: #0b2240;
            color: white;
            text-align: center;
            padding: 20px;
            margin-top: 40px;
            font-size: 0.9rem;
        }
    </style>
</head>
<body>

    <!-- Encabezado principal -->
    <header>
        <h1>Bienvenidos a Londres</h1>
        <p>Explorando la capital del Reino Unido para el TECNOFES 2026</p>
    </header>

    <!-- Menú de navegación interna -->
    <nav>
        <a href="#historia">Historia</a>
        <a href="#lugares">Lugares Turísticos</a>
        <a href="#cultura">Cultura</a>
    </nav>

    <!-- Contenido del sitio -->
    <div class="container">

        <!-- Sección Historia -->
        <section id="historia">
            <h2>Historia de la Ciudad</h2>
            <p>Londres es una de las ciudades más antiguas e influyentes del mundo. Fundada por los romanos hace casi dos milenios bajo el nombre de <em>Londinium</em>, ha sobrevivido a plagas, grandes incendios y guerras, convirtiéndose hoy en un epicentro global de finanzas, arte y diversidad cultural.</p>
        </section>

        <!-- Sección Lugares Turísticos -->
        <section id="lugares">
            <h2>Lugares Emblemáticos</h2>
            <p>Descubre los puntos de interés más importantes que definen el paisaje londinense:</p>
            
            <div class="grid">
                <div class="card">
                    <h3>El Big Ben</h3>
                    <p>La famosa torre del reloj del Palacio de Westminster, conocida oficialmente como la Torre de Isabel.</p>
                </div>
                <div class="card">
                    <h3>London Eye</h3>
                    <p>Una gigantesca noria a orillas del río Támesis que ofrece las mejores vistas panorámicas de la ciudad.</p>
                </div>
                <div class="card">
                    <h3>El Puente de la Torre</h3>
                    <p>El icónico puente levadizo victoriano que cruza el Támesis, famoso en todo el mundo.</p>
                </div>
            </div>
        </section>

        <!-- Sección Cultura -->
        <section id="cultura">
            <h2>Cultura y Datos Curiosos</h2>
            <p>Londres es famosa por sus icónicos autobuses rojos de dos pisos, sus cabinas telefónicas clásicas y su monarquía. Además, cuenta con museos de entrada gratuita como el Museo Británico y la Galería Nacional, lo que la convierte en una capital del conocimiento accesible para todos.</p>
        </section>

    </div>

    <!-- Pie de página con tus datos escolares -->
    <footer>
        <p>TECNOFES 2026 | Colegio Bautista | Diseñado por Maria Lopez</p>
    </footer>
