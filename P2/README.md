## DIU - Practica2

### IDEACIÓN 

Tras haber terminado la practica 1, hemos llegado a diversas conclusiones respecto a la web *Moda re-*. Para expresarlas, hemos creado una malla receptoram en con distintos campos de información. 
<br>
**1. Worked:** Puntos positivos que hemos encontrado sobre la web.
<br>
**2. Change:** Problemas claros a nivel de usabilidad.
<br>
**3. Questions:** Preguntas que un usuario puede llegar a preguntarse nada más entrar a la página.
<br>
**4. Ideas:** Distintas propuestas de mejora.

![Malla receptora](malla_receptora.png)



### PROPUESTA DE VALOR

Tras haber analizado el diseño de la página web actual, hemos encontrado que una de las principales mejoras que podemos implementar, es el añadir una especie de foro, donde los distintos usuarios de forma pública, pueden añadir posts. El hilo de conversación sobre estos posts obviamente, girarán en torno a la ropa reciclada, y derivados de este. Además de compartir alguna experiencia personal, compartir tips sobre un estilo de vida reciclable etc. La imaginación es infinita, y los usuarios tendrán total libertad en este aspecto.

Aun así, esta libertad no puede ser total. Si cualquier usuario puede escribir lo que quiera, la página no tardará en llenarse de posts que no tengan nada que ver sobre el tema principal. Para ello, se tendrán varios filtros para controlar este hilo de posts:

1. Los propios usuarios, podrán valorar con un sistema interno de "felicidad" basado en tortugas. Si les gusta, y están de acuerdo con este, sumarán en uno, el contador de tortugas sanas y felices. Si no están de acuerdo, sumarán en uno, el contador de tortugas tristes y difuntas :(

2. Habrá un tipo de usuario, denominado, "usuario admin", el cual tiene poder sobre los post ajenos, pudiendo eliminar alguno de ellos, si lo considera ofensivo.

3. Habrá a su vez un filtro automático por código, el cual no dejará publicar posts que detecte que contenga palabras palabras malsonantes. 

![Scope Canvas](scope_canvas.png)



### TASK ANALYSIS

Hemos diseñado los pasos a seguir para 3 de las acciones que podrán realizar los usuarios que interactúen con nuestra propuesta de funcionalidad.

- Añadir una nueva publicación:

![Task1](task1.png)

- Ver las publicaciones de los demás:

![Task2](task2.png)



### ARQUITECTURA DE INFORMACIÓN


#### SiteMap (Mapa de sitio)
Es una representación estructurada de las páginas y contenido dentro de un sitio web o aplicación. Sirve como una guía para entender la organización y la jerarquía de la información. Vamos a definir la navegabilidad y la indexación de nuestra plataforma, beneficiando la experiencia de los usuarios.
  
El Sitemap de nuestra implementación es realmente básico, ya que al acceder al foro todo girará en torno al carrusel vertical de las publicaciones. Las distintas ventanas que aparecen, como la lateral o la de publicación de un nuevo post, son ventanas emergentes, que se muestran encima de la original. Partiendo de esto, llegamos a la siguiente estructura: 

![SiteMap](siteMap.png)

* Labelling

| Término         | Significado                                                             |
| -------------- | ---------------------------------------------------------------------- |
| FORO           | Ingresamos a la implementación                                       |
| Principal      | Pantalla principal que nos aparece al ingresar                       |
| Publicaciones  | Ventana que mediante scroll, vemos los distintos posts.              |
| Nueva Publicación | Ventana emergente que nos permite añadir un post.                  |
| Barra Lateral  | Menú desplegable, para ordenar y ver marcadores globales de tortugas. |
| Buscador       | Ingresamos texto para filtrar los posts.                             |




### Prototipo Lo-FI Wireframe 


### Conclusiones  
(incluye valoración de esta etapa)

Aquí tienes el texto con la misma estructura que el original, pero mejor redactado:  

---

Una de las valoraciones más positivas que sacamos de esta práctica es el enfoque imaginativo que se nos propone a la hora de recrear e implementar una nueva funcionalidad a nivel de diseño. Quisimos darle un toque de humor con el sistema de *tortugas tristes y felices*, enfocando la idea principal de valoraciones de los posts en esto, para aportar originalidad a nuestro sistema de publicación.  

A su vez, el diseño en Figma de la interfaz fue tedioso por momentos, especialmente al intentar estructurar cada elemento en su lugar. Sin embargo, lo más satisfactorio fue ver el proyecto terminado, con todos los bocetos y esquemas bien definidos.  

A modo de anécdota, hubo un momento curioso durante el desarrollo. Cuando ya teníamos diseñado el sistema para la web, incluimos un botón para añadir una nueva publicación, pero se nos pasó por completo poner uno para guardar y publicar el post.  

Como conclusión, hemos aprendido muchas ideas de diseño durante esta práctica, las cuales podremos aplicar en la creación de aplicaciones o páginas web en el futuro.
