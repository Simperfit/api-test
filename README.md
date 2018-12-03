This application is a symfony API based on API-platform.

It needs: 

- Mysql or Postgresql,
- http/h2 server (nginx or apache)  
- PHP 7.2 - composer (need to install the dependencies) (https://getcomposer.org/)
- Symfony 4.2, it need icu at least.

if the nginx dies, it should be restarted, if the php server dies it should be restarted automatically
if the database dies, we should restart it manually
