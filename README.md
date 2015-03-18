# Постараюсь сегодня описать здесь выполненную работу (дополняется)
В последнем коммите находится мой локальный проект полностью с папками bower_components и stylesheets. Второй коммит ("done") не содержит этих папок.

Изменения вносил только в index.html, scss/_settings.scss, scss/app.scss, js/app.js и создал папку с парой изображений img.

Не нравится реализация шапки, точнее верхней навигации, на мобильных экранах.
Возможное решение: скрывать навигацию или сделать шапку в два ряда.

Реализовал фильтры не c помощью tabs, а с помощью accordion, так как tabs подразумевает отображение информации в одной постоянной области.
Для мобильных экранов фильтры должны перестраиваться в горизонтальный список. Перестраиваются именно пункты каждого фильтра. Возможно, задание подразумевало перестроение и самих фильтров. В таком случае, для мобильных экранов как раз подойдёт реализация с помощью tabs. Если это критично, могу переверстать.

P. S. В последнем коммите исправил опечатку после проверки w3c валидатором

# Foundation Compass Template

The easiest way to get started with Foundation + Compass.

## Requirements

  * Ruby 1.9+
  * [Node.js](http://nodejs.org)
  * [compass](http://compass-style.org/): `gem install compass`
  * [bower](http://bower.io): `npm install bower -g`

## Quickstart

  * [Download this starter compass project and unzip it](https://github.com/zurb/foundation-compass-template/archive/master.zip)
  * Run `bower install` to install the latest version of Foundation
  
Then when you're working on your project, just run the following command:

```bash
bundle exec compass watch
```

## Upgrading

If you'd like to upgrade to a newer version of Foundation down the road just run:

```bash
bower update
```
