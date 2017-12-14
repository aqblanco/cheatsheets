Symfony 3 Cheatsheet
====================

Symfony's console
-----------------

All the above commands must be called as parameters to the Symfony console, wich, with no parameters, will show the help.

`php bin/console`

- **Start Symfony server:** `server:run`

- **Create new bundle:** `generate:bundle`

- **Create new database (using config from app/config/parameters.yml):** `doctrine:database:create`

- **Drop database:** `doctrine:database:drop --force`