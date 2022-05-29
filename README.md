# Practice with GIT & JSON

 **1. Создать внешний репозиторий c названием JSON.**  
```  //репозиторий создан https://github.com/balsis/JSON ```  
 **2. Клонировать репозиторий JSON на локальный компьютер.**  
  	`$ git clone https://github.com/balsis/JSON.git`  
 **3. Внутри локального JSON создать файл “new.json”.**  
  `	$ touch new.json  `  
 **4. Добавить файл под гит.**  
  	`$ git add new.json`  
 **5. Закоммитить файл.**  
	 ` $ git commit -m 'add new.json'`  
**6. Отправить файл на внешний GitHub репозиторий.**  
	  `$ git push`  
**7. Отредактировать содержание файла “new.json” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате JSON.**  
	 ` $ nano new.json `  
 **8. Отправить изменения на внешний репозиторий.**  
	 ` $ git commit -am 'modify new.json'`  
	 ` $ git push`  
 **9. Создать файл preferences.json**  
	 ``` $ nano preferences.json ```  
  **10. В файл preferences.json добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате JSON.**  
  `  // добавлено по результатам выполнения п.13`  
 **11. Создать файл sklls.json добавить информацию о скиллах которые будут изучены на курсе в формате JSON**  
	 ` $ nano skills.json`  `// Добавлены скиллы с сайта в формате массива "skills": [skill_1, skill_2, skill_3]`  
  **12. Отправить сразу 2 файла на внешний репозиторий.**  
	  `$ git add .`   
	  `$ git commit -m 'add preferences.json and skills.json'`    
	  `$ git push`    
  **13. На веб интерфейсе создать файл bug_report.json.**  
	  `// Создан`  
  **14. Сделать Commit changes (сохранить) изменения на веб интерфейсе.**  
	  `// Сделаны Commit changes`  
  **15. На веб интерфейсе модифицировать файл bug_report.json, добавить баг репорт в формате JSON.**  
	  `// Модифицирован `  
  **16. Сделать Commit changes (сохранить) изменения на веб интерфейсе.**  
	  `// Сделаны Commit changes`  
  **17. Синхронизировать внешний и локальный репозиторий JSON**  
	`$ git pull` 
