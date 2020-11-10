# Introduccion al contenido

A shorthand => (arrow) syntax is handy for functions that contain a single statement. This syntax is especially useful when passing anonymous functions as arguments:

flybyObjects.where((name) => name.contains('turn')).forEach(print);
Besides showing an anonymous function (the argument to where()), this code shows that you can use a function as an argument: the top-level print() function is an argument to forEach().

Read more about functions in Dart, including optional parameters, default parameter values, and lexical scope.