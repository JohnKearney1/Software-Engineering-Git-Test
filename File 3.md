# File 3


JAVA BASICS 

Write one example code for each topic. 

Interfaces:
```java
interface Animal {
  public void eat();
  public void sound();
}
```

Inheritance:
```java
class Dog extends
Animal {
  public void eat() {
    System.out.println("Dog eats");
  }
  public void sound() {
    System.out.println("Dog barks");
  }
}
```

Polymorphism:
```java
class Cat extends
Animal {
  public void eat() {
    System.out.println("Cat eats");
  }
  public void sound() {
    System.out.println("Cat meows");
  }
}
```

Encapsulation:
```java
class Dog {
  private String breed;
  public String getBreed() {
    return breed;
  }
  public void setBreed(String breed) {
    this.breed = breed;
  }
}
```

Overriding:
```java
class Dog extends
Animal {
  public void eat() {
    System.out.println("Dog eats");
  }
  public void sound() {
    System.out.println("Dog barks");
  }
}
```

Overloading:
```java
class Dog extends
Animal {
  public void eat() {
    System.out.println("Dog eats");
  }
  public void sound() {
    System.out.println("Dog barks");
  }
  public void sound(String sound) {
    System.out.println("Dog barks " + sound);
  }
}
```

Packages
```java
package com.example;
public class Dog {
  public void eat() {
    System.out.println("Dog eats");
  }
}
```

Abstraction
```java
abstract class Animal {
  public abstract void eat();
  public void sound() {
    System.out.println("Animal makes a sound");
  }
}
```
