---
layout: post
title:  "Учет рабочего времени (под Android)"
version: 0.7
preview: /assets/img/projects/worktime-app.png
date: 2018-11-08
categories: java db time
---
##### Стэк: `Java 8` `Android` `H2` 
<!--more-->
Логичное продолжение [настольной версии]({% link _projects/2018-10-01-worktime-desktop.md %}). Заодно и 
повод попробовать сделать что-то под **Android**. Сделал под две версии **API — 15 и 25**, 
под оба свои телефона. 

![](/assets/img/projects/worktime-app-o.png)

Совершенно базовое приложение, использующее стандартные виджеты. Но пользоваться 
было довольно удобно. Посмотрел и азы работы с файловой системой — использовал не 
встроенный SQLite, а H2. И добавил возможность эту базу скопировать, чтобы скинуть 
для открытия в настольной версии. 