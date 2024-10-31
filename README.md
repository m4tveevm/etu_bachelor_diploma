# etu_bachelor_diploma

## Функциональные требования:

* Возможность для администрации создавать и редактировать расписание.
* Ограничения по занятости преподавателей, *аудиторий и групп.
* Отображение расписания для студентов (по номеру группы) и преподавателей.
* Управление конфликтами и предупреждения о них.
* Расписание с учетом четности недели.

## Нефункциональные требования:

* Масштабируемость. - ?
* Надежность и отказоустойчивость. - предположительно
* Удобство использования интерфейса.

## Архитектура приложения

### Frontend

1. ReactAPP - ядро,
2. Bootstrap - Готовый набор стилей, для быстроты разработки

### Backend

1. Django (Поскольку там есть готовый ORM для работы, не нужно будет
   заморачиваться)

### Data Base

1. Postgres, за счет удобного хранения объектов в виде объектов и возможности 
в дальнейшем использовать масштабирования



--
1. Сформировать расписание на семестр (группа -> преподаватель -> дисциплины)
2. 1 пара 1.5 ч и 4ч
3. день 2 практики или 4 пары
