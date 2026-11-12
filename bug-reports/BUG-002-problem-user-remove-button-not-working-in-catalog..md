# BUG-002: У problem_user кнопка "Remove" в каталоге не убирает товар из корзины 

**Окружение:** saucedemo.com, браузер Google Chrome, версия 157.0.8103.40, ОС Windows 10, пользователь problem_user

**Шаги:**

1. Открыть: https://www.saucedemo.com
2. Войти: логин problem_user, пароль: secret_sauce
3. Нажать на кнопку "Add to cart" под товаром "Sauce Labs Backpack"
4. Нажать на кнопку "Remove" под товаром "Sauce Labs Backpack"

**Ожидаемый результат:** товар из корзины убран

**Фактический результат:** товар из корзины не убран

**Серезность:** средняя

**Обходной путь:**

1. Открыть корзину
2. Убрать "Sauce Labs Backpack"

**Вложения:**

Каталог после добавления товара "Sauce Labs Backpack" 
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/c1073e6e-fa61-4df3-82b6-ed62856d1084" />

Каталог после нажатия кнопки "Remove" под товаром "Sauce Labs Backpack"
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/88055ad9-1655-41fb-84a0-23507b46b3af" />


