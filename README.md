# 7laba_2sem — Калькулятор и сортировка

Лабораторная №7, 2 семестр. Два задания: рекурсивный калькулятор и построение цепочек чисел.

## Что внутри
- `Calculator.cpp` — рекурсивный разбор `+/-/()/пробелы` (`evaluateExpression`, `calculate`)
- `SortedArray.cpp` — поиск макс. цепочки по правилу `lastDigit(prev)==firstDigit(next)`

## Стек
C++

## Запуск
```bash
g++ Calculator.cpp -o calc && ./calc
g++ SortedArray.cpp -o sorted && ./sorted
```

## Что изучено
Рекурсия, парсинг выражений, перебор с backtracking.

---
**Автор:** Assweg · Telegram: [@assweg](https://t.me/assweg) · Учебное портфолио, все работы — студенческие.
