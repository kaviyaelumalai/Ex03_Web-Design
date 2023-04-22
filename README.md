# Ex.03 Slot Time Table
## AIM
  To create slot time table.

## ALGORITHM
### STEP-1
  Open notepad and type the HTML code.

### STEP-2
  Insert the college logo using ```<img>``` tag.

### STEP-3
  Use the ```<table>``` tag with proper cell spacing and cell padding.  

### STEP-4
  Give your name and register number as table title using ```<caption>``` tag.

### STEP-5
  Enter the slot times and days as table header using ```<th>``` tag.
  
### STEP-6
  Type the subjects in the respective slots using ```<tr>``` and ```<td>``` tags.
 
### STEP-7
  Open the file in a browser and verify the output.
  
## CODE
~~~
<html>
<head>
<title>slot timetable</title>
</head>
<body>
<img src="saveethalogo.png"width="1000" height="150" align"center">
<h1 style="text-align:center">SLOT TIME TABLE-KAVIYA.E(212222250013)</h1>
<table border=1px solid black width="100%">
<tr style="background-color:purple">
<th>Day/Time</th>
<th>Monday</th>
<th>Tuesday</th>
<th>Wednesday</th>
<th>Thursday</th>
<th>Friday</th>
</tr>
<tr style="background-color:pink">
<td style="background-color:purple"">8-10</td>
<td>COMPLEX VARIABLES & DIFFERENTIAL EQUATIONS</td>
<td>WEB DESIGNING</td>
<td>STRENGTH OF MATERIALS</td>
<td>ENGINEERING PHYSICS</td>
<td>COMPLEX VARIABLES & DIFFERENTIAL EQUATIONS</td>
</tr>
<tr style="background-color:pink">
<td style="background-color:purple">10-12</td>
<td>ELECTRICAL MACHINES & POWER UTILIZATION</td>
<td>FREE SLOT</td>
<td>FREE SLOT</td>
<td>THEORY OF MACHINES</td>
<td>STRENGTH OF MATERIALS</td>
</tr>
<tr style="background-color:pink">
<td style="background-color:purple">12-1</td>
<td colspan="5" align="center">LUNCH</td>
</tr>
<tr style="background-color:pink">
<td style="background-color:purple">1-3</td>
<td>IRRIGATION & DRAINAGE ENGINEERING</td>
<td>IRRIGATION & DRAINAGE ENGINEERING</td>
<td>ENGINEERING PHYSICS</td>
<td>PRINCIPLES OF SOIL SCIENCE</td>
<td>PRINCIPLES OF HORTICULTURE</td>
</tr>
<tr style="background-color:pink"">
<td style="background-color:purple">3-5</td>
<td>PRINCIPLES OF HORTICULTURE</td>
<td>PRINCIPLES OF SOIL SCIENCE</td>
<td>FREE SLOT</td>
<td>ELECTRICAL MACHINES & POWER UTILIZATION</td>
<td>WEB DESIGNING</td>
</tr>
</table>
</body>
</html>
~~~

## OUTPUT
![ex03](https://user-images.githubusercontent.com/127817032/233778437-22a2c6a6-2d62-4083-9222-b0fe8386474a.png)


## RESULT
 Slot time table is created successfully.
