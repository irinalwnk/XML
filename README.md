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
	Нажать "i" для ввода данных.  
	В формате XML:  
```XML
	<name> Leshenko Irina </name>  
	<age> 31 </age>  
	<cats> 1 </cats>  
	<expected_salaty> 800$ </expected_salary>  
```  
Нажать "Esc" и ввести для выхода из редактора      
	`:wq`   

28. Отправить изменения на внешний репозиторий.  
`git commit -am 'add information in XML new.xml'; git push`  
29. Создать файл preferences.xml  
`touch preferences.xml`  
30. В файл preferences.xml добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате XML.  
`vim preferences.xml`  
Нажать "i" для ввода данных.   
	в формате XML:  
```XML
	<film> Lord of the rings </film>  
	<series> Friends </series>   
	<food> Orange </food>  
	<season> Spring </season>    
	<country_to_visit> Ireland </country_to_visit>  
```  
Нажать "Esc" и ввести для выхода из редактора  
`:wq`  

31. Создать файл skills.xml добавить информацию о скиллах которые будут изучены на курсе в формате XML  
`touch skills.xml`  
`vim skills.xml`   
	Нажать "i" для ввода данных.  
	В формате XML:  
```XML   
<Skill_1> QA Testing </Skill_1>  
<Skill_2> Terminal </Skill_2>    
<Skill_3> Postman </Skill_3>    
<Skill_4> Jmeter </Skill_4>    
<Skill_5> SQL </Skill_5>   
<Skill_6> Android Studio </Skill_6>  
```  
Нажать "Esc" и ввести для выхода из редактора   
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
	В формате XML:   
```XML  
<title> Не работает кнопка отправки заказа. </title>  
<steps_to_reproduce>  
<Step_1> Открыть сайт *.</Step_1>  
<Step_2> Нажать по ссылке *. </Step_2>  
<Step_3> Пролистать до поля *. </Step_3>  
<Step_4> Ввести значение в поле *. </Step_4>  
<Step_5> Попытаться нажать кнопку отправки заказа. </Step_5> </steps_to_reproduce>  
<ar> Кнопка неактивна. </ar>  
<er> Ожидаемый результат кнопка нажимается можно сделать заказ. </er>  
```  


37.  Сделать Commit changes (сохранить) изменения на веб интерфейсе.  
`В строку "Commit new file" добавить "add information XML" - Нажать "Commit new file"`  
38. Синхронизировать внешний и локальный репозиторий XML  
`git pull`
