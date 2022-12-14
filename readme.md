# Инструкция для работы с Git и удалёнными репозиториями

## **Что такое Git?**
*Git* - это одна из реализаций распределённых систем контроля версий, имеющая как и локальные, так и удалённые репозитории. Является самой популярной реализацией систем контроля версий в мире.
## **Подготовка репозитория**
Для создание репозитория необходимо выполнить команду *git init*  в папке с репозиторием и у Вас создаться репозиторий (появится скрытая папка *.git*)
![Рис.1 Создание репозитория](init.jpg)
## **Создание коммитов**

### *Git add*
Для добавления измений в коммит используется команда *git add*. Чтобы использовать команду *git add* напишите *git add <имя файла>*
![Рис.2 Добавление изменений в commit](add.jpg)
### **Просмотр состояния репозитория**
Для того, чтобы посмотреть состояние репозитория используется команда *git status*. Для этого необходимо в папке с репозиторием написать *git status*, и Вы увидите были ли измения в файлах, или их не было.

### **Создание коммитов**
Для того, чтобы создать коммит(сохранение) необходимо выполнить команду *git commit*. Выполняется она так: *git commit -m "<сообщение к коммиту>*. Все файлы для коммита должны быть ***ДОБАВЛЕНЫ*** и сообщение к коммиту писать ***ОБЯЗАТЕЛЬНО***.
![Рис.3 Создание коммитов](commit.jpg)
## **Перемещение между сохранениями**
Для того, чтобы перемещаться между коммитами, используется команда *git checkout*. Используется она в папке с репозиторием следующим образом: *git checkout <номер коммита>*
![Рис.4 Перемещение между коммитами](checkout.jpg)
## **Журнал изменений**
Для того, чтобы посмoтреть все сделанные изменения в репозитории, используется команда *git log*. Для этого достаточно выполнить команду *git log* в папке с репозиторием
![Рис.5 Посмотреть все изменения в репозитории](log.jpg)
## **Ветки в Git**

### **Создание ветки**

Для того, чтобы создать ветку, используется команда *git branch*. Делается это следующим образом в папке с репозиторием: *git branch <название новой ветки>*
![Рис.6 Создание веток](branch%20new.jpg)
## **Слияние веток**

Для того чтобы дабавить ветку в текущую ветку используется команда *git merge <name branch>*
![Рис.7 Слить ветки](merge.jpg)
## **Удаление веток**
Для удаления ветки ввести команду "git branch -d 'name branch'"
![Рис.8 удаление веток](branch_del.jpg)