# LR6
Лабораторная работа №6
## 1. Цель работы
Изучение базовых возможностей системы управления версиями, опыт работы с Git Api, опыт работы с локальным и удаленным репозиторием. 
## 2. Ход работы
1. Задаём имя пользователя и почту

![Скриншот 1.](/scr/scr1.png)

2. Клонируем личный удалённый репозиторий 

![Скриншот 2.](/scr/scr2.png)

3. Добавляем файл через интерфейс GitHub и подтягиваем изменения в локальный репазиторий

![Скриншот 3.](/scr/scr3.png)

4. Получаем историю операций для каждой из веток

![Скриншот 4.](/scr/scr4.png)

5. Смотрим последние изменения

![Скриншот 5.](/scr/scr5.png)

6. Выполняем слияние в ветку master

![Скриншот 6.](/scr/scr6.png)

7. Удаляем побочную ветку

![Скриншот 7.](/scr/scr7.png)

8. Делаем изменения и фикисруем их, оставляя комментарии несколько раз

![Скриншот 8.](/scr/scr8.png)

9. Делаем откат коммита

![Скриншот 9.](/scr/scr9.png)

10. Создаём ветку для отчёта

![Скриншот 10.](/scr/scr10.png)

## 3. Лог команд
Перечень использлванных команд:

`  git config --global user.name "4319 Кошев Т.С." `

` git config --global user.email "timonk23@yandex.ru"`

` git clone https://github.com/Jaaames0/LR6.git`

` cd LR6`

` git pull`

` git log --graph`

` git log`

` git merge origin/branch1`

` git add mergefile.txt `

` git commit -m "Разрешение конфликта"`

` git commit`

` git merge origin/branch1`

` git push origin --delete branch1`

` git add .`

` git commit -m "Изменение 1"`

` git add .`

` git commit -m "Изменение 2"`

` git add .`

` git commit -m "Изменение 3"`

` git reset --hard HEAD~`

` git branch report`

` git push --set-upstream origin report`

` git log --pretty=format:"%h %ad %an %s" --graph --date=short`

## 4. История операций в форматированном видел

![Скриншот 11.](/scr/scr11.png)

## 5. Вывод
Были изучены базовые возможности системы управления версиями, получен опыт работы с Git Api, опыт работы с локальным и удаленным репозиторием. 
