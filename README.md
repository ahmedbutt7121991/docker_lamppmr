# docker_lamppmr
Linux-Apache-Mysql-PHP-PHPMyAdmin-MailHog-Redis
### for sending mails
sudo docker exec -it webserver php -r 'mail("foo@example.com", "test", time(), "From: Mailhog <mailhog@example.com>");'
