# Git_TXT

## TXT
0. Первоначальная настройка Git с GitHub.
  >git config --global user.name "имя пользователя в GitHub"  
  >git config --global user.email "эл. почта на GitHub"  
  >ssh-keygen -t rsa -C "имя пользователя GitHub"  
  >В GitHub скопировать ssh ключ
1. Создать внешний репозиторий c названием TXT. 
  >Git_TXT 
2. Клонировать репозиторий TXT на локальный компьютер.
  >git clone git@github.com:vv-vasilyev08/Git_TXT.git
3. Внутри локального TXT создать файл “new.txt”.
  >touch new.txt
4. Добавить файл под гит.
  >git add new.txt
5. Закоммитить файл.
  >git commit -m "add first file"
6. Отправить файл на внешний GitHub репозиторий.
  >git push
7. Отредактировать содержание файла “new.txt” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате TXT.
  >cat >> new.txt  
  >ФИО: Лучший Пухляш Неотразимый  
  >Возраст: 22  
  >Количество домашних животных: 5  
  >Будущая желаемая зарплата: 120 000 рублей  
  >CTRL+C  
8. Отправить изменения на внешний репозиторий.
  >git commit -m "changes txt file"  
  >git push
9. Создать файл preferences.txt
  >touch preferences.txt
10. В файл preferences.txt” добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате TXT.
  >cat >> preferences.txt  
  >Любимый фильм: На основе реальных событиях  
  >Любимый сериал: Нету  
  >Любимая еда: Овощное рагу  
  >Любимое время года: Лето  
  >Страна, котору. хотели бы посетить: Не знаю  
  >CTRL+C
11. Создать файл skills.txt добавить информацию о скиллах которые будут изучены на курсе в формате TXT
  >cat >> skills.txt  
  >Linux  
  >Bash  
  >Git  
  >GitHub  
  >API  
  >HTTP/HTTPS  
  >Web testing  
  >Mobile testing  
  >Proxy  
  >VPN  
  >SQL  
  >JMeter  
  >CTRL+C  
12. Сделать коммит в одну строку.
  >git add . ; git commit -m "add skills and preferences"
13. Отправить сразу 2 файла на внешний репозиторий.
  >git push
14. На веб интерфейсе создать файл bug_report.txt.
  >Создать файл в GitHub bug_report.txt
15. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
  >Файл bug_report.txt закоммитить в GitHub
16. На веб интерфейсе модифицировать файл bug_report.txt, добавить баг репорт в формате TXT.
  >Модифицировать в GitHub файл bug_report.txt
17. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
  >Сделать коммит bug_report.txt
18. Синхронизировать внешний и локальный репозиторий TXT
  >git fetch  
  >git pull
