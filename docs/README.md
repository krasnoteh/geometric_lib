Этот репозитоий - "дань истории", старый учебный проект. Nothing interesting here.


# Библеотека **Geometric lib**
Данная библеотека имеет набор функций, позволящих вычислять площать и периметр
для следующих геметрических фигур:
- квадрат 
- прямоугольник 
- круг 
- треугольник.

## Описание функций
Для каждой геометрической фигуры есть две функции **perimetr** и **area**, вычисляющие
периметр и площадь соответственно.

Вот пример вызова функции для **круга**:

```sh
r = 5
a = area(r)
p = perimeter(r)
#a = 78.53...
#b = 31.415...
```
где **r** - радиус круга

Для **квадрата**:
```sh
a = 5
ar = area(a)
p = perimeter(a)
#ar = 25
#p = 20
```
где **a** - сторона квадрата

Для **прямоугольника**:
```sh
a = 2
b = 3
ar = area(a, b)
p = perimeter(a, b)
#ar = 6
#p = 10
```
где **a** и **b** - стороны прямоугольника

Для **треугольника**:
```sh
a = 3
b = 2
c = 4
h = 4
ar = area(a, h)
p = perimeter(a, b, c)
#ar = 6
#p = 9
```
где **a** , **b**, **c** - стороны треугольника,
**h** - его высота

## Тестирование
Добалено тестирование при помощи unittests

## Предыдущие версии
Вы можете использовать предыдущие версии проекта, воспользовавшись коммитами:
| хэш | внесенные изменемия |
| --- | --------------------|
| 1b4b1ba |  Добавлены тесты |
| 6bb8270 |  исправлена ошибка |
| 9a55316 |  добавлен файл rectangle.py |
| d078c8d |  Docs added |
| 8ba9aeb |  Circle and square added |



