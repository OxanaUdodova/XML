# XML
 1. Создать внешний репозиторий c названием XML.
Создала репозиторий https://github.com/OxanaUdodova/XML

 2. Клонировать репозиторий XML на локальный компьютер.
 git clone https://github.com/OxanaUdodova/XML.git

 3. Внутри локального XML создать файл “new.xml”.
cd XML >> touch new.xml

 4. Добавить файл под гит.
 git add new.xml
 git status

 5. Закоммитить файл.
git config --global user.email "zaraza06121986@mail.ru"
git commit -m "add new.xml"

 6. Отправить файл на внешний GitHub репозиторий.
git push

 7. Отредактировать содержание файла “new.xml” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате XML.

nano new.xml

<?xml version="1.0" encoding="UTF-8" ?>
<name>Udodova Oxana Sergeevna</name>
<age>35</age>
<pet>1</pet>
<salary>50000</salary>

Сtrl+o (Сохранить изменения) >> Сtrl+x (Выйти)

 8. Отправить изменения на внешний репозиторий.
 git add new.xml >>  git commit -m "modify new.xml" >> git push

 9. Создать файл preferences.xml
touch preferences.xml

 10. В файл preferences.xml добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате XML.

nano preferences.xml

<?xml version="1.0" encoding="UTF-8" ?>
<preferences>
    <favor_film>Harry Potter</favor_film>
    <favor_serial>none</favor_serial>
    <favor_food>none</favor_food>
    <favor_season>spring</favor_season>
    <country>Italy</country>
</preferences>

Сtrl+o (Сохранить изменения) >> Сtrl+x (Выйти)

 11. Создать файл sklls.xml добавить информацию о скиллах которые будут изучены на курсе в формате XML

nano sklls.xml 

<?xml version="1.0" encoding="UTF-8" ?>
<skillsCourse>
    <skill>Базовая теория (Что такое тестирование, багрепорты, документация, виды, методы, направления тестирования и т.п.) SDLC, STLC</skill>
    <skill>Что такое клиент-серверная архитектура</skill>
    <skill>HTTP Методы запросов на сервер</skill>
    <skill>Коды ответов HTTP сервера</skill>
	.....

</skillsCourse>

Сtrl+o (Сохранить изменения) >> Сtrl+x (Выйти)

 12. Сделать коммит в одну строку.
git add preferences.xml skills.xml (или git add .) >> git commit -m "add 2 file"


 13. Отправить сразу 2 файла на внешний репозиторий.
git push

 14. На веб интерфейсе создать файл bug_report.xml.
Add file >> Create new file

 15. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
Commit changes

 16. На веб интерфейсе модифицировать файл bug_report.xml, добавить баг репорт в формате XML.

<?xml version="1.0" encoding="UTF-8" ?>
<bug_report>
    <Bug_id>2</Bug_id>
    <Title>Add widget” button is not working on device</Title>
    <Severity>high</Severity>
    <Priority>low</Priority>
    <Environment>Honor 8x JSN-L21 Android 10.0.0260</Environment>
    <Precondition>Clear the app from running</Precondition>
    <Step_To_Reproduce>1)Open app; 2)Click “Add Widget” button</Step_To_Reproduce>
    <Actual_Result>Nothing happens, button is not working, widget is not created on any page</Actual_Result>
    <Expected_Result>Widget creation window appears/widget created</Expected_Result>
</bug_report>

 17. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
Commit changes

 18. Синхронизировать внешний и локальный репозиторий XML
 git pull
