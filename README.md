# JSON

 1. Создать внешний репозиторий c названием JSON.
	        
	        repositories->new->create repository
 2. Клонировать репозиторий JSON на локальный компьютер.

		$ git clone https://github.com/kaminska1313/JSON.git
 3. Внутри локального JSON создать файл “new.json”.

		$ cd JSON
		$ touch new.json
 4. Добавить файл под гит.
		
		$ git add new.json
 5. Закоммитить файл.
		
		$ git commit new.json -m "created new.json"
 6. Отправить файл на внешний GitHub репозиторий.
		
		$ git push
 7. Отредактировать содержание файла “new.json” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате JSON.
		
		$ cat >> new.json
		*text here*
		ctrl+c	
 8. Отправить изменения на внешний репозиторий.
		
		$ git add new.json
		$ git commit -m "filled new.json"
		$ git push
 9. Создать файл preferences.json
		
		$ touch preferences.json
 10. В файл preferences.json добавить информацию о своих предпочтениях (любимый фильм, любимый сериал, любимая еда, любимое время года, страна которую хотели бы посетить) в формате JSON.
		
 	        $ cat >> preferences.json
	        *text here*
	        ctrl+c
 11. Создать файл sklls.json добавить информацию о скиллах которые будут изучены на курсе в формате JSON.
		
        	$ touch skills.json
        	$ cat >> skills.json
        	*text here*
        	ctrl+c
 12. Отправить сразу 2 файла на внешний репозиторий.
		 
	        $ git add .
	        $ git commit -m "created new files"
	        $ git push
 13. На веб интерфейсе создать файл bug_report.json.

	        add file->create new file
 14. Сделать Commit changes (сохранить) изменения на веб интерфейсе.

	        ->commit new file
 15. На веб интерфейсе модифицировать файл bug_report.json, добавить баг репорт в формате JSON.
  
	        bug_report.json->edit this file
	        *insert text*
 16. Сделать Commit changes (сохранить) изменения на веб интерфейсе.

	        ->commit changes
 17. Синхронизировать внешний и локальный репозиторий JSON.

	        $ git pull
		
