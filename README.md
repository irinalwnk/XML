# XML
21. Создать внешний репозиторий c названием XML.  
 `Github - Repositories - New - Repository name: XML - поставить галочку у Add Readme file - Cteate repository`
22. Клонировать репозиторий XML на локальный компьютер.  
`Зайти в репозитрий XML - Code HTTPS (скопировать ссылку);
в GitBash:
git clone https://github.com/irinalwnk/XML.git`  
23. Внутри локального XML создать файл “new.xml”.  
`cd XML`  
`touch new.xml`   
24. Добавить файл под гит.  
`git add new.xml`  
25. Закоммитить файл.  
 `git commit -m 'create file new.xml'`  
26. Отправить файл на внешний GitHub репозиторий.    
`git push`  
27. Отредактировать содержание файла “new.xml” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате XML.  
`vim new.xml `  
	В формате XML:  
	`<name> Leshenko Irina </name>`  
	`<age> 31 </age>`  
	`<cats> 1 </cats>`  
	`<expected_salaty> 800$ </expected_salary>`  
	`:wq`

28. Отправить изменения на внешний репозиторий.  
`git commit -am 'add information in XML new.xml'; git push`  
 29. Создать файл preferences.xml  
`touch preferences.xml`  
 30. В файл preferences.xml добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате XML.  
`vim preferences.xml`  
	в формате XML:  
	`<film> Lord of the rings </film>`  
	`<series> Friends </series>`  
	`<food> Orange </food>`  
	`<season> Spring </season>`  
	`<country> to visit> Ireland </country>`  
	`:wq`  

 31. Создать файл sklls.xml добавить информацию о скиллах которые будут изучены на курсе в формате XML  
`touch skills.xml`  
`vim skills.xml`  
	в формате XML:  
	`<Skill_1> QA Testing </Skill_1>`  
	`<Skill_2> Terminal </Skill_2>`    
	`<Skill_3> Postman </Skill_3>`    
	`<Skill_4> Jmeter </Skill_4>`    
	`<Skill_5> SQL </Skill_5>`   
	`<Skill_6> Android Studio </Skill_6>`    
	`:wq`  
 32. Сделать коммит в одну строку.  
`git add . ; git commit -m 'add information in XML'`  
 33. Отправить сразу 2 файла на внешний репозиторий.  
`git push`  
 34. На веб интерфейсе создать файл bug_report.xml.  
`File - Cteate New File - bug_report.xml`  
 35. Сделать Commit changes (сохранить) изменения на веб интерфейсе.  
`В строку "Commit new file" добавить "Cteate New File - bug_report.xml" - Нажать "Commit new file"`  
 36. На веб интерфейсе модифицировать файл bug_report.xml, добавить баг репорт в формате XML.  
`Edit this file - внести информацию в файл  в формате XML`  
 37. Сделать Commit changes (сохранить) изменения на веб интерфейсе.  
`В строку "Commit new file" добавить "add information XML" - Нажать "Commit new file"`  
 38. Синхронизировать внешний и локальный репозиторий XML  
`git pull`
