Деплой SPA приложения, использующего Blazor WASM и не зависящее от сервера.

link: https://mahoninje.github.io/BlazorWASMAppStatic/

В localStorage клиента "захардкожены" 2 аккаунта с разными ролями:
1) login: 'user', password 'user', role: 'SimpleUser'
2) login: 'admin', password 'admin', role: 'Admin'
По ним логинимся и юзаем SPA. Страница /admin - 'админ. панель' доступна только пользователям с ролью 'Admin'
