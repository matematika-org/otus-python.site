# Исходники сайта [otus-python.site](https://otus-python.site)


<br/>

### Запустить otus-python.site для разработки

    $ docker-compose up


<br/>

### Запустить otus-python.site локально как сервис

<a href="https://sysadm.ru/linux/servers/containers/docker/install/">Docker</a> должен быть установлен.

    # cp otus-python.site.service /etc/systemd/system/otus-python.site.service

<br/>

    # systemctl enable otus-python.site.service
    # systemctl start  otus-python.site.service
    # systemctl status otus-python.site.service


http://localhost:4018

