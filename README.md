# Ex03 Time Table
## Date:20.11.2024

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
'''
<html>
    <head>
        <title>
           <b>SLOT TIMETABLE - MERIL GOLDLINA A (24007299)</b>
        </title>
    </head>
    <body>
        <center>
            <img src="/static/logo.png" height="100" width="630"><br><br>
        </center>
        <table border="2" cellpadding="10" bgcolor="AntiqueWhite" width="630">
            <tr> 
                <th bgcolor="silver">Day/Time</th>       
                <th bgcolor="white">8.00 - 10.00</th>
                <th bgcolor="silver">10.00 - 12.00</th>
                <th bgcolor="white">1.00 - 3.00</th>
                <th bgcolor="silver">3.00 - 5.00</th>
            </tr>
            <tr> 
                <th bgcolor="white">Monday</th>
                <td bgcolor="LightCoral" align="center">-</td>
                <td bgcolor="yellow" align="center">FWAD</td>
                <td bgcolor="pink" align="center">BEEE</td>
                <td bgcolor="LightCoral" align="center">-</td>
            </tr>
            <tr>
                <th bgcolor="silver">Tuesday</th>
                <td bgcolor="LightCoral" align="center">-</td>
                <td bgcolor="violet" align="center">Maths</td>
                <td bgcolor="NavajoWhite" align="center">Chemistry</td>
                <td bgcolor="LightCoral" align="center">-</td>
            </tr>
            <tr>
                <th bgcolor="white">Wednesday</th>
                <td bgcolor="LightCoral" align="center">-</td>
                <td bgcolor="yellow" align="center">FWAD</td>
                <td bgcolor="PaleGreen" align="center">Mentor Meet</td>
                <td bgcolor="LightCoral" align="center">-</td>
            </tr>
            <tr>
                <th bgcolor="silver">Thursday</th>
                <td bgcolor="LightCoral" align="center">-</td>
                <td bgcolor="LightSkyBlue" align="center">C Programming</td>
                <td bgcolor="pink" align="center">BEEE</td>
                <td bgcolor="LightCoral" align="center">-</td>
            </tr>
            <tr>
                <th bgcolor="white">Friday</th>
                <td bgcolor="NavajoWhite" align="center">Chemistry</td>
                <td bgcolor="gold" align="center">DE</td>
                <td bgcolor="LightSkyBlue" align="center">C Programming</td>
                <td bgcolor="LightCoral" align="center">-</td>
            </tr>
            <tr>
                <th bgcolor="silver">Saturday</th>
                <td bgcolor="gold" align="center">DE</td>
                <td bgcolor="violet" align="center">Maths</td>
                <td bgcolor="yellow" align="center">FWAD</td>
                <td bgcolor="LightCoral" align="center">-</td>
            </tr>
        </table>
        <br>
        <table border="2" cellpadding="10" bgcolor="white">
            <tr> 
                <th>S.No.</th>  
                <th align="center">Subject Code</th>     
                <th align="center">Subject Name</th>  
            </tr>   
            <tr>
                <th>1.</th>
                <td align="center">19AI414</td>
                <td>Fundamentals of Web Application Development(FWAD)</td>
            </tr> 
            <tr>
                <th>2.</th>
                <td align="center">19CY205</td>
                <td>Principles of Chemistry in Engineering(CHE)</td>
            </tr>   
            <tr>
                <th>3.</th>
                <td align="center">19EE404</td>
                <td>Digital Electronics(DE)</td>
            </tr>   
            <tr>
                <th>4.</th>
                <td align="center">19A1304</td>
                <td>Fundamentals of C Programming(C Progm)</td>
            </tr>   
            <tr>
                <th>5.</th>
                <td align="center">19A1305</td>
                <td>Basic Electrical, Electronics and Measurement Engineering(BEEE)</td>
            </tr>   
            <tr>
                <th>6.</th>
                <td align="center">19MA201</td>
                <td>Calculus and Matrix Algebra(Math)</td>
            </tr>   
        </table>
    </body>
</html>

'''

## OUTPUT
![alt text](<Screenshot 2024-11-20 203606.png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
