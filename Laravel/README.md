<h2>What is HTTP?
<h6>The Hypertext Transfer Protocol (HTTP) is designed to enable communications between clients and servers.

HTTP works as a request-response protocol between a client and server.

Example: A client (browser) sends an HTTP request to the server; then the server returns a response to the client. The response contains status information about the request and may also contain the requested content.
 
HTTP Methods

    1. GET
    2. POST
    3. PUT
    4. HEAD
    5. DELETE
    6. PATCH
    7. OPTIONS
 
The two most common HTTP methods are: GET and POST. 
 
<h3>The GET Method
<h6>GET is used to request data from a specified resource.

GET is one of the most common HTTP methods. 
 
   1. GET requests can be cached
   2. GET requests remain in the browser history
   3. GET requests can be bookmarked
   4. GET requests should never be used when dealing with sensitive data
   5. GET requests have length restrictions
   6. GET requests are only used to request data (not modify)
   7. Data is visible to everyone in the URL

<h3>The POST Method
<h6>POST is used to send data to a server to create/update a resource.
 
   1. POST requests are never cached
   2. POST requests do not remain in the browser history
   3. POST requests cannot be bookmarked
   4. POST requests have no restrictions on data length
   5. Data is not displayed in the URL
 
><h3> MVC framework
 <h6> M-> Model , 
      v-> View ,
      C-> Controller

<h2>What is Model?
<h6>In MVC framework, the letter “M” stands for Model. 
Model are means to handle the business logic in any MVC framework based application. 
In Laravel, Model is a class that represents the logical structure and relationship of underlying data table. 
In Laravel, each of the database table has a corresponding “Model” that allow us to interact with that table. 
Models gives you the way to retrieve, insert, and update information into your data table.
All of the Laravel Models are stored in the main app directory.
  
<h2>What is Laravel routing?
<h6>Routing is one of the core components of Laravel framework, it is simply a mechanism that performs the mapping for your requests to a specific controller action. All Laravel routes are defined in the file located as app/Http/routes.php file, which is automatically loaded by the framework.

<h3>Basic Routing
<h6>A very basic Laravel routes is simply expressed as following-

      Route::get('/', function () {
          return 'Welcome to Laravel Site.';
      });

It accept two parameters URL(here url is blade file path in view folder) and Closure (Closure is basically a anonymous function can be passed as a parameter to other functions).  
  
>For more details visit https://www.w3adda.com/laravel-tutorial/laravel-routing  

<h2>What is Controller?
<h6>In MVC framework, the letter “C” stands for Controller. Controller is the entry point for any MVC framework based application, it receives the incoming HTTP requests and process it communicating with models and views, then return the results back to the web browser. In Laravel, controllers is completely responsible for handling the application logic.
In Laravel, all of the controllers stored in the Controllers folder, located in App/Http/Controllers.
  
<h3>Creating Restful Resource Controllers
<h6>In any web application CRUD (Create, Read, Update and Delete) are the basic operations on a resource. With a resource controllers you get a generic controller structure that includes all the methods for performing CRUD operations. In Laravel, using a single command you can create a resource controller. In Laravel,you don’t need setup different routes for CRUD operations. Single route declaration can handle all of the RESTful operations for specified resource.  
  
> For better understanding https://www.w3adda.com/laravel-tutorial/laravel-controllers  
  
<h2>How To Use CSRF Tokens With Laravel
<h6>Very often with a Laravel application you will have some type of CRUD (Create, Read, Update, Delete). This, of course requires HTML forms and submitting data from the front-end to the back end controllers. Laravel uses CSRF tokens to add another layer of security on top of your web application. If the CSRF token is missing during form submission or likewise, Laravel will complain about it.

> For more details https://www.codewall.co.uk/how-to-use-csrf-tokens-with-laravel/?utm_source=rss&utm_medium=rss&utm_campaign=how-to-use-csrf-tokens-with-laravel 

<h2>Insert HTML Form data into database using Laravel
><h6> Visit https://demonuts.com/insert-form-data-into-database-using-laravel/
