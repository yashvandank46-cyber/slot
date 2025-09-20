# Ex03 Time Table
## Date:20.09.2025

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
'''
<html>
    <head>
        <title>SLOT TIME TABLE-YASHVANDAN-(25017523)</title>
    </head>
    <body>
       <img src="/static/logo.png" height="100" width="540">
        <h1>SLOT TIME TABLE-YASHVANDAN(25017523)</h1>
        <table border="4" align="centre">
            <tr bgcolor="green">
                <th>Day/Time</th>
                <th>Monday</th>
                <th>Tuesday</th>
                <th>Wednesday</th>
                <th>Thursday</th> 
                <th>Friday</th>
                <th>Saturday</th>
            </tr>
            <tr>
                <th bgcolor="green">8:00-10:00</th>
                <td>Free</td>
                <td>Free</td>
                <td>Web</td>
                <td>Free</td>
                <td>Free</td>
                <td>Web</td>
            </tr>
            <tr>
                <th bgcolor="green">10:00-12:00</th>
                <td>Python</td>
                <td>English</td>
                <td>Web</td>
                <td>English</td>
                <td>Free</td>
                <td>Free</td>
            <tr>
                <th bgcolor="green">12:00-1:00</th>
                <td colspan="6" align="center">LUNCH BREAK</td>
            </tr>
            <tr>
                <th bgcolor="green">1:00-3:00</th>
                <td>Python</td>
                <td>Python</td>  
                <td>Mentor</td>
                <td>Python</td>
                <td>Web</td>
                <td>Web</td>
            </tr>
            <tr>
                <th bgcolor="green">3:00-5:00</th>
                <td>English</td>
                <td>English</td>
                <td>English</td>
                <td>Python</td>
                <td>Free</td>
                <td>English</td>
            </tr>
        </table>
    </body>
</html>
<br>
<html>
    <head>
        <table border="4">
            <tr>
                <th>S.No.</th>
                <th>Subject Code</th>
                <th>Subject Name</th>
            </tr>
            <tr>
                <th>1.</th>
                <th>19AI414</th>
                <th>FWAD</th>
            </tr>
            <tr>
                <th>2.</th>
                <th>19AI301</th>
                <th>Python</th>
            </tr>
            <tr>
                <th>3.</th>
                <th>19EN101</th>
                <th>English</th>
            </tr>
        </table>
    </head>
</html>
'''

## OUTPUT
![alt text](Screenshot_20-9-2025_12310_127.0.0.1-1.jpeg)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
