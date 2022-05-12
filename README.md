# TXT
 1. Создать внешний репозиторий c названием TXT.
  
  
 	Перехожу на github, создать новый репозиторий, добавляю название, сохраняю.
 
 2. Клонировать репозиторий TXT на локальный компьютер. 

	git clone  https://github.com/Ilyamrkl/TXT.git
 
 3. Внутри локального TXT создать файл “new.txt”.

	cd TXT
	touch new.txt
	
 4. Добавить файл под гит.

	git add .
	
 5. Закоммитить файл.

	git commit -m 'Create new.txt'
	
 6. Отправить файл на внешний GitHub репозиторий.

	git push
 7. Отредактировать содержание файла “new.txt” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате TXT.

	vim new.txt
	перехожу в режим редактирования'ins'заполняю необходимую информацию
	
 8. Отправить изменения на внешний репозиторий.


	git commit -am 'Update new.txt' && git push
		
 9. Создать файл preferences.txt

	toush preferences.txt
	
 10. В файл preferences.txt” добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате TXT.

	vim preferences.txt
	перехожу в режим редактирования'ins'заполняю необходимую информацию
	
 11. Создать файл sklls.txt добавить информацию о скиллах которые будут изучены на курсе в формате TXT

	vim skils.txt
	перехожу в режим редактирования'ins'заполняю необходимую информацию
	
 12. Сделать коммит в одну строку.

	git add . && git commit -m 'Create'
 13. Отправить сразу 2 файла на внешний репозиторий.

	git push
	
 14. На веб интерфейсе создать файл bug_report.txt.

	веб интерфейс Add file - Create new file 
	
 15. Сделать Commit changes (сохранить) изменения на веб интерфейсе.

	коммит Create bug_report.xml и сохранить
	
	
 16. На веб интерфейсе модифицировать файл bug_report.txt, добавить баг репорт в формате TXT.

	редактирую файл/заполняю необходимую информацию
	
 17. Сделать Commit changes (сохранить) изменения на веб интерфейсе.

	коммит Update bug_report.txt и сохранение Commit changes
	
 18. Синхронизировать внешний и локальный репозиторий TXT


	git pull
	
