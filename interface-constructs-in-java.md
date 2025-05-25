*Published On : 2025-04-28*

## Interface Constructs In Java
Interface is a construct type and in java abstract class and interface types are not directly instantiated. So how can they are used indirectly, Let use an example code : `Runnable r = new <AClassThatImplementARunnableInterface>;`.

So what does mean using a reference variable of interface types? Even though interface types
can not be directly instantiate because interfaces only have a list of methods prototype, there
is no use to create an object of such blue print. A class can inherit an interface and define
its prototype then a reference variable of that implmented interface type can refer to the instance 
of that class and access only methods that are implemented from the interface.

> [!NOTE]
Also the idea is related to late binding concept in polymorphism, Since there is no implementation
given in the Runnable interface the method invocation using that reference variable of interface type
is depend on the object type that is being referenced not the reference type.
>

## Conclusion
When an object implement a given interface a reference variable of that interface type is a way for indirectly use an object of that interface type(technically it is not an object of that interface, but conceptually).
