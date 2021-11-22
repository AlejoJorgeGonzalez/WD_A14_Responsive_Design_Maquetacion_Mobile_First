# ESTRUCTURA DE SECCIÓN DE PLANES

La sección de planes tiene el siguiente diseño.

![](../imagenes/img58.png)

Se puede observar que esta sección tiene de color de fondo el color principal, esta estructurado con un encabezado h2, seguido de un párrafo. Despues tiene varias tarjetas que se cambian uno con la otra con flechas, estas tarjetas esta compuesto por un elemento flotante, un encabezado, el costo en una fuente mas grande de lo normal, un párrafo y un botón.

La estructura de HTML queda como:
~~~html
<!-- Sección de planes -->
<section id="plans" class="main-plans-container">
    <!-- Parte del encabezado y el párrafo -->
    <div class="plans--title">
        <h2>Escoge el plan que mejor se ajuste a ti.</h2>
        <p>Cualquier plan te da acceso completo a nuestra plataforma</p>
    </div>
    <!-- Contenedor de las tarjetas -->
    <section class="plans-container--slider">
        <!-- tarjeta -->
        <article class="plans-container-card">
            <!-- Elemento flotante -->
            <p>Recomendado</p>
            <!-- Encabezado y precio -->
            <div>
                <h3>Pago Anual</h3>
                <!-- Se agrega un span para colocar
                el signo pesos mas pequeño-->
                <p><span>$</span> 99</p>
                <p>*Ahorras $129 comparado al plan mensual.</p>
            </div>
            <!-- boton -->
            <button>Escoger este <span></span></button>
        </article>
    </section>
</section>
~~~

![](../imagenes/img59.png)