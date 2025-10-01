# Bucles

### Descripción

Este proyecto de consola muestra ejemplos de uso de bucles en java:

* while
* do while
* for clasico
* for-each (enhanced for)
* Stream
* Stream for each con lambda
* Stream for each con filtro

Buenas Prácticas

* Usar for each cuando solo necesitas recorrer la colección sin indices
* Usar while o do while si no se sabe cuantas interacciones habrá
* Evitar bucles infinitos asegurándote de actualizar la condición dentro del ciclo
* Preferir streams cuando se necesiten operaciones de filtrado, mapeo o transformaciones en colecciones
* No mezclar demaciada lógica dentro del bucle, extrarla a métodos si es necesario

### Requisitos

* Java 17+ (recomendado)
* IDE como IntelliJ, Eclipse o VS Code

Bucles/\
│── src/\
│ └── Main.java\
│── README.md

{% embed url="https://docs.oracle.com/javase/tutorial/java/nutsandbolts/for.html" %}

{% embed url="https://docs.oracle.com/javase/8/docs/technotes/guides/language/foreach.html" %}

{% embed url="https://www.datacamp.com/es/doc/java/java-while-loop" %}

{% embed url="https://docs.oracle.com/javase/8/docs/api/java/util/stream/Stream.html" %}
