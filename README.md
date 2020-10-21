# docker_lamppmr
Linux-Apache-Mysql-PHP-PHPMyAdmin-MailHog-Redis
### for sending mails
sudo docker exec -it webserver php -r 'mail("foo@example.com", "test", time(), "From: Mailhog <mailhog@example.com>");'
### For sending Mails using MAILGUN
cd /usr/sbin/swaks
./swaks --auth --server smtp.mailgun.org --au <postmaster@sandboxxxx.mailgun.org> --ap <password> --to <registered email> --h-Subject: "Hello" --body 'Testing some Mailgun awesomness!'
