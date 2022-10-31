# Определение четности n-го большого числа Фибоначчи
Дано целое число 1 ≤ n ≤ 10^{6}1≤n≤10 
6
  , необходимо написать функцию fib_eo(n) для определения четности nn-го числа Фибоначчи.

Как мы помним, числа Фибоначчи растут очень быстро, поэтому при их вычислении нужно быть аккуратным с переполнением. В данной задаче, впрочем, этой проблемы можно избежать, поскольку нас интересует только последняя цифра числа Фибоначчи: если 0 ≤ a, b ≤ 90≤a,b≤9 — последние цифры чисел F_nF 
n
​
  и F_{n+1}F 
n+1
​
  соответственно, то (a+b) \bmod{10}(a+b)mod10 — последняя цифра числа F_{n+2}F 
n+2
​
 .

В результате выполнения, функция должна вывести на экран четное ли число или нет (even или odd соответственно), например fib_eo(841645) должна вывести odd, т.к. последняя цифра данного числа — 5.
