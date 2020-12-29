# Лабораторные работы по курсу "Методы трансляции и компиляции" НГУ
## Блок 1. Знакомство с языком flow
1. [Написать фукнцию, преобразующую массив целых чисел в массив строк, распечатать этот массив.](https://github.com/Dross0/Translation-And-Compilation-Methods-flow9-Labs/blob/main/firstBlock/task1.flow)
2. [Написать функцию, считающую сумму целых чисел в массиве.](https://github.com/Dross0/Translation-And-Compilation-Methods-flow9-Labs/blob/main/firstBlock/task2.flow)
3. [Написать функцию, fib(n : int) -> [int], вычисляющую n первых чисел фиббоначчи. Сделать ее а) рекурсивной б) с хвостовой рекурсией в) с использованием ссылок на массив, сложности O(n).](https://github.com/Dross0/Translation-And-Compilation-Methods-flow9-Labs/blob/main/firstBlock/task3.flow)
4. [Дан массив целых чисел [n_1,...,n_k] и число m. Найти все пары индексов (i, j) такие, что n_i + n_j == m. Сигнатура функции: inds(a : [int], m : int) -> [Pair<int, int>]. Усложнение: сделать эту функцию сложности O(n log(n)), а не O(n^2).](https://github.com/Dross0/Translation-And-Compilation-Methods-flow9-Labs/blob/main/firstBlock/task4.flow)
## Блок 2. Работа с парсерами и AST. Реализация арифметики 
5. [Написать PEG-парсер грамматики простых арифметических выражений, генерирующий AST дерево.](https://github.com/Dross0/Translation-And-Compilation-Methods-flow9-Labs/tree/main/secondBlock/Arithmetic)
6. [Преобразовать AST дерево арифметических выражений обратно в строковую форму](https://github.com/Dross0/Translation-And-Compilation-Methods-flow9-Labs/tree/main/secondBlock/Arithmetic)
7. [Реализовать калькулятор, вычисляющий значение арифметического выражения.](https://github.com/Dross0/Translation-And-Compilation-Methods-flow9-Labs/tree/main/secondBlock/Arithmetic)
8. [Сделать этот калькулятор символьным, принимающим значения переменных из командной строки](https://github.com/Dross0/Translation-And-Compilation-Methods-flow9-Labs/tree/main/secondBlock/Arithmetic)
9. [Расширить язык функциями степени, дробями.](https://github.com/Dross0/Translation-And-Compilation-Methods-flow9-Labs/tree/main/secondBlock/rationalArithmetic)
10. [Реализовать функцию упрощения алгебраического выражения (трансформация AST дерева с сохранением семантики)](https://github.com/Dross0/Translation-And-Compilation-Methods-flow9-Labs/tree/main/secondBlock/Arithmetic)
11. [Реализовать функцию символьного дифференцирования алгебраического выражения (+ упрощение).](https://github.com/Dross0/Translation-And-Compilation-Methods-flow9-Labs/tree/main/secondBlock/Arithmetic)
## Блок 3. Реализация языка НеМо
12. [Написать PEG-парсер модельного языка  НеМо.](https://github.com/Dross0/Translation-And-Compilation-Methods-flow9-Labs/tree/main/thirdBlock/task12)
13. [Написать PEG-парсер для языка вируальной машины НеМо.](https://github.com/Dross0/Translation-And-Compilation-Methods-flow9-Labs/tree/main/thirdBlock/task13/nemo/vnemo)
14. [Написать реализацию виртуальной машины НеМо, исполняющую программы на ее языке.](https://github.com/Dross0/Translation-And-Compilation-Methods-flow9-Labs/blob/main/thirdBlock/task13/nemo/vnemo/run.flow)
15. [Написать транслятор их модельного языка НеМо в язык его виртуальной машины.](https://github.com/Dross0/Translation-And-Compilation-Methods-flow9-Labs/blob/main/thirdBlock/task12-15/nemo/vnemo/translator.flow)
## Блок 4. Реализации функционала формальной верификации для НеМо
16. ~~[Придумать язык спецификаций для Немо.](#)~~
17. ~~[Добавить в грамматику Немо язык спецификаций, дополнить парсер.](#)~~
18. ~~[Написать генератор условий корректности для Немо.](#)~~
19. ~~[Сделать язык условий корректности входным для какого-либо инструмента автоматизации поиска доказательств.](#)~~
