# Schelling-Model
## Построение модели расового разделения Шеллинга
### Задача:
на вход подается соотношение и количество цветов клеток на поле(по умолчанию используется 3 цвета)
Необходимо сделать все клетки на поле "счастливыми". Клетка считается счастиливой, если вокруг нее есть хотябы два соседа такого же цвета, как и она.

Для того, чтобы сделать все клетки счастливыми, каждая несчастливая клетка перемещается в случайное свободное место на поле до тех пор, пока все клетки не станут счастливы.
### Выводы
В итоге выполнения работы было выявленно, что в большинстве случаев все клетки на поле становятся счастливыми, когда они разделяются на группы по своим цветам.
### Особенности реализации
При реализации работы была использована библеотека <b>pygame</b>, благодаря которой была выполнена анимациция, наглядно показывающая перемещение цветных клеток на поле.

#### работу выполняли:
1) Трофимов Иван
2) Тимофеева Алена
3) Чабдаров Раиль


#### Пример работы:
<img src="https://github.com/alena195101/Schelling-Model/blob/master/example.jpg?raw=true" width="200" height="200">

<img src="https://github.com/alena195101/Schelling-Model/blob/master/example2.jpg?raw=true" width="200" height="200">
