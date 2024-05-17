# Página Web sobre Inteligencias Artificiales

Este repositorio contiene el código HTML para una página web sobre Inteligencias Artificiales (IA). La página proporciona una visión general de la IA, sus aplicaciones, ventajas, desafíos y una sección de contacto.

## Estructura del Proyecto

El proyecto consta de un solo archivo HTML con estilos CSS incluidos en el mismo documento. La estructura de la página web es la siguiente:

- **Inicio:** Una introducción a la inteligencia artificial.
- **Aplicaciones:** Ejemplos de aplicaciones prácticas de la IA.
- **Ventajas:** Beneficios de utilizar la IA.
- **Desafíos:** Retos y preocupaciones asociados con la IA.
- **Contacto:** Un formulario para que los visitantes puedan enviar mensajes.

## Contenido del Archivo

### index.html

```html
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Inteligencias Artificiales</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f0f0f0;
        }
        header {
            background-color: #282c34;
            color: white;
            padding: 10px 0;
            text-align: center;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: #61dafb;
        }
        nav a {
            padding: 15px;
            text-decoration: none;
            color: white;
        }
        nav a:hover {
            background-color: #21a1f1;
        }
        .container {
            padding: 20px;
        }
        .section {
            background-color: white;
            margin: 20px 0;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        footer {
            background-color: #282c34;
            color: white;
            text-align: center;
            padding: 10px 0;
            position: fixed;
            bottom: 0;
            width: 100%;
        }
        form {
            display: flex;
            flex-direction: column;
        }
        form input, form textarea {
            margin-bottom: 10px;
            padding: 10px;
            border: 1px solid #ccc;
            border-radius: 4px;
        }
        form button {
            padding: 10px;
            background-color: #61dafb;
            border: none;
            color: white;
            border-radius: 4px;
            cursor: pointer;
        }
        form button:hover {
            background-color: #21a1f1;
        }
    </style>
</head>
<body>
    <header>
        <h1>Inteligencias Artificiales</h1>
    </header>
    <nav>
        <a href="#overview">Inicio</a>
        <a href="#applications">Aplicaciones</a>
        <a href="#advantages">Ventajas</a>
        <a href="#challenges">Desafíos</a>
        <a href="#contact">Contacto</a>
    </nav>
    <div class="container">
        <section id="overview" class="section">
            <h2>¿Qué es la Inteligencia Artificial?</h2>
            <p>La inteligencia artificial (IA) se refiere a la simulación de procesos de inteligencia humana por par
