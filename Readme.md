2.1
	Вариант №10:
	Сайт с расписанием занятий студентов, в котором есть следующие возможности:
		- редактирование расписания для разных групп разных факультетов
		- управление (CRUD) группами и факультетами
		- поиск расписания по группе на сайте
		- иерархия доступа к расписанию группы
	Генерация расписания не нужна.
2.2
	1. Необходимо скачать и установить технологическую платформу 1С:Предприятие 8.2 (8.2.19.83). Скачать её можно с сайта http://www.1c.ru/
	При установке необходимо выбрать следующие компоненты: 1С:Предприятие и модули расширения веб-сервера. 
	2. Необходимо скачать и установить сервер Apache версии 2.2.25 с сайта www.apache.org.
	3. Запустить 1С:Предприятие (от имени администратора). Создать новую информационную базу на данном компьютере.
	4. Войти в конфигуратор созданной базы.
	5. Администрирование -> Загрузить информационную базу -> Выбрать файл LR2-7.dt, нажать F7.
	6. Запустить сервер Apache. 
	7. Администрирование -> Публикация на веб-сервере. Указать имя (допустим Rasp), Каталог указать conf/ в директории сервера (там находится файл httpd.conf).
	8. Нажимаем опубликовать.
	9. Войти в браузер (использовался Safari). В адресной строке указать http://127.0.0.1:8080/Rasp/ru_RU/
	У всех пользователей пароли пусты.
