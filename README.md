# Ex03 Time Table
## Date:21-04-25

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
        <title>My Time Table</title>
    </head>
    <body>
        <img src="/static/logo.png" height="100" width="570">
<br>
<table align="center" width="540" cellspacing="2" cellpadding="4" border="5" bgcolor="violet">
<caption><b>My Time Table - AKASH P(212224220006)</b></caption>
<tr align="center">
<th bgcolor="lavender">Day/Time</th>
<th bgcolor="sky blue">Monday</th>
<th bgcolor="sky blue">Tuesday</th>
<th bgcolor="sky blue">Wednesday</th>
<th bgcolor="sky blue">Thursday</th>
<th bgcolor="sky blue">Friday</th>
<th bgcolor="Sky blue">Saturday</th>
</tr>
<tr align="center">
<th bgcolor="Brown">8-10</th>
<td  bgcolor="orange"colspan="0" align="center">English</td>
<td bgcolor="orange">free slot</td>
<td bgcolor="orange">Free Slot</td>
<td bgcolor="orange">Free slot</td>
<td bgcolor="orange">Free slot</td>
<td bgcolor="orange">Free Slot</td>
</tr>
<tr align="center">
<th bgcolor="brown">10-12</th>
<td bgcolor="Fuchsia">Free Slot</td>
<td bgcolor="Fuchsia">Free slot</td>
<td bgcolor="Fuchsia">Logic And Combinatorics</td>
<td bgcolor="Fuchsia">Free slot</td>
<td bgcolor="Fuchsia">web app</td>
<td bgcolor="Fuchsia">Logic And Combinatorics</td>
</tr>
<tr>
<th bgcolor="brown">12-1</th>
<td colspan="6" align="center" bgcolor="White">L U N C H</td>
</tr>
<tr align="center">
<th bgcolor="brown">1-3</th>
<td colspan="0" align="center" bgcolor="red">software</td>
<td bgcolor="Red" >python</td>
<td bgcolor="Red">Mentor Meet</td>
<td bgcolor="Red">physics</td>
<td bgcolor="Red">physics</td>
<td bgcolor="Red">software</td>
</tr>
<tr align="center">
<th bgcolor="brown">3-5</th>
<td colspan="0" align="center" bgcolor="Cyan">software</td>
<td bgcolor="Cyan">free slot</td>
<td bgcolor="Cyan">python</td>
<td bgcolor="Cyan">web app</td>
<td bgcolor="Cyan">Free Slot</td>
<td bgcolor="Cyan">English</td>
</tr>
</table>
<br>
<table align="center" cellspacing="2" cellpadding="4" border="2">
<tr align="center">
<th>S. No.</th>
<th>Subject Code</th>
<th>Subject Name</th>
</tr>
<tr>
<td align="center">1.</td>
<td align="center">19AI301C</td>
<td>Python</td>
</tr>
<tr>
<td align="center">2.</td>
<td align="center">19AI414</td>
<td>Fundamentals of Web Application Development(FWAD)</td>
</tr>
<tr>
<td align="center">3.</td>
<td align="center">19CS408</td>
<td>Software Engineering</td>
</tr>
<tr>
<td align="center">4.</td>
<td align="center">19PY101</td>
<td>Quantum Physics</td>
</tr>
<tr>
<td align="center">5.</td>
<td align="center">19MA206</td>
<td>Logic And Combinatorics</td>
</tr>
<tr>
<td align="center">6.</td>
<td align="center">19EN101</td>
<td>Communicative English</td>
</tr>
<tr>
<td align="center">7.</td>
<td align="center">ECA-M</td>
<td>Mentor Meet</td>
</tr>
</table>
    </body>
</html>
```

## OUTPUT
![alt text](<Screenshot 2025-04-21 215737.png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
