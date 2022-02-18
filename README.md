# JSON

4. **Создать внешний репозиторий c названием JSON.** - Авторизоваться на [github.com](https://github.com). На вкладке ***"Repositories"*** нажать на кнопку ***"New"***. Заполнить необходимые поля (в данном случае: вести название репозитория ***"JSON"*** в поле ***"Repository name"***, отметить чекбокс ***"Add a README file"***, убедиться что выбран тип репозитория ***"Public"***). Нажать на кнопку ***"Create repository"***.

 5. **Клонировать репозиторий JSON на локальный компьютер.** - На гитхабе на странице созданного репозитория нажать на кнопку ***"Code"***, скопировать ссылку HTTPS. В git bash перейти в папку курса с помощью команты **`cd - cd d://ksendzov`**. Ввести команду **`git clone [скопированная ссылка]`**
 6. **Внутри локального JSON создать файл “new.json”.** - **`cd json`** (переход в репозиторий), **`touch new.json`** (создание файла)
 7. **Добавить файл под гит.** - **`git add new.json`**
 8. **Закоммитить файл.** - **`git commit -m "Add new.json"`**
 9. **Отправить файл на внешний GitHub репозиторий.** - **`git push`**
 10. **Отредактировать содержание файла “new.json” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате JSON.** - **`vim new.json`**. В редакторе - **`i`** для входа в режим редактирования, **`esc`** - для выхода из режима редактирования, **`:wq`**
 11. **Отправить изменения на внешний репозиторий.** - **`git add new.json`** (добавление в staging), **`git commit -m "Change new.json"`** (коммит), **`git push`** (отправка на сервер)
 12. **Создать файл preferences.json.** - **`touch preferences.json`**
 13. **В файл preferences.json добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате JSON.** - **`vim preferences.json`**. В редакторе - **`i`** для входа в режим редактирования, **`esc`** - для выхода из режима редактирования, **`:wq`** - выход из vim
 14. **Создать файл sklls.json добавить информацию о скиллах которые будут изучены на курсе в формате JSON** - **`touch skills.json`**
 15. **Отправить сразу 2 файла на внешний репозиторий.** - **`git add .`**
 **`git commit -m "Add files: preferences.json, skills.json"`**
**`git push`**
 16. **На веб интерфейсе создать файл bug_report.json.** - Нажать на кнопку ***"Add file"*** -> ***"Create new file"***. Ввести название
 17. **Сделать Commit changes (сохранить) изменения на веб интерфейсе.** - В блоке ***"Commit new file"*** ввести комментарий к коммиту, нажать на кнопку ***"Commit new file"***
 18. **На веб интерфейсе модифицировать файл bug_report.json, добавить баг репорт в формате JSON.** - Нажать на кнопку редактирования, внести изменения. 
 19. **Сделать Commit changes (сохранить) изменения на веб интерфейсе.** - В блоке ***"Commit changes"*** ввести комментарий к коммиту, нажать на кнопку ***"Commit changes"***
 20. **Синхронизировать внешний и локальный репозиторий JSON** - **`git pull`**
