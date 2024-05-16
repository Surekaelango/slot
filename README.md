# Ex03 Time Table
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
    <title>Timetable</title>
</head>
<body bgcolor="white">
    <img src="./logo.png" height="200" width="1080">
    <table border="3" cellspacing="4" cellpadding bgcolor="skyblue" height="300" width="1000" align="center">
    <caption ><b>MY TIMETABLE - SUREKA E (212221040167)</b></caption>
        <tr align="center" bgcolor="silver">
        <th>Day/Time</th>
        <th>8 - 10</th>
        <th>10 - 12</th>
        <th>1 - 3</th>
        <th>3 - 5</th>
        </tr>

        <tr align="center">
            <th align="center" bgcolor="silver">Mon</th>
            <th>-</th>
            <th>AI</th>
            <th>-</th>
            <th>FWAD</th>
        </tr>

        <tr>
            <th align="center" bgcolor="silver">Tue</th>
            <th>3D Printing</th>
            <th>-</th>
            <th>SE</th>
            <th>CD</th>
        </tr>

        <tr>
            <th align="center" bgcolor="silver">Wed</th>
            <th>FWAD</th>
            <th>-</th>
            <th>-</th>
            <th>3D Printing</th>
        </tr>

        <tr>
            <th align="center" bgcolor="silver">Thu</th>
            <th>-</th>
            <th>Creative Skills</th>
            <th>CD</th>
            <th>CAD</th>
        </tr>

        <tr>
            <th align="center" bgcolor="silver">Fri</th>
            <th>-</th>
            <th>SE</th>
            <th>-</th>
            <th>-</th>
        </tr>

        <tr>
            <th align="center" bgcolor="silver">Sat</th>
            <th>FWAD</th>
            <th>AI</th>
            <th>CAD</th>
            <th>-</th>
        </tr>
        
    </table>
    <br>

    <table border="3" cellspacing="4" cellpadding  height="300" width="1000" align="center" bgcolor="beige">
        <tr align="center">
            <th>S.No</th>
            <th>Subject Code</th>
            <th>Subject Name</th>
            </tr>

        <tr align="center">
            <th>1</th>
            <th>19AI414</th>
            <th>Fundamentals of Web Application Development</th>
            </tr>

        <tr align="center">
            <th>2</th>
            <th>19CS408</th>
            <th>Software Engineering (SE)</th>
            </tr>
            <tr align="center">
                <th>3</th>
                <th>19CS409</th>
                <th>Compiler Design (CD)</th>
                </tr>
                <tr align="center">
                    <th>4</th>
                    <th>19CS413</th>
                    <th>Artificial Intelligence (AI)</th>
                    </tr>
                    <tr align="center">
                        <th>5</th>
                        <th>19EY702</th>
                        <th>Creative Skills for Communication</th>
                        </tr>
                        <tr align="center">
                            <th>6</th>
                            <th>19ME505</th>
                            <th>Computer Aided Design (CAD)</th>
                            </tr>
                            <tr align="center">
                                <th>7</th>
                                <th>19ME533</th>
                                <th>3D Printing Processing</th>
                                </tr>
    </table>
</body>
</html>
```

## OUTPUT
<img width="960" alt="ex3" src="https://github.com/Surekaelango/slot/assets/127727904/4addd07f-bcf3-43b0-a179-616be963bbe1">


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
