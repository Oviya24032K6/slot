# Ex03 Time Table
## Date:

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
<html>
    <title>TIME TABLE</title>
    <body>
       
        <br>
        <br>
    </body>
    <head>
    <center>
            <img src="oviya/static/logo.png" height="100" width="800">
        </center>

        <title>SLOT TIMETABLE-OVIYA P (23013207)</title>
    </head>
    <body bgcolor="white" align="center" >
    <table align="left" border="10" cellspacing="2" cellpadding="3">
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
            <th bgcolor="teal">8-10</th>
            <th bgcolor="salmon">FREE SLOT</th>
            <th bgcolor="salmon">SNM</th>
            <th bgcolor="salmon">FWAD</th>
            <th bgcolor="salmon">OS</th>
            <th bgcolor="salmon">FREE SLOT</th>
            <th bgcolor="salmon">CSC</th>
        </tr>
        <tr>
            <th bgcolor="teal">10-12</th>
            <th bgcolor="salmon">EBD</th>
            <th bgcolor="salmon">FWAD</th>
            <th bgcolor="salmon">FREE SLOT</th>
            <th bgcolor="salmon">CA</th>
            <th bgcolor="salmon">FCP</th>
            <th bgcolor="salmon">SNM</th>
        </tr>
        <tr>
            <th bgcolor="teal">12-1</th>
            <th bgcolor="salmon" colspan="6">LUNCH BREAK</th>
        </tr>
        <tr>
            <th bgcolor="teal">1-3</th>
            <th bgcolor="salmon">FWAD</th>
            <th bgcolor="salmon">OS</th>
            <th bgcolor="salmon">FREE SLOT</th>
            <th bgcolor="salmon">FREE SLOT</th>
            <th bgcolor="salmon">CA</th>
            <th bgcolor="salmon">FREE SLOT</th>
        </tr>
        <tr>
            <th bgcolor="teal">3-5</th>
            <th bgcolor="salmon">FCP</th>
            <th bgcolor="salmon">FREE SLOT</th>
            <th bgcolor="salmon">EBD</th>
            <th bgcolor="salmon" colspan="4">FREE SLOT</th>
        </tr>
        <tr>
            <th bgcolor="teal">5-7</th>
            <th bgcolor="salmon" >EMPD</th>
            <th bgcolor="salmon" colspan="2">FREE SLOT</th>
            <th bgcolor="salmon" >EMPD</th>
            <th bgcolor="salmon" colspan="2">FREE SLOT</th>

        </tr>
        


    <table bgcolor="salmon" align="left" border="10" cellspacing="5" cellpadding="3">
        <tr>
            <th>S.No</th>
            <th>Subject Code</th>
            <th>Subject Name</th>
        </tr>
        <tr>
            <th>1.</th>
            <th>19AI141</th>
            <th>Fundamentals of Web Application Development(FWAD)</th>
        </tr>
        <tr>
            <th>2.</th>
            <th>19CS405</th>
            <th>Operating System(OS)</th>
        </tr>
        <tr>
            <th>3.</th>
            <th>19AI303</th>
            <th>Engineering Mechanics and Product Development(EMPD)</th>
        </tr>
        <tr>
            <th>4.</th>
            <th>19AI304</th>
            <th>Fundamentals of C Programming(FCP)</th>
        </tr>
        <tr>
            <th>5.</th>
            <th>19CS305</th>
            <th>Embedded Board Design(EBD)</th>
        </tr>
        <tr>
            <th>6.</th>
            <th>19CS305</th>
            <th>Creative Skills for Communication(CSC)</th>
        </tr>
        <tr>
            <th>7.</th>
            <th>19CS542</th>
            <th>Embedded Board Design(EBD)</th>
        </tr>
        <tr>
            <th>8.</th>
            <th>19MA211</th>
            <th>Statics and Numerica Methods(SNM)</th>
        </tr>
        <tr>
            <th>9.</th>
            <th>19CS405</th>
            <th>Computer Architechture(CA)</th>
        </tr>
    </table>
</body>
</html>
</html>

## OUTPUT
![output](<EX-03 WEB OUTPUT.jpg>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
