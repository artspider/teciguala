+++
author = "A. Pope"
autor-avatar = ""
date = ""
featuredImage = "/uploads/Flexbox.png"
tags = ["Diseño", "Web", "FlexBox", "CSS"]
title = "Flexbox y el diseño responsive unidireccional"

+++
## **Tabla de contenidos**

1. Primeros pasos con Flexbox
2. Distribución de los elementos
3. Dirección de los ejes
4. Propiedades de los elementos hijos
5. Compatibilidad en navegadores

Si eres de esos que todavía sufren con la propiedad **float** o desperdician una tarde entera intentando **alinear elementos verticalmente**, tengo la solución para ti.

La propiedad Flexbox **no es nueva**, el concepto de Flexbox tiene más de una década y se ha ido mejorando con el paso de los años. Ahora, es una de las propiedades más usadas y útiles junto a [**CSS Grid**](https://www.inarvis.com/blog/css-guia-definitiva/#css-grid), que nos permiten crear diseños responsive con una sintaxis muy sencilla.

> La propiedad **Flexible Box**, o **Flexbox**, de CSS3 es un modo de diseño que permite colocar los elementos de una página para que se comporten de forma predecible cuando el diseño de la página debe acomodarse a diferentes tamaños de pantalla y diferentes dispositivos.
>
> [MDN Web Docs](https://developer.mozilla.org/es/docs/Web/CSS/CSS_Flexible_Box_Layout/Usando_las_cajas_flexibles_CSS)

### **1. Primeros pasos con Flexbox**

Lo primero de todo, para definir un bloque flexbox y **habilitar flex a todos sus hijos**, necesitamos el siguiente fragmento de código.

    .container {
      display: flex;
    }

A partir de ahora, ya podemos aplicar el resto de propiedades que definen la dirección, orden y espaciado del resto de elementos. Por ejemplo, un truco muy útil para **centrar vertical y horizontalmente** haríamos lo siguiente.