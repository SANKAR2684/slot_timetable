# Ex03 Time Table
## Date:19-11-2024

## AIM
To write a html webpage page to display your slot timetable.

## ALGORITHM
### STEP 1
Create a Django-admin Interface.

### STEP 2
Create a static folder and inert HTML code.

### STEP 3
Create a simple table using ```<table>``` tag in html.

### STEP 4
Add header row using ```<th>``` tag.

### STEP 5
Add your timetable using ```<td>``` tag.

### STEP 6
Execute the program using runserver command.

## PROGRAM
```
<html>
  <head>
    <title>
      Slot_Timetable
    </title>
  </head>
  <center>
  <body>
    <img src="logo.png" width="800"><br><br>
    
   <table> <tr><td></td><td>SLOT TIME TABLE -Sankar S (24900401)</td></table>
    <table border="5"  width="50%" align="center" bgcolor="cyan">

      <tr>
         <th bgcolor="yellow">DAY/TIME</th>
         <th bgcolor="yellow">MONDAY</th>
         <th bgcolor="yellow">TUESDAY</th>
         <th bgcolor="yellow">WEDNESDAY</th>
         <th bgcolor="yellow">THURSDAY</th>
         <th bgcolor="yellow">FRIDAY</th>
         <th bgcolor="yellow">SATURDAY</th>
      </tr>

     
      <tr align="center">
         
         <td bgcolor="yellow">8:00AM-10:00AM</td> 
         <td>FREE SLOT</td> 
         <td bgcolor="green" style="color:aliceblue">BEE</td> 
         <td bgcolor="white" style="color:black">MATH</td> 
         <td>PHYSICS</td>
         <td>-</td>
         <td>-</td>

      </tr>
      <tr align="center">
         <td bgcolor="yellow">10:00AM-12:00PM</td> 
         <td bgcolor="white" style="color:black">SOFT SKILLS</td> 
         <td bgcolor="brown"style="color:aliceblue"> DE </td> 
         <td bgcolor="green"style="color:aliceblue"> BEE </td> 
         <td>MATH</td>
         <td bgcolor="orange" style="color:aliceblue"> DE</td>
         <td bgcolor="blue" style="color:aliceblue">FWAD</td>
      </tr>
      <tr>
         <td bgcolor="yellow">12:00PM-1:00pm</td>
         <td align="center" COLSPAN="6">LUNCH BREAK
         </td>
 
      </tr>

      <tr align="center">
      <td bgcolor="yellow">1:00PM-3:00AM</td> 
      <td bgcolor="gray" style="color:aliceblue">PYTHON</td> 
      <td bgcolor="blue" style="color:aliceblue">FWAD</td> 
      <td>MENTOR</td> 
      <td bgcolor="blue" style="color:aliceblue">FWAD</td>
      <td bgcolor="brown" style="color:aliceblue">PHYSICS</td>
      <td bgcolor="orange" style="color:aliceblue">PYTHON</td>

     </tr>
   </table><br><br>

    <table border="5">

      <tr>
        <th>
          S.No
        </th>
        <th>
          Subject Code
        </th>
        <th>
          Subject Name
        </th>
      </tr>


      <tr>
        <td>
          1.
        </td>
        <td>
          19AI414
        </td>
        <td>
          Fundamentals of Web Application Development(FWAD)
        </td>
      </tr>


      <tr>
        <td>
          2.
        </td>
        <td>
          19MA201
        </td>
        <td>
          Calculas and Matrix Algebra(MAT)
        </td>
      </tr>

      <tr>
        <td>
         3.
        </td>
        <td>
          19AI301
        </td>
        <td>
          Python Programming(PYTHON)
        </td>
      </tr>

      <tr>
        <td>
          4.
        </td>
        <td>
          SH7101
        </td>
        <td>
          Heritage Of Tamils(TAMIL)
        </td>
      </tr>

      <tr>
        <td>
          5.
        </td>
        <td>
          19EE305
        </td>
        <td>
          Basic Electrical ,Electronics and Measurment Engineering(BEEE)
        </td>
      </tr>

      <tr>
        <td>
          6.
        </td>
        <td>
          19EE404
        </td>
        <td>
          Digital Electronics(DE)
        </td>
      </tr>

      <tr>
        <td>
          7.
        </td>
        <td>
          19EY708
        </td>
        <td>
          Soft Skills
        </td>
      </tr>

      <tr>
        <td>
          8.
        </td>
        <td>
          SH3214
        </td>
        <td>
          Physics for quantum computing
        </td>
      </tr>

    </table>
  </body>
</center>
</html>
```
## OUTPUT
![alt text](<Screenshot 2024-11-19 185332.png>)
## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
