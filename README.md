# Ex02 Time Table
# Date: 11.05.2026
# AIM
To write a html webpage page to display your slot timetable.

# ALGORITHM
## STEP 1
Create a Django-admin Interface.

## STEP 2
Create a static folder and inert HTML code.

## STEP 3
Create a simple table using `<table>` tag in html.

## STEP 4
Add header row using `<th>` tag.

## STEP 5
Add your timetable using `<td>` tag.

## STEP 6
Execute the program using runserver command.

# PROGRAM
```
<!DOCTYPE html>
<html>
    <style>
    img 
    {
        width: 500px;
        height: auto;
    }
    </style>
    <center>
        <img src="https://saveetha.ac.in/wp-content/uploads/2024/03/sec-logo-01as.png">
    </center>
    <head>
        <title>Time Table 📆</title>
        <style>
            table,th,td{
                text-align: center;
                border: 4px;
                padding: 10px;
            }
        </style>
    </head>
    <body>
        <center>
            <h2 style="text-align: center;"> TIME TABLE- Deetchana S</h2>
            <table style="background-color:rgb(255, 1, 103)">
                <th>DAYS</th>
                <th>8-10</th>
                <th>10-12</th>
                <th>12-1</th>
                <th>1-3</th>
                <th>3-5</th>
            </tr>
            <tr bgcolor="pink" align="center">
                <th style="background-color:rgb(255, 1, 103) ">MONDAY</th>
                <td colspan="5"> HOLIDAY </td>
            </tr>
            <tr bgcolor="pink" align="center">
                <th style="background-color: rgb(255, 1, 103)">TUESDAY</th>
                <td>Fundamentals of Web Application Development</td>
                <td>Free Slot</td>
                <td rowspan="6"> L<br>U<br>N<br>C<br>H<BR></td>
                <td>Free Slot</td>
                <td>Free Slot</td>
                
            </tr>
            <tr bgcolor="pink" align="center">
                <th style="background-color: rgb(255, 1, 103)">WEDNESDAY</th>
                <td>Fundamentals of Web Application Development</td>
                <td>Free Slot</td>
                <td>Mentor Meet</td>
                <td>Fundamentals of C Programming</td>
                
                
            </tr>
            <tr bgcolor="pink" align="center">
                <th style="background-color: rgb(255, 1, 103)">THURSDAY</th>
                <td>Cloud Computing</td>
                <td>Fundamentals of C Programming</td>
                
                <td>Free Slot</td>
                <td>Free Slot</td>
            </tr>
            <tr bgcolor="pink" align="center">
                <th style="background-color: rgb(255, 1, 103)">FRIDAY</th>
                <td>Fundamentals of Web Application Development</td>
                <td>Fundamentals of C Programming</td>
                
                <td>Cloud Computing</td>
                <td>Free Slot</td>
            </tr>
            <tr bgcolor="pink" align="center">
                <th style="background-color: rgb(255, 1, 103)">SATURDAY</th>
                <td>Fundamentals of Web Application Development</td>
                <td>Fundamentals of C Programming</td>
                
                <td>Free Slot</td>
                <td>Free Slot</td>
            </tr>
           
            
        </table>
        </center>
    </body>
</html>
 <br>
 <br>z
 <center>
    <table bgcolor="lavender">
        <tr bgcolor="plum">
            <th>S.no</th>
            <th>SUBJECT CODE</th>
            <th>SUBJECT NAME</th>
        </tr>
        <tr>
<td bgcolor="plum">1.</td>
            <td bgcolor="plum">19AI414</td>
            <td bgcolor="plum">Fundamentals of Web Application Development</td>
        </tr>
        <tr>
            <td bgcolor="plum">2.</td>
            <td bgcolor="plum">19AI304</td>
            <td bgcolor="plum">Fundamentals of C Programming </td>
        </tr>
        <tr>
        <td bgcolor='plum'>3.</td>
            <td bgcolor="plum">19AI541</td>
            <td bgcolor="plum">Cloud Computing</td>
        </tr>
    </table>
 </center>
```
# OUTPUT
<img width="1607" height="963" alt="image" src="https://github.com/user-attachments/assets/f7518f6c-20cb-473a-8cf7-7f853f215141" />


# RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
