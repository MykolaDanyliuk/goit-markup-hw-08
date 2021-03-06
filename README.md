![Web Studio Logo](https://github.com/MykolaDanyliuk/goit-markup-hw-08/blob/main/images/webstudio.svg)

![Gif](https://media.giphy.com/media/ZDTbix65Me1YDNLDF3/giphy.gif)

# My first project (Web Studio)

<p>My first student project <a href="https://mykoladanyliuk.github.io/goit-markup-hw-08/"><b>Web Studio</b></a> as part of the <a href= https://goit.ua/?lang=uk><b>Full Stack Developer course GO IT.</b></a>&nbsp;Final homework assignment №8. Used Technologies (HTML, CSS, JAWASCRIPT, SASS, BEM).</p>

![](https://media.giphy.com/media/cUAGuLiEcTBwRfkAQq/giphy.gif)

<!-- ![](https://media.giphy.com/media/SWoSkN6DxTszqIKEqv/giphy.gif) -->

# goit-markup-hw-08 (домашнее задание)

- Создай репозиторий `goit-markup-hw-08`.
- Склонируй созданный репозиторий и скопируй в него файлы предыдущей работы.
- Выполни вёрстку адаптивной версии всех страниц и элементов макета
  [**домашнего задания #8**](<https://www.figma.com/file/oTYBECAN79dXy19hzWObO4/Web-Studio-(Version-2.1)?node-id=1%3A3330>).
- Настрой `GitHub Pages` и добавь ссылку на живую страницу в шапку
  GitHub-репозитория.

## Критерии приёма работы наставником

### Проект

**`«A1»`** Используется методология `BEM`.

**`«A2»`** Ипользуется препроцессор `SASS`.

**`«A3»`** В файлах `index.html` и `portfolio.html` подключен минифицированный
файл стилей `main.min.css` из папки `css`.

**`«A4»`** При просмотре страницы на любом устройстве шириной от `320px`, не появляется горизонтальная полоса прокрутки.

**`«A5»`** Скрипт мобильного меню подключен в HTML отдельным файлом
`mobile-menu.js`.

## Разметка

**`«B1»`** У всех страниц в блоке `<head>` есть метатег `viewport`.

**`«B2»`** Все фоновые и контентные растровые изображения - отзывчивые, и поддерживают экраны с плотностью `x1` и `x2`.

**`«B3»`** Для отзывчивых контентных изображений использован элемент `<img>` с
атрибутом `srcset` и дескриптором `x`.

**`«B3»`** Для отзывчивых фоновых изображений использованы медиа-фукцнии
`min-device-pixel-ratio` и `min-resolution`.

**`«B4»`** Выполнена разметка мобильного меню.

## Оформление

**`«C1»`** При написании стилей использован `Mobile First` подход и
медиа-функция `(min-width: )`.

**`«C2»`** Стили необходимые только в определённом промежутке, закрыты в
медиа-запросы `(min-width: ) and (max-width: )` или только `(max-width: )`.

**`«C3»`** В медиа-запросах отсутствует лишнее дублирование стилей.

**`«C4»`** Вёрстка выполнена относительно трёх точек перелома: 480px, 768px и
1200px.

**`«C5»`** Выполнено оформление мобильного меню.

### План занятия Александра Репеты

## Часть 1 - Меню

[Формула расчёта ширины flex-элемента в сетке](https://gist.github.com/luxplanjay/b2cdf8f124fc2c896789a28b6ba16a87)
.element {
flex-basis: calc((100% - кол-во маржинов в строке \* значение маржина) / кол-во элементов в строке);
}

## Часть 2 - Меню

- Модальное окно на телефоне
- Разметка и стили кнопки-переключателя
- Скрипт
- Рарметка бургер-меню
- Стили бургер-меню
  - Переключение иконки по `.menu-button.is-open`
- Медиа-выражения
- Как определить когда убирать бургер не привязываясь жёстко к макету

- Отзывчивые изображения
  - Проблема базовых изображений и width 100%
  - Стили для отзывчивого изображения (max-width)
  - [Плотность пикселей экрана](https://www.mydevice.io/) и ретинизация
- Отзывчивый элемент `<img>`
  - Имитация плотности пикселей в devtools
  - Атрибут `srcset`
  - Дексриптор `x`
  - Дексриптор `w`
  - Атрибут `sizes`
  - Отзывчивая галерея (порядок медиа-запросов)
- Фоновые изображения по конспекту
  - Пару слов про `image-set()`
- Элемент `<picture>`
  - Различные форматы изображений
  - Кадрирование
    - [](https://www.html5rocks.com/en/tutorials/responsive/picture-element/resized-image@2X.png)
    - [](https://www.html5rocks.com/en/tutorials/responsive/picture-element/art-direction@2X.png)

## Допмат

- [Srcset and sizes](https://ericportis.com/posts/2014/srcset-sizes/)
- [Picture element](https://www.html5rocks.com/en/tutorials/responsive/picture-element/)
- [Можно ли задавать разменрность шрифтам так, чтобы они сами подстраивались размером под нашу адаптивность](https://css-tricks.com/fun-viewport-units/)
