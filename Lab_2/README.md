# Здесь находится 2 лаба
# Вариант 9
Чат-бот поиска лекарств в аптеках города (название лекарства) (+парсинг)

В файле Parser.py находится парсер, который возвращает информацию, полученную при запросе

Файл main.py содержит бота 

При запуске бота он выводит следующий текст

![Screenshot](Screenshots/start.png)


При вводе названия лекарства бот выводит информацию о найденных лекарствах в отсортированном по цене виде и инлайн кнопками для навигации по лекарствам

![Screenshot](Screenshots/find.png)

При нажатии на кнопку "Подробнее" пользователь переходит на страницу лекарства в онлайн аптеке

![Screenshot](Screenshots/ref.png)

При нажатии кнопки "В меню" бот удаляет сообщение с кнопками и предлегает заново ввести название лекарства

![Screenshot](Screenshots/to_menu.png)
