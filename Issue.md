**При сложении двух переменных получается отрицательный результат**

**Материалы для тестирования** 

-[ Домашнее задание](https://github.com/netology-code/javaqa-homeworks/tree/master/programming)

**Шаги для воспроизведения**

1. Открыть IDEA
2. Завести новый проект
3. Создать ClassMain
4. Переменная 

<pre><code>int balance = 2_000_000_000;
int transferSum = 500_000_000;
int totalVa = balanse + transferSum;</code></pre>

5. Команда для вывода результата System.out.printLn
6. Запустить метод Ctrl+Shift+F10

**Результат**

Ожидаемый:
Сумма = 2500000000

Фактический:
Сумма = -1794967296

**Cкриншот ошибки**

![Скриншот](https://github.com/MashaOsipova/Java1.2.1/blob/4d09647dd03694a96e568478d296e16d82f5bde7/%D0%A1%D0%BD%D0%B8%D0%BC%D0%BE%D0%BA%20%D1%8D%D0%BA%D1%80%D0%B0%D0%BD%D0%B0.png)

**Окружение**

- Windows 10 
- Java version "11.0.9.1" 
- IntelliJ IDEA Community Edition 2020.3.1
