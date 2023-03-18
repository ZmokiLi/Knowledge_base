# rm

"**rm**" - (англ. *remove* - "*удалить*") это команда в командной строке, которая используется для удаления файлов или директорий в UNIX-подобных операционных системах, таких как Linux и macOS.


### [Синтаксис команды](../glossary.md#cинтаксис-консольных-команд):
    `rm [опции] файл/директория`

### Опции:
* "**-f**" (force) - `удаление файлов без запроса подтверждения`.
* "**-i**" (interactive) - `запрос на подтверждение перед удалением каждого файла`.
* "**-r**" (recursive) - `удаление директории и её содержимого рекурсивно`.
* "**-v**" (verbose) - `вывод подробной информации о процессе удаления файлов`.
* "**--preserve-root**" - `предотвращение удаления корневой директории системы`.
* "**--no-preserve-root**" - `позволяет удалить корневую директорию системы, если выполнить команду от имени суперпользователя (root)`.
* "**--one-file-system**" - `предотвращает рекурсивное удаление файлов, находящихся в разных файловых системах`.
* "**--help**" - `вывод информации о команде "rm" и доступных опциях`.
* "**--version**" - `вывод информации о версии команды "rm".`

### Аргументы:
* `имена файлов или директорий, которые нужно удалить`.

***

#### Примеры использования:
1. Удаление файлов без запроса подтверждения:
    `rm -f example.txt`
    > Эта команда удалит файл "example.txt" без запроса подтверждения. Если файл не существует, то будет выведено сообщение об ошибке.
2. Запрос на подтверждение перед удалением каждого файла:
    `rm -i example.txt`
    > Эта команда удалит файл "example.txt" и запросит подтверждение перед удалением каждого файла. Если вы хотите удалить несколько файлов, команда будет запросить подтверждение перед каждым файлом.
3. Удаление директории и её содержимого рекурсивно:
    `rm -r my_directory`
    > Эта команда удалит директорию "my_directory" и все файлы и поддиректории, которые она содержит.
4. Вывод подробной информации о процессе удаления файлов:
    `rm -v example.txt`
    > Эта команда удалит файл "example.txt" и выведет сообщение о каждом файле, который был удален.
5. Предотвращение удаления корневой директории системы:
    `rm --preserve-root /example.txt`
    > Эта команда попытается удалить файл "/example.txt", но если файл является частью корневой директории, то команда не выполнится и будет выведено сообщение об ошибке.
6. Позволяет удалить корневую директорию системы, если выполнить команду от имени суперпользователя (root):
    `sudo rm --no-preserve-root /`
    > Эта команда **удалит всю файловую систему**, так как опция "--no-preserve-root" позволяет удалить корневую директорию системы. Однако, выполнение команды требует прав администратора, поэтому мы используем команду "sudo", чтобы запустить ее от имени суперпользователя.
7. Предотвращает рекурсивное удаление файлов, находящихся в разных файловых системах:
    `rm --one-file-system /my_directory`
    > Эта команда **удалит все файлы и поддиректории в "my_directory"**, но она не будет удалать файлы, находящиеся в других файловых системах.

***

Команда rm позволяет удалить один или несколько файлов или директорий. Если файлы находятся в директории, то они удаляются вместе с директорией. Если вы хотите удалить директорию со всем её содержимым, вы должны использовать опцию -r (рекурсивное удаление).

Важно быть осторожным при использовании команды rm, так как **удаленные файлы и директории не могут быть восстановлены из корзины**. Поэтому перед использованием этой команды важно дважды проверить, что вы удаляете правильные файлы и директории.