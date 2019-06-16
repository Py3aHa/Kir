# Readme file

<h1>Заголовок</h1>

*Файл должен быть простым и коротким*

Оформление:
<br>Заголовок абзаца должен быть подчеркнут “минусом”, также можно использовать <hr>

<br>Пример:
Документация
<br>----------------
<br>Между абзацами должна быть одна пустая строка


Что должно быть:
<li>имена проектов, всех подмодулей и библиотек, а также их краткое описание и пример использования(не более пяти строк)
<li>инструкция как найти документацию
<li>инструкция эксплуатации
<li>краткое описание проекта

Примеры оформления файлов:
<br>
[Пример 1](http://svn.apache.org/repos/asf/httpd/httpd/trunk/README)
<br>Пример 2  <http://svn.apache.org/repos/asf/httpd/httpd/trunk/README>

<br>
<br>
<br>
 
<br>Нужно написать три фигнюльки и на той же строке язык, который используешь
```scss /* или css */

@import "bower_components/tree-normalize/generic.normalize";
h1 {
 font-size:1.5em;
 font-weight: 300;
}
```

```python
# ~/app/__init__.py
from flask import Flask

app = Flask(name)
service = YourService(app) # app is the flask object that is running
service.init_app() # initializing the package/service once the app starts

#...

def create_app(): # this function is being ran in run.py which starts the server

    app = Flask(name)
    service.init_app()
    return app
```


```html
<meta name="viewport" content="width=device-width, initial-scale=1.0">
```

Чтобы сделать блок текста используй '>'
>блок первого уровня
>><br>блок второго уровня
>>><br>блок третьего уровня




**Таблица**

Название файла  | Содержание файла
----------------|----------------------
style.css       | Пустой файл каскадной таблицы стилей, в который производится сбока необходимых стилей
reset.css       | Reset CSS от Эрика Мейера
normalize.css   | Нормалайзер CSS от Nicolas Gallagher
block.css       | Основные стили блоков системы
addition.css    | Дополнительные стили
fontawesome.css | Стили иконочного шрифта
layout.css      | Основные стили, применительно к определённому сайту
lightbox.css    | Стили лайтбокса, если таковой используется
index.html      | Индексный файл для проверки вносимых изменений
