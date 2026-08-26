# Material de partida — Fragment dinámico con contenedor dedicado

Ejemplo docente de 2019 sobre **Fragments** en Android.

El objetivo es crear un `Fragment` por programación e insertarlo dinámicamente en un contenedor dedicado de la Activity, permitiendo comparar este enfoque con la declaración estática en XML y con la inserción directa en un `LinearLayout`.

La reconstrucción utiliza `FragmentContainerView` y añade una interacción mínima común: introducir un mensaje, pulsar **Procesar** y mostrar desde el Fragment el número de caracteres introducidos.

También se evita insertar una segunda instancia del Fragment cuando la Activity se recrea.

No existe una base de datos asociada.
