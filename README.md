# Преимущества использования системы контроля версий и сервиса GitHub.com 

* удалённые репозитории могут использоваться для совместной работы;
* хранение истории измений;
* видимость и авторство каждого изменения;
* «резервная копия» проекта.

## Начало работы
Установка GIT на локальный компьютер

Создание локального репозитория для проекта

Подключение удалённого репозитория к локальному


## Подготовка:
* Установить GIT на локальный компьютер:
     * Windows: https://git-scm.com/download/win
     
     * Mac: https://git-scm.com/download/mac
     * Другие версии Linux: https://git-scm.com/download/linux
     

* Создайте пустой репозиторий на 
[GITHub](https://github.com/)

## Установка и запуск
### На локальном компьютере в Git Bash

1. *Задать имя пользователя и email:*
 
       git config --global user.name "Vasya Pupkin"

       git config --global user.email vasya@localhost



1. *Задать редактор:*

       git config --global core.editor nano

1.  *Создать репозиторий:*

       
        git init Initialized empty Git repository in C:/project/.git/  
             
1. *Добавить файлы в «список отслеживаемых»*

         git add index.html

1. *Фиксация изменений в файлах проекта*

        git commit
1. *Отправить изменения в удалённый репозиторий*   

        git push 
        


