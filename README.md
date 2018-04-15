# vboxwebsrv
скопировано и модифицировано для коннекта по ключу с clue/vboxwebsrv

Предварительно копируем ключ на сервер:
ssh-copy-id -i ~/.ssh/id_rsa.pub user@ip_address
Далее:
docker run -d -v ~/.ssh/id_rsa:/id_rsa dry1d/vboxwebsrv user@ip_address
