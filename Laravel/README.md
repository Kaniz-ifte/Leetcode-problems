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
  
