# PyCharm_task
## Профилизатор filter.py
![Profiler of filter](https://github.com/speedUpDev/PyCharm_task/blob/main/screenshots/profiler_filter.png)
> Продолжительность работы программы увеличивается из-за ручного ввода пользователем параметров.
## Профилизатор old_filter.py
![Profiler of old_filter](https://github.com/speedUpDev/PyCharm_task/blob/main/screenshots/profiler_old_filter.png)
> Очевидно,  данная версия программы работает долго из-за большого количества вложенных циклов.
## Профилизатор filter_with_filenames.py
![Profiler of filter_with_filenames](https://github.com/speedUpDev/PyCharm_task/blob/main/screenshots/profiler_filter_with_filenames.png)
> В файле filter_with_filenames был исправлен недочет с временем требуемым пользователю на ввод параметров, они задавались изначально. Соответственно, результат сильно отличается от тестов предыдущей версии filter.py.
***
## Результат работы фильтра
### Как выглядело изображение до использования фильтра:
![Image before filter](https://github.com/speedUpDev/PyCharm_task/blob/main/test.jpg)
### Как выглядит изображение после использования фильтра:
![Image after filter](https://github.com/speedUpDev/PyCharm_task/blob/main/res.jpg)
***
## Отладчик
![Watches](https://github.com/speedUpDev/PyCharm_task/blob/main/screenshots/watches.png)
> Я вывел в отладчике тип картинки(format), длину(size[0]) и ширину(size[1]), вывел их в Watches для удобства.(Использовал исходное фото из репозитория test.jpg)
