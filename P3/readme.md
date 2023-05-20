# DIU - Práctica 3
Prácticas Diseño Interfaces de Usuario 2022-23 (Tema: turismo)

Grupo: DIU3.LosMijos  Curso: 2022/23 
Actualizado: 25/04/2023

Proyecto: 

 Granada Handcraft: aplicación web de compra de experiencias personalizables de artesanía nazarí en la ciudad de Granada.

Descripción: 

 Nuestra aplicación web está orientada a la personalización de una especie de paquetes turísticos enfocados a la artesanía nazarí en Granada. La idea es ofrecer un conjunto de opciones elegibles por el usuario final, dotándolo de flexibilidad, de manera que tenga mayor interés en la realización de este tipo de actividades. Además, cabe reseñar que queremos involucrar a empresas locales tanto para ampliar las opciones de personalización, como fomentar una sinergia de empresas locales.

 En esta práctica se va a definir el estilo visual de la página web, por lo que se hará uso de diversas herramientas y metodologías de trabajo para tal fin. Estos recursos empleados se mencionarán a lo largo de este documento.

Logotipo:

![Logotipo Granada Handcraft](logo.png)

Miembros

 * :bust_in_silhouette:   Luis Miguel Guirado Bautista     :octocat:     
 * :bust_in_silhouette:   Miguel Ángel Serrano Villena     :octocat:

GitHub: 

  * https://github.com/DIU3-LosMijos/DIU3.LosMijos

## Moodboard (diseño visual + logotipo)   

 La primera fase de este proceso consiste en desarrollar un tablero de inspiración que recoja diferentes aspectos de diseño de nuestra página web. No todo lo que aparezca en este tablero debe de aparecer en los bocetos HI-FI que se van a perfilar de la práctica anterior, aunque es importante lograr que haya consistencia entre el resultado final de dicho tablero y el de los mencionados bocetos.

![moodboard](moodboard.png)

## Landing Page

![Landing page](Prototipos/landing_page.png)

## Patrones y *Guidelines* usados

### Patrones de interfaz de usuario utilizados

- **Pestañas de navegación**
  Los usuarios pueden acceder a secciones importantes de la aplicación mediante un conjunto de botones que cumplen con la misma funcionalidad que puede tener un conjunto de pestañas.       Presente en todas las páginas salvo en *landing page*.
  
  ![Pestañas de navegación](Elementos_patrones/pestanias_navegacion.png)
  
- ***Fat Footer***
  Las páginas web tienen un pie de página común con enlaces de interés. Presente en todas las páginas.
  
  ![Pie de página](Elementos_patrones/pie_pagina.png)
   
- **Enlace al *home***
  En la cabecera hay un logo que redirige al *home* si el usuario hace clic sobre él. Presente en todas las páginas.
  
  ![Logo que redirige al home](Elementos_patrones/logo_home.png)
  
- **Miniaturas**
  El usuario tiene a su disposición un conjunto de imágenes que describen visualmente lo que tiene que ofrecer la aplicación. Presente en el *home*, la descripción de experiencia y en la *landing page*.
  
  ![Miniaturas descriptivas](Elementos_patrones/miniaturas.png)
  
- **Tarjetas**
  Conjuntos de información, normalmente suelen ser conjuntos de una foto y texto. Presente en el historial, la página de favoritos, el carrito y en la *landing page*.
  
  ![Tarjetas informativas](Elementos_patrones/tarjetas_info.png)
  
- **Carrusel**
  parecido al elemento de la paginación pero sin indexar, puede ser automático y cuando llega al final, vuelve al principio. Usado en la landing page, en la descripción de la experiencia y en el *home*.
  
  ![Carrusel](Elementos_patrones/carrusel.png)
  
- **Deslizadores**
  utilizados en los filtros de búsqueda y en la personalización de búsqueda para evitar que el usuario ponga números negativos y que solo pueda escoger entre un rango.
  
  ![Deslizadores](Elementos_patrones/deslizadores.png)
  
- **Sección de favoritos** (ver el boceto de "Favoritos (clientes y empresas)").

- **Filtros de búsqueda**
  el usuario puede ordenar lo que se le muestra en el *home* según los criterios mostrados.
  
  ![Filtros de búsqueda](Elementos_patrones/filtros_busqueda.png)
  
- **Presentación de diapositivas**:
  diapositivas que muestran elementos, se suelen manejar con un carrusel. Presente en el *home* y en la descripción de experiencia.
  
  ![Presentación de diapositivas](Elementos_patrones/miniaturas.png)
  
- **FAQ (*Frequently Asked Questions*)**:
  se puede acceder en el *fat footer*.
  
  ![FAQ](Elementos_patrones/faq.png)
  
- **Página de producto**
  la página de descripción y personalización de experiencia tienen el papel de páginas de producto.
  
- **Carrito de la compra** (ver el boceto "Carrito (clientes)").

- **Registro perezoso**

  El usuario puede registrarse con una cuenta de Google o Facebook si asi lo desea.
  
  ![Registro perezoso](Elementos_patrones/registro_perezoso.png)
  
- **Registro de cuentas**

  Cubierto por el punto anterior, aunque este punto no incluye el registro tradicional (por correo), por lo que lo hemos incluido en la sección de registro/inicio de sesión.

- **Preferencias / ajustes**

  El usuario puede personalizar algunos ajustes de la aplicación según sus necesidades

  ![Perfil (clientes)](Prototipos/perfil_clientes.png)

### *Guidelines* utilizados

- **Diseño por columnas**
Para realizar el diseño del Mockup nos hemos basado en una pantalla de escritorio con un ancho de 1440 px con sus elementos distribuidos en 12 columnas y con un espacio entre columnas de 24 pixeles

  ![Diseño por columnas](Elementos_patrones/columnas.png)

- **Iconos de la cabecera del *home***
Transmiten con claridad a la página a la que llevan con un icono minimalista, por ejemplo, un icono de un carrito de la compra que lleva al la pagina del carrito de la aplicación

  ![Pestañas de navegación](Elementos_patrones/pestanias_navegacion.png)

- ***Seams + Steps***
Hay una separación evidente entre la cabecera/pie de página y el cuerpo, borde y color de fondo distinto

  ![Pie de página](Elementos_patrones/pie_pagina.png)

- ***Whiteframes***
En algunas páginas, por ejemplo el inicio de sesión, todo el contenido destacado del formulario se encuentra en una especie de tarjeta flotante

  ![Inicio de sesión (clientes y empresas)](Prototipos/inicio_sesion_clientesyempresas.png)



## Mockup: LAYOUT HI-FI

 Dado que en la práctica anterior realizamos unos prototipos con más detalle del debido, en esta ocasión nos hemos centrado en matizar ciertos detalles en base al moodboard presentado al principio. Es por esto que hemos vuelto a utilizar Figma como herramienta para este apartado, pues nos ha permitido aplicar los estilos requeridos sin nigún problema. Sin más dilación, el resultado del refinamiento de esos bocetos, quitando la landing page presentada en el apartado anterior, es el que sigue:

#### Inicio de sesión (clientes y empresas)

![Inicio de sesión (clientes y empresas)](Prototipos/inicio_sesion_clientesyempresas.png)

#### Registro (clientes y empresas)

![Registro (clientes y empresas)](Prototipos/registro_clientesyempresas.png)

#### Home page (clientes y empresas)

![Home page (clientes y empresas)](Prototipos/home_clientesyempresas.png)

#### Favoritos (clientes y empresas)

![Favoritos (clientes y empresas)](Prototipos/favoritos_clientesyempresas.png)

#### Descripción experiencia (clientes)

![Descripción experiencia (clientes)](Prototipos/descripcion_experiencia_clientes.png)

#### Personalizar experiencia (clientes)

![Personalizar experiencia (clientes)](Prototipos/personalizar_experiencia_clientes.png)

#### Panel de comentarios (clientes)

![Panel de comentarios (clientes)](Prototipos/panel_comentarios_clientes.png)

#### Carrito (clientes)

![Carrito (clientes)](Prototipos/carrito_clientes.png)

#### Historial (clientes)

![Historial (clientes)](Prototipos/historial_clientes.png)

#### Perfil (clientes)

![Perfil (clientes)](Prototipos/perfil_clientes.png)

#### Finalización de la compra (clientes)

![Finalización de la compra (clientes)](Prototipos/finalizar_compra_clientes.png)

#### Edición de servicios en una experiencia (empresas)

![Edición de servicios en una experiencia (empresas)](Prototipos/edicion_servicios_experiencia_empresa.png)

#### Descripción experiencia (empresas)

![Descripción experiencia (empresas)](Prototipos/descripcion_experiencia_empresas.png)

#### Perfil (empresas)

![Perfil (empresas)](Prototipos/perfil_empresas.png)

## Documentación: Publicación del Case Study
 
Para publicar nuestro caso de estudio, hemos utilizado [docsify](https://docsify.js.org/), una herramienta muy sencilla de aprender que ha generado un fichero HTML que coge la información del fichero README.md y la renderiza de manera bonita.

Para el despliege de la web, hemos utilizado GitHub Pages.

La web se aloja en el siguiente enlace: https://diu3-losmijos.github.io/DIU3.LosMijos/

*Gracias, [Cherry Pink](https://github.com/Asmilex/DIU21)*