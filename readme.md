git status // Показывает файлы и их статус

git config user.name "FIRST_NAME LAST_NAME"
git config user.email "email@email.com"

git add [files] or git add . // Добавляет файлы в stage

git commit -m "comment"  //

git log  // показывает подробную информацию о коммите
git log --oneline  // показывает краткую информацию о комите

git push [repo_link] [branch_name]

git reset  // откатывает измененные файлы из stage (после команды add)
git reset --hard // отменяет изменения в том числе в коде (откатывает до версии, которая была в комите)

git remote -v // показывает адрес к origin

git branch // Показывает ветки.
git branch [branch_name] // создает ветку develop

git checkout [branch_name] // переключает на другую ветку (например с mster на develop)

git merge [ветка_которую_нужно_смерджить_с_текущей] // перед этим нужно сделать переключени не ту ветку, в которую будут слиты изменения