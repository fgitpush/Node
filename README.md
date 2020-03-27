# Node Interview Questions & Answers

> Click :star: if you like the project. Pull Request are highly appreciated.

### Table of Contents

| No. | Questions |
| --- | --------- |
|1  | [What is Django?](#What-is-Django) |
|2  | [What is the difference between Flask and Django?](#What-is-the-difference-between-Flask-and-Django) |
|3  | [Name some companies that make use of Django?](#Name-some-companies-that-make-use-of-Django) |
|4  | [What are the features of Django?](#What-are-the-features-of-Django) |
|5  | [How to check Django Version?](#How-to-check-Django-Version) |
|6  | [Explain Django architecture?](#Explain-Django-architecture) |
|7  | [What is django-admin?](#What-is-django-admin) |
|3  | [What is django's default DB?](#What-is-djangos-default-DB) |
|4  | [Does the Django framework scale?](#Does-the-Django-framework-scale) |
|5  | [Does Django support NoSQL?](#Does-Django-support-NoSQL) |
|6  | [What is a filter hook?](#What-is-a-filter-hook) |
|7  | [What are Seeders?](#what-are-seeders) |
|8  | [What are Service Providers?](#what-are-service-providers) |
|9  | [What is Middleware?](#what-is-middleware) |
|10 | [What is ORM?](#what-is-orm) |
|11 | [What is Eloquent?](#what-is-eloquent) |
|12 | [What is Query Builder?](#what-is-query-builder)
|13 | [What are Facades?](#what-are-facades) |
|14 | [What is Repository Pattern?](#what-is-repository-pattern) |
|15 | [What is Authentication using Passport CSRF XSRF?](#What-is-Authentication-using-Passport-CSRF-XSRF) |
|16 | [What is Unit testing?](#what-is-unit-testing) |
|17 | [What is Caching?](#what-is-caching) |
|18 | [How to setup Emails?](#how-to-setup-emails) |
|19 | [What are Queues?](#what-are-queues) |
|20 | [What are Jobs?](#what-are-jobs)
|21 | [What are Advanced Eloquent and Query Builder?](#what-are-advanced-eloquent-and-query-builder) |
|22 | [Which is Error management?](#which-is-error-management) |
|23 | [How to create an API?](#how-to-create-an-api) |
|24 | [What are Events?](#what-are-events) |
|25 | [What are Listeners?](#what-are-listeners) |
|26 | [What are Payments and cashier?](#what-are-payments-and-cashier) |
|27 | [What is Test Driven Development?](#what-is-test-driven-development) |
|28 | [What is Package development?](#what-is-package-development) |
|29 | [What are Laravel Scout search and Algolia?](#what-are-laravel-scout-search-and-algolia) |
|30 | [What is Socialite and Auth?](#what-is-socialite-auth) |
|31 | [What is Vue-js?](#what-is-vue-js) |
|32 | [How to connect Laravel with other SQL databases?](#How-to-connect-Laravel-with-other-SQL-databases) |
|33 | [How to connect Laravel with non-SQL databases?](#How-to-connect-Laravel-with-non-SQL-databases) |
|34 | [What is Lumen?](#what-is-lumen) |
|35 | [What is Redis?](#what-is-redis) |
|36 | [What is Memcache?](#what-is-memcache) |
|37 | [What is Horizontal scaling?](#What-is-Horizontal-scaling) |
|38 | [What is Vertical scaling?](#What-is-Vertical-scaling) |
|39 | [What is Single Page Application in Laravel?](#What--Single-Page-Application-in-Laravel) |
|40 | [What are Microservices in Laravel?](#What-are-Microservices-in-Laravel) |
|41 | [What is CSRF and JWT token?](#what-is-CSRF-and-JWT-token) |
|42 | [What is Service Oriented Architecture in Laravel?](#what-is-soa) |
|43 | [What are Validations and custom validations?](#what-are-validators) |
|44 | [What is Composer?](#what-is-composer) |
|45 | [What is Symfony?](#what-is-symfony) |
|46 | [What is Route caching?](#what-is-route-caching) |
|47 | [What are Default packages: Cashier,Envoy,Passport,Scout,Socialite,Horizon?](#default-packages) |
|48 | [What are Named routes?](#what-are-named-routes) |
|49 | [What is Dependency injection in Laravel?](#what-is-dependency-injection) |
|50 | [What are Laravel contracts?](#what-are-contracts) |
|51 | [What is Query log?](#what-is-query-log) |
|52 | [What are Laravel Traits?](#what-are-laravel-traits) |
|53 | [What are Bundles in Laravel?](#what-are-Bundles-in-Laravel) |
|54 | [What are System requirements for Laravel?](#what-are-system-requirements-for-laravel) |
|55 | [What are Aggregate methods in query builder?](#what-are-aggregate-methods-in-query-builder) |
|56 | [What is Singelton design pattern?](#what-is-singelton-design-pattern) |
|57 | [What is Reverse routing?](#what-is-reverse-routing) | 
|58 | [What are Popular composer packages?](#what-are-Popular-composer-packages) |
|59 | [How to get the data from more than 3 table without using a join?](#how-to-get-the-data-from-more-than-3-table-without-using-a-join) |
|60 | [List some artisan commands](#list-some-artisan-commands) |
|61 | [What are Sessions?](#what-are-sessions) |
|62 | [What are Cookies?](#what-are-cookies) |
|63 | [What is Current version of PHP, MySQL, Laravel, MongoDB etc?](#what-is-current-version-of-PHP-MySQL-Laravel-MongoDB-etc) |
|64 | [Describe design architecture of an app?](#Describe-design-architecture-of-an-app) |
|65 | [What are SQL Injections?](#What-are-SQL-Injections) |
|66 | [How to call static methods?](#How-to-call-static-methods) |
|67 | [How to achieve multiple DB hosts?](#How-to-achieve-multiple-DB-hosts)
|68 | [What is Abstract class?](#what-is-Abstract-class) |
|69 | [What are Default ports for MySQL Email etc?](#what-are-Default-ports-for-MySQL-Email-etc) |
|70 | [Explain Joins](#Explain-Joins) |
|71 | [Explain Unions](#Explain-Unions) |
|72 | [How mongodb is better than relational databases?](#How-mongodb-is-better-than-relational-databases) |
|73 | [What is  mongodb?](#What-is-mongodb) |
|74 | [What is default session time?](#What-is-default-session-time)


 
1. ###  What is Django?

   An opensource framework for rapid development.

   **[⬆ Back to Top](#types-of-routes)**
    
2. ### What is the difference between Flask and Django?

   Flask is good for smaller projects and Django is good for larger projects.

   **[⬆ Back to Top](#what-is-web-php)**
    
3. ###  Name some companies that make use of Django?

   Quora, Instagram, YouTube
    
   **[⬆ Back to Top](#types-of-routes)**
    
4. ### What are the features of Django? 

    A. Extremely fast response time

    B. Extremely fast development time

    C. Can handle high traffic
    
5. ### How to check Django Version?

     py -m django --version

 **[⬆ Back to Top](#what-is-api-php)**

6. ### Explain Django architecture

   Django follows MVT ( Model View Template architecture whcih is based on the MVC or Model View Controller architecture).

   **[⬆ Back to Top](#what-is-api-php)**
   
    
7. ### What is django-admin?

    django-admin is the cli utility to manage admin tasks in a project.

   **[⬆ Back to Top](#table-of-contents)**
    
8. ###  What is django's default DB?

      SQLite.


   **[⬆ Back to Top](#table-of-contents)**
    
9. ### Does the Django framework scale?
    It can handle upto 50,000 hits per second.

   **[⬆ Back to Top](#table-of-contents)**
    
10. ###  Does Django support NoSQL?

    You can use it unofficially. No support by default.

   **[⬆ Back to Top](#table-of-contents)**
    
6. ### What is a filter hook?

    Migrations help us keep SQL tables in code. When we have to setup the DB, we just run the migration.


   **[⬆ Back to Top](#table-of-contents)**
    
7. ###  How do you enable debug mode in WP?

    Service providers are responsible for booting and configuration (binding all resources.)
    
   **[⬆ Back to Top](#table-of-contents)**
    
8. ### What is a WordPress taxonomy?

    Middleware checks for authentication.


   **[⬆ Back to Top](#table-of-contents)**
    
9. ###  Is WordPress secure?

    Object oriented and Model based way of DB query


   **[⬆ Back to Top](#table-of-contents)**
    
10. ### How many default tables are the WordPress, Can you list them?

    The ORM wrapper Laravel uses is called Eloquent. Every table has a model associated with it.
    
   **[⬆ Back to Top](#table-of-contents)**
    
11. ### What is default table prefix for wordpress?

   A database wrapper that makes it easy to access DB.

   **[⬆ Back to Top](#table-of-contents)**
    
12. ### What are Facades?

    Facades are used to hide implementation details and complexities from end user making him/her feel like interacting with a black box.

   **[⬆ Back to Top](#table-of-contents)**
    
13. ### What are disadvantages of WordPress?

    Repository pattern is used to create templates where implementation details are left to be implemented in child classes. It helps with further expansion of code and avoid bottlenecks in class updation.

   **[⬆ Back to Top](#table-of-contents)**
    
14. ### What is the difference between installing and activating a theme?
    
    Passport provides a better way to create API.

   **[⬆ Back to Top](#table-of-contents)**
    
15. ### Which ‘meta box’ is not hidden by default on Post and Page screens?
    Testing every function

   **[⬆ Back to Top](#table-of-contents)**
    
16. ### What is the difference between the two URLs in General Settings? (Hint: WordPress Address AND Site Address).

    Configured using `config/cache.php`. Used for database caching. Popular ways Redis and Memcache.

   **[⬆ Back to Top](#table-of-contents)**
    
17. ### What are Importers in WordPress?

    Writing a test for every unit (function or class) you write.

   **[⬆ Back to Top](#table-of-contents)**
   
18. ### What do you mean by the custom field in WordPress?

    Using PHP's `mail()` function amnd Laravel's `sendmail()` function. You can custoimize it using templates.

  **[⬆ Back to Top](#table-of-contents)**
  
18. ### In WordPress, objects are passed by value or by reference?

    Queue is a line of jobs to be proccessed. You can create multiple queues which is multiple lines of jobs
   **[⬆ Back to Top](#table-of-contents)**
    
19. ### What is the loop in WordPress?

    Job is a task being performed in the background.

   **[⬆ Back to Top](#table-of-contents)**
   
19. ### How to setup Emails?

   Use Laravel's sendmail() function and create a mail template.

   **[⬆ Back to Top](#table-of-contents)**
    
20. ### ) How can you disable comments in WordPress?

    Complex eloquent queries are called advanced eloquent. Query builder is wrapper for database queries.

   **[⬆ Back to Top](#table-of-contents)**
    
21. ### Which JS frameworks do you know?

   Error handling is managing `exception` in a Laravel application.

   **[⬆ Back to Top](#table-of-contents)**
    
22. ### 1 yard of string cost $0.10 . If you have 60 cents how many strings can you buy?

  Use api.php. Link will be x.com/api/slug

   **[⬆ Back to Top](#table-of-contents)**
    
23. ### How to create a WordPress child theme and why should we create a child theme?

   You get notified when an action is triggered.

   **[⬆ Back to Top](#table-of-contents)**
    
24. ### Can we create a child plugin like child theme?

    Which listen to the events.

   **[⬆ Back to Top](#table-of-contents)**
    
25. ### What plugins are you familiar with in WP?

    Payment processing is difficult. Cashier is a package which makes it easy. Its installed using composer.

   **[⬆ Back to Top](#table-of-contents)**
    
26. ### How would you change all the occurrences of “Hello” into “Good Morning” in post/page contents, when viewed before 11AM?

    Test is written first and then the function is written.

   **[⬆ Back to Top](#table-of-contents)**
    
27. ### What is the $wpdb variable in WordPress?

    Larvel uses composer which gets packages. You can develop your own package and submit.

   **[⬆ Back to Top](#table-of-contents)**
    
28. ### How to add a script in WordPress?

   https://laravel.com/docs/5.8/scout

   **[⬆ Back to Top](#table-of-contents)**
    
29. ### How to add a style in WordPress?

    Socialite is Social login for Laravel.
    Auth is Laravel's authentication.

   **[⬆ Back to Top](#table-of-contents)**
    
30. ### How to create a plugin?

    In easy way to do SPA where you can change state.

   **[⬆ Back to Top](#table-of-contents)**
    
31. ### How to create a theme?

    Go to config/database.php

   **[⬆ Back to Top](#table-of-contents)**
    
32. ### What are shortcodes?

   Add the entry to config/database.php

   **[⬆ Back to Top](#table-of-contents)**
    
33. ### What are the requirements of Wordpress?

    Lumen is the lightweight version of Laravel used usually for making microservices.

   **[⬆ Back to Top](#table-of-contents)**
    
34. ### How to turn on debugging in WordPress?
    
    Key-value database making query faster.

   **[⬆ Back to Top](#table-of-contents)**
    
35. ### What are custom fields?

    Key-value database making query faster.


   **[⬆ Back to Top](#table-of-contents)**
    
36. ### What are template tags?

    By adding more servers we scale horizontally.

   **[⬆ Back to Top](#table-of-contents)**
    
37. ###	How to recover from a hack?

    By increasing the size of the same server we scale vertically.

   **[⬆ Back to Top](#table-of-contents)**
    
38. ### Can Deactivated Plugins Slow Down a WP Website?

    There is single URL. The assets are loaded once and only content keeps changing using JSON request. Its not great for SEO but there are workarounds to create virtual URL.

   **[⬆ Back to Top](#table-of-contents)**
    
40. ### What are the types of hooks in WordPress and mention their functions?

    There are many services which are similar sized. Each performs exactly one function and they talk to each other.

   **[⬆ Back to Top](#table-of-contents)**
    
41. ### What is the prefix of WordPress tables by default?
    CSRF and JWT tokens are used to make sure the action is performed by the user. If there is no token, someone can give a link to user to click or hide it behind some action and him do what the hacker wants.
    A JWT token is hidden in the request while CSRF token is not.

   **[⬆ Back to Top](#table-of-contents)**
    
42. ###  What is WordPress loop?

    There are many services which are similar sized. Each performs exactly one function and they talk to each other. 

   **[⬆ Back to Top](#table-of-contents)**
    
43. ### How can you disable the WordPress comment?

    Validations are used to make sure input is of the kind function wanted. Custom validators are custom made valiators.

   **[⬆ Back to Top](#table-of-contents)**
    
44. ### What is white screen of death?
   
    Composer is PHP's package manager.

   **[⬆ Back to Top](#table-of-contents)**
    
45. ### What are the plugins you can use to create a contact form in WordPress?
    Symfony is a framework Laravel is inspired from.

   **[⬆ Back to Top](#table-of-contents)**
    
46. ### Describe WordPress files and directory structure

    Caching of routes to make going to routes faster. Command: `php artisan route:cache`

   **[⬆ Back to Top](#table-of-contents)**
    
47. ### What are Default packages?
    Cashier, Envoy, Passport, Scout, Socialite, Horizon etc

   **[⬆ Back to Top](#table-of-contents)**
    
48. ### How to get a website URL in WordPress?

    You can give route a name using a parameter.

   **[⬆ Back to Top](#table-of-contents)**
    
49. ### How to secure in our WordPress site?

    Laravel injects dependencies as function parameters.
    Read more: https://medium.com/a-young-devoloper/how-laravel-injects-our-dependencies-14e1b1a044e


   **[⬆ Back to Top](#table-of-contents)**
    
50. ### How to change the homepage URL in WordPress?

    https://laravel.com/docs/7.x/contracts

   **[⬆ Back to Top](#table-of-contents)**
    
51. ### How to display custom Post in WordPress?

   You can enable logging queries and Laravel will record the queries which were run.

   **[⬆ Back to Top](#table-of-contents)**
    
52. ### What is wp_footer() in WordPress?

    They solve diamond problem which is when you have to inherit from two classes.

   **[⬆ Back to Top](#table-of-contents)**
    
53. ### How to add custom dynamic sidebars in WordPress?

    Used for grouping stuff like route groups (CRUD in one line.)

   **[⬆ Back to Top](#table-of-contents)**
    
54. ### How to Create a Widget in WordPress?

    PHP version, MySQL, PHP packages mentioned on Laravel.com, apache server

   **[⬆ Back to Top](#table-of-contents)**
    
55.	### What is a permalink in WordPress?

    Max, min, sum etc
   ```
   $price = DB::table('orders')->max('price');
   ```
   
   **[⬆ Back to Top](#table-of-contents)**
  
    
56.	### How do you create a page template?

    A single object of a class is created throughout the lifecycle.

   **[⬆ Back to Top](#table-of-contents)**
    
57.	### How to make any others pages to front page in WordPress?

   To generate the process of generating the URL which leads to a route. Its used in MVC apps. You can use it using named routes in laravel.
   
   **[⬆ Back to Top](#table-of-contents)**
    
58.	### Why WordPress is the best CMS?

    Guzzle

   **[⬆ Back to Top](#table-of-contents)**
    
59.	### What are the difference between post and page in WordPress?

    Answer: Subquery, union.


   **[⬆ Back to Top](#table-of-contents)**
    
60.	### Explain the usermeta function in WordPress.

    ```
    php artisan list
    php artisan make:migrate
    php artisan make:controller
    php artisan make:model
    php artisan config:clear
    php artisan serve
    ```

   **[⬆ Back to Top](#table-of-contents)**
    
61.	### Explain Avatar in WordPress?

    Session is data related to a specific user.

   **[⬆ Back to Top](#table-of-contents)**
    
62.	### What is Category in WordPress?

    Cookies is generalized data.

   **[⬆ Back to Top](#table-of-contents)**
    
63.	### How to change the default length of the excerpt in WordPress?

    PHP: PHP 7.4
    MySQL: 7
    Laravel: 6
    MongoDB: 4

   **[⬆ Back to Top](#table-of-contents)**
    
64.	### What are the difference between Tag & Category in WordPress?

    There are three layers
    1. Presentation layer: Front end
    2. Business layer: Backend and logic
    3. Data layer: Model and database 
  
   **[⬆ Back to Top](#table-of-contents)**
    
65.	### What is config file in WordPress?

    Its a hacking trick used to complete a SQL query by filling a form content and placing query parts inside the form.

   **[⬆ Back to Top](#table-of-contents)**
    
66.	### How to display menu in WordPress?

    Using `::` before function name instead of `->`.

   **[⬆ Back to Top](#table-of-contents)**
    
67.	### How to check if any plugin is active in WordPress?

    Define the new DB in env or config/database.php and use it.
    
   **[⬆ Back to Top](#table-of-contents)**
    
68.	### How is it possible to rename the WordPress folder?

    A class which is just a template i.e has no defination but just declaration.

   **[⬆ Back to Top](#table-of-contents)**
    
69.	### How to display the current page title in WordPress?

    http: 80
    MYSQL: 3306
    Email: 587

   **[⬆ Back to Top](#table-of-contents)**
    
70.	### What is wp_head() in WordPress?

    There are 4 types of joins,
    1. Inner Join
    2. Outer Join
    3. Left Join
    4. Right Join

   **[⬆ Back to Top](#table-of-contents)**
    
71.	### EHow to check a featured image exists or not in WordPress?

    Union horizontally joins tables together i.e the records are added into the same columns.

   **[⬆ Back to Top](#table-of-contents)**
    
72.	### How to display custom field value in page?

    It is faster and it stores data in JSON form so you can enter multiple types of data without being dependent on the data being consistent in type.
