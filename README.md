APIs del Servidor

GET /educacion: devuelve una lista de todos los objetos Educacion que se han guardado en el servidor.

GET /proyectos: devuelve una lista de todos los objetos Proyecto que se han guardado en el servidor.

GET /: devuelve una cadena de texto que indica que la API se encuentra en /api/.

POST /educacion: guarda un nuevo objeto Educacion en el servidor. El objeto debe ser proporcionado en el cuerpo de la solicitud HTTP.

GET /educacion/{id}: devuelve el objeto Educacion con el ID especificado en la URL.

DELETE /educacion/{id}: borra el objeto Educacion con el ID especificado en la URL.

PUT /educacion/{id}: actualiza el objeto Educacion con el ID especificado en la URL. Los nuevos valores deben ser proporcionados en el cuerpo de la solicitud HTTP.

POST /proyectos: guarda un nuevo objeto Proyecto en el servidor. El objeto debe ser proporcionado en el cuerpo de la solicitud HTTP.

GET /proyectos/{id}: devuelve el objeto Proyecto con el ID especificado en la URL.

DELETE /proyectos/{id}: borra el objeto Proyecto con el ID especificado en la URL.

PUT /proyectos/{id}: actualiza el objeto Proyecto con el ID especificado en la URL. Los nuevos valores deben ser proporcionados en el cuerpo de la solicitud HTTP.

GET /login/{id}: devuelve el objeto Auth con el ID especificado en la URL.
