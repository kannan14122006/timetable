# Ex03 Time Table
# Date:27/09/2024
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
```<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>SLOT TIME TABLE</title>
    <style>
        body {
            display: flex;
            flex-direction: column;
            align-items: center;
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 20px;
        }
        img {
            width: 400px;
            margin-bottom: 20px;
        }
        h1 {
            text-align: center;
            margin-bottom: 20px;
        }
        table {
            border: 1px solid rgb(165, 28, 28);
            border-collapse: collapse;
            width: 100%;
            max-width: 1000px; /* Adjust this value as needed */
            margin-bottom: 20px;
        }
        th, td {
            border: 1px solid rgb(165, 28, 28);
            text-align: center;
            padding: 10px;
        }
        th {
            background-color: lightgreen;
            color: white;
        }
        td {
            background-color: whitesmoke;
        }
        img{
            height: 100px;
            width: 1000px;
        }
    </style>
</head>
<body>
    <img src="C:\Users\admin\Downloads\WhatsApp Image 2024-10-19 at 11.17.23 AM.jpeg">
    <h1>SLOT TIME TABLE - KANNAN R (24900979)</h1>

    <table>
        <tr>
            <th>Day/time</th>
            <th>Monday</th>
            <th>Tuesday</th>
            <th>Wednesday</th>
            <th>Thursday</th>
            <th>Friday</th>
            <th>Saturday</th>
        </tr>
        <tr>
            <th>8-10</th>
            <td>FREE SLOT</td>
            <td>BEEM</td>
            <td>CRYPTOCURRENCY</td>
            <td>FREE SLOT</td>
            <td>FREE SLOT</td>
            <td>MATHS</td>
        </tr>
        <tr>
            <th>10-12</th>
            <td>CRYPTOCURRENCY</td>
            <td>MATHS</td>
            <td>BEEM</td>
            <td>CARRIER DEVELOPMENT</td>
            <td colspan="2">WEB DEVELOPMENT</td>
        </tr>
        <tr>
            <th>12-1</th>
            <td colspan="6">LUNCH</td>
        </tr>
        <tr>
            <th>1-3</th>
            <td>WEB DEVELOPMENT</td>
            <td>C PROGRAMMING</td>
            <td>MENTOR MEET</td>
            <td>DIGITAL ELECTRONICS</td>
            <td>HUMAN VALUES</td>
            <td>C PROGRAMMING</td>
        </tr>
        <tr>
            <th>3-5</th>
            <td>FREE SLOT</td>
            <td>DIGITAL ELECTRONICS</td>
            <td colspan="4">FREE SLOT</td>
        </tr>
    </table>

    <table>
        <tr>
            <th>s.no</th>
            <th>subject code</th>
            <th>subject name</th>
        </tr>
        <tr>
            <td>1.</td>
            <td>19MA211</td>
            <td>Statistics and Numerical Methods</td>
        </tr>
        <tr>
            <td>2.</td>
            <td>19A1414</td>
            <td>Fundamental of Web Development</td>
        </tr>
        <tr>
            <td>3.</td>
            <td>19CS547</td>
            <td>Fundamental of Cryptocurrency</td>
        </tr>
        <tr>
            <td>4.</td>
            <td>19AI304</td>
            <td>Fundamental of C Programming</td>
        </tr>
        <tr>
            <td>5.</td>
            <td>19EE305</td>
            <td>Basic Electrical, Electronics and Measurement Engineering</td>
        </tr>
        <tr>
            <td>6.</td>
            <td>19EY708</td>
            <td>Career Development Skills</td>
        </tr>
        <tr>
            <td>7.</td>
            <td>19EE404</td>
            <td>Digital Electronics</td>
        </tr>
        <tr>
            <td>8.</td>
            <td>SH7801</td>
            <td>Human Values and Professional Ethics</td>
        </tr>
        <tr>
            <td>9.</td>
            <td>ECA-M-Scoft</td>
            <td>Mentor Meet</td>
        </tr>
    </table>

</body>
</html>
```

# OUTPUT
![Screenshot 2024-12-06 100413](https://github.com/user-attachments/assets/323ba811-872b-4014-b767-b20f92fbd0f4)

# RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
