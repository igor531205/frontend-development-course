### Задача №0. Замкнутый калькулятор

#### Условие

Напиши калькулятор. Калькулятор должен уметь выполнять базовые арифметические операции (сложение, вычитание, умножение, деление) и сохранять результат предыдущей операции. Интерфейс калькулятора должен предоставлять методы add, subtract, multiply, divide, result для получения текущего результата и reset для сброса результата на 0.
Доступ к текущему состоянию (числу) должен быть только у калькулятора.

#### Пример

```js
const calculator = createCalculator();

calculator.add(10).subtract(2).multiply(3).divide(2); // (0 + 10 - 2) * 3 / 2

console.log(calculator.result()); // Результат: 12

calculator.reset();

console.log(calculator.result()); // Результат: 0
```

#### Подсказка

[Замыкание](https://learn.javascript.ru/closure).
