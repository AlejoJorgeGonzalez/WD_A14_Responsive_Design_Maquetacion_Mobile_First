![](../imagenes/img06.png)

Primero se muestra como debe ser el header de la página web, el cual tiene un titulo, un texto principal y un boton. El main esta compuesto por 4 secciones de la siguiente forma

![](../imagenes/img07.png)
![](../imagenes/img08.png)
![](../imagenes/img09.png)

Y por último se tiene un Footer.

![](../imagenes/img10.png)

Resumiendo, la arquitectura inicial esta compuesta por:

1 Header
1 Main con 4 Secciones
1 Footer

Para comenzar se crea el archivo index.html que es el archivo que el navegador busca primero para ejecutar el código, se escribe el head del archivo

```html
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
```

Ahora se crea la arquitectura inicial con las secciones que ya se vieron 

~~~html
<body>
    <!-- Se crea el header -->
    <header></header>
    <!-- Se crea el main con 4 secciones -->
    <main>
        <section></section>
        <section></section>
        <section></section>
        <section></section>
    </main>
    <!-- Se crea el footer -->
    <footer></footer>
</body>
~~~

