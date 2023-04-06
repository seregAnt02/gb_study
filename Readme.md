# Инструкций для работы с Git  и удаленными репозиториями

## Что такое Git?
Git - это одна из реализаций распределенных систем
контроля версий, имеющая как локальные, так и удаленные респозиторий. Является самой популярной реализацией систем контроля версийв мире.
## Подготовка репозитория
Для создания репозитория необходимо выполнит команду *git init* в папке с репозиторием и  у Вас создаться репозиторий (появится скрытая папка -git)

## Git add
Для добавления изменений в коммит используется команда
*git add*. Чтобы использовать команду *git add* напишите
*git add <имя файла>*

## Просмотор состояния репозитория
Для того, чтобы посмотреть состояние репозитория
используется команда *git status*. Для этого необходимо
в папке с репозиторием написать *git status*, и вы
увидите были ли изменения в файлах, или их не было.

## Создание коммитов
Для того, чтобы создать коммит(сохранение) необходимо выполнить команду *git commit*. Выполняется она так:
*git commit -m <имя фала>*

## Переключаться между ветками можно такой командой:
*git checkout <название_ветки>*

## Просмотр историю ветки:
*git log*

## Для того, чтобы создать новую ветку вводим:
*git branch <название_ветки>*
### или вот так
*git checkout -b <название_ветки>*

## Переключаться между ветками можно такой командой:
*git checkout <название_ветки>*

## Таким же образом, можно отправить любую другую ветку
### После того, как вы завершили работу над своей задачей, ветку можно слить в master . 
### Для этого нужно переключиться в ветку master и выполнить следующую команду:

## Переключаемся в master:
git checkout master

## Обновляем локальную ветку с сервера:
git pull origin master

## Делаем merge вашей ветки, в ветку в которой вы находитесь:
git merge <название_ветки>

## Другие пользователи не увидят вашу ветку, пока она не будет отправлена на удаленный репозиторий. 
### Поэтому, после того как вы слили все изменения в master , нужно отправить их в GitHub.
### Для этого обязательно нужно находиться в ветке master :
*git checkout master*

## Отправляем наши изменения в GitHub:
*git push origin master*

## Таким же образом, можно отправить любую другую ветку:
*git checkout <название_ветки>*
*git push origin <название_ветки>*


## Просмотреть изменения относительно двух веток можно командой: 
*git diff*. Выполняется она так:
*git diff <исходная_ветка> <целевая_ветка>*

## Удалить ненужную ветку:
*git branch -d <название_ветки>*

## Спаравка по всем коммандам:
*git help*
### или по конкретной команде:
git help <название_команды>

## Как его скопировать обратно себе на компьютер
*git clone <адрес_репозитория>*

### Адрес картинки: 
https://habrastorage.org/r/w1560/getpro/habr/upload_files/574/bb2/a87/574bb2a8719a01dad2f63e803f550a66.png



