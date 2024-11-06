<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Portafolio Electrónico</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Portafolio Electrónico del Curso</h1>
        <nav>
            <ul>
                <li><a href="#home">Inicio</a></li>
                <li><a href="#about">¿Quiénes somos?</a></li>
                <li>
                    <a href="#temas">Temas</a>
                    <ul class="submenu">
                        <li><a href="#tema1">Gestión de la Información</a></li>
                        <li><a href="#tema2">Trabajo Colaborativo en Línea</a></li>
                        <li><a href="#tema3">Internet, Navegadores y Plataformas Educativas</a></li>
                        <li><a href="#tema4">Manejo de Medios y Portafolio Electrónico</a></li>
                    </ul>
                </li>
            </ul>
        </nav>
    </header>

    <!-- Sección de Inicio -->
    <section id="home" class="hero-section">
        <h2>Bienvenidos a nuestro Portafolio Electrónico</h2>
        <p>Explora nuestras actividades, aprendizajes y evidencias a lo largo del curso.</p>
    </section>

    <!-- Sección ¿Quiénes somos? -->
    <section id="about">
        <h3>¿Quiénes somos?</h3>
        <div class="team-member">
            <img src="ruta_foto_integrante.jpg" alt="Foto del integrante">
            <h4>Nombre Completo</h4>
            <p>Carrera: Ingeniería Industrial</p>
            <p>Semestre: 5to</p>
            <p>Aficiones: Música, deportes y programación</p>
        </div>
        <!-- Repetir bloque .team-member por cada integrante -->
        <div class="team-group-photo">
            <img src="ruta_foto_equipo.jpg" alt="Foto del equipo completo">
            <p>Equipo completo trabajando juntos para alcanzar nuestras metas.</p>
        </div>
    </section>

    <!-- Sección Temas -->
    <section id="temas">
        <h3>Temas del Curso</h3>
        <!-- Tema 1 -->
        <div id="tema1" class="tema">
            <h4>Gestión de la Información</h4>
            <p>Descripción de las competencias desarrolladas y reflexiones.</p>
            <p>Evidencias del trabajo en equipo: [añadir enlaces o documentos]</p>
        </div>
        <!-- Tema 2 -->
        <div id="tema2" class="tema">
            <h4>Trabajo Colaborativo en Línea</h4>
            <p>Descripción de las competencias desarrolladas y reflexiones.</p>
            <p>Evidencias del trabajo en equipo: [añadir enlaces o documentos]</p>
        </div>
        <!-- Tema 3 -->
        <div id="tema3" class="tema">
            <h4>Internet, Navegadores y Plataformas Educativas</h4>
            <p>Descripción de las competencias desarrolladas y reflexiones.</p>
            <p>Evidencias del trabajo en equipo: [añadir enlaces o documentos]</p>
        </div>
        <!-- Tema 4 -->
        <div id="tema4" class="tema">
            <h4>Manejo de Medios y Portafolio Electrónico</h4>
            <p>Descripción de las competencias desarrolladas y reflexiones.</p>
            <p>Evidencias del trabajo en equipo: [añadir enlaces o documentos]</p>
        </div>
    </section>

    <footer>
        <p>&copy; 2024 Portafolio Electrónico. Todos los derechos reservados.</p>
    </footer>
</body>
</html>


/* General */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: Arial, sans-serif;
}

body {
    color: #333;
    background-color: #f4f7f6;
}

/* Header */
header {
    background-color: #003366;
    color: white;
    padding: 1em;
    text-align: center;
}

header nav ul {
    display: flex;
    justify-content: center;
    list-style: none;
}

header nav ul li {
    margin: 0 15px;
    position: relative;
}

header nav ul li a {
    color: white;
    text-decoration: none;
}

.submenu {
    display: none;
    position: absolute;
    top: 100%;
    left: 0;
    background-color: #003366;
}

header nav ul li:hover .submenu {
    display: block;
}

.submenu li {
    margin: 0;
}

/* Hero Section */
.hero-section {
    background-color: #e0f2f1;
    padding: 50px 20px;
    text-align: center;
}

.hero-section h2 {
    margin-bottom: 15px;
}

/* ¿Quiénes somos? */
#about {
    padding: 20px;
    margin: 20px;
    text-align: center;
}

.team-member {
    margin: 15px;
    display: inline-block;
    text-align: left;
}

.team-member img {
    max-width: 150px;
    border-radius: 50%;
}

.team-group-photo img {
    max-width: 400px;
    margin-top: 20px;
}

/* Temas */
.tema {
    padding: 20px;
    margin: 20px;
    background-color: #f4f7f6;
    border-left: 4px solid #00796b;
}

/* Footer */
footer {
    background-color: #003366;
    color: white;
    text-align: center;
    padding: 10px;
    position: fixed;
    bottom: 0;
    width: 100%;
}

