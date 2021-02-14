# BrokenFork
Web application for creating and editing "content maps"

## Идея
Сервис предназначен для совместного создания различного контента для приложений и игр.
Тип абстракции информации - графовая структура на условных листах.
Вершины графа - блоки с контентом, куда мы можем прикреплять текст и картинки.
Ребра графа - соединения между блоками, отображающие их логическую взаимосвязь.
Лист - полотно, разбитое на ячейки (клетки), каждая из которых представляет из себя плейсхолдер для вершин графа. Листы можно будет прокручивать или просматривать для навигации по графу.
Лист разбивается на ячейки из соображений удобства редактирования и навигации.

### Примеры использования:
- разветвленная система диалогов.
- древо навыков в RPG играх.

## Детали
- Стек технологий - Kotlin, Spring Boot, HTML, CSS, JavaScript, jQuery.

## Что реализовано
- Регистрация/авторизация
- Изменение настроек пользователя
- Около половины UI
