# ICEP-SM
Sitio web oficial del Instituto de Capacitación y Especialización Profesional San Marcos.

<html lang="es">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Instituto San Marcos</title>

<style>
body {
    margin: 0;
    font-family: Arial, sans-serif;
    background: #f4f6f9;
}

/* HEADER */
.header {
    background: #c62828;
    color: white;
    padding: 15px 40px;
    display: flex;
    justify-content: space-between;
    align-items: center;
}

.header h1 {
    font-size: 18px;
    margin: 0;
}

.nav a {
    color: white;
    text-decoration: none;
    margin-left: 20px;
    font-weight: bold;
}

/* HERO */
.hero {
    display: flex;
    flex-wrap: wrap;
    padding: 60px 40px;
    align-items: center;
    background: #ffffff;
}

.hero-text {
    flex: 1;
    min-width: 300px;
}

.hero-text h2 {
    font-size: 42px;
    color: #1f2937;
}

.hero-text p {
    font-size: 16px;
    color: #555;
    max-width: 500px;
}

.btn {
    display: inline-block;
    background: #d32f2f;
    color: white;
    padding: 12px 20px;
    border-radius: 8px;
    margin-top: 15px;
    text-decoration: none;
}

.btn-secondary {
    background: #b71c1c;
}

/* IMAGES GRID */
.hero-images {
    flex: 1;
    display: grid;
    grid-template-columns: repeat(2, 1fr);
    gap: 15px;
    min-width: 300px;
}

.hero-images img {
    width: 100%;
    border-radius: 10px;
    height: 180px;
    object-fit: cover;
}

/* SECTION */
.section {
    padding: 50px 40px;
    text-align: center;
}

.section h3 {
    font-size: 28px;
    color: #1f2937;
}

.section p {
    max-width: 600px;
    margin: auto;
    color: #555;
}

/* FOOTER */
.footer {
    background: #1f2937;
    color: white;
    text-align: center;
    padding: 20px;
}

/* RESPONSIVE */
@media (max-width: 768px) {
    .hero {
        flex-direction: column;
    }
}
</style>

</head>
<body>

<!-- HEADER -->
<div class="header">
    <h1>INSTITUTO SAN MARCOS</h1>
    <div class="nav">
        <a href="#" class="mantenimiento">Inicio</a>
        <a href="#" class="mantenimiento">Cursos</a>
        <a href="#" class="mantenimiento">Capacitación</a>
        <a href="#" class="mantenimiento">Contacto</a>
    </div>
</div>

<!-- HERO -->
<div class="hero">

    <div class="hero-text">
        <h2>INSTITUTO DE CAPACITACIÓN Y ESPECIALIZACIÓN PROFESIONAL SAN MARCOS</h2>

        <p>
        Brindamos formación técnica y profesional de calidad orientada al desarrollo 
        de competencias laborales, fortaleciendo las capacidades de nuestros estudiantes 
        para un mejor desempeño en el mercado laboral.
        </p>

      <button class="mantenimiento">Ver Cursos</button>
<button class="mantenimiento">Explorar Programas</button>
    </div>
<script>
document.querySelectorAll(".mantenimiento").forEach(function(elemento) {
    elemento.addEventListener("click", function(e) {
        e.preventDefault();
        alert("⚠️ Este módulo se encuentra en mantenimiento. Intente más tarde.");
    });
});
</script>
    <div class="hero-images">
        <img src="https://i.postimg.cc/KjZQPFx8/4.png">
        <img src="https://i.postimg.cc/c4crHnDC/Chat-GPT-Image-13-jun-2026-10-42-29-a-m.png">
        <img src="https://images.unsplash.com/photo-1519389950473-47ba0277781c">
        <img src="https://images.unsplash.com/photo-1523240795612-9a054b0db644">
    </div>

</div>

<!-- SECTION -->
<div class="section">
    <h3>¿Quiénes Somos?</h3>
    <p>
    El Instituto de Capacitación y Especialización Profesional San Marcos es una institución 
    comprometida con la formación continua, ofreciendo programas actualizados que responden 
    a las necesidades del mercado laboral y al desarrollo profesional de la población.
    </p>
</div>

<!-- FOOTER -->
<div class="footer">
    © 2026 Instituto San Marcos - Todos los derechos reservados
</div>

</body>
</html>
