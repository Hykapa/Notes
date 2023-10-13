## Этот проект представляет собой приложение для создания заметок. Он позволяет создавать, удалять и редактировать заметки, добавлять теги к заметкам и прикреплять к заметкам дату.

## Стэк технологий
- [Angular](https://angular.io/Angular/)
- [ORM EntityFramework Core](https://learn.microsoft.com/ru-ru/ef/core/)
- [Bulma](https://bulma.io/)
- [C#](https://learn.microsoft.com/ru-ru/dotnet/csharp/)

## Как запустить проект

Установите путь к проекту 
```
cd notes-main
```

Установите зависимости

```
npm install --legacy-peer-deps @angular-devkit/build-angular
npm install bulma --save
```
Установите связь с DB в файле appsettings.json

```
Server=localhost;Username=name_user;Database=name_db;Password=password;Port=5432"
```

клиент -- ng serve
сервер -- откладка в IDE Visual Studio