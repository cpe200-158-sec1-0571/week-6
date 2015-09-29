# Lab601: Identify the design pattern and participants from the program (group of 2 students)

In this lab, each group of 2 students has to identify a design pattern and all participants 
from the provided C# source code. 

## Submission: a written report which contains

1. A class diagram of the original source code
![570610571](http://www.uppic.biz/images/2015/09/29/601.png)
2. Detail explaination about the identified pattern and all the parcipants
= Overview i think this code use Abstract  Factory patterns
 + AnimalWorld is client which  create ContinentFactory and can create 2 abstract class (hervivore and canivore).
 + Hervivore and Canivore use prototype patterns notice from Canivore and Herbivore can create many animal.
 + ContinentFactory use prototype patterns too notice from ContinentFactory create AfricaFactory and AmericaFactory so they are look like  ContinentFactory .
  

3. Explain how to include "an asian herbivore and an asian carnivore" to the program: 
  - Show the class diagram of the program after including the new requirment.
  ![570610571](http://www.uppic.biz/images/2015/09/29/601_a.png)
  - Test the new requirment by modifying the main function and show the result.
  ![570610571](http://www.uppic.biz/images/2015/09/29/output.jpg)
  - Show the main function and snippet of C# code that is related to the process.
  ![570610571](http://www.uppic.biz/images/2015/09/29/main.jpg)
  ![570610571](http://www.uppic.biz/images/2015/09/29/1.jpg)
  ![570610571](http://www.uppic.biz/images/2015/09/29/2.jpg)


