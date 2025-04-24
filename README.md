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

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Timetable</title>
</head>
 
<style>
    table,th,td{border: 2px solid black; text-align: center;border-collapse: collapse;}
    
    th{ background-color: rgb(183, 170, 153);}
    
</style>    
<body style="background-color: rgb(234, 226, 226);">
    <div><a href="http://training.saveetha.in/" title="Saveetha Engineering College"> <img src="http://training.saveetha.in/pluginfile.php/1/core_admin/logo/0x200/1736356034/logo_1.png"; width=100% height=200px></a></div>
    <h1></h1>
    <table width = 100% height="50px" style="background-color: rgba(255, 255, 255, 0.937); border: 0cap;">
        <tr>
            <th style="background-color:rgb(57, 179, 216);border: 0cap; text-align: center;">SLOT TIME TABLE - KAVIYA V M (24900714)</th>
        </tr>  
    </table> 
    <table style="border: 2px solid black; text-align: center;background-color: rgb(255, 0, 230); width: 100%; height: 400px;">
        <tr>
            <th width="100"> Day/time </th>
            <th width="100"> Monday </th>
            <th width="100"> Tuesday </th>
            <th width="100"> Wednesday</th>
            <th width="100"> Thursday</th>
            <th width="100"> Friday</th>
            <th width="100"> Saturday</th>
        </tr>
        <tr>
            <th>8:00-10:00</th>
            <td>Chemistry</td>
            <td>Free slot</td>
            <td>Probability</td>
            <td colspan="3">Free hour</td>
        </tr>
        <tr>
            <th>10:00-12:00</th>
            <td>Reasoning</td>
            <td>Physics</td>
            <td>Python</td>
            <td>C programmer</td>
            <td colspan="2">Web</td>
        </tr>
        <tr>
            <th>12:00-1:00</th>
            <td colspan="7">LUNCH</td>
        </tr>
        <tr>
            <th>1:00-3:00</th>
            <td>Web</td>
            <td>Probability</td>
            <td>Free hour</td>
            <td>Chemistry</td>
            <td>C programmer</td>
            <td>Physics</td>
        </tr>
    </table>
<h1>
</h1>
<h2>
    
</h2>
    <table style="border: 2px solid black;background-color: white; width: 100%; height: 400px;">
         <tr>
            <th style="background-color: white;">S.NO</th>
            <th style="background-color: white;">SUBJECT CODE</th>
            <th style="background-color: white;">SUBJECT NAME</th>
         </tr>
         <tr> 
            <td>1.</td>
            <td>19AI414</td>
            <td>Fundamentals of Web Application Development(Web)</td>
         </tr>
         <tr>
            <td>2.</td>
            <td>19AI304</td>
            <td>C programming(c programmer)</td>
         </tr>
         <tr>
            <td>3.</td>
            <td>SH3214</td>
            <td>Physics for Quantum Computing(Physics)</td>
         </tr>
         <tr>
            <td>4.</td>
            <td>19EY709</td>
            <td>Reasoning ability(reasoning)</td>
         </tr>
         <tr>
            <td>5.</td>
            <td>19CY205</td>
            <td>Principles of Chemistry in Engineering(Chemistry)</td>
         </tr>
         <tr>
            <td>6.</td>
            <td>19MA211</td>
            <td>Probability and queing models(probability)</td>
         </tr>
    </table>


## OUTPUT

![image](https://github.com/user-attachments/assets/84cd35ae-cf6d-4e20-9296-8f9de7a3535e)
![image](https://github.com/user-attachments/assets/c9d74368-d5b7-41ee-8887-91116265968f)


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
