# Ex03 Time Table
## Date: 14.3.2024

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
<html>
    <head>
        <title>My Time Table </title>
    </head>
    <body>
        <img src="logo.png" heigth="150" width="800">
        <table border="2" cellspacing="5" cellspacing="5" width="800" height="300">
            <caption>
                SLOT TIME TABLE -M.suren(23005055)
            </caption>
            <tr>
                <th bgcolor="#0094FA"> DAY/TIME</th>
                <th bgcolor="#0094FA">Monday</th>
                <th bgcolor="#0094FA">Tuesday</th>
                <th bgcolor="#0094FA"> Wednesday</th>
                <th bgcolor="#0094FA"> Thursday</th>
                <th bgcolor="#0094FA"> Friday</th>
                <th bgcolor="#0094FA"> Saturday</th>
            </tr>
            <tr>
                <td bgcolor="#000BFA">8-10</td>
                <td bgcolor="#FA007D">BEEE</td>
                <td bgcolor="#FA007D">Communicative English</td>
                <td bgcolor="#FA007D">Free Slot</td>
                <td bgcolor="#FA007D">Free Slot</td>
                <td bgcolor="#FA007D">Web Development</td>
                <td bgcolor="#FA007D">Free Slot</td>
            </tr>
            <tr>
                <td bgcolor="#000BFA">10-12</td>
                <td bgcolor="#FA007D">Free Slot</td>
                <td bgcolor="#FA007D">Free Slot</td>
                <td bgcolor="#FA007D">Advanced c</td>
                <td bgcolor="#FA007D">Communicative English</td>
                <td bgcolor="#FA007D">Computer Network</td>
                <td bgcolor="#FA007D">Free Slot</td>
            </tr>
            <tr>
                <td bgcolor="#000BFA">12-1</td>
                <td bgcolor="#FA007D">Lunch TIME</td>
                <td bgcolor="#FA007D">Mentor Meet</td>
                <td bgcolor="#FA007D">Lunch TIME</td>
                <td bgcolor="#FA007D">Lunch TIME</td>
                <td bgcolor="#FA007D">Lunch TIME</td>
                <td bgcolor="#FA007D">Lunch TIME</td>
            </tr>


            <tr>
                <td bgcolor="#000BFA">1-3</td>
                <td bgcolor="#FA007D">Computer Network</td>
                <td bgcolor="#FA007D">web Development</td>
                <td bgcolor="#FA007D">Creative Skill</td>
                <td bgcolor="#FA007D">web Development</td>
                <td bgcolor="#FA007D">Advanced C </td>
                <td bgcolor="#FA007D">BEEE</td>
             </tr>
             <tr>
                <td bgcolor="#000BFA">3-5</td>
                <td bgcolor="#FA007D">Free Slot</td>
                <td bgcolor="#FA007D">Free Slot</td>
                <td bgcolor="#FA007D">Free Slot</td>
                <td bgcolor="#FA007D">Free Slot</td>
                <td bgcolor="#FA007D">Free Slot</td>
                <td bgcolor="#FA007D">Free Slot</td>
             </tr>   
            </table>

            <table border="2" cellspacing="5" cellpading="5" width="600" height="50">
                <br>
                <br>
            
                <tr>
                    <th>S.NO</th>
                    <th >Subject Code</th>
                    <th><center>Subject Name</center></th>
                    
                </tr>
                <tr>
                    <th><center>1.</center></th>
                    <th>19AI305</th>
                    <th><center>Advanced C Programming</center></th>
                    
                </tr>
                <tr>
                    <th><center>2.</center></th>
                    <th>19CS406</th>
                    <th><center>Computer Network</center></th>
                    
                </tr>
                <tr>
                    <th><center>3.</center></th>
                    <th>19AI414</th>
                    <th><center>Fundamentals of Web Application Development</center></th>
                    
                </tr>
                <tr>
                    <th><center>4.</center></th>
                    <th>19EE305</th>
                    <th><center>BEEE</center></th>
                    
                </tr>
                <tr>
                    <th ><center>5.</center></th>
                    <th >19EN101</th>
                    <th><center>Communcative English</center></th>
                    
                </tr>
                <tr>
                    <th><center>6.</center></th>
                    <th>19EY702</th>
                    <th><center</center>Creative Skill</th>
                    
                </tr>
                <tr>
                    <th><center>7.</center></th>
                    <th>22HS102</th>
                    <th><center>Tamil and technology </center></th>
                </tr>
                <tr>
                    <th><center>8.</center></th>
                    <th>ECA-M</th>
                    <th><center>Mentor Meet  </center></th>
                </tr>
                </table>
    </body>
</html>
```


## OUTPUT
![alt text](<Screenshot (3).png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
