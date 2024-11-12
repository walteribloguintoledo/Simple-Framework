# Simple Framework
**SMPL Framework (Web Development Framework)**

Lightweight, easy to learn web development programming tool. It uses a very simple and easy to understand tools and programming languages. What to learn web development easily? Simple Framework works in any platform via Desktop or Mobile you can easily develop simple and complex application and systems.  It emphasis on simplicity and rapid development rather than infinite flexibility and features. Helps you quickly write simple yet powerful web applications and APIs.

*HTML5, Bootstrap 5 (CSS), JavaScript, JQuery, MustacheJS, PathJS, Slim Framework (PHP), MySQL, Idiorm (ORM)*


**Philosophy**

> The *[Pareto Principle](https://en.wikipedia.org/wiki/Pareto_principle)* states that roughly 80% of the effects come from 20% of the causes. In software development terms, this could be translated into something along the lines of 80% of the results come from 20% of the complexity. In other words, you can get pretty far by being pretty stupid.
> 

**HTML5 (Hypertext Markup Language 5)** is a markup language used for structuring and presenting hypertext documents on the World Wide Web. It was the fifth and final major HTML version that is now a retired [World Wide Web Consortium](https://en.wikipedia.org/wiki/World_Wide_Web_Consortium) (W3C) recommendation. The current specification is known as the HTML Living Standard. It is maintained by the [Web Hypertext Application Technology Working Group](https://en.wikipedia.org/wiki/Web_Hypertext_Application_Technology_Working_Group) (WHATWG), a consortium of the major browser vendors ([Apple](https://en.wikipedia.org/wiki/Apple_Inc.), [Google](https://en.wikipedia.org/wiki/Google), [Mozilla](https://en.wikipedia.org/wiki/Mozilla), and [Microsoft](https://en.wikipedia.org/wiki/Microsoft)).

**Bootstrap** (formerly ***Twitter Bootstrap***) is a free and open-source CSS framework directed at responsive, mobile-first front-end web development. It contains HTML, CSS and (optionally) JavaScript-based design templates for typography, forms, buttons, navigation, and other interface components.

As of May 2023, Bootstrap is the 17th most starred project (4th most starred library) on [GitHub](https://en.wikipedia.org/wiki/GitHub), with over 164,000 stars. According to W3Techs, Bootstrap is used by 19.2% of all websites.

**Bootstrap 5**
Bootstrap 5 was officially released on May 5, 2021.

***Major changes include:***
* New offcanvas menu component
* Removing dependence on jQuery in favor of vanilla JavaScript
* Rewriting the grid to support responsive gutters and columns placed outside of rows
* Migrating the documentation from Jekyll to Hugo
* Dropping support for Internet Explorer
* Moving testing infrastructure from QUnit to Jasmine
* Adding custom set of SVG icons
* Adding CSS custom properties
* Improved API
* Enhanced grid system
* Improved customizing docs
* Updated forms
* RTL support
* Built in darkmode support

**JavaScript** (/ˈdʒɑːvəskrɪpt/), often abbreviated as ***JS***, is a programming language and core technology of the Web, alongside HTML and CSS. 99% of websites use JavaScript on the client side for webpage behavior.

Web browsers have a dedicated JavaScript engine that executes the client code. These engines are also utilized in some servers and a variety of apps. The most popular runtime system for non-browser usage is Node.js.

**JQuery** is a JavaScript library designed to simplify HTML DOM tree traversal and manipulation, as well as event handling, CSS animations, and Ajax. It is free, open-source software using the permissive [MIT License](https://en.wikipedia.org/wiki/MIT_License). As of August 2022, [jQuery](https://jquery.com/) is used by 77% of the 10 million most popular websites. Web analysis indicates that it is the most widely deployed JavaScript library by a large margin, having at least three to four times more usage than any other JavaScript library.

**MustacheJS**
[mustache.js](https://github.com/janl/mustache.js) is a zero-dependency implementation of the mustache template system in JavaScript.

[Mustache](http://mustache.github.io/) is a logic-less template syntax. It can be used for HTML, config files, source code - anything. It works by expanding tags in a template using values provided in a hash or object.

We call it "logic-less" because there are no if statements, else clauses, or for loops. Instead there are only tags. Some tags are replaced with a value, some nothing, and others a series of values.

**PathJS**
[PathJS](https://github.com/mtrpcic/pathjs) is a lightweight, client-side routing library that allows you to create "single page" applications using Hashbangs and/or HTML5 pushState.

***Features***
* Lightweight
* Supports the HTML5 History API, the 'onhashchange' method, and graceful degredation
* Supports root routes, rescue methods, paramaterized routes, optional route components (dynamic routes), and Aspect Oriented Programming
* Well Tested (tests available in the ./tests directory)
* Compatible with all major browsers (Tested on Firefox 3.6, Firefox 4.0, Firefox 5.0, Chrome 9, Opera 11, IE7, IE8, IE9)
* Independant of all third party libraries, but plays nice with all of them

## Slim Framework

Slim is a PHP micro framework that helps you quickly write simple yet powerful web applications and APIs. At its core, Slim is a dispatcher that receives an HTTP request, invokes an appropriate callback routine, and returns an HTTP response. That’s it.

```
<?php
use Psr\Http\Message\ResponseInterface as Response;
use Psr\Http\Message\ServerRequestInterface as Request;
use Slim\Factory\AppFactory;

require __DIR__ . '/../vendor/autoload.php';

$app = AppFactory::create();

$app->get('/hello/{name}', function (Request $request, Response $response, array $args) {
    $name = $args['name'];
    $response->getBody()->write("Hello, $name");
    return $response;
});

$app->run();
```
### Slim Version 3.0
**[Download and Install](https://www.slimframework.com/docs/v3/)**

**MySQL** (/ˌmaɪˌɛsˌkjuːˈɛl/) is an open-source relational database management system (RDBMS). Its name is a combination of "My", the name of co-founder Michael Widenius's daughter *My*, and "SQL", the acronym for Structured Query Language. A relational database organizes data into one or more data tables in which data may be related to each other; these relations help structure the data.

[MySQL](https://en.wikipedia.org/wiki/MySQL) is free and open-source software under the terms of the GNU General Public License, and is also available under a variety of proprietary licenses. MySQL was owned and sponsored by the Swedish company MySQL AB, which was bought by Sun Microsystems (now [Oracle Corporation](https://en.wikipedia.org/wiki/Oracle_Corporation)). In 2010, when Oracle acquired Sun, Widenius forked the open-source MySQL project to create [MariaDB](https://en.wikipedia.org/wiki/MariaDB).

**Idiorm**
A lightweight nearly-zero-configuration object-relational mapper and fluent query builder for PHP5.

***Features***
* Makes simple queries and simple CRUD operations completely painless.
* Gets out of the way when more complex SQL is required.
* Built on top of PDO.
* Uses prepared statements throughout to protect against SQL injection attacks.
* Requires no model classes, no XML configuration and no code generation: works out of the box, given only a connection string.
* Consists of one main class called ORM. Additional classes are prefixed with Idiorm. Minimal global namespace pollution.
* Database agnostic. Currently supports SQLite, MySQL, Firebird and PostgreSQL. May support others, please give it a try!
* Supports collections of models with method chaining to filter or apply actions to multiple results at once.
* Multiple connections supported
* PSR-1 compliant methods (any method can be called in camelCase instead of underscores eg. find_many() becomes findMany()) - you'll need PHP 5.3+

Documentation
-------------
The documentation is hosted on Read the Docs: [idiorm.rtfd.org](https://idiorm.rtfd.org)

The documentation will now be in docs/_build/html/index.html

Let's See Some Code
-------------------

```php
$user = ORM::for_table('user')
    ->where_equal('username', 'j4mie')
    ->find_one();

$user->first_name = 'Jamie';
$user->save();

$tweets = ORM::for_table('tweet')
    ->select('tweet.*')
    ->join('user', array(
        'user.id', '=', 'tweet.user_id'
    ))
    ->where_equal('user.username', 'j4mie')
    ->find_many();

foreach ($tweets as $tweet) {
    echo $tweet->text;
}
```
