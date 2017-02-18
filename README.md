# API REST SLIM PHP

Ejemplo de API REST con Slim PHP.


```
TRUNCATE users;

INSERT INTO `users` VALUES ('1', 'Juan', 'juanmartin@delpotro.com');
INSERT INTO `users` VALUES ('2', 'Federico', null);
INSERT INTO `users` VALUES ('3', 'Leo', null);
INSERT INTO `users` VALUES ('4', 'Carlos', null);
INSERT INTO `users` VALUES ('5', 'Diego', 'diego@gmail.com');

TRUNCATE tasks;

INSERT INTO `tasks` (`id`, `task`, `status`, `created_at`) VALUES
(1, 'Find bugs', 1, '2016-04-10 23:50:40'),
(2, 'Review code', 1, '2016-04-10 23:50:40'),
(3, 'Fix bugs', 1, '2016-04-10 23:50:40'),
(4, 'Refactor Code', 1, '2016-04-10 23:50:40'),
(5, 'Push to prod', 1, '2016-04-10 23:50:50');
```
