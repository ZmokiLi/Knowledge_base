# Mетоды запросов

HTTP-протокол определяет несколько методов запросов, которые могут быть использованы для получения или отправки данных между клиентом и сервером. Ниже представлены наиболее распространенные методы HTTP-запросов:

* **GET** - метод GET используется для получения ресурса по указанному URL-адресу. Клиент отправляет GET-запрос на сервер, и сервер отвечает содержимым запрашиваемого ресурса. Этот метод обычно используется для получения HTML-страниц, изображений, видео и других типов файлов.

* **POST** - метод POST используется для отправки данных на сервер для обработки. Клиент отправляет POST-запрос на сервер с данными, которые нужно обработать, и сервер обрабатывает эти данные и отправляет ответ клиенту. Этот метод обычно используется для отправки форм на сервер, а также для выполнения других операций, требующих передачи данных на сервер.

* **PUT** - метод PUT используется для обновления ресурса на сервере. Клиент отправляет PUT-запрос на сервер с новыми данными для замены существующего ресурса на сервере. Этот метод может использоваться для обновления файлов, изображений и других типов данных на сервере.

* **DELETE** - метод DELETE используется для удаления ресурса на сервере. Клиент отправляет DELETE-запрос на сервер с указанием ресурса, который нужно удалить, и сервер удаляет этот ресурс. Этот метод может использоваться для удаления файлов, изображений и других типов данных на сервере.

* **HEAD** - метод HEAD используется для получения метаданных о ресурсе, но не самого ресурса. Клиент отправляет HEAD-запрос на сервер, и сервер отправляет только метаданные о запрашиваемом ресурсе без его фактического содержимого. Этот метод может использоваться для получения информации о размере файла, дате создания или типе содержимого, без загрузки всего ресурса на клиент.

* **OPTIONS** - метод OPTIONS используется для получения списка методов, поддерживаемых сервером для указанного ресурса. Клиент отправляет OPTIONS-запрос на сервер, и сервер отправляет список методов, которые могут быть использованы для взаимодействия с запрашиваемым ресурсом. Этот метод может использоваться для проверки поддержки сервером конкретного метода запроса.

* **PATCH** - метод PATCH используется для частичного обновления ресурса на сервере. Клиент отправляет PATCH-запрос на сервер с измененными данными для замены только определенных частей существующего ресурса на сервере. Этот метод может использоваться, когда необходимо внести изменения только в некоторые части существующего ресурса.

* **CONNECT** - метод CONNECT используется для установки сетевого соединения с удаленным ресурсом. Клиент отправляет CONNECT-запрос на сервер, и сервер устанавливает прозрачное соединение с запрашиваемым ресурсом, которое можно использовать для безопасного обмена данными.

* **TRACE** - метод TRACE используется для получения копии запроса, отправленного на сервер. Клиент отправляет TRACE-запрос на сервер, и сервер отправляет обратно содержимое запроса. Этот метод может использоваться для отладки сетевых проблем и для обнаружения ошибок, связанных с преобразованием запроса на пути к серверу.

Каждый метод запроса HTTP имеет свои особенности и может использоваться в разных сценариях взаимодействия между клиентом и сервером. Важно понимать, как использовать каждый из этих методов в соответствии с требованиями приложения.

### Дополнительные материалы
+ [Методы HTTP запроса MDN](https://developer.mozilla.org/ru/docs/Web/HTTP/Methods) 