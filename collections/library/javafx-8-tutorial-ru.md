﻿---
layout: article
title: "Учебник по JavaFX 8 (Русский)"
date: 2014-04-19 00:00
updated: 2016-04-20 00:00
description: "Этот учебник состоящий из семи частей, введет вас в проектирование, программирование и развёртывание приложения Адресной книги, с помощью JavaFX"
slug: javafx-8-tutorial/ru
github: https://github.com/marcojakob/code.makery.ch/edit/master/collections/library/javafx-8-tutorial-ru.md
image: /assets/library/javafx-8-tutorial/addressapp.png
published: true
prettify: true
comments: true
sidebars:
- header: "Статьи в этой серии"
  body:
  - text: "Введение"
    link: /library/javafx-8-tutorial/ru/
    paging: Intro
    active: true
  - text: "Часть 1: Scene Builder"
    link: /library/javafx-8-tutorial/ru/part1/
    paging: 1
  - text: "Часть 2: Модель и компонент TableView"
    link: /library/javafx-8-tutorial/ru/part2/
    paging: 2
  - text: "Часть 3: Взаимодействие с пользователем"
    link: /library/javafx-8-tutorial/ru/part3/
    paging: 3
  - text: "Часть 4: Стилизация с помощью CSS"
    link: /library/javafx-8-tutorial/ru/part4/
    paging: 4
  - text: "Часть 5: Хранение данных в XML"
    link: /library/javafx-8-tutorial/ru/part5/
    paging: 5
  - text: "Часть 6: Статистическая диаграмма"
    link: /library/javafx-8-tutorial/ru/part6/
    paging: 6
  - text: "Часть 7: Развертывание"
    link: /library/javafx-8-tutorial/ru/part7/
    paging: 7
languages: 
  header: Языки
  collection: library
  item: javafx-8-tutorial
  part: 
  active: ru
---

В 2012 году я написал для своих студентов очень детальный [учебник по JavaFX 2](http://code.makery.ch/library/javafx-2-tutorial/). Он был прочитан многими людьми из разных частей света, и они очень позитивно отозвались о данном материале. Поэтому я решил переписать этот учебник для новой версии JavaFX 8 (об изменениях вы можете почитать здесь - [Обновление до JavaFX 8 - Что Нового](http://code.makery.ch/blog/update-to-javafx-8-whats-new/ "Update to JavaFX 8 - What's New")).

В этом учебнике я расскажу о проектировании, программировании и развёртывании приложения с функциональностью адресной книги. Так будет выглядеть наше приложение в конце разработки:

![Screenshot AddressApp](http://code.makery.ch/assets/library/javafx-8-tutorial/addressapp.png "AdressApp")


## Нам предстоит научиться

- Создавать и запускать проект JavaFX;
- Использовать приложение Scene Builder для проектирования пользовательского интерфейса;
- Структурировать приложение с помощью шаблона Модель-Представление-Контроллер (MVC);
- Использовать коллекцию `ObservableList` для автоматического обновления пользовательского интерфейса;
- Использовать компонент `TableView` и реагировать на выбор ячеек в таблице;
- Создавать пользовательские всплывающие диалоги для редактирования записей в приложении;
- Выполнять проверку пользовательского ввода;
- Изменять дизайн приложения JavaFX с помощью каскадных таблиц стилей (CSS);
- Хранить данные приложения в виде XML-файла;
- Сохранять последний открытый путь к файлу в настройках пользователя;
- Создавать диаграммы JavaFX для отображения статистики;
- Развёртывать приложение JavaFX с помощью процесса нативной упаковки (native package).

**Это довольно много!** А это значит, что после изучения данного материала мы будем знать, как создавать сложные приложения с помощью JavaFX.


## Как пользоваться этим учебником

Есть два варианта использования этого материала:

- **учите много**: Создавайте с нуля свой проект JavaFX и постепенно наполняйте кодом его классы и методы.
- **учите быстро**: Импортируйте исходники кода для каждой части учебника в вашу среду разработки а потом пытайтесь понять данный материал.

Я надеюсь, что, что вам понравится! Начнём с [Часть 1: Приложение Scene Builder](/library/javafx-8-tutorial/ru/part1/ "Part 1: Scene Builder.").

<div class="alert alert-success">
  <strong><i class="fa fa-trophy"></i> Attribution:</strong> Russian translations have been contributed by 
  <ul>
    <li><a href="https://github.com/sobolevstp" class="alert-link">Sobolev Stepan</a></li> 
    <li><a href="https://github.com/eugenedotru" class="alert-link">Evgen Ishchenko</a></li>
	<li><a href="https://github.com/leonisx" class="alert-link">Stavila Leonid</a></li>
  </ul>
  Thank you very much!
</div>

