 wProject: number-display
Authors: Michael Kölling and David J. Barnes

This project is part of the material for the book

   Objects First with Java - A Practical Introduction using BlueJ
   Seventh edition
   David J. Barnes and Michael Kölling

It is discussed in chapter 3.

To use this project, create an instance of class NumberDisplay. Then inspect this 
instance and leave the inspector window open. With the inspector window open, 
call the object's methods, such as increment and setValue.


NUMBER DISPLAY PROJECT
1.The differences are that the class diagram is more simple and straight foward when the object diagram is more specific and has more arrows. The class diagram is persistent. The object diagram doesn't get saved on GitHub only the java code.

2. The class diagram can change when we remove, add or change the name of the class. We can have more classes, less or even nothing changes except the name. 

3.The object diagram can change if we add another object of that class which will add another box or we we can remove one with will remove a box.

4.private Instructor tutor; (Instructor won't work because no class)

5.This is what was shown in the Terminal window for the object named hours: hours.increment();

6.This is what was shown in the Terminal window for the object named minutes: minutes.increment(); I need to check if the value is at 0  for minutes.increment and if it is I have to call hours.increment so that it goes up by one like a real digital clock.

8. Well the first time display.getValue() returned int 3 but the when I tried to put in display.Value(10) it still returned int 3. After reading the code and the description, I understood that it did nothing because the code is set to do nothing if the value is over the limit. It says to run the code only if the replacementValue is more or equal to 0 and if the replacementValue is less than than the limit.

9.I think the getValue will be 0. I was right. It goes back to zero when the limit has been reached. 

11. I think the error for display.setValue(int 5); was that by putting int I am declaring a variable but if you take it off I pass it onto the setValue method. 

12. I have to repeat number 9. So I think the result of the getValue will be 10 because it is less or equal to the limit which is ten. Lets see if I was right. I was right. 

13. The only valid parameter would be 0 because we took out the = from >=.

14. Negative numbers are now valid because even if one side is false and teh other side is true it will still say true and only say flase of both sides are false.

15. false: Right
true: Right
true: Wrong 
false: Right
true: Right



