Практически в любом веб приложении нужно:
 1)Принять запрос
 2)Определить какой обраотчик должен выполняться 
 3)Выполнить обработчик т подготовить ответ 
 4)Вернуть ответ клиенту 

Путь - то часть адреса, идущая следом за доменным в HTTP-запросе.

---

# СУБД
Это система управления базами данных. 
# Что надо 
Перечислю некоторые новые темы, которые нужно изучить, чтобы без проблем писать код:

- Базы данных — умение устанавливать и настраивать их, управление пользователями, оперирование сокетами, в том числе сетевыми
- Знание операционных систем и сетей
- Знание SQL, что включает в себя и основы теории множеств
- Понятия нормализации и денормализации — нормальные формы, ключи и индексы
- Сериализация и десериализация
- Идемпотентность
- Fluent Interface
- Итератор
- Экранирование, SQL Injection и другие темы, связанные с безопасностью

---


# API
Application Programming Interface или «Программный интерфейс приложения») — это протокол взаимодействия между вашим приложением и другими программами. API не отвечает за общение приложения и пользователя. Вместо этого пользователь обычно использует отдельную программу-клиент, которая обращается к серверу по необходимости.

---


# Тесты
Тесты нужно писать в любом случаи, для проверки ссвоего проекта. Чем больше проект, тем больше хорошо написаные тесты спасают от различных ошибок и проблем. 

> [!ПРОЧИТАТЬ] Доп статья 
> ссылка на хекслет - https://ru.hexlet.io/blog/posts/how-to-test-code

Написание тестов (особенно до кода) входит в методологию, называемую XP или экстремальное программирование. Она включает в себя лучшие практики, помогающие писать качественный код. Вот их список:
- Тестирование
- Игра в планирование
- Заказчик всегда рядом
- Парное программирование
- Непрерывная интеграция
- Рефакторинг
- Частые небольшие релизы
- Простота проектирования
- Метафора системы
- Стандарты оформления кода
---

## Коллекции
Любые данные нужно как-то представлять в памяти компьютера — и делать это нужно так, чтобы с данными было удобно и эффективно работать. Поэтому в программах данные часто хранятся в _коллекциях_. Список пользователей, список страниц, список дат, список строк, список серверов — все эти сущности можно представить в коде в виде коллекций.
Python известен тем, что поставляется с набором готовых видов коллекций, которые работают очень эффективно и удобны в использовании. Вот основные встроенные типы коллекций в Python:
- Списки (lists)
- Словари (dictionaries)
- Множества или наборы (sets)
Разные типы коллекций требуют разных подходов к использованию и полезны в разных ситуациях. Более того, существует несколько сильно различающихся подходов для работы с одними только списками! И Python-разработчик должен понимать, какую коллекцию нужно применить, каким способом с ней работать, какие преимущества это даст и какими недостатками этот выбор будет обладать.
