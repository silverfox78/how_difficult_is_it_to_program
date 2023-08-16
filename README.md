# ¿Qué tan difícil es programar?

Muchas veces escuchamos frases que refieren a la complejidad de programar. Aunque la codificación puede ser desafiante, enfocarse solo en esta área sería caer en el **“Efecto del Martillo”**. 
El desafío más grande al programar no es simplemente escribir código, sino asegurarse de que el producto resultante sea **Mantenible a largo plazo**.

## Aspectos clave en la mantenibilidad

### Mercado y Negocio
Antes que nada, un producto de software responde a una necesidad del mercado. Debemos preguntarnos sobre las expectativas del usuario, cómo se posiciona la competencia y qué factores económicos pueden influir en su mantenibilidad.

### Legalidad y Normativas
No debemos asumir que todos los aspectos legales están considerados desde la creación del producto. Las regulaciones cambian, y es crucial asegurarnos de que nuestro software se mantenga al día con estas actualizaciones.

### Cultura y Equipo
La forma en que trabajamos, nuestra cultura organizativa y la mentalidad de nuestro equipo juegan un papel crucial en cómo abordamos la mantenibilidad.


### Riesgos
Hay que estar preparados para imprevistos y desafíos. No todos los riesgos necesitan la misma preparación, pero es esencial tener una estrategia clara.

### Tecnología
Más allá del lenguaje de programación, es fundamental considerar cómo gestionamos dependencias, la integración con otros sistemas, la seguridad y la escalabilidad.



## Desafíos en contextos más amplios
Los productos de software rara vez operan en aislamiento. Es probable que convivan con otros sistemas y aplicaciones. 

La mantenibilidad no es solo sobre el producto individual, sino sobre cómo encaja en un ecosistema más amplio, especialmente si este ecosistema ya está establecido o está en proceso de migración.

### Otros factores a tener en cuenta
- Globalización del producto.
- Soporte y operación durante incidentes.
- Consideraciones éticas y sociales.
- Dirección estratégica y visión organizacional.
- Bienestar del equipo.
- Calidad del código.

---

Programar no es simplemente escribir código. Es diseñar soluciones que se mantendrán relevantes, útiles y funcionales en el futuro. Considerar la mantenibilidad desde una perspectiva amplia es esencial para lograr este objetivo.


-----

> REVISAR para otro articulo...

En más de una ocasión, posiblemente hemos escuchado alguna frase que alude a lo complejo que puede resultar codificar algo. Es claro que este proceso conlleva varias facetas que hacen que esta labor sea compleja.

En algunas ocasiones, simplemente entender un requisito ya es un desafío, o cumplir con los plazos impuestos para completar el desarrollo. Trabajar en equipo puede resultar complejo, al igual que mantener la tecnología al día, balancear la calidad versus la velocidad, y abordar temas como la seguridad. Y finalmente, aspectos como las pruebas, la deuda técnica, la documentación o el proceso de optimización son factores fundamentales en el desarrollo, pero son puntos que añaden complejidad a la labor de programar.

Pero nos volvemos a preguntar: el acto de programar por sí mismo, ¿es difícil o complejo? Si bien requiere cierto grado de habilidad y tiene sus propias complejidades, el programar, me atrevería a decir, no es la parte compleja de un desarrollo en sí. Hacer que ese código resulte **mantenible**, eso ya es otro tema, y creo que gran parte de la complejidad que envuelve al arte de la programación recae en este punto.

Es claro que en la medida en que un desarrollador gana experiencia, o en función de con cuántas piedras haya tropezado, su camino se vuelve más llano. Pero posiblemente no sea simplemente porque conozca mejor el lenguaje o use cierto editor de texto. Lo más seguro es que lo que en un punto encontró complejo ahora lo hace de manera más natural, y es porque adquirió ciertos hábitos o se guía por ciertos principios a la hora de codificar.

A continuación, listaré algunos **principios** o **'guías espirituales'** que hacen que el acto de codificar y todo lo que conlleva sea más simple.

---

## Worse is Better

> referencia: https://en.wikipedia.org/wiki/Worse_is_better

Traducido como **“Peor es Mejor”** y también conocido como “Estilo Nueva Jersey”, este principio nos enseña que no siempre debemos buscar la perfección en el diseño o la ejecución.

A veces, una voz en nuestro interior nos dice: “Esto puede ser mejor” o incluso “Esto debe ser mejor”. Pero, ¿debemos siempre escuchar esa voz? Al hacerlo, podemos caer en un antipatrón llamado **“Gold plating” o “Patinador de oro”**, que ocurre cuando el esfuerzo dedicado a una tarea excede lo justificable, generando una distorsión en la planificación y estimación del proyecto.

“Peor es Mejor” nos ofrece una perspectiva contraria, argumentando que un diseño simple, aunque imperfecto, a menudo es preferible a un diseño complejo y perfecto. La idea es enfocarnos en aspectos puntuales como:
- La simplicidad de la tarea a realizar.
- La corrección, es decir, que lo que hagamos debe ser correcto.
- La consistencia, que la tarea sea acorde con la simplicidad y las casuísticas que aborda o existen.
- La completitud, es decir, que la tarea abarque todos sus aspectos dentro de la simplicidad con la que se abordó.

En otras palabras, no debemos tender a buscar de manera prioritaria un resultado final perfecto. En su lugar, debemos apuntar a resolver temas puntuales de manera simple y concreta. Es como el dicho “Lo perfecto es enemigo de lo bueno”, y es muy similar al espíritu detrás de un MVP, para que se hagan una idea.

---

## YAGNI / You aren't gonna need it

> referencia: https://en.wikipedia.org/wiki/You_aren%27t_gonna_need_it

Traducido como "No lo vas a necesitar", el principio YAGNI nos invita a evitar agregar funcionalidades hasta que estas sean realmente necesarias. Su filosofía se centra en mantener el sistema simple y enfocado en las necesidades actuales, en lugar de sobrecargarlo con características futuras que podrían no ser utilizadas.

A menudo, un desarrollador puede sentir la necesidad de incluir algo adicional para cubrir un caso hipotético. Puede ser algo que se sabe que podría suceder o incluso que ocurrirá con certeza en el futuro. Sin embargo, el espíritu de este principio es respetar el alcance y el tiempo de la tarea actual, omitiendo esas necesidades futuras aunque no parezca intuitivo hacerlo.

La ventaja de adherirse a este principio es que se obtienen códigos más atómicos y legibles. Esto repercute directamente en la mantenibilidad del sistema, ya que cada parte está diseñada con un propósito claro y definido. 

YAGNI nos enseña a ser cautelosos y acotados en nuestro desarrollo, centrando nuestras energías en lo que es verdaderamente esencial en el momento presente.

---

## Pendientes

- Separation of Concerns (Separación de Responsabilidades)
- Keep it simple, stupid (KISS) (Mantenlo Simple, Estúpido)
- Keep it DRY (DRY) (Manténlo No Repetitivo)
- Avoid premature (Evita lo Prematuro)
- Arrange, Act, Assert (Organizar, Actuar, Afirmar)
- SOLID - Inversion de control (Inversión de Control)
- Oh FRIC! (Fragility, Rigidity, Immobility, Complexity) (¡Oh FRIC! Fragilidad, Rigidez, Inmovilidad, Complejidad)
- POLA — Principle of Least Astonishment (Principio de Menor Asombro)
- The Boy Scout Rule (La Regla del Boy Scout)
- Follow a Consistent Naming Convention
- Structure Your Code Aesthetically
- Write Good Comments — Take Your Time
