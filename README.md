# Ex03 Time Table
## Date: 25.03.2024

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
<title>Slot Timetable</title>
</head>
<body>
<center>
<img src="C:\Users\admin\Downloads\WhatsApp Image 2024-03-25 at 08.31.31_d6b840ce.jpg"" height="100" width="500">
</center>
<br>
<table align="center" width="500" cellspacing="3" cellpadding="2" border="2" bgcolor="gold">
<caption><b>SLOT TIME TABLE - HARRISH VENKAT V (23013973)</b></caption>
<tr align="center">
<th bgcolor="silver">Day/Time</th>
<th bgcolor="silver">Monday</th>
<th bgcolor="silver">Tuesday</th>
<th bgcolor="silver">Wednesday</th>
<th bgcolor="silver">Thursday</th>
<th bgcolor="silver">Friday</th>
<th bgcolor="silver">Saturday</th>
</tr>
<tr align="center">
<th bgcolor="silver">8-10</th>
<td>Fundamentals of Web Application Development</td>
<td>Digital electronics</td>
<td>C programming</td>
<td>Digital electronics</td>
<td>FREE SLOT</td>
<td>FREE SLOT</td>
</tr>
<tr align="center">
<th bgcolor="silver">10-12</th>
<td>C programming</td>
<td>Computer Networks</td>
<td>Basic elelectrical electronics and measurement engineering</td>
<td>Computer Networks</td>
<td>FREE SLOT</td>
<td>FREE SLOT</td>
</tr>
<tr>
<th bgcolor="silver">12-1</th>
<td colspan="6" align="center">L U N C H  B R E A K </td>
</tr>
<tr align="center">
<th bgcolor="silver">1-3</th>
<td>Basic elelectrical electronics and measurement engineering</td>
<td>Physics for quantum computing</td>
<td>Physics for qauntum computing</td>
<td>Fundamentals of Web Application Development</td>
<td>Fundamentals of Web Application Development</td>
<td>FREE SLOT</td>
</tr>
<tr align="center">
<th bgcolor="silver">3-5</th>
<td>FREE SLOT</td>
<td>FREE SLOT</td>
<td>FREE SLOT</td>
<td>FREE SLOT</td>
<td>FREE SLOT</td>
<td>FREE SLOT</td>
</tr>
</table>
<br>
<table align="center" cellspacing="2" cellpadding="2" border="2">
<tr align="center">
<th>S. No.</th>
<th>Subject Code</th>
<th>Subject Name</th>
</tr>
<tr>
<td align="center">1.</td>
<td align="center">19AI414</td>
<td>Fundamentals of Web Application Development(FWAD)</td>
</tr>
<tr>
<td align="center">2.</td>
<td align="center">19EE305</td>
<td>Basic elelectrical electronics and measurement engineering(BEEE)</td>
</tr>
<tr>
<td align="center">3.</td>
<td align="center">19CS406</td>
<td>Computer Networks(CN)</td>
</tr>
<tr>
<td align="center">4.</td>
<td align="center">19EE404</td>
<td>Digital Electronics(DE)</td>
</tr>
<tr>
<td align="center">5.</td>
<td align="center">19PH214</td>
<td>Physics for quantum computing(PQC)</td>
</tr>
<tr>
<td align="center">6.</td>
<td align="center">19AI305</td>
<td>C programming(C)</td>
</tr>
</table>
</body>
</html>
```

## OUTPUT
![image](https://github.com/HarrishVenkat/slot/assets/144979588/d691f3ab-fce8-479a-a33a-4feda3fb4915)


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
