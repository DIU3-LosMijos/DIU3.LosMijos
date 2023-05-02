## DIU - Práctica 2
Prácticas Diseño Interfaces de Usuario 2022-23 (Tema: turismo)

Grupo: DIU3.LosMijos  Curso: 2022/23 
Actualizado: 25/04/2023

Proyecto: 
>>> Granada Handcraft: aplicación web de compra de experiencias personalizables de artesanía nazarí en la ciudad de Granada.

Descripción: 
>>> Nuestra aplicación web está orientada a la personalización de una especie de paquetes turísticos enfocados a la artesanía nazarí en Granada. La idea es ofrecer un conjunto de opciones elegibles por el usuario final, dotándolo de flexibilidad, de manera que tenga mayor interés en la realización de este tipo de actividades. Además, cabe reseñar que queremos involucrar a empresas locales tanto para ampliar las opciones de personalización, como fomentar una sinergia de empresas locales.

Logotipo:
![Logotipo Granada Handcraft](logo.png)

Miembros
 * :bust_in_silhouette:   Luis Miguel Guirado Bautista     :octocat:     
 * :bust_in_silhouette:   Miguel Ángel Serrano Villena     :octocat:


### IDEACIÓN

>>> Tras haber analizado los defectos de las visitas a los talleres de artesanía nazarí de Granada, así como tras haber elaborado una serie de críticas constructivas en torno a esto, hemos ideado una propuesta para impulsar este tipo de experiencias en la ciudad de Granada. Para ello, hemos diseñado una aplicación web enfocada en esto mismo, pero aportando aspectos novedosos e interesantes, de cara a mejorar la experiencia de los/as usuarios/as finales: Granada Handcraft.

#### Malla receptora de información

Hemos elegido esta herramienta por la facilidad de uso junto con la agilidad visual que brinda a la hora de ver rápidamente aspectos relacionados con el surgimiento de la idea de nuestra aplicación web.

![Malla receptora de información](malla_receptora_informacion.png)

### PROPUESTA DE VALOR

>> En la descripción del presente archivo se ha aportado información referente a nuestro proyecto web, pero a continuación vamos a reflejar una serie de aspectos relevantes de cara a conformar una estructura más sólida sobre el sentido de nuestro proyecto.
>> Antes de nada, cabe mencionar que hemos analizado las necesidades de nuestros/as usuarios/as, la misión de nuestro proyecto, los objetivos a corto y largo plazo que pretendemos alcanzar como organización, las acciones que pretendemos que lleven a cabo nuestros/as usuarios/as en nuestra web, así como la forma en la que mediremos el éxito de nuestro proyecto (indicadores de éxito).

![ScopeCanvas](scope_canvas.png)

### TASK ANALYSIS

>> Con la ayuda de la propuesta de valor anterior, hemos identificado quiénes serían nuestros principales usuarios/as. Encontramos dos tipos de usuarios/as: por un lado, tenemos a los/as usuarios/as que harán uso de la web para comprar experiencias y, por otro, tenemos a empresas locales que colaborarán con nosotros para aparecer como opciones en la personalización de las experiencias.
>> Dicho esto, vamos a proceder a especificar más cada uno de estos/as tipos de usuarios/as:
>> * Los/as usuarios/as principales, que serán los/as que comprarán las experiencias. Estos/as podrán ver las diferentes experiencias que se ofertan, modificar diversas opciones de sus perfiles de usuario, realizar reseñas y valoraciones y, por supuesto, comprar las entradas para dichas experiencias (teniendo a su disposición varios tipos de funcionalidades para la gestión de las compras, como son un historial con experiencias ya compradas en el pasado, un carrito con las compras pendientes de finalizar y un apartado con las experiencias marcadas como favoritas). Dentro de este conjunto, se pueden distinguir los siguientes grupos de usuarios/as:
>>     * Grupos normales: conjunto de personas adultas que quieren acudir juntas a la experiencia.
>>     * Grupos especiales: conjunto de personas adultas junto con menores de edad que quieren acudir juntas a la experiencia.
>>     * Individuos: personas que quieren acudir en solitario a la experiencia.
>> * Las empresas locales colaboradoras, que serán las que podrán añadir sus servicios al sistema. Estas únicamente podrán añadir sus servicios a las distintas experiencias que les interesen y modificar diversas opciones de sus perfiles de usuario.
>> A continuación se presenta una matriz con las tareas que se pueden realizar en nuestra web (filas) y los tipos y subtipos de usuarios de nuestro sistema (columnas). En esta matriz se representa tanto la frecuencia de uso de cada tarea en función del tipo de usuario (A: alta, M: media, B: baja), como las tareas y perfiles más críticos e importantes (marcados con un fondo gris; esto ayudará a indentificar claramente aquellas tareas que deben de ser diseñadas con más detalle):

![Matriz de tareas/usuarios](matriz_tareas_usuarios.png)

>> Nota: el motivo que nos ha llevado a elegir esta herramienta es la posibilidad de comprimir una información tan amplia e importante como esta, pudiendo observar fácil y rápido la funcionalidad general del sistema y el comportamiento de los diferentes usuarios/as con esta.

### ARQUITECTURA DE INFORMACIÓN

#### *Sitemap*

Esquema de la estructura de nuestro sitio web

![Sitemap](Labelling.drawio.png)

#### Labelling

Descripción breve de cada una de las páginas indicadas en el *Sitemap*

| Nombre      | Descripción |
|-------------|-------------|
| Landing page | Primera página que verán los usuarios nuevos y empresas. Tendrá una introducción llamativa (contenido destacado de la empresa) y una sección de entrada para cada uno. Incluirá información de contacto y ubicación |
| Área clientes | Página principal dirigida a los clientes ya registrados, tiene formato de tienda online |
| Área empresas | Dirigida a los intereses de las empresas (colaboraciones, patrocinios, etc.) |
| FAQ | Sección de preguntas frecuentes |
| Inicio de sesión | Inicia sesión como usuario de la aplicación ya registrado |
| Registro | Aquí los usuarios nuevos pueden crear una cuenta nueva |
| Config. experiencia | En caso de querer comprar una experiencia, esta se podra personalizar en funcion a las preferencias del usuario (como si de un formulario se tratase) |
| Carrito | Lista de productos que un usuario ha añadido a su carrito, ver los detalles de cada uno y modificarlos (eliminar del carrito, modificar cantidad/detalles, añadir a favoritos, comprar directamente uno de los productos, etc.) |
| Fin de compra | Cuando se tramita correctamente la compra, se informa al usuario acerca de los detalles necesarios (id. compra, día estimado de llegada, etc.), se añade el pedido al historial y se vacia el carrito |
| Historial | Lista con los pedidos realizados anteriormente por el usuario, podrá ver los detalles de cada uno y ver lo que compró en su momento, además de poder añadir a favoritos o al carrito los elementos que necesite, o incluso poder comprarlo directamente |
| Favoritos | Lista con los productos favoritos del usuario, para cada uno de ellos puede quitarlo de favoritos, añadirlo al carrito o comprarlo directamente |
| Perfil | El usuario puede ver y modificar su información de la aplicación como la información personal, los métodos de pago y sus preferencias, además de realizar ciertas funciones como cerrar la sesión o borrar su cuenta |


### Prototipo Lo-FI Wireframe


### Conclusiones  

>> A lo largo de esta etapa se ha ido desarrollando una paulatina orientación al diseño, velando por identificar aquellas críticas constructivas de la etapa anterior, de manera que fuera posible diseñar una aplicación web que, además de mejorar estos aspectos señalados, aportase cierto grado de valor añadido. Es por esto que se ha realizado un análisis de tareas, fundamental también de cara al siguiente paso del proceso (arquitectura de información). Finalmente, se ha procedido a realizar un prototipo de diseño preliminar que refleje un poco la estructura y funcionamiento de nuestro proyecto.

>> Es reseñable comentar que, para lograr cuadrar los diseños, se han tenido que llevar a cabo algunas reconceptualizaciones, por lo que esta etapa no sigue una progresión lineal, sino cíclica. Esto es así porque, conforme se avanza en el proceso, se hace necesario revisar y/o modificar lo realizado hasta el momento.

>> Tras todo lo anteriormente comentado, hemos podido comprobar la relevancia y complejidad de la etapa de diseño, pues surgen numerosas preguntas e inquietudes a las que hay que dar respuesta para que las etapas posteriores puedan tener la suficiente consistencia y valor.
