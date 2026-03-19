# Del software al prototipo físico: el camino de Ventana Celeste para el MIM

En **Ventana Celeste** definimos una ruta clara para construir nuestro prototipo: comenzar por el sistema base en celular y, desde ahí, diseñar toda la parte física para que esa experiencia funcionara de forma estable en terreno.

Nuestro objetivo fue llevar al **Museo Interactivo Mirador (MIM)** una versión funcional que representara la interacción real de uso astronómico, cumpliendo los criterios solicitados para su exhibición.

## ¿Cómo fue nuestro proceso de desarrollo?

Primero implementamos el sistema base de software en celular. Con esa base lista, ajustamos la aplicación para que funcionara directamente en el teléfono destinado a ir montado en el prototipo físico.

Después incorporamos una conexión con **Arduino** para controlar el zoom desde la estructura mecánica. Integramos un disco físico que, al girarlo, aplica niveles de zoom definidos por el sistema, logrando una experiencia de **zoom continuo** durante la observación.

## Integración software-hardware

La conexión entre software y hardware fue uno de los avances más importantes de esta etapa. En términos prácticos, conseguimos:

* Ejecutar el sistema astronómico directamente en el celular del prototipo.
* Vincular Arduino con el control de zoom para convertir el giro físico en respuesta digital.
* Mantener una interacción fluida entre manipulación manual y navegación astronómica en pantalla.

Esto nos permitió pasar de una idea conceptual a un sistema interactivo completo.

## Decisiones clave del diseño físico

Para el desarrollo mecánico consideramos especialmente los pesos de los componentes montados (celular, soportes y estructura), porque ese balance determina la estabilidad del uso real.

En base a ello, diseñamos una resistencia al giro que ayudara a mantener el apuntado lo más estable posible durante la interacción. Así, el movimiento no queda ni demasiado suelto ni demasiado rígido, y el usuario puede controlar mejor la observación.

Además, tomamos como referencia una **montura dobsoniana**, replicándola con materiales de bajo presupuesto. Esta elección nos permitió:

* Construir una estructura accesible y replicable.
* Probar una interacción similar a la de un telescopio real.
* Evaluar el comportamiento del prototipo en condiciones de demostración.

## Prototipo presentado para el MIM

El resultado de esta fase es un prototipo pensado específicamente para su presentación en el MIM, considerando los criterios técnicos y de funcionamiento que nos indicaron para mostrarlo en su establecimiento.

Más que una maqueta, es una plataforma de prueba que integra software móvil, control físico y estructura mecánica en un mismo flujo de uso.

## Proyección educativa

A futuro, buscamos desarrollar una versión de acceso más simple para colegios, con fines educativos en astronomía. La meta es conservar la experiencia de interacción del prototipo actual, pero adaptada a contextos escolares y a recursos más limitados.

Seguimos trabajando para permitir la exploración del cielo de forma interactiva, accesible y educativa.
