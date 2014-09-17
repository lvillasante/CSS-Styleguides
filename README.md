CSS Styleguides
===============

Guías de estilo css

## Cabecera
Para la cabecera de todo proyecto

```
/*------------------------------------*\
    Nombre de la institución
\*------------------------------------*/

/*------------------------------------*\
    Proyect     : Sistema de  ....  / Theme for Bootstrap
    Description : Design based on HTML5 & CSS3
    Bootstrap   : Currently version3.2.0
    Designer    : Luis Villasante
    E - mail    : luis[at]enbolivia.com | luis.villasante[at]gmail.com
    Filename    : style.css
    Version     : 1.2
    Date        : Aug 21, 2014 - 0800
\*------------------------------------*/
```

## Delimitar secciones

Se debe coemnzar con el signo ($ - Pesos) para facilitar la busqueda 

```
/*------------------------------------*\
    $Header
\*------------------------------------*/
```



## Break Point 

Los puntos de anclajes a travez de Media queries

```
/*------------------------------------*\
    $RESPONSIVE
\*------------------------------------*/

/* Extra small devices (phones, up to 480px) */
/* No media query since this is the default in Bootstrap */

@media (max-width: 767px) {
    /*.navbar .nav li a{
        background-color: red;
    }*/
}
@media (min-width: 768px) and (max-width: 991px) {
    /*.navbar .nav li a{
        background-color: yellow;
    }*/
}    
@media (min-width: 992px) and (max-width: 1199px) {
    /*.navbar .nav li a{
        background-color: green;
    }*/
}
@media (min-width: 1200px) {
    /*.navbar .nav li a{
        background-color: blue;
    }*/
}

```
