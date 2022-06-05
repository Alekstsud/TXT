# TXT

 1. Создать внешний репозиторий c названием TXT.       New
                                                       Create repository

 2. Клонировать репозиторий TXT на локальный компьютер.     git clone https://github.com/Alekstsud/TXT.git

 - cd TXT
 3. Внутри локального TXT создать файл “new.txt”.      touch new.txt

 4. Добавить файл под гит.     git add . new.txt
       
 5. Закоммитить файл.         git commit -m "add txt"

 6. Отправить файл на внешний GitHub репозиторий.     git push

 7. Отредактировать содержание файла “new.txt” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате TXT.
 
Вносим изменения: vim new.txt 
нажать клавишу "i" ввести текст

Firstname: Aliaksandr
Surname: Tsudzila
Age: 32
Pet Count: 0
Desired Salary: 1000$	

Cохранить и выйти: "esc" ":wq"

8. Отправить изменения на внешний репозиторий.   git commit -m "edit new.txt"
                                                 git push

 9. Создать файл preferences.txt          touch preferences.txt

 10. В файл preferences.txt” добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате TXT.

Вносим изменения: vim preferences.txt
нажать клавишу "i" ввести текст

Favorite Movie: Star Wars
Favorite Serial: The Big Bang Theory
Favorite Food:  Lasagna
FavoiteSeason:  Summer
Country Would Like To Visit: China

Cохранить и выйти: "esc" ":wq"

 11. Создать файл skills.txt добавить информацию о скиллах которые будут изучены на курсе в формате TXT

Создаём файл: touch skills.txt
Вносим изменения vim skills.txt
нажать клавишу "i" ввести текст

                1) Basic theory (What is testing, bug reports, documentation, types, methods, testing areas, etc.) SDLC, STLC,
		2) HTTP server response codes,
		3) Structures of HTTP Requests and Responses,
		4) Client-Server Architecture,
		5) HTTP Server Request Methods,
		6) JSON, XML,
		7) API testing in Postman (JS, API autotests),
		8) Reading logs from an external server,
		9) Sniffing http web traffic with Charles and Fiddler,
		10) Web Browser Dev Tools (Google Chrome, FireFox),
		11) VPN,
		12) Mobile testing,
		13) iOS, Android, guidelines,
		14) Building iOS Apps with Xcode,
		15) Building Android Applications with Android Studio,
		16) ADB,
		17) Setting up proxy and vpn on iOS and Android,
		18) Sniffing of mobile traffic via Charles and Fiddler on iOS and Android,
		19) Terminal,
		20) Bash scripting,
		21) Access to remote servers,
		22) SQL (Create, Delete, Drop, Insert Into, Select, From, Where, Join),
		23) Postgres database (installation, configuration and use),
		24) Non-relational Redis database (installation, configuration and use),
		25) Load Testing in Jmeter,
		26) Scrum Development Methodology,
		27) Python (Learning the basics. Creating a client-server application)


Cохранить и выйти: "esc" ":wq"

 12. Сделать коммит в одну строку.              git commit -m "add new txt"

13. Отправить сразу 2 файла на внешний репозиторий.         git add preferences.txt skills.txt
                                                            git commit -m "add new.txt"
                                                            git push
              
 14. На веб интерфейсе создать файл bug_report.txt.         - Add file
							    - Create new file
							    - Commit new file
  
 15. Сделать Commit changes (сохранить) изменения на веб интерфейсе.   -edit this file
                                                                       в строке Commit changes написать новый Commit
                                                                       Commit changes
 
 16. На веб интерфейсе модифицировать файл bug_report.txt, добавить баг репорт в формате TXT.
 
ID: 
Title: 
Project: 
STR:	
		1. 
		2. 
Enviroment:
		OS: 
		Browser: 
Component: 
Build: 
Actual result: 
Expected result: 
Severity: 
Priority: 
Status: 
Author: 
Sign to: 
Attachments: 

 17. Сделать Commit changes (сохранить) изменения на веб интерфейсе.    edit this file
                                                                        в строке Commit changes написать новый Commit
                                                                        Commit changes 
 
 18. Синхронизировать внешний и локальный репозиторий TXT       git pull
