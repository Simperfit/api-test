This application is a symfony API based on API-platform.

It needs: 

- Mysql or Postgresql,
- http/h2 server (nginx or apache)  
- composer (need to install the dependencies)
- PHP 7.2

if the nginx dies, it should be restarted, if the php server dies it should be restarted automatically
if the database dies, we should restart it manually
