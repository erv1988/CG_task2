# CG Task 2 Растровые алгоритмы
Задания 2 по курсу "Компьютерная графика" https://github.com/erv1988/CG_task2
Используется основа с задания https://github.com/erv1988/CG_task1

# 1. Алгоритм заливки.
- Изучить алгоритм заливки изображения.
https://ru.wikipedia.org/wiki/%D0%97%D0%B0%D0%BB%D0%B8%D0%B2%D0%BA%D0%B0
- На основе примера, приведенного в задании 1, реализовать алгоритм заливки выбранным цветом (4 и 8 связность). Границы заливки загружать из файла, граница всегда имеет черный цвет, рисунок может быть произвольным и содержать вложенные фигуры. Начальная точка заливки выбирается кликом мыши. 
Примеры входного изображения: data/img1.png
        результата:           data/img2.png

# 2. Выделение границы связной области.
- Изучить алгоритм определения границы связной области.
https://ru.wikipedia.org/wiki/%D0%92%D1%8B%D0%B4%D0%B5%D0%BB%D0%B5%D0%BD%D0%B8%D0%B5_%D0%B3%D1%80%D0%B0%D0%BD%D0%B8%D1%86
алгоритм Жука 
http://wiki.technicalvision.ru/index.php/%D0%92%D1%8B%D0%B4%D0%B5%D0%BB%D0%B5%D0%BD%D0%B8%D0%B5_%D0%B8_%D0%BE%D0%BF%D0%B8%D1%81%D0%B0%D0%BD%D0%B8%D0%B5_%D0%BA%D0%BE%D0%BD%D1%82%D1%83%D1%80%D0%BE%D0%B2#:~:text=%22%D0%96%D1%83%D0%BA%22%20%D0%BD%D0%B0%D1%87%D0%B8%D0%BD%D0%B0%D0%B5%D1%82%20%D0%B4%D0%B2%D0%B8%D0%B6%D0%B5%D0%BD%D0%B8%D0%B5%20%D1%81%20%D0%B1%D0%B5%D0%BB%D0%BE%D0%B9,%D0%BD%D0%B5%20%D0%B2%D0%B5%D1%80%D0%BD%D0%B5%D1%82%D1%81%D1%8F%20%D0%B2%20%D0%B8%D1%81%D1%85%D0%BE%D0%B4%D0%BD%D1%83%D1%8E%20%D1%82%D0%BE%D1%87%D0%BA%D1%83.
- На основе примера, приведенного в задании 1, реализовать алгоритм выделения границы связной области. На вход подается изображение. Граница связной области задается одним цветом. Имея начальную точку границы организовать ее обход, занося точки в список в порядке обхода. Начальную точку границы можно получать любым способом. Для контроля полученную границу прорисовать поверх исходного изображения.
Примеры входного изображения: data/img3.png
        результата:           data/img4.png

# 3. Интерполяция.
- На основе примера, приведенного в задании 1, реализовать градиентное окрашивание произвольного треугольника, у которого все три вершины разного цвета.
https://ru.wikipedia.org/wiki/%D0%91%D0%B8%D0%BB%D0%B8%D0%BD%D0%B5%D0%B9%D0%BD%D0%B0%D1%8F_%D0%B8%D0%BD%D1%82%D0%B5%D1%80%D0%BF%D0%BE%D0%BB%D1%8F%D1%86%D0%B8%D1%8F
Примеры результата: data/img5.png
                    data/img6.png

