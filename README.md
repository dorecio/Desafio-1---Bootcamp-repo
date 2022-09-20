# Desafio-1---Bootcamp-repo
Proyecto 1 en Bootcamp 2022

## Propósito

Este proyecto fué ralizado con la finalidad de aprender conceptos de sémantica, refactorización y accesibilidad en html, para así cumplir el propósito principal declarado en la Historia del usuario.
Se otorga un código de inicio sobre el cual trabajé aprendiendo habilidades de manejo de repositorios con las mejores prácticas.


## Historia del Usuario

COMO UNA agencia de marketing
QUIERO una base de código que siga estándares de accesibilidad
PARA QUE nuestro sitio web se encuentre optimizado para los motores de bûsqueda

## Criterios de aceptación

CONSIDERANDO una página web que cumple con estándares de accesibilidad
CUANDO veo el código fuente.
ENTONCES encuentro elemenetos semánticos de HTML 
CUANDO veo la estructura de los elementos de HTML
ENTONCES encuentro que los elementos siguen una estructura lógica e independiente de estilo y posicionamiento
CUANDO veo los elementos de imagen
ENTONCES encuentro atributos "alt" accesibles 
CUANDO veo los atributos de encabezado
ENTONCES siguen un orden secuencial
CUANDO veo el elemento de titulo 
ENTONCES encuentro un titulo conciso y descriptivo

## Istrucciones que se siguiuieron para completar el desafío


1. Clone su código de inicio de este enlace [inicio](hgit@github.com:coding-boot-camp/legendary-memory.gitttp:// "inicio")

2. Refactorice el código para que cumpla con los criterios de aceptación.

3. Asegúrese de que su trabajo cumpla con la lista completa de requisitos de calificación.

4. Siga las instrucciones para enviar su desafío para revisión.

## Criterios técnicos de aceptación

1. Cumple con todos los criterios de aceptación anteriores más las siguientes mejoras en el código:

2. Los enlaces de la aplicación funcionan correctamente.

3. Los selectores y propiedades CSS de la aplicación están consolidados y organizados para seguir la estructura semántica.

4. El archivo CSS de la aplicación está correctamente comentado.

## Requisitos para despliegue

1. Aplicación desplegada en URL en vivo.

2. La aplicación se carga sin errores.

3. URL de GitHub de la aplicación enviada.

4. Repositorio de GitHub que contiene el código de aplicación.

## Calidad de la aplicación

La aplicación se asemeja (al menos el 90 %) a las capturas de pantalla proporcionada

![foto demo](./assets/images/01-html-css-git-homework-demo.png)

## Calidad del repositorio

1. El repositorio tiene un nombre único.

2. El repositorio sigue las mejores prácticas para la estructura de archivos y las convenciones de denominación.

3. El repositorio sigue las mejores prácticas para convenciones de denominación de clase/identificador, sangría, comentarios de calidad, etc.

4. El repositorio contiene varios mensajes descriptivos sobre hacer commit.

5. El repositorio contiene un archivo README de calidad con descripción, captura de pantalla y enlace a la aplicación desplegada.

## Instruccioines para enviar el desafío

Se envía lo siguiente:

La URL de la aplicación desplegada.

La URL del repositorio de GitHub que contiene su código. Dé al repositorio un nombre único e incluya un archivo README que describa el proyecto.

##Código html refactorizado

## Código HTML después de cumplir el desafío

<!DOCTYPE html>
<html lang="en-us">

<head>
    <meta charset="UTF-8" />
    <meta name="description" content="search engine optimization and refactoring">
    <meta name="keywords" content="HTML, CSS">
    <title>Horiseon online business solutions</title>
    <link rel="stylesheet" href="./assets/css/style.css">
</head>

<body>
    <header>
      <h1>Hori<span class="seo">seo</span>n</h1>
        <nav>
          <ul>
            <li><a href="#search-engine-optimization">Optimización del motor de búsqueda</a></li>
            <li><a href="#online-reputation-management">Gestión de reputación en línea</a></li>
            <li><a href="#social-media-marketing">Comercialización en redes sociales</a></li>
          </ul>
        </nav>
    </header>
    <div class="hero"></div>
    <main>
       <section id="search-engine-optimization">
           <img src="./assets/images/search-engine-optimization.jpg" alt="Libro con herramientas para mejorar la busqueda de paginas web"
                class="float-left" />
           <h2>Optimización del motor de búsqueda</h2>
           <p>El dominio del uso de Internet móvil significa que los usuarios están buscando el negocio correcto
              mientras viajan, compran o se sientan en su sofá en casa. Search Engine Optimization (SEO) le
              permite aumentar su visibilidad y encontrar los clientes adecuados para su negocio.</p>
       </section>
       <section id="online-reputation-management">
           <img src="./assets/images/online-reputation-management.jpg" alt="Computadora con un sistema para administrar reputacion de paginas web"
                class="float-right" />
           <h2>Gestión de reputación en línea</h2>
           <p>La web está llena de opiniones, y algunas de ellas pueden ser negativas. Las redes sociales permiten
              que cualquier persona con conexión a Internet diga lo que quiera sobre su negocio. La gestión de
              reputación en línea le da el control sobre lo que ven los clientes potenciales cuando buscan su
              negocio.</p>
       </section>
       <section id="social-media-marketing">
           <img src="./assets/images/social-media-marketing.jpg" alt="imagen de medios sociales para negocios en linea " 
                class="float-left" />
           <h2>Comercialización en redes sociales</h2>
           <p>Las redes sociales siguen teniendo una influencia considerable en los hábitos de compra. La
              comercialización en redes sociales le ayuda a determinar qué plataformas son adecuadas para su
              marca, utilizando análisis para encontrar los mercados adecuados y aumentar su generación de
              clientes potenciales.</p>
       </section>
    </main>
        <aside>
            <section>
                <h3>Generación de clientes potenciales</h3>
                <img src="./assets/images/lead-generation.png" />
                <p>Las estrategias entrantes para la generación de clientes potenciales requieren menos trabajo para su
                    negocio, lo que lleva a los clientes directamente a su sitio web.</p>
            </section>
            <section>
                <h3>Conocimiento de la marca</h3>
                <img src="./assets/images/brand-awareness.png" />
                <p>Los usuarios encuentran su negocio a través de búsquedas pagas y orgánicas, lo que aumenta la
                    clasificación de búsqueda y la visibilidad de su negocio.</p>
            </section>
            <section>
                <h3>Gestión de costos</h3>
                <img src="./assets/images/cost-management.png" />
                <p>A medida que aumenta la clasificación de búsqueda de su negocio, sus costos de publicidad disminuyen
                    y ya no necesita publicitar su página.</p>
            </section>
        </aside>   
    <footer>
        <h2>Made with ❤️️ by Horiseon</h2>
        <p>&copy; 2019 Horiseon Social Solution Services, Inc.</p>
    </footer>
</body>

</html>

## Hoja de estilos CSS

  /* TODO: Aplicar formato a todo (Formato Universal) */
* {
    box-sizing: border-box;
    padding: 0;
    margin: 0;
}

/* Aplica color de fondo a todo lo contenido dentro del bloque "body" */
body {
    background-color: #d9dcd6;
}  

  /* TODO: Aplica formato a todo elemento dentro de "header" */
header  {
    padding: 20px;
    font-family: 'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif;
    background-color: #2a607c;
    color: #ffffff;
}

header h1 {
    display: inline-block;
    font-size: 48px;
}

header h1 .seo {
    color: #d9dcd6;
}
 
  /* TODO: Aplica formato a barra de navegación */
nav {
    padding-top: 15px;
    margin-right: 20px;
    float: right;
    font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
    font-size: 20px;
}

header nav ul {
    list-style-type: none;
}

header nav ul li {
    display: inline-block;
    margin-left: 25px;
}

/* Dar formato al enlace */
a {
    color: #ffffff;
    text-decoration: none;
}

p {
    font-size: 16px;
}
  /* TODO: Aplica formato a clase "hero" */ 
.hero {
    height: 800px;
    width: 100%;
    margin-bottom: 25px;
    background-image: url("../images/digital-marketing-meeting.jpg");
    background-size: cover;
    background-position: center;
}

  /* TODO: Aplica formato a todo el contenido dentro de "main" */
main {
    width: 75%;
    display: inline-block;
    margin-left: 20px;
}

  /* TODO: Aplica formato a todos los elementos dentro de los "section" contenidos en "main" */
main section {
    margin-bottom: 20px;
    padding: 50px;
    height: 300px;
    font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
    background-color: #0072bb;
    color: #ffffff;
}

/* Aplica formato a las imagenes que estan en cada "section" de "main" */
main section img {
    max-height: 200px;
}

main section h2 {
    margin-bottom: 20px;
    font-size: 36px;
}
.float-left {
    float: left;
    margin-right: 25px;
}

.float-right {
    float: right;
    margin-left: 25px;
}

/* TODO: Aplica formato a todos los elementos dentro de "aside" */
aside {
    margin-right: 20px;
    padding: 20px;
    clear: both;
    float: right;
    width: 20%;
    height: 100%;
    font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
    background-color: #2589bd;
}

  /* TODO: Aplica a todo elemento dentro de "section" */
section {
    margin-bottom: 32px;
    color: #ffffff;
}

section h3 {
     margin-bottom: 10px;
     text-align: center;
 }

section img {
    display: block;
    margin: 10px auto;
    max-width: 150px;
}

  /* TODO: Aplica formato a todos los elementos contenidos en "footer" */
footer {
    padding: 30px;
    clear: both;
    font-family: 'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif;
    text-align: center;
}

footer h2 {
    font-size: 20px;
}
