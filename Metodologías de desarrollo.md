# Metodologías de desarrollo

---

### **METODOLOGÍA EN CASCADA**

- Esta metodología es ideal para proyectos en donde se tengan bien especificados sus requerimientos, y su diseño esté bien detallado así como que el equipo tenga una experiencia alta.
- Se realiza de forma completa para pasar a la siguiente fase.

### **Fases**

1. **Análisis de requerimientos:** En esta fase se analizan que requisitos tendrá el software, funcionales y no funcionales (hardware, software, de seguridad, entre otros).
2. **Diseño:** Se diseñan cada uno de los modulos del software, algoritmos, Interfaces de usuario y la arquitectura.
3. **Implementación:** Se desarrolla el código, base de datos y se implementan los modulos desarrollados anteriormente.
4. **Pruebas:** Se aplican pruebas unitarias al software para concluir si cumple con cada uno de los requisitos solicitados.
5. **Mantenimiento:** Una vez entregado el software se realizan correcciones de errores y el mantenimiento o mejoras de este.

****************VENTAJAS****************

- **Estructura clara.**
- ****Documentación completa.**** Puesto que cada fase debe de estar terminada para pasar a la siguiente se posee una documentación extensa de cada una de estas.
- ************Control de calidad.************ Para cada fase se hacen pruebas y validaciones que mejoran la calidad del software.

**********************DESVENTAJAS**********************

- ******************************Falta de flexibilidad.****************************** Por ser un modelo secuencial no se permiten cambios pasando a la siguiente fase.
- ****************Riesgo de retrasos.**************** Si se descubre un error en fases pasadas sería necesario volver y retrasar la entrega del proyecto.
- ******************************************************************Enfoque en la documentación más que en la calidad.****************************************************************** Esto suele pasar porque el modelo enfatiza más en la documentación que en la calidad del software, haciendo que los desarrolladores pongan mas esfuerzo en la documentación.

**En resumen esta es útil para proyectos en donde todos los requisitos estén bien claros y definidos puesto que no tiene flexibilidad para realizar cambios aparte se necesita una precisión alta porque si se descubren errores en una fase anterior, corregirlo retrasará la entrega del proyecto.
Tambien es ideal para proyectos críticos como aéroespaciales, militares o médicos puesto que ya se tienen metas muy bien definidas**

### CUANDO UTILIZARLA / EJEMPLOS

1. Desarrollo de software para sistemas embebidos:
Dado que se integra el hardware estrechamente con el software es muy poco probable que los requisitos puedan cambiar a lo largo del proyecto. Este modelo es buena opción puesto que los requisitos pueden definirse con claridad desde el principio.
2. Proyectos de software a pequeña escala: 
Los proyectos pequeños son relativamente simple y se puede definir el alcance del proyecto con claridad desde el principio.
3. Desarrollo de software de tipo herramienta: 
En proyectos que implican el desarrollo de software de tipo herramienta, donde el software se utiliza para realizar una tarea específica, como la edición de imágenes o la gestión de archivos, el modelo en cascada puede ser una buena opción porque los requisitos del software son generalmente claros y bien definidos desde el principio.
4. Proyectos en los que los requisitos son estáticos: 
En proyectos en los que los requisitos son estáticos como en proyectos de migración de datos, el modelo en cascada puede ser una buena opción porque los requisitos pueden definirse con claridad desde el principio y no es probable que cambien significativamente.

---

---

## METODOLOGÍA EN ESPIRAL

- Este modelo se enfoca más en la gestión de riesgos.
- Existe un ciclo continuo de planificación, diseño, construcción y evaluación en cada ciclo.
Ideal para proyectos de software complejos y grandes o **************************************************de requisitos cambiantes.**************************************************
- Se gestionan riesgos técnicos, de mercado, de tiempo, de costo, entre otros.
- Permite identificar los riesgos que puedan desestabilizar el proyecto y mitigarlos o evitarlos de forma temprana en cada fase.
- Es iterativo

### **Se divide en 4 fases**

1. ****Planificación:**** En esta fase se define el alcance del proyecto y los requisitos, así como los recursos que se necesitarán emplear para llevarse a cabo.
2. ******Análisis de riesgos:****** Se identifican los riesgos que puedan perjudicar al proyecto y se desarrolla un plan para mitigarlos. Esto se puede hacer a través de pruebas o simulaciones.
3. **************************************************Desarrollo y revision:************************************************** Los prototipos se desarrollan (o se amplían y se les añaden funcionalidades si se viene de una iteración), se realizan pruebas técnicas hasta que pueda ser implementado en un entorno productivo.
4. ********************Planeación de la siguiente iteración:******************** Se analiza lo finalizado, si existen errores se corrigen y si existe una mejor alternativa, se implementa en el siguiente ciclo.

![Untitled](Metodologi%CC%81as%20de%20desarrollo%200a5d62362db240b9a39826ff2c4086cb/Untitled.png)

Al terminar cada ciclo/iteración se trabaja sobre lo que ya se tenía anteriormente, añadiendo mejoras en el nuevo ciclo y haciendo cada fase de nuevo con mayor detalle.

****************VENTAJAS****************

- Mejor gestión de los riesgos. 
Esto ya que en cada iteración se identifican, se evalúan y mitigan.
- Mayor calidad del software.
Las iteraciones se centran en mejorar el software.
- Flexibilidad.
Permite cambios del cliente.
- Satisfacción de cliente.
El modelo le permite integrar al cliente para poder retroalimentar el proyecto en el proceso del desarrollo.

**********************DESVENTAJAS**********************

- Complejidad.
Se necesitan habilidades especiales para identificar, evaluar y mitigar riesgos.
- Mayor tiempo y costo.
Por la naturaleza del modelo, no hay tiempos exactos de entrega puesto que cada iteración es tardada así como su costo que puede elevarse por tener varias ciclos.
- Gestion rigurosa.
Se debe gestionar de manera especifica y detallada para garantizar que los riesgos puedan identificarse y mitigarse.

**En resumen la metodología es precisa para proyectos en donde se necesite una precisión y seguridad alta, esto puesto que se necesitan detectar todos los riesgos posibles en cada iteración. 
Cada iteración permite una mejora continua y la detección de nuevos riesgos por lo que es ideal para software donde puedan depender vidas o datos muy importantes. 
O también puede ser usado para proyectos en donde se requiera una flexibilidad y adaptabilidad en cambios alta para poder implementarla sin dificultad.**

### CUANDO UTILIZARLA / EJEMPLOS

1. Sistemas de control de tráfico aéreo: 
Estos sistemas requieren de mucha precision y control por los riesgos altos de seguridad que existen, el modelo en espiral permite gestionar de mucho mejor manera estos riesgos y mitigarlos alcanzando un software de alta calidad por cada iteración.
2. Sistemas de gestión bancaria: los sistemas de gestión bancaria requieren una alta seguridad y precisión, y deben ser capaces de manejar grandes volúmenes de datos. La metodología de desarrollo en espiral puede ayudar a los desarrolladores a mitigar los riesgos asociados con la seguridad y la gestión de datos, y permitir una mayor adaptación a los cambios en las regulaciones bancarias y los requisitos del cliente.
3. Sistemas de gestión de proyectos complejos: los sistemas de gestión de proyectos complejos, como los utilizados en la industria aeroespacial o de defensa, pueden requerir una gestión rigurosa de riesgos y cambios en los requisitos. La metodología de desarrollo en espiral permite a los desarrolladores identificar y mitigar los riesgos en cada iteración del proceso de desarrollo, lo que ayuda a garantizar el éxito del proyecto y la satisfacción del cliente.
4. Proyecto de software para una aplicación móvil de comercio electrónico:
Podría requerir una gestión efectiva de riesgos, ya que la seguridad y privacidad de los datos de los usuarios son críticos para la confianza del cliente en la aplicación. Además, la aplicación podría requerir una gestión efectiva de cambios en los requisitos, ya que los requisitos de los clientes y los cambios en las regulaciones comerciales pueden cambiar rápidamente.

---

---

## METODOLOGÍA RAD (RAPID APP DEVELOPMENT)

- Modelo iterativo e incremental
- Basado en la entrega rápida de software
- Se colabora con el cliente
- Tiene más en cuenta el uso del software y la opinión del usuario que la planificación rigurosa y registro de requisitos
- Se centra en prototipos

### **Se divide en 5 fases**

1. Requisitos
2. Diseño de prototipos
3. Feedback del usuario
4. Prueba del producto
5. Presentación, lanzamiento de la aplicación

****************VENTAJAS****************

- Tiempos de entregas más rápidos
- Feedback constante
- Menor costo.
Puesto que se hacen uso de herramientas que permitan desarrollar código más rápido y reutilizable.

**********************DESVENTAJAS**********************

- Complejidad.
- Menor documentación.
A comparación de otras metodologías, puede ser menor
- Requisitos del cliente incompletos

**En resumen esta metodología es ideal para proyectos en donde los requisitos no estén completos y se necesiten entregas rápidas puesto que se centra en la creación de prototipos que posteriormente se mejorarán en cada iteración gracias también a una interacción continua con el cliente que aportará un feedback a estos.**

### CUANDO UTILIZARLA / EJEMPLOS

1. Desarrollo de software empresarial: La metodología RAD puede ser utilizada en proyectos de desarrollo de software empresarial que requieren una entrega rápida y una mayor flexibilidad para realizar cambios.
2. Desarrollo de aplicaciones móviles: La metodología RAD puede ser utilizada en proyectos de desarrollo de aplicaciones móviles donde los ciclos de desarrollo deben ser cortos para garantizar una rápida entrega y retroalimentación del usuario.
3. Desarrollo de sitios web: La metodología RAD puede ser utilizada en proyectos de desarrollo de sitios web donde se requiere una entrega rápida y frecuentes cambios basados en la retroalimentación del usuario.
4. Desarrollo de software para juegos: La metodología RAD puede ser utilizada en proyectos de desarrollo de software para juegos donde se requiere una entrega rápida y frecuentes iteraciones para mejorar la experiencia del usuario.
5. Desarrollo de sistemas de gestión de bases de datos: La metodología RAD puede ser utilizada en proyectos de desarrollo de sistemas de gestión de bases de datos donde se requiere una entrega rápida y una mayor flexibilidad para realizar cambios basados en los requisitos del usuario.

---

---

## METODOLOGÍA LEAN SOFTWARE DEVELOPMENT

- Es el método menos divulgado
- Se basa en 7 principios
- Por ser una metodología ágil su estructura de fases no es tan rígida como una tradicional.
- Es iterativo
- Se basa en la planeación a largo plazo

### **FASES**

1. Planificación: En esta fase, se identifican las necesidades del cliente y se establecen los objetivos del proyecto. Se define la visión del producto, se identifican los requisitos y se crea un plan de desarrollo para cumplir con estos objetivos.
2. Análisis y diseño: En esta fase, se detallan los requisitos del proyecto y se crea una solución de diseño para cumplir con estos requisitos. Los diseños pueden ser prototipos de baja fidelidad para probar la solución.
3. Desarrollo e implementación: En esta fase, se construyen los componentes del software y se integran en el sistema completo. Se crean pruebas para verificar que la funcionalidad se ajuste a los requisitos.
4. Pruebas y verificación: En esta fase, se prueban y verifican las funcionalidades del software, se ajustan errores, se realiza un control de calidad y se verifica que el software esté listo para ser entregado.
5. Entrega: En esta fase, se entrega el software al cliente y se realiza un seguimiento y soporte posterior a la entrega.

### PRINCIPIOS

1. Eliminar desperdicios: 
se refiere a eliminar todo aquello que no agrega valor al producto final, como tareas que no son necesarias o procesos ineficientes. (eliminar el código que no se está utilizando, evitar reuniones innecesarias y reducir el tiempo de espera entre tareas)
2. Amplificar el aprendizaje: 
A través de pruebas y retroalimentación con el cliente ofrecer oportunidades de capacitación a los miembros del equipo.
3. Decidir lo más tarde posible: 
No tomar decisiones hasta que se tenga todo el conocimiento posible. Así con una mayor información se pueden acertar de manera más precisa las decisiones.
4. Entregar lo más rápido posible: 
se refiere a entregar el software lo más rápido posible sin sacrificar la calidad. Un ejemplo de cómo aplicar este principio sería utilizar entregas iterativas e incrementales para entregar funcionalidades completas y probadas a intervalos regulares.
5. Empoderar al equipo: se refiere a dar al equipo de desarrollo la autoridad y responsabilidad para tomar decisiones y llevar a cabo el trabajo de manera autónoma. Un ejemplo de cómo aplicar este principio sería permitir que los desarrolladores elijan las herramientas y tecnologías que mejor se ajusten a las necesidades del proyecto y fomentar la colaboración y el trabajo en equipo.
6. Crear integridad en el trabajo: 
se refiere a crear un ambiente de trabajo en el que se fomente la honestidad, la transparencia y la responsabilidad individual y colectiva. Un ejemplo de cómo aplicar este principio sería realizar revisiones de código, definir y hacer cumplir estándares de calidad y transparencia en la comunicación entre el equipo y el cliente.
7. Ver el todo: 
se refiere a tener una visión completa del proyecto y considerar cómo todas las partes interactúan entre sí. Un ejemplo de cómo aplicar este principio sería tener una visión clara del producto final y considerar cómo cada pieza del proyecto contribuye a ese objetivo. Además, se debe considerar cómo el proyecto interactúa con otros proyectos y objetivos más amplios de la organización.

****************VENTAJAS****************

- Tiempos de entregas rápidos.
- Feedback y participación del cliente.
- Flexibilidad

**********************DESVENTAJAS**********************

- No tiene un líder centralizado que tome decisiones importantes.
- Se depende mucho del equipo
- Al promover el trabajo en equipo se pierde el control sobre la gestión del proyecto
- Puede ser menos efectivo en proyectos grandes y complejos, ya que la gestión del proceso de desarrollo puede ser más difícil en esos casos.

**En resumen, esta metodología se basa en ágil por lo que se enfoca entregas constantes de valor al cliente y la mejora continua gracias a la participación del cliente.
También promueve el trabajo en equipo y la eliminación de acciones innecesarias en el desarrollo que no aporten algo de valor al cliente como tareas innecesarias o  la espera, el transporte, la sobreproducción, entre otros..
Presume una alta calidad de software por la flexibilidad que puede tener en situaciones donde no se tengan completamente definidos requisitos o el análisis del proyecto y la mejora continua en cada iteración.
Ideal para proyectos pequeños a medianos** 

---

---

## METODOLODÍA SCRUM

- Es una metodología que se enfoca en la planificación a corto plazo
- Iterativa incremental
- Las tareas se realizan en periodos de tiempo llamados sprints (que pueden durar de 4 a 6 semanas)
- Existen reuniones diarias para el seguimiento de avances
- sprint backlog es la lista de tareas por realizar dentro del sprint, y el product backlog es la lista de tareas de todo el proyecto
- Los clientes pueden tomar el rol de skateholders, que son las partes interesadas en el resultado del proyecto.
- Se enfoca mas en la gestión de proyectos

****************VENTAJAS****************

- Flexibilidad
- Entregas tempranas. Gracias a la rapidez de los sprints se entrega avances más rapido.
- Mejora continua. Debido a que el equipo se reune periódicamente pueden ajustar y mejorar el proceso
- Mayor colaboración
- Mayor transparencia. Permite tener una mayor visibilidad del progreso del proyecto que se realiza.

**********************DESVENTAJAS**********************

- Complejidad.  Si no se tiene la experiencia necesaria, es dificil de implementar
- Requiere tiempo y recursos. Puede representar una desventaja para equipos pequeños
- Dificultad para estimar el tiempo.  Debido a sus entregas iterativas, puede ser dificil estimar el tiempo que llevara completar el proyecto.
- Dependencia del equipo. La metodología
- Falta de documentación. Se enfoca más en el desarrollo iterativo lo que puede llevar a la falta de documentación de procesos y decisiones

**En resumen, scrum es ideal para proyectos en los que se requiere una mejora continua y una visibilidad del avance del proyecto, esto gracias a sus reuniones diarias, así como al iniciar y terminar cada sprint en donde se analiza que se ha logrado y que se puede mejorar.
Los sprints tienen duraciones aproximadas de 4 a 6 semanas lo que permite tener una entrega rápida de avances y una retroalimentación seguida que ayudará a mejorar el producto o corregir errores de manera iterativa lo que permite que tenga una flexibilidad alta.**

---

---

## METODOLOGÍA XP (EXTREME PROGRAMMING)

- Se enfoca en la calidad de software y de código
- Los programadores trabajan en parejas
- Iteraciones mas cortas (1 a 3 semanas)
- Comparten roles con scrum
- Planificación abierta con cronograma de actividades flexible

![Untitled](Metodologi%CC%81as%20de%20desarrollo%200a5d62362db240b9a39826ff2c4086cb/Untitled%201.png)

****************VENTAJAS****************

- Flexibilidad
- Entregas tempranas. Gracias a la rapidez de los sprints se entrega avances más rápido.
- Ciclos de desarrollo cortos
- Se enfoca en diseño simple
- Mejora continua

**********************DESVENTAJAS**********************

- Complejidad.  Si no se tiene la experiencia necesaria, es dificil de implementar
- Menor documentación

En resumen esta metodología se enfoca en tiempos de desarrollos más cortos, teniendo una flexibilidad de cambios alta, teniendo practicas como la programación en parejas  y la integración continua en entornos de prueba que permite detectar riesgos o errores de manera más rápida.
Se enfoca también en la calidad alta de código lo que da como resultado software de mayor calidad.
Tambien se enfoca en la mejora continua y en el cliente. Sus entregas constantes es gracias a que se trata de mantener un diseño simple, elegante y funcional para evitar tareas innecesarias o una complejidad alta de código.

---

---

## METODOLOGÍA DE PROTOTIPOS

- Se basa en el desarrollo de prototipos, de baja fidelidad, alta fidelidad o de papel
- Se crea un prototipo inicial que se evalua
- Utilizan el puesto UX/UI

### Fases

1. Requisitos: en esta fase, se identifican los requisitos y objetivos del sistema o aplicación que se va a desarrollar.
2. Diseño: en esta fase, se crea un diseño conceptual del sistema y se establecen las especificaciones técnicas necesarias para crear el prototipo.
3. Desarrollo del prototipo: en esta fase, se crea el prototipo inicial del sistema o aplicación, que se utilizará para probar y evaluar su funcionalidad y usabilidad.
4. Pruebas y evaluación: en esta fase, se realizan pruebas y evaluaciones del prototipo para identificar problemas y oportunidades de mejora.

****************VENTAJAS****************

- Flexibilidad.
- Retroalimentación temprana.
- Estimación más precisa de los tiempos. Esto ya que al entregar un primer prototipo se logra identificar mejor los requisitos.
- Reducción de costos. De la misma manera este modelo permite identificar riesgos de manera temprana.
- Mayor interacción con el cliente desde el inicio.

**********************DESVENTAJAS**********************

- Aumento de costos en la fase de desarrollo del prototipo: el desarrollo del prototipo puede requerir tiempo y recursos adicionales que pueden aumentar los costos del proyecto.
- Posible dificultad para obtener retroalimentación del usuario o cliente: algunos usuarios o clientes pueden tener dificultades para proporcionar retroalimentación útil sobre el prototipo, lo que puede limitar su utilidad.
- Peligro de crear un prototipo demasiado completo: si se dedica demasiado tiempo y recursos a desarrollar el prototipo, puede convertirse en una versión completa del sistema o aplicación, lo que aumentaría los costos y el tiempo de desarrollo.
- Posible falta de compromiso del equipo de desarrollo: si el equipo de desarrollo no está comprometido con la metodología de desarrollo de prototipos, es posible que no se logren los beneficios esperados.

**En resumen esta metodología se enfoca más en desarrollar de manera temprana un prototipo de alta fidelidad (que se asemeje al producto final) o baja fidelidad (incluso en papel) con el cual se puedan identificar riesgos y requisitos con la ayuda de la retroalimentación temprana del cliente, esto puede hacer que se minimicen el uso de recursos y estimar de manera más precisa la finalización del proyecto. Sin embargo se debe tener un compromiso de ambas partes para que el proyecto pueda fluir de mejor manera.
Tambien es útil donde la creatividad sea parte importante, donde la experiencia del usuario y la usabilidad sea importante, y tambien donde pueda haber incertidumbre con los requisitos del cliente.**