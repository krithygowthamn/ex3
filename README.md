# Ex03 Time Table
## Date:08-04-2025
## Name: Gowtham N
## Reg no: 212222220013
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
    <meta name="viewport" content="width=device-width, initial-scale=0.2">
    <title>Weekly Timetable</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 30px;
        }
        table {
            margin: 0 auto;
            width: 80%;
            border-collapse: collapse;
        }
        th, td {
            border: 1px solid #e9dede;
            padding: 8px;

            text-align: center;
        }
        .free_slot {
            background-color: #bede4c;
            font-weight: bold;
        }
        th{
            background-color: #98c2f2; 
        }
        .time-col {
            background-color: #f2f2f2;
            font-weight: bold;
        }
        .break {
            background-color: #efb0b0;
        }
    </style>
</head>
<body>
    
    <img src="logo image.png" alt="Timetable Logo" style="display: block; margin: 0 auto; width: 250px;" />
    <h1 style="text-align: center;">Gowtham (212222220013) Weekly Routine</h1>
    <table>
        <thead>
            <tr>
                <th>Time</th>
                <th>Monday</th>
                <th>Tuesday</th>
                <th>Wednesday</th>
                <th>Thursday</th>
                <th>Friday</th>
                <th>Saturday</th>
                
            </tr>
        </thead>
        <tbody>
            <tr>
                <td class="time-col">8:00 - 10:00</td>
                <td class="free_slot"> Free slot</td>
                <td>19EC408</td>
                <td class="free_slot">Free slot</td>
                <td class="free_slot">Free slot</td>
                <td>19TD608</td>
                <td class="free_slot">Free slot</td>

            </tr>
            <tr>
                <td class="time-col">10:00 - 12:00</td>
                <td>19EE305</td>
                <td class="free_slot">Free slot</td>
                <td>19EC408</td>
                <td>19CS417</td>
                <td>19AI513</td>
                <td>19EC408</td>
            </tr>
            <tr class="break">
                <td class="time-col">12:00 - 1:00</td>
                <td colspan="6">Lunch Time</td>
            </tr>
            <tr>
                <td class="time-col">1:00 - 3:00</td>
                <td>19TD608</td>
                <td>19AI414</td>
                <td>ECA-M</td>
                <td>19AI513</td>
                <td>19AI414</td>
                <td>19CS417</td>
                
            </tr>
            <tr>
                <td class="time-col">3:00 - 5:00</td>
                <td class="free_slot">Free slot</td>
                <td class="free_slot">Free slot</td>
                <td>19EE305</td>
                <td>19CS504</td>
                <td>19EY710</td>
                <td>19CS504</td>
                
            </tr>
            
            
        </tbody>
    <table>
    
    <h2 style="text-align: center;"> course </h2>
    <table>
    <thead>
        <tr>
            <th>Course code</th>
            <th>Course Name</th>            
        </tr>
    </thead>
    <tr>
        <td class="time-col">19EE305</td>
        <td>Basic Electrical,Electronics and Measurement Engineering</td>
    </tr>
    <tr>
        <td class="time-col">19EC408</td>
        <td>Microprocessor and Microcontroller</td>
    </tr>
    <tr>
        <td class="time-col">19EY710</td>
        <td>Qunatity ablity phase 1</td>
    </tr>
    <tr>
        <td class="time-col">19AI414</td>
        <td>Fundamentals of web application development</td>
    </tr>
    <tr>
        <td class="time-col">19AI513</td>
        <td>Game programming</td>
    </tr>
    <tr>
        <td class="time-col">19TD608</td>
        <td>Prompt Engineering</td>
    </tr>
    <tr>
        <td class="time-col">19CS417</td>
        <td>Ethical Hacking </td>
    </tr>
    <tr>
        <td class="time-col">19CS504</td>
        <td>Software project management </td>
    </tr>
    <tr>
        <td class="time-col">ECA-M</td>
        <td>Mentor meet</td>
    </tr>

</table>
</body>
</html>
```

## OUTPUT
![image](https://github.com/user-attachments/assets/74906ae8-e384-4929-ab96-c210112cd161)


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
