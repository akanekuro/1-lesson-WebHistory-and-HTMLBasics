# Вводный Урок: История Веба и Основы HTML

История Веба

Тим Бернерс-Ли (Изобретатель Всемирной паутины): Британский ученый, который в 1989 году в ЦЕРНе (Европейская организация по ядерным исследованиям) предложил концепцию гипертекстовой системы, что стало основой для создания Всемирной паутины.

ЦЕРН (Ведущая лаборатория по физике частиц): Европейская организация, занимающаяся исследованиями в области физики высоких энергий. Именно здесь в 1989-1990 годах Тим Бернерс-Ли разработал первый веб-браузер и веб-сервер.

Развитие Веб-технологий: После изобретения веба последовало быстрое развитие технологий. HTML, CSS и JavaScript стали ключевыми инструментами для создания веб-страниц и веб-приложений.

История HTML, CSS и JavaScript
HTML (HyperText Markup Language): Язык разметки, разработанный в начале 90-х годов, который определяет структуру и содержимое веб-страниц.

CSS (Cascading Style Sheets): Стилевой язык, представленный в 1996 году, который используется для оформления внешнего вида HTML-документов.

JavaScript: Язык программирования, впервые представленный в 1995 году Бренданом Эйхом (Американский программист и создатель JavaScript), стал ключевым элементом для добавления интерактивности к веб-страницам.

Основы HTML
Структура HTML-документа:

`<!DOCTYPE html>`: Объявление, указывающее браузеру версию HTML.
`<html>`: Корневой элемент, который обрамляет весь HTML-документ.
`<head>`: Содержит метаинформацию и заголовок страницы.
`<body>`: Основное содержимое веб-страницы.
Основные Элементы HTML:

`<h1>`, `<h2>`, ..., `<h6>`: Заголовки различных уровней.
`<p></p>`: Параграф или абзац текста.
`<a href="...">`: Ссылка на другую веб-страницу.
`<img src="..." alt="...">`: Вставка изображения.
`<ul>, <ol>, <li>`: Списки (ненумерованные и нумерованные).
`<div>`: Разделительный контейнер для группировки и форматирования блоков содержимого. Очень мощный инструмент для структурирования веб-страницы и управления макетом с помощью CSS.

Что такое HTML-теги?

HTML-теги - это основные строительные блоки HTML. Они используются для создания и форматирования веб-страниц.
Теги обозначаются угловыми скобками, например, <tagname>. Каждый тег имеет свое назначение и функцию.
Большинство тегов имеют закрывающие пары, например <p>...</p>, но есть и самозакрывающиеся теги, такие как <img src="..." alt="...">.
Типы Тегов:

Структурные теги: Определяют структуру и разделы веб-страницы, например, <html>, <head>, <body>.
Теги контента: Используются для добавления текста, изображений, ссылок и т.д., например, <p>, <img>, <a>.

Важность Тегов в HTML:
Теги определяют, как браузер должен интерпретировать и отображать содержимое веб-страницы.
Правильное использование тегов обеспечивает лучшую доступность и совместимость с различными устройствами и браузерами.

Блочные и Строчные Теги в HTML


В HTML теги делятся на два основных типа: блочные и строчные. Понимание различий между этими типами тегов важно для правильного построения структуры веб-страницы.
Блочные Теги: Блочные теги создают "блоки" контента, которые автоматически начинаются с новой строки и занимают всю доступную ширину.
Особенности: Занимают всю ширину контейнера, в котором находятся.
Можно управлять шириной и высотой.
Часто используются для создания крупных структурных элементов страницы.
Примеры:
`<div>`: Универсальный контейнер для группировки элементов.
`<p>`: Параграф текста.
`<h1>, <h2>, ..., <h6>`: Заголовки различных уровней.
`<ul>, <ol>`: Ненумерованные и нумерованные списки.
`<li>`: Элемент списка.
`<header>, <footer>, <section>, <article>`: Семантические элементы для структурирования содержимого.
Строчные Теги:

Описание: Строчные теги предназначены для форматирования отдельных частей текста или добавления небольших элементов, не прерывая поток документа.
Особенности:
Не начинаются с новой строки и занимают только столько места, сколько необходимо для содержимого.
Не возможно управлять шириной и высотой.
Используются для мелких элементов, таких как ссылки, выделение текста, изображения.
Примеры:
`<a>`: Ссылка.
`<span>`: Универсальный строчный контейнер.
`<img>`: Изображение.
`<strong>, <em>`: Выделение текста с помощью жирного или курсивного начертания.
`<br>`: Перенос строки.
`<small>`, <big>: Изменение размера текста.
Важность Различия между Блочными и Строчными Тегами
Понимание различий между блочными и строчными тегами помогает создавать более организованные и структурированные веб-страницы. Блочные элементы часто используются для создания основного макета страницы, в то время как строчные элементы применяются для мелкой стилизации и выделения отдельных частей контента.

Эти знания помогут вам правильно размещать и стилизовать элементы на веб-странице, создавая чистую, доступную и эстетически приятную структуру контента.


 пример HTML-разметки с использованием двух блочных элементов <div> и текстом внутри:

<!DOCTYPE html>
<html>
<head>
    <title>Пример страницы с двумя div</title>
</head>
<body>
    <div>
        <p>Это первый блок div. Здесь может быть ваш текст, например, вступление или описание чего-либо.</p>
    </div>

    <div>
        <p>Это второй блок div. Этот блок также содержит текст, который может относиться к другому разделу или теме вашего сайта.</p>
    </div>
</body>
</html>
