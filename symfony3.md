Symfony 3 Cheatsheet
====================

Symfony's console
-----------------

All the below commands must be called as parameters to the Symfony console, wich, with no parameters, will show the help.

`php bin/console`

- **Start Symfony server:** `server:run`

- **Create new bundle:** `generate:bundle`

- **Create new database (using config from app/config/parameters.yml):** `doctrine:database:create`

- **Drop database:** `doctrine:database:drop --force`

- **Create Entity:** `doctrine:generate:entity`

- **Update database schema (with --force or --dump-sql, not recommended for production):** `doctrine:schema:update`

- **Generate missing getter and setter methods for a entity/bundle/namespace:** `doctrine:generate:entities` *name*

- **Create a form class from an entity:** `generate:doctrine:form` *entity*

- **Create CRUD for an entity:** `generate:doctrine:crud --entity=` *entity* ` --format=annotation --with-
write --no-interaction`