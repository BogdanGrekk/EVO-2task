<h1 align="center">Завдання 2 - Сайт-форма для привітаннь</h1>

## Плюси

- Сайт загорнуто в **Docker**.
- Сайт поставлено на хостинг на безкоштовному сервісі **infinityfree.net**.
- Для сайта використані **Git Hub Actions**.

## Ще трошки про сайт

- Для написання сайту використовувалися HTML/CSS і мова програмування PHP.
- Для збереження стану використаний файл txt.
- Сайт розроблявся  тестувався за допомогою Sublime text, і OpenServer.

### Короткий опис 
- index.html - в файлі за допомогою різних тегів прописана структура сторінки і таблиці
- style.css - в файлі прописані стилі, що задають вигляд сторінці
- input.php - в файлі прописані команди мовою php, що відповідають за введення інформацію у форму і запис її у файл, і виведення привітання.
- input1.php - містить код для виводу читання і виводу інформації з файлу.
- Dockerfile - містить інструкцію для збирання образу. Це простий текстовий файл, у ньому вказуються всі програми, залежності та образи, які потрібні для розгортання образу.
- 000-default.conf - файл віртуального хоста Apache.
- start-apache - містить скрипт для динамічного перевизначення порту Apache, коли запуститься контейнер.
