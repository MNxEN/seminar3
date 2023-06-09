# **Инструкция по работе с Git**

Система контроля версий Git нужна для ...

## Создание локального репозитория

Чтобы создать (инициализировать) новый локальный репозиторий нужно в терминале (находясь в нужной папке) ввести команду:

    git init

## Проверка состояния репозитория


 - git init
 - git status
 - git add \<filename>
 - git add .
 - git commit
 - git commit -m "message"
 - git commit -a
 - git commit -am "message"
 - git log
 - git log --oneline
 - git log --all
 - git log --oneline --all
 - git checkout \<hash>
 - git checkout master
 - git diff
 - git diff \<hash1> \<hash2>

 # *Семинар 1. Домашнее задание*

 ## *Система контроля версий Git* нужна для ведения и отслеживания истории изменений файлов проекта в репозитории (хранилище проекта) с возможностью возврата к ранним версиям состояния проекта.

 ## *Инициализация репозитория*

 Для инициализации текущего каталога в качестве репозитория (хранилища проекта) нужно ввести команду:

    git init

## *Проверка состояния репозитория*

Для проверки текущего состояния репозитория нужно ввести команду:

    git status

## *Добавление изменений в индекс*

Для добавления изменения конкретного файла в индекс репозитория (подготовка к commit) нужно ввести команду:

    git add <filename>

Для добавления всех изменений в хранилище в индекс репозитория нужно ввести команду:

    git add .

## *Фиксация изменений (сохранение текущей версии проекта)*

Для фиксации выполненных изменений с последующим вводом комментария в редакторе нужно ввести команду:

    git commit

Для фиксации выполненных изменений с одновременным вводом комментария нужно ввести команду:

    git commit -m "message"

Для фиксации выполненных изменений с одновременным добавлением их в индекс (не используя предварительно команду "git add") нужно ввести команду:

    git commit -a

Для фиксации выполненных изменений с одновременным добавлением их в индекс и одновременным вводом комментария нужно ввести команду:

    git commit -am "message"

## *Отображение журнала (истории) фиксаций изменений*

Для отображения журнала фиксаций изменений, выполненных до текущей позиции (версии), нужно ввести команду:

    git log

Для отображения журнала фиксаций изменений, выполненных до текущей позиции (версии), в сокращенной форме нужно ввести команду:

    git log --oneline

Для отображения журнала всех фиксаций изменений (при этом неважно в какой версии вы в данный момент находитесь) в сокращенной форме нужно ввести команду:

    git log --all --oneline

## *Перемещение позиции к ранее сохранненой версии (фиксации изменений)*

Для перехода к ранним версиям проекта (имея имя этой версии или 4 первых символа имени версии) нужно ввести команду:

    git checkout <hash>

Для возврата к основной актуальной версии проекта (вершине веток) нужно ввести команду:

    git checkout master

## *Отображение выполненных изменений и различий версий*

Для отображения выполненных изменений не добавленных в индекс нужно ввести команду:

    git diff

Для отображения различий между конкретными версиями, зная их имена нужно ввести команду:

    git diff <hash1> <hash2>


# Семинар 2

![emblem](git.jpg)

## Ветвления в Git

Ветвления нужны для ...

### Просмотр существующих веток

Для просмотра имеющихся веток используется команда:

    git branch
### Создание новой ветки

Для создания новой ветки используется команда:

    git branch <branch_name>

### Переключение между ветками

Для того чтобы переключиться между ветками используется команда:

    git checkout <branch_name>

### Слияние веток

Для того чтобы влить другую ветку в текущую надо ввести команду:

    git merge <branch_name>


# *Семинар 2. Домашнее задание*

## Ветвления в Git

*Ветвления в Git нужны для удобства решения разных задач по одному проекту. Для каждой задачи или подзадачи лучше создать свою собственную ветку и подветки, чтобы в последующем объединить их в готовый или промежуточный проект*
## Отображение существующих веток

Для просмотра всех существующих веток используется команда:

    git branch

## Создание новой ветки

Для создания новой ветки используется команда:

    git branch <branch_name>

## Переключение между ветками

Для переключения между ветками проекта используется команда:

    git checkout <branch_name>

## Слияние веток

Для объединения другой ветки с текущей используется команда:

    git merge <branch_name>

## Удаленные репозитории

Удаленные репозитории используются для ...

## Связывание локального репозитория с удаленным
