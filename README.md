# DIU25
Prácticas Diseño Interfaces de Usuario (Tema: Reciclaje y artesanía (handcraft)) 

[Guiones de prácticas](GuionesPracticas/)

**Grupo:** DIU3.Pizza-con-Curry.  Curso: 2024/25 

Actualizado: 08/04/2025

**Proyecto:**

Tutoriales de **reciclado de ropa**.

**Descripción:** 

Nuestra propuesta de valor se basa en añadir esta nueva funcionalidad a la página, incluyendo un sistema de posts para que los usuarios puedan publicar sus propios tutoriales de reciclaje de ropa y, a su vez, consultar los tutoriales publicados por el resto.

El hilo de conversación sobre estos posts obviamente girará en torno a la ropa reciclada, y derivados de este. Además de compartir alguna experiencia personal, compartir tips sobre un estilo de vida reciclable etc. La imaginación es infinita, y los usuarios tendrán total libertad en este aspecto.

**Logotipo:** 

>>> Si diseña un logotipo para su producto en la práctica 3 pongalo aqui, a un tamaño adecuado. Si diseña un slogan añadalo aquí

Miembros:
 * :bust_in_silhouette:  [Samuel Sánchez Cantero](https://github.com/Zapi24)     :octocat:   
 
 * :bust_in_silhouette:  [Victoria Dueñas Salcedo](https://github.com/vduesal)     :octocat:   

----- 



# Proceso de Diseño 


## Paso 1. UX User & Desk Research & Analisis 

### 1.a User Reseach Plan
![Método UX](img/Competitive.png) 
-----

La plataforma que vamos a analizar es la tienda de ropa de segunda mano *Moda re-*, la cual fomenta el uso sostenible de la ropa, dándole una segunda vida en tiendas locales a nivel nacional. Con este plan de investigación, vamos a localizar aquellas posibles taras que dificultan la experiencia que pueda tener el usuario sobre esta, con el objetivo siempre de proponer mejoras y sugerir nuevas funcionalidades que mejoren esta experiencia.

Taras: 
- **Sobrecarga de información**: la web no sigue la conocida “regla de los tres clics”. Esta regla consiste en que para hacer alguna operación en la página, al tener algunas funcionalidades demasiado rebuscadas, tenemos que indagar más de lo necesario en esta. Esto incluye la calidad del contenido y la desestructuración de la web. También afecta negativamente a la promoción de las ventas.
- **Limitación geográfica**: al ser una página web de ropa, nos pueden dar la falsa idea, así como la posibilidad de comprar por internet. Sin embargo, en ningún momento nos especifica que esta funcionalidad no está implementada, sino que solo ofrece opciones de compra en tiendas físicas locales, lo que reduce mucho su alcance.
- **No va a lo importante**: el objetivo final de las empresas de ropa es promocionar sus ventas. Por esta razón, nada más entrar a la página web, lo primero que se nos debería mostrar es la información correspondiente a las compras. Desconocemos el objetivo principal de la empresa, ya que nos lo ofrece como el reciclaje de la ropa, mientras que este debería ser el objetivo secundario que va ligado a la compra de ropa de segunda mano y reciclada.
- **Problema con la interfaz**: se han querido añadir tantos “efectos” y “transiciones” de imágenes e información que a veces no es fácil interactuar con la web. La entrada a esta página es complicada, una persona que no tenga mucha soltura con las tecnologías, puede no llegar a entenderla e interactuar con esta fácilmente. También resulta difícil identificar, con qué elementos de la página, podemos interactuar realmente, y con cuáles no. Además, si nos damos cuenta, la información relevante pasa a un segundo plano, llamando mucho más la atención las imágenes y los efectos visuales que la información que nos quiere llegar a ofrecer.

Propuestas de mejora y nuevas funcionalidades:
- **Simplificar la navegación y hacerla más intuitiva**: la web necesita una estructura mucho más clara y sencilla, donde los usuarios encuentren lo que buscan de forma directa. Podría mejorarse con la implementación de una barra de búsqueda visible nada más entrar en la web que muestre las distintas funcionalidades que puede ofrecer. Una interfaz limpia con botones claros y fáciles de usar haría que cualquier persona pueda utilizar la web sin problemas.
- **Tienda online**: actualmente la web da la impresión de que se puede comprar online, pero no es así. Se podría implementar una tienda online, priorizando las ventas, aunque puede que no sea viable para la economía de la empresa. Debería informarse al usuario de que esta funcionalidad no existe, proporcionando la ubicación de las tiendas físicas de forma más directa.
- **Priorizar las ventas**: la página web, debe enfocarse en promocionar los productos y ofertas desde el primer momento. El reciclaje y la sostenibilidad, son señales de identidad para la empresa, pero es un complemento asociado a su producto de venta, que es la ropa de segunda mano.
- **Añadir funcionalidad a la empresa**: podríamos incluir una sección de tutoriales para reutilizar prendas viejas, pudiendo ser posibles productos para la empresa, reforzando la imagen sostenible de la empresa.


### 1.b Competitive Analysis
![Método UX](img/Competitive.png) 
-----

La plataforma que hemos elegido para analizar es *Moda re-*, la cual es un proyecto de inclusión social que gestiona ropa usada, genera puestos de empleo para personas en riesgo de exclusión y fomenta la economía circular. Posee una red de tiendas textiles locales repartidas por todo el territorio nacional, en las cuales puedes donar ropa que ya no utilices para darle una segunda vida.

![](P1/competitor_analysis.jpg)

### 1.c Personas
![Método UX](img/Persona.png) 
-----

A la hora de analizar las diferentes situaciones problemáticas que pueden surgir a la hora de acceder a [Moda re-](https://modare.org/), hemos generado dos perfiles ficticios (Amparo y Jorge).

Las siguientes dos personas tienen interés por los servicios que ofrece Mora re-. Aparentemente, son perfiles de personas muy diferentes, tanto en raíces como en conocimiento, recursos y estilo de vida. Aún así, se ven relacionados en el hecho de que Amparo quiere buscar como poder darle una segunda vida a ropa que tiene acumulada, y Jorge quiere comprar ropa de segunda mano online.

![Amparo](P1/amparo.jpg)

![Jorge](P1/jorge.png)


### 1.d User Journey Map
![Método UX](img/JourneyMap.png) 
----

Escogemos dos experiencias de usuario que hacen uso de las funcionalidades de la plataforma para poder saber cuales son sus puntos débiles.

La aspiración de Amparo es poder encontrar un uso que darle a toda esa ropa guardada que tiene en casa.

![Journey map de Amparo](P1/amparo_journeymap.jpg)

Jorge está intentando buscar nuevas webs de ropa de segunda mano, y es ahí cuando se encuentra con *Moda re-* y decide acceder para ver las prendas que oferta este sitio.

![Journey map de Jorge](P1/jorge_journeymap.png)


### 1.e Usability Review
![Método UX](img/usabilityReview.png) 
----

Tras hacer una revisión de usabilidad de la web de *Moda re-* a fondo, encontramos sus puntos fuertes y débiles.

- Enlace al documento: [plantilla](P1/Usability-review-Modare.pdf)
- URL y Valoración numérica obtenida: 60/100
- Comentario sobre la revisión: Tras haber encontrado los puntos fuertes y débiles de la página web hemos podido llegar a distintas conclusiones. Por lo general, es una web que tiene un correcto funcionamiento, hace lo esperado, sin embargo, esto no implica que esté bien diseñada. La interfaz para nosotros, es el mayor problema. Es introducirte en la web, y te saturas de imágenes, transiciones y efectos visuales, alejando la puerta de entrada y confundiendo a los usuarios. No se sabe muy bien con qué elementos se pueden interactuar, y con cuáles no. Además, las funcionalidades que nos ofrecen, están muy limitadas, como ya hemos comentado dentro del punto "1a", pues no ofrece las posibilidades, que te puedes esperar de primeras de una web de ropa de segunda mano.

<br>

## Paso 2. UX Design  

### 2.a IDEACION: Feedback Capture Grid 
![Método UX](img/feedback-capture-grid.png) 
----

Tras haber terminado la práctica 1, hemos llegado a diversas conclusiones respecto a la web *Moda re-*. Para expresarlas, hemos creado una malla receptora con distintos campos de información. 
<br>
**1. Worked:** Puntos positivos que hemos encontrado sobre la web.
<br>
**2. Change:** Problemas claros a nivel de usabilidad.
<br>
**3. Questions:** Preguntas que un usuario puede llegar a preguntarse nada más entrar a la página.
<br>
**4. Ideas:** Distintas propuestas de mejora.

![Malla receptora](P2/malla_receptora.png)


### 2.b ScopeCanvas
![Método UX](img/ScopeCanvas.png)
----

Tras haber analizado el diseño de la página web actual, hemos encontrado que una de las principales mejoras que podemos implementar, es el añadir una especie de foro, donde los distintos usuarios de forma pública, pueden añadir posts. El hilo de conversación sobre estos posts obviamente, girarán en torno a la ropa reciclada, y derivados de este. Además de compartir alguna experiencia personal, compartir tips sobre un estilo de vida reciclable etc. La imaginación es infinita, y los usuarios tendrán total libertad en este aspecto.

Aun así, esta libertad no puede ser total. Si cualquier usuario puede escribir lo que quiera, la página no tardará en llenarse de posts que no tengan nada que ver sobre el tema principal. Para ello, se tendrán varios filtros para controlar este hilo de posts:

1. Los propios usuarios, podrán valorar con un sistema interno de "felicidad" basado en tortugas. Si les gusta, y están de acuerdo con este, sumarán en uno, el contador de tortugas sanas y felices. Si no están de acuerdo, sumarán en uno, el contador de tortugas tristes y difuntas :(

2. Habrá un tipo de usuario, denominado, "usuario admin", el cual tiene poder sobre los post ajenos, pudiendo eliminar alguno de ellos, si lo considera ofensivo.

3. Habrá a su vez un filtro automático por código, el cual no dejará publicar posts que detecte que contenga palabras palabras malsonantes. 

![Scope Canvas](P2/scope_canvas.png)


### 2.b User Flow (task) analysis 
![Método UX](img/Sitemap.png) 
-----

Hemos diseñado los pasos a seguir para 3 de las acciones que podrán realizar los usuarios que interactúen con nuestra propuesta de funcionalidad.

- Añadir una nueva publicación:

![Task1](P2/task1.png)

- Ver las publicaciones de los demás:

![Task2](P2/task2.png)



### 2.c IA: Sitemap + Labelling 
![Método UX](img/labelling.png) 
----

#### SiteMap (Mapa de sitio)
Es una representación estructurada de las páginas y contenido dentro de un sitio web o aplicación. Sirve como una guía para entender la organización y la jerarquía de la información. Vamos a definir la navegabilidad y la indexación de nuestra plataforma, beneficiando la experiencia de los usuarios.
  
El Sitemap de nuestra implementación es realmente básico, ya que al acceder al foro todo girará en torno al carrusel vertical de las publicaciones. Las distintas ventanas que aparecen, como la lateral o la de publicación de un nuevo post, son ventanas emergentes, que se muestran encima de la original. Partiendo de esto, llegamos a la siguiente estructura: 

![SiteMap](P2/siteMap.png)



#### Labelling
El proceso de asignar nombres claros y descriptivos a los elementos de una interfaz de usuario, como menús, botones y enlaces. Su objetivo es mejorar la usabilidad y la comprensión del usuario al proporcionar indicaciones precisas y coherentes sobre la función de cada elemento.

   
| Término         | Significado                                                             |
| -------------- | ---------------------------------------------------------------------- |
| FORO           | Ingresamos a la implementación                                       |
| Principal      | Pantalla principal que nos aparece al ingresar                       |
| Ver Publicación  | Ventana para ver el post desde más cerca.             |
| Nueva Publicación | Ventana emergente que nos permite añadir un post.                  |
| Barra Lateral  | Menú desplegable, para ordenar y ver marcadores globales de tortugas. |
| Buscador       | Ingresamos texto para filtrar los posts.                             |



### 2.d Wireframes
![Método UX](img/Wireframes.png) 
-----


<div align="center">
  <img src="./P2/Inicio.png" alt="Inicio" height="600" width="auto">
</div>
<br>

**Pantalla de inicio:**  
Interfaz de inicio, con la cual podemos navegar a través del foro. Si pulsamos en la primera publicación, que es una publicación vacía, podemos añadir una nueva publicación. Si utilizamos el buscador podemos filtrar por palabras para buscar algo en concreto. Podemos pulsar en las 3 líneas para abrir la barra lateral. Y por último y más importante, podemos scrollear hacia abajo, para ver los demás post del foro, pudiendo pulsar en ellos para verlos desde más cerca.

---

<div align="center">
  <img src="./P2/Filtrar.png" alt="Filtrar" height="600" width="auto">
</div>
<br>

**Ordenación de publicaciones y contador global de interacciones (barra lateral):**  
Al pulsar en las 3 líneas accedemos a la barra lateral, y pulsándolas de nuevo, salimos de esta. Dentro de esta barra podemos ordenar los posts por “post más ecológicos” o “menos ecológicos”, es decir, ordenar los post por mayor número de tortugas felices o tristes en todo el foro. Además de un marcador global donde se ven estas estadísticas.

---

<div align="center">
  <img src="./P2/Publicar.png" alt="Publicar" height="600" width="auto">
</div>
<br>

**Publicar un post:**  
Al pulsar en la primera publicación (vacía) nos aparece una ventana emergente sobre el foro, donde podemos añadir una nueva publicación a este. Debemos completar los campos obligatorios de identificación, y completar el post a nuestro gusto, pudiendo añadir multimedia. Podemos volver atrás si no queremos publicar nada, o terminar de publicar nuestro post.

---

<div align="center">
  <img src="./P2/Visualizar.png" alt="Visualizar" height="600" width="auto">
</div>

<br>

**Visualizar e interaccionar con una publicación:**  
Al pulsar en una de las publicaciones ya existentes en el foro nos aparece una ventana emergente en la que podemos ver la publicación actual completa, con sus archivos adjuntos, y en la que podemos interaccionar mediante las tortugas en función de si nos gusta más o menos la publicación. Podemos volver atrás cuando queramos volver a la pantalla de inicio del foro, o podemos pasar a la siguiente publicación para seguir interaccionando con ellas.

---


<br>

### Conclusión sobre la P2:

Una de las valoraciones más positivas que sacamos de esta práctica es el enfoque imaginativo que se nos propone a la hora de recrear e implementar una nueva funcionalidad a nivel de diseño. Quisimos darle un toque de humor con el sistema de tortugas tristes y felices, enfocando la idea principal de valoraciones de los posts en esto, para aportar originalidad a nuestro sistema de publicación.

A su vez, el diseño en Figma de la interfaz fue tedioso por momentos, especialmente al intentar estructurar cada elemento en su lugar. Sin embargo, lo más satisfactorio fue ver el proyecto terminado, con todos los bocetos y esquemas bien definidos.

A modo de anécdota, hubo un momento curioso durante el desarrollo. Cuando ya teníamos diseñado el sistema para la web, incluimos un botón para añadir una nueva publicación, pero se nos pasó por completo poner uno para guardar y publicar el post.

Como conclusión, hemos aprendido muchas ideas de diseño durante esta práctica, las cuales podremos aplicar en la creación de aplicaciones o páginas web en el futuro.

<br>

## Paso 3. Mi UX-Case Study (diseño)

>>> Cualquier título puede ser adaptado. Recuerda borrar estos comentarios del template en tu documento


### 3.a Moodboard
![Método UX](img/moodboard.png)
-----

>>> Diseño visual con una guía de estilos visual (moodboard) 
>>> Incluir Logotipo. Todos los recursos estarán subidos a la carpeta P3/
>>> Explique aqui la/s herramienta/s utilizada/s y el por qué de la resolución empleada. Reflexione ¿Se puede usar esta imagen como cabecera de Instagram, por ejemplo, o se necesitan otras?


### 3.b Landing Page
![Método UX](img/landing-page.png) 
----

>>> Plantear el Landing Page del producto. Aplica estilos definidos en el moodboard


### 3.c Guidelines
![Método UX](img/guidelines.png) 
----

>>> Estudio de Guidelines y explicación de los Patrones IU a usar 
>>> Es decir, tras documentarse, muestre las deciones tomadas sobre Patrones IU a usar para la fase siguiente de prototipado. 


### 3.d Mockup
![Método UX](img/mockup.png) 
----

>>> Consiste en tener un Layout en acción. Un Mockup es un prototipo HTML que permite simular tareas con estilo de IU seleccionado. Muy útil para compartir con stakeholders


### 3.e ¿My UX-Case Study?
![Método UX](img/caseStudy.png) 
-----

>>> Publicar my Case Study en Github... Es el momento de dejar este documento para que sea evaluado y calificado como parte de la práctica
>>> Documente bien la cabecera y asegurese que ha resumido los pasos realizados para el diseño de su producto

<br>

## Paso 4. Pruebas de Evaluación 

### 4.a Reclutamiento de usuarios 
![Método UX](img/usability-testing.png)
-----

>>> Breve descripción del caso asignado (llamado Caso-B) con enlace al repositorio Github
>>> Tabla y asignación de personas ficticias (o reales) a las pruebas. Exprese las ideas de posibles situaciones conflictivas de esa persona en las propuestas evaluadas. Mínimo 4 usuarios: asigne 2 al Caso A y 2 al caso B.



| Usuarios | Sexo/Edad     | Ocupación   |  Exp.TIC    | Personalidad | Plataforma | Caso
| ------------- | -------- | ----------- | ----------- | -----------  | ---------- | ----
| User1's name  | H / 18   | Estudiante  | Media       | Introvertido | Web.       | A 
| User2's name  | H / 18   | Estudiante  | Media       | Timido       | Web        | A 
| User3's name  | M / 35   | Abogado     | Baja        | Emocional    | móvil      | B 
| User4's name  | H / 18   | Estudiante  | Media       | Racional     | Web        | B 


### 4.b Diseño de las pruebas 
![Método UX](img/usability-testing.png) 
-----

>>> Planifique qué pruebas se van a desarrollar. ¿En qué consisten? ¿Se hará uso del checklist de la P1?



### 4.c Cuestionario SUS
![Método UX](img/Survey.png) 
----

>>> Como uno de los test para la prueba A/B testing, usaremos el **Cuestionario SUS** que permite valorar la satisfacción de cada usuario con el diseño utilizado (casos A o B). Para calcular la valoración numérica y la etiqueta linguistica resultante usamos la [hoja de cálculo](https://github.com/mgea/DIU19/blob/master/Cuestionario%20SUS%20DIU.xlsx). Previamente conozca en qué consiste la escala SUS y cómo se interpretan sus resultados
http://usabilitygeek.com/how-to-use-the-system-usability-scale-sus-to-evaluate-the-usability-of-your-website/)
Para más información, consultar aquí sobre la [metodología SUS](https://cui.unige.ch/isi/icle-wiki/_media/ipm:test-suschapt.pdf)
>>> Adjuntar en la carpeta P4/ el excel resultante y describa aquí la valoración personal de los resultados 


### 4.d A/B Testing
![Método UX](img/ABtesting.png) 
-----

>>> Los resultados de un A/B testing con 3 pruebas y 2 casos o alternativas daría como resultado una tabla de 3 filas y 2 columnas, además de un resultado agregado global. Especifique con claridad el resultado: qué caso es más usable, A o B?

### 4.e Aplicación del método Eye Tracking 
![Método UX](img/eye-tracking.png)
----

>>> Indica cómo se diseña el experimento y se reclutan los usuarios. Explica la herramienta / uso de gazerecorder.com u otra similar. Aplíquese únicamente al caso B.


![experimento](img/experimentoET.png)  
>>> Cambiar esta img por una de vuestro experimento. El recurso deberá estar subido a la carpeta P4/  

>>> gazerecorder en versión de pruebas puede estar limitada a 3 usuarios para generar mapa de calor (crédito > 0 para que funcione) 


### 4.f Usability Report de B
![Método UX](img/usability-report.png) 
-----

>>> Añadir report de usabilidad para práctica B (la de los compañeros) aportando resultados y valoración de cada debilidad de usabilidad. 
>>> Enlazar aqui con el archivo subido a P4/ que indica qué equipo evalua a qué otro equipo.

>>> Complementad el Case Study en su Paso 4 con una Valoración personal del equipo sobre esta tarea



<br>

## Paso 5. Exportación y Documentación 


### 5.a Exportación a HTML/React
![Método UX](img/usabilityReview.png) 
----

>>> Breve descripción de esta tarea. Las evidencias de este paso quedan subidas a P5/


### 5.b Documentación con Storybook
![Método UX](img/usabilityReview.png)
----

>>> Breve descripción de esta tarea. Las evidencias de este paso quedan subidas a P5/


<br>

## Conclusiones finales & Valoración de las prácticas


>>> Opinión FINAL del proceso de desarrollo de diseño siguiendo metodología UX y valoración (positiva /negativa) de los resultados obtenidos. ¿Qué se puede mejorar? Recuerda que este tipo de texto se debe eliminar del template que se os proporciona 




