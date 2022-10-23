<h1 align="center">Привет всем. Это мой калькулятор на Windows Forms C#
<h3 align="center">Карпович Артём 20ИТ-2 || Лабораторная работа №1 ВСРПП</h3>

## Предварительный осмотр приложения и его запуск
Приложение находится в моем репозиторие по ссылке:"https://github.com/Arsiom/Calculator". Скачивайте ZIP архив и запускаете приложение через файл Calculater.sln.

![image](https://user-images.githubusercontent.com/95384044/197418868-f8bae548-0ad6-4f74-8891-bb24b218b8e1.png)

## Функционал данного приложения и его использование
Приложение "Calculator" выполняет функции ввода чисел и последующих операций над ними. 
Например: сложение, вычетание, умножение, деление, изменение знака.
### Сумма чисел

![image](https://user-images.githubusercontent.com/95384044/197419278-a47ed041-cc64-4d3f-9c7d-37e38d375f64.png)

После того как ввели нужное вам число(в моем случае это 31), требуется нажать на одну из предоставленных кнопок арифметического действия(в данном случае это будет являтся "+").
В поле потребуется ввести второе число(в моем случае это 4), дальше нажать на кнопку "=" и увидеть результат(31+4=35). Данный метод расчета применяется ко всем арифметическим действиям.

![image](https://user-images.githubusercontent.com/95384044/197419783-15857300-816c-459c-ba1a-816739732a68.png) 

#### !!!Предупреждение!!! Если вы нажмете на арифметический знак действия и после этого на любой другой знак арифметического действия("-", "+", "*", "/"), то в приоритете будет знак нажатый первым, это значит, что другие последующие прожатые знаки не подействуют.
### Очистка поля
Для того чтобы очистить поле ввода и историю действий, требуется нажать на кнопку "C".

![image](https://user-images.githubusercontent.com/95384044/197421026-08c7d7d6-f8b3-482d-91bb-8ada23808be6.png)

### Изменения знака
Для изменения знака числа, требуется нажать на кнопку "+/-", как показано на приведенной картинке ниже:

![image](https://user-images.githubusercontent.com/95384044/197421967-51ea6fe2-9f0d-4513-894c-63bb104ba2c4.png)

## Unit-тесты
Модульные тесты выполняют проверки основыных арифметических действий калькулятора с корректными и некорректными данными.

![image](https://user-images.githubusercontent.com/95384044/197422079-10627296-080f-41eb-b262-b59b4f7ccc6c.png)
