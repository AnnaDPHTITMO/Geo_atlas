# Географическая Номенклатура - Интерактивный Атлас

Интерактивный [веб-атлас](https://annadphtitmo.github.io/Geo_atlas/) мира для изучения географической номенклатуры (5 класс).

## Описание

Веб-приложение для визуализации географических объектов на карте мира. Позволяет изучать материки, океаны, горы, равнины, реки, озёра, моря и другие географические объекты с их точным расположением на карте.

## Основные возможности

- **Интерактивная карта** с маркерами географических объектов
- **Фильтрация по категориям**: материки, океаны, горы и равнины, реки и озёра, моря и др.
- **Поиск объектов** по названию
- **Масштабирование карты**: от 0.5x до 6x с помощью кнопок или колесика мыши
- **Перетаскивание карты** мышью для навигации
- **Отображение координат** в реальном времени при наведении мыши
- **Таблица объектов** с возможностью выделения на карте
- **Статистика**: общее количество объектов, видимых на карте, категорий

## Технические детали

- **Проекция карты**: Псевдоцилиндрическая
- **Система координат**: Поддержка как географических координат (широта/долгота), так и прямых пиксельных координат (x/y)
- **Технологии**: HTML5, CSS3, JavaScript (Vanilla)
- **Формат**: Одностраничное приложение (SPA)

## Использование

1. Откройте страницу в веб-браузере
2. Используйте кнопки фильтров для отображения объектов по категориям
3. Введите название в поле поиска для быстрого поиска
4. Наведите мышь на маркер для просмотра названия объекта
5. Используйте кнопки масштабирования или колесико мыши для увеличения/уменьшения
6. Перетаскивайте карту мышью для навигации

## Структура проекта

```
Geo_atlas/
├── index.html          # Основной файл приложения
├── images/
│   └── map.jpeg        # Изображение карты мира
├── css/                # CSS файлы (если используются)
├── js/                 # JavaScript файлы (если используются)
└── README.md           # Документация
```

## Особенности

- Маркеры автоматически изменяют размер при изменении масштаба
- Поддержка двух систем координат для точного позиционирования объектов
- Адаптивный дизайн для различных размеров экрана
- Интерактивная связь между таблицей объектов и картой

## Лицензия

MIT License

Copyright (c) 2026 Geo_atlas

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.