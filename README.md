# Ex03 Time Table
## Date:13:03:2024

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
<!DOCTYPE html>
<html>
<head>
    <title>SLOT TIMETABLE-OVIYA P (23013207)</title>
</head>
<body bgcolor="white">
<center>
    <img src="oviya/static/logo.png" height="100" width="800">
</center>
<table align="center" border="1" cellspacing="2" cellpadding="3">
    <caption>SLOT TIMETABLE-OVIYA P (23013207)</caption>
    <tr>
        <th bgcolor="teal">DAY/TIME</th>
        <th bgcolor="teal">MONDAY</th>
        <th bgcolor="teal">TUESDAY</th>
        <th bgcolor="teal">WEDNESDAY</th>
        <th bgcolor="teal">THURSDAY</th>
        <th bgcolor="teal">FRIDAY</th>
        <th bgcolor="teal">SATURDAY</th>
    </tr>
    <tr>
        <td bgcolor="teal">8-10</td>
        <td bgcolor="salmon">FREE SLOT</td>
        <td bgcolor="salmon">SNM</td>
        <td bgcolor="salmon">FWAD</td>
        <td bgcolor="salmon">OS</td>
        <td bgcolor="salmon">FREE SLOT</td>
        <td bgcolor="salmon">CSC</td>
    </tr>
    <tr>
        <td bgcolor="teal">10-12</td>
        <td bgcolor="salmon">EBD</td>
        <td bgcolor="salmon">FWAD</td>
        <td bgcolor="salmon">FREE SLOT</td>
        <td bgcolor="salmon">CA</td>
        <td bgcolor="salmon">FCP</td>
        <td bgcolor="salmon">SNM</td>
    </tr>
    <tr>
        <td bgcolor="teal">12-1</td>
        <td bgcolor="salmon" colspan="6">LUNCH BREAK</td>
    </tr>
    <tr>
        <td bgcolor="teal">1-3</td>
        <td bgcolor="salmon">FWAD</td>
        <td bgcolor="salmon">OS</td>
        <td bgcolor="salmon">FREE SLOT</td>
        <td bgcolor="salmon">FREE SLOT</td>
        <td bgcolor="salmon">CA</td>
        <td bgcolor="salmon">FREE SLOT</td>
    </tr>
    <tr>
        <td bgcolor="teal">3-5</td>
        <td bgcolor="salmon">FCP</td>
        <td bgcolor="salmon">FREE SLOT</td>
        <td bgcolor="salmon">EBD</td>
        <td bgcolor="salmon" colspan="3">FREE SLOT</td>
    </tr>
    <tr>
        <td bgcolor="teal">5-7</td>
        <td bgcolor="salmon">EMPD</td>
        <td bgcolor="salmon" colspan="2">FREE SLOT</td>
        <td bgcolor="salmon">EMPD</td>
        <td bgcolor="salmon" colspan="2">FREE SLOT</td>
    </tr>
</table>

<table bgcolor="salmon" align="center" border="1" cellspacing="5" cellpadding="3">
    <caption>Subject Details</caption>
    <tr>
        <th>S.No</th>
        <th>Subject Code</th>
        <th>Subject Name</th>
    </tr>
    <tr>
        <td>1.</td>
        <td>19AI141</td>
        <td>Fundamentals of Web Application Development (FWAD)</td>
    </tr>
    <tr>
        <td>2.</td>
        <td>19CS405</td>
        <td>Operating System (OS)</td>
    </tr>
    <tr>
        <td>3.</td>
        <td>19AI303</td>
        <td>Engineering Mechanics and Product Development (EMPD)</td>
    </tr>
    <tr>
        <td>4.</td>
        <td>19AI304</td>
        <td>Fundamentals of C Programming (FCP)</td>
    </tr>
    <tr>
        <td>5.</td>
        <td>19CS305</td>
        <td>Embedded Board Design (EBD)</td>
    </tr>
    <tr>
        <td>6.</td>
        <td>19CS305</td>
        <td>Creative Skills for Communication (CSC)</td>
    </tr>
    <tr>
        <td>7.</td>
        <td>19CS542</td>
        <td>Embedded Board Design (EBD)</td>
    </tr>
    <tr>
        <td>8.</td>
        <td>19MA211</td>
        <td>Statics and Numerical Methods (SNM)</td>
    </tr>
    <tr>
        <td>9.</td>
        <td>19CS405</td>
        <td>Computer Architecture (CA)</td>
    </tr>
</table>
</body>
</html>
```



## OUTPUT
![slot final](https://github.com/Oviya24032K6/slot/assets/147139999/3fd53fba-b63d-4b68-b4d2-9b48678635e0)


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
