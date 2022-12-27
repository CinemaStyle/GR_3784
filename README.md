# Инструкция git
```
```

0. [Инициализация](##Инициализация)
1. [Проверка статуса](##Проверка-статуса)
2. [Добавление файла в git](##Добавление-файла-в-git)
3. [Подтверждение](##Подтверждение)
4. [Просмотр журналов](##Просмотр-журналов)
5. [Работа с ветками](##Работа-с-ветками)
6. [Переключения](##Переключения)
7. [Просмотр разницы текущего состояния и git](##Просмотр-разницы-текущего-состояния-и-git)
8. [Слияние веток](##Слияние-веток)
9. [Клонирование удаленного репозитория](##Клонирование-удаленного-репозитория)
10. [Вытянуть изменения из удаленного репозитория](##Вытянуть-изменения-из-удаленного-репозитория)
11. [Записать изменения в удаленный репозиторий](##Записать-изменения-в-удаленный-репозиторий)
12. [Работа с удаленными ветками](##Работа-с-удаленными-ветками)
13. [Привязать пустой репозиторий к локальному репозиторию](##Привязать-пустой-репозиторий-к-локальному-репозиторию)
14. [Fork и pull request](##Fork-и-pull-request)
15. [Котик](##Котик)

## Инициализация

**git init**

## Проверка статуса

**git status**

## Добавление файла в git

* **git add readme.md** - добавить файл
* **git add .**  - добавить все
* __git add `*/*`__ - добавить все подпапки
* __git add *.jpg__ - добавить jpg файлы

## Подтверждение

* **git commit** - создать коммит
* **git commit -m "readme.md"** - создать коммит сразу с комментарием
* **git commit -am "_Комментарий_"** - добавить в git и закоммитить, для файлов которые уже добавлялись в git

## Просмотр журналов

* **git log** - просмотр журнала
* **git log --oneline** - просмотр журнала в одну строку
* **git log --graph** - просмотр журнала в виде графа
* **git log --all** - просмотр журнала всех ветвей
* **git log --oneline --graph --all** - просмотр журнала в виде графа с краткими записями все ветви

## Работа с ветками

* **git branch** - список веток
* **git branch dev** - создать ветку dev
* **git branch -d dev** - удалить ветку  

## Переключения

* **git checkout <_первые 4 цифры коммита_>** - переход к коммиту
* **git checkout master** - переключиться на ветку
* **git checkout -b dev** - создать новую ветку и переключиться

## Просмотр разницы текущего состояния и git

**git diff**

## Слияние веток

**git merge div**

## Клонирование удаленного репозитория

* **git clone https://github.com/nata44845/homework3.git** - клонировать
* **git clone https://github.com/nata44845/homework3.git** gr_3784H3 - клонировать в определенную папку

## Вытянуть изменения из удаленного репозитория

**git pull**

## Записать изменения в удаленный репозиторий

* **git push**
* **git push --set-upstream origin dev** - записать в новую ветку 

## Работа с удаленными ветками

* **git branch --all** - посмотреть удаленные ветки
* **git checkout dev** - если есть удаленная ветка, создаст ее локально и вытянет данные

## Привязать пустой репозиторий к локальному репозиторию

* **git remote add origin https://github.com/nata44845/Test.git**
* **git branch -M main**
* **git push -u origin main**

## Fork и pull request

1. Fork - создать копию на аккаунте gitHub
2. Clone - клонировать
3. Создать новую ветку dev
4. Сделать изменения, выполнить add, выполнить commit
5. git push --set-upstream origin dev
6. compare&pull request

## Котик

![Котик](1.jpg)
