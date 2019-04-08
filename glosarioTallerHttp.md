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

##Tablas

###[http://www.inf.ucv.cl/~ifigueroa](http://www.inf.ucv.cl/~ifigueroa "inf.ucv.cl")
| REQ/ RES | Método HTTP (solo REQ) |                                                        URL                                                       |                                                                  Headers (solo nombres)                                                                  | Status  (solo RES |                                 Descripción                                 |
|:--------:|:----------------------:|:----------------------------------------------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------------------------------------------------------------------------:|:-----------------:|:---------------------------------------------------------------------------:|
|    REQ   |           GET          |                                         http://www.inf.ucv.cl/~ifigueroa                                         |                                    Upgrade-Insecure-Requests User-Agent Accept Accept-Encoding Accept-Language Cookie                                    |        n/a        |                      Petición para ingresar al servidor.                     |
|    RES   |           n/a          |                                                        n/a                                                       |                                           Redirect Date Server Location Content-Length Connection Content-Type                                           |        301        | Redirecciona a otra URL y corta la conexión con la que se trata de acceder. |
|    REQ   |           GET          |                                         http://zeus.inf.ucv.cl/~ifigueroa                                        |                                    Upgrade-Insecure-Requests User-Agent Accept Accept-Encoding Accept-Language Cookie                                    |        n/a        |             Pide acceso a la URL de la redirección del servidor.            |
|    RES   |           n/a          |                                                        n/a                                                       |                                      Redirect Date Server Location Vary Content-Encoding Content-Length Content-Type                                     |        301        |                      Vuelve a redireccionar  a otra URL.                     |
|    REQ   |           GET          |                                        http://zeus.inf.ucv.cl/~ifigueroa/                                        |                                    Upgrade-Insecure-Requests User-Agent Accept Accept-Encoding Accept-Language Cookie                                    |        n/a        |                           Pide conexión a la URL.                           |
|    RES   |           n/a          |                                                        n/a                                                       |                    Redirect Date Server X-Powered-By Location Vary Content-Encoding Content-Length Keep-Alive Connection Content-Type                    |        302        |                  Manda al cliente temporalmente a otra URL.                 |
|    REQ   |           GET          |                                    http://zeus.inf.ucv.cl/~ifigueroa/doku.php                                    |                                    Upgrade-Insecure-Requests User-Agent Accept Accept-Encoding Accept-Language Cookie                                    |        n/a        |                       Petición de acceso al servidor.                       |
|    RES   |           n/a          |                                                        n/a                                                       | Date Server X-Powered-By Expires Cache-Control Pragma X-UA-Compatible Set-Cookie Vary Content-Encoding Content-Length Keep-Alive Connection Content-Type |        200        |        Se dirige al sitio, se setea la cookie y mantiene la conexión.        |
|    REQ   |           GET          |          http://zeus.inf.ucv.cl/~ifigueroa/lib/tpl/bootstrap3/assets/bootstrap/default/bootstrap.min.css         |                                             User-Agent Accept Referer Accept-Encoding Accept-Language Cookie                                             |        n/a        |                       Se pide un recurso de texto css.                       |
|    RES   |           n/a          |                                                        n/a                                                       |                              Date Server Last-Modified ETag Accept-Ranges Vary Content-Encoding Content-Lenght Content-Type                              |        200        |                       Se envía el recurso de texto css.                      |
|    REQ   |           GET          |       http://zeus.inf.ucv.cl/~ifigueroa/lib/exe/css.php?t=bootstrap3&tseed=44b1422730da0b8e0624124cac9afe4b      |                                             User-Agent Accept Referer Accept-Encoding Accept-Language Cookie                                             |        n/a        |                            Pide un recurso de php.                           |
|    RES   |           n/a          |                                                        n/a                                                       |                    Date Server X-Powered-By Cache-Control Pragma ETag Last-Modified Vary Content-Encoding Content-Lenght Content-Type                    |        200        |                             Envía el recurso php.                            |
|    REQ   |           GET          |         http://zeus.inf.ucv.cl/~ifigueroa/lib/tpl/bootstrap3/assets/font-awesome/css/font-awesome.min.css        |                                             User-Agent Accept Referer Accept-Encoding Accept-Language Cookie                                             |        n/a        |                         Pide un recurso de texto css.                        |
|    RES   |           n/a          |                                                        n/a                                                       |                              Date Server Last-Modified ETag Accept-Ranges Vary Content-Encoding Content-Lenght Content-Type                              |        200        |                        Envía el recurso de texto css.                        |
|    REQ   |           GET          |            http://zeus.inf.ucv.cl/~ifigueroa/lib/exe/jquery.php?tseed=23f888679b4f1dc26eef34902aca964f           |                                             User-Agent Accept Referer Accept-Encoding Accept-Language Cookie                                             |        n/a        |                             Pide un recurso php.                             |
|    RES   |           n/a          |                                                        n/a                                                       |                            Date Server X-Powered-By Cache-Control Pragma ETag Last-Modified Vary Content-Encoding Content-Type                           |        200        |                             Envía el recurso php.                            |
|    REQ   |           GET          |       http://zeus.inf.ucv.cl/~ifigueroa/lib/exe/js.php?t=bootstrap3&tseed=44b1422730da0b8e0624124cac9afe4b       |                                             User-Agent Accept Referer Accept-Encoding Accept-Language Cookie                                             |        n/a        |                             Pide un recurso php.                             |
|    RES   |           n/a          |                                                        n/a                                                       |                    Date Server X-Powered-By Cache-Control Pragma ETag Last-Modified Vary Content-Encoding Content-Length Content-Type                    |        200        |                             Envía el recurso php.                            |
|    REQ   |           GET          |             http://zeus.inf.ucv.cl/~ifigueroa/lib/tpl/bootstrap3/assets/bootstrap/js/bootstrap.min.js            |                                             User-Agent Accept Referer Accept-Encoding Accept-Language Cookie                                             |        n/a        |                       Pide un recurso js (javascript).                       |
|    RES   |           n/a          |                                                        n/a                                                       |                              Date Server Last-Modified ETag Accept-Ranges Vary Content-Encoding Content-Lenght Content-Type                              |        200        |                             Envía el recurso js.                             |
|    REQ   |           GET          |                http://zeus.inf.ucv.cl/~ifigueroa/lib/tpl/bootstrap3/assets/anchorjs/anchor.min.js                |                                             User-Agent Accept Referer Accept-Encoding Accept-Language Cookie                                             |        n/a        |                       Pide un recurso js.                       |
|    RES   |           n/a          |                                                        n/a                                                       |                              Date Server Last-Modified ETag Accept-Ranges Vary Content-Encoding Content-Lenght Content-Type                              |        200        |                             Envía el recurso js.                             |
|    REQ   |           GET          |                       http://zeus.inf.ucv.cl/~ifigueroa/lib/tpl/bootstrap3/images/logo.png                       |                                             User-Agent Accept Referer Accept-Encoding Accept-Language Cookie                                             |        n/a        |                             Pide un recurso png.                             |
|    RES   |           n/a          |                                                        n/a                                                       |                                         Date Server Last-Modified ETag Accept-Ranges Content-Lenght Content-Type                                         |        200        |                             Envía el recurso png.                            |
|    REQ   |           GET          |                 http://zeus.inf.ucv.cl/~ifigueroa/lib/tpl/bootstrap3/images/button-bootstrap3.png                |                                             User-Agent Accept Referer Accept-Encoding Accept-Language Cookie                                             |        n/a        |                             Pide un recurso png.                             |
|    RES   |           n/a          |                                                        n/a                                                       |                                         Date Server Last-Modified ETag Accept-Ranges Content-Lenght Content-Type                                         |        200        |                             Envía el recurso png.                            |
|    REQ   |           GET          |                     http://zeus.inf.ucv.cl/~ifigueroa/lib/tpl/dokuwiki/images/button-php.gif                     |                                             User-Agent Accept Referer Accept-Encoding Accept-Language Cookie                                             |        n/a        |                             Pide un recurso gif.                             |
|    RES   |           n/a          |                                                        n/a                                                       |                                         Date Server Last-Modified ETag Accept-Ranges Content-Lenght Content-Type                                         |        200        |                             Envía el recurso gif.                            |
|    REQ   |           GET          |                    http://zeus.inf.ucv.cl/~ifigueroa/lib/tpl/dokuwiki/images/button-html5.png                    |                                             User-Agent Accept Referer Accept-Encoding Accept-Language Cookie                                             |        n/a        |                             Pide un recurso png .                            |
|    RES   |           n/a          |                                                        n/a                                                       |                                         Date Server Last-Modified ETag Accept-Ranges Content-Lenght Content-Type                                         |        200        |                             Envía el recurso png.                            |
|    REQ   |           GET          |                     http://zeus.inf.ucv.cl/~ifigueroa/lib/tpl/dokuwiki/images/button-css.png                     |                                             User-Agent Accept Referer Accept-Encoding Accept-Language Cookie                                             |        n/a        |                             Pide un recurso png.                             |
|    RES   |           n/a          |                                                        n/a                                                       |                                         Date Server Last-Modified ETag Accept-Ranges Content-Lenght Content-Type                                         |        200        |                             Envía el recurso png.                            |
|    REQ   |           GET          |                      http://zeus.inf.ucv.cl/~ifigueroa/lib/tpl/dokuwiki/images/button-dw.png                     |                                             User-Agent Accept Referer Accept-Encoding Accept-Language Cookie                                             |        n/a        |                             Pide un recurso png.                             |
|    RES   |           n/a          |                                                        n/a                                                       |                                         Date Server Last-Modified ETag Accept-Ranges Content-Lenght Content-Type                                         |        200        |                             Envía el recurso png.                            |
|    REQ   |           GET          |                     http://zeus.inf.ucv.cl/~ifigueroa/lib/exe/indexer.php?id=start&1522071379                    |                                             User-Agent Accept Referer Accept-Encoding Accept-Language Cookie                                             |        n/a        |                             Pide un recurso php.                             |
|    RES   |           n/a          |                                                        n/a                                                       |                          Date Server X-Powered-By Expires Cache-Control Pragma Connection Set-Cookie Content-Lenght Content-Type                         |        200        |                             Envía el recurso php.                            |
|    REQ   |           GET          | http://zeus.inf.ucv.cl/~ifigueroa/lib/tpl/bootstrap3/assets/font-awesome/fonts/fontawesome-webfont.woff2?v=4.7.0 |                                          Origin User-Agent Accept Referer Accept-Encoding Accept-Language Cookie                                         |        n/a        |                  Pide un recurso de fuente (tipo de letra).                  |
|    RES   |           n/a          |                                                        n/a                                                       |                                         Date Server Last-Modified ETag Accept-Ranges Content-Lenght Content-Type                                         |        200        |                          Envía el recurso de fuente.                         |
|    REQ   |           GET          |  http://zeus.inf.ucv.cl/~ifigueroa/lib/tpl/bootstrap3/assets/bootstrap/fonts/glyphicons-halflings-regular.woff2  |                                          Origin User-Agent Accept Referer Accept-Encoding Accept-Language Cookie                                         |        n/a        |                          Pide un recurso de fuente.                          |
|    RES   |           n/a          |                                                        n/a                                                       |                                         Date Server Last-Modified ETag Accept-Ranges Content-Lenght Content-Type                                         |        200        |                          Envía el recurso de fuente.                         |
|    REQ   |           GET          |                      http://zeus.inf.ucv.cl/~ifigueroa/lib/plugins/note/images/important.png                     |                                             User-Agent Accept Referer Accept-Encoding Accept-Language Cookie                                             |        n/a        |                             Pide un recurso png.                             |
|    RES   |           n/a          |                                                        n/a                                                       |                                         Date Server Last-Modified ETag Accept-Ranges Content-Lenght Content-Type                                         |        200        |                             Envía el recurso png.                            |

* El servidor respondió con varias redirecciones al momento de colocar el link(URL) del sitio en el navegador web. Luego, al momento de ingresar, se cargaron recursos de varios tipos que hicieron posible mostrar la página de manera correcta.

###[https://animeflv.net/](https://animeflv.net/ "animeflv.net")
| REQ/ RES | Método HTTP (solo REQ) |                            URL                            |                                                                                            Headers (solo nombres)                                                                                            | Status  (solo RES |                                  Descripción                                 |
|:--------:|:----------------------:|:---------------------------------------------------------:|:------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------:|:-----------------:|:----------------------------------------------------------------------------:|
|    REQ   |           GET          |                    http://animeflv.net/                   |                                                                  Upgrade-Insecure-Requests User-Agent Accept Accept-Encoding Accept-Language                                                                 |        n/a        |                      Petición para ingresar al servidor.                     |
|    RES   |           n/a          |                            n/a                            |                                                            Redirect Date Transfer-Encoding Connection Cache-Control Expires Location Server CF-RAY                                                           |        301        | Redirecciona a la URL y mantiene la conexión con la que se trata de acceder. |
|    REQ   |           GET          |                   https://animeflv.net/                   |                                                                  Upgrade-Insecure-Requests User-Agent Accept Accept-Encoding Accept-Language                                                                 |        n/a        |             Pide acceso a la URL de la redirección del servidor.             |
|    RES   |           n/a          |                            n/a                            |            Status Date Content-Type Set-Cookie Set-Cookie Set-Cookie Expires Cache-Control Pragma Vary X-Powered-By ms-author-via x-turbo-charged-by expect-ct Server cf-ray Vary content-encoding           |        200        |                   Se dirige al sitio y se setea la cookie.                   |
|    REQ   |           GET          |    https://animeflv.net/uploads/animes/covers/2702.jpg    |                                                                       User-Agent Accept Referer Accept-Encoding Accept-Language Cookie                                                                       |        n/a        |                             Pide un recurso jpg.                             |
|    RES   |           n/a          |                            n/a                            |           status date content-type content-length cache-control expires etag last-modified x-powered-by ms-author-via x-turbo-charged-by cf-cache-status vary accept-ranges expect-ct serve cf-ray           |        200        |                             Envía un recurso jpg.                            |
|    REQ   |           GET          | https://animeflv.net/assets/animeflv/css/font-awesome.css |                                                                       User-Agent Accept Referer Accept-Encoding Accept-Language Cookie                                                                       |        n/a        |                         Pide un recurso de texto css.                        |
|    RES   |           n/a          |                            n/a                            |                 status date content-type cache-control expires etag last-modified vary x-powered-by ms-author-via x-turbo-charged-by cf-cache-status expect-ct server cf-ray content-encoding                |        200        |                        Envía el recurso de texto css.                        |
|    REQ   |           GET          |   https://animeflv.net/assets/animeflv/css/css.css?v=1.4  |                                                                       User-Agent Accept Referer Accept-Encoding Accept-Language Cookie                                                                       |        n/a        |                         Pide un recurso de texto css.                        |
|    RES   |           n/a          |                            n/a                            |                 status date content-type cache-control expires etag last-modified vary x-powered-by ms-author-via x-turbo-charged-by cf-cache-status expect-ct server cf-ray content-encoding                |        200        |                        Envía el recurso de texto css.                        |
|    REQ   |           GET          |   https://animeflv.net/assets/animeflv/css/bootstrap.css  |                                                                       User-Agent Accept Referer Accept-Encoding Accept-Language Cookie                                                                       |        n/a        |                         Pide un recurso de texto css.                        |
|    RES   |           n/a          |                            n/a                            |                 status date content-type cache-control expires etag last-modified vary x-powered-by ms-author-via x-turbo-charged-by cf-cache-status expect-ct server cf-ray content-encoding                |        200        |                        Envía el recurso de texto css.                        |
|    REQ   |           GET          |    https://animeflv.net/assets/animeflv/js/modernizr.js   |                                                                       User-Agent Accept Referer Accept-Encoding Accept-Language Cookie                                                                       |        n/a        |                              Pide un recurso js.                             |
|    RES   |           n/a          |                            n/a                            |                 status date content-type cache-control expires etag last-modified vary x-powered-by ms-author-via x-turbo-charged-by cf-cache-status expect-ct server cf-ray content-encoding                |        200        |                             Envía el recurso js.                             |
|    REQ   |           GET          |     https://animeflv.net/assets/animeflv/img/logo.png     |                                                                       User-Agent Accept Referer Accept-Encoding Accept-Language Cookie                                                                       |        n/a        |                             Pide un recurso png.                             |
|    RES   |           n/a          |                            n/a                            |           status date content-type content-length cache-control expires etag last-modified x-powered-by ms-author-via x-turbo-charged-by cf-cache-status vary accept-ranges expect-ct server cf-ray          |        200        |                             Envía el recurso png.                            |
|    REQ   |           GET          |      https://animeflv.net/uploads/animes/covers/7.jpg     |                                                                       User-Agent Accept Referer Accept-Encoding Accept-Language Cookie                                                                       |        n/a        |                             Pide un recurso jpg.                             |
|    RES   |           n/a          |                            n/a                            | status date content-type content-length cache-control cf-bgj cf-polished etag expires last-modified ms-author-via x-powered-by x-turbo-charged-by cf-cache-status vary accept-ranges expect-ct server cf-ray |        200        |                             Envía el recurso jpg.                            |
|    REQ   |           GET          |    https://animeflv.net/uploads/animes/covers/2096.jpg    |                                                                       User-Agent Accept Referer Accept-Encoding Accept-Language Cookie                                                                       |        n/a        |                             Pide un recurso jpg.                             |
|    RES   |           n/a          |                            n/a                            |           status date content-type content-length cache-control expires etag last-modified x-powered-by ms-author-via x-turbo-charged-by cf-cache-status vary accept-ranges expect-ct server cf-ray          |        200        |                             Envía el recurso jpg.                            |

* El servidor respondió inmediatamente al momento de colocar el link(URL) del sitio en el navegador web y al ingresar, se cargaron distintos recursos de diferentes tipos con los cuales la página pudo cargar correctamente.
