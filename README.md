# SixthLab
Файл attention кладём в /etc/sysconfig/
Файл log.service в /etc/systemd/system
Выполняем systemctl enable log
Выполняем systemctl start log
При появлении в файле /var/log/attention.log слова ATTENTION будет произведена запись в journald
