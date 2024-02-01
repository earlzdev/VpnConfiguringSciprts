1) Зайти на сервер через ssh
2) Ввести четыре команды

git clone https://github.com/earlzdev/VpnConfiguringSciprts.git

cp -r /root/VpnConfiguringSciprts/* .

sudo chmod +x wg-conf

./wg-conf

3) Согласиться со всем прадлагаемым и дождаться конца установки


Получить конфигурацию сервера можно GET запросом

http://ip_address:8000/add_peer


