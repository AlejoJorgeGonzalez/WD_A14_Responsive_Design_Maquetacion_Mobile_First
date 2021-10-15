# ESTRUCTURA BASE DE LA SECCIÓN DE INTERCAMBIO

Se comienza con la arquitectura de la primera sección del main, el cual su diseño es el siguiente

![](../imagenes/img07.png)

Se observa una imagen como background, seguido de un título H2, un párrafo y se termina con una tabla que tiene los valores de las diferentes monedas.

La arquitectura de la primera sección del main en el body de HTML queda como:

~~~css
<!-- Sección con información y valores de las 
monedas -->
<section class="main-exchange-container">
    <!-- Imagen moneda -->
    <div class="backgroundImg"></div>
    <!-- contenedor de texto -->
    <div class="main-exchange-container--title">
        <!-- Titulo h2 -->
        <h2>Visibilizamos todas las tasas de cambio.</h2>
        <!-- Párrafo -->
        <p>Traemos información en tiempo real de las casas de cambio y las monedas más importantes del mundo.</p>
    </div>
    <!-- Contenedor de tabla de conversión de monedas, 
    se utiliza la etiqueta section ya que contiene
    muchos elementos individuales -->
    <section class="main-tables-container">
        <div></div>
    </section>
</section>
~~~

![](../imagenes/img21.png)

Estilos del main en general en CSS

~~~css
main {
    /* Ancho de toda la pantalla */
    width: 100%;
    /* Alto de acuerdo al contenido */
    height: auto;
    /* Color de fondo */
    background-color: var(--off-white);
}
~~~

Estilos de la primera sección del main en CSS

~~~css
.main-exchange-container {
    /* Ancho de toda la pantalla */
    width: 100%;
    /* Alto se ajusta al contenido */
    height: auto;
    /* Separacion con el header para evitar que el botón de
    este se cruce con el contenido del header y con la parte
    de abajo de la segunda seccion de main */
    padding-top: 80px;
    padding-bottom: 30 px;
    /* Texto centrado */
    text-align: center;
}
~~~

![](../imagenes/img21.png)

Estilos del título y parrafo de la primera sección del main

~~~css
.main-exchange-container--title{
    /* Ancho del 90% de la pantalla, como minimo de 288px y 
    máximo de 900px*/
    width: 90%;
    min-width: 288px;
    max-width: 900px;
    /* Se centra el contenedor */
    margin: 0 auto;
}
~~~

![](../imagenes/img22.png)