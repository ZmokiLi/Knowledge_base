# tail

"**tail**" (англ. "tail" означает "хвост") - это команда в UNIX-подобных операционных системах, которая позволяет вывести последние строки из файла или потока данных. Вот подробнее о том, как использовать эту команду:

### [Синтаксис команды](../glossary.md#cинтаксис-консольных-команд):
    `tail [опции] [файлы]`

### Опции:
* "**-n N**" - `вывести последние N строк (по умолчанию 10)`.
* "**-f**" - `отслеживать изменения файла и выводить новые строки`.
* "**-c N**" - `вывести последние N байт из файла`.
* "**-q**" - `не выводить заголовок с именем файла`.
* "**-v**" - `выводить заголовок с именем файла для каждого файла`.
* "**--pid=PID**" - `завершать вывод, когда процесс с указанным PID завершится`.
* "**--retry**" - `продолжать попытки открыть файл при ошибке`.
* "**--sleep-interval=S**" - `время задержки между попытками открыть файл (по умолчанию 1 секунда)`.

### Аргументы:
* `файлы - имена файлов для чтения. Если имена файлов не указаны, tail будет читать данные из стандартного ввода`.

***

#### Примеры использования:
1. Вывести последние 10 строк из файла:
    `tail filename.txt`
2. Вывести последние 20 строк из файла:
    `tail -n 20 filename.txt`
3. Отслеживать изменения файла и выводить новые строки:
    `tail -f filename.txt`
4. Вывести последние 100 байт из файла:
    `tail -c 100 filename.txt`
5. Вывести последние 10 строк из нескольких файлов:
    `tail file1.txt file2.txt file3.txt`
6. Вывести последние 5 строк из нескольких файлов и показать заголовок с именем файла для каждого файла:
    `tail -n 5 -v file1.txt file2.txt file3.txt`

***

Команда "tail" может быть полезна для мониторинга лог-файлов, следящих за последними строками вывода, а также для вывода последних строк больших файлов, чтобы не нужно было читать весь файл целиком.
