## Тестовые задания для Python

### Задача 1: Что может быть проще SQL?

Вам дана таблица в postgres, которая представляет из себя список сотрудников с их зарплатами и отделами.
Необходимо написать запрос, который будет выбирать человека с максимальной зарплатой из каждого отдела. В качестве тестовых данных можете использовать [дамп таблицы](https://github.com/obulygin/test_tasks/blob/master/python_developer/some_py_developer/employee.sql).


### Задача 2: Smashing Wallpaper Downloader

Есть сайт [Smashing Magazine](https://www.smashingmagazine.com/), который каждый месяц выкладывает отличные обои для десктопа. Заходить каждый месяц и проверять, что там нового дело не благородное, поэтому давайте попробуем автоматизировать эту задачу.
Требуется написать cli утилиту, которая будет качать все обои в требуемом разрешение за указанный месяц-год в текущую директорию пользователя. Вот [тут](https://www.smashingmagazine.com/tag/wallpapers/) находятся все обои, а [здесь](https://www.smashingmagazine.com/2022/08/desktop-wallpaper-calendars-september-2022/) находятся обои за сентябрь 2022.

Условия:
* Python 3.7+
* Любые сторонние библиотеки
* PEP8
* Если останется время, то можете покрыть её тестами с помощью py.test (:

Особенности:
* Если обои доступны в вариантах с календарём и без, утилита скачает оба.
* Не все обои доступны во всех разрешениях, если конкретных обоев запрошенного разрешения нет, утилита их пропустит.
