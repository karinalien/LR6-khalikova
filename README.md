# Лабораторная работа №6
**Тема: СИСТЕМА КОНТРОЛЯ ВЕРСИЙ**

## Цель лабораторной работы: 
изучение базовых возможностей системы управления версиями, опыт работы с Git Api, опыт работы с локальным и удаленным репозиторием.

## Ход работы:

### 1.	Создать аккаунт на сайте GitHub. Установить Git (https://git-scm.com/). После установки настроить клиент git, введя имя пользователя (Группа Фамилия И.О.) и email. 

Аккаунт и настройка клиента уже были сделаны до начала работы над лабораторной работой, поэтому пропущу этот момент.

### 2.	Сделать копию в личное хранилище из https://github.com/Kurtyanik/LR6/ (Fork).

Копия была выполнена при помощи перехода в ветку (fork) и создания новой ветки (своей собственной) с названием LR6-khalikova.

 <div align="center">
	 <img src="https://github.com/karinalien/LR6-khalikova/blob/OTCHET6/screenshots/1.png" alt="Рисунок 1 – Создание копии в личное хранилище">
 </div>
	
### 3.	Клонировать свой личный удалённый репозиторий на компьютер. 

Репозиторий был склонирован в папку (C:\Users\karina\Desktop\study\op) при помощи команды git clone и ss ключа,
так как я ранее использовала его для проекта и он является более безопасным (хоть и в данном задании не особо играет роли безопасность). 

<div align="center">
	 <img src="https://github.com/karinalien/LR6-khalikova/blob/OTCHET6/screenshots/2.png" alt="Рисунок 2 – Клонирование репозитория">
 </div>
 
### 4.	Добавить файл через интерфейс GitHub. Подтянуть изменения в локальный репозиторий. Работу продолжать локально. 

При нажатии Add file – Create new file добавлен новый файл с расширением .py. Изменения были подтянуты в локальный
репозиторий при помощи перехода в папку, где находится репозиторий и команды git pull origin.

<div align="center">
	<img src="https://github.com/karinalien/LR6-khalikova/blob/OTCHET6/screenshots/3.png" alt="Рисунок 3 – Создание нового файла">
</div>
<br/>
<div align="center">
	<img src="https://github.com/karinalien/LR6-khalikova/blob/OTCHET6/screenshots/4.png" alt="Рисунок 4 – Обновление изменений">
 </div>
 
### 5.	Получить историю операций для каждой из веток. 

Получение истории операций при помощи git log.

<div align="center">
	<img src="https://github.com/karinalien/LR6-khalikova/blob/OTCHET6/screenshots/5.png" alt="Рисунок 5 – история коммитов">
 </div>
 
### 6.	Просмотреть последние изменения. 

<div align="center">
	<img src="https://github.com/karinalien/LR6-khalikova/blob/OTCHET6/screenshots/6.png" alt="Рисунок 6 – Последнее внесенное изменение">
 </div>
 
### 7.	Выполнить слияние в ветку master, разрешив конфликт (можно использовать специальные редакторы или графический интерфейс git). 

<div align="center">
	<img src="https://github.com/karinalien/LR6-khalikova/blob/OTCHET6/screenshots/7.png" alt="Рисунок 7 – Создание новой ветки">
 </div>
 <br/>
 <div align="center">
	 <img src="https://github.com/karinalien/LR6-khalikova/blob/OTCHET6/screenshots/8.png" alt="[Рисунок 8 – Слияние веток">
 </div>
 
### 8.	Удалить побочную ветку после успешного слияния. 

<div align="center">
	<img src="https://github.com/karinalien/LR6-khalikova/blob/OTCHET6/screenshots/9.png" alt="Рисунок 9 – Удаление второй ветки">
 </div>


### 9.	Сделать изменения и зафиксировать их, оставляя комментарии, несколько раз. 

Было создано 3 коммита, в каждом создание/изменение файлов.

<div align="center">
	<img src="https://github.com/karinalien/LR6-khalikova/blob/OTCHET6/screenshots/10.png" alt="Рисунок 10 – Создание новых коммитов">
 </div>
 
### 10.	Сделать откат коммита. 

Был сделан откат коммита при помощи git reset. 

<div align="center">
	<img src="https://github.com/karinalien/LR6-khalikova/blob/OTCHET6/screenshots/11.png" alt="Рисунок 11 – Откат коммита">
 </div>
 
### 11.	Создать ветку для отчёта. 

<div align="center">
	<img src="https://github.com/karinalien/LR6-khalikova/blob/OTCHET6/screenshots/12.png" alt="Рисунок 12 – Новая ветка для отчета">
 </div>
 
### 12.	Получить историю операций в форматированном виде. Добавить её в отчёт и сделать финальную фиксацию изменений. 

- %h — сокращённый хеш коммита
- %an — имя автора коммита
- %ar — время, прошедшее с момента коммита
- %s — комментарий коммита
<br/>
<div align="center">
	<img src="https://github.com/karinalien/LR6-khalikova/blob/OTCHET6/screenshots/13.png" alt="Рисунок 13 – История операций">
 </div>

## Лог команд
```
	git clone
	git pull
	git add
	git commit -m
	git push
	git show
	git branch -b
	git checkout
	git log
	git merge
	git branch -d
	git reset
	git revert HEAD
	git push origin
	git log --pretty=format:"%h - %an, %ar : %s" –date=short
```

<div align="center">
	<img src="https://github.com/karinalien/LR6-khalikova/blob/OTCHET6/screenshots/14.png" alt="Рисунок 14">
 </div>

 <div align="center">
	<img src="https://github.com/karinalien/LR6-khalikova/blob/OTCHET6/screenshots/15.png" alt="Рисунок 15">
 </div>

 <div align="center">
	<img src="https://github.com/karinalien/LR6-khalikova/blob/OTCHET6/screenshots/16.png" alt="Рисунок 16">
 </div>

<div align="center">
	<img src="https://github.com/karinalien/LR6-khalikova/blob/OTCHET6/screenshots/17.png" alt="Рисунок 17">
 </div>

 <div align="center">
	<img src="https://github.com/karinalien/LR6-khalikova/blob/OTCHET6/screenshots/18.png" alt="Рисунок 18">
 </div>

# Выводы 
Мы научились работать с системой контроля версий Git: изменять файлы,
создавать и откатывать коммиты, смотреть изменения, просматривать ветки и добавлять новые.



