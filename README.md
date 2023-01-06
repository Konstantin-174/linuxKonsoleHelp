# БАЗОВЫЕ КОМАНДЫ ДЛЯ ТЕРМИНАЛА
* `./ <имя файла>` - *Запуск любого файла;*
* `cd (cd ..)` - *Смема папки вниз/вверх;*
  * `cd --help` - *Получить список атрибутов к конкретной команде;*
  * `man cd` - *Получить полный мануал по конкретной команде;*
* `ls` - *Показывает список контента в текущей папке;*
  * `ls <путь к папке>` - *Показывает список контента в указанной папке;*
  * `ls -l` - *Показывает список контента с параметрами;*
  * `ls -la` - *Показывает скрытые файлы;*
* `pwd` - *Вывести рабочий каталог (показать в каком каталоге находимся);*
* `cp -v` - *Скопировать файл, **атрибут -v отображает процесс копирования***  
`cp -v text.doc /home/doc/`;
* `mv` - *Команда для перемещения* `mv text.txt /hoom/new/` *и  
переименования* `mv text.txt newText.txt` *файлов;*
* `nano` - *Текстовый редактор терминала;*
* `cat` - *Читает содержимое выбранного файла (показывает содержимое в строке терминала);*
  * `cat text.txt | grep src` - *Команда* `grep src` *отобразит содержимое файла, содержащее в строках слово* `src`*;*
  * `grep -i` - *Атрибут `-i` для игнорирования регистра, т.к. Linux чувствителен к регистру;*
* `less` - *Читает содержимое выбранного файла, но показывает его в отдельном окне;*
* `echo` - *Выводит написанное значение/текст на экран "как эхо";*  
```
kali@kali:/home/# echo Hello World!
Hello World!
```
*Так же записывает строку в файл;*
```
kali@kali:/home/# echo Hello World > test.txt
kali@kali:/home/# cat test.txt
Hello World!
```
* `touch` - *Команда для быстрого создания файла;*
  * `kali@kali:/home/# touch file.txt file.doc` 
* `mkdir` - *Команда создаёт директорию/папку;*
  * `kali@kali:/home/# mkdir Новая папка`  
