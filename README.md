# Ex03 Time Table
## Date:19/11/2024

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
    <body>
        <img src="/static/logo.png" width="1500" height="200">
        <h2 align="center">SLOT TIME TABLE-M.D.DHANUSH(24900042)</h2>
    <Table border="2"  CELLPADDING="5" align="center">
       <tr style="background-color: blueviolet;">
            <th>time</th>
            <th>mon</th>
            <th>tue</th>
            <th>wed</th>
            <th>thu</th>
            <th>fri</th>
            <th>sat</th>
        </tr>
        <tr>
            <td style="background-color: blueviolet;">8-10 am</td>
            <td>FREE SLOT</td>
            <td>FREE SLOT</td>
            <td style="background-color: aqua;">statistics and numerical method</td>
            <td style="background-color: gold;">physics for quantum computing</td>
            <td>FREE SLOT</td>
            <td>FREE SLOT</td>
        </tr>
        <tr>
            <td style="background-color: blueviolet;">10-12 am</td>
            <td style="background-color: chocolate;">fundamental of web development</td>
            <td style="background-color: darkslateblue;">digital electronic</td>
            <td style="background-color: chocolate;">fundamental of web development</td>
            <td>FREE SLOT</td>
            <td style="background-color: darkslateblue;">digital electronic</td>
            <td style="background-color: gold;">physics for quantum computing</td>
        </tr>
        </tr>
             <td style="background-color: blueviolet;">12-1 pm</td>
               <td colspan="7" align="center">LUNCH TIME</td>
        </tr>
        <tr>
            <td style="background-color: blueviolet;">1-3 pm</td>
            <td>FREE SLOT</td>
            <td style="background-color: aqua;">statistics and numerical method</td>
            <td style="background-color: blue;">mentor meeting</td>
            <td style="background-color: chartreuse;">fundamental of c programming</td>
            <td style="background-color: chartreuse;">fundamental of c programming</td>
            <td style="background-color: chocolate;">fundamental of web development</td>
        </tr>
    </Table><br>
    <Table  border="2"  CELLPADDING="5" align="center">
        <th>S.NO.</th>
        <th>Subject code</th>
        <th>Subject Name</th>
        <tr>
            <td>1</td>
            <td>19AI304</td>
            <td>Fundamental of C programming</td>
        </tr>
        <tr>
            <td>2</td>
            <td>19AI414</td>
            <td>Fundamental of web application development</td>
        </tr>
        <tr>
            <td>3</td>
            <td>19EE404</td>
            <td>Digital electronic</td>
        </tr>
        <tr>
            <td>4</td>
            <td>19MA211</td>
            <td>statistics and numerical method</td>
        </tr>
        <tr>
            <td>5</td>
            <td>ECA-M-SCOFT</td>
            <td>Mentor meet</td>
        </tr>
        <tr>
            <td>6</td>
            <td>SH3214</td>
            <td>physics for quantum computing</td>
        </tr>
    </Table>
    </body>
</html>
```


## OUTPUT
![alt text](<Screenshot 2024-11-19 185857.png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
