**Author:**
Andrew Reese

**Email Address:** 
a.reese626@gmail.com

**Phone Number:** 
(205)-577-7642


# ProjectTwo
The Second Project for CS304

## Overview

This project was made in NetBeans to keep me up to date with the Java language and to help my little sister with her math homework. The program is not very high end but shows a basic understanding of the language and what we can do with it. The best way for this to work on your computer is download a Java compatible IDE; i.e. NetBeans. The download link for NetBeans is provided below.

https://netbeans.org/downloads/8.2/

## What Does the Program Do?

This program takes user input to figure out the volume of a 3D shape. It has 5 shapes available and they are a cylinder, a cone, a rectangular prism, a pyramid, and a cube. Since each shape has a different formula to evaluate the volume, each one has to have its own class. Once an option is chosen, the program will ask the user to input certain information depending on shape. 

Once the program is running, the system gives the user six options. Which will look something like this the follow:

```
What shape do you want to find the volume of? 
1) Cylinder 
2) Cone 
3) Rectangular Prism 
4) Pyramid 
5) Cube 
6) Quit 

You're choosing option:
```

## Installation

From the following link, https://github.com/Areese4/ProjectOne, you can get to the repository for the first project Once there, you can click either the title of the code which is “ProjectOne.zip” or you can click the green button that is titled “Clone or Download”. Once you have clicked the “Clone or Download” button you can click “Download ZIP”. You should be able to choose where the ZIP file is downloaded to for easier access when trying to run the program. 

After downloading the ZIP file will be where you saved it at and you should be able to right click on the file and choose “Extract All” which will extract all of the files you will need to compile and run the Java Program.

## Running

After the installation process you are now able to run the program. The easiest way to do this is to open the recently installed NetBeans Program, if you previously did not have it. Once you have NetBeans up and running you will need to do the following steps:

>1.	File
>2.	Open Project
>3.	Find ‘ProjectTwo’ where ever you extracted the files at, then select the one file with Java logo next to it. Picture is shown below for your help
>4.	Once the project has been chosen, click “Open Project” and you should have the left most tab open with Volume now listed

<img width="1280" alt="Screen Shot 2019-03-21 at 11 01 17 AM" src="https://user-images.githubusercontent.com/37488517/54766132-c3153480-4bc8-11e9-9d4c-92e46484318c.png">

Now that you have done those four steps to get the code into NetBeans, it is good practice before running the code to hit the ‘Clean and Build Project’ button. This is located on the top bar of NetBeans; the button looks like a hammer and a broom. That should only take a couple of moments, you can check the progress bar at the bottom of the page in NetBeans to know when it is done.

Once the Clean and Build is finished, and no errors occur, which none should for this project. You can choose the ‘Run Project’ button which is just right of the ‘Clean and Build Project’ button. It looks like a normal play button or a somewhat rounded out triangle facing right. Once clicked it will start to run and do what was previously stated in this readme.

## Examples of Some of the Option for Reference

This is after the first part is ran and given the output that was shown above. This is to show what is given based on a couple of different user inputs.

```
You're choosing option: 1
CYLINDER! 

Enter Radius: 
Enter Height: 
3
9
Volume of your Cylinder is: 254.46900494077323
```

**Another Example would be:**

```
You're choosing option: 4
PYRAMID! 

Enter Height:
Enter Width:
Enter Length:
3
10
9
Volume of your Rectangular Prism is: 270.0
```

Once the output is given to the user, the program repeats itself until the user uses option number six which ends the program safely. Looking like:

```
You're choosing option: 6
Ending Program!
```

### Side Notes

Now the code is downloaded and opened in NetBeans if you want to you can open and look at the executable code.  If you choose to do so double click ‘Source Packages’, then double click ‘Volume’ inside that ‘Source Packages’ folder you will see the six Java files that contain the code. If you highlight all six of them and right click you will see the ‘Open’ option, click it. Now that you have the code open, which is six separate Java files, you can see what each one does.

Each .java file is an extension to the option that are given as soon as the program starts. The best way to explain it is that each class has the formulas and other information in it. For example, Cube.java, this class when you open it has the set information; height, radius, pi, and V which is Volume. Once the user chooses to run the first option which evaluates the cube’s volume, it asks for the height and radius, but notice how it does not ask for the pi value. That is because pi is already built into the Java language with an import that looks like:
```
Import java.util.math;
```
If you keep following along in the Cube.java file, I have V (Volume) equal to radius squared multiplied by pi then we multiply that by the total of height divided by 3 which is easier represented as:
```
V = ( (pi * (radius * radius) * (height/3) )
```
