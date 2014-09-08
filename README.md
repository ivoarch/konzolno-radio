konzolno-radio (конзолно-радио)
-------------------------------

Какво е това
------------

Просто конзолно интернет радио (или лесен начин) за слушане на български радио станции онлайн в GNU/Linux. (с `Mplayer`)

Зависимости
-----------

Използва `mplayer` за слушане/записване

Инсталация на последната стабилна версия (1.0.1.dev)
---------------------------------------------------

    $ wget -c https://github.com/ivoarch/konzolno-radio/archive/1.0.1.dev.tar.gz
    $ tar -xvf 1.0.1.dev.tgz
    $ cd /път/до/konzolno-radio-1.0.1.dev/
    $ make install

Инсталация на git версията
--------------------------

    $ git clone https://github.com/ivoarch/konzolno-radio
    $ cd /път/до/konzolno-radio/
    $ make install

По подразбиране `konzolno-radio` се инсталира в `/usr/local/bin`, ако искате да му промените пътя, редактирайте `Makefile`.
