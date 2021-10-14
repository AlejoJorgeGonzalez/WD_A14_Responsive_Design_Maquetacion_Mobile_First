# USO DE LINEAR GRADIENT

Se agrega el background con el degradado en dos colores, que es conocido como linear gradient, ademas de los estilos del H1 y del párrafo.

Se agrega el background

~~~css
header {
    position: relative;
    display: flex;
    flex-direction: column;
    justify-content: center;
    width: 100%;
    min-width: 320px;
    height: 334px;
    text-align: center;
    /* Se crea el background con los colores copiados desde 
    Figma, linear-gradient recibe como parametros primero
    los grados a los que va a dividir los dos colores, 
    segundo el primer color y el porcentaje en que se mezcla
    y tercero el segundo color y el porcentaje de mezcla */
    background: linear-gradient(207.8deg, #201e1c 16.69%, #f7931a 100%);
}
~~~
![](../imagenes/img16.png)

Estilos del H1

~~~css
/* Como buenas práctica primero se llama la clase que lo 
contiene y luego elemento como tal */
.header--title-container h1{
    /* Tamaño de fuente, note que se utiliza rem para escalarlo
    según el tamaño de la pantalla */
    font-size: 2.4rem;
    /* peso de la fuente */
    font-weight: bold;
    /* Salto entre líneas */
    line-height: 2.6rem;
    /* Color de la fuente, note como se llama una de las 
    variables creadas anteriormente */
    color: var(--just-white);
}
~~~
![](../imagenes/img17.png)

Estilos del párrafo

~~~css
/* Estilos del párrafo del header */
.header--title-container p{
    /* Separación del H1 */
    margin-top: 25px;
    /* Tamaño de fuente */
    font-size: 1.4rem;
    /* grosor de la fuente */
    font-weight: 500;
    /* Salto entre líneas */
    line-height: 1.8rem;
    /* Color de la fuente dada como variable */
    color: var(--soft-orange);
}
~~~
![](../imagenes/img18.png)