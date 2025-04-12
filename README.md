# Ex-03 Time Table
## Date: 12-04-2025

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
    <title>Document</title>
    <style>
        div
        {
            padding-top: 50px;
            padding-bottom: 50px;
            padding-left: 50px;
            padding-right: 50px;
        }
        </style>
</head>
<body>
    <center>
        <div><img src="logo.png" height="150" width="750" alt=""></div>
        <table border="3" bgcolor="cyan">
            <caption><b>SLOT TIME TABLE-NIRANJAN V (24900851)</b></caption>
            <tr style="background-color: yellow;">
                <td>Date/Time</td>
                <td>Monday</td>
                <td>Tuesday</td>
                <td>Wednesday</td>
                <td>Thursday</td>
                <td>Friday</td>
            </tr>
            <tr style="text-align: center;">
                <td style="background-color: yellow;">8-10</td>
                <td colspan="3">Free Slot</td>
                <td>PHY</td>
                <td>CHEM</td>
            </tr>
            <tr style="text-align: center;">
                <td style="background-color: yellow;">10-12</td>
                <td>GER</td>
                <td>Free Slot</td>
                <td>FWAD</td>
                <td>FWAD</td>
                <td>PHY</td>
            </tr>
            <tr style="text-align: center;">
                <td style="background-color: yellow;">12-1</td>
                <td colspan="5">LUNCH</td>
            </tr>
            <tr style="text-align: center;">
                <td style="background-color: yellow;">1-3</td>
                <td colspan="2">Free Slot</td>
                <td>MAT</td>
                <td>MATH</td>
                <td>SS</td>
            </tr>
            <tr style="text-align: center;">
                <td style="background-color: yellow;">3-5</td>
                <td colspan="2">Free Slot</td>
                <td>GER</td>
                <td>CHE</td>
                <td>FWAD</td>
            </tr>
        </table><br>
        <table border="3">
            <tr style="text-align: center;">
                <td><b>S. No.</b></td>
                <td><b>Subject Code</b></td>
                <td><b>Subject Name</b></td>
            </tr>
            <tr>
                <td style="text-align: center;">1.</td>
                <td style="text-align: center;">19AI414</td>
                <td>Fundamentals Of Web Application Development(FWAD)</td>
            </tr>
            <tr>
                <td style="text-align: center;">2.</td>
                <td style="text-align: center;">19EN612</td>
                <td>German Basic(GER)</td>
            </tr>
            <tr>
                <td style="text-align: center;">3.</td>
                <td style="text-align: center;">19PH206</td>
                <td>Physics For Information Technoloy(PHY)</td>
            </tr>
            <tr>
                <td style="text-align: center;">4.</td>
                <td style="text-align: center;">19CY205</td>
                <td>Principles Of Chemistry In Engineering(CHE)</td>
            </tr>
            <tr>
                <td style="text-align: center;">5.</td>
                <td style="text-align: center;">19MA201</td>
                <td>Calculus And Matrix Algebra(MAT)</td>
            </tr>
            <tr>
                <td style="text-align: center;">6.</td>
                <td style="text-align: center;">19EY701</td>
                <td>Soft Skills(SS)</td>
            </tr>
            

        </table>
    </center>
</body>
</html>
```

## OUTPUT

![Screenshot 2025-03-13 215422](https://github.com/user-attachments/assets/ead333a7-c314-4641-8a10-31fda892cbf3)


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
