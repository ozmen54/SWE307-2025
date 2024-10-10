# SWE307-2024 PROJECT 1: Data visualization
## Due date: 24.10.2024 Thursday, in class.

<hr>

## DESCRIPTION OF THE PROBLEM:
In this project, you are asked to implement a *Java Spring-Boot* web application that calls one of the *R* plot functions over GraalVM. 

**What is required from you is as follows:**<br>
**1)** Every person in the group must install GraalVM and able to run the project that you are supposed to implement as a group. <br>
**2)** Every group will use the attached CSV file as data source [swe307_pro1.csv](swe307_pro1.csv). Each group will use their column in this study, such as first group will use only *Col-1* data. There will be 100 rows (100 data) in the file. and this file will be read by  not R. <br>
**3)** Your Java program will read one consequtive row every second from the file, and the double number read will be sent to R function for plot as shown in the class. <br>
**4)** Preferebly use *xyplot()* from lattice library. In your plot, x axis will be integer from [0-99] and y axis will plot the double value sent from your Java program. <br>
**5)** Your plot should be *line* type and the line color should be *dark brown*. Use *grid* in your graph.<br>
<br>
Data source file: [swe307_pro1.csv](swe307_pro1.csv)
