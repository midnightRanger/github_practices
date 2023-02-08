<h1 align="center"> Практическая работа №1 </h1>
<h3 align="center"> Тема: Создание аккаунта Github </h3>
<p> Цель: Создание и настройка аккаунта для системы управления версиями Git. </p>
</br>
<p> №1. Создание аккаунта </p>
Для создания нового аккаунта в GitHub необходимо перейти на ресурс github.com, затем осуществить редирект на страницу авторизации. На странице авторизации необходимо перейти на регистрацию, нажав на кнопку "Create an account"
<div align="center"> 
<img src="https://github.com/midnightRanger/github_practices/blob/first_practice/images/pic1.png?raw=true">
</div>
<p color="grey" style="font-size: 12px" align="center"> Рисунок 1 - Страница авторизации </p>

Далее необходимо заполнить поле с электронной почтой 

<div align="center"> 
<img src="https://github.com/midnightRanger/github_practices/blob/first_practice/images/pic_3.jpg?raw=true">
</div>
<p color="grey" style="font-size: 12px" align="center"> Рисунок 2 - Ввод электронной почты </p>


<div align="center"> 
<img src="https://github.com/midnightRanger/github_practices/blob/first_practice/images/pic_4.jpg?raw=true">
</div>
<p color="grey" style="font-size: 12px" align="center"> Рисунок 3 - Ввод пароля </p>

Затем нужно проинициализировать локальный git-репозиторий. Для этого нужно перейти в папку с проектом и открыть ее через Git Bash. В открывшемся терминале нужно прописать команду <p style="font-style: italic"> > git init </p> 

<div align="center"> 
<img src="https://github.com/midnightRanger/github_practices/blob/first_practice/images/pic_5.jpg?raw=true">
</div>
<p color="grey" style="font-size: 12px" align="center"> Рисунок 4 - git init </p>

Далее необходимо добавить отслеживание всех файлов в репозитории. Для этого нужно прописать команду: <p style="font-style: italic"> > git add * </p>
Для фиксации коммита, нужно прописать команду : <p style="font-style: italic">  > git commit -m "Сообщение" </p> 

<div align="center"> 
<img src="https://github.com/midnightRanger/github_practices/blob/first_practice/images/pic_6.jpg?raw=true">
</div>
<p color="grey" style="font-size: 12px" align="center"> Рисунок 5 - git add / git commit </p>

Затем, нужно создать удаленный репозиторий на аккаунте Github. Для этого нужно перейти во вкладку "Профиль" -> "Репозитории" и нажать на кнопку "New" 

<div align="center"> 
<img src="https://github.com/midnightRanger/github_practices/blob/first_practice/images/pic_7.jpg?raw=true">
</div>
<p color="grey" style="font-size: 12px" align="center"> Рисунок 6 - Создание удаленного репозитория </p>

На вкладке создания можно отредактировать название репозитория, его доступность и выбрать тип лицензии.  

<div align="center"> 
<img src="https://github.com/midnightRanger/github_practices/blob/first_practice/images/pic_8.jpg?raw=true">
</div>
<p color="grey" style="font-size: 12px" align="center"> Рисунок 7 - Настройка репозитория </p>

После создания удаленного репозитория, нужно подключить локальный репозиторий к нему. Для этого используется команда: <p style="font-style: italic">  > git remote add <название> <ссылка> </p> 

<div align="center"> 
<img src="https://github.com/midnightRanger/github_practices/blob/first_practice/images/pic_9.jpg?raw=true">
</div>
<p color="grey" style="font-size: 12px" align="center"> Рисунок 8 - Подключение удаленного репозитория к локальному </p>


Можно сколько угодно коммитить изменения в проекте, но на удаленном репозитории они не появятся. Для этого используется команда: <p style="font-style: italic">  > git push -u <название удаленного репозитория> <название ветки>  </p> 

<div align="center"> 
<img src="https://github.com/midnightRanger/github_practices/blob/first_practice/images/pic_10.jpg?raw=true">
</div>
<p color="grey" style="font-size: 12px" align="center"> Рисунок 9 - Добавление изменений проекта в удаленный репозиторий </p>

<h3> Заключение </h3>

В ходе выполнения данной практической работы были усвоены навыки по работе с системой управления версиями Git. Был создан аккаунт на сервисе Github, проинициализирован локальный репозиторий, а затем он был связан с удаленным, куда были добавлены изменения. 









  
