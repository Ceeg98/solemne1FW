Contexto: El trabajo es sobre un Blog el cual contiene temas o topicos y estos contienen post de diferentes usuarios. Quise agregarle más cosas de las solicitadas para lograr aprender aún más, estas cosas son, por ejemplo: El cambio del navbar si hay una sesion inciada, un contador de post para cada topico, respuestas a un post, un contador de respuestas para un post.

A pesar de esto hubieron errores que no pude solucinar en el periodo acordado pero aun así el trabajo cumplica con los requisitos que se solicitaron. Los errores no corregidos son los siguientes:

- Al no iniciar sesión, aparece encima del header el mensaje de que no se encuentra el array user (la sesion que viene con los datos de la misma) Ya que para mostrar las opciones de "mis post" y "cerrar sesión" lo hice con la condicion if(empty()) a una sesion llamada "user", no logré pensar en otra forma de mostrar esas opciones de sesión. El boton de cerrar sesión hace llamado a la funcion session_destroy() por ende al hacerlo vuelve a aparecer el error. Se soluciona al iniciar sesión con algún usuario.


- La columna que se llama "Post" en el index debería mostrar la cantidad de posts que tiene cada tema, no logré hacer que esto funcionara.

- Para ingresar a ver los post de cada tema debe precionar el nombre del tema, al precionarlo y mostrar los posts, hay una columna que se llama respuestas que al igual que el punto anterior, no logré hacerlo funcionar.

- Al ingresar al post y tratar de agregar un comentario, este se ingresa correctamente a la base de datos, pero no se muestra, no logré hacer que funcionara.

___________________________________________________________________________________________________________


- Al iniciar sesion, en el navbar le aparecera la opcion "Mis post" aquí puede ver los post creados por el id que inició sesión, en esta sección puede ver, editar y eliminar su post.