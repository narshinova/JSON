# JSON
<h1 align="center">GIT HW_1/JSON</h1>

**1.Создать внешний репозиторий c названием JSON.**
```
веб интерфейс github.com, залогинитьс, перейти в Repositories, создание новой репозитории New, имя JSON, Add a ReadMe file, Create repository
```
**2. Клонировать репозиторий JSON на локальный компьютер.**
```
в веб интерфейсе Code - HTTPS - COPY

git clone https://github.com/narshinova/JSON.git
```
**3. Внутри локального JSON создать файл “new.json”.**
```
cd JSON
touch new.json
```
**4. Добавить файл под гит.**
```
git add new.json
```
**5. Закоммитить файл.**
```
git commit -m 'create new.json'
```

**6. Отправить файл на внешний GitHub репозиторий.**
```
git push
```
**7. Отредактировать содержание файла “new.json” - написать информацию о себе (ФИО, возраст, количество домашних животных, будущая желаемая зарплата). Всё написать в формате JSON.`**
```
vim new.jsom
```
<i>режим редактироваие i </i>
```json
{
	"ФИО":"Arsinova Natalia Alexandrovna",
	"возраст":"37",
	"количество домашних животных":"21",
	"будущая желаемая зарплата":"600$"
}
```
<i>выйти из vim нажатием Esc :wq Enter</i>

**8. Отправить изменения на внешний репозиторий.**
```
git commit -am 'changes in new.json' && git push
```
**9. Создать файл preferences.json**
```
vim preferences.json
```
**10. В файл preferences.json добавить информацию о своих предпочтениях (Любимый фильм, любимый сериал, любимая еда, любимое время года, сторона которую хотели бы посетить) в формате JSON.**

<i>режим редактироваие i</i>
```json
{
	"Любимый фильм":"Harry Potter",
	"любимый сериал":"Friends",
	"любимая еда":"potato", 
	"любимое время года":"summer",
	"страна которую хотели бы посетить":"New Zeland"
}
```
<i>выйти из vim нажатием Esc :wq Enter</i>

**11. Создать файл skills.json добавить информацию о скиллах которые будут изучены на курсе в формате JSON**
```
vim skills.json
```
<i>режим редактироваие i</i>
```json
{
	"skill 1.":"Базовая теория. Что такое тестирование, багрепорты, документация, виды, методы, направления тестирования и т.п. SDLC, STLC.",
        "skill 2.":"Что такое клиент-серверная архитектура.",
        "skill 3.":"HTTP Методы запросов на сервер.",
        "skill 4.":"Коды ответов HTTP сервера.",
        'skill 5.':'Структуры HTTP запросов и ответов.',
        'skill 6.':'Что такое JSON, XML. Их структура.',
        'skill 7.':'Тестирование API через Postman (JS, автотесты API).',
        'skill 8.':'Снятие и чтение логов c внешнего сервера.',
        'skill 9.':'Снифинг http web трафика через Charles и Fiddler.',
        'skill 10.':'Dev Tools веб браузеров (Google Chrome, FireFox).',
        'skill 11.':'VPN. (Как работает, зачем нужен, как использовать, варианты инструментов)',
        'skill 12.':'Мобильное тестирование.',
        'skill 13.':'Особенность iOS, Android, гайдлайны.',
        'skill 14.':'Сборка iOS приложений на XCode.',
        'skill 15.':'Сборка Android приложений на Android Studio.',
        'skill 16.':'ADB (управление андройд девайсами).',
        'skill 17.':'Настройка прокси и vpn на iOS и Android.',
        'skill 18.':'Перехват (сниффинг) мобильного трафика через Charles и Fiddler на iOS и Android.',
        'skill 19.':'Командная строка (terminal) Linux (копирование, создание, просмотр, перемещение файлов на серверах без графического интерфейса)',
        'skill 20.':'Основы bash скриптинг, автоматизация рутинных задач на сервере.',
        'skill 21.':'Доступ к удалённым серверам.',
        'skill 22.':'Основы SQL (Create, Delete, Drop, Insert Into, Select, From, Where, Join).',
        'skill 23.':'База данных Postgres (установка, настройка и использование).',
        'skill 24.':'Нереляционная база данных Redis (установка, настройка и использование).',
        'skill 25.':'Нагрузочное тестирование в Jmeter.',
        'skill 26.':'Методология разработки Scrum.',
        'skill 27.':'Python. (Изучение основ. Создание клиент серверного приложения)'
}
```
<i>выйти из vim нажатием Esc :wq Enter</i>

**12. Отправить сразу 2 файла на внешний репозиторий.**
```
git commit -m 'changes' && git push
```
**13. На веб интерфейсе создать файл bug_report.json.**
```
веб интерфейс Add file - Create new file создание файла - название bug_report.json
```
**14. Сделать Commit changes (сохранить) изменения на веб интерфейсе.**
```
Create bug_report.json, сохранение Commit changes
```
**15. На веб интерфейсе модифицировать файл bug_report.json, добавить баг репорт в формате JSON.**
<i>редактирование файла</i>
```json
{
	"Id":"B1",
	"Summary":"404 error is displayed",
	"Preconditions":" ",
	"Steps to reproduce":"1. Go to http://www.example.com, 2. Click on Login button",
  "Actual Result":"404 error is displayed",
  "Expected Result":"Authorization page is opened",
  "Attachments":"http://prntscr.com/ic93kw"
}
```
**16. Сделать Commit changes (сохранить) изменения на веб интерфейсе.**
```
Update bug_report.json - Commit changes
```
**17. Синхронизировать внешний и локальный репозиторий JSON**
```
git pull
```
