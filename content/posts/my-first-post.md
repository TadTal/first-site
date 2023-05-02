---
title: "My First Post"
date: 2023-04-15T17:59:03-03:00
draft: false
---

<head>
	<meta charset="UTF-8">
	<title>Servicio de [nombre del servicio]</title>
	<style>
		body {
			background-color: #FFFFFF;
			color: #000000;
			font-family: Arial, sans-serif;
			font-size: 16px;
			line-height: 1.5;
			margin: 0;
			padding: 0;
		}
    h1, h2 {
		margin: 0;
		padding: 0;
	}
	
	h1 {
		font-size: 36px;
		font-weight: bold;
		text-align: center;
		margin: 40px 0;
	}
	
	h2 {
		font-size: 24px;
		font-weight: bold;
		margin: 20px 0;
	}
	
	p {
		margin: 0 0 20px;
	}
	
	ul {
		margin: 0;
		padding: 0;
		list-style: none;
	}
	
	li {
		margin-bottom: 10px;
	}
	
	form {
		margin: 20px 0;
		padding: 20px;
		background-color: #CCCCCC;
		border-radius: 5px;
	}
	
	input[type=text], textarea {
		display: block;
		width: 100%;
		padding: 10px;
		margin-bottom: 20px;
		border-radius: 5px;
		border: none;
		font-size: 16px;
	}
	
	input[type=submit] {
		background-color: #000000;
		color: #FFFFFF;
		border: none;
		border-radius: 5px;
		padding: 10px 20px;
		font-size: 16px;
		cursor: pointer;
	}
	
	input[type=submit]:hover {
		background-color: #FFFFFF;
		color: #000000;
	}
</style>
  </head>
<body>
	<header>
		<h1>Servicio de [nombre del servicio]</h1>
	</header>
	<main>
		<section>
			<h2>Nuestros servicios</h2>
			<ul>
				<li>[Descripción del servicio 1]</li>
				<li>[Descripción del servicio 2]</li>
				<li>[Descripción del servicio 3]</li>
			</ul>
		</section>
		<section>
			<h2>¿Por qué elegirnos?</h2>
			<ul>
				<li>[Ventaja 1]</li>
				<li>[Ventaja 2]</li>
				<li>[Ventaja 3]</li>
				<li>[Ventaja 4]</li>
			</ul>
		</section>
		<section>
			<h2>¿Cómo funciona?</h2>
			<ol>
				<li>[Paso 1]</li>
				<li>[Paso 2]</li>
				<li>[Paso 3]</li>
			</ol>
		</section>
		<section>
			<h2>Testimonios</h2>
			<ul>
				<li>"[Testimonio 1]"</li>
				<li>"[Testimonio 2]"</li>
				<li>"[Testimonio 3]"</li>
			</ul>
		</section>
		<section>
			<h2>Contáctanos</h2>
			<form action="formulario-de-contacto.php" method="post">
				<label for="nombre">Nombre:</label>
				<input type="text" id="nombre" name="nombre" required>
				<label for="email">Correo electrónico:</label>
				<input type="text" id="email" name="email" required>
				<label for="mensaje">Mensaje:</label>
				<textarea id="mensaje" name="mensaje" required></textarea>
				<input type="submit" value="Enviar">
			</form>
		</section>
	</main>
</body>
	
