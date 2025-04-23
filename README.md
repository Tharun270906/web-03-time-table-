# Ex03 Time Table
# Date:23-04-2025
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

# PROGRAM:
```
<html>
<head>
<title> Course Schedule </title>
</head>
<body>
    <center>
        <img src="web exp-img.png"
        height="100"
        width="540"
    </center>
<br>
<table align="center" width="540" cellspacing="2" cellpadding="4" border="5" bgcolor="cyan">
<caption><b>SCHEDULE OF ALL COURSES - Tharun.A (212224100060)</b></caption>
<tr align="center">
<th bgcolor="yellow">Day/Time</th>
<th bgcolor="yellow">Monday</th>
<th bgcolor="yellow">Tuesday</th>
<th bgcolor="yellow">Wednesday</th>
<th bgcolor="yellow">Thursday</th>
<th bgcolor="yellow">Friday</th>
</tr>
<tr align="center">
<th bgcolor="yellow">8-10</th>
<td >FREE SLOT</td>
<td>FREE SLOT</td>
<td>FREE SLOT</td>
<td>C PROGRAMMING</td>
<td>C PROGRAMMING</td>
</tr>
<tr align="center">
<th bgcolor="yellow">10-12</th>
<td>BEEE</td>
<td>Computer Network</td>
<td>Communicative english</td>
<td>STATISTICS</td>
<td>FUNDAMENTALS OF WEB</td>
</tr>
<tr>
<th bgcolor="yellow">12-1</th>
<td colspan="5" align="center">L U N C H</td>
</tr>
<tr align="center">
<th bgcolor="yellow">1-3</th>
<td >STATISTICS</td>
<td>Ethical hacking</td>
<td>MENTOR MEET</td>
<td>Communicative english</td>
<td>Computer Network</td>
</tr>
<tr align="center">
<th bgcolor="yellow">3-5</th>
<td>FREE SLOT</td>
<td>FREE SLOT</td>
<td>FUNDAMENTALS OF WEB</td>
<td>Human values</td>
<td>BEEE</td>
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
<td align="center">19AI414</td>
<td>FUNDAMENTALS OF WEB APPLICATION DEVELOPMENT (FWAD)</td>
</tr>
<tr>
<td align="center">2.</td>
<td align="center">19AI304</td>
<td>FUNDAMENTALS OF C PROGRAMMING (C PROGRAM)</td>
</tr>
<tr>
<td align="center">3.</td>
<td align="center">19EN101</td>
<td> Communicative english (com.eng)</td>
</tr>
<tr>
<td align="center">4.</td>
<td align="center">19CS405</td>
<td>Computer network (CN)</td>
</tr>
<tr>
<td align="center">5.</td>
<td align="center">19MA211</td>
<td>STATISTICS AND NUMERICAL METHODS (MAT)</td>
</tr>
<tr>
<td align="center">6.</td>
<td align="center">19CS415</td>
<td>Ethical hacking(Etical)</td>
</tr>
<td align="center">7.</td>
<td align="center">19EY709</td>
<td>Human values (HV)</td>
</tr>
<td align="center">8.</td>
<td align="center">19EE305</td>
<td>BASIC ELECTRICAL ELECTRONICS AND MEASUREMENT ENGINEERING (BEEE)</td>
</table>
</body>
</html>
```
# OUTPUT:
![Screenshot 2025-04-23 135101](https://github.com/user-attachments/assets/559027e1-2b8c-4138-aab0-aae4a465f8fa)

# RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
