# angularjscertification.github.io
### You can take Intellipaat's [Angular JS  training](https://intellipaat.com/angular-training/).It has been designed to help you create web applications and deploy Angular CLI, Angular components, TypeScript, Bootstrap and more. You will learn Angular Dependency Injection, Directives, Pipes, Forms, Routing, HTTP Promises and more through hands-on projects.
## Angular JS Interview question and answers
1) What is AngularJS?

AngularJS is a JavaScript framework used for creating single web page applications. It allows you to use HTML as your template language and enables you to extend HTML's syntax to express your application's components clearly.

2) What are the key features of AngularJS?

The key features of AngularJS are:

Scope
Controller
Model
View
Services
Data Binding
Directives
Filters
Testable
3) Explain function scope in AngularJS

Scope refers to the application model. It acts like a glue between the application controller and the view. Scopes are arranged in a hierarchical structure and impersonate the DOM (Document Object Model) structure of the application. It can watch expressions and propagate events.




Primis Player Placeholder




4) Explain services in AngularJS

AngularJS services are the singleton objects or functions that are used for carrying out specific tasks. It holds some business logic.

5) What is Angular Expression? Explain the key difference between angular expressions and JavaScript expressions

Like JavaScript, Angular expressions are code snippets that are usually placed in binding such as {{ expression }}

The key difference between the JavaScript expressions and Angular expressions is:

Context: In Angular, the expressions are evaluated against a scope object, while the JavaScript expressions are evaluated against the global window
Forgiving: In Angular expression, evaluation is forgiving to null and undefined, while in JavaScript undefined properties generate TypeError or ReferenceError
No Control Flow Statements: Loops, conditionals or exceptions cannot be used in an angular expression
Filters: You can use filters to format data before displaying it.
6) How can you initialize a select box with options on page load?

You can initialize a select box with options on page load by using ng-init directive.

<div ng-controller = " apps/dashboard/account " ng-switch
On = "! ! accounts" ng-init = " loadData ( ) ">
7) What are directives? Name some of the most commonly used directives in AngularJS application

A directive is something that introduces new syntax. They are like markers on the DOM element, which attaches a special behavior to it. In any AngularJS application, directives are the most important components.

Some of the commonly used directives are:

1) ng-model

2) ng-App

3) ng-bind

4) ng-repeat

5) ng-show

8) How Angular JS routes work?

AngularJS routes enable you to create different URLs for different content in your application. Different URLs for different content enable the user to bookmark URLs to specific content. Each such bookmarkable URL in AngularJS is called a route

A value in Angular JS is a simple object. It can be a number, string, or JavaScript object. Values are typically used as configuration injected into factories, services, or controllers. A value should belong to an AngularJS module.

Injecting a value into an AngularJS controller function is done by adding a parameter with the same name as the value

9) What is data binding in AngularJS?

Automatic synchronization of data between the model and view components is referred to as data binding in AngularJS. There are two ways for data binding

Data mining in classical template systems
Data binding in angular templates
10) What are the benefits of AngularJS?

Benefits of AngularJS are:

Registering Callbacks: There is no need to register callbacks. This makes your code simple and easy to debug.
Control HTML DOM programmatically: Applications which are created using Angular are not required to manipulate the DOM.
Transfer data to and from the UI: AngularJS helps to eliminate almost all of the boilerplate. It can validate the form, display errors, return to an internal model, and so on.
No initialization code: With AngularJS, you can bootstrap your app easily. You can use auto injected services into your application in Guice.
11) What is string interpolation in Angular.JS ?

In Angular.js, the compiler during the compilation process matches text and attributes. It uses interpolate service to see if they contain embedded expressions. As part of the normal digest cycle, these expressions are updated and registered as watches.

12) What are the steps for the compilation process of HTML?


Compilation of HTML process occurs in the following ways

Using the standard browser API, first, the HTML is parsed into DOM
By using the call to the $compile () method, a compilation of the DOM is performed. The method traverses the DOM and matches the directives.
Link the template with a scope by calling the linking function returned from the previous step
13) Explain directives and their types

During compilation process, when specific HTML function is triggered, it is referred to as directive. It is executed when the compiler encounters it in the DOM.

Different types of directives are:

1) Element directives

2) Attribute directives

3) CSS class directives

4) Comment directives.

14) Explain the linking function and its types

Link combines the directives with a scope and produces a live view. For registering DOM listeners as well as for updating the DOM, link function is responsible. After the template is cloned, it is executed.

Pre-linking function: Pre-linking function is executed before the child elements are linked. It is not considered as a safe way for DOM transformation.
Post linking function: Post linking function is executed after the child elements are linked. It is safe to do DOM transformation by post-linking function
15) Explain injector in AngularJS

An injector is a service locator. It is used to retrieve object instances as defined by provider, instantiate types, invoke methods, and load modules. There is a single injector per Angular application, it helps to lookup an object instance by its name.

16) What is the main difference between a link and compile in Angular.js?

Compile function: It is used for template DOM manipulation and collects all of the directives.
Link function: It is used for registering DOM listeners as well as for instance, DOM manipulation. It is executed once the template has been cloned.
17) What is the factory function in AngularJS?

For creating the directive, factory method is used. It is invoked only once when the compiler matches the directive for the first time. By using $injector.invoke the factory method is invoked.

18) Explain the styling form that ngModel adds to CSS classes

NgModel adds these CSS classes to allow styling of form. Validation classes of AngularJS are:

ng- valid
ng- invalid
ng-pristine
ng-dirty
19) What are the characteristics of "Scope"?

To observer model mutations scopes provide APIs ($watch)
To propagate any model changes through the system into the view from outside of the Angular realm
A scope inherits properties from its parent scope, while providing access to shared model properties, scopes can be nested to isolate application components
Scope provides context against which expressions are evaluated
20) What is DI (Dependency Injection) and how an object or function can get a hold of its dependencies?


DI or Dependency Injection is a software design pattern that deals with how code gets hold of its dependencies. In order to retrieve elements of the application which is required to be configured when the module gets loaded, the operation "config" uses dependency injection.

These are the ways that object uses to hold of its dependencies

Typically using the new operator, dependency can be created
By referring to a global variable, dependency can be looked up
Dependency can be passed into where it is required
21) Explain the concept of scope hierarchy

Each angular application consists of one root scope but may have several child scopes. As child controllers and some directives create new child scopes, an application can have multiple scopes. When new scopes are formed or created, they are added as a children of their parent scope. They also create a hierarchical structure similar to DOM.

22) Explain the main difference between AngularJS and backbone.js

AngularJS	Backbone.js
AngularJS is a JavaScript-based open-source framework which is designed to support dynamic web applications.	backbone.js is a framework which abstracts DOM into views and data into models and then binds both using events.
It's performance is good as it provides two-way data binding process	Backbone.js technology offers faster performance than AngularJS if the data sets are small
It works on MVS (Multiple Virtual Storage).	It works on MVP architecture.
AngularJS uses dynamic HTML attribute to make an easy to understand the application.	Backbone.js uses underscore templates to understand the application.
It has large community support.	Community support is restricted to the underscore template.
23) Who created Angular JS?

AngularJS was developed by Adam Abrons and Misko Hevery. Currently, it is developed by Google.

24) How can you integrate AngularJS with HTML?

Developers can follow the following steps to integrate AngularJS with HTML:

Step 1: including AngularJS JavaScript in html page.

<head>
   <script src = "https://ajax.googleapis.com/ajax/libs/angularjs/1.3.14/angular.min.js"></script>
</head>
Step 2: Point out AngularJS application.

You have to add ng-app attribute inside HTML body tag to tell what part of HTML AngularJS app has as shown in the following example:

<body ng-app = "testapp">
</body>
25) What is orderby filter in AngularJS?

Orderby filter in AngularJS orders the array based on specified criteria. Following example states how you can order product by price.

<ul>
<li ng-repeat = "company in product.products | orderBy:'price">
      {{ company.product + ', price:' + product.price }}
   </li>
</ul>
26) What is ng-non-bindable in AngularJS?

Ng-non-bindable specifies AngularJs to not compile the HTML element and its child nodes. For example:

<title ng-non-bindable > </title>

27) Explain the use of double click event in AngularJS

double click event of AgularJS let you to specify custom behavior on double click event of mouse on a web page like:

<ELEMENT ng-dblclick="{expression}"> 
... 
</ELEMENT>
28) Explain ng-click directives in AngularJS with example

Ng-click directives can be used in a scenario when you have to click on the button or want to perform any operation.

Example:

<button ng-click="count = count ++">Click</button>
29) Why use ng-include in AngularJS?

Ng-include in AngularJS helps you to embed HTML pages within a single HTML page. Example:

<div ng-app = "" ng-controller = "interviewController">
   <div ng-include = "'first.htm'"></div>
   <div ng-include = "'phases.htm'"></div>
</div>
30) How can you make an ajax call using Angular JS?

AngularJS offers $https: control that helps you to make ajax call to read server data. The server makes a database call in order to get the required records. Once your data in JSON format is ready, you can use $https: to retrieve data from the server in the following manner:

function employeeController($scope,$https:) {
   var url = "tasks.txt";
   $https.get(url).success( function(response) {
      $scope.employee = response; 
   });
}
31) Explain the use of $routeProvider

In Angular JS $routeProvider sets the URL configuration. It maps with the related ng-template or HTML page and attaches a controller with the same.

32) How can you set, get, and clear cookies in AngularJS?

You can use:

$cookies.put() method to set the cookies.
$cookies.get() method to get the cookies.
$cookies.remove to remove cookies in AngularJS.
33) What is service method?

Service method in AngularJS helps you to define service and method to it. In the following example, we have injected a simple addition service, which adds two numbers.

<! DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <title>Event Registration</title>
</head>
<script src="https://ajax.googleapis.com/ajax/libs/angularjs/1.6.4/angular.min.js"></script>
<body>
<h3> Guru99 Global Event</h3>
<div ng-app = "mainApp" ng-controller = "DemoController">
    <p>Result: {{result}}</p>
</div>
<script>
    var mainApp = angular.module("mainApp", []);
    mainApp.service('AdditionService', function(){
        this.ADDITION = function(a,b) {
            return a+b;
        }
    });

    mainApp.controller('DemoController', function($scope, AdditionService) {

            $scope.result = AdditionService.ADDITION(5,6);
    });
</script>
</body>
</html>
34) Name the AngularJS components that can be injected as dependency

AngularJS components that can be injected as a dependency are: 1) value, 2) factory, 3) service, 4) provider, 5) constant.

35) What are the common Angular Global API functions

Some commonly used Angular Global API functions are:

Angular.isString: It will return true only if the given reference is of type string.
Angular.lowercase: It converts any string to lowercase
Angular.uppercase: It converts any string to uppercase.
Angular.isNumber: It returns true only if the reference is a numeric value or number.
36) Write a program to hide an HTML tag just by one button click in angular

<!DOCTYPE html>
<html>
<head>
    <meta chrset="UTF 8">
    <title>Event Registration</title>
</head>
<body>
<script src="https://code.angularjs.org/1.6.9/angular.js"></script>
<script src="https://code.jquery.com/jquery-3.3.1.min.js"></script>

<h1> Guru99 Global Event</h1>
<div ng-app="DemoApp" ng-controller="DemoController">
    <input type="button" value="Hide Angular" ng-click="ShowHide()"/>
    <br><br><div ng-hide="IsVisible">Angular</div>
</div>
<script type="text/javascript">
    var app = angular.module('DemoApp',[]);
    app.controller('DemoController',function($scope){
        $scope.IsVisible = false;
        $scope.ShowHide = function(){
            $scope.IsVisible = $scope.IsVisible = true;
        }
        });
</script>
</body>
</html>
37) What is BOM(Browser Object Model)?

BOM or Browser Object Model consists of history, object navigator, screen location, etc. It specifies the global browser objects like console, local storage, and window.

38) Explain "$rootScope" in AngularJS

"$rootScope" is a scope that is created on the DOM (Document Object Model) element.

An application can have only one $rootScope that shares, among other components. It has the ng-app directive. Other scopes are called as its child scope. It can watch expressions as well as propagate events.

39) Give an example of ng-view in Angular

Consider the following example:

<!DOCTYPE html>
<html>
<head>
    <meta chrset="UTF 8">
    <title>Event Registration</title>
    <script src="https://code.angularjs.org/1.5.9/angular-route.js"></script>
    <script src="https://code.angularjs.org/1.5.9/angular.min.js"></script>
    <script src="/lib/bootstrap.js"></script>
</head>
<body ng-app="sampleApp">
<h1> Global Event</h1>
<div class="container">
    <ul><li><a href="#!NewEvent"> Add New Event</a></li>
        <li><a href="#!DisplayEvent"> Display Event</a></li>
    </ul>
    <div ng-view></div>
</div>
<script>
    var app = angular.module('sampleApp',["ngRoute"]);
    app.config(function($routeProvider){
        $routeProvider.
        when("/NewEvent",{
            templateUrl : "add_event.html",
            controller: "AddEventController"
        }).
        when("/DisplayEvent", {
            templateUrl: "show_event.html",
            controller: "ShowDisplayController"
        }).
        otherwise ({
            redirectTo: '/DisplayEvent'
        });
    });
    app.controller("AddEventController", function($scope) {
        $scope.message = "This is to Add a new Event";
    });
    app.controller("ShowDisplayController",function($scope){
        $scope.message = "This is display an Event";
    });
</script>
</body>
</html>
40) What is the syntax of factory method in AngularJS?

The syntax of Factory is as follows:

app.factory('serviceName',function(){ return serviceObj;})

41) Name different phases of the AngularJS Scope lifecycle.

Here, are different phases of AngularJS Scope lifecycle:

Creation
Model mutation
Watcher registration
Mutation observation
Scope destruction
42) Write a program for to bootstrap process in Angular

program for to bootstrap process in Angular is:

<html>
    <body ng-app="TestApp">
        <div ng-controller="Ctrl">Hi{{msg}}!</div>
        <script src="https://ajax.googleapis.com/ajax/libs/angularjs/1.7.8/angular.min.js"> 
</script>
        <script>
            var test = angular.module('TestApp', []);
            test.controller('Ctrl', function($scope) {
                $scope.msg = 'Good Morning';
            });
        </script>
    </body>
</html>
43) What is a single page application in AngularJS?

SPA or single page application is a website or web application which interacts with the users dynamically. In AngularJS, JavaScript, HTML, and CSS fit on a single page. It performs navigation without refreshing the whole HTML page.

44) Explain the concept of webpack

Webpack is a module bundler for Angular2 or above. It bundles, transpiles, and minifies AngularJS application.

45) What do you mean by NPM?

NPM stands for Node Package Manager. It consists of a command line tool client for interacting with the repository of Node.js project.

46) How can you create a new project in angularJS using Command Line Interface?

Once you install the Angular command-line interface, you have to run ng new project-name command in order to create a new project in Angular.

47) Explain the auto bootstrap process in AngularJS

Angular initializes automatically DOMContentLoaded event or when you download angular.js script is to the browser.

After this, AngularJS find the ng-app directive that is the root of angular app compilation. When ng-app directive is found, AngularJS do the following steps:

1) load the module, which is associated with the directive,

2) Create application injector,

3) Compile the DOM from the ng-app root element. This process is known as auto bootstrapping.

48) What is immediately invoked function expressions?

IIFEs or Immediately Invoked Function Expressions is a function that executes as soon as it is created. It offers a simple way to isolate the variable declaration. IIFEs contains two major functions:

1) operator()

2) expression()

49) What is the digest cycle in AngularJS?

Digest cycle is important part of the data binding in AngularJS, which compares the old and new version of the scope model. Digest cycle triggered automatically or manually by using $apply() function.

50) What is the basic requirement to work with AngularJS?

You have to download the latest version of AngularJS from AngularJS.com to learn or work with AngularJS. You can either need JS file and host it locally, or you can also use google CDN (Content Delivery Network) for referencing it.

51) Can we create nested controllers in AngularJS?

Yes, we can create a nested controller in AngularJS.

Example of nested controller is as follows:

<div ng-controller="MainCtrl">
 <p>{{msg}} {{name}}!</p>
<div ng-controller="SubCtrl1">
<p>Hi {{name}}!</p>
   <div ng-controller="SubCtrl2">
     <p>{{msg}} {{name}}! Your name is {{name}}.</p>
   </div>
</div>
</div>
52) What is Authentication?

The authentication is a service that is used to login and logout of Angular application. The credentials of users pass to API on the server. Then post server-side validation these credentials, JSON Web Token is returned, which as detail about the current user.

53) Define AngularJS Material

AngularJS Material is an implementation of the Material Design Specification of Google. It offers a set of well-tested, reusable UI components for AngularJS programmer.

54) What are the important differences between Angular 7 and Angular 8

Angular 7	Angular 8
Angular 7 is hard to use	Angular 8 is very easy to use
It provides supports for the lower version of Typescript 3.4 programming language	It does not provide support for the lower version of Typescript 3.4 programming language
Supports all versions of Node.js	Supports only Node.js 12 version.
55) What is ngzone?

The ngzone is a JavaScrip wrapper class which is denoted by Zone.js. It enables developers to explicitly run certain code outside Angular's zone, which inhibits angular to run any change detection.

56) List out the difference between Angular Component and Directive

Component	Directive
Angular component is a directive that enables you to utilize the web component functionality throughout the application.	Angular directive is a technique by which we attach behavior to the elements.
It helps you to divides your application into smaller components.	It helps you to design the reusable components.
It can define pipes	It cannot define pipes.
57) Define ECMAScript

ECMAScript (European Computer Manufacturer's Association) is a standard for scripting languages. JavaScript uses ECMAScript as a core language. Developers can take help of it for writing client-side scripting on the world wide web and or server applications and services. ECMAScript has numerous features like functional, prototype, dynamic, and structured features.

58) What is a Traceur Compiler?

Traceur is a JavaScript compiler that uses classes, generators, and other features from ECMAScript.

59) How to convert a string into currency?

You can convert string input into the currency type currency filter in Angular.

60) What are templates in AngularJS?

A template is HTML file that is used with AngularJs directives and attributes.

61) Explain the differences between Angular and jQuery

AngularJS	JQuery
AngularJs is difficult to understand	Jquery is very easy to understand.
It supports two-way binding process	It does not support data binding process
It provides support for deep linking routing	It does not provide support for deep linking routing
62) What is the Ahead of Time Compilation?

Angular AOT (Ahead of Time) is a compiler that converts your angular HTML and typescript code into the JavaScript code.

63) List types of filters in AngularJS

Types of filters used in AngularJS are: 1) Currency, 2) Uppercase, 3) Lowercase, 4) orderBy, 5) JSON, and 6) limitTo.

64) Explain ngOnInit () function

ngOnInit () function is a lifecycle hook which is called after completion of data-bound properties of the directive.

65) What is transclusion in AngularJS?

The transclusion in AngulaJS enables developers to reallocate the original directive children into a specific location within a template. The directive ng shows the insertion point for a transcluded DOM of the nearest parent directive, which is using transclusion. Ng-transclude-slot or ng-transclude directives are mainly used for transclusion.

66) Lit out hooks are available in AngularJS

Various hooks in AngularJS are:

1) ngOnInit()

2) ngOnChanges(),

3) ngDoCheck(),

4) ngAfterContentInit(),

5) ngAfterContentChecked(),

6) ngOnDestroy(),

7) ngAfterViewChecked(), and

8) ngAfterViewInit()

67) What are the important parts of AngularJS metadata?

AngularJS metadata is used to decorate a class that depicts the expected behavior of a particular class. Various parts of metadata are: 1) class decorator, 2) Method decorators, Parameter decorators, and 4) Property decorators.

68) What is Angular CLI?

Angular CLI is also called as the command line interface tool. It is used to build, initialize, and maintain Angular apps. CLI software can be used through very interactive UI like a command shell or Angular Console.

69) Explain parameterized pipe in AngularJS

In angularJS, pipes can have more than one parameter in order to tune the fine output. You can create a parameterized pipe by declaring the pipe with colon(:) and values of parameter. Developer can separate multiple parameter values with colon(:).

70) What is Routing?

Routing is a method of merging various views. The controller takes the decision to combine these views depend on logical needs.

71) What do you mean by isolated unit tests?

Isolated test is a process of checking instance of class without using any injected values or Angular dependence. It helps you to implement program very easily.

72) Name DSL animation functions in AngularJS

DSL animation functions in AngularJS are: 1) group(), 2) state(), 3) transition(), 4) style(), 5) keyframes(), 6) trigger(), 7) sequence(), and 8) animate().

73) What is AngularJS module?

In angularJS, a module is a process to group directives, and services components that are related. It arranges them in a way that they can mix with other modules to create an application.

74) What are pipes in AngularJs?

In angular, pipes provide a simple method to transform the data. It takes the values like arrays, integers, data, and strings as input and divided with pipe (|) symbol. It converts the data in the required format. Pipes displays the same thing in the browser. In angularJS, it provides some in-built pipes, but developers can also develop their own pipes.

75) Explain ViewEncapsulation in AngularJS

ViewEncapsulation determines whether the styles defined in the AngularJS component will affect the entire app or not.
