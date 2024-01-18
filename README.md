# Littlelemon
Welcome to littlelemon 

There are the useful **`URLs`** to navigate easily in **`web browser`** or **`Insomnia`**.


### Users
Users can `create new user` and can `login` and `logout`.
Users can only see their informations. Admin can see list of all users.

|URLs|Admin|User|
|:----- |:------|:-------|
|http://127.0.0.1:8000/auth/users/|GET|GET|
|http://127.0.0.1:8000/api-auth/login/|POST|POST|
|http://127.0.0.1:8000/api-auth/logout/|POST|POST|

### Token Generation
Users can generate token for authentication.
Use `POST` method with `username` and `password` for token generation.

|URLs|Admin|User|
|:----- |:------|:-------|
| http://127.0.0.1:8000/api/api-token-auth/ | POST | POST |

### Home page
Homepage for `Littlelemon` website.

http://127.0.0.1:8000/api/

### Menu
Admin can `get` information about menu items and can `create` new menu-items. Admin can `update` or `delete` single menu item.

User can `get list` of menu items and can `get` information about Single menu item.

|URLs|Admin|User|
|:----- |:------|:-------|
|http://127.0.0.1:8000/api/menu-items/|GET, POST|GET|
|http://127.0.0.1:8000/api/menu-items/{menuitemID}/|GET, PUT, PATCH, DELETE|GET|

### Table Reservation
You can use these `method` for table reservations.

|URLs|Admin|User|
|:----- |:------|:-------|
|http://127.0.0.1:8000/tables/|GET, POST, PUT, PATCH, DELETE|GET, POST, PUT, PATCH, DELETE|



Created by **`Abhinav Anand`**

Thanks
