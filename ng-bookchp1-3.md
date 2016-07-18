# ng-book chapters 1-3
	The main benefit to using angular is that it remembers and updates values that can be dynamically changed. It does this through a look checker called the $digest() loop. values are bound together using bi-directional binding.

	Every angular should have a declartion at the start of that declares the name of the app in the html tag, i.e. <html ng-app="myApp">. Controllers are set to control a certain part of the web page decalred inside an html element. i.e.
	<div ng-controller="myController">. Likewise, with declaring the named app a module has to be set using angular.module('myApp', []), and the controller can be added by .controller() function on that module. The controller function takes two arguments, the first declares the name of the controller and the second is a function that will determine the behavior of the controller.

	If you are using $scope to bind an element to the view, $scope does not have to be declared on the view because it is implied. It is considered best practice to bind references in the view to an attribute on an object and not the object itslef.
