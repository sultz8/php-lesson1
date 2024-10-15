# Первое занятие
## Вступление

### Содержание курса:
* Основы PHP
  + Переменные, Операции над переменными.
  + Условные конструкции.
  + Циклы.
  + Массивы. Функции над массивами.
  + Строки. Функции над строками.
  + Основы ООП.
    - Классы и объекты
    - Наследование и полиморфизм
    - Инкапсуляция
    - Интерфейсы и Абстрактные классы
    - static, self
  + Базы данных
* Laravel
  + Docker
  + Установка проекта
  + Routing
  + Controller
  + Валидация
  + Middleware
  + Eloquent
    - Модели
    - Миграции
    - Relations
    - Фабрики
    - Сидеры
  + API
  + Аутентификация и авторизация. Laravel Sanctum
  + Event and Listener
  + Cache, Redis
  + Queue, Jobs
  + Localization
  + Scheduler
  + File storage


## Необходимое ПО
1. Docker 
![Docker](https://upload.wikimedia.org/wikipedia/commons/thumb/4/4e/Docker_%28container_engine%29_logo.svg/2560px-Docker_%28container_engine%29_logo.svg.png)
2. PhpStorm or Fleet, VS Code 
![PhpStorm](https://university.sensiolabs.com/images/posts/Phpstorm-logo.png?sluv=6c0209a7d73f4f418f93da050cec7320fb92107c)



---

## Основы PHP. echo, переменные, арифметические операции.

### echo
```php
<?php

echo "Hello, world!";

?>
```
<br />

```php
<?php

echo "Hi";
echo "Hello";
```
<br />

```php
echo "Hi\n";
echo "Hello" . "\n";
echo "Howdy";
```
<br />
<br />

### Числовые литералы
```php
echo "2 + 3" . "\n";
echo 2 + 3;
echo "2" + "3";
```

<br />
<br />

### Переменные
```php
$a = 1;
$b = 3;

$c = $a + $b;

echo $c;
```

<br />

### Арифметические операции
```php
$a = 10;
$b = 2;

$sum = $a + $b;
$mul = $a * $b;
$diff = $a - $b;
$div = $a / $b
$mod = $a % b;

var_dump($sum, $mul, $diff, $div, $mod);
```

### Типы данных
```php
$varInteger = 13; // integer
$varFloat = 13.4; // float
$varBool = true; // true/false boolean
$varString = "php"; // string "", ''
$varArray = array(1, 2, 3); // array
$varObject = new stdClass(); // object

var_dump($varInteger, $varFloat, $varBool, $varString, $varArray, $varObject);
```

### Считывание данных с консоли
```php
$firstNumber = (int) fgets(STDIN));  // 2

$secondNumber = (int) fgets(STDIN);  // 1

echo $firstNumber + $secondNumber; // 3
```

### Практика
1. [ACMP](https://acmp.ru/asp/do/index.asp?main=course&id_course=2)
2. [LeetCode](https://leetcode.com/)

### Задачи на уроке.
1. [A+B](https://acmp.ru/asp/do/index.asp?main=task&id_course=2&id_section=10&id_topic=1&id_problem=1)
2. [Журавлики](https://acmp.ru/asp/do/index.asp?main=task&id_course=2&id_section=10&id_topic=1&id_problem=4)
3. [Магазин канцелярских товаров](https://acmp.ru/asp/do/index.asp?main=task&id_course=2&id_section=10&id_topic=1&id_problem=19)

---


### Домашнее задание.
1. [Неглухой телефон](https://acmp.ru/asp/do/index.asp?main=task&id_course=2&id_section=10&id_topic=1&id_problem=2)
2. [Два бандита](https://acmp.ru/asp/do/index.asp?main=task&id_course=2&id_section=10&id_topic=1&id_problem=3)
3. [Игра](https://acmp.ru/asp/do/index.asp?main=task&id_course=2&id_section=10&id_topic=1&id_problem=5)



### Установка Docker.
1. [WSL](https://ubuntu.com/tutorials/install-ubuntu-desktop#1-overview)
2. [Docker](https://docs.docker.com/desktop/install/windows-install/)