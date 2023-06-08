# Тестовое задание "Алгоритмы - базовая теория"

## Задания:

### 1. Составить алгоритм: если введенное число больше 7, то вывести “Привет”.

<details>
  <summary>Решение</summary>
  
  ```
  package org.example;

import java.util.Scanner;

public class TaskN1 {
    public static void main(String[] args) {
        Scanner scan = new Scanner(System.in);
        System.out.println("Введите число: ");
        int number = scan.nextInt();
        if (number > 7) {
            System.out.println("Привет");
        }
    }
}
  ```
</details>

### 2. Составить алгоритм: если введенное имя совпадает с Вячеслав, то вывести “Привет, Вячеслав”, если нет, то вывести "Нет такого имени".

<details>
  <summary>Решение</summary>
  
  ```
  package org.example;

import java.util.Scanner;

public class TaskN2 {
    public static void main(String[] args) {
        Scanner scan = new Scanner(System.in);
        System.out.println("Введите имя: ");
        String name = scan.nextLine();
        if (name.equals("Вячеслав")) {
            System.out.println("Привет, Вячеслав");
        } else {
            System.out.println("Нет такого имени");
        }
    }
}
  ```
</details>

### 3. Составить алгоритм: на входе есть числовой массив, необходимо вывести элементы массива кратные 3.

<details>
  <summary>Решение</summary>
  
https://github.com/DmitriyRonMan/Kolesnikov_Java/blob/a39182ada9be782386ec2812e5800a29dcec51f4/src/main/java/org/example/TaskN3.java#L1-L22
  
</details>
