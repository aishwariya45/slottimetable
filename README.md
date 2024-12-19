# Ex03 Time Table
# Date: 27/11/2024
# AIM
To write a html webpage page to display your slot timetable.

# ALGORITHM
## STEP 1
Create a Django-admin Interface.

## STEP 2
Create a static folder and inert HTML code.

## STEP 3
Create a simple table using ```<table>``` tag in html.

## STEP 4
Add header row using ```<th>``` tag.

## STEP 5
Add your timetable using ```<td>``` tag.

## STEP 6
Execute the program using runserver command.

# PROGRAM

```
<html>
<head>
<title>time table</title>
</head>
<body>
    <center>
        <img src="C:\Users\admin\slottimetable\sec logo.png">

    <table>'
        <style>
             table,th,td{border:2px solid black;
            border-collapse:collapse;}
        </style>
        <caption align="center"><b>SLOT TIME TABLE-AISHWARIYA S(24900840)</b></caption>
        <tr>
            <td bgcolor="violet">day</td>
            <td bgcolor="grey">8am to 10am</td>
            <td bgcolor="grey">10am to 12pm</td>
            <td bgcolor="grey">1pm to 3pm</td>
            <td bgcolor="grey">3pm to 5pm</td>
        </tr>
        <tr>
        <td bgcolor="violet">MONDAY</td>
        <td bgcolor="aquamarine"></td>
        <td bgcolor="blue">WEB</td>
        <td bgcolor="aquamarine"></td>
        <td bgcolor="aquamarine"></td>
        </tr>
        <tr>
        <td bgcolor="violet">Tuesday</td>
        <td bgcolor="yellow">BEEE</td>
        <td bgcolor="red">DE</td>
        <td bgcolor="green">python</td>
        <td bgcolor="aquamarine"></td>
        </tr>
        <tr>
        <td bgcolor="violet">Wednesday</td>
        <td bgcolor="aquamarine"></td>
        <td bgcolor="yellow">BEEE</td>
        <td bgcolor="aquamarine"></td>
        <td bgcolor="aquamarine"></td>
        </tr>
        <tr>
        <td bgcolor="violet">Thursday</td>
        <td bgcolor="aquamarine"></td>
        <td bgcolor="green">python</td>
        <td bgcolor="blue">WEB</td>
        <td bgcolor="aquamarine"></td>
        </tr>
        <tr>
        <td bgcolor="violet">Friday</td>
        <td bgcolor="aquamarine"></td>
        <td bgcolor="red">DE</td>
        <td bgcolor="green">python</td>
        <td bgcolor="aquamarine"></td>
        </tr>
        <tr>
        <td bgcolor="violet">Saturday</td>
        <td bgcolor="aquamarine"></td>
        <td bgcolor="pink">CDS</td>
        <td bgcolor="green">python</td>
        <td bgcolor="blue">WEB</td>
        </tr>

    </table><br>

    
    <table>
    
        <style>
            table,th,td{border:2px solid black;border-collapse: collapse;}
        </style>

        <tr bgcolor="wheat">
            <td>slot number</td>
            <td>subject</td>
        </tr>
        <tr bgcolor="green">
            <td>19AI301C</td>
            <td>Python and Linear algebra</td>
        </tr>
        <tr bgcolor="blue">
            <td>19AI414</td>
            <td>Fundamentals of web application</td>
        </tr>
        <tr bgcolor="yellow">
            <td>19EE305</td>
            <td>BEEE</td>
        </tr>
        <tr bgcolor="red">
            <td>19EE404</td>
            <td>Digital electronics</td>
        </tr>
        <tr bgcolor="pink">
            <td>19EY708</td>
            <td>Career Development skills</td>

        </tr>
        </center
        </table>
        </body>
        </html>

```
# OUTPUT
![image](https://github.com/user-attachments/assets/fad423d7-c539-47a7-90a4-f41392d9706a)

# RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
