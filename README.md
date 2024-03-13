##Original Post from a Student
Title: Issue with Running Java Program to Calculate Square of Number

##Body:
Hello, I'm trying to run a Java program that reads a number from a file and prints its square. However, every time I try to run it with java and bash, I get a file not found error but the file does exist in my repo. I've attached a screenshot of the error and my terminal commands.

##Screenshot: ![Image](step5.png)
![Image](step5.png)
![Image](step5.png)

Guess at the bug: I suspect the issue might have something to do with how the file is being read because the error occurs when trying to execute the Java program. Perhaps the file number.txt isn't being found or read correctly. I used the run.sh script to compile and run my Java program.

##Failure-inducing input: I believe the input file number.txt is where things are going wrong, but I'm not sure if it's because of the contents of the file or its location.

##Response from a TA
Body:
Hello! To better understand the issue, could you please run your Java program directly from the terminal with the command java square_number and share the output? This might give us more detailed error information. Additionally, ensure the file number.txt is in the same directory as your Java program and check its contents to confirm it only contains a number.

##Follow-up Post from the Student
Body:
Thanks for you help, the issues is indeed within the path to the txt file, I have put it in a different dir. Now I have fixed the issues.

##Screenshot: ![Image](step5.png)
![Image](step5.png)
