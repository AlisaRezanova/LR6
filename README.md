# Лабораторная работа №6
## 1. Цель работы
Изучение базовых возможностей системы управления версиями, опыт работы с Git Api, опыт работы с локальным и удаленным репозиторием.
## 2. Ход выполнения работы
### 1. Создание копии репозитория
На данном этапе работы создается форк репозитория.
![Рисунок 1](/PrtSC/1.png)
### 2. Настройка клиента git
Ввод имени пользователя, а также email.
![Рисунок 2](/PrtSC/2.png)
### 3. Клонирование личного удаленного репозитория на компьютер
Создание папки локального репозитория на компьютере.
![Рисунок 3](/PrtSC/3.png)
### 4. Добавление файла через интерфейс GitHub
Помимио добавления файла New_file на данном этапе были также подтянуты изменения в локальный репозиторий.
![Рисунок 4](/PrtSC/4.png)
### 5. Получение истории операций для каждой из веток
Для получения истории операций также была применена команда на GitBash.
![Рисунок 5](/PrtSC/5.png)
### 6. Просмотр последних изменений
Был сделан просмотр последних 3 изменений.
![Рисунок 6](/PrtSC/6.png)
### 7. Выполнение слияния в ветку master
В ходе данного этапе появился конфликт, который был решен путем оставления изменений только из текущей ветки и удалением других изменений.
![Рисунок 7](/PrtSC/7.png)
![Рисунок 8](/PrtSC/7.1.png)
### 8. Удаление побочной ветки
После успешного слияния удаляется побочная ветка branch1.
![Рисунок 9](/PrtSC/8.png)
### 9. Добавление изменений, а также их последующая фиксация
Были выполнены 3 изменения файла New_file, а также поочередное закомментирование изменений.
![Рисунок 10](/PrtSC/9.png)
### 10. Откат коммита
Был проделан один откат последнего коммита, а также дальнейшее изменение его на другой коммит.
![Рисунок 11](/PrtSC/10.png)
### 11. Создание ветки для отчета
Была создана новая ветка для отчета branch2.
![Рисунок 12](/PrtSC/11.png)
## 3. Лог команд
```
git clone https://github.com/AlisaRezanova/LR6
git config --global user.name "4319 Резанова А.Р."
git config --global user.email alsa2002g@gmail.com
cd LR6
git log -3
git merge origin/branch1
git reset --soft HEAD~1
git push origin --delete branch1
git add .
git commit -m
git status
touch README.md
git checkout -b branch2
ls
git push origin branch2
git push origin master
```
## 4. История операций в форматированном виде
Добавление истории операций в форматированном виде.
![Рисунок 13](/PrtSC/12.png)
## 5. Выводы
Изучили базовые возможности системы управления версиями, получили опыт работы с Git Api, а также опыт работы с локальным и удаленным репозиторием.
