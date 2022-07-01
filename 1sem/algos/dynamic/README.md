# Лабрадорная 2. Демоническое программирование
## A. Кузнечик
ограничение по времени на тест
2 секунды
ограничение по памяти на тест
256 мегабайт
ввод
input.txt
вывод
output.txt

Кузнечик прыгает по столбикам, расположенным на одной линии на равных расстояниях друг от друга. Столбики имеют порядковые номера от 1 до N. В начале Кузнечик сидит на столбике с номером 1. Он может прыгнуть на следующий столбик или сразу на второй столбик, считая от текущего. Требуется найти количество способов, которыми Кузнечик может добраться до столбика с номером N. Учитывайте, что Кузнечик не может прыгать назад.
### Входные данные

Входная строка содержит натуральное число N (1 ≤ N ≤ 45).
### Выходные данные

Программа должна вывести одно число: количество способов, которыми Кузнечик может добраться до столбика с номером N.
### Примеры
Входные данные
```
3
```

Выходные данные
```
2
```

Входные данные

```
4
```

Выходные данные

```
3
```

Входные данные
```
45
```

Выходные данные

```
1134903170
```

## B. Кузнечик собирает монеты
ограничение по времени на тест
2 секунды
ограничение по памяти на тест
256 мегабайт
ввод
input.txt
вывод
output.txt

Кузнечик прыгает по столбикам, расположенным на одной линии на равных расстояниях друг от друга. Столбики имеют порядковые номера от 1 до N. В начале Кузнечик сидит на столбике с номером 1 и хочет добраться до столбика с номером N. Он может прыгнуть вперед на расстояние от 1 до K столбиков, считая от текущего.

На каждом столбике Кузнечик может получить или потерять несколько золотых монет (для каждого столбика это число известно). Определите, как нужно прыгать Кузнечику, чтобы собрать наибольшее количество золотых монет. Учитывайте, что Кузнечик не может прыгать назад.
### Входные данные

В первой строке вводятся два натуральных числа: N и K (2 ≤ N, K ≤ 10000), разделённые пробелом. Во второй строке записаны через пробел N - 2 целых числа – количество монет, которое Кузнечик получает на каждом столбике, от 2-го до N - 1-го. Если это число отрицательное, Кузнечик теряет монеты. Гарантируется, что все числа по модулю не превосходят 10 000.
### Выходные данные

В первой строке программа должна вывести наибольшее количество монет, которое может собрать Кузнечик. Во второй строке выводится число прыжков Кузнечика, а в третьей строке – номера всех столбиков, которые посетил Кузнечик (через пробел в порядке возрастания).

Если правильных ответов несколько, выведите любой из них.
### Пример
Входные данные

```
5 3
2 -3 5
```

Выходные данные

```
7
3
1 2 4 5 
```

## C. Последовательность из 0 и 1
ограничение по времени на тест
2 секунды
ограничение по памяти на тест
256 мегабайт
ввод
input.txt
вывод
output.txt

Требуется подсчитать количество последовательностей длины N, состоящих из 0 и 1, в которых никакие две единицы не стоят рядом.
### Входные данные

На вход программы поступает целое число N (1 ≤ N ≤ 100).
### Выходные данные

Выведите количество искомых последовательностей.
### Примеры
Входные данные
```
1
```

Выходные данные

```
2
```

Входные данные

```
50
```

Выходные данные

```
32951280099
```

## D. Черепаха и монеты
ограничение по времени на тест
2 секунды
ограничение по памяти на тест
256 мегабайт
ввод
input.txt
вывод
output.txt

Черепаха хочет переползти из левого верхнего угла поля размером N на M клеток (2 ≤ N, M ≤ 1000) в правый нижний. За один шаг она может переместиться на соседнюю клетку вправо или на соседнюю клетку вниз. Кроме того, проходя через каждую клетку, Черепаха получает (или теряет) несколько золотых монет (это число известно для каждой клетки).

Определите, какое максимальное количество монет может собрать Черепаха по пути и как ей нужно идти для этого.
### Входные данные

В первой строке вводятся два натуральных числа: N и M (2 ≤ N, M ≤ 1000), разделённые пробелом. В каждой из следующих N строк записаны через пробел по M чисел aij(|aij| ≤ 10), которые обозначают количество монет, получаемых Черепашкой при проходе через каждую клетку. Если это число отрицательное, Черепашка теряет монеты.
### Выходные данные

В первой строке программа должна вывести наибольшее количество монет, которое может собрать Черепаха. Во второй строке без пробелов выводятся команды, которые нужно выполнить Черепахе: буква 'R' (от слова right) обозначает шаг вправо, а буква 'D' (от слова down) – шаг вниз.
### Пример
Входные данные
```
3 3
0 2 -3
2 -5 7
1 2 0
```

Выходные данные

```
6
RRDD
```

## E. Числа фиксированной суммы
ограничение по времени на тест
2 секунды
ограничение по памяти на тест
256 мегабайт
ввод
стандартный ввод
вывод
стандартный вывод

Сколько существует K-значных чисел с суммой цифр равной S? Числа берутся в десятичной системе счисления. Ведущие нули допустимы.
### Входные данные

K (1 ≤ K ≤ 1000) и S (0 ≤ S ≤ 9·K).
### Выходные данные

Количество таких чисел, посчитанное по модулю 109 + 7.
### Примеры
Входные данные
```
3 10
```

Выходные данные
```
63
```

## F. Лошадью ходи!
ограничение по времени на тест
0.5 секунд
ограничение по памяти на тест
256 мегабайт
ввод
knight.in
вывод
knight.out

В левом верхнем углу прямоугольной доски NxM находится шахматный конь. Перемещаться по доске он может только двумя способами: на две клетки вправо и на одну вниз, либо на две клетки вниз и на одну вправо.

Ваша задача состоит в том, чтобы посчитать количество способов, которыми конь может попасть в правую нижнюю клетку.
### Входные данные

В единственной строчке находятся два числа N и M (1 ≤ N, M ≤ 50)  — размеры доски.
### Выходные данные

Нужно вывести одно число  — количество различных способов переместиться коню из левой верхней в правую нижнюю клетку.
### Пример
Входные данные
```
4 4
```

Выходные данные
```
2
```

## G. Лошадью ходи - 2!
ограничение по времени на тест
1 секунда
ограничение по памяти на тест
256 мегабайт
ввод
knight.in
вывод
knight.out

Шахматный конь должен пройти по клетчатой доске размером N на M клеток из левого верхнего угла в правый нижний. Из каждой клетки есть четыре возможных хода:

Определите, сколькими способами конь может пройти этот маршрут. Поскольку это число может быть очень велико, вычислите его по модулю 106 + 7 , то есть найдите остаток от деления этого числа на 106 + 7.
### Входные данные

Входная строка содержит два натуральных числа: размеры доски N и M (1 ≤ N, M ≤ 500).
### Выходные данные

Программа должна вывести число возможных маршрутов шахматного коня из левого верхнего угла поля в правый нижний, вычисленное по модулю 106 + 7.
### Пример
Входные данные
```
5 5
```

Выходные данные
```
4
```

## H. Расстояние по Левенштейну
ограничение по времени на тест
2 секунды
ограничение по памяти на тест
256 мегабайт
ввод
стандартный ввод
вывод
стандартный вывод

Дана текстовая строка. С ней можно выполнять следующие операции:

1. Заменить один символ строки на другой символ.

2. Удалить один произвольный символ.

3. Вставить произвольный символ в произвольное место строки.

Например, при помощи первой операции из строки «СОК» можно получить строку «СУК», при помощи второй операции — строку «ОК», при помощи третьей операции — строку «СТОК».

Минимальное количество таких операций, при помощи которых можно из одной строки получить другую, называется стоимостью редактирования или расстоянием Левенштейна.

Определите расстояние Левенштейна для двух данных строк.
### Входные данные

Программа получает на вход две строки, длина каждой из которых не превосходит 1000 символов, строки состоят только из заглавных латинских букв.
### Выходные данные

Требуется вывести одно число — расстояние Левенштейна для данных строк.
### Пример
Входные данные
```
ABCDEFGH
ACDEXGIH
```

Выходные данные
```
3
```

## I. Кафе
ограничение по времени на тест
2 секунды
ограничение по памяти на тест
64 мегабайта
ввод
стандартный ввод
вывод
стандартный вывод

Около Петиного университета недавно открылось новое кафе, в котором действует следующая система скидок: при каждой покупке более чем на 100 рублей покупатель получает купон, дающий право на один бесплатный обед (при покупке на сумму 100 рублей и меньше такой купон покупатель не получает).

Однажды Пете на глаза попался прейскурант на ближайшие n дней. Внимательно его изучив, он решил, что будет обедать в этом кафе все n дней, причем каждый день он будет покупать в кафе ровно один обед. Однако стипендия у Пети небольшая, и поэтому он хочет по максимуму использовать предоставляемую систему скидок так, чтобы его суммарные затраты были минимальны. Требуется найти минимально возможную суммарную стоимость обедов и номера дней, в которые Пете следует воспользоваться купонами.
### Входные данные

В первой строке входного файла записано целое число n (0 ≤ n ≤ 100). В каждой из последующих n строк записано одно целое число, обозначающее стоимость обеда в рублях на соответствующий день. Стоимость — неотрицательное целое число, не превосходящее 300.
### Выходные данные

В первой строке выдайте минимальную возможную суммарную стоимость обедов. Во второй строке выдайте два числа k1 и k2 — количество купонов, которые останутся неиспользованными у Пети после этих n дней и количество использованных им купонов соответственно.

В последующих k2 строках выдайте в возрастающем порядке номера дней, когда Пете следует воспользоваться купонами. Если существует несколько решений с минимальной суммарной стоимостью, то выдайте то из них, в котором значение k1 максимально (на случай, если Петя когда-нибудь ещё решит заглянуть в это кафе). Если таких решений несколько, выведите любое из них.
### Примеры
Входные данные
```
5
110
40
120
110
60
```

Выходные данные
```
260
0 2
3
5
```

Входные данные
Скопировать
```
3
110
110
110
```

Выходные данные
Скопировать
```
220
1 1
2
```

## J. Строй штурмовиков.
ограничение по времени на тест
2 секунды
ограничение по памяти на тест
256 мегабайт
ввод
стандартный ввод
вывод
стандартный вывод

На планете Татуин снова проходит сражение между армией штурмовиков и повстанцев. Армия штурмовиков представляет из себя укоплектованный строй из N × M солдат. После продолжительной битвы многие солдаты пали и войска штурмовиков поредели. Максимилиан Вирс всегда отличался умением вести битвы, и на этот раз у него есть разрушительная стратегия, но для ее исполнения ему необходимо узнать обстановку в его войске.

Он отправляет одного из коммандеров штурмовиков сесть на гравицикл и пролететь надо войском для его оценки. Если точнее, ему необходимо знать, какой максимальный квадрат его армии остался уцелевшим. Коммандер видит строй и может сказать о том, в какой точке присутсвует штурмовик, а в какой — уже пал. Помогите коммандеру найти длину такого максимального квадрата, где войско осталось целым по данным, которые он вам предоставит.
### Входные данные

В первой строке даны два натуральных числа N и M (1 ≤ N, M ≤ 1000). Далее в N строках расположено по M чисел, разделенных пробелами (число равно 0, если в позиции отсутствует штурмовик, или 1, если уцелел).
### Выходные данные

Выведите одно число — сторону максимального квадрата, полностью состоящего из уцелевших штурмовиков.
### Пример
Входные данные
```
4 5
0 0 0 1 0
0 1 1 1 0
0 0 1 1 0
1 0 1 0 0
```

Выходные данные
```
2
```

## K. Наибольшая возрастающая подпоследовательность
ограничение по времени на тест
2 секунды
ограничение по памяти на тест
256 мегабайт
ввод
стандартный ввод
вывод
стандартный вывод

Пусть a1, a2, ..., an — числовая последовательность. Длина последовательности — это количество элементов этой последовательности. Последовательность ai1, ai2, ..., aik называется подпоследовательностью последовательности a, если 1 ≤ i1 < i2 < ... < ik ≤ n. Последовательность a называется возрастающей, если a1 < a2 < ... < an.

Вам дана последовательность, содержащая n целых чисел. Найдите ее самую длинную возрастающую подпоследовательность.
### Входные данные

В первой строке задано одно число n (1 ≤ n ≤ 2000) — длина подпоследовательности. В следующей строке задано n целых чисел ai ( - 109 ≤ ai ≤ 109) — элементы последовательности.
### Выходные данные

В первой строке выведите число k — длину наибольшей возрастающей подпоследовательности. В следующей строке выведите k чисел — саму подпоследовательность.
### Примеры
Входные данные
```
5
1 3 5 4 2
```

Выходные данные
```
3
1 3 5 
```

Входные данные
```
3
1 2 3
```

Выходные данные
```
3
1 2 3 
```

## L. Большая наибольшая возрастающая подпоследовательность
ограничение по времени на тест
2 секунды
ограничение по памяти на тест
256 мегабайт
ввод
стандартный ввод
вывод
стандартный вывод

Числовая последовательность задана рекуррентной формулой: ai+1=(kai+b)modm

. Найдите её наибольшую возрастающую подпоследовательность.
### Входные данные

Программа получает на вход пять целых чисел: длину последовательности n
(1⩽n⩽105), начальный элемент последовательности a1, параметры k, b, m для вычисления последующих членов последовательности (1⩽m⩽105, 0⩽k<m, 0⩽b<m, 0⩽a1<m

).
### Выходные данные

Требуется вывести длину наибольшей возрастающей подпоследовательности.
### Пример
Входные данные
```
5 41 2 1 100
```

Выходные данные
```
3
```

Примечание

В данном примере последовательность состоит из 5 элементов: a1=41
, ai+1=(2ai+1)mod100

, то есть последовательность имеет вид 41, 83, 67, 35, 71.

## M. Задача о рюкзаке: точный вес, без ответа
ограничение по времени на тест
2 секунды
ограничение по памяти на тест
512 мегабайт
ввод
стандартный ввод
вывод
стандартный вывод

Дано n золотых слитков массой w1, ..., wn. Ими наполняют рюкзак, который выдерживает вес не более s. Можно ли набрать вес в точности s?
### Входные данные

В первой строке вводится натуральное число n, не превышающее 100 и натуральное число s, не превышающее 10000.

Во второй строке вводятся n натуральных чисел wi, не превышающих 100.
### Выходные данные

Выведите YES или NO.
### Примеры
Входные данные
```
4 102
50 52 54 2
```

Выходные данные
```
YES
```

Входные данные
```
2 3195
38 41
```

Выходные данные
```
NO
```

## N. Задача о рюкзаке: наибольший вес, с ответом
ограничение по времени на тест
2 секунды
ограничение по памяти на тест
512 мегабайт
ввод
стандартный ввод
вывод
стандартный вывод

Дано n золотых слитков массой w1, ..., wn. Ими наполняют рюкзак, который выдерживает вес не более s. Какую наибольшую массу золота можно унести в таком рюкзаке?
### Входные данные

В первой строке вводится натуральное число n, не превышающее 100 и натуральное число s, не превышающее 10000.

Во второй строке вводятся n натуральных чисел wi, не превышающих 100.
### Выходные данные

Выведите в первой строке одно целое число — наибольшую возможную массу золота, которую можно унести в данном рюкзаке. Во второй строке выведите число слитков, которое нужно взять, а в третьей строке — веса слитков, которые нужно взять. Если ответов несколько, выведите любой.
### Примеры
Входные данные
```
5 47
42 52 38 67 10
```

Выходные данные
```
42
1
42 
```

Входные данные
```
4 8
2 3 4 7
```

Выходные данные
```
7
2
4 3 
```

## O. Задача о рюкзаке
ограничение по времени на тест
2 секунды
ограничение по памяти на тест
512 мегабайт
ввод
стандартный ввод
вывод
стандартный вывод

Дано n предметов массой w1, ..., wn.

Ими наполняют рюкзак, который выдерживает вес не более s. Как набрать вес в точности s, используя как можно меньше предметов?
### Входные данные

В первой строке вводится натуральное число n, не превышающее 100 и натуральное число s, не превышающее 10000.

Во второй строке вводятся n натуральных чисел wi, не превышающих 100.
### Выходные данные

Выведите наименьшее необходимое число предметов или 0, если набрать данный вес невозможно.
### Пример
Входные данные
```
4 6
4 2 3 1
```

Выходные данные
```
2
```