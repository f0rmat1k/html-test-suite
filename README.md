# Тесты для HTML кода
[![Build Status](https://travis-ci.org/urfu-2015/html-test-suite.svg)](https://travis-ci.org/urfu-2015/html-test-suite)

## Использование
1. Положить содержимое папки `task-stub` в корень репозитория с задачей. При необходимости скопировать тесты для
конкретных задач из папки `extra-tests`.
2. Включить репозиторий с заданием в [https://travis-ci.org/](https://travis-ci.org/).

## Проверки
* Наличие 2х и более html-файла в корне проекта;
* Deprecated-теги ('i', 'b', 'font', 'center', 'marquee', 'u', 's');
* Наличие табуляций;
* Кратность кол-ва пробелов в отступе четырем;
* Использование запрещенных атрибутов (`style`, `border`, `align`);
* Лишние пробелы:
  * после открывающих тегов;
  * перед закрывающими тегами, после `<`;
  * Перед и после `=`;
* Строки длиной более 110 символов;
* Две пустыне строки подряд;
* Блочные теги внутри строчных;
* Блочные теги внутри `<p>`;
* Закрыте пустые теги (например, `<meta />`);
* Правильные кавычки у значений атрибутов.