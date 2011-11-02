This is a JavaScript inheritance implementation I developed to add some functionality that was missing in other JS inheritance systems.

Key differences:

* Different implementation of super():
** Does not modify this.super() every time a method is called.
** Does not parse a function's string value and wrap it to pass $super as the first argument.
** Also works in static methods
* Inheritance of static methods
* Abstract classes that cannot be instantiated if they do not have a initialize method defined.
