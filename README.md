# Ex03 Time Table
## Date:17/04/2025

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
~~~
<html>
    <head>
        
    </head>
    <body>
        
        <center>
            
            
            <img src="/static/logo.png" height="100" width="550">
            
            <h1>SLOT TIMETABLE </h1>

            <br><h2> V.HARSHINI       (reg no:212224040109)</h2>
            <hr color="black">
        </center>
        
        
        <table align="center" width="540" cellspacing="2" cellpadding="4" border="5" bgcolor="light green">
            <tr align="center">
                <th bgcolor="lightblue">DAY/TIME</th>
                <th bgcolor="lightblue">8:00-10:00</th>
                <th bgcolor="lightblue">10:00-12:00</th>
                <th bgcolor="lightblue">12:00-1:00</th>
                <th bgcolor="lightblue">1:00-3:00</th>
                <th bgcolor="lightblue">3:00-5:00</th>
            </tr>
            <tr align="center">
                <th bgcolor="yellow">MONDAY</th>
                <td>PROGRAMMING MICROCONTROLLERS</td>
                <td>FREE SLOT</td>
                <td>LUNCH</td>
                <td>PYTHON PROGRAMMING</td>
                <td>FREE SLOT</td>
                
            </tr>
            <tr align="center">
                <th bgcolor="yellow">TUESDAY</th>
                <td>INTRODUCTION TO MACHINE LEARNING</td>
                <td>COMPUTER ARCHITECTURE</td>
                <td>LUNCH </td>
                <td>FUNDAMENTALS OF WEB APPLICATION DEVELOPMENT</td>
                <td>FREE SLOT</td>
                
                
            </tr>
            <tr align="center">
                <th bgcolor="yellow">WEDNESDAY</th>
                <td>INTRODUCTION TO MACHINE LEARNING</td>
                <td>COMPUTER ARCHITECTURE</td>
                <td>LUNCH</td>
                <td>MENTOR MEET</td>
                <td>FREE SLOT</td>
            </tr>
            <tr align="center">
                <TH bgcolor="yellow">THURSDAY</TH>
                <TD>FREE SLOT</TD>
                <TD>FUNDAMENTALS OF WEB APPLICATION DEVELOPMENT</TD>
                <TD>LUNCH</TD>
                <TD>CHEMISTRY</TD>
                <TD>FREE SLOT</TD>
            </tr>
            <TR align="center">
                <TH bgcolor="yellow">FRIDAY</TH>
                <TD>FREE SLOT</TD>
                <TD>PYTHON PROGRAMMING</TD>
                <TD>LUNCH</TD>
                <TD>PROGRAMMING MICROCONTROLLERS</TD>
                <td>FREE SLOT</td>

            </TR>
            <TR align="center">
                <TH bgcolor="yellow">SATURDAY</TH>
                <TD>FREE SLOT</TD>
                <TD>CHEMISTRY</TD>
                <TD>LUNCH</TD>
                <TD>REASONING ABILITY</TD>
                <TD>FREE SLOT</TD>

            </TR>
        </table>
        <BR>
        <table align="center" cellspacing="2" cellpadding="4" border="2">
            <tr align="center">
                <th>S.NO : </th>
                <TH>SUBJECT CODE :</TH>
                <TH>SUBJECT NAME :</TH>
            </tr>
            <TR align="center">
                <td>1.</td>
                <td>19AI414</td>
                <TD>FUNDAMENTALS OF WEB APPLICATION</TD>
            </TR>
            <TR align="center">
                <TD>2.</TD>
                <TD>19AI301</TD>
                <TD>PYTHON PROGRAMMING</TD>
            </TR>
            <TR align="center">
                <TD>3.</TD>
                <TD>19AI401</TD>
                <TD>INTRODUCTION TO MACHINE LEARNING</TD>
            </TR>
            <TR align="center">
                <TD>4.</TD>
                <TD>19CS305</TD>
                <TD>COMPUTER ARCHITECTURE</TD>
            </TR>
            <TR align="center">
                <TD>5.</TD>
                <TD>19CY205</TD>
                <TD>PRINCIPLES OF CHEMISTRY IN ENGINEERING</TD>
            </TR>
            <TR align="center">
                <TD>6.</TD>
                <TD>19EY709</TD>
                <TD>REASONING ABILITY</TD>
            </TR>
            <TR align="center">
                <TD>7.</TD>
                <TD>19EE309</TD>
                <TD>PROGRAMMING MICROCONTROLLERS</TD>
            </TR>
        </table>
        
    </body>
</html>
~~~


## OUTPUT


![alt text](<Screenshot (104).png>)

![alt text](<Screenshot (102).png>)

![alt text](<Screenshot (103).png>)


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
