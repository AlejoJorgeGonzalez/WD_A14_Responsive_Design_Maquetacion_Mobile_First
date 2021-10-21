# ESTRUCTURA BASE DE LA SECCION DE BENEFICIOS

![](../imagenes/img42.png)

Se puede observar que esta sección tiene un color de fondo distinto, Comienza con un ícono entre la sección anterios y este, se tiene un encabezado que hace intro a esta sección, seguido de un parrafo, despues una serie de 4 tarjetas, en el cual cada tarjeta contiene un ícono, un encabezado y un párrafo con texto. La estructura HTML queda como

~~~html
<!-- Sección mostrando los beneficios de la empresa -->
<section class="main-product-detail">
    <!-- Ícono entre la sección de información de la
    moneda y la sección de beneficios -->
    <span></span>
    <!-- Contenedor del texto -->
    <div>
        <!-- Título de la sección -->
        <h2>Creamos un producto sin comparación.</h2>
        <!-- Párrafo -->
        <p>Confíable y diseñado para su uso diario</p>
    </div>
    <!-- Contenedor con las tarjetas de beneficios -->
    <section class="product-cards--container">
        <!-- Cada tarjeta se convierte en un articulo,
        en total son 4  -->
        <article class="product-detail--card">
            <!-- Ícono de la tarjeta -->
            <span class="clock"></span>
            <!-- Encabezado de la tarjeta -->
            <p class="product--card-title">Tiempo real</p>
            <!-- Texto de la tarjeta -->
            <p class="product--card-body">Nuestro API toma información minuto a minuto sobre las tasas que más determinan el comportamiento.</p>
        </article>
        <article class="product-detail--card">
            <!-- Ícono de la tarjeta -->
            <span class="eye"></span>
            <!-- Encabezado de la tarjeta -->
            <p class="product--card-title">No hay tasas escondidas</p>
            <!-- Texto de la tarjeta -->
            <p class="product--card-body">Ni en la compra o al momento de exit, Batabit siempre te muestra el costo real de los que estás adquiriendo.</p>
        </article>
        <article class="product-detail--card">
            <!-- Ícono de la tarjeta -->
            <span class="dollar-sign"></span>
            <!-- Encabezado de la tarjeta -->
            <p class="product--card-title">Compara monedas</p>
            <!-- Texto de la tarjeta -->
            <p class="product--card-body">No más rumores, con Batabit sabrás el valor real de cada moneda en el mercado actual.</p>
        </article>
        <article class="product-detail--card">
            <!-- Ícono de la tarjeta -->
            <span class="check-circle"></span>
            <!-- Encabezado de la tarjeta -->
            <p class="product--card-title">Información Confiable</p>
            <!-- Texto de la tarjeta -->
            <p class="product--card-body">Nuestras fuentes están 100% verificadas y continuamos auditando su contenido mientras se actualizan.</p>
        </article>
    </section>
</section>
~~~

![](../imagenes/img43.png)