# библиотеки для всех яп

- bcrypt (кеширование данных)
- soket.io (работа с web soket
    но лучше реализована в js)
- openGL (библиотека(api) для отрисовки изображений через
    любую видеокарту)
- openCL (библиотека(api) для расчета через-
    любую видеокарту)
- directX (библиотека(api) для отрисовки изображений через
        видеокарту nvidia)
- cuda (библиотека(api) для расчета через
        видеокарту nvidia)
- (для веба вместо openGl и openCl используется
webGl и webCL)
- асинхронный код поддерживается во всех языках
    очень упрощает написание многопоточного кода
- rx библитека для работы с реактивностью во всех популярных яп
    ![rx](./rx.jpeg)
    
# общее технологии для веб разработки:
- языки:
    - javascript (версии не ниже 2015 года)
    - typescript (продвинутый)
- язык разметки:
    - css 3
    - scss
    - sass
- библиотека стилей:
    - bootstrap
    - tailwindcss
    - Materialize
- приколюшки
    - Passport (регистрация на разных браузерах)

# парадигмы программирования облегчающие жизнь

- императивный
    - Процедурная
    - Структурная
    - Обобщённое программирование
    - Аспектно-ориентированная
    - Объектно-ориентированная
- декларативный 
    - Функциональная
    - Логическая
- Метапрограммирование
- Методы и алгоритмы
    - Автоматное
    - Потоков данных
    - Событийно-ориентированное
    - Реактивное
    - Сервис-ориентированное
# Особенности и фреймворки для каждого яп

## js/typescript:
- особености:
    - основа веб програмированая
        а так же популярен в desktop и мобильной разработке
    - самый хайповый язык на данный момент
        большинство современных парадигм
        часто в первую очаредь получаются у него
    - из-за очень простого синтаксиса,
        очень удобно обрабатывать различные данные
    - шустрый, так как компилируется в машиный код,
        оптимизирован на работу с процессорами
    - редко используют для рассчетов
        из-за невозможности созданий своих математических типов
    - мало хороших библиотек для работы с ос
    - последние парадигмы получает как правило именно этот яп
    - слаботипизированый( что может привести к неожиданным последствиям)
    - динамической типизацией( решает эту проблему typescript)
    - не яваня типизация( решает эту проблему typescript)
- фронтенд:
    - react
    - vue
    - angular
    - svetle (новая технолгия)
    - next (сначала нужно изучить react)
    - nuxt (сначала нужно изучить vue)
- бекенд:
    - express.js
    - nest.js (продвинутый уровень)
- оброботка даных:
    - lodash (функциональное программирование)
    - rxjs (реакционое программирование)
    - axios (получение даных)
    - sequlize, Knex.js, TypeORM(работа с реляционными базами данных)
    - Mongoose (работа с нереляциоными базами данных)
    - soket.io (работа с веб сокетами)
    - cheerio, jsdom, node-html-parser (парсинг html)
    - webpack, gulp.js (сборка и работа с препроцессорами)
    - Nodemailer (отправка писем)
    - Moment (работа с датой)
    - Validator (валидация)
    - GraphicsMagic, ImageMagick, sharp (обработка изображений)
    - PDFKit (создание pdf)
    - ploty.js (построение графиков)
    - p5.js (отрисовка графики на canvas)
- charts.js (построение диаграм)
- кросплатформеная
    - meteor.js (не слышал чтобы использовали)
- десктоп
    - electron.js
- мобильная
    - react native
    - javascript native
    - pwa(перегнать сайт в приложение за клик)
- игры
    - unity
    - cocos2d
    - ...
- нейронки
    - есть, но лень искать
- Iot
    - пишут, но не очень популярно(вроде)

## python
- особености
    - основа машиного обучения, аналитики данных
        и написание скриптов для серверов
    - большинство конструкций выполняются на
        c библиотеках, поэтому он довольно шустрый
    - очень много разных библиотек
        на все случаи жизни
    - много библиотек для работы с ос и системными файлами
    - плохо с играми
    - на нем пишутся не мало скриптов для Iot
    - строготипизированый
    - динамической типизацией(но есть поддержка типов с python 3.6)
    - неявная типизацией(но есть поддержка типов с python 3.6)
- бекенд:
    - flask
    - asyncio (сложнее, менее популярная)
    - Django( продвинутый)
- обработка данных:
    - nampy (обработка матриц)
    - scipy (продвинутая обработка матриц)
    - tanserflow (численое решение уравнений,
        - паралельный расчет задач, Работа с тензерами)
    - matplotlib (построение графиков)
    - ReactiveX (рактивное програмирование)
    - f (фп менее популярно чем на js из-за синтаксиса)
    - functools, itertools (встроеные библиотеки по фп)
    - Pillow (обработка изображений)
    - MoviePy (обработка видео)
    - NLTK, gensim, pymorphy2  (обработка естественного языка)
    - SQLAlchemy (работа с бд)
    - tqdm, manim (для работы с математикой)
    - Dash (продвинутая визуализация данных)
- десктоп
    - PyQT
    - wxPython
    - EEL (на основе web)
- мобильная
    - kivy
- нейронки
    - scikit-learn
    - pytorch
    - keras (продвинутый)
    - ...
- игры(очень простые)
    - pyxel
    - pygame

## c#
- особености
    - основа разработки кросплатформеных игр, vr(unity)
    - основа для создания desktop приложений на windows
    - есть почти все самые крутые фишки с других языков
    - язык интерпертируемо-компилируемый
        с кучей разных платформ
        - .NET официальная работающая только для windows
        - .NET Core windows + linux, но довольно сырая
        - mono разработана xamarin для все ос
        - Unity разработаная unity для всех фреймвороков
    так как куча разных платформ, то не мало проблем с поддержкой
    - есть затруднения с обработкой данных, поэтому не очень удобно
        писать скрипты на нем
    - microsoft очень рукожопы
    - строготипизированый
    - со статической типизацией( но можно использовать динамическую)
    - явная типизацией
- обработка данных
    - entity framework (база данных)
    - ...
- бекенд
    - asp.net
    - asp.net core
- десктоп
    - windows form
    - ...
- кросплатформеная
    - xamarin
- игры
    - unity

## с++
- особености
    - основа всех языков,
    - на нем пишутся библиотеки для js, python и др.
    - на нем пишутся большинство движков и языков(например Python)
    - пишутся большинство драйверов
    - пишутся код для Iot
    - пишутся высокопроизводительные игры
    - разрабатывался как язык, который может
        заменить любую программу на асемблере
    - поэтому очень шустрый язык,
        позволяющий взаимодействовать со всеми параметрами железа
    - имеет очень много компиляторов, поэтому
        есть проблема с унифицированностью кода
    - менее охотно развивается язык, по сравнению с другими,
        то есть не все реализованы в нем современные фишки
        поэтому труднее писать код для веба, мобильных приложений
        и обработки данных
    - слаботипизированый
    - со статической типизацией( но можно использовать динамическую)
    - явная типизацией
- обработка данных
    - ...
- десктоп
    - windows form
- игры
    - UnrealEngine
    - CryEngine
    - ...

## java
- особености
    - основа андроид разработки и big data
    - все скрипты для мобильных приложений
        пишутся на java
    - разрабатывался как кросплатформенный язык
        приложения на котором могли бы запуститься
        на любом устройстве
    - очень не охотно обновляется, поэтому там
        мало современных фишек
- обработка данных:
    - загуглите...
- десктоп
    - Swing API
    - java 2d
    - java 3d
    - ...
- мобильная
    - android studio

# молодые языки:

- dart
    - особености
        - основа кросплатформеной мобильной разработки
        - разработан компанией google как алтернатива js
            - но он долго не мог обрести известность
            - до появления библитеки flutter
            - которая является более качественой заменой react native
        - молодой язык, поэтому достаточно мало библиотек
    - обработка данных
        - загуглите
    - мобильная
        - flutter

- rust
    - особености
        - набирающий популярность язык, постепено вытесняющий c++
            является более безопастной современной альтернативой c++
        - большинство вещей написанных на c++ требущих повышеную
            безопастность переписывается на этот язык
        - реализовано не мало интересных новых концепций
            облегчающих разработку
        - молодой язык, поэтому достаточно скудная база библиотек
    - обработка данных:
        - ...
    - бекенд:
        - rocket
        - flosse
    - десктоп:
        - ...

- go
    - особености
        - основа для написания огромных серверов
        - язык является альтернативой c++
        - создан был для того, чтобы решить проблему
            с разным стилем написания кода и стабильности написаных
            приложений
        - вариацию этого языка использует игровой движок
            gobot, который вытесняет unity
    - обработка данных:
        - ...
    - бекенд:
        - встроен в яп
    - игры:
        - gobbot

- swift
    - особености
        - основа для написания приложений на mac/ios
        - современный язык, поддерживающий большинство технологий
        - требуется mac Для написания на данном яп
    - обработка данных:
        - ...
    - десктоп:
        - ...
    - мобильная
        - SwiftyFORM
        - Chatto
        - SwiftyOnboard
        - ....

> под работает вместе с java имеется ввиду,
>    что вы можете использовать библиотеки java в kotlin(scala)
>   и наоборот ибо каждый файл скомпилируется в индентичный byte code

- kotlin (работает вместе с java)
    - особености
        - основа мобильной разработки
        - разработана российскими разработчиками jetbrains
            как замена java
        - данный язык компилируется в java byte код
            поэтому можно писать код в связке с java
        - более охотно обновляется чем java
        - поддерживает все-то что поддерживает java

- scala(работает вместе с java)
    - особености
        - функциональная версия языка java

- F# (работает с c#)
    - особености
        - функциональная версия языка c#

- ruby
    - особености
        - прославился за счет бекенд фреймворка  ruby on rails
        - который был одно время одним из самых крутых
    - бекенд
        - ruby on rails

- php
    - особености
        - самый лучший язык для создания простых web приложений
        - на нем написано большинство конструкторов для браузеров
        - приложения на php легче всего выкладывать на хостинг
            так как он поддерживается на всех хостингах
        - плохо поддерживает все современные веб технологии
    - обротка данных:
        - phpQuery (парсинг html)
        - ...
    - бекенд
        - натинвый php
        - laravel(продвинутый)
        - simfony(продвинутый)
- paskal и диалекты
    - особености
        - все еще на что-то способен, но не очень
    - desktop
        - delphi
        - visual paskal
    - игры
        - love

# для рофельных чувачков
- haskel
    - особености
        - самый любимый функциональный язык у всех программистов

- lisp
    - особености
        - самый первый функциональный язык язык
        - трушное фп

- OCaml
    - особености
        - самый рофляный объектно-ориентированный язык функционального программирования

- prolog
    - особености
        - первый яп реализующий логическую парадигму

- basic
    - особености
        - изучали в совестких школах и в некоторых современных
        - рофляно писать на visual basic
    - desktop
        - visual basic

- ассемблер
    - особености
        - самый популярный яп низкого уровня
        - на нем можно написать все что угодно
        - есть 2 версии x86 и arm для разных типов процессоров
        - написание кода очень сильно зависит от
            количества команд процессора, ядер, разрядности
            так-как ты практически буквально пишешь машинным
            кодом
