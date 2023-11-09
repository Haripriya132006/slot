# Ex03 Time Table
## Date: 2.11.2023

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
   <title>title</title>
       <body>
        <center>
            <img src="/static/logo.png" height="100" width="540" >
          <table border="6" cellspacing="4" cellpadding="4">
              <caption>MY TIME TABLE</caption>

                  <tr>
                    <th bgcolor="sky blue" align="center">day/time</th>
                    <th bgcolor="sky blue" align="center">8:9 am</th>
                    <th bgcolor="sky blue" align="center">9:10 am</th>
                    <th bgcolor="sky blue" align="center">10:11 am</th>
                    <th bgcolor="sky blue" align="center">11:12 am</th>
                    <th bgcolor="sky blue" align="center">12:1 pm</th>
                    <th bgcolor="sky blue" align="center">1:2 pm</th>
                    <th bgcolor="sky blue" align="center">2:3 pm</th>
                    <th bgcolor="sky blue" align="center">3:4 pm</th>
                    <th bgcolor="sky blue" align="center">4:5 pm</th>
                 </tr>

                  <tr>
                    <th bgcolor="sky blue" align="center" bgcolor="orange">MONDAY</th>
                    <td colspan="2" align="center" bgcolor="orange">soft skills</td> 
                    <td colspan="2" align="center" bgcolor="orange">python</td>
                    <td align="center" bgcolor="orange">LUNCH</td>
                    <td colspan="2" align="center" bgcolor="orange">physics</td>
                    <th colspan="2" align="center" bgcolor="orange">free</th>                   
                    </tr>

                  <tr>
                    <th bgcolor="sky blue" align="center" >TUESDAY</th>
                    <th colspan="4" align="center" bgcolor="orange">free</th>
                    <td align="center" bgcolor="orange">LUNCH</td>
                    <th colspan="4" align="center" bgcolor="orange">free</thh>
                    </tr>

                  <tr>
                    <th bgcolor="sky blue" align="center">WEDNESDAY</th>
                    <td colspan="2" align="center" bgcolor="orange">web application</td>
                    <td colspan="2" align="center" bgcolor="orange">computer architecture</td>                    
                    <td align="center" bgcolor="orange">LUNCH</td>
                    <td colspan="2" align="center" bgcolor="orange">maths</td>                    
                    <th colspan="2" align="center" bgcolor="orange">free</th>                    
                 </tr>

                  <tr>
                    <th bgcolor="sky blue" align="center">THURSDAY</th>
                    <td colspan="2" align="center" bgcolor="orange">maths</td>
                    <td colspan="2" align="center" bgcolor="orange">web application</td>                    
                    <td align="center" bgcolor="orange">LUNCH</td>
                    <td colspan="2" align="center" bgcolor="orange">python</td>                    
                    <th colspan="2" align="center" bgcolor="orange">free</th>                    
                 </tr>

                    <tr>
                    <th bgcolor="sky blue" align="center">FRIDAY</th>
                    <th colspan="2" align="center" bgcolor="orange">free</th>                    
                    <td align="center" bgcolor="orange">computer architecture</td>
                    <th align="center" bgcolor="orange">free</th>
                    <td align="center" bgcolor="orange">LUNCH</td>
                    <td colspan="2" align="center" bgcolor="orange">web application</td>                    
                    <td align="center" bgcolor="orange">physics</td>
                    <th align="center" bgcolor="orange">free</th>
                 </tr>

          </table>
          <table border="4" cellspacing="4" cellpadding="4">

<caption>SUBJECT AND THEIR RESPECTIVE SUBJECT CODES </caption>
                     <tr>
                    <th align="center" bgcolor="blue">S.NO</th>
                    <th align="center" bgcolor="blue">Subject Code</th>
                    <th align="center" bgcolor="blue">Subject Name</th>
                    </tr>

                     <tr>
                    <td align="center" bgcolor="blue">1.</td>
                    <td align="center" bgcolor="yellow">19AI414</td>
                    <td align="center" bgcolor="gold">Fundamentals Of Web Application Development (web application)</td>
                    </tr>

                     <tr>
                    <th align="center" bgcolor="blue">2.</th>
                    <td align="center" bgcolor="yellow">19AI301</th>
                    <td align="center" bgcolor="gold">Python Programming (python)</th>
                    </tr>

                     <tr>
                    <th align="center" bgcolor="blue">3.</th>
                    <td align="center" bgcolor="yellow">19CS305</th>
                    <td align="center" bgcolor="gold">Computer Architecture</th>
                    </tr>

                     <tr>
                    <th align="center" bgcolor=" blue">4.</th>
                    <td align="center" bgcolor="yellow">19EY701</th>
                    <td align="center" bgcolor="gold"> Soft Skills </th>
                    </tr>

                     <tr>
                    <th align="center" bgcolor="blue">5.</th>
                    <td align="center" bgcolor="yellow">19MA222</th>
                    <td align="center" bgcolor="gold">Probablity And Queing Models (Maths)</th>
                    </tr>

                     <tr>
                    <th align="center" bgcolor="blue">6.</th>
                    <td align="center" bgcolor="yellow">19PH214</th>
                    <td align="center" bgcolor="gold">Physics For Qantum Computing (physics)</th>
                    </tr>

          </table>    
      </body>
</html>
```


## OUTPUT
![Screenshot 2023-11-08 090528](https://github.com/Haripriya132006/slot/assets/144870747/594deedb-4b17-4542-b2b4-12d1bee8620a)
![Screenshot 2023-11-08 090554](https://github.com/Haripriya132006/slot/assets/144870747/803cec8a-cb08-439c-868f-eb5202bf6dfe)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
