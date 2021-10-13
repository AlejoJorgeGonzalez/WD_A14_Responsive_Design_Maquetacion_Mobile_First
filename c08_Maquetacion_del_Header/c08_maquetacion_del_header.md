# MAQUETACIÓN DEL HEADER

El header en Figma se ve de la siguiente forma 

![](../imagenes/img06.png)

El header tiene un logotipo, un texto que se puede tomar como un H1 por ser un encabezado principal, es de anotar que por buenas prácticas un diseño solo puede tener un solo H1. En tercer lugar tiene un texto y por último un boton que funciona como un call action que lleva a otra sección.

El header en HTML queda como:

~~~html
<header>
    <!-- Logotipo -->
    <img src="" alt="">
    <div>
        <!-- Contenedor con encabezado principal H1-->
        <h1>La próxima revolución en el intercambio de criptomonedas</h1>
        <!-- Parrafo -->
        <p>Batatabit te ayuda a navegar entre los diferentes precios y tendencias</p>
        <!-- Boton, note que dentro de 'a' hay una 
        etiqueta span para agregar iconos como una flecha
        hacia abajo -->
        <a href="">Conoce Nuestros Planes <span><i></i></span></a>
    </div>
</header>
~~~