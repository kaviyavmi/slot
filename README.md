# Ex03 Time Table
## Date:24-04-25

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
<head>
    <title>Class Timetable</title>
    <style>
        table {
            width: 60%;
            border-collapse: collapse;
            margin-bottom: 20px;
        }
        th, td {            border: 1px solid black;
            padding: 8px;
            text-align: center;
        }
        th {
            background-color: yellow;
        }
        .highlight {
            background-color: lightblue;
        }
    </style>
</head>
<body>
<center>
    <img src="logo.png" height="100" width="750">

    
<h2>Class Timetable</h2>
<table>
    <tr>
        <th>Day/Time</th>
        <th>Monday</th>
        <th>Tuesday</th>
        <th>Wednesday</th>
        <th>Thursday</th>
        <th>Friday</th>
    </tr>
    <tr class="highlight">
        <td>8-10</td>
        <td>CHEMISTRY</td>
        <td>C PROGRAMMING</td>
        <td>FREE SLOT</td>
        <td>PHY</td>
        <td>PROBABILITY</td>
    </tr>
    <tr class="highlight">
        <td>10-12</td>
        <td>STATISTICS</td>
        <td>PHY</td>
        <td>FWAD</td>
        <td>FWAD</td>
        <td>FREE SLOT</td>
    </tr>
    <tr>
        <td>12-1</td>
        <td colspan="5">LUNCH</td>
    </tr>
    <tr class="highlight">
        <td>1-3</td>
        <td>C PROGRAMMING</td>
        <td>CHEMISTRY</td>
        <td>MAT</td>
        <td>MAT</td>
        <td>SS</td>
    </tr>
    <tr class="highlight">
        <td>3-5</td>
        <td>FREE SLOT</td>
        <td>STATISTICS</td>
        <td>PROBABILITY</td>
        <td>FWAD</td>
        <td>FREE SLOT</td>
    </tr>
</table>

<h2>Subject Details</h2>
<table>
    <tr>
        <th>S. No.</th>
        <th>Subject Code</th>
        <th>Subject Name</th>
    </tr>
    <tr>
        <td>1</td>
        <td>19AI414</td>
        <td>Fundamentals of Web Application Development (FWAD)</td>
    </tr>
    <tr>
        <td>2</td>
        <td>19CY205</td>
        <td>Chemistry(chem)</td>
    </tr>
    <tr>
        <td>3</td>
        <td>19PH206</td>
        <td>Physics for Information Technology (PHY)</td>
    </tr>
    <tr>
        <td>4</td>
        <td>19MA211</td>
        <td>Probability (MAT)</td>
    </tr>
    <tr>
        <td>5</td>
        <td>19AI304</td>
        <td>C Programming (C PROGRAM)</td>
    </tr>
    <tr>
        <td>6</td>
        <td>19EY701</td>
        <td>Soft Skills (SS)</td>
    </tr>
    <tr>
        <td>7</td>
        <td>19MA412</td>
        <td>Statistics (MAT)</td>
    </tr>
</table>
</center>

</body>
</html>
```
## OUTPUT

![image](https://github.com/user-attachments/assets/9fc6e851-5372-41c2-b315-470c779cf6e4)


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
