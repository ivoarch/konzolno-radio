konzolno-radio (конзолно-радио)
-------------------------------

Какво е това
------------

Просто конзолно интернет радио (или лесен начин) за слушане на български радио станции онлайн в GNU/Linux. (с `Mplayer`)

Зависимости
-----------

Използва `mplayer` за слушане/записване

Инсталация на последната стабилна версия (1.0.2)
---------------------------------------------------

    $ wget -c https://github.com/ivoarch/konzolno-radio/archive/1.0.2.tar.gz
    $ tar -xvf 1.0.2.tgz
    $ cd /път/до/konzolno-radio-1.0.2/
    $ make install

Инсталация на git версията
--------------------------

    $ git clone https://github.com/ivoarch/konzolno-radio
    $ cd /път/до/konzolno-radio/
    $ make install

По подразбиране `konzolno-radio` се инсталира в `/usr/local/bin`, ако искате да му промените пътя, редактирайте `Makefile`.

Bugs
----
За всякакви грешки или заявки, пишете на [GitHub](https://github.com/ivoarch/konzolno-radio) [issue](https://github.com/ivoarch/konzolno-radio/issues).

Лиценз
------
Проекта е лицензиран под MIT лиценз.
