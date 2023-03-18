# HTTP-статус-коды

HTTP-статус-коды – это числовые значения, которые возвращаются в ответ на запросы, отправленные клиентами на серверы с протоколом HTTP. Коды состоят из трех цифр и сообщают о статусе выполнения запроса или об ошибке, которая возникла в процессе его выполнения.

Коды статусов делятся на пять классов:

* **1xx** (**Информационные**) – используются для информирования о процессе передачи запроса.

* **2xx** (**Успешные**) – указывают на успешное выполнение запроса.

* **3xx** (**Перенаправление**) – используются для перенаправления клиента на другой ресурс.

* **4xx** (**Ошибки клиента**) – указывают на ошибки, которые произошли на стороне клиента.

* **5xx** (**Ошибки сервера**) – указывают на ошибки, которые произошли на стороне сервера.

****

Некоторые из наиболее распространенных статус-кодов:

* 200 OK – успешный запрос, который возвращает запрошенный ресурс.
* 301 Moved Permanently – ресурс был перемещен на другой URL и запрос должен быть перенаправлен на новый URL.
* 404 Not Found – запрошенный ресурс не найден на сервере.
* 500 Internal Server Error – сервер обнаружил ошибку при выполнении запроса.

**Знание HTTP-статус-кодов очень важно** для разработчиков веб-приложений, так как позволяет быстро выявлять и исправлять ошибки и улучшать работу приложения в целом. Кроме того, статус-коды могут использоваться для определения поведения приложения при различных сценариях взаимодействия с сервером.

### Дополнительные материалы
+ [Коды ответа HTTP запроса MDN](https://developer.mozilla.org/ru/docs/Web/HTTP/Status) 