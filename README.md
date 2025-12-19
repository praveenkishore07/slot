# Ex02 Time Table
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
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>TIME TABLE </title>
</head>
<body>
    <center>
    <img  src="logo.png"  width="700" height="100" >
    <br>
    <table align="center" border="1" cellpadding="15" cellspacing="3" bgcolor="lightblue">
      <tr>
        <th bgcolor="lightpink">A Praveen Kishore</th>
        <th bgcolor="lightpink">REF:25010010</th>
        
      </tr>
    </table>
    </center>
    <table align="center" border="1" cellpadding="15" cellspacing="3" bgcolor="lightblue">
      <tr>
        
        <th bgcolor="lightcyan">TIME</th>
        <th bgcolor="lightGrey">MON</th>
        <th bgcolor="lightGrey">TUE</th>
        <th bgcolor="lightGrey">WED</th>
        <th bgcolor="lightGrey">THU</th>
        <th bgcolor="lightGrey">FRI</th>
        <th bgcolor="lightGrey">SAT</th>                    
      </tr>
      <tr>
        
        <td bgcolor="lightyellow">8-10</td>
        <td>-</td>
        <td>-</td>
        <td>-</td>
        <td>web</td>
        <td>-</td>
        <td>Public speak</td>
      </tr>
      <tr>
        
        <td bgcolor="lightyellow">10-12</td>
        <td>web</td>
        <td>-</td>
        <td>public speak</td>
        <td>-</td>
        <td>-</td>
        <td>c program</td>
      </tr>
      <tr>
        
        <td bgcolor="lightyellow">12-1</td>
        <td colspan="6" align="center" bgcolor="lightcyan" ><font color="chocolate">---------LUNCH !!--------<font></td>
      </tr>
      <tr>
        
        <td bgcolor="lightyellow">1-3</td>
        <td>c program</td>
        <td>c program</td>
        <td>Mentor meet</td>
        <td>public speak</td>
        <td>web</td>
        <td>Public speak</td>
      </tr>
      <tr>
        
        <td bgcolor="lightyellow">3-5</td>
        <td>-</td>
        <td>-</td>
        <td>web</td>
        <td>c program</td>
        <td>web</td>
        <td>c program</td>
      </tr>



    </table>
</body>
</html>
```

## OUTPUT

<img width="1007" height="702" alt="table" src="https://github.com/user-attachments/assets/4c263eb5-4120-4a9d-8973-3304996218c4" />


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
