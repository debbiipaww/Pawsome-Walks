![index.html](Attachments/ECF3FFA4-32C0-4A1F-9E6C-176AB7819917.png)  
  
<!DOCTYPE html>  
<html lang="es">  
<head>  
    <meta charset="UTF-8">  
    <title>Paseo de Perros Feliz</title>  
    <style>  
        body {  
            font-family: Arial, sans-serif;  
            margin: 0;  
            background-color: #f4f4f4;  
        }  
        header {  
            background-color: #4CAF50;  
            color: white;  
            padding: 20px;  
            text-align: center;  
        }  
        nav {  
            background-color: #333;  
            padding: 10px;  
            text-align: center;  
        }  
        nav a {  
            color: white;  
            margin: 10px;  
            text-decoration: none;  
            font-weight: bold;  
        }  
        nav a:hover {  
            color: #4CAF50;  
        }  
        .container {  
            padding: 20px;  
        }  
        .services {  
            display: flex;  
            gap: 20px;  
            flex-wrap: wrap;  
        }  
        .card {  
            background: white;  
            padding: 15px;  
            border-radius: 10px;  
            flex: 1;  
            min-width: 200px;  
            box-shadow: 0 2px 5px rgba(0,0,0,0.1);  
        }  
        footer {  
            background-color: #333;  
            color: white;  
            text-align: center;  
            padding: 10px;  
            margin-top: 20px;  
        }  
        button {  
            background-color: #4CAF50;  
            border: none;  
            padding: 10px;  
            color: white;  
            border-radius: 5px;  
            cursor: pointer;  
        }  
        button:hover {  
            background-color: #45a049;  
        }  
    </style>  
</head>  
<body>  
  
<header>  
    <h1>Paseo de Perros Feliz 🐕</h1>  
    <p>Cuidamos y paseamos a tu mejor amigo</p>  
</header>  
  
<nav>  
    <a href="#inicio">Inicio</a>  
    <a href="#servicios">Servicios</a>  
    <a href="#contacto">Contacto</a>  
</nav>  
  
<div class="container" id="inicio">  
    <h2>Bienvenido</h2>  
    <p>Ofrecemos paseos seguros, divertidos y llenos de cariño para tu perro. Nos aseguramos de que tu mascota esté feliz y activa.</p>  
</div>  
  
<div class="container" id="servicios">  
    <h2>Nuestros Servicios</h2>  
    <div class="services">  
        <div class="card">  
            <h3>Paseo Individual</h3>  
            <p>Atención personalizada para tu perro.</p>  
        </div>  
        <div class="card">  
            <h3>Paseo en Grupo</h3>  
            <p>Socialización con otros perros.</p>  
        </div>  
        <div class="card">  
            <h3>Cuidado en Casa</h3>  
            <p>Visitamos a tu mascota cuando no estás.</p>  
        </div>  
    </div>  
</div>  
  
<div class="container" id="contacto">  
    <h2>Contáctanos</h2>  
    <p>Email: contacto@paseoperros.com</p>  
    <p>Teléfono: 123-456-7890</p>  
    <button onclick="alert('¡Gracias por tu interés!')">Enviar mensaje</button>  
</div>  
  
<footer>  
    <p>© 2026 Paseo de Perros Feliz</p>  
</footer>  
  
</body>  
</html>  
