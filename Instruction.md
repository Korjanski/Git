# Git
GitHub. HW_2
1. На локальном репозитории сделать ветки для:
- Postman
 git branch Postman
- Jmeter
 git branch Jmeter
- CheckLists
 git branch Checklists
- Bug Reports
 git branch BugReports
- SQL
 git branch SQL
- Charles
 git branch Charles
- Mobile testing
 git branch MobileTesting

2. Запушить все ветки на внешний репозиторий
 git push -u origin --all

3. В ветке Bug Reports сделать текстовый документ со структурой баг репорта
 git checkout BugReports
 vim BugReports.txt
 git commit -m "BugReports"

4. Запушить структуру багрепорта на внешний репозиторий
 git push

5. Вмержить ветку Bag Reports в Main
 git merge BugReports

6. Запушить main на внешний репозиторий.
 git push

7. В ветке CheckLists набросать структуру чек листа.
 git checkout CheckLists
 vim CheckLists.txt

8. Запушить структуру на внешний репозиторий
 git add .;git commit -m "new" ;git push

9. На внешнем репозитории сделать Pull Request ветки CheckLists в main
 pull request

10. Синхронизировать Внешнюю и Локальную ветки Main
 git checkout main
 git pull
