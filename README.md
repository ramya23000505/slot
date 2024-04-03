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
  <html>
        <head>
                 <title> Web </title>
        </head>
        <body bgcolor="white" TEXT="black">
   <center>
        <img src="/static/images/saveetha logo.png"  height="100" width="1000" align="center" /> </center>
             
             <table border= "4" cellspacing="0px" cellpadding="10px" bgcolor="purple" align="center" >
             <CAPTION align=“top”> <b>SLOT TIME TABLE - RAMYA R(212223230169)</b> </CAPTION>
             <br>
             <br>
                  <tr> 
                  <th bgcolor="gray">   DAY/TIME </th>
                  <th bgcolor="plum">   MONDAY </th>
                  <th bgcolor="plum">   TUESDAY </th>
                  <th bgcolor="plum">   WEDNESDAY </th>
                  <th bgcolor="plum">   THURSDAY </th>
                  <th bgcolor="plum">   FRIDAY </th>
                  </tr>
                  <tr>
                   <th bgcolor="plum"> 8-10 </th>
                   <td> -- </td>
                   <td> C programming </td>
                     <td> -- </td>
                   <td > FWAD </td>
                   <td> FWAD </td>
                  </tr>
                  <tr>
                   <th bgcolor="plum"> 10-12 </th>
                   <td> -- </td>
                   <td> DL </td>
                   <td> DIP </td>
                   <td> DIP </td>
                   <td> DL </td>
                  </tr>
                  <tr>
                   <th bgcolor="plum"> 12-1 </th>
                    <td colspan="5" align="center">LUNCH TIME</td>
                  </tr>
                  <tr>
                   <th bgcolor="plum"> 1-3 </th>
                   <td> -- </td>
                   <td> -- </td>
                   <td> FWAD </td>
                   <td> -- </td>
                   <td> Physics/- </td>
                  </tr>
                  
                 
                 <tr>
                  <th bgcolor="plum"> 3-5 </th>
                  <td> Statictis </td>
                  <td> Physics </td>
                  <td> C Program </td> 
                  <td> -- </td> 
                  <td> Statictis </td>
                 </tr>
                 
              </table> <br>
               <table border= "4" cellspacing="0px" cellpadding="10px"  align="center" >
              <tr>
              <th> S.No </th>
                <th> SUBJECT CODE </th>
              <th> SUBJECT NAME </th>
              </tr>
              <tr> 
              <td> 1. </td>
              <td> 19AI414 </td>
              <td> Fundamental of web application and development </td>
              </tr>
              <tr>
              <td> 2. </td>
              <td> 19AI406 </td>
              <td> Digital Image Processing techniques </td>
              </tr>
              <tr>
              <td> 3. </td>
              <td> 19AI304 </td> 
              <td> Fundamental of C programming </td>
              </tr>
              <tr>
              <td> 4. </td>
              <td> 19PH214 </td>
              <td> Physics for quantum computing </td>
              </tr>
              <tr>
              <td> 5. </td>
              <td> 19AI413 </td>
              <td> Deep Learning and Applications </td>
              </tr>
              <tr>
              <td> 6. </td>
              <td> 19MA211 </td>
              <td> Statictis and Numerical Methods </td>
              </tr>
              </table>
                 
           </body>
   </html>
</html>

## OUTPUT
![Screenshot 2024-04-03 195407](https://github.com/ramya23000505/slot/assets/149370791/496f43c7-e9ca-4a3c-9424-4fb85c36d65d)
## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
