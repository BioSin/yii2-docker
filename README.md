Place the code to your project root path

At your DSN at main-local.php use something like that:
'mysql:host=dbContainer;dbname=testdb'
, where:
dbContainer - your mysql container name from docker-compose.yml

Also, add nginx/data/* to .gitignore files

Rename server_name at nginx/vhost.conf
and add your DNS name to hosts file
