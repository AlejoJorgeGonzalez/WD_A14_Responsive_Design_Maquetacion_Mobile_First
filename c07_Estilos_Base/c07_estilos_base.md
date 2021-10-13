# ESTILOS BASE

Se crea el archivo styles.css en donde va a estar todos los diseños de la página web, comenzando por agregar los estilos que son base para el proyecto.

Es de anotar que la manera correcta de agregar estilos viene dado por el siguiente orden:

1. Posicionamiento
2. Modelo caja (box model)
3. Tipografía
4. Estilos Visuales
5. Miscelaneos y otros

Se comienza con los colores que se utilizan en la página web que se pueden consultar en el Figma, los cuales se agregan como variables en el root del CSS

~~~css
/* Se implementan las variables en el root */
:root{
    /* Variables de Color */
    --bitcoin-orange: #f7931a;
    --soft-orange: #ffe9d5;
    --secondary-blue: #1a9af7;
    --soft-blue: #e7f5ff;
    --warm-black: #201e1c;
    --black: #282623;
    --grey: #bababa;
    --off-white: #faf8f7;
    --just-white: #fff;
}
~~~

Se resetea los valores por defecto del tamaño para 
que se ocupe todo el espacio de la pantalla y se trabaje con
el border box

~~~css
*{
    box-sizing: border-box;
    margin: 0;
    padding: 0;
}
~~~

Por ultimo se agrega los estilos de fuente

~~~css
html{
    /* El font-size es necesario para utilizar tamaños rem 
    en vez de pixeles, para que el tamaño fuente escale según
    el tamaño de la pantalla*/
    font-size: 62.5%;
    /* Fuente base desde google fonts */
    font-family: 'DM Sans', sans-serif;
}
~~~