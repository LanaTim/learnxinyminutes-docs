---
language: html
filename: learnhtml.html
contributors:
    - ["Christophe THOMAS", "https://github.com/WinChris"]
translators:
    - ["Lana Tim", "https://github.com/LanaTim"]
---

HTML расшифровывается как Hypertext Markup Language(гипертекстовый язык разметки).
Это язык используют для написания страниц для World Wide Web(всемирной паутины).
Это язык разметки позволяет писать веб-страниц с помощью кода, чтобы определять, 
как должны быть отображены текст и данные.
На самом деле, HTML файлы представляют собой простые текстовые файлы.
Что такое разметка? Это способ организации данных страницы,
путем открытия и закрытия тегов(помещая данные внутрь этих тегов).
Эта разметка служит, чтобы придать значение тексту, который он окружает.
Как и в других языках программирования, HTML имеет много версий. Здесь мы будем говорить о HTML5.


**Примечание:** Вы можете тестировать различные теги и элементы по мере продвижения 
через учебник на сайте, как [codepen](http://codepen.io/pen/) для того, чтобы увидеть 
их влияние, понять, как они работают и ознакомиться с языком.
В данной статье рассматривается в основном HTML синтаксис и некоторые полезные советы.

```html
<!-- Комментарии заключаются как эта лини\! -->

<!-- #################### Теги #################### -->
   
<!-- Ниже приведен пример HTML-файл, который мы будем анализировать. -->

<!doctype html>
	<html>
		<head>
			<title>Мой сайт</title>
		</head>
		<body>
			<h1>Привет, мир!</h1>
			<a href = "http://codepen.io/anon/pen/xwjLbZ">
				Переходите сюда, чтоб посмотреть как это выглядит.
			</a>
			<p>Это параграф.</p>
			<p>Это другой параграф.</p>
			<ul>
				<li>Это элемент не нумерованного списка (маркированный список)</li>
				<li>Это другой элемент</li>
				<li>Это последний элемент в списке</li>
			</ul>
		</body>
	</html>

<!-- HTML-файл всегда начинается с указанием браузеру, что страница это HTML. -->
<!doctype html>

<!-- После этого, страница начинается с <html> тега. -->
<html>

<!-- страница будет закрыта в конце с помощью тега </html>. -->
</html>

<!-- Ничто не должно появиться после этого заключительного тега. -->

<!-- Внутри (между открывающим и закрывающим тегами <html> </ html>), мы находим: -->

<!-- Заголовок определяется <head> (it он должен быть закрыт </head>). -->
<!-- Заголовок содержит описание и дополнительную информацию, которая не отображается; это метаданные. -->

<head>
	<title>My Site</title><!-- The tag <title> indicates to the browser the title to show in browser window's title bar and tab name. -->
</head>

<!-- After the <head> section, we find the tag - <body> -->
<!-- Until this point, nothing described will show up in the browser window. -->
<!-- We must fill the body with the content to be displayed. -->

<body>
	<h1>Hello, world!</h1> <!-- The h1 tag creates a title. -->
	<!-- There are also subtitles to <h1> from the most important (h2) to the most precise (h6). -->
	<a href = "http://codepen.io/anon/pen/xwjLbZ">Come look at what this shows</a> <!-- a hyperlink to the url given by the attribute href="" -->
	<p>This is a paragraph.</p> <!-- The tag <p> lets us include text in the html page. -->
	<p>This is another paragraph.</p>
	<ul> <!-- The tag <ul> creates a bullet list. -->
	<!-- To have a numbered list instead we would use <ol> giving 1. for the first element, 2. for the second, etc. -->
		<li>This is an item in a non-enumerated list (bullet list)</li>
		<li>This is another item</li>
		<li>And this is the last item on the list</li>
	</ul>
</body>

<!-- And that's it, creating an HTML file can be simple. -->

<!-- But it is possible to add many additional types of HTML tags. -->

<!-- To insert an image. -->
<img src="http://i.imgur.com/XWG0O.gif"/> <!-- The source of the image is indicated using the attribute src="" -->
<!-- The source can be an URL or even path to a file on your computer. -->

<!-- It is also possible to create a table. -->

<table> <!-- We open a <table> element. -->
	<tr> <!-- <tr> allows us to create a row. -->
		<th>First Header</th> <!-- <th> allows us to give a title to a table column. -->
		<th>Second Header</th>
	</tr>
	<tr>
		<td>first row, first column</td> <!-- <td> allows us to create a table cell. -->
		<td>first row, second column</td>
	</tr>
	<tr>
		<td>second row, first column</td>
		<td>second row, second column</td>
	</tr>
</table>

```

## Применение

HTML файлы имеют окончание(расширение) `.html`.

## Узнать больше

* [википедиа](https://en.wikipedia.org/wiki/HTML)
* [HTML учебник](https://developer.mozilla.org/en-US/docs/Web/HTML)
* [W3School](http://www.w3schools.com/html/html_intro.asp)
