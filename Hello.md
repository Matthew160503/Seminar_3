## ***1. Инструкция для работы с Git и удалёнными репозиториями***

***

## **Что такое Git?**

*Git* - это одна из реализаций распределённых систем контроля версий, имеющая как и локальные, так и удалённые репозитории. Является самой популярной реализацией систем контроля версий в мире.

## **Подготовка репозитория**

Для создание репозитория необходимо выполнить команду *git init*  в папке с репозиторием и у Вас создаться репозиторий *(появится скрытая папка .git)*

## **Создание коммитов**

**Git add**

Для добавления измений в коммит используется команда *git add*. Чтобы использовать команду *git add* напишите *git add <имя файла>*

**Просмотр состояния репозитория**

Для того, чтобы посмотреть состояние репозитория используется команда *git status*. Для этого необходимо в папке с репозиторием написать *git status*, и Вы увидите были ли измения в файлах, или их не было.

**Создание коммитов**

Для того, чтобы создать коммит(сохранение) необходимо выполнить команду *git commit*. Выполняется она так: *git commit -m "<сообщение к коммиту>*. Все файлы для коммита должны быть ***ДОБАВЛЕНЫ*** и сообщение к коммиту писать ***ОБЯЗАТЕЛЬНО***.

**Перемещение между сохранениями**

Для того, чтобы перемещаться между коммитами, используется команда *git checkout*. Используется она в папке с пепозиторием следующим образом: *git checkout <номер коммита>*

**Журнал изменений**

Для того, чтобы посмтреть все сделанные изменения в репозитории, используется команда *git log*. Для этого достаточно выполнить команду *git log* в папке с репозиторием

## **Ветки в Git**

**Создание ветки**

Для того, чтобы создать ветку, используется команда *git branch*. Делается это следующим образом в папке с репозиторием: *git branch <название новой ветки>*

**Слияние веток**

Для того чтобы дабавить ветку в текущую ветку используется команда *git merge <name branch>*

**Удаление веток**

Для удаления ветки ввести команду "git branch -d 'name branch'"
***


## ***2. Добавление картинок***
***

Команда для добавления *картинки* выглядит следующим образом:

 ![Котик](https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRImL1RQ-gc-phd0JWga1Kk3ktlk1NHq2JEq83h2PQDzg&s)

 Добавим еще *картинок*

 ![Самолёт](https://upload.wikimedia.org/wikipedia/commons/thumb/9/91/Aeroflot_Airbus_A320_Kustov.jpg/1200px-Aeroflot_Airbus_A320_Kustov.jpg)

![Курсы в GB](https://thumbs.dreamstime.com/b/%D1%81%D1%87%D0%B0%D1%81%D1%82%D0%BB%D0%B8%D0%B2%D1%8B%D0%B9-%D1%80%D0%B0%D0%B4%D0%BE%D1%81%D1%82%D0%BD%D1%8B%D0%B9-%D1%87%D0%B5%D0%BB%D0%BE%D0%B2%D0%B5%D0%BA-%D0%BD%D0%B0%D1%81%D0%BB%D0%B0%D0%B6%D0%B4%D0%B0%D1%8F%D1%81%D1%8C-%D0%B5%D0%B3%D0%BE-%D0%BE%D1%81%D1%82%D0%B0%D1%82%D0%BA%D0%B0%D0%BC%D0%B8-113633672.jpg)

***

 ## ***3. Добавление ссылок***

 ***

 [*Работа с Markdown*](https://lifehacker.ru/chto-takoe-markdown/)

 Закрепим ссылки, где можно будет посмотреть дополнительно информацию по VS Code и Git

[*Установка и настройка VS Code*](https://habr.com/ru/post/490754/)

[*Руководство по гид для начинающих*](https://proglib.io/p/git-for-half-an-hour)

***

## ***4. Добавление цитаты***

***

Работа с **цитатами** выполняется через знак *">"*
>Кто глупее: дурак или тот, кто последовал за ним?
>> А это я добавил подцитату

> **Хочется сказать, что я умею работать с цитатами!**
___

## ***5. Оформление списков***

___

1. Первый
2. Второй
3. Третий

* Первый
- Второй
- Второй
+ Третий

***

## ***6. git pull***

***

Эта команда позволяет скачать все из текущего репозитория и автоматически сделать merge с нашей версией

## ***7. git push***

***

При первом её использовании нужна авторизация.
Эта команда позволяет отправить нашу версию репозитория на внешний репозиторий. ТРЕБУЕТ АВТОРИЗАЦИИ на внешнем репозитории.

## ***8. Как настроить совместную работу***

***

1. Создать аккаунт на GitHub.com
2. Создать локальный репозиторий
3. “Подружить” ваш локальный и удалённый репозитории. 
    
GitHub при создании нового репозитория подскажет, как это можно сделать
    
4. Отправить (push) ваш локальный репозиторий в удалённый (на GitHub), при этом, возможно, вам нужно будет авторизоваться на удалённом репозитории
5. Провести изменения “с удаленного репозитория”
6. Выкачать (pull) актуальное состояние из удалённого репозитория

## ***9. pull request***

***

- команда для предложения изменений 

- запрос на вливание изменений в репозиторий

В больших компаниях один ответственный за проект создает аккаунт. Другие пользователи дают команду **pull request**. Предлагать изменения на GitHub нужно в отдельной ветке. 
Сначала пользователь копирует репозиторий на свой компьютер, делает fork репозитория, затем клонирует версию на своём ПК, создаёт ветку с предлагаемыми изменениями, отправляет изменения командой push в свой аккаунт на GitHub и даёт команду pull request.
 
 Как сделать pull request (по шагам):

- Делаем fork (ответвление) репозитория
- Делаем git clone СВОЕЙ версии репозитория
- Создаем новую ветку и в НЕЕ вносим свои изменения
- Фиксируем изменения (делаем коммиты)
- Отправляем свою версию в свой GitHub
- На сайте GitHub нажимаем кнопку pull request


***
