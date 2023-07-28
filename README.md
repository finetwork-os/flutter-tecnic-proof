<img src="https://play-lh.googleusercontent.com/Xhg5bvT9EGsjTzb8vEuEii2l_0ZTgxv8k2RXysXIozRNozUtHyHu66fq5blDsBxmC8yY" width="200" height="200" />

# Finetwork - Flutter - Prueba técnica

La prueba consiste en crear una pequeña app en Flutter que ataque la API pública de Finetwork y publicarla como pública en un perfil de GitHub que se utilizará para valorar la prueba.

La api a tilizar sera la siguiente:

    https://gateway.finetwork.com/product/offering/products?page=1&size=20

Lo primero que habrá que hacer para empezar es crear un proyecto nuevo de Flutter y hacer el commit inicial al repositorio de GitHub sin hacer ninguna modificación en el código. Una vez hecho esto se podrá empezar a desarrollar.

La app tendrá mínimo 2 pantallas.

Pantalla principal:

- Listado de productos.
- por defecto que el paginado sea de 20 productos.
- Cada producto se mostrará con un estilo distinto por el campo **typo** ( que puede ser una img, o simplemente el texto del typo) y el nombre de producto del campo **displayName**.
- Al hacer clic en el producto navegaremos a la pantalla de detalle.
- La pantalla tendrá una AppBar con el nombre de la app como título.
- Funcionalidad extra no obligatoria: Cuando lleguemos al final de la lista se tendrá que hacer una petición para cargar 20 series más (Infinite scroll), o que se pinten todos los products en un skeleton desde la propiedad **totalElements** y que estos carguen según la posición de scroll.

Pantalla de detalle:

- Opcional mostrar información del producto.

Los colores de la app son a libre elección del desarrollador y no se valorarán.

No hay restricciones a la hora de utilizar librerías de terceros.

Los aspectos que se valorarán en el desarrollo son:

- La solución utilizada para el state management de la app.
- La estructura del código.
- Que el código subido a Github tenga como mínimo 2 commits hechos durante el desarrollo.

Además, puede agregar un fichero README con las observaciones que quiera hacernos llegar como puedan ser:

- ¿Cómo decidió las opciones técnicas y arquitectónicas utilizadas como parte de su solución?
- ¿Qué haría de manera diferente si se le asignara más tiempo?

Una vez terminado el proyecto solo hay que enviar el link del repositorio de GitHub.

¡Mucha suerte!
