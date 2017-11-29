# MCS День 4

---

# Ревью пройденного

---

## Основы

- История веба и html-разметки
- Спецификации (договоренности)
- Из чего состоит html-документ
- Базовые тэги

---

## Основы > История

- История появления и развития [HTML](https://vertex-academy.com/tutorials/ru/html_history/)
- О физической части мира [интернета](https://habrahabr.ru/company/it-grad/blog/339616/.com)
- О разнообразии [браузеров](https://ru.wikipedia.org/wiki/%D0%92%D0%BE%D0%B9%D0%BD%D0%B0_%D0%B1%D1%80%D0%B0%D1%83%D0%B7%D0%B5%D1%80%D0%BE%D0%B2)
---

## Основы > Спецификации

- От мирового консорциума [W3C](https://w3c.github.io/html/)
- От рабочей группы [WHATWG](https://html.spec.whatwg.org/multipage/)

---

## Основы > Внутренности документа
- Синтаксис `<имя_тэга атрибут="значение">`
- Структура [страницы](https://html5book.ru/osnovy-html/#part1)
- Элементы без закрывающего [тэга](https://w3c.github.io/html/syntax.html#optional-tags)
- Проверить правильность кода – валидатор [html](https://validator.w3.org/)

---

## Основы > Базовые тэги

- [Справочник](https://webref.ru/html)
- [Группирующие и строчные элементы](https://html5book.ru/block-inline-elements/)
– [Списки](https://html5book.ru/html-lists/)
– [Таблицы](https://html5book.ru/html-table/)
- [Текстовые элементы](https://html5book.ru/html-text/#part2)

---

## Введение в HTML

- Многоязычность документов (Internationalization = i18n)
- Семантическая разметка и Accessibility = a11y
- Ссылки между документами и ресурсами
- Встраиваемое содержимое (аудио, видео, картинки)
- Тэг `<form>` и элементы формы

---

## Введение в HTML > Интернационализация

- `<meta charset="UTF-8">`
- Про стандарт кодирования символов [Юникод](https://ru.wikipedia.org/wiki/%D0%AE%D0%BD%D0%B8%D0%BA%D0%BE%D0%B4)
- Про одну из кодировок, [UTF-8](https://ru.wikipedia.org/wiki/UTF-8)

---

## Введение в HTML > Семантика

- Семантические элементы [HTML5](https://html5book.ru/html5-semantic-elements/)
- Тонкости использования [заголовков](https://webdesign.tutsplus.com/articles/the-truth-about-multiple-h1-tags-in-the-html5-era--webdesign-16824)
- `(*)` Микроразметка: [Microformats](http://microformats.org/wiki/Main_Page) и [Schema.org](https://yandex.ru/support/webmaster/schema-org/intro-schema-org.xml (перевод от яндекса))

---

## Введение в HTML > Ссылки

- Устройство [URL](https://ru.wikipedia.org/wiki/URL)
- Напоминание: `<a href='тут URL'>`
- [HTML–ссылки](https://html5book.ru/hyperlinks-in-html/)
- Anchors and [Links](http://html.com/anchors-links/)

---

## Введение в HTML > Встраиваемые элементы

- [HTML–изображения](https://html5book.ru/images-in-html/)
- [Видео](https://webref.ru/html/video)
- [Аудио](https://webref.ru/html/audio)
- Атрибут `alt` для [изображений](http://prgssr.ru/development/alternativnyj-tekst-dlya-izobrazhenij.html)
- `(*)` Субтитры для [видео](https://www.html5rocks.com/en/tutorials/track/basics/)

---

## Введение в HTML > Форм

- Поле ввода [input](https://webref.ru/html/input)
- О [HTML5–формах](https://html5book.ru/html5-forms/)
- Перечень элементов [форм](https://webref.ru/html/type/form)
- Подробности о элементе [form](https://webref.ru/html/form)
- `(*)` атрибут method [тэга `<form>`](http://htmlbook.ru/html/form/method)

---

## Вопрос на 1 000 000 $

Как сделать кликабельную картинку?

---

## Введение в CSS

 - Анатомия: `селектор, другой селектор { правило1; правило2; правило3;}`
 - Виды слекторов https://flukeout.github.io/
 - Анатомия правила: `css-свойство: значение`
 - `(*)` [Псевдо-классы: динамические и структурные](https://html5book.ru/psevdoklassy/)
 - `(*)` [Псевдо-элементы](https://html5book.ru/css-content/)

---

## Введение в CSS 2

 - Отношения: потомок, сын, брат
 - [Наследование и Специфичность](https://html5book.ru/osnovy-css/#part5)
 - [Единицы измерения](https://learn.javascript.ru/css-units)
 - Способы задать css: `style=`, `<style>`, отдельный файл

---

## Введение в CSS 2 > Отношения

- `div div` потомок
- `div > div` сын (непосредственный потомок)
- `(*)` css4 `div >> div` внуки-правнуки (_не_ непосредственный потомок)
- `div + div` брат (следующий)
- `div ~ div` все (следующие) братья

---

## Верстаем страничку

https://gist.github.com/tyanas/a6121f58fbfde2cd0c93232d7d2bddc3

---?image=https://4.downloader.disk.yandex.ru/preview/8cc7182f83db9daee83176ad2d515cdbf9c5260cf5f2e68770825b25b5e91ff3/inf/UXnuqw7H6qgAe1aEUe5ZmmvRWm0dv4drGZ50CrbABh5mBcFUqbiL1FqhizfJeQ8vPjt14ztmM178wDw8vnJtZQ%3D%3D?uid=0&filename=2017-11-29_16-28-41.png&disposition=inline&hash=&limit=0&content_type=image%2Fpng&tknv=v2&size=XXL&crop=0

---

## Верстаем формочку
https://gist.github.com/tyanas/128f656c8b5efd5c33686bda04076926

---?image=https://html5book.ru/wp-content/uploads/2015/05/html5_form.png

---

## Подробнее о CSS

 - [Шрифт](https://developer.mozilla.org/en-US/docs/Web/CSS/font): размеры, начертания
 - Расстояния: [строки](https://developer.mozilla.org/en-US/docs/Web/CSS/line-height), [буквы](https://developer.mozilla.org/en-US/docs/Web/CSS/letter-spacing), [слова](https://developer.mozilla.org/en-US/docs/Web/CSS/word-spacing)
 - Базовая работа с текстом: [выравнивание](https://developer.mozilla.org/en-US/docs/Web/CSS/text-align), [цвет](https://css-tricks.com/nerds-guide-color-web/)
 - Верстка [колонками](https://habrahabr.ru/company/microsoft/blog/143158/), [переполнение](https://developer.mozilla.org/en-US/docs/Web/CSS/overflow) (`overflow`)
 - Пробелы и переносы

---

## `(*)` Advanced CSS

- о семействах шрифтов
- псевдо-элементы
- `border-image`
- `box-shadow`
