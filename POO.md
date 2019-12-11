## Content

1. Definition
2. This
3. Concepts OOP


# 1. Definition
Is a programming paradigm based of the concept of "_objects_" and this objects contain "_data_". It have attributes ans methods.

_Example:_

```Javascript
const car = {
    color: 'red',
    branch: 'tesla',
    run: () => {
        // make the car run
    }
}
```

# 2. This
Is the a function, the value of _THIS_ depends of where the function is called.

```Javascript
var car = {
   color: 'red'
};

car.paintCar = function() {
   this.color = 'blue';
};
```

Examples:

This files contain a different way to solve a problem with the THIS.

[- Wrong this](https://codesandbox.io/s/example-of-this-1-qj5e4)

[- Solution with bind](https://codesandbox.io/s/this-example-with-bind-mf9n3)

[- Solution with scope](https://codesandbox.io/s/this-example-with-scope-pzyr0)

[- Solution with foreach parameter](https://codesandbox.io/s/this-example-with-foreach-parameter-nbks4)


# 3. Concepts OOP

Let's take in reference a PERSON

`Attributes:` Properties that differentiate them with others

Example => Color, size, Age, name

`Methods:` Actions that do the objects

`Objects:` 

`Classes:` Template of objects

`Abstraction:` Classification of objects by their features and functions. (It create a new class in representation of it classification).

Example => Attributes: (Color, size, Age, name) / Functions: (Talk, walk, Eat, Sleep, work)

`Inheritance:` Subclasses inheritance attributes or methods of the father class.

`Polymorphism:` Separation of responsibilities.

`Encapsulation:` The way we have to add security to our methods and attributes.

Example => Sometimes we don't want to make visible our method for other classes.


