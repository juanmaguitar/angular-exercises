#Excersie 4: Using angular-route

##Introduction

This lesson is about following skills :

* using angular-route component
* writing controller
* binding data

Expected result of this exercise is an application which allows user to route to `postDetails.html` using `view` button.

##Before you start, read about...
* ngRoute: [https://docs.angularjs.org/api/ngRoute](https://docs.angularjs.org/api/ngRoute)
* $routeProvider: [https://docs.angularjs.org/api/ngRoute/provider/$routeProvider](https://docs.angularjs.org/api/ngRoute/provider/$routeProvider)

##Hints

###angular-route.js package
In order to use angular-route library you need to install it in your app `bower install` then include in your index.html file `bower_components/angular-route/angular-route.js`.

###dependency annotation
Inject `$routeParams` to PostDetailsCtrl.

##The exercise

In order to complete this exercise you will need to follow these steps:

* use `get()` function from `PostDAO.js` in `PostDetailsCtrl.js`
* add button in `postList.html` which redirects you to `postDetails.html`

##Setup
You should have installed `npm`, `bower`, `grunt`  packages to run this example. First, run sequentially

```
npm install
```

```
bower install
```

To start the application, run

```
grunt serve
```

To start unit test, run

```
grunt karma
```

Good luck !
