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

```
<html>
<head>
<title>Semester Time Table</title>
</head>
<body background="C:\Users\user\slot\bgphoto.jpg">
<img src="C:\Users\user\slot\logo.png">
<h3>SLOT TIME TABLE-SMRITI M (212221040157)</h3>
<table border="2" cellspacing="5" cellpadding="5" width="40" height="30">
<tr>
<th bgcolor="lightgrey">Day/Time</th>
<th bgcolor="lightblue">Monday</th>
<th bgcolor="lightgreen">Tuesday</th>
<th bgcolor="lightyellow">Wednesday</th>
<th bgcolor="lightcoral">Thursday</th>
<th bgcolor="lightsalmon">Friday</th>
<th bgcolor="lightseagreen">Saturday</th>
</tr>
<tr>
<td bgcolor="lightgrey">8-9</td>
<td bgcolor="lightblue" rowspan='2'>FREE SLOT</td>
<td bgcolor="lightgreen" rowspan='2'>AI</td>
<td bgcolor="lightyellow" rowspan='2'>PQT</td>
<td bgcolor="lightcoral" rowspan='2'>MP&MC</td>
<td bgcolor="lightsalmon" rowspan='2'>FWAD</td>
<td bgcolor="lightseagreen">TOC</td>
</tr>
<tr>
<td bgcolor="lightgrey">9-10</td>
<td bgcolor="lightseagreen">FREE SLOT</td>
</tr>
<tr>
<td bgcolor="lightgrey">10-11</td>
<td bgcolor="lightblue" rowspan='2'>FREE SLOT</td>
<td bgcolor="lightgreen" rowspan='2'>TOC</td>
<td bgcolor="lightyellow" rowspan='2'>FREE SLOT</td>
<td bgcolor="lightcoral" rowspan='2'>EMPLOYMENT SKILLS</td>
<td bgcolor="lightsalmon" rowspan='2'>FREE SLOT</td>
<td bgcolor="lightseagreen">MP&MC</td>
</tr>
<tr>
<td bgcolor="lightgrey">11-12</td>
<td bgcolor="lightseagreen">FREE SLOT</td>
</tr>
<tr>
<td bgcolor="lightgrey">12-1</td>
<td bgcolor="lightblue">LUNCH</td>
<td bgcolor="lightgreen">MENTORING</td>
<td bgcolor="lightyellow">LUNCH</td>
<td bgcolor="lightcoral">LUNCH</td>
<td bgcolor="lightsalmon">LUNCH</td>
<td bgcolor="lightseagreen">LUNCH</td>
</tr>
<tr>
<td bgcolor="lightgrey">1-2</td>
<td bgcolor="lightblue" rowspan='2'>MP&MC</td>
<td bgcolor="lightgreen" rowspan='2'>FWAD</td>
<td bgcolor="lightyellow" rowspan='2'>MAD</td>
<td bgcolor="lightcoral" rowspan='2'>FWAD</td>
<td bgcolor="lightsalmon" rowspan='2'>PQT</td>
<td bgcolor="lightseagreen" rowspan='2'>MAD</td>
</tr>
<tr>
<td bgcolor="lightgrey">2-3</td>
</tr>
<tr>
<td bgcolor="lightgrey">3-4</td>
<td bgcolor="lightblue" rowspan='2'>FREE SLOT</td>
<td bgcolor="lightgreen" rowspan='2'>FREE SLOT</td>
<td bgcolor="lightyellow" rowspan='2'>FREE SLOT</td>
<td bgcolor="lightcoral" rowspan='2'>FREE SLOT</td>
<td bgcolor="lightsalmon" rowspan='2'>FREE SLOT</td>
<td bgcolor="lightseagreen" rowspan='2'>AI</td>
</tr>
<tr>
<td bgcolor="lightgrey">4-5</td>
</tr>
</table>
<br>
<table border="2" cellspacing="3" cellpadding="5">
<tr>
<th bgcolor="orange">S.No.</th>
<th bgcolor="pink">Subject Code</th>
<th bgcolor="lightyellow">Subject Name</th>
</tr>
<tr>
<td bgcolor="orange">1.</td>
<td bgcolor="pink">19AI414</td>
<td bgcolor="lightyellow">Fundamentals of Web Application Development (FWAD)</td>
</tr>
<tr>
<td bgcolor="orange">2.</td>
<td bgcolor="pink">19CS407</td>
<td bgcolor="lightyellow">Theory of Computation (TOC)</td>
</tr>
<tr>
<td bgcolor="orange">3.</td>
<td bgcolor="pink">19CS413</td>
<td bgcolor="lightyellow">Artificial Intelligence (AI)</td>
</tr>
<tr>
<td bgcolor="orange">4.</td>
<td bgcolor="pink">19CS414</td>
<td bgcolor="lightyellow">Mobile Application Development (MAD)</td>
</tr>
<tr>
<td bgcolor="orange">5.</td>
<td bgcolor="pink">19EC408</td>
<td bgcolor="lightyellow">Microprocessor and Microcontroller (MP&MC)</td>
</tr>
<tr>
<td bgcolor="orange">6.</td>
<td bgcolor="pink">19EY705</td>
<td bgcolor="lightyellow">Employment Enhancement Skills</td>
</tr>
<tr>
<td bgcolor="orange">7.</td>
<td bgcolor="pink">19MA218</td>
<td bgcolor="lightyellow">Probability and Queueing Theory (PQT)</td>
</tr>
<tr>
<td bgcolor="orange">8.</td>
<td bgcolor="pink">ECA-M</td>
<td bgcolor="lightyellow">Mentor Meet</td>
</tr>
</table>
</body>
</html>
```

## OUTPUT

<img width="954" alt="slotweb" src="https://github.com/SmritiManikand/slot/assets/113674204/e1ea6480-327b-4a24-8bce-faccc57dc2a4">

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
