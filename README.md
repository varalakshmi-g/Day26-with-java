# Day26-with-java

Hey all Today I started learning with OOPS in java. Here is what I learned. Lets goo....

Firstly full form of OOPS is Object Oriented Programming System. It can be defined as, It is fundamental paradigm that provides a structured approach to designing and organizing code. 

Key concepts of OOPs are 1. class 2. Object 3. Abstraction 4. Encapsulation 5. Inheritance 6. Polymorphism.

Among them, Abstraction, Encapsulation, Inheritance, Polymorphism are the pillars of OOPs. 

1.Class : class is a blueprint for creating objects. It defines the structure and behaviour that objects of that type will exhibit. Unlike objects, classes do not consume memory directly. In java everything is associated with classes and objects.

2.object: Object is created from class and it represents a real world entity. It encapsulates both state and behaviour.   For instance, dog object has properties like color, breed and behaviours like barking and wagging its tail.

3. Encapsulation: Encapsulation binds code and data together into a single unit. It ensures that the internal details of an object are hidden from external access.

In java, encapsulation is achieved by declaring the instance variables of a class as private. Which means they can only be accesses within the class. To allow outside access to the instance variables, public methods called getters and setters are defined. Getters retrieve the values of the instance variables, while setters modify them.

Example:
 
 public class Person {
    private String name;
    private int age;
    public String getName() {
        return name;
    }
    public void setName(String name) {
        this.name = name;
    }
    public int getAge() {
        return age;
    }
    public void setAge(int age) {
        this.age = age;
    }
}

In the above example, name and age are instance variables and they are private. 

getName(), setName() methods provides access to the name variable.

getAge(), setAge() methods provides access to the age variable.

Advantages of Encapsulation are:

1. Data hiding: It restricts access to data members by hiding the implementation details. Users interact with the class through the public interface without knowing how the class stores values internally.

2. Control over data: Class can enforce its own data validation rules using setters.

3. Easy testing: Encapsulation simplifies testing because you can focus on the public methods without worrying about internal details.


#resources are Geeks for Geeks, W3 schools 
