# CSE15L LAB 5 REPORT 

This lab report contains two parts. 
The first part will replicate an EdStem conversatinon between a student an a TA. 
The second part will be my final reflection of this class.

**Part 1: EdStem**

**Student**

Hello, I'm using a mac operating system, and I'm coding on VS Code for Lab 3. I'm not sure why my code is failing the test. 
I created a test.sh file to test my files when I call <bash test.sh>, I'm prompted with an index out of bounds error. 

Heres my code
![Image](errorCode.png)

Heres my test.sh file 
![Image](commandSH.png)
 
 
Heres my output
![Image](errorTest.png)
 
Thank you!
 
 
 
**TA Response**

Hi! (insert student name)
It seems like you have two bugs in your code in reverseInPlace() and reversed(), more specifically inside the for loops. 
I wrote down some hints for you in the image below. 
 
![Image](taFix1.png)
Good Luck!
 
 
**Student**
Hey! Just wanted to say thank you for the help. 
After tracing the code through the for loops, I realized why I was getting an index out of bounds error and fixed it for both methods. 
 
Here is how my code looks like after debugging!

![Image](correctCode.png)
 
 ``` 
changed 
 
arr[i] = arr[arr.length - i];
TO 
arr[i] = arr[arr.length - i - 1];

AND

arr[i] = newArray[arr.length - i];
TO 
arr[i] = newArray.length - i - 1];
 ```

 
And here is how my test results look like after debugging!  
 
 ![Image](correctTest.png)
 
 
 **Part 2: Reflection**
 
 This class has been a blast! I've learned so much in this class. 
 During lecture, I learned the material and during lab, I honded my skills. 
 Something that I learned in the second half of thei quarter that I found super interested was **vim** 
 Ever since I learned of this command, my productivity increased. Rather than opening an entirely new project on VS Code, I could
 open the project through the bash script while not refreshing VS Code.  (Not sure if this makes sense)

 
 
