# java-cofre: piggy bank in Java

Console application written as coursework for object-oriented programming (2023). It simulates a piggy bank that holds coins in three currencies.

## Features

- Add and remove coins in Real, Dollar and Euro
- List everything in the piggy bank
- Convert the total to Brazilian Real

## Concepts used

- Abstract class `Moeda` with the subclasses `Real`, `Dolar` and `Euro`
- Polymorphism for the currency conversion
- `ArrayList` and input validation with exception handling

## Running

The classes are declared in the package `trabalho`:

```bash
mkdir trabalho && cp *.java trabalho/
javac trabalho/*.java
java trabalho.Principal
```

The menu is in Portuguese.
