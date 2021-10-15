# Imagen de Background

Estilos de la imagen de la primera sección del main en CSS

~~~css
.main-exchange-container .backgroundImg{
    /* Ancho y alto del contenedor de la imagen */
    width: 200px;
    height: 200px;
    /* Se centra el contenedor */
    margin: 0 auto;
    /* Se crea el espacio entre la imagen y el texto */
    margin-bottom: 50px;
    /* Se inserta la imagen */
    background-image: url('../assets/imgs/bitcoin.svg');
    /* Como buenas prácticas se agregan los siguientes 
    estilos */
    /* La imagen cubra el contenedor */
    background-size: cover;
    /* La imagen se centre al crecer la pantalla */
    background-position: center;
    /* Evitar que la imagen se repita para cubrir el 
    contenedor */
    background-repeat: no-repeat;
}
~~~

![](../imagenes/img24.png)

Estilos del título h2 de la primera sección del header en CSS

~~~css
.main-exchange-container h2{
    /* Separacion con el texto de abajo */
    margin-bottom: 30px;
    /* Estilos de la fuente */
    font-size: 2.4rem;
    font-weight: bold;
    /* Espacio entre líneas */
    line-height: 2.6rem;
    color: var(--black);
}
~~~

![](../imagenes/img25.png)

Estilos del párrafo de la primera sección del header en CSS

~~~css
.main-exchange-container p{
    /* Separación del parrafo con el final del contenedor */
    margin-bottom: 30px;
    /* Estilos de la fuente */
    font-size: 1.4rem;
    font-weight: 500;
    line-height: 1.6rem;
    color: #757575;
}
~~~

![](../imagenes/img26.png)