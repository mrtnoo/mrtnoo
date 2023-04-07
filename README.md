
<!DOCTYPE html>
<html>
<head>
	<title>Bienvenido</title>
	<link rel="stylesheet" type="text/css" href="style.css">
</head>
<body>
	<header>
		<h1>Bienvenido</h1>
		<nav>
			<ul>
				<li><a href="#">Inicio</a></li>
				<li><a href="#">Acerca de nosotros</a></li>
				<li><a href="#">Contacto</a></li>
			</ul>
		</nav>
	</header>
	<section>
		<h2>¡Gracias por visitarnos!</h2>
		<p>En nuestro sitio web encontrar



martin huerta
crea una pagina web con html y css en la misma hoja para pagina de bienvenida
Claro, aquí tienes un ejemplo de cómo crear una página de bienvenida con HTML y CSS en la misma hoja:

html
Copy code
<!DOCTYPE html>
<html>
<head>
	<title>Bienvenido</title>
	<style>
		body {
			background-color: #f2f2f2;
			font-family: Arial, sans-serif;
			margin: 0;
			padding: 0;
		}

		header {
			background-color: #333;
			color: #fff;
			display: flex;
			align-items: center;
			justify-content: space-between;
			padding: 20px;
		}

		h1 {
			margin: 0;
		}

		nav ul {
			list-style: none;
			margin: 0;
			padding: 0;
			display: flex;
		}

		nav li {
			margin: 0 10px;
		}

		nav a {
			color: #fff;
			text-decoration: none;
			font-weight: bold;
		}

		section {
			margin: 50px;
			text-align: center;
		}

		h2 {
			margin-top: 0;
		}

		p {
			font-size: 18px;
			line-height: 1.5;
		}
	</style>
</head>
<body>
	<header>
		<h1>Bienvenido</h1>
		<nav>
			<ul>
				<li><a href="#">Inicio</a></li>
				<li><a href="#">Acerca de nosotros</a></li>
				<li><a href="#">Contacto</a></li>
			</ul>
		</nav>
	</header>
	<section>
		<h2>¡Gracias por visitarnos!</h2>
		<p>En nuestro sitio web encontrarás información útil y relevante sobre una variedad de temas.</p>
	</section>
</body>
</html>
