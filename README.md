# Ex04 Time Table
## Date:17.11.2026

## AIM
To write a html webpage page to display your slot timetable.

## ALGORITHM
### STEP 1
Create a Django-admin Interface.

### STEP 2
Create an App inside the Django project.

### STEP 2
Create a static folder uder the created App and insert HTML code.

### STEP 3
Create a simple table using ```<table>``` tag in html with the relevant attributes.

### STEP 4
Add rows using ```<tr>``` tag.

### STEP 5
Add your course schedule using ```<td>``` tag.

### STEP 6
Execute the program using runserver command.

## PROGRAM
```
<!DOCTYPE html>
<html>
<head>
    <title>Slot Time Table</title>
</head>
<body bgcolor="#082F35" text="white">

    <center>
        <h1>SAVEETHA ENGINEERING COLLEGE</h1>
        <h2>SLOT TIME TABLE</h2>
    </center>

    <table border="1" align="center" cellpadding="15" cellspacing="0"
           bgcolor="#164E4A">
        <tr bgcolor="#0F766E">
            <th>TIME</th>
            <th>MONDAY</th>
            <th>TUESDAY</th>
            <th>WEDNESDAY</th>
            <th>THURSDAY</th>
            <th>FRIDAY</th>
            <th>SATURDAY</th>
        </tr>

        <tr>
            <th bgcolor="#14532D">8:00 AM - 9:29 AM</th>
            <td>PYT</td>
            <td>FREE SLOT</td>
            <td>FWAD</td>
            <td>PYT</td>
            <td>PYT</td>
            <td>MATHS</td>
        </tr>

        <tr>
            <th bgcolor="#14532D">9:45 AM - 11:15 AM</th>
            <td>FWAD</td>
            <td>FREE SLOT</td>
            <td>FREE SLOT</td>
            <td>GERMAN</td>
            <td>FREE SLOT</td>
            <td>GERMAN</td>
        </tr>

        <tr>
            <th bgcolor="#14532D">11:30 AM - 12:15 PM</th>
            <td>FREE SLOT</td>
            <td>FREE SLOT</td>
            <td>SCOFT-MM</td>
            <td>SCOFT-MM</td>
            <td>FREE SLOT</td>
            <td>SCOFT-MM</td>
        </tr>

        <tr>
            <th bgcolor="#14532D">12:15 PM - 12:59 PM</th>
            <td>FREE SLOT</td>
            <td>SCOFT-MM</td>
            <td>FREE SLOT</td>
            <td>FREE SLOT</td>
            <td>SCOFT-MM</td>
            <td>FREE SLOT</td>
        </tr>

        <tr>
            <th bgcolor="#14532D">1:15 PM - 2:45 PM</th>
            <td>FREE SLOT</td>
            <td>FWAD</td>
            <td>FREE SLOT</td>
            <td>MATHS</td>
            <td>FREE SLOT</td>
            <td>DE</td>
        </tr>

        <tr>
            <th bgcolor="#14532D">3:00 PM - 4:30 PM</th>
            <td>EDM</td>
            <td>FREE SLOT</td>
            <td>FREE SLOT</td>
            <td>DE</td>
            <td>EDM</td>
            <td>FREE SLOT</td>
        </tr>
    </table>

    <br>

    <center>
        <h2>SUBJECT DETAILS</h2>
    </center>

    <table border="1" align="center" cellpadding="10" cellspacing="0"
           bgcolor="#164E4A">
        <tr bgcolor="#0F766E">
            <th>S.NO</th>
            <th>SUBJECT CODE</th>
            <th>SUBJECT NAME</th>
        </tr>
        <tr>
            <td>1</td>
            <td>19AI414</td>
            <td>FUNDAMENTALS OF WEB APPLICATION DEVELOPMENT (FWAD)</td>
        </tr>
        <tr>
            <td>2</td>
            <td>19EN612</td>
            <td>GERMAN BASIC (GER)</td>
        </tr>
        <tr>
            <td>3</td>
            <td>19AI301</td>
            <td>PYTHON PROGRAMMING (PYT)</td>
        </tr>
        <tr>
            <td>4</td>
            <td>19CY205</td>
            <td>DIGITAL ELECTRONICS (DE)</td>
        </tr>
        <tr>
            <td>5</td>
            <td>19MA201</td>
            <td>CALCULAS AND MATRIX ALGEBRA (MATHS)</td>
        </tr>
        <tr>
            <td>6</td>
            <td>19AI302</td>
            <td>ENGINEERING DESIGN AND MODELLIIMG (EDM)</td>
        </tr>
    </table>

</body>
</html>

```

## OUTPUT
![alt text](<saravana/Xapp/Screenshot 2026-11-17 143502.png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
