# day_6_crud

A simple and basic CRUD application (Create, Read, Update, Delete) using Node.js, Express, MySQL & EJS Templating Engine.

to start the application :
```use nodemon index or npm start```

``` I'm using xampp to create database ```

Creating database and table

```
CREATE DATABASE node_crud;

use node_crud;

CREATE TABLE `users` (
  `id` int(11) NOT NULL,
  `name` varchar(150) NOT NULL,
  `email` varchar(150) NOT NULL,
  `phone_no` varchar(25) NOT NULL
) ENGINE=InnoDB DEFAULT CHARSET=latin1;
 
 
ALTER TABLE `users`
  ADD PRIMARY KEY (`id`);
 
ALTER TABLE `users`
  MODIFY `id` int(11) NOT NULL AUTO_INCREMENT, AUTO_INCREMENT=1;
```
