/* Reset de estilos básicos */
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

/* Estilos generales */
body {
    font-family: 'IBM', sans-serif;
    line-height: 1.6;
    color: #333;
}

header {
    background-color: #003366;
    color: #fff;
    padding: 1rem;
}

nav ul {
    list-style: none;
    display: flex;
}

nav ul li {
    margin-right: 20px;
}

nav ul li a {
    text-decoration: none;
    color: #fff;
}

section {
    padding: 2rem;
}

h1, h2, h3 {
    color: #003366;
}

/* Estilos para la sección de proyectos */
.proyecto {
    margin-bottom: 20px;
}

.proyecto img {
    max-width: 100%;
}

/* Estilos para la sección de contacto */
#contacto a {
    display: inline-block;
    background-color: #003366;
    color: #fff;
    padding: 10px 20px;
    text-decoration: none;
    border-radius: 5px;
    margin-top: 10px;
}

/* Estilos para el footer */
footer {
    background-color: #003366;
    color: #fff;
    text-align: center;
    padding: 1rem;
}

/* Media query para dispositivos móviles */
@media (max-width: 768px) {
    nav ul {
        flex-direction: column;
    }

    nav ul li {
        margin-right: 0;
        margin-bottom: 10px;
    }

    header {
        text-align: center;
    }
}
