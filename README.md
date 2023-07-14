## Spring Boot
1) Перевести проект на Spring Boot. Для этого надо:
   <br> 1.1) Зайти на сайт https://start.spring.io/ 
   <br> 2.2) Выбрать Maven Project.
   <br> 2.3) Выбрать язык Java.
   <br> 2.4) Выбрать последнюю версию Spring Boot.
   <br> 2.5) Добавить зависимость Spring Web.
   <br> 2.6) Добавить зависимость PostgreSQL Driver или MySQL Driver.
   <br> 2.7) Добавить зависимость Spring Data JPA.
   <br> 2.8) Нажать Generate Project.
   <br> 2.9) Перенести в новый проект все классы из текущего проекта.
2) Не забудьте добавить в application.properties настройки для подключения к БД и добавить в pom.xml зависимости hibernate.
3) Переписать DAO на Spring Data JPA.
4) Конфигурация больше не нужна. Удалите ее.
5) Запустите приложение и проверьте, что все работает.

## Spring Security
Написать CRUD приложение на spring boot + spring data + spring mvc + spring security + thymeleaf.
В качестве базы данных использовать postgresql или mysql.

В приложении должны быть две сущности: пользователь, роль.
У пользователя должны быть поля: имя, фамилия, почта, пароль, роли.
У роли должны быть поля: имя.
Сделать страницы:
1. Страница логина (/login). Доступна для всех.
2. Страница обычного пользователя (/user). Доступна для пользователя с ролью User. Там должна быть информация о пользователе.
3. Страницы админа (/admin). Доступна для пользователя с ролью Admin. Там должна быть информация о всех пользователях и возможность их удаления(/admin/{id}/delete), редактирования(/admin/{id}/edit) и создания(/admin/new).
4. Логин это почта. Пароль хранить в зашифрованном виде.

## Bootstrap
Следующее задание добавить bootstrap к проекту и сделать красивый интерфейс.
![img.png](img.png)

## REST
Следующее задание изменить MVC на REST и сделать тоже самое, но без перезагрузки страницы.
Почитайте про RestController: https://spring.io/guides/gs/rest-service/
Для этого можно использовать thymeleaf.
Больше информации тут: https://spring.io/guides/gs/rest-service/
Почитайте про REST: https://habr.com/ru/post/38730/
Почитайте про jquery ajax: https://learn.javascript.ru/ajax-intro
Почитайте про fetch: https://learn.javascript.ru/fetch
