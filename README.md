<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <title>Curso de Computadores - Luis Carlos Duarte</title>

    <style>
        body {
            font-family: 'Segoe UI', sans-serif;
            margin: 0;
            background: linear-gradient(120deg, #1e3c72, #2a5298);
            color: #333;
        }

        header {
            background: rgba(0,0,0,0.7);
            color: white;
            padding: 25px;
            text-align: center;
        }

        nav {
            background: #111;
            padding: 12px;
            text-align: center;
        }

        nav a {
            color: #00d4ff;
            margin: 15px;
            text-decoration: none;
            font-weight: bold;
        }

        nav a:hover {
            color: white;
        }

        section {
            background: white;
            margin: 20px;
            padding: 20px;
            border-radius: 10px;
        }

        .card {
            background: #f1f1f1;
            padding: 15px;
            margin-top: 10px;
            border-left: 5px solid #2a5298;
        }

        img {
            width: 100%;
            border-radius: 10px;
            margin-top: 10px;
        }

        footer {
            text-align: center;
            padding: 15px;
            color: white;
        }

        button {
            background: #2a5298;
            color: white;
            border: none;
            padding: 10px 15px;
            border-radius: 5px;
            cursor: pointer;
        }

        button:hover {
            background: #1e3c72;
        }
    </style>
</head>

<body>

<header>
    <h1>Curso de Computadores</h1>
    <p>Creado por Luis Carlos Duarte</p>
</header>

<nav>
    <a href="#">Inicio</a>
    <a href="#">Temas</a>
    <a href="#">Contacto</a>
</nav>

<section>
    <h2>Bienvenido</h2>
    <p>Este es mi proyecto del curso de computadores donde explico conceptos básicos de forma sencilla.</p>

    <div class="card">
        <h3>💻 Tema 1: Hardware</h3>
        <img src="https://upload.wikimedia.org/wikipedia/commons/6/6a/Computer_components.jpg">
        <p>Partes físicas del computador como teclado, mouse y CPU.</p>
    </div>

    <div class="card">
        <h3>🧠 Tema 2: Software</h3>
        <img src="https://upload.wikimedia.org/wikipedia/commons/3/3b/Software-diagram.png">
        <p>Programas que hacen funcionar el computador.</p>
    </div>

    <br>
    <button onclick="mensaje()">Haz clic aquí</button>
</section>

<section>
    <h2>Contacto</h2>
    <p>Si deseas comunicarte conmigo:</p>

    <div class="card">
        <p><strong>Nombre:</strong> Luis Carlos Duarte</p>
        <p><strong>Teléfono:</strong> <a href="tel:3142032426">3142032426</a></p>
        <p><strong>Email:</strong> luis.duarte02@uptc.edu.co</p>
    </div>
</section>

<footer>
    <p>© 2026 Luis Carlos Duarte</p>
</footer>

<script>
function mensaje() {
    alert("¡Bienvenido a mi página web 😎!");
}
</script>

</body>
</html>
