# Creación de una base de datos con Azure Cosmos DB
**Objetivo:** Crear una base de datos no estructurada con el recurso de Azure Cosmos DB de Azure.

![](/imagenes/virtual%20machine.png)

**Requisitos**
- Cuenta de Azure con una suscripción activa
- Equipo de cómputo con sistema operativo: Windows, Linux o MacOs.

**Pasos**  
inicia sesión en Portal.Azure.com  
En la barra de búsqueda escribimos “Azure Cosmos DB” y lo seleccionamos.  
Damos clic en el apartado crear.  
Seleccionamos la opción de núcleo de SQL.  
Damos clic en crear.

En la pestaña datos básicos, llenamos lo siguiente:

**En Detalles del proyecto**  
Suscripción: La suscripción que queramos utilizar.  
Grupo de recursos: Podemos crear uno o seleccionar uno ya existente.  
![Imagen 1](/imagenes/Imagen1.png)

**En Detalles de Instancia**  
Nombre de cuenta: Ponemos el que queramos.  
Ubicación: Podemos escoger cualquiera, pero si no queremos que haya mucha latencia escogemos uno cercano a donde vivimos.  
Lo demás lo dejamos como esta.  
Por último, damos clic en el botón de revisar y crear, y luego en crear.  
![](/imagenes/Imagen2.png)

Cuando se termine de crear nuestro recurso, daremos clic en el botón de ir al recurso.

Seleccionamos la plataforma (Lenguaje de programación) que queremos que use nuestra base de datos.  
Damos clic en crear contenedor Ítems.  
Damos clic en descargar.  
Damos clic en abrir el explorador de datos.  
![](/imagenes/Imagen3.png)

De la lista desplegable seleccionamos la opción de ToDoList.  
Enseguida damos clic en Ítems.  
Seleccionamos la opción de Ítems.  
Agregamos un nuevo ítem.  
Del lado derecho escribiremos el siguiente código que se muestra en la imagen siguiente.  
Damos clic en guardar.  
![](/imagenes/Imagen4.png)

Si queremos hacer una consulta, en el menú de la parte de arriba seleccionamos el icono que diga New SQL Query, por ejemplo, podemos poner este comando para el que hicimos: SELECT * FROM c where c.id="1". Nos dará los datos de nuestra consulta.
![](/imagenes/Imagen5.png)