Project: clock-display
Authors: David Barnes and Michael Kölling

This project is part of the material for the book

   Objects First with Java - A Practical Introduction using BlueJ
   Seventh edition
   David J. Barnes and Michael Kölling

It is discussed in chapter 3.

To use this project, create an instance of class ClockDisplay. Then inspect this 
instance and leave the object inspector window open. With the inspector window open, 
call the object's methods, such as timeTick and setTime. Watch the 
"displayString" in the inspector.

The displayString field simulates the actual clock display device. Were this 
program running in a real clock, it would change the real, physical display 
hardware instead of this string. The timeTick method would be triggered once 
every minute by some timer hardware.

Everything else could be pretty much the same.


Note: This project does not implement adequate handling of errors.


Answers

21. The initial time the clock has been set to is 00:00. I think it starts at that particular time because the default constructor sets the hours and minutes to zero. 

23. I would need to call the timeTick method 60 times on a newly created ClockDisplay objec to make its time reach 01:00.
    I could create a new ClockDisplay with the time set to 1 hour and 0 minutes.

24. NumberDisplay digit;
    digit = new NumberDisplay (10)
    
25. Rectangle window;
    window = new Rectangle (5,10) 
    
26. The second constructor let me create a clock set to a specific time by taking the hour and minute I give it 
    
27. 
