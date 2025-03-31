# Ex03 Time Table

# Date:31.03.2025

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

# PROGRAM

```
<!DOCTYPE html>
<html>
<head>
    <title>Time Table</title>
</head>
<body>
    <center>
    <img src="\static\logo.png" height="100" width="600">
    </center>
    <h4 align="center"><b>SLOT TIME TABLE - SAI SATHYA V (22008626)</b></h4>
    <table border="4" width="40%" align="center" bgcolor="cyan" >
        <tr bgcolor="yellow" align="center">
            <th>Day/Time</th>
            <th>Monday</th>
            <th>Tuesday</th>
            <th>Wednesday</th>
            <th>Thursday</th>
            <th>Friday</th>
        </tr>
        <tr bgcolor="cyan" align="center">
            <td bgcolor="yellow"><b>8-10</b></td>
            <td colspan="3" align="center">FREE SLOT</td>
            <td>PHY</td>
            <td>CHE</td>
        </tr>
        <tr bgcolor="cyan" align="center">
            <td bgcolor="yellow"><b>10-12</b></td>
            <td>GER</td>
            <td>FREE SLOT</td>
            <td>FWAD</td>
            <td>FWAD</td>
            <td>PHY</td>
        </tr>
        <tr bgcolor="cyan" align="center">
            <td bgcolor="yellow"><b>12-1</b></td>
            <td colspan="6" align="center">LUNCH</td>
        </tr>
        <tr bgcolor="cyan" align="center">
            <td bgcolor="yellow"><b>1-3</b></td>
            <td colspan="2" align="center">FREE SLOT</td>
            <td>MAT</td>
            <td>MAT</td>
            <td>SS</td>
        </tr>
        <tr bgcolor="cyan" align="center">
            <td bgcolor="yellow"><b>3-5</b></td>
            <td colspan="2" align="center">FREE SLOT</td>
            <td>GER</td>
            <td>CHE</td>
            <td>FWAD</td>
        </tr>

    </table>
    
    <table border="3" width="40%" align="center"><br>
        <tr align="center">
            <th>S. No.</th>
            <th>Subject Code</th>
            <th>Subject Name</th>
        </tr>
        <tr align="center">
            <td>1</td>
            <td>19AI414</td>
            <td>Fundamentals of Web Application Development (FWAD)</td>
        </tr>
        <tr align="center">
            <td>2</td>
            <td>19EN612</td>
            <td>German Basic (GER)</td>
        </tr>
        <tr align="center">
            <td>3</td>
            <td>19PH206</td>
            <td>Physics for Information Technology (PHY)</td>
        </tr>
        <tr align="center">
            <td>4</td>
            <td>19CY205</td>
            <td>Principles of Chemistry in Engineering (CHE)</td>
        </tr>
        <tr align="center">
            <td>5</td>
            <td>19MA201</td>
            <td>Calculus and Matrix Algebra (MAT)</td>
        </tr>
        <tr align="center">
            <td>6</td>
            <td>19EY701</td>
            <td>Soft Skills (SS)</td>
        </tr>
    </table>
</body>
</html>
```
# OUTPUT
![alt text](<Screenshot 2025-03-31 162320.png>)

# RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
