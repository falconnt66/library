# library
Веб-интерфейс для удаленной работы с базой данных библиотеки написанный на языке программирования PHP и языке разметки HTML

Данный сайт предназначен для ввода и просмотра книг,хранящихся в библиотеке пользователя.

# demo
Протестировать проект можно на сайте http://falconnt.ru/ или по адресу http://31.41.43.12/<br><br>
<center>![alt tag](http://falconnt.ru/demo.png "demo")​</center>

# Установка и настройка library 
1. Зайдите в панель управления хостингом.
2. Создайте в ней новую базу данных (и, возможно, пользователя).
3. Через phpMyAdmin импортируйте базу данных на хостинг из папки BD.
4. Отредактируйте файл connection.php из папки src

      $database = 'name_bd'; //имя базы данных<br>
      $user = 'user'; //имя пользователя<br>
      $password = 'password'; //пароль
      
5. Подключитесь к хостингу по FTP.     
6. Загрузите все файлы из папок src и img в папку www (или public_html) на хостинге.
