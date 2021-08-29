# AssignmentTrial
Trial of assignment

Here are the instructions: 

kills: compiling, running, mathematical calculations, substring, coding a basic class, testing, prompting (use BufferedReader, as shown in class), assert,
Classes: Math, Point, String, BufferedReader, Date (only to get the current date), write your own class from a given design

If you have not completed the HiWorld application from the Start Java page from Orientation, please use that program to verify that your environment is set up and that you can compile and run a Java application. Show the completed program to one of your TAs by early Monday evening.

Note that there are no loops in this assignment.

Please make sure to include your name, Andrew ID, and the honor statement in all your submissions for htis course (see the starting DigitTester.java code).

Due Thu Week 2, by 10pm.

Write the following programs:

Update the PlayMath.java code to prompt the user for 2 numbers and then perform the basic calculations described in the comments. Read about and use the Math class. Be sure to use the BufferedReader class, as described in class, for the prompting; do this for all of your programs that prompt for input.
Write a program called ConvertSeconds that takes a total number of seconds and converts it to hours, minutes, and seconds. The program should prompt for a total number of seconds and calculate the hours, minutes, and seconds and then print them. Below is an example dialog:
Enter the seconds: 3712

** Output **

Hours:   1
Minutes: 1
Seconds: 52
Write the code for the replaceDigitN() method in this Java source file: DigitTester.java. Read the comments for the method to determine exactly what it should do and requirements for how it should do it.
The provided code demonstrates using asserts to test the results. They are turned off by default; execute with this command to enable them:

java -ea DigitTester

If you are using an IDE, figure out how to enable them in your environment.

Note that this program has no input. Read the comments in the code for more instructions.

Write a program called LinuxPermissions that prompts for a 9-character string representing Linux file permissions, and prints the value that the chmod command would use to properly set the permissions.
You should write and use the following methods:

public static String permissionString(String perms)
Call this method from your main(). This method returns the 3-digit string for chmod.

public static String onePermission(String perms)
Call this method from permissionString() to get the individual decimal number. Your permissionString() method should call this three times, concatenate the results together, then return the answer.

Note: this program is working with String data, so no math and no ints.
As an example, if the user enters rwxr-xr-x, your permissionString() method should return the string 755, and your main should print it. The permissionString() method should call onePermission() three times - once with "rwx", once with "r-x", and once with "r-x". It should combine the results from these 3 calls into a String, and return that answer.

Be sure to follow the basic algorithm discussed in class.

Complete the program based on 3.16 in your book that was started in the short Lab sessions on Tuesday. Be sure to call your class HeartRate and your test program HeartRateTester. Don't forget to write toString().
Update your code that calculates the age to get and use the current year, day, and month to determine the correct value. These values will come from a Date object that represents the current date.

Note: you may not use the Date class for the calculation, but must write the logic yourself based on the three attributes.

Add a static method to your HeartRateTester code that will take an int and return it in hex. Call it with the age to show the person's age in hex too. Note that the return-type for this method is String. You may use any algorithm you like to do this calculation.

Make sure your name, Andrew ID, and the Academic Integrity statement are in all of your submitted code, using the format shown in DigitTester. You will turn in your work using Autolab - make sure you are setup this week.
Last Updated - 08/26/2021 10:43:01
