## HW_GitHub_1.3
1. Создать внешний репозиторий c названием TXT. - done
2. Клонировать репозиторий TXT на локальный компьютер. -	
git clone https://github.com/AnatolyTyurin/Ksendzov_TXT.git
3. Внутри локального TXT создать файл “new.txt”. - touch new.txt
4. Добавить файл под гит. - git add new.txt
5. Закоммитить файл. - git commit -am "add new txt file"
6. Отправить файл на внешний GitHub репозиторий. – git push
7. Отредактировать содержание файла “new.txt” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате TXT. -

vim new.txt

    Person: Tyurin Anatoly;
    Age: 35;
    Pets: no pets;
    Desired salary: USD 1000.

8. Отправить изменения на внешний репозиторий. – 
Git commit –am “add text to new.txt” && git push
9. Создать файл preferences.txt - touch preferences.txt
10. В файл preferences.txt” добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате TXT. -

vim preferences.txt
    
    Favourite_film: “Existenz”;
    Favourite_TV_series: “The Sopranos”;
    Favourte_food: mama's homemade food;
    Favourite_season: summer;
    Desired country to visit: State of Maine, the USA
11. Создать файл sklls.txt добавить информацию о скиллах которые будут изучены на курсе в формате TXT – vim skills.txt

- Basic testing theory (QA, QC, testing, bug reports, testing documentation, types and methods of testing, SDLC, STLC);
- HTTP (client-server architecture, HTTP methods of requests, HTTP server response codes, Structures of HTTP requests and responses);
- Data interchange format (JSON, XML);
- API (Postman, JS, API autotests);
- Sniffing (Charles, Fiddler);
- DevTool (Google Chrome, FireFox);
- VPN (General info);
- Mobile testing (IOS, Android, XCode, Android Studio, ADB, Proxy and vpn settings on iOS and Android, Sniffing traffic using Charles and Fiddler on IOS and Android);
- Linux Terminal (Copying, creating, viewing, moving files and etc.);
- Linux Terminal (Base of Bash scripting, Access to remote servers);
- SQL (Create, Delete, Drop, Insert Into, Select, From, Where, Join);
- SQL (PostgreSQL, Redis);
- Load testing (Jmeter);
- Development methodology (SCRUM);
- Programming language (Base of Python).
12. Сделать коммит в одну строку. –
git add . && git commit -am "add text to preferences and skills txt files"
13. Отправить сразу 2 файла на внешний репозиторий. – git push
14. На веб интерфейсе создать файл bug_report.txt. - done
15. Сделать Commit changes (сохранить) изменения на веб интерфейсе. - done
16. На веб интерфейсе модифицировать файл bug_report.txt, добавить баг репорт в формате TXT.

Bug N: 1

    Title: Lesson start screen image fails to load when open the application from the background and return from Lesson module
	STR:
	1. Open the application
	2. Tap any item lesson
	3. Tap [Start]
	4. Send the application to the background
	5. Open the application
	6. Tap return button (or swipe right-to-left / left-to-right)
	AR: Lesson start screen image fails to load
	ER: Lesson start screen image is displayed
	Environment: Xiaomi Mi9, Android 10
	Severity: Major
	Priority: N/A
	Author: Anatoly Tyurin
17. Сделать Commit changes (сохранить) изменения на веб интерфейсе. - done
18. Синхронизировать внешний и локальный репозиторий TXT – git pull
