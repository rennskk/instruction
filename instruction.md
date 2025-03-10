# Инструкция по работе с Git

## Что такое Git?

__*Git*__ - система управления версиями, которая отслеживает историю изменений в процессе совместной работы над проектами.

## Подготовка программного обеспечения

* Установить *Git* [(перейти на сайт)](https://git-scm.com/downloads) и *Visual Studio Code* [(перейти на сайт)](https://code.visualstudio.com/) 
* Запустить *Visual Studio Code* и терминал
* Проверить версию *Git* с помощью команды ```git --version```

## Подготовка репозитория

* Создать папку в репозитории компьютера
* Перейти с помощью проводника в VSCode в папку
* Инициализировать репозиторий командой ```git init```

## Создание коммитов

### Git add

Для добавления изменений в коммит используется команда ```git add``` и имя файла.

### Отправить коммит 

* ```git commit -m "first commit"``` - комманда для отправка коммита
* ```git commit``` - обращение к **GIT**
* ```-m``` - добавить комментарий

### Посмотреть список коммитов

```git log```

### Перейти к сохранению

* ```git checkout```
* ```git checkout <номер коммита>``` - перейти к определённому изменению
* ```git master``` - перейти к изменению последнего коммита

### Посмотреть изменения репозитория

```git status```
