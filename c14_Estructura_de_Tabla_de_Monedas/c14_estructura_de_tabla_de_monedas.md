# ESTRUCTURA DE TABLA DE MONEDAS

La tabla de la primera sección del main esta compuesto por:

- Encabezado de texto h3 o h4
- Tabla con texto, precios e íconos
- Información de la última actualización

Arquitectura HTML de la tabla de la primera sección del main

~~~html
<!-- Contenedor de tabla de conversión de monedas, 
se utiliza la etiqueta section ya que contiene
muchos elementos individuales -->
<section class="main-tables-container">
    <!-- Como el diseño contiene dos tablas, se
    hace necesario tener dos div -->
    <!-- Tabla de monedas -->
    <div class="main-currency-table">
        <!-- Título de la tabla -->
        <p class="currency-table--title">Monedas</p>
        <!-- Contenedor de la Tabla -->
        <div class="currency-table--container">
            <table>
                <!-- tr hace referencia a las 
                filas que va a contener la tabla-->
                <tr>
                    <!-- td es la información de la
                    fila, cada una es una 
                    columna -->
                    <td class="table__top-left">Bitcoin</td>
                    <td class="table__top-right table__right">$1.96 <span></span></td>
                </tr>
                <tr>
                    <td>Ethereum</td>
                    <td class="table__right">$0.07</td>
                </tr>
                <tr>
                    <td>Ripple</td>
                    <td class="table__right">$2.17</td>
                </tr>
                <tr>
                    <td class="table__bottom-left">Stellar</td>
                    <td class="table__bottom-right table__right">$4.96</td>
                </tr>
            </table>
        </div>
        <!-- Actualización de la tabla -->
        <div></div>
    </div>
    <!-- Tabla de comisiones -->
    <div class="currency-table--date">
        <!-- La etiqueta b es para poner en bold 
        (negrita) el texto -->
        <p><b>Actualizado:</b> 19 Julio 23:45</p>
    </div>
</section>
~~~

![](../imagenes/img27.png)