# FINALIZANDO ESTILOS DE TABLA DE MONEDAS

Estilos de la parte de actualización

~~~css
.currency-table--date {
    /* tamaño del contenedor */
    width: 190px;
    height: 30px;
    /* Se centra el contenedor */
    margin: 0 auto;
    /* Separación con la tabla */
    margin-top: 15px;
    /* Espacio interno del contenedor */
    padding: 8px;
    /* Color de fondo */
    background-color: var(--soft-orange);
    /* Redondeo en las esquinas */
    border-radius: 8px;
}
~~~

![](../imagenes/img38.png)

Estilos de la fuente de la parte de actualización

~~~css
.currency-table--date p{
    font-size: 1.2rem;
    line-height: 1.5rem;
    color: var(--warm-black);
}
~~~

![](../imagenes/img39.png)

De igual forma se agrega los estilos para la parte de comisiones quedando como 

![](../imagenes/img40.png)

Sin embargo note que hay un problema, según el diseño en figma el grosor del texto de actualización es mas angosta, sin embargo no se esta aplicando, esto se debe a que hay un conflicto de herencia, ya que al crear la clase '.main-exchange-container p' que es un contenedor padre, se definio un grosor de fuente de 500, el cual hereda a todos los p que esten dentro de este contenedor. Se puede cambiar por medio de una instancia mas especifica que cambie este grosor como se realiza a continuación

~~~css
.currency-table--date p{
    font-size: 1.2rem;
    line-height: 1.5rem;
    font-weight: 300;
    color: var(--warm-black);
}
~~~
![](../imagenes/img41.png)