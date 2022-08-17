### О коде

Руководство по созданию PHP приложения без фреймворка [[Перевод](https://github.com/PatrickLouys/no-framework-tutorial)]


#### **Вступление**

Если вы новичок в PHP, этот учебник не для вас. Данное руководство предназначено для людей, которые постигли основы PHP и уже знакомы с OОП.

Также, вы должны быть знакомы с принципами [SOLID](https://ru.wikipedia.org/wiki/SOLID). Перед тем, как приступить к учебному пособию, рекомендую  ознакомиться с ними.

Я видел, как много людей заходили в чат Stack Overflow PHP и спрашивали, хорош ли framework X для разработки приложения. Но в большинстве случаев, ответ не зависел от фреймворка, им просто нужно было начать разработку на PHP. Но многих такие ответы пугали, так как они не знали с чего им начать.

Итак, моя цель в том, чтобы предоставить простой ресурс, на который можно указать людям. Использование фреймворка, в некоторых случаях избыточно, и написание приложения с нуля с помощью различных сторонних пакетов намного проще, чем кажется.

Этот учебник был написан для PHP 7.0 или более новых версий. Если вы используете более старую версию, пожалуйста, обновите ее перед началом работы. Я рекомендую вам использовать текущую [стабильную версию](https://php.net/downloads.php).


Давайте сразу начнем с [первой части >>](01-front-controller.adoc).


#### Оглавление

*  [Front Controller](01-front-controller.adoc)
*  [Composer](02-composer.adoc)
*  [Error Handler](03-error-handler.adoc)
*  [HTTP](04-http.adoc)
*  [Router](05-router.adoc)
*  [Dispatching to a Class](06-dispatching-to-a-class.adoc)
*  [Inversion of Control](07-inversion-of-control.adoc)
*  [Dependency Injector](08-dependency-injector.adoc)
*  [Templating](09-templating.adoc)
*  [Dynamic Pages](10-dynamic-pages.adoc)
*  [Page Menu](11-page-menu.adoc)
*  [Frontend](12-frontend.adoc)


#### Ресурс использует разметку AsciiDoc:

* AsciiDoc extension
* asciidoctor
* ruby-asciidoctor-pdf

#### Команда для конвертации в pdf:

```shell

$ make pdf

```