# Bluetooth Controlled Robot Arm
This will serve as a brief description of your project. Limit this to three sentences because it can become overly long at that point. This copy should draw the user in and make she/him want to read more.

| **Engineer** | **School** | **Area of Interest** | **Grade** |
|:--:|:--:|:--:|:--:|
| Clara F | The Athenian School | Mechanical Engineering | Rising Senior

![Headstone Image](https://lh3.googleusercontent.com/pw/AM-JKLXsK3lNGGu61SQXigdJyIAEo9SjGkfPI22a49oZETByClf-c2qKyyXh5xXfWqGBXRmi4MA_x8g7ikZG8GlxJhH7K0M3Jx50SIMyORBxDius3G_AhSm-57lfM9T5V6V3nLcrN6QhtYGI9XU3lU4Ailrg=s1578-no?authuser=0)

# First Milestone
  
I spent the past two days assembling this robot arm with a claw and I uploaded the code. The robot arm has four servo connected to the arduino and there’s instruction and source code available. It is controlled by two joysticks. Each joystick can move along the x axis and y axis, and each axis controls a servo. 
The original instruction was wrong so the arm was assembled reversely. When I got the actual instruction I realized that the claw was gonna face the wrong direction the way I assembled. To avoid taking the entire arm apart, I reverse the claw assembling as well so now they fit just fine. 
After I uploaded the code to the arduino, it works inconsistently. So we tested it and found out that the arduino keeps restarting itself. It was because the arduino doesn’t get enough power when it’s connected to my laptop. So we connected it to an outlet and it doesn’t restart anymore. 
Then some parts of the arm weren’t working and some didn't have the motion range as they could mechanically. That was because the servo only moves in a certain range, but the direction the arm part was attached to the servo doesn’t fit into the angle the servo rotates. I reassembled many parts and now it’s working fine. They still don’t fit perfectly, but I think this is an acceptable margin of error. 
The next step is to connect to bluetooth. And one thing that can be improved on the robot arm is that right now the servo only spins at its ma
ximum speed, and only moves when the joystick exceeds a certain angle, which is basically when it’s all the way to the side. I would like to maybe write my own code so that the joysticks work like actual joysticks, where the angle of the joystick controls the speed the servo is rotating. This way, the robot arm will be easier to control, make more precise movement, and move more smoothly. 

![](https://res.cloudinary.com/marcomontalbano/image/upload/v1656719699/video_to_markdown/images/youtube--2OmYGRiQO98-c05b58ac6eb4c4700831b2b3070cd403.jpg)

# Second Milestone
I spent the first half of today and afternoon of last Friday making the bluetooth control app for the arm claw. Now the robot arm can be controlled by an app on an android phone with bluetooth connection. 
The packet comes with source code but I don’t have the android app. So I used MIT App Inventor to make my own app. The app I made didn't go well with the code so we had to change the code. I didn’t know how to make a bluetooth connection button on my app so I got help from my classmate. I also couldn’t figure out why the code doesn’t work with the app and I got a lot of help from my instructor. 
Through this experience, I learned how to use MIT App Inventor, and I learned programming on Arduino. 

![](https://res.cloudinary.com/marcomontalbano/image/upload/v1656604288/video_to_markdown/images/youtube--irIIvKyG0IE-c05b58ac6eb4c4700831b2b3070cd403.jpg)

**Laser Cut Parts Design**
![Laser Cut Parts Design](https://lh3.googleusercontent.com/TZxWjPHchkxylm7HSZKYm-JtO2rbewmp2qmyUKZq-lT0VD5BMPnT3h2pgGm3RiAhlM6D_Bgykp77j67KISqUl2MtHATCeN-_E2KM9CTUVZ2DfBNBFkW6adAavkcwo0XHUyVjVpXAFFDW-RunBBFqMePPe2_OXCVTadRvtbDyUu5tVFzZHC9A-R0LFurv01pEqUwlZtAoVDLPOQdOlLFNIH4xs0ngsu4z-aLzIRJdUWPk1jNB1F_gfvSIVFUndl4rVh7PCAxhYJkmNv4RO3HCEAaj2bShKUzNAXrXCWHN9ksxQxKdtklaWS8ksCVXR1PFE46P9ri4fObI6_uGp9Wjla_WoOZ37M4toppV8w-JGEbLqeEd6VvXPMcTeg86UjVRU-iZqG5-v4fY68GVoTD_BeUzfsXTiMaSqMDpm8nnz97UpbztRXUIBbSH1Z3vm0hjDrYNGKkeM7veDTP9hlN2g51jOdhTIyXymatK0uoKsQDC4F3sLx3lf9Nbn0ep3tmLMYIKBjw32PqkIlF21-B7JtdwCRAC7GITDAPv958oQQPahGcUetHXUurfQzPGtm2uraVmJtE7jjf8dIYb1rwZ3GmTTuUNLL6sYl0HaiU44aCePnrRYmxBZJcLHUTeD12rBaM1ZQRReYGUB55Fhs3WuKMO0ENs11YC32WFluorViwgLZARIgW0uLOxZsEcFYaPo_4Ro-3bzl6LqYVzeMmG51KvDlMDaceXMx5NnG0A9BLlpd9RUZNjaMjaIvc=w1406-h538-no?authuser=0)

![CAD File](https://github.com/BlueStamp-Engineering-2022/Clara_BSE_Project/blob/main/laser%20cut%20parts%20v4.step)

# Starter Project

Today I started by working on my starter project: a useless machine. We first learned soldering and then I started doing soldering on my starter project. There is a switch on the outside of the useless machine, but when you press it, the motor inside rotates the arm to reach out of the box and push the switch back to its original position, and rotate backwards into the box. Inside the box is another button. It is pressed in before we turn the switch outside, but once we do and the arm moves, the button is released. When the button is released and the switch outside is at the original position, the current flows to the opposite direction, and the motor moves the arm to rotate backward. 
The challenge was that I first put the switch on the wrong side, and then I stuffed all the holes for the LED light, then I had to push the LED light in while heating the holes. The main issue was that for some reason, in order to have the little handle to roll up and push the switch, the switch cannot go all the way. We didn’t figure out why but we ended up solving this problem by putting together some metal wire and duct tapes to stop the switch from going all the way. The hardest part was the final assembly. It was hard to screw the little box together. 

![Starter Project - Useless Machine](https://res.cloudinary.com/marcomontalbano/image/upload/v1656087559/video_to_markdown/images/youtube--6KiQ8fqsXjA-c05b58ac6eb4c4700831b2b3070cd403.jpg)



