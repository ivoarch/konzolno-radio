:radio: konzolno-radio (конзолно-радио)
-------------------------------

> Гуру начина за слушане на български радиостанции онлайн в GNU/Linux !

**konzolno-radio** е шел скрипт, конзолно интернет радио, което има за цел да 
бъде бързо, и лесно за използване, като по този начин да улесни слушането на 
български радиостанции онлайн в Gnu/Linux (с помощта на `Mplayer`). 

# Новини

**Излезна новата версия 1.0.9!**

- Обновени URL адреси за Radio MaxxFM, Radio Belisimo, Radio City .
- Добавяне на Volume информация .
- Премахване на ICY info от информацията .
- Премахване на Радио Веселина, добавяне на Радио Ултра.
- Премахване на MFM Hitradio, добавяне на Radio Mixx .
- Премахване на Dee Jay, добавяне на Радио Vega+ .
- Добавяне на Пример във **-s|--stream** опцията .
- Премахване на излишната/нежелана информация .

# Снимки

![preview](http://storage5.static.itmages.ru/i/15/0823/h_1440336841_9775259_f3a36a0388.png)

# Характеристики

- Около 50 радиостанции (български).
- Сортиране на радиостанциите според жанра.
- Записване на любимите предавания на (.mp3) файл.
- Управление от линията на команди (терминал).
- Ремоте контрол през fifo.
- Функция за събуждане (аларма).
- Не се нуждаете от GUI интерфейс да слушате музика.
- Лесен за научаване и използване.
- Не се изисква никаква настройка.
- KISS дизайн.

# Зависимости

- Използва `mplayer` за слушане/записване .
- Нуждаете се от `curl` ако искате да актуализирате версията през опциите **-u|--update** на програмата .
- Стандартните UNIX средства `cat`, `sed`, `egrep`, `pr`, `less` .
- Нуждаете се от `sound-theme-freedesktop` ако искате да използвате алармата .

# Инсталация

## Arch Linux

```
$ git clone https://gist.github.com/ec4ed298d879cf9b9588.git 
$ cd ec4ed298d879cf9b9588 
$ makepkg -si
```

Source: [PKGBUILD](https://gist.github.com/ec4ed298d879cf9b9588)

## Debian/Ubuntu/Mint 

```
# echo "deb http://dl.bintray.com/etem/deb /" | sudo tee -a /etc/apt/sources.list
# apt-get install konzolno-radio
```

Source: [DEB](http://dl.bintray.com/etem/deb/konzolno-radio_1.0.9_all.deb)

## RHEL/CentOS/Fedora

```
# yum install "http://www.stotinkaos.net/stotinkaOS/repo/7/x86_64/konzolno-radio-1.0.9-1.el7.centos.sos.noarch.rpm"
```

Source: [RPM](http://www.stotinkaos.net/stotinkaOS/repo/7/x86_64/konzolno-radio-1.0.9-1.el7.centos.sos.noarch.rpm)

## Други дистрибуции

```
$ wget --no-check-certificate https://github.com/ivoarch/konzolno-radio/archive/1.0.9.tar.gz 
$ tar -xvf 1.0.9.tar.gz 
$ cd /път/до/konzolno-radio-1.0.9 
# make install
```

# Благодарности

- На авторът на първоначалната версия (шаблона), Asen Bozhilov @abozhilov.
- На Etem Hyusnev @etem за помощта със дебиан пакета, и неуморното тестване на приложението.
- На @Red D за дизайна на логото!

# Лиценз

Проекта е лицензиран под MIT лиценз.
