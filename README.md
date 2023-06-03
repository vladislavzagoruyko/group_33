# Homework 1

# JSON
 1. Создать внешний репозиторий c названием JSON.<p>в правом верхнем углу нажать "плюс" и выбрать New repository

 2. Клонировать репозиторий JSON на локальный компьютер.
	<p>git clone https://github.com/vladislavzagoruyko/JSON.git

 3. Внутри локального JSON создать файл “new.json”.
	<p>touch new.json

 4. Добавить файл под гит.
	<p>git add new.json

 5. Закоммитить файл.
	<p>git commit -m "add the first file"

 6. Отправить файл на внешний GitHub репозиторий.
	<p>git push
 
 7. Отредактировать содержание файла “new.json” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате JSON.
	<p>cat >> new.json -> добавить информацию -> Enter -> ctrl C
 
 8. Отправить изменения на внешний репозиторий.
	<p>git add new.json
	<p>git commit -m "исправил содержимое файлов"
	<p>git push
 
 9. Создать файл preferences.json
	<p>touch preferences.json
 
 10. В файл preferences.json добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате JSON.
	<p>cat >> preferences.json -> добавить информацию -> Enter -> ctrl C
 
 11. Создать файл sklls.json добавить информацию о скиллах которые будут изучены на курсе в формате JSON
	<p>cat >  sklls.json -> добавить информацию -> Enter -> ctrl C
 
 12. Отправить сразу 2 файла на внешний репозиторий.
	<p>git add preferences.json sklls.json
	<p>git commit -m "исправил содержимое файлов"
	<p>git push
	
 13. На веб интерфейсе создать файл bug_report.json.
	<p>add file -> Create new file
 
 14. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
	 <p>Commit new file
 
 15. На веб интерфейсе модифицировать файл bug_report.json, добавить баг репорт в формате JSON.
	<p>edit this file
 
 16. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
	<p>Commit changes
	
 17. Синхронизировать внешний и локальный репозиторий JSON
	<p>git fetch
	<p>git pull

# XML
 18. Создать внешний репозиторий c названием XML.
	<p>в правом верхнем углу нажать "плюс" и выбрать New repository
	
 19. Клонировать репозиторий XML на локальный компьютер.
	<p>git clone https://github.com/vladislavzagoruyko/XML.git
	
 20. Внутри локального XML создать файл “new.xml”.
	<p>touch new.xml

 21. Добавить файл под гит.
	<p>git add new.xml
 
 22. Закоммитить файл.
	<p>git commit -m "add the first xml file" 
 
 23. Отправить файл на внешний GitHub репозиторий.
	<p>git push
 
 24. Отредактировать содержание файла “new.xml” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате XML.
	<p>cat >> new.xml -> добавить информацию -> Enter -> ctrl C
 
 25. Отправить изменения на внешний репозиторий.
	<p>git add new.xml
	<p>git commit -m "добавил содержимое"
	<p>git push
 
 26. Создать файл preferences.xml
	<p>touch preferences.xml
 
 27. В файл preferences.xml добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате XML.
	<p>cat >> preferences.xml -> добавить информацию -> Enter -> ctrl C
 
 28. Создать файл sklls.xml добавить информацию о скиллах которые будут изучены на курсе в формате XML
	<p>cat > sklls.xml -> добавить информацию -> Enter -> ctrl C

 29. Сделать коммит в одну строку.
	<p>git add preferences.xml sklls.xml&&git commit -m "создал 2 файла с содержимым"
 
 30. Отправить сразу 2 файла на внешний репозиторий.
	<p>git push
  
 31. На веб интерфейсе создать файл bug_report.xml.
	<p>Add file -> Create new file
 
 32. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
	<p>Commit new file
 
 33. На веб интерфейсе модифицировать файл bug_report.xml, добавить баг репорт в формате XML.
	<p>edit this file
 
 34. Сделать Commit changes (сохранить) изменения на веб интерфейсе.
	<p>Commit changes
	
 35. Синхронизировать внешний и локальный репозиторий XML
	<p>git fetch
	<p>git pull
  
  
  # Homework 2
  
1. На локальном репозитории сделать ветки для:
<p>- Postman
<p>- Jmeter
<p>- CheckLists
<p>- Bag Reports
<p>- SQL
<p>- Charles
<p>- Mobile testing
	<p>git branch (название ветки)

2. Запушить все ветки на внешний репозиторий
	<p>git push --all
	
3. В ветке Bag Reports сделать текстовый документ со структурой баг репорта
	<p>git checkout Bag_Reports
	<p>cat > bag_structure.txt -> заполнить документ -> Enter -> ctrl C
	
4. Запушить структуру багрепорта на внешний репозиторий
	<p>git add bag_structure.txt
	<p>git commit -m "add bag_structure"
	<p>git push
	
5. Вмержить ветку Bag Reports в Main
	<p>git checkout main
	<p>git merge Bag_Reports -m "merge_Bag_Reports"

6. Запушить main на внешний репозиторий.
	<p>git push
	
7. В ветке CheckLists набросать структуру чек листа.
	<p>git checkout CheckLists
	<p>cat > check_list.txt -> заполнить документ -> Enter -> ctrl C
	
8. Запушить структуру на внешний репозиторий
	<p>git add check_list.txt
	<p>git commit -m "add check_list"
	<p>git push
	
9. На внешнем репозитории сделать Pull Request ветки CheckLists в main
	<p>нажать кнопку "Pull requests"
	<p>нажать зеленую кнопку "Compare & pull request"
	<p>нажать зеленую кнопку "Create pull request"
	<p>нажать зеленую кнопку "Merge pull request"
	<p>нажать зеленую кнопку "Confirm merge"
	
10. Синхронизировать Внешнюю и Локальную ветки Main	
	<p>git checkout main
	<p>git fetch
	<p>git pull
	<p>cat check_list.txt (проверим файл)


 
