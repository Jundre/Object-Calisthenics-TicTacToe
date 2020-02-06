# Object-Calisthenics-TicTacToe
TicTacToe created according to KATA rules

## KATA Rules
### Only one level of indentation per method
This improves readability and maintainability, also helps with keeping methods small.
This rule implies only having one for, while, switch or if in a method.

### Don't use the ELSE keyword
This brings focus to default behaviour

### Wrap all primitives and Strings
Simple data has properties, encapsulating these properties will help with Seperation of Concern.

### First class collections
A class that contains a collection can not have any other member variables.
This brings the behaviour of a collection to a single class.

### One dot per line
This improves readability and prevents method chaining.
This also prevents to access object a class should not have direct access to.

### No abbreviations
Speaks for itself :)

### Keep all entities small
No package has more than 10 classes.
No class has more than 100 lines.
No method has more than 10 lines.

### No classes have more than two instance variables
Improves high cohesion and better incapsulation.

### No getters/setters/properties
Tell, don't ask. It is ok to use accessors to get the state of an object, but can not be used to make results.

