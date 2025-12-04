# RMsaniplas-web
Página oficial de SaniPlas R&amp;M Limitada.
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>SaniPlas R&M Limitada – Fumigaciones Profesionales</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>

    <header>
        <div class="logo">
            <img src="logo.png" alt="Logotipo SaniPlas R&M" class="logo-img">
            <div>
                <h1>SaniPlas R&M Ltda.</h1>
                <p>Control de Plagas y Sanitización Profesional</p>
            </div>
        </div>

        <nav>
            <a href="#servicios">Servicios</a>
            <a href="#nosotros">Nosotros</a>
            <a href="#contacto">Contacto</a>
        </nav>
    </header>

    <section class="hero">
        <h2>Protegemos tu hogar y tu empresa</h2>
        <p>Servicios de fumigación con estándares profesionales y certificación sanitaria.</p>
        <a href="#contacto" class="btn">Solicitar Cotización</a>
    </section>

    <section id="servicios" class="servicios">
        <h2>Servicios</h2>
        <div class="cards">
            <div class="card">
                <h3>Fumigación General</h3>
                <p>Eliminación de insectos rastreros y voladores en hogares, empresas y bodegas.</p>
            </div>
            <div class="card">
                <h3>Control de Roedores</h3>
                <p>Instalación de trampas, cebos y sellos preventivos.</p>
            </div>
            <div class="card">
                <h3>Sanitización</h3>
                <p>Desinfección de ambientes con productos certificados y seguros.</p>
            </div>
            <div class="card">
                <h3>Programa Integral de Plagas</h3>
                <p>Planes mensuales para empresas, restaurantes e industrias.</p>
            </div>
        </div>
    </section>

    <section id="nosotros" class="nosotros">
        <h2>Sobre Nosotros</h2>
        <p>
            En <strong>SaniPlas R&M Limitada</strong> contamos con experiencia en control de plagas y sanitización,
            ofreciendo servicios confiables, rápidos y efectivos. Nuestro equipo utiliza productos aprobados por
            autoridades sanitarias y técnicas seguras para personas, mascotas y el medio ambiente.
        </p>
    </section>

    <section id="contacto" class="contacto">
        <h2>Contacto</h2>
        <form>
            <input type="text" placeholder="Nombre" required>
            <input type="email" placeholder="Correo electrónico" required>
            <input type="text" placeholder="Teléfono" required>
            <textarea placeholder="Mensaje o solicitud de cotización" required></textarea>
            <button type="submit">Enviar</button>
        </form>
    </section>

    <footer>
        <p>SaniPlas R&M Limitada — Todos los Derechos Reservados © 2025</p>
    </footer>

</body>
</html>
body {
    margin: 0;
    font-family: Arial, sans-serif;
    background: #f5f5f5;
    color: #333;
}

header {
    background: #0b6e4f;
    color: white;
    padding: 15px 40px;
    display: flex;
    justify-content: space-between;
    align-items: center;
    flex-wrap: wrap;
}

.logo {
    display: flex;
    align-items: center;
    gap: 15px;
}

.logo-img {
    width: 80px;
    height: auto;
}

header nav a {
    margin: 0 10px;
    color: white;
    text-decoration: none;
    font-weight: bold;
}

.hero {
    background: url('https://images.unsplash.com/photo-1581579188871-45ea61f2a0c8') center/cover;
    color: white;
    text-align: center;
    padding: 120px 20px;
}

.hero .btn {
    background: #0b6e4f;
    padding: 12px 25px;
    color: white;
    text-decoration: none;
    border-radius: 5px;
    font-size: 18px;
}

.servicios {
    padding: 50px 20px;
    text-align: center;
}

.cards {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    gap: 20px;
}

.card {
    background: white;
    padding: 20px;
    width: 250px;
    border-radius: 10px;
    box-shadow: 0 2px 6px rgba(0,0,0,0.1);
}

.nosotros, .contacto {
    padding: 50px 20px;
    background: white;
}

form {
    max-width: 500px;
    margin: auto;
    display: flex;
    flex-direction: column;
    gap: 12px;
}

input, textarea {
    padding: 12px;
    border-radius: 5px;
    border: 1px solid #ccc;
}

button {
    background: #0b6e4f;
    color: white;
    padding: 12px;
    border: none;
    border-radius: 5px;
    cursor: pointer;
}

footer {
    background: #0b6e4f;
    color: white;
    text-align: center;
    padding: 15px;
    margin-top: 30px;
}
