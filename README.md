# Homework 1

# JSON
 1. Создать внешний репозиторий c названием JSON.
	в правом верхнем углу нажать "плюс" и выбрать New repository

 2. Клонировать репозиторий JSON на локальный компьютер.
	git clone https://github.com/vladislavzagoruyko/JSON.git

 3. Внутри локального JSON создать файл “new.json”.
	touch new.json

 4. Добавить файл под гит.
	git add new.json

 5. Закоммитить файл.
	git commit -m "add the first file"

 6. Отправить файл на внешний GitHub репозиторий.
	git push
 
 7. Отредактировать содержание файла “new.json” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате JSON.
	cat >> new.json -> добавить информацию -> Enter -> ctrl C
 
 8. Отправить изменения на внешний репозиторий.
	git add new.json
	git commit -m "исправил содержимое файлов"
	git push
 
 9. Создать файл preferences.json
	touch preferences.json
 
 10. В файл preferences.json добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате JSON.
	cat >> preferences.json -> добавить информацию -> Enter -> ctrl C
 
 11. Создать файл sklls.json добавить информацию о скиллах которые будут изучены на курсе в формате JSON
	cat >  sklls.json -> добавить информацию -> Enter -> ctrl C
 
 12. Отправить сразу 2 файла на внешний репозиторий.
	git add preferences.json sklls.json
	git commit -m "исправил содержимое файлов"
	git push
	
 13. На веб интерфейсе создать файл bug_report.json.
	Add file -> Create new file
 
 14. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
	Commit new file
 
 15. На веб интерфейсе модифицировать файл bug_report.json, добавить баг репорт в формате JSON.
	edit this file
 
 16. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
	Commit changes
	
 17. Синхронизировать внешний и локальный репозиторий JSON
	git fetch
	git pull

# XML
 18. Создать внешний репозиторий c названием XML.
	в правом верхнем углу нажать "плюс" и выбрать New repository
	
 19. Клонировать репозиторий XML на локальный компьютер.
	git clone https://github.com/vladislavzagoruyko/XML.git
	
 20. Внутри локального XML создать файл “new.xml”.
	touch new.xml

 21. Добавить файл под гит.
	git add new.xml
 
 22. Закоммитить файл.
	git commit -m "add the first xml file" 
 
 23. Отправить файл на внешний GitHub репозиторий.
	git push
 
 24. Отредактировать содержание файла “new.xml” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате XML.
	cat >> new.xml -> добавить информацию -> Enter -> ctrl C
 
 25. Отправить изменения на внешний репозиторий.
	git add new.xml
	git commit -m "добавил содержимое"
	git push
 
 26. Создать файл preferences.xml
	touch preferences.xml
 
 27. В файл preferences.xml добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате XML.
	cat >> preferences.xml -> добавить информацию -> Enter -> ctrl C
 
 28. Создать файл sklls.xml добавить информацию о скиллах которые будут изучены на курсе в формате XML
	cat > sklls.xml -> добавить информацию -> Enter -> ctrl C

 29. Сделать коммит в одну строку.
	git add preferences.xml sklls.xml&&git commit -m "создал 2 файла с содержимым"
 
 30. Отправить сразу 2 файла на внешний репозиторий.
	git push
  
 31. На веб интерфейсе создать файл bug_report.xml.
	Add file -> Create new file
 
 32. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
	Commit new file
 
 33. На веб интерфейсе модифицировать файл bug_report.xml, добавить баг репорт в формате XML.
	edit this file
 
 34. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
	Commit changes
	
 35. Синхронизировать внешний и локальный репозиторий XML
	git fetch
	git pull
  
  
  # Homework 2
  
1. На локальном репозитории сделать ветки для:
- Postman
- Jmeter
- CheckLists
- Bag Reports
- SQL
- Charles
- Mobile testing
	git branch (название ветки)

2. Запушить все ветки на внешний репозиторий
	git push --all
	
3. В ветке Bag Reports сделать текстовый документ со структурой баг репорта
	git checkout Bag_Reports
	cat > bag_structure.txt -> заполнить документ -> Enter -> ctrl C
	
4. Запушить структуру багрепорта на внешний репозиторий
	git add bag_structure.txt
	git commit -m "add bag_structure"
	git push
	
5. Вмержить ветку Bag Reports в Main
	git checkout main
	git merge Bag_Reports -m "merge_Bag_Reports"

6. Запушить main на внешний репозиторий.
	git push
	
7. В ветке CheckLists набросать структуру чек листа.
	git checkout CheckLists
	cat > check_list.txt -> заполнить документ -> Enter -> ctrl C
	
8. Запушить структуру на внешний репозиторий
	git add check_list.txt
	git commit -m "add check_list"
	git push
	
9. На внешнем репозитории сделать Pull Request ветки CheckLists в main
	нажать кнопку "Pull requests"
	нажать зеленую кнопку "Compare & pull request"
	нажать зеленую кнопку "Create pull request"
	нажать зеленую кнопку "Merge pull request"
	нажать зеленую кнопку "Confirm merge"
	
10. Синхронизировать Внешнюю и Локальную ветки Main	
	git checkout main
	git fetch
	git pull
	cat check_list.txt (проверим файл)


 
