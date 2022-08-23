# KotlinEssentialTraining-ObjectOrientedAndAsyncCode
Learning about object oriented and async code at LinkedInlearning.


Abstract can apply both, the class level and the property level.

<img width="178" alt="image" src="https://user-images.githubusercontent.com/66931789/185804232-2a8ae7b3-07e0-4c14-b9ee-faf98c6b8037.png">

**By marking the property abstract in this case, we would leave the initialization to whatever class later extended the person class.**

## Init blocks
Init blocks are sections of code that run when an instance of a class is created. 

Init blocks and properties are processed in the order in which they're defined within a class body. 

In cases where we don't need to validate a parameter before assigning it to a property, we can use a simplified syntax for defining class properties right in the constructor itself. 

## Check function

<img width="401" alt="image" src="https://user-images.githubusercontent.com/66931789/185804502-51d75ee6-e64a-44e8-8a21-a6b97243c67b.png">

<img width="675" alt="image" src="https://user-images.githubusercontent.com/66931789/185804529-e81504d1-ef25-44b2-9531-afa872709057.png">

## Interfaces

<img width="624" alt="image" src="https://user-images.githubusercontent.com/66931789/186190273-a6d86e77-081a-4280-8d15-0293dbafbbd1.png">

In addition to methods, interfaces may also define properties.

## Enum Classes
Sometimes we want to define a new type **that only has a limited set of values** 
Enum classes are a special class type that help us do just that, with enum classes we prevent the addition of new values. 

Any enum value HAS A COUPLE OF COMMON PROPERTIES. 

We may access the name of the enum value. The name is a string representation of the actual typed name defined in the enum class body. 

<img width="896" alt="image" src="https://user-images.githubusercontent.com/66931789/186218054-500b106e-c2cf-43f5-90cf-df11a303f0a4.png">

We can also determine the index of the value WITHIN THE TYPE BY USING THE 'ordinal' PROPERTY. 

<img width="911" alt="image" src="https://user-images.githubusercontent.com/66931789/186218590-cfd152c2-0cd7-4d08-b779-7866a521b072.png">

We can convert a string into a enum value by using valueOf.

<img width="516" alt="image" src="https://user-images.githubusercontent.com/66931789/186218880-b7b0b185-c264-485c-920d-d376862309cd.png">

If we were to pass something else in 'valueOf', we would gete an exception. We see an IllegalArgumentException. 











<img width="278" alt="image" src="https://user-images.githubusercontent.com/66931789/186191417-11bbf34d-863b-4839-beaf-b0314f04b19d.png">

<img width="434" alt="image" src="https://user-images.githubusercontent.com/66931789/186191666-29984be6-9419-4a59-9403-8700df866adf.png">

We can implement default behavior on interfaces. To provide the default implementation, ALL WE NEED TO DO IS FINISH IMPLEMENTING THE METHOD.

<img width="388" alt="image" src="https://user-images.githubusercontent.com/66931789/186192428-e90b20b0-814f-4674-b99a-9116832b0283.png">

**While we can provide default implementations for an interface, we cannot provide a default value for an interface property.**

## Enum Classes
When you need a data type with a limited set of possible values you can us eenum classes. They are a special class.

For a variable of data type enum you can see its name, ordinal (index position when declared).

You can also get all the values of the enum as an array invoking the 'values()' method. 

Enum types can provide properties THAT EVERY VALUE TYPE MUST IMPLEMENT. We can add a constructor, and define a property that will be present on any value type of this enum. 

<img width="381" alt="image" src="https://user-images.githubusercontent.com/66931789/186249631-4c65ca11-a865-4c3a-a96f-5be44928c0f3.png">









