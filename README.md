# Ex03 Time Table
## Date:14/11/24

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
    <body>
        <img src="logo.png">
        <table border="1" cellpadding="2">
            <caption>SLOT TIME TABLE-SUKIRTHANA(24005497)</caption>
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
                <td bgcolor="green">8-10</td>
                <td bgcolor="yellow" colspan="2">Free slot</td>
                <td bgcolor="yellow">Mat</td>
                <td bgcolor="yellow">Eng</td>
                <td bgcolor="yellow">FWAD</td>
                <td bgcolor="yellow">Free slot</td>
            </tr>
            <tr>
                <td bgcolor="green">10-12</td>
                <td bgcolor="yellow">Eng</td>
                <td bgcolor="yellow">EDM</td>
                <td bgcolor="yellow">C prog</td>
                <td bgcolor="yellow">Mat</td>
                <td bgcolor="yellow">C prog</td>
                <td bgcolor="yellow">CDM</td>
            </tr>
            <tr>
                <td bgcolor="green">12-1</td>
                <td bgcolor="yellow" colspan="6">Lunch</td>
            </tr>
            <tr>
                <td bgcolor="green">1-3</td>
                <td bgcolor="yellow">FWAD</td>
                <td bgcolor="yellow">FWAD</td>
                <td bgcolor="yellow">Mentor </td>
                <td bgcolor="yellow">Free slot</td>
                <td bgcolor="yellow">EDM</td>
                <td bgcolor="yellow">Chem</td>
            </tr>
            <tr>
                <td bgcolor="green">3-5</td>
                <td bgcolor="yellow" colspan="2">Free slot</td>
                <td bgcolor="yellow">Chem</td>
                <td bgcolor="yellow" colspan="3">Free slot</td>
            </tr>
        </table>
        <table border="1">
            <tr>
           <th>S.NO</th>
           <th>Course code</th>
           <th>Course name</th>
            </tr>
            <tr>
                <td>1.</td>
                <td>19AI414</td>
                <td>Fundamentals of Web Applications(FWAD)</td>
            </tr>
            <tr>
                <td>2.</td>
                <td>19AI304</td>
                <td>Fundamentals of C Programming(C Prog)</td>
            </tr>
            <tr>
                <td>3.</td>
                <td>19AI302</td>
                <td>Engineering Design and Modelling(EDM)</td>
            </tr>
            <tr>
                <td>4.</td>
                <td>19CY205</td>
                <td>Principles of Chemistry in Engineering(Chem)</td>
            </tr>
            <tr>
                <td>5.</td>
                <td>19EN101</td>
                <td>Communicative English(Eng)</td>
            </tr>
            <tr>
                <td>6.</td>
                <td>19EY708</td>
                <td>Career Development Skills(CDM)</td>
            </tr>
            <tr>
                <td>7.</td>
                <td>19MA201</td>
                <td>Calculus and Matrix Algebra(Mat)</td>
            </tr>
            <tr>
                <td>8.</td>
                <td>ECA-M-SCOFT</td>
                <td>Mentor Meet(Mentor)</td>
            </tr>
        </table>
    </body>
</html>
```
## OUTPUT
![alt text](<Screenshot (16).png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
