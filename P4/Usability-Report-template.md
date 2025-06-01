# Usability Report



<img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRF017nhV-TFmNER2OM8UbXtdN6xwAKBYrv0i6onNfKu6Yn0BV0RK6aiOroeXl73LSY-B0&usqp=CAU" alt="usability Download png" style="zoom:50%;" />


---

Realizado por:
Informe realizado por el equipo DIU3.pizza_con_curry, dentro de la asignatura Diseño de Interfaces de Usuario.
En esta práctica combinamos técnicas como A/B Testing, SUS y Eye Tracking para valorar la usabilidad.

### 1 DESCRIPCIÓN DEL PROYECTO

El proyecto de rediseño de **EcoNecta** se centra en crear una plataforma que promueva un estilo de vida más sostenible y saludable, facilitando el acceso a productos ecológicos directamente de agricultores y ganaderos locales. Su aplicación busca ser un punto de conexión entre productores y consumidores, ofreciendo una experiencia de usuario fluida y un catálogo de productos sostenibles.

### 2 RESUMEN EJECUTIVO

Este documento presenta el análisis de usabilidad de dos prototipos: nuestro proyecto de prácticas y el de nuestros compañeros de EcoNecta, utilizando **A/B Testing**, **cuestionarios SUS** y **Eye Tracking**.

**Principales hallazgos:**

* Ambos prototipos muestran una **alta usabilidad percibida** por los usuarios, con puntuaciones elevadas en el cuestionario SUS.
* La funcionalidad clave de "publicar un nuevo post" (o "vender un nuevo producto") es **accesible en ambos diseños**, aunque con diferencias en la eficiencia.
* La **jerarquía visual** y la ubicación de los elementos de interacción impactan directamente en la **rapidez y el número de errores** al completar tareas.
* Los enlaces de descarga en la *landing page* de EcoNecta captan **alta atención visual**, lo que es ideal para su objetivo.

**Problemas detectados:**

* En el caso del prototipo de EcoNecta, la opción de "vender" en el *footer* puede **retrasar la interacción inicial** de algunos usuarios, requiriendo más clics y tiempo.
* Una **imagen decorativa** en la *landing page* de EcoNecta capta **demasiada atención** de algunos usuarios, lo que podría distraer del contenido principal o de los llamados a la acción.


### 3 METODOLOGÍA

Para evaluar las interfaces, aplicamos tres métodos principales:

* **A/B Testing:** Comparamos de forma estructurada nuestro prototipo con el de EcoNecta para una tarea específica (publicar un *post* / vender un producto), midiendo tiempo, clics y errores.
* **Cuestionario SUS (System Usability Scale):** Utilizamos un cuestionario de 10 preguntas para obtener una puntuación cuantificable de la usabilidad percibida por los usuarios de cada prototipo.
* **Eye Tracking:** Empleamos GazeRecorder para analizar los patrones de atención visual de los usuarios en la *landing page* del prototipo de EcoNecta, identificando los elementos que más llaman la atención y las zonas de interés.

**Test de usuarios: Participantes**

| Usuarios | Sexo/Edad | Ocupación | Exp.TIC | Personalidad | Plataforma | Caso | Real/Ficticio |
| :------- | :-------- | :-------- | :-------- | :----------- | :--------- | :--- | :------------ |
| Ángela   | M / 21    | Enfermera en prácticas | Medio   | Intensa      | Windows / Web / Android | A    | Real          |
| Alba     | M / 20    | Estudiante de Ingeniería de Computadores | Alta    | Independiente | Linux / Windows / Web / Android | A    | Real          |
| Samuel   | H / 20    | Estudiante de Ingeniería informática | Alta    | Emocional    | Linux / Windows / Web / Android | B    | Real          |
| Vicky    | M / 25    | Desarrolladora de D365 | Alta    | Resolutiva   | Windows / Web / IOS | B    | Real          |

**Resultados obtenidos**

**Cuestionario SUS:**

* **Caso A (Nuestro proyecto):** 95/100 (Ángela), 90/100 (Alba)
* **Caso B (EcoNecta):** 92.5/100 (Samuel), 95/100 (Vicky)

Los resultados del cuestionario SUS para ambos proyectos son bastante altos, sugiriendo una buena percepción general de usabilidad por parte de todos los usuarios evaluados. En particular, Samuel destacó la intuición y facilidad de uso del *wireframe* de EcoNecta, y Vicky resaltó sus funcionalidades y alta facilidad de uso.

**A/B Testing (Tarea: Publicar un nuevo post/Vender un nuevo producto):**

| Usuario | Caso A (Tiempo / Clics / Errores) | Caso B (Tiempo / Clics / Errores) | Observaciones |
| :------ | :-------------------------------- | :-------------------------------- | :------------ |
| Ángela  | 2.5 seg / 1 clic / 1 error        | 5 seg / 4 clics / 2 errores       | Ángela (personalidad "intensa") exploró rápidamente, mostrando una tendencia a navegar en lugar de leer en el Caso A. En el Caso B, su búsqueda de la opción "vender" fue más indirecta. |
| Alba    | 3 seg / 1 clic / 0 errores        | 6 seg / 1 clic / 0 errores        | Alba, más calmada y analítica, completó ambas tareas sin errores, pero tardó más en el Caso B al analizar la interfaz. |

El **Caso A** demostró ser **más intuitivo y rápido** para la tarea de publicación en ambos usuarios, requiriendo menos tiempo, clics y errores. La ubicación de la funcionalidad en el *footer* del **Caso B** parece influir negativamente en la eficiencia inicial.

**Eye Tracking (solo para Caso B – EcoNecta):**

* **Alta concentración visual** en los **enlaces de descarga**, lo que es un éxito para el objetivo de la *landing page*.
* Se observó que una **imagen decorativa** en la derecha de la *landing page* captó una cantidad significativa de atención visual, especialmente en el primer usuario.


### 4 CONCLUSIONES

Las pruebas de usabilidad realizadas sobre nuestro prototipo y el de EcoNecta revelan una **experiencia de usuario mayoritariamente positiva**. Ambos diseños demuestran ser efectivos, y los cuestionarios SUS confirman una **alta percepción de usabilidad**.

**Problemas principales:**

* La **ubicación de elementos clave** (como la opción de "vender" en el *footer* de EcoNecta) puede generar un mayor tiempo de interacción y más clics para usuarios que no están familiarizados con el diseño.
* Elementos visuales **puramente decorativos** pueden desviar la atención de los usuarios de los puntos de interés principales, como se observó con la imagen en la *landing page* de EcoNecta.

**Valoración:**

* Ambos *wireframes* muestran una **buena accesibilidad** para la funcionalidad evaluada, aunque con diferencias en la eficiencia.
* Nuestro prototipo (Caso A) demostró una **mayor intuición y rapidez** para la tarea de publicación.
* La *landing page* de EcoNecta (Caso B) logra **captar la atención** en sus enlaces de descarga, lo cual es fundamental para su objetivo de difusión.
* El diseño general de ambos proyectos presenta **coherencia y consistencia**, lo que facilita la navegación.

**Recomendaciones y propuesta de mejoras:**

* Para el prototipo de EcoNecta, considerar la **reubicación de la funcionalidad "vender"** a una zona más prominente o añadir señales visuales más claras, especialmente fuera del *footer*, para mejorar la eficiencia.
* Revisar la **relevancia visual de elementos decorativos** en las *landing pages* para asegurar que no distraen la atención de los llamados a la acción principales. Si la imagen decorativa es clave, quizás se podría integrar de una forma que no compita tanto con otros elementos.

**Valoración de la prueba de usabilidad (self-assessment):**

Las técnicas empleadas (A/B Testing, cuestionario SUS y Eye Tracking) resultaron **sumamente útiles** para identificar tanto las fortalezas como las oportunidades de mejora en ambos diseños. El **A/B Testing** fue clave para comparar la eficiencia de la tarea específica, mientras que el **cuestionario SUS** nos dio una visión cuantificable de la percepción general de usabilidad. El **Eye Tracking** fue particularmente revelador para entender la atención visual de los usuarios y validar si los elementos clave captan la mirada como se espera.

En conjunto, las pruebas han sido fundamentales para **detectar detalles de usabilidad** que de otro modo podrían haber pasado desapercibidos, y nos permiten validar que los rediseños cumplen con los objetivos de accesibilidad, claridad y eficiencia en la experiencia del usuario.
