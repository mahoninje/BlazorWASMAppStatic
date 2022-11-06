Деплой SPA приложения, использующего Blazor WASM и не зависящее от сервера.

link: https://mahoninje.github.io/BlazorWASMAppStatic/

В localStorage клиента "захардкожены" 2 аккаунта с разными ролями:
1) login: 'user', password 'user', role: 'SimpleUser'
2) login: 'admin', password 'admin', role: 'Admin'
По ним логинимся и юзаем SPA. Страница /admin - 'админ. панель' доступна только пользователям с ролью 'Admin'
Пароли хранятся в зашифрованном виде.
Справа сверху кнопка 'Logout' для выхода из аккаунта.

Screenshots:
![admin](https://user-images.githubusercontent.com/51750167/200148181-408c5647-40f9-44a8-8d47-15aeb4af76f0.PNG)
![user](https://user-images.githubusercontent.com/51750167/200148193-45bd9b41-d732-42d3-93ba-74611cc5eb60.PNG)
