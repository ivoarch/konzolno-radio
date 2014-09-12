konzolno-radio (конзолно-радио)
-------------------------------

Какво е това
------------

Просто конзолно интернет радио (или лесен начин) за слушане на български радио станции онлайн в _GNU/Linux_. (с `Mplayer`)

Характеристики
--------------

- Написан на **bash**
- Управление от линията на команди (терминал)
- Не се нуждаете от **GUI** интерфейс да слушате музика
- Съпорт за записване на любимите предавания на **.mp3** файл
- Много бърз
- Лесен за научаване и използване
- **KISS** дизайн

Зависимости
-----------

- Използва `mplayer` за слушане/записване
- Стандартните **UNIX** средства `sed`, `egrep`, `pr`

Инсталация на последната стабилна версия (1.0.3)
---------------------------------------------------

    $ wget --no-check-certificate https://github.com/ivoarch/konzolno-radio/archive/1.0.3.tar.gz
    $ tar -xvf 1.0.3.tar.gz
    $ cd /път/до/konzolno-radio-1.0.3/
    $ make install

Инсталация на git версията
--------------------------

    $ git clone https://github.com/ivoarch/konzolno-radio
    $ cd /път/до/konzolno-radio/
    $ make install

По подразбиране `konzolno-radio` се инсталира в `/usr/local/bin`, ако искате да му промените пътя, редактирайте `Makefile`.

Инсталирай от RPM пакет
-----------------------

За _RedHat_ базираните дистрибуции, _Fedora/CentOS_ и тн..

- [konzolno-radio-1.0.3-1.noarch.rpm](https://dl.dropboxusercontent.com/u/66222581/repo/ivorepo/i386/repoview/konzolno-radio.html)
- [ivorepo.repo](https://dl.dropboxusercontent.com/u/66222581/repo/ivorepo/ivorepo.repo)

Bugs
----
За всякакви грешки или заявки, пишете на [GitHub](https://github.com/ivoarch/konzolno-radio) [issue](https://github.com/ivoarch/konzolno-radio/issues).

Благодарности
--------------
На Etem Hyusnev [@etem](https://github.com/etem) за неуморното тестване на приложението, по време на разработката.

Лиценз
------
Проекта е лицензиран под MIT лиценз.
