---
order: 1
author: 
    name: Mateo R.
    avatar: ../../../media/avatar/mateo.jpg
---
<style>
    body {
        max-width: 90%;
        margin: 0 auto;
    }
    img {
    border-radius: 7px; 
    margin-top: 1%; 
    margin-bottom: 1%;
    max-width: 100%;
    float: left; /* Añade el float para alinear la imagen a la izquierda */
    margin-right: 10px; /* Espacio entre la imagen y el texto */
    }

    .clearfix2 {
    overflow: hidden; /* Limpiar el float sin necesidad de ::after */
    }

    .clearfix2 img {
    float: none; /* Anula el float para centrar las imágenes */
    margin-bottom: 3%
    }

    .clearfix::after {
    content: "";
    display: table;
    clear: both; /* Asegura que no haya elementos flotantes a su izquierda ni derecha */
    }

    .clearfix img:first-child {
    margin-right: 10px; /* Espacio entre las imágenes */
    margin-left: auto; /* Centrar la primera imagen horizontalmente */
    }

    /* Estilo inicial para el contenido de PC en pantallas grandes */
    @media only screen and (min-width: 960px) {
        .pc {
            display: block;
        }

        .movil {
            display: none;
        }
    }

    /* Estilo inicial para el contenido de móvil en pantallas pequeñas */
    @media only screen and (max-width: 960px) {
        .pc {
            display: none;
        }

        .movil {
            display: block;
        }

        .clearfix {
            margin-bottom: 1.5rem;
        }
    }
</style>

# Discord: Uso del IAR
!!!danger Advertencia
Por el momemento solo está disponible para canales de texto, por lo que si tienes un problema que afecte en alguna otra de las competencias de Discord, debes dirigirte [aquí](https://dis.gd/report).
!!!
Una de las modificaciones más grandes que vamos a hacer a la metodología de moderación actual dentro de Discord, es comenzar a usar el IAR como herramienta al hablar de infracciones de los [Términos del Servicio](https://discord.com/terms) de la plataforma.
IAR es la sigla de _In App Reporting_, que es una implementación que ha llevado a cabo la empresa recientemente.

Esto tiene efecto en los siguientes casos:
- Cuando nos encontramos frente a un menor de la edad permitida
- Si se presenta un comportamiento extremadamente tóxico, hiriente o discriminante
- Aparición de [contenido restringido](./contenido-sugestivo-vs-restringido.md#contenido-restringido)

## ¿Cómo proceder?
:::pc
!!!info
Se ha detectado automáticamente que estás usando un dispositivo con una resolución de ordenador.
!!!
Imagina que estás en un canal de texto tranquilamente y te encuentras con esto:
<div class="clearfix">
    <img src="../../../media/ej/ej_IAR_1.png" width="300" height="200" style="margin-bottom: 1.5rem;">
</div>

En el pasado, debías de dirigirte al [sitio oficial de reportes de Discord](https://dis.gd/report) y rellenar un formulario para notificar de esto. Ciertos servidores vetan el acceso, también, de estos usuarios.
Ahora, es tan sencillo como seguir este procedimiento para notificar a la plataforma:

<div class="clearfix">
    <img src="../../../media/ej/ej_IAR_2.png" width="550" height="50">
    <img src="../../../media/ej/ej_IAR_3.png" width="300" height="100" style="margin-bottom: 1.5rem;">
</div>

A continuación debemos indicar el motivo de la solicitud, que como no es ninguna de las opciones que aparecen, aparecerá en la sección _Otro_:

<div class="clearfix clearfix2">
    <img src="../../../media/ej/ej_IAR_4.png" width="300" height="100">
    <img src="../../../media/ej/ej_IAR_5.png" width="250" height="100">
</div>

Seleccionamos lo que nos concierne, que es un problema de la edad del usuario (_para estar en Discord, debes de tener trece o más años según lo establecido en los [Términos y Condiciones](https://discord.com/terms)) y respondemos adecuadamente a las preguntas que el interfaz nos formule.

<div class="clearfix clearfix2">
    <img src="../../../media/ej/ej_IAR_6.png" width="200" height="100">
    <img src="../../../media/ej/ej_IAR_7.png" width="200" height="100">
</div>

Es un proceso muy sencillo que no toma más de unos segundos, como se puede observar en las imágenes. Gracias a esto, contribuimos al ecosistema de la plataforma y aumentamos la seguridad en ella, como moderadores.
La decisión de vetar el acceso al usuario es del responsable y Discord no obliga a llevarla a cabo siempre y cuando se cumpla con el reporte vía IAR.
:::

:::movil
!!!info
Se ha detectado automáticamente que estás usando un dispositivo con una resolución de móvil o tablet.
!!!
Imagina que estás en un canal de texto tranquilamente y te encuentras con esto:
<div class="clearfix">
    <img src="../../../media/ej/ej_MIAR_1.png" width="300" height="200" style="margin-bottom: 1.5rem;">
</div>

En el pasado, debías de dirigirte al [sitio oficial de reportes de Discord](https://dis.gd/report) y rellenar un formulario para notificar de esto. Ciertos servidores vetan el acceso, también, de estos usuarios.
Ahora, es tan sencillo como seguir este procedimiento:

- Mantenemos presionado el mensaje que vemos que tiene la infracción y nos dará pie a este menú:
<div class="clearfix">
    <img src="../../../media/ej/ej_MIAR_2.png" width="550" height="50">
    <img src="../../../media/ej/ej_MIAR_3.png" width="300" height="100" style="margin-bottom: 1.5rem;">
</div>

- A continuación debemos indicar el motivo de la solicitud, que como no es ninguna de las opciones que aparecen, aparecerá en la sección _Otro_:

<div class="clearfix">
    <img src="../../../media/ej/ej_MIAR_4.jpeg" width="300" height="100">
    <img src="../../../../media/ej/ej_MIAR_5.jpeg" width="250" height="100">
</div>

- Seleccionamos lo que nos concierne, que es un problema de la edad del usuario (_para estar en Discord, debes de tener trece o más años según lo establecido en los [Términos y Condiciones](https://discord.com/terms)_) y respondemos adecuadamente a las preguntas que el interfaz nos formule, lo cual nos deja finalmente en el resumen para finalmente enviarlo:

<div class="clearfix">
    <img src="../../../media/ej/ej_MIAR_6.png" width="300" height="200">
</div>

Es un proceso muy sencillo que no toma más de unos segundos, como se puede observar en las imágenes. Gracias a esto, contribuimos al ecosistema de la plataforma y aumentamos la seguridad en ella, como moderadores.
<br>La decisión de vetar el acceso al usuario es del moderador responsable y Discord no obliga a llevarla a cabo siempre y cuando se cumpla con el reporte vía IAR o mediante una [solicitud](https://dis.gd/report).
:::

[!button variant="ghost" text="Manual completo"](./discord_uso-del-iar-multiples-dipositivos.md)

---
[!badge variant="dark" text="Contribución por Mateo R."](https://mateo.ltd/) [!badge variant="ghost" text="CEO del proyecto"](https://mateo.ltd/)