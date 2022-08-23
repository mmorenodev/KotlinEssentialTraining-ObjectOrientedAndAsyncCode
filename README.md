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

<img width="278" alt="image" src="https://user-images.githubusercontent.com/66931789/186191417-11bbf34d-863b-4839-beaf-b0314f04b19d.png">

<img width="434" alt="image" src="https://user-images.githubusercontent.com/66931789/186191666-29984be6-9419-4a59-9403-8700df866adf.png">

We can implement default behavior on interfaces. To provide the default implementation, ALL WE NEED TO DO IS FINISH IMPLEMENTING THE METHOD.

<img width="388" alt="image" src="https://user-images.githubusercontent.com/66931789/186192428-e90b20b0-814f-4674-b99a-9116832b0283.png">

**While we can provide default implementations for an interface, we cannot provide a default value for an interface property.**

## Enum Classes








