# clase 77 Ejercitacion

1. En el HTML se debe ver en forma de `<ul>` y `<li>`, la lista de usuarios (solo el nombre). No es necesario ningun estilado. 

2. Una vez logrado eso, agregar al lado de cada usuario un boton que diga "borrar". Al hacerse click, debe enviarse el metodo DELETE a la ruta /users/${id} con el id del usuario. 

3. Una vez logrado eso, que la lista de usuarios se actualice luego de borrar. 

4. Luego, crear un formulario con los campos Nombre, Email, Direccion y Telefono. Al enviar ese formulario, se debe enviar el metodo POST a la ruta /users para crear un usuario nuevo. La lista debe actualizarse e incluir al final el usuario recientemente creado. 

OPTATIVO

5. Agregar un boton "Modificar". Al hacerse click se abre un formulario (puede ser un modal, o aparecer al final). El formulario debe estar *pre completado* con los datos del usuario a mofificarse. Al enviarse se hace un PUT a la ruta /users/${id}, y la lista se modifica para incluir al usuario actualizado. 

