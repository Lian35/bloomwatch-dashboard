<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Portfolio - Elian</title>
<style>
    /* Reset y tipografía */
    * {
        margin: 0;
        padding: 0;
        box-sizing: border-box;
        font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    }
    body {
        background: #121212;
        color: #f0f0f0;
        line-height: 1.6;
    }
    a {
        color: #ff6f61;
        text-decoration: none;
    }
    a:hover {
        text-decoration: underline;
    }

    /* Contenedor principal */
    .container {
        max-width: 900px;
        margin: 2rem auto;
        padding: 2rem;
        background: #1e1e1e;
        border-radius: 12px;
        box-shadow: 0 4px 20px rgba(0,0,0,0.5);
    }

    h1, h2, h3 {
        color: #ff6f61;
        margin-bottom: 1rem;
    }

    h1 {
        font-size: 2.5rem;
    }
    h2 {
        font-size: 2rem;
        margin-top: 2rem;
    }
    h3 {
        font-size: 1.5rem;
        margin-top: 1.5rem;
    }

    p, li {
        color: #e0e0e0;
        margin-bottom: 0.8rem;
    }

    ul {
        list-style-type: square;
        padding-left: 1.5rem;
        margin-bottom: 1rem;
    }

    /* Secciones de proyectos */
    .project {
        background: #2a2a2a;
        padding: 1rem 1.5rem;
        margin-bottom: 1rem;
        border-radius: 8px;
        transition: transform 0.2s;
    }
    .project:hover {
        transform: scale(1.02);
    }

    /* Tabla de tecnologías */
    table {
        width: 100%;
        border-collapse: collapse;
        margin-top: 1rem;
    }
    th, td {
        padding: 0.75rem 1rem;
        text-align: left;
    }
    th {
        background-color: #ff6f61;
        color: #fff;
    }
    td {
        background-color: #2a2a2a;
    }

    /* Contacto */
    .contact a {
        display: inline-block;
        margin-right: 1rem;
        padding: 0.5rem 1rem;
        border: 1px solid #ff6f61;
        border-radius: 6px;
        transition: background 0.3s, color 0.3s;
    }
    .contact a:hover {
        background: #ff6f61;
        color: #121212;
    }

</style>
</head>
<body>

<div class="container">
    <h1>🌎 Geoespacial | Ciencia de Datos | Desarrollo Web</h1>
    <p>Soy un desarrollador de <strong>Tu País/Región</strong> apasionado por la <strong>Observación de la Tierra</strong> y la creación de soluciones basadas en datos para problemas ambientales y agrícolas. Mi enfoque actual es la <strong>Fenología Global</strong> y los sistemas de alerta temprana.</p>

    <h2>🚀 Proyectos Destacados</h2>

    <div class="project">
        <h3>🌸 BloomWatch - Global Phenology Dashboard</h3>
        <p>Un dashboard en Streamlit para el monitoreo en tiempo casi real de la salud de la vegetación (NDVI/EVI) utilizando datos satelitales (NASA EO). Detecta anomalías térmicas y estrés hídrico.</p>
        <p><a href="https://github.com/Lian35/bloomwatch" target="_blank">Link al Repositorio de BloomWatch</a></p>
    </div>

    <div class="project">
        <h3>Otro Proyecto 1</h3>
        <p>Breve descripción de 1-2 líneas.</p>
    </div>

    <h2>🛠️ Tecnologías y Herramientas</h2>
    <table>
        <tr>
            <th>Categoría</th>
            <th>Herramientas (Lenguajes)</th>
        </tr>
        <tr>
            <td><strong>Análisis Geoespacial</strong></td>
            <td>Python (xarray, rasterio), GDAL, NetCDF</td>
        </tr>
        <tr>
            <td><strong>Lenguajes</strong></td>
            <td>Python, HTML, CSS, JavaScript (Básico)</td>
        </tr>
        <tr>
            <td><strong>Frameworks</strong></td>
            <td>Streamlit, Folium, Matplotlib</td>
        </tr>
        <tr>
            <td><strong>Bases de Datos</strong></td>
            <td>SQL, PostGIS</td>
        </tr>
    </table>

    <h2>📫 Conéctate Conmigo</h2>
    <div class="contact">
        <a href="https://www.linkedin.com/in/<TuEnlaceLinkedIn>" target="_blank">LinkedIn</a>
        <a href="mailto:<TuEmail>">Email</a>
        <a href="<OtroEnlace>" target="_blank">Blog / Twitter</a>
    </div>
</div>

</body>
</html>
