# Посказка по Git

## Добавление имени пользователя
```sh
git config user.name "Darya"
```
## Добавление почты пльзователя
```sh
git config user.email "d130887@tut.by"
```
## Инициализация локального репозитория
```sh
git init 
```
## Получить информацию от git о его текущем состоянии
```sh
git status
```
## Добавить файл к коммиту
```sh
git add
```
## Создание коммита
```sh
git commit -m"message"
```
## Вывод на экран всех коммитов с хеш-кодами
```sh
git log
```
## Переход оот одного коммита к другому
```sh
git checkout
```
## Вернуться к актуальному состоянию и продолжить работу
```sh
git checkout master
```
## Увидеть разницу между текущим файлом и закоммиченным файлом
```sh
git diff
```
## Добавить новую ветку
```sh
git branch имя ветки
```
## Проверить на какой ветке мы находимся
```sh
git branch
```
## Слияние веток
```sh
git merge
```
## Увидеть все изменения в ветках
```sh
git log --graph
```

## Отображение всех веток
```sh
git branch
```
## Перемещение по веткам
```sh
git checkout <имя ветки>
```
## Создание новой ветки
```sh
git branch <имя ветки>
```
## Переименование ветки
```sh
git branch -m {имя ветки}
```
## Копирование репозитория из github
```sh
git clone
```
## Отправка данных на github
```sh
git push
```
## Отправка данных с github
```sh
git pull
```
## Удаление ветки при выгрузке
```sh
git push origin --delete {имя ветки}
```
## Для решения кофликта
```sh
git pull --rebase
```