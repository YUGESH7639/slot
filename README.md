# Ex03 Time Table
## Date:15-11-2024

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
    <center>
 <img src="logo.png"height="100" width="550" align="center">
    </center>
 <br>

<table border="8" width="550" cellspacing="8" cellpadding="7" align="center" >
    <caption><b>Time table (YUGESH-24900164)</b></caption>
    <tr bgcolor="green">
        <th bgcolor="grey">Day</th>
        <th>8-10</th>
        <th>10-12</th>
        <th>12-1</th>
        <th>1-3</th>
        <th>3-5</th>
    </tr>
    <tr>
        <td bgcolor="grey">Monday</td>
        <td>D.E</td>
        <td>C prog</td>
        <td bgcolor="red">LUNCH</td>
        <td>Chem</td>
        <td bgcolor="yellow">FREE</td>
        
    </tr>
    <tr>
        <td bgcolor="grey">Tuesday</td>
        <td>WEB</td>
        <td bgcolor="yellow">FREE</td>
        <td bgcolor="red">LUNCH</td>
        <td>D.E</td>
        <td bgcolor="yellow">FREE</td>
    </tr>
    <tr>
        <td bgcolor="grey">Wednesday</td>
        <td>Mat</td>
        <td>EEE</td>
        <td bgcolor="red">LUNCH</td>
        <td>Scoft</td>
        <td bgcolor="yellow">FREE</td>    
    </tr>
    <tr>
      <td bgcolor="grey">Thursday</td>
      <td bgcolor="yellow">FREE</td>
      <td>Mat</td>
      <td bgcolor="red">LUNCH</td>
      <td>Chem</td>
      <td bgcolor="yellow">FREE</td>  
    </tr>
    <tr>
        <td bgcolor="grey">Friday</td>
        <td bgcolor="yellow">FREE</td>
        <td>C prog</td>
        <td bgcolor="red">LUNCH</td>
        <td>WEB</td>
        <td bgcolor="yellow">FREE</td>
    </tr>
    <tr>
        <td bgcolor="grey">Saturday</td>
        <td bgcolor="yellow">FREE</td>
        <td>EEE</td>
        <td bgcolor="red">LUNCH</td>
        <td>WEB</td>
        <td bgcolor="yellow">FREE</td>
    </tr>
</table>
<br>




<table border="1" cellspacing="1" cellpadding="2" align="center">
    <tr>
        <th>S.NO</th>
        <th>COURSE CODE</th>
        <th>COURSE NAME</th>
    </tr>
    <tr>
        <td>1</td>
        <td>19AI304</td>
        <td>Fundamentals of C Programming</td>
    </tr>
    <tr>
        <td>2</td>
        <td>19AI414</td>
        <td>Fundamentals of Web Application Development</td>
    </tr>
    <tr>
        <td>3</td>
        <td>19CY205</td>
        <td>Principle of Chemistry in Engineering</td>
    </tr>
    <tr>
        <td>4</td>
        <td>19EE305</td>
        <td>Basic Electrical,Electronics and Measurement Engineering</td>
    </tr>
    <tr>
        <td>5</td>
        <td>19EE404</td>
        <td>Digital Electronics</td>
    </tr>
    <tr>
        <td>6</td>
        <td>19MA201</td>
        <td>Calculus and Matrix Algebra</td>
    </tr>
    <tr>
        <td>7</td>
        <td>ECA-M</td>
        <td>Mentor Meet</td>
    </tr>
</table>
</body>
</html>
```

## OUTPUT
![alt text](<Screenshot (49).png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
