# Ex02 Time Table
## Date:12.02.2026

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
<html>
<head>
    <title>Slot Time Table</title>
    <style>
        body {
            font-family: Arial, sans-serif;
        }

        h3 {
            text-align: center;
            margin: 5px;
        }

        img {
            display: block;
            margin: auto;
            width: 400px;   
        }

        table {
            border-collapse: collapse;
            margin: 15px auto;
            width: 90%;
        }

        th, td {
            border: 1px solid black;
            padding: 8px;
            text-align: center;
        }

        .head {
            background-color: yellow;
            font-weight: bold;
        }

        .slot {
            background-color: #00e5ee;
        }

        .sub-table {
            width: 80%;
        }

        .sub-table th {
            background-color: #e6e6e6;
        }
    </style>
</head>

<body>

    <!-- LOGO IMAGE -->
    <img src="/static/logo.png" alt="College Logo">

    <h3>SLOT TIME TABLE - IRFAN KHAN.N (212224230097)</h3>

    <!-- TIME TABLE -->
    <table>
        <tr class="head">
            <th>Day / Time</th>
            <th>Monday</th>
            <th>Tuesday</th>
            <th>Wednesday</th>
            <th>Thursday</th>
            <th>Friday</th>
            <th>Saturday</th>
        </tr>

        <tr class="slot">
            <th class="head">8 - 10</th>
            <td colspan="2">FREE SLOT</td>
            <td>FWAD</td>
            <td>FREE SLOT</td>
            <td>FWAD</td>
            <td>FREE SLOT</td>
        </tr>

        <tr class="slot">
            <th class="head">10 - 12</th>
            <td>FWAD</td>
            <td colspan="2">FREE SLOT</td>
            <td>FWAD</td>
            <td>FREE SLOT</td>
            <td>NN</td>
        </tr>

        <tr class="slot">
            <th class="head">12 - 1</th>
            <td colspan="6">LUNCH</td>
        </tr>

        <tr class="slot">
            <th class="head">1 - 3</th>
            <td>FREE SLOT</td>
            <td>FWAD</td>
            <td>MM</td>
            <td colspan="3">FREE SLOT</td>
        </tr>

        <tr class="slot">
            <th class="head">3 - 5</th>
            <td colspan="4">NN</td>
            <td colspan="2">FREE SLOT</td>
        </tr>

    </table>

    <!-- SUBJECT DETAILS -->
    <table class="sub-table">
        <tr>
            <th>S.No</th>
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
            <td>19AI411</td>
            <td>Neural Network (NN)</td>
        </tr>

        <tr>
            <td>2</td>
            <td>ECA-M</td>
            <td>Mentor Meet (MM)</td>
        </tr>

        
    </table>

</body>
</html>

```

## OUTPUT

![alt text](<Screenshot 2026-02-12 113514.png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
