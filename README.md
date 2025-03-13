# PR3
Данный репозиторий представляет собой выполненные нижеперчисленные задачи Практической Работы №3. 

Задача №1
Ввести значение 2-х целых переменных а и b. Направить два указателя на эти переменные. С помощью указателя увеличить значение переменной а в 2 раза, а b уменьшить в 2 раза.

Задача №2
Описать 3 указателя на вещественный тип. Выделить для них динамическую память. Присвоить произвольные значения в выделенные ячейки в операторе присвоения. Поменять местами значения первых 2-х переменных.

Задача №3
Создать динамические массивы, используя указатели. Задан одномерный массив а (n). Найти все номера и среднее арифметическое отрицательных элементов массива

Задача №4
Дан массив b (n) . Переписать в массив C(n) корни квадратные из положительных элементов массива b(n) деленные на 5. (со сжатием., без пустых элементов внутри) Затем упорядочить методом «выбора и перестановки» по возрастанию новый массив.

## Инструкция по сборке и использованию

1. **Клонировать репозиторий и перейти в корневой каталог:**
   ```bash
   git clone https://github.com/Anuta05/pr3.git
   cd PR3
   ```
2. **Создать и перейти в директорию сборки:**
   ```bash
   mkdir build
   cd build
   mkdir bin
   ```
3. **Запустить CMake и собрать проект:**
   ```bash
   cmake ..
   cmake --build .
   ```
4. **Перейти в папку с выполненными файлами и запустить:**
   ```bash
   cd bin
   ```
   Пример использования:
   ```bash
   ./Num1
   ./Num2
   ./Num3 <ввод значений>
   ./Num4 <ввод значений>
   ```
