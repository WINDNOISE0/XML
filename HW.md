XML

1. Создать внешний репозиторий c названием XML. +
***
2. Клонировать репозиторий XML на локальный компьютер. clone
***
3. Внутри локального XML создать файл “new.xml”. 

cd XML 

git init 

cat > new.xml
***
4. Добавить файл под гит. 

git add .
***
5. Закоммитить файл. 

git commit -m "Created new file XML"
***
6. Отправить файл на внешний GitHub репозиторий.

git remote add origin https://github.com/WINDNOISE0/XML.git

git branch -M main

git push -u origin main
***
7. Отредактировать содержание файла “new.xml” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате XML.
 # nano new.xml
```
<xml>
    <name>Yaroslav</name>
    <surname>Yaroslavov</surname>
    <patronymic>Yaroslavovich</patronymic>
    <age>25</age>
    <count_home_pets>1</count_home_pets>
    <future_expected_salary>1000$ +</future_expected_salary>
</xml>
```
***
8. Отправить изменения на внешний репозиторий. 

git push -u origin main & login + key
***
9. Создать файл preferences.xml

cat > preferences.xml
***
10. В файл preferences.xml добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате XML.
 # nano preferences.xml
```
<xml>
    <favorite_movie>fear and loathing in las vegas</favorite_movie>
    <favorite_TV-show>none</favorite_TV-show>
    <favorite_food>delicious</favorite_food>
    <favorite_season>summer</favorite_season>
    <country_which_I_want_visit>Spain</country_which_I_want_visit>
</xml>
```
***
11. Создать файл sklls.xml добавить информацию о скиллах которые будут изучены на курсе в формате XML
 # nano sklls.xml
```
<xml>
    <will_studys_skills>
        <skill>Bash terminal</skill>
        <skill>Git system of control version</skill>
        <skill>SQL</skill>
        <skill>Postman</skill>
        <skill>Jmeter</skill>
        <skil>AndroidStudio</skil>
        <skill>Charles</skill>
        <skill>DB Browser</skill>
        <skill>Fiddler</skill>
    </will_studys_skills>
</xml>
```
***
12. Сделать коммит в одну строку. 

git commit -a -m "Add two files"
***
13. Отправить сразу 2 файла на внешний репозиторий. 

git push -u origin main
***
14. На веб интерфейсе создать файл bug_report.xml. +
***
15. Сделать Commit changes (сохранить) изменения на веб интерфейсе. +
***
16. На веб интерфейсе модифицировать файл bug_report.xml, добавить баг репорт в формате XML. +
```
<xml>
    <number_ID>1</number_ID>
    <Title>Link 'create new account' Global Menu isn't open when clicking</Title>
    <Seveity>critical</Seveity>
    <Priority>hight</Priority>
    <STR>
        <one>Open link</one>
        <two>Tap to button 'create new account'</two>
    </STR>
    <Expected_Result>Registration's window is opened</Expected_Result>
    <Actual_Result>nothing happens, link isn't opened</Actual_Result>
</xml>
```
***
17. Сделать Commit changes (сохранить) изменения на веб интерфейсе. +
***
18. Синхронизировать внешний и локальный репозиторий XML 

git pull
***
