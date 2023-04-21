## <pre>IT 314 - Software Engineering </pre> 
### Lab 8 : Unit Testing with JUnit
### Name : Chintankumar Suthar
### S.ID: 202001242

<h3 align="center" >
  <b>Lab Exercises</b>
</h3>
<br/>
1. I created a new Java project in eclipse with name <b>Lab8</b> and created a package inside it with name <b>mypackage</b>

![1](https://user-images.githubusercontent.com/75067919/233598213-5a8fddb0-7a46-4237-94b5-850d17c64c05.png)

2.I then created a class with name <b>Boa</b> and then added the given code inside it.
![2](https://user-images.githubusercontent.com/75067919/233598284-1b581770-bef8-42b8-ad9e-0f3246ac2058.png)

3.Then I created a JUnit test file for the Boa Class with name <b>BoaTest</b>
![3](https://user-images.githubusercontent.com/75067919/233598323-fa30c823-9baf-46ca-a724-cf545fbed343.png)

4.Then I modified the setUp method to initialize the variables.

5.Then I also implemented tests for the given two functions <b>testIsHealthy()</b> and <b>testFitsInCage()</b>.
![4](https://user-images.githubusercontent.com/75067919/233598741-b9bf86d5-e6c9-4ae8-8820-1b88cac840db.png)

For testing thee fitsInCage() function, there is no need to write tests for both jen and ken objects as the function is same for both and the output of test cases depends only whether the given lenght is greater than,less than or equal to actual length of object.The behaviour will be similar in both cases.

6.Then I ran the Junit test file and all the tests are passed.There are no red bars in the output.
![5](https://user-images.githubusercontent.com/75067919/233599009-86b285a1-3833-4cc1-8042-7520880e1c6f.png)
It can be seen that 2 out of 2 test cases have been passed. 

7.Then I added a new method to the Boa class with name <b>lenghtInInches()</b> to get the length in inches.
![6](https://user-images.githubusercontent.com/75067919/233599064-ab3ff8a8-9681-40fd-9530-7abe79c3bfde.png)
As the length of the Boa is given in feet, to convert it into inches, I had multiplied length with 12 and returned the value.

8.Then I wrote another test case for this new method and ran the 3 test cases together. 
![7](https://user-images.githubusercontent.com/75067919/233599099-22a7723e-60a1-4197-94e5-5de0696c64f4.png)

Thus, test cases have been written for the given Boa class and all the three methods have been tested with required Junit test cases.
