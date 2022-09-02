# JSON

1. Создать внешний репозиторий с названием JSON
      ```javasript
   https://github.com/svetasts/JSON
     ```
2. Клонировать репозиторий JSON в необходимую папку
   ```javasript
   В GitHub копируем HTTPS code репозитория JSON и в Terminal пишем команду
  
   git clone https://github.com/svetasts/JSON.git
   ```

3. Внутри локального JSON создать файл “new.json”
    ```javasript
    В терминал пишем команду
    vim new.json
    ```
4. Добавить файл под гит
   ```javasript
   git add new.json
   ```
5. Закоммитить файл
   ```javasript
   git commit -m "create preferences.json"
   ```
6.   Отправить файл на внешний GitHub репозиторий
     ```javasript
     git push 
      ```
7. Отредактировать содержание файла “new.json” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате JSON.
   ```javasript{
	"name" : "Sveta",
	"age" : "36",
	"pet" : "1",
	"salary" : "5000"
   }
   ```
8. Отправить изменения на внешний репозиторий.
   ```javasript
     git push 
      ```
9. Создать файл preferences.json
   ```javasript
    В терминал пишем команду
    vim preferences.json
   ```
10. В файл preferences.json добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате JSON.
```javasript
{
	"film" : "dreamers",
	"series" : "twin peaks",
	"food" : "pelmeni",
	"season" : "summer",
	"country" : "America"
}
```
11. Создать файл sklls.json добавить информацию о скиллах которые будут изучены на курсе в формате JSON
    ```javasript
    {
	"1" : "Terminal",
	"2" : "HTTP методы",
	"3" : "DevTools",
	"4" : "Postman",
	"5" : "JS",
	"6" : "SDLC, STLC",
	"7" : JSON, XML"}
    ```
12. Отправить сразу 2 файла на внешний репозиторий
    ```javasript
    git add .
    git commit -m "create -m "preferences.json,skills.json"
    git push
    ```
13. На веб интерфейсе создать файл bug_report.json
    ```javasript
    Add file --> Create new file --> bug_report.json
    ```
14. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
   ```javasript
   Click on "Commit changes"
   ```
15. На веб интерфейсе модифицировать файл bug_report.json, добавить баг репорт в формате JSON.
 ```javasript
 {
   "header" : "name_of_header",
   "steps_to_reproduce" : "1...; 2...; 3...;",
   "project" : "project_1",
   "severity" : "minor",
   "priority" : "medium"
}
   ```
16.  Сделать Commit changes (сохранить) изменения на веб интерфейсе.
 ```javasript
 Click on "Commit changes"
   ```
17. Синхронизировать внешний и локальный репозиторий JSON
 ```javasript
 В Terminal ввести комнаду 
 git merge - синхронизация
 git fetch - проверка изменений на внешнем репозитории
   ```

# XML
1. Создать внешний репозиторий c названием XML
    ```javasript
    https://github.com/svetasts/XML
     ```
2. Клонировать репозиторий XML на локальный компьютер
    ```javasript
    В GitHub копируем HTTPS code репозитория XML и в Terminal пишем команду
  
   git clone https://github.com/svetasts/XML.git     ```
3. Внутри локального XML создать файл “new.xml”.
    ```javasript
    В терминал пишем команду
    vim new.xml
     ```
4. Добавить файл под гит
    ```javasript
     git add new.xml
     ```
5. Закоммитить файл
    ```javasript
    git commit -m "create new.xml"
     ```
6. Отправить файл на внешний GitHub репозиторий.
    ```javasript
    git add new.xml
     ```
7. Отредактировать содержание файла “new.xml” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате XML.
    ```javasript
    <xml>
	<name>"Sveta"</name>
	<age>36</age>
	<pet>1</pet>
	<salary>5000</salary>
     ```
8. Отправить изменения на внешний репозиторий.
    ```javasript
    git push
     ```
9. Создать файл preferences.xml
   ```javasript
    В терминал пишем команду
    vim preferences.xml
   ```
10. В файл preferences.xml добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате xml.
    ```javasript
    <xml>
   	<film>"dreamers"</film>
   	<series>"Twin Peaks"</series>
   	<food>"pelmeni"</food>
	   <season>"summer"</season>
	   <country>"America"</country>```
   
11. Создать файл sklls.xml добавить информацию о скиллах которые будут изучены на курсе в формате xml
    ```javasript
    <xml>
	<1> "Terminal",
	<2> "HTTP методы",
	<3> "DevTools",
	<4> "Postman",
	<5> "JS",
	<6> "SDLC, STLC",
	<7> "JSON, XML"
    ```
12. Сделать коммит в одну строку
     ```javasript
    git add .
    git commit -m "create preferences.xml,skills.xml"
    ```
13. Отправить сразу 2 файла на внешний репозиторий
    ```javasript 
    git push
    P.S. Если возникает проблема с аунтетификацией вводим 
    git remote set-url origin git@github.com:svetasts/REPOSITORY.git
    ```
14. На веб интерфейсе создать файл bug_report.xml
    ```javasript
    Add file --> Create new file --> bug_report.xml
    ```
   
15. Сделать Commit changes (сохранить) изменения на веб интерфейсе.  
      ```javasript
    Click on "Commit changes"
     ```

16. На веб интерфейсе модифицировать файл bug_report.xml, добавить баг репорт в формате xml.
    ```javasript
    <xml>
    <header>"name_of_header"</header>
    <steps_to_reproduce>"1...; 2...; 3...;"</steps_to_reproduce>
    <project>"project_1"</project>
    <severity>"minor"</severity>
    <priority>"medium"</priority>
    ```

17.  Сделать Commit changes (сохранить) изменения на веб интерфейсе.
        ```javasript
      Click on "Commit changes"
      ```
18. Синхронизировать внешний и локальный репозиторий XML
    ```javasript
    В Terminal ввести комнаду 
    git merge - синхронизация
    git fetch - проверка изменений на внешнем репозитории
     ```




# TXT
1. Создать внешний репозиторий c названием TXT
    ```javasript
    https://github.com/svetasts/TXT
     ```
2. Клонировать репозиторий TXT на локальный компьютер
    ```javasript
    В GitHub копируем HTTPS code репозитория TXT и в Terminal пишем команду
  
   git clone https://github.com/svetasts/TXT.git     ```
3. Внутри локального TXT создать файл “new.txt”.
    ```javasript
    В терминал пишем команду
    vim new.txt
     ```
4. Добавить файл под гит
    ```javasript
     git add new.txt
     ```
5. Закоммитить файл
    ```javasript
    git commit -m "create new.txt"
     ```
6. Отправить файл на внешний GitHub репозиторий.
    ```javasript
    git push 
     ```
7. Отредактировать содержание файла “new.txt” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате txt.
    ```javasript
    1. Sveta
    2. 36
    3. 1
    4. 5000
     ```
8. Отправить изменения на внешний репозиторий.
    ```javasript
    git push
     ```
9. Создать файл preferences.txt
   ```javasript
    В терминал пишем команду
    vim preferences.txt
   ```
10. В файл preferences.txt добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате txt.
    ```javasript
    1. Dreamers
    2. Twin Peaks
    3. pelmeni
    4. summer
    5. America
11.  Создать файл sklls.txt добавить информацию о скиллах которые будут изучены на курсе в формате txt
    ```javasript
    1. Terminal
    2. HTTP методы
    3. DevTools
    4. Postman
    5. JS
    6. SDLC, STLC
    7. JSON, XML
    ```
12. Сделать коммит в одну строку
     ```javasript
    git add .
    git commit -m "create preferences.txt,skills.txt"
    ```

13. Отправить сразу 2 файла на внешний репозиторий
    ```javasript 
    git push
    P.S. Если возникает проблема с аунтетификацией вводим git remote set-url origin git@github.com:svetasts/REPOSITORY.git
    ```
14. На веб интерфейсе создать файл bug_report.txt
    ```javasript
    Add file --> Create new file --> bug_report.txt
    ```
   
15. Сделать Commit changes (сохранить) изменения на веб интерфейсе.  
    ```javasript
    Click on "Commit changes"
     ```

16. На веб интерфейсе модифицировать файл bug_report.txt, добавить баг репорт в формате txt.
    ```javasript
    1. name_of_header
    2. 1...; 2...; 3...;
    3. . project_1
    4. minor
    5. medium
    ```

17.  Сделать Commit changes (сохранить) изменения на веб интерфейсе.
        ```javasript
      Click on "Commit changes"
      ```
18. Синхронизировать внешний и локальный репозиторий txt
    ```javasript
    В Terminal ввести комнаду 
    git merge - синхронизация
    git fetch - проверка изменений на внешнем репозитории
     ```



