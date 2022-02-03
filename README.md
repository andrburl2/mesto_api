# andrburl-mesto API

API для проекта Mesto. API написан по принципу REST. В данный момент реализованы следующие возможности:
- регистрация и вход пользователя, при входе создается токен в cookie для последующего входа без пароля;
- редактирование профиля и переадресация, если не выполнен вход;
- добавление, удаление и возможность лайкать карточки;
- входящие данные валидируются, пути защищены проверкой авторизации, ошибки обрабатываются единым обработчиком.
API выложен на поддомене **api.andrburl-mesto**, для правильной работы настроен CORS.

## Ссылки:

### [Сайт](https://andrburl-mesto.ml)
### [Frontend](https://github.com/andrburl2/mesto_react)

## В работе использовались:
- Node.js;
- Express;
- MongoDB;
- Mongoose;
- Git.