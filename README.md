# SWE307-2024 BIG DATA

## Projects:

<table>
  <header>
    <th>No</th>
    <th>Project Title</th>
    <th>Tasks</th>
    <th>Due Date</th>
    <th>Other</th>
  </header>
  <body>
    <tr>
      <td>1</td>
      <td><b>Data visualization.</b></td>
      <td>
        <b>a)</b> Every person in the group must install GraalVM and able to run the project that you are supposed to implement as a group.<br> 
        <b>b)</b> Groups will use the attached CSV file as data source [swe307_pro1.csv](swe307_pro1.csv). Use only one column in this study, such as first group will use only *Col-1* data. There are 100 rows (100 data) in the file, and this file will be opened, read by Java not R.<br>
        <b>c)</b> Your Java program will read one consequtive row every second from the file, and the double number read will be sent to the R function for plot as shown in the class.<br>
        <b>d)</b> referebly use *xyplot()* from lattice library. In your plot, x axis will be integer from [0-99] and y axis will plot the double value sent from your Java program.<br>
        <b>e)</b> Your plot should be *line* type and the line color should be *dark brown*. Use *grid* in your graph.<br>
        <b>f)</b> Data source file: [swe307_pro1.csv](swe307_pro1.csv). Example output: ![pro1.png](pro1.png).
      </td>
      <td>24 October 2024 <br></td>
      <td><a href="pro1.pdf">Project1</a></td>
    </tr>
    <tr>
      <td>2</td>
      <td><b>Hadoop-HDFS (or G-Drive, AWS-S3) acess from web app.</b></td>
      <td>
        <b>a)</b> Employee and department data will be read from the database [swe307_pro1.csv](swe307_pro1.csv). Implement CRUD operations. <br>
        <b>b)</b> Employee images will be taken directly from HDFS (see Figure 1).<br>
        <b>c)</b> There will be a single web page, on this page the information will be displayed in a table using the JOIN operation. Information to display: employee name, manager name, salary, commission, department (see Figure 2). <br>
        <b>d)</b> Show that the user image file uploading and displaying them on the web page work. <br>
        <b>e)</b> Show that your application runs as expected.
      </td>
      <td>15 November 2024<br></td>
      <td><a href="pro2.pdf">Project2</a></td>
    </tr>
    <tr>
      <td>3</td>
      <td><b>To be announced.</b></td>
      <td>
        <b>a)</b>  <br>
        <b>b)</b>  <br>
        <b>c)</b>  <br>
        <b>d)</b> <br>
        <b>e)</b>  <br>
      </td>
      <td>To be announced.<br></td>
      <td><a href="pro3.pdf">Project3</a></td>
    </tr>
</body>
</table>




# SWE307-2024 PROJECT 1: Data visualization
## Due date: 24.10.2024 Thursday, in class.

<hr>

## DESCRIPTION OF THE PROBLEM:
In this project, you are asked to implement a *Java Spring-Boot* web application that calls one of the *R* plot functions over GraalVM. 

**What is required from you is as follows:**<br>
**1)** Every person in the group must install GraalVM and able to run the project that you are supposed to implement as a group. <br>
**2)** Groups will use the attached CSV file as data source [swe307_pro1.csv](swe307_pro1.csv). Use only one column in this study, such as first group will use only *Col-1* data. There are 100 rows (100 data) in the file, and this file will be opened, read by Java not R. <br>
**3)** Your Java program will read one consequtive row every second from the file, and the double number read will be sent to the R function for plot as shown in the class. <br>
**4)** Preferebly use *xyplot()* from lattice library. In your plot, x axis will be integer from [0-99] and y axis will plot the double value sent from your Java program. <br>
**5)** Your plot should be *line* type and the line color should be *dark brown*. Use *grid* in your graph.<br>
<br>
Data source file: [swe307_pro1.csv](swe307_pro1.csv)
