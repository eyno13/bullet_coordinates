# bullet_coordinates
Device to determine bullet hit coordinates
Решение проблемы определения координат попадания пули посредством обработки сигналов от четырех звуковых датчиков и известными координатами.

На данный момент решение предполагается искать на базе следующих материалов по теме:

Патант на аналогичное устройство. Но приведенные расчеты не точны. 
https://patents.google.com/patent/RU2367885C1/ru

Попытка найти решение на базе задачи Аполлония: 
https://ru.wikipedia.org/wiki/%D0%97%D0%B0%D0%B4%D0%B0%D1%87%D0%B0_%D0%90%D0%BF%D0%BE%D0%BB%D0%BB%D0%BE%D0%BD%D0%B8%D1%8F

Рабочий алгоритм для построения описанной окружности. Не вполне подходит, необходима вписанная:
https://gist.github.com/mbostock/751fdd637f4bc2e3f08b

Набор решений задач Аполлония. Необходимо разбираться, нужно найти решение для вписанной окружности:
https://mathworld.wolfram.com/ApolloniusProblem.html

Подборка готового кода для разных языков для решения задачи Аполлония. Необходимо разбираться, как это всё работает:
https://rosettacode.org/wiki/Problem_of_Apollonius

Моделирование патента по известным координатам попадания. Вычисления не сходятся:
[расчет временных интервалов версяи 4.xlsx](https://github.com/eyno13/bullet_coordinates/files/8408892/4.xlsx)

testing
