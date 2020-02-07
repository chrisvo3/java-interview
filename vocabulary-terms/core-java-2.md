# Core Java 2

## Methods

> Methods contain the logic that provide an objcet with behavior.

A method is a collection of statements that perform some specific task and return the result to the caller.

```
public int max (imt x, int y) {
    if (x > y) 
        return x;
    else
        return y;
}
```

__modifier__ : public
__return type__ : int
__method name__ : max
__parameter list__ : int x, int y
the rest inside the method is the __body of the method__

## Access Modifier

> Defines access type of the method i.e. from where it can be accessed in your application

Access modifiers determine the visibility of classes, fields, and methods, so that information can be hidden in order to reduce complexity.

- __public:__ accessible in all class in your application.
- __private:__ accessible only within the class in which it is defined.
- __default__ (declared/defined without using any modifier) : accessible within same class and package within which its class is defined.
- __protected:__ accessible within the class in which it is defined and in its subclass(es) and package


## The '_final_' Keyword

> The _final_ keyword determines whether an object reference can be changed after being assigned.

_final_ is a non-access modifier applicable only to a variable, a method or a class

- `final variable` : to crate constant variables
- `final methods` : to prevent method overriding
- `final classes` : to prevent inheritance


## The '_static_' Keyword

> The `static` is a non-access modifier in Java which is applicable for the following: blocks, variables, methods, nested, classes

To create a `static` member(block,variable,method,nested class), precede its declaration with the keyword `static`. When a member is declared `static`, it can be accessed before any objects of its class are created, and without reference to any object.

```
static int a = 10;
static String str = "Hello";
public static void main(String[] args) {}
public static int getAge(int index) {}
```
