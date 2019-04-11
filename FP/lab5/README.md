### Лабораторная работа #5: обобщённые функции, методы и классы объектов. ###

Вариант 5.45

Определите обычную функцию с двумя параметрами:

p - многочлен, т.е. экземпляр класса polynom,

a - список действительных чисел (a1 ... an), где n - степень многочлена p.

Функция должна возвращать список действительных чисел (d0 ... dn), таких что:

P(х) = d0 + d1 * (x - a1) + d2 * (x - a1) * (x - a2) + ... + dn * (x - a1) * ... * (x - an)


### Примеры использования ###
```lisp
(load (compile-file "main.lisp"))
(58.339996 44.8 5)
(13 6 3 1)
(14724 -2454 200 -52 8 -2)
```