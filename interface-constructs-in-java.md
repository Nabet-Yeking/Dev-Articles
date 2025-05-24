---
title : "Interace Constructs In Java"
date : 2025-04-28
author : Nahom Yengesu
---

#Interace Constructs In Java
##Introduction
Interfaces are construct types and in java abstract class and interface types are not directly instantiated. If they are not directly how can they are used indirectly, Let use an example code :
`Runnable r = new <AClassThatImplementARunnableInterface>;`
So what does mean using interface types of a reference variable, Even though interface types
can not be directly instantiate because interfaces only have a list of methods prototype there
is no use to create an object of such blue print, A class can inherit an interface and define
its prototype then a reference variable of that implmented interface type can refer to instance 
of that class and access only methods that are implemented from the interface.

> [!NOTE]
Also the idea is related to late binding concept in polymorphism, Since there is no implementation
given in the Runnable interface the method invocation using that interface type reference variable
is depend on the object type that is being referenced not the reference type.
> Information the user should notice even if skimming

##Conclusion
Assigning an object(that implement the interface which is the type of the reference variable) to an interface type reference variable is a way for indirectly use an object of that interface type(technically it is not but conceptually).