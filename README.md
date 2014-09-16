konzolno-radio (конзолно-радио)
-------------------------------

Какво е това
------------

Просто конзолно интернет радио (или лесен начин) за слушане на български радио станции онлайн в _GNU/Linux_. (с `Mplayer`)

Характеристики
--------------

- Повече от 40 радиостанции (български)
- Съпорт за записване на любимите предавания на **.mp3** файл
- Написан на `bash`
- Управление от линията на команди (терминал)
- Не се нуждаете от GUI интерфейс да слушате музика
- Лесен за научаване и използване
- KISS дизайн

Зависимости
-----------

- Използва `mplayer` за слушане/записване
- Стандартните **UNIX** средства `sed`, `egrep`, `pr`

Инсталация от Source
----------------------

    $ wget --no-check-certificate https://github.com/ivoarch/konzolno-radio/archive/1.0.3.tar.gz
    $ tar -xvf 1.0.3.tar.gz
    $ cd /път/до/konzolno-radio-1.0.3/
    # make install

Инсталация на git версията
--------------------------

    $ git clone https://github.com/ivoarch/konzolno-radio
    $ cd /път/до/konzolno-radio/
    # make install

По подразбиране `konzolno-radio` се инсталира в `/usr/local/bin`, ако искате да му промените пътя, редактирайте `Makefile`.

Инсталация за RedHat/Fedora/Centos
-----------------------

От терминал: _(препоръчително)_

    $ cd /etc/yum.repos.d/
    # wget -c https://dl.dropboxusercontent.com/u/66222581/repo/ivorepo/ivorepo.repo
    # yum install konzolno-radio

Със един клик:

- [konzolno-radio-1.0.3-1.noarch.rpm](https://dl.dropboxusercontent.com/u/66222581/repo/ivorepo/i386/konzolno-radio-1.0.3-1.noarch.rpm)

Инсталация за Debian/Ubuntu/Linux Mint
------------------------

От терминал: _(препоръчително)_

    # echo "deb http://dl.bintray.com/etem/deb /" | sudo tee -a /etc/apt/sources.list
    # apt-get install konzolno-radio

Със един клик:

- [konzolno-radio_1.0.3_all.deb](http://dl.bintray.com/etem/deb/konzolno-radio_1.0.3_all.deb)

Инсталация за Arch linux/Manjaro
----------------------------

    $ yaourt -S konzolno-radio

Bugs
----
За всякакви грешки или заявки, пишете на [GitHub](https://github.com/ivoarch/konzolno-radio) [issue](https://github.com/ivoarch/konzolno-radio/issues).

Благодарности
--------------
На Etem Hyusnev [@etem](https://github.com/etem) за помощта със дебиан пакета, и неуморното тестване на приложението.

Лиценз
------
Проекта е лицензиран под MIT лиценз.
