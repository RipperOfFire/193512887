## Glosario


### ● [Request](https://doc.4d.com/4Dv17/4D/17.1/HTTP-Request.301-4178732.es.html)

Permite enviar peticiones o solicitudes HTTP a cualquier url y procesar la respuesta del servidor HTTP (Response).


### ● [Response](http://www.solocodigoweb.com/blog/2017/06/29/introduccion-al-diseno-de-una-api-http-parte-2-de-4-http-responses/)

Es una respuesta del servidor luego de recibir y procesar un mensaje o una solicitud HTTP del cliente.


### ● [Status Codes](https://developer.mozilla.org/es/docs/Web/HTTP/Status)

Los Status codes de HTTP indican si se ha completado una solicitud o peticion HTTP. Las respuestas se agrupan en cinco clases: respuestas informativas, respuestas satisfactorias, redirecciones, errores de los clientes y errores de los servidores.


### ● [Methods](https://developer.mozilla.org/es/docs/Web/HTTP/Methods)

Indica la acción que se desea realizar para un recurso determinado. Aunque estos también pueden ser sustantivos, estos métodos de solicitud a veces son llamados HTTP verbs.


####   ○ [  GET](https://developer.mozilla.org/es/docs/Web/HTTP/Methods)

Solicitud de un recurso específico. Las peticiones que usan el método GET sólo deben recuperar datos.


####   ○ [  POST](https://developer.mozilla.org/es/docs/Web/HTTP/Methods)

Envia una entidad a un recurso en específico, causando un cambio en el estado o efectos secundarios en el servidor.


####   ○ [  HEAD](https://developer.mozilla.org/es/docs/Web/HTTP/Methods)

Pide una respuesta idéntica a la de una petición GET, pero sin el cuerpo de la respuesta.


####   ○ [  OPTIONS](https://developer.mozilla.org/es/docs/Web/HTTP/Methods)

Es utilizado para describir las opciones de comunicación para el recurso de destino.


####   ○ [  PUT](https://developer.mozilla.org/es/docs/Web/HTTP/Methods)

Reemplaza todas las representaciones actuales del recurso de destino con la carga útil de la petición.


####   ○ [  DELETE](https://developer.mozilla.org/es/docs/Web/HTTP/Methods)

Borra un recurso en específico.


### ● [Header](https://developer.mozilla.org/es/docs/Web/HTTP/Headers)

Permite enviar información adicional junto a una petición o respuesta.


####   ○ [  Accept](https://developer.mozilla.org/es/docs/Web/HTTP/Headers/Accept)
Anuncia que tipo de contenido el cliente puede procesar.

####   ○ [  Accept-Charset](https://developer.mozilla.org/es/docs/Web/HTTP/Headers/Accept-Charset)

Anuncia qué conjunto de caracteres puede entender el cliente.


####   ○ [  Accept-Encoding](https://developer.mozilla.org/es/docs/Web/HTTP/Headers/Accept-Encoding)

Anuncia qué codificación de contenido puede entender el cliente.


####   ○ [  Cache-Control](https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers/Cache-Control)

Se utiliza para especificar directivas para los mecanismos de almacenamiento en caché tanto en las solicitudes como en las respuestas. Las directivas de almacenamiento en caché son unidireccionales, lo que significa que una directiva determinada en una solicitud no implica que la misma directiva deba darse en la respuesta.


####   ○ [  Connection](https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers/Connection)

Controla si la conexión de red permanece abierta o no después de que finalice la transacción actual. Si el valor enviado es keep-alive, la conexión es persistente y no está cerrada, lo que permite que se realicen las solicitudes posteriores al mismo servidor.


####   ○ [  Cookie](https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers/Cookie)

Este header contiene cookies HTTP almacenadas previamente enviadas por el servidor con el header Set-Cookie.


####   ○ [  Set-Cookie](https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers/Set-Cookie)

Se utiliza para enviar cookies desde el servidor al usuario.


####   ○ [  Host](https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers/Host)

Especifica el nombre de dominio del servidor y el número de puerto TCP en el que el servidor está escuchando.


####   ○ [  Origin](https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers/Origin)

Indica de dónde se origina un Fetch. No incluye ninguna información de ruta, solo el nombre del servidor. Se envía con solicitudes CORS, así como con solicitudes POST. Es similar al header "Referer", pero, a diferencia de este encabezado, no revela la ruta completa.


####   ○ [  Referer](https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers/Referer)

Contiene la dirección de la página web anterior desde la cual se siguió un enlace a la página solicitada actualmente. Este header permite a los servidores identificar dónde los visitan las personas y pueden usar esos datos para análisis, registro o almacenamiento en caché optimizado.


####   ○ [  User-Agent](https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers/User-Agent)

Contiene una cadena característica que permite a los interlocutores del protocolo de red identificar el tipo de aplicación, el sistema operativo, el proveedor de software o la versión de software del agente de usuario de software solicitante.


####   ○ [  Content-Encoding](https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers/Content-Encoding)

Se utiliza para comprimir el media-type. Cuando está presente, su valor indica qué codificaciones se aplicaron al entity-body. Le permite al cliente saber cómo decodificar para obtener el media-type al que hace referencia el encabezado Content-Type.


####   ○ [  Content-Length](https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers/Content-Length)

Indica el tamaño del entity-body, en bytes, enviado al destinatario.


####   ○ [  Content-Type](https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers/Content-Type)

Se utiliza para indicar el tipo de medio del recurso. En las respuestas(Response) le dice al cliente cuál es el tipo de contenido devuelto.


####   ○ [  Location](https://developer.mozilla.org/en-US/docs/Web/HTTP/Headers/Location)

Indica la URL a la que se redirige una página. Esta tiene significado cuando se proporciona con una respuesta de estado 3xx (redirección) o 201 (creada).


####   ○ [  Upgrade](https://es.wikipedia.org/wiki/Cabecera_HTTP/1.1_Upgrade)

Se utiliza para indicar una preferencia o un requisito para cambiar a una versión diferente de HTTP o a otro protocolo. la actualizacion(upgrade) de la conexion debe ser solicitada por el cliente, si el servidor quiere imponer un upgrade puede enviar una respuesta "426 upgrade required". El cliente puede entonces enviar una nueva solicitud con las cabeceras upgrade apropiadas.
