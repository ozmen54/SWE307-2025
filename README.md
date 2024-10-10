# SWE307-2024 PROJECT 1
## Due date: 24.10.2024 Thursday, in class.

<hr>

## DESCRIPTION OF PROBLEM:
In this project, you are asked to implement a *Java Spring-Boot* web application that calls one of the *R* plot functions over GraalVM. 

**What is required from you is as follows:**<br>
**1)** Every person in the group must install GraalVM and able to run the project that you are supposed to implement as a group. <br>
**2)** Every group will use their CSV file as data source. CSV files are provided from here, the names are encoded as *swe307_pro1_GRPNO.csv*. For example first group will use data *swe307_pro1_1.csv*. There will be 100 rows in the file and this file will be read by Java program not R. <br>
**3)** Every second a new double number from next row will be sent to R function under the column of *value* as shown in the class. <br>
**4)** Preferebly use *xyplot()* from lattice library. In the project work,  For example first group will use data *swe307_pro1_1.csv*, columnt with header *value* will be sent to R function at every second as we did in the example at class. <br>
