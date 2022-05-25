### Setup ###
If PHP and/or composer (version 2) is NOT installed locally:

- Run `docker-compose up -d` to start a PHP 8.1 FPM docker container.
- Run `docker-compose run php composer i` to install dependencies.
- Run `docker-compose run php php vendor/bin/phpstan analyze --verbose` to cause the error

If PHP AND composer (version 2) IS installed locally:

- Run `composer i` to install dependencies.
- Run `php vendor/bin/phpstan analyze --verbose` to cause the error
