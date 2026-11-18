# Ex02 Time Table
## Date:18-11-2026

## AIM
To write a html webpage page to display your slot timetable.

## ALGORITHM
### STEP 1
Create a Django-admin Interface.

### STEP 2
Create an App inside the Django project.

### STEP 2
Create a static folder uder the created App and insert HTML code.

### STEP 3
Create a simple table using ```<table>``` tag in html with the relevant attributes.

### STEP 4
Add rows using ```<tr>``` tag.

### STEP 5
Add your course schedule using ```<td>``` tag.

### STEP 6
Execute the program using runserver command.

## PROGRAM
slot.html

```
<html>
    <head>
        <title>Time Table</title>
        <img src="logo.png" style="display:block ; margin: auto; margin-left:auto; margin-right: auto ; width: 100%; max-width: 580px ; height: auto;"><br><br>
    </head>
    <body>
        
     <table align="center" border="1" cellspacing="2" cellpading="12" >
     
        <tr bgcolor="yellow" align="center">
            <td> Day/Time </td>
            <td> Monday </td>
            <td> Tuesday </td>
            <td> Wednesday </td>
            <td> Thursday </td>
            <td> Friday </td>
            <td> Saturday </td>
        </tr>

        <tr align="center">
            <td bgcolor="lightgreen"> 08:00-09:30 </td>
            <td> free slot</td>
            <td> Maths </td>
            <td> FWAD </td>
            <td> CDS </td>
            <td> Cyber </td>
            <td> Python </td>
        </tr>
        
        <tr align="center">
            <td bgcolor="lightgreen"> 09:30-11:15 </td>
            <td> FWAD </td>
            <td> Maths </td>
            <td> Free slot </td>
            <td> Python</td>
            <td> Free slot </td>
            <td> Cyber </td>
        </tr>

        <tr>
            <td bgcolor="lightgreen"> 11:30-12:15 </td>
            <td colspan="6" align="center"> Mentor Meet or Event </td>
        </tr>

         <tr>
            <td bgcolor="lightgreen"> 12:15-01.15 </td>
            <td colspan="6" align="center"> Lunch Break </td>
        </tr>

        <tr align="center">
            <td bgcolor="lightgreen"> 01.15-02.44 </td>
            <td> Free Slot </td>
            <td> FWAD </td>
            <td> Free Slot </td>
            <td> Free Slot  </td>
            <td> Free slot </td>
            <td> Digital </td>
        </tr>

        <tr align="center">
            <td bgcolor="lightgreen"> 03:00-04:30 </td>
            <td> Free Slot  </td>
            <td> Python </td>
            <td> Free Slot  </td>
            <td> Digital</td>
            <td> EDM</td>
            <td> EDM </td>
        </tr>

     </table><br><br>
     <table align="center" border="1" cellspacing="2" cellpading="12">
      <caption align="center" style="font-family:'Times New Roman', Times, serif; font: size 45px;"><b>SLOT TIME TABLE - SHAMINI B [26016698]</b></caption>

     <tr bgcolor="lavender" align="center">
        <td> S.No </td>
        <td> Subject Code </td>
        <td> Subject Name </td>
     </tr>
     <tr align="center">
        <td  bgcolor="pink"> 1. </td>
        <td bgcolor="pink"> 19AI414 </td>
        <td> Fundamentals of Web Application Development(FWAD) </td>
     </tr>
     <tr align="center">
        <td  bgcolor="pink"> 2. </td>
        <td bgcolor="pink"> 19AI301 </td>
        <td> Python Programming(Python) </td>
     <tr align="center">
        <td bgcolor="pink"> 3. </td>
        <td  bgcolor="pink"> 19AI302 </td>
        <td> Engineering Design And Modelling(EDM) </td>
     <tr align="center">
        <td  bgcolor="pink"> 4. </td>
        <td  bgcolor="pink"> 19MA201 </td>
        <td> Calculus and Matrix Algebra(calculus)</td>
     <tr align="center">
        <td  bgcolor="pink"> 6. </td>
        <td  bgcolor="pink"> 19EE404 </td>
        <td> Digital Electronics(Digital)</td>
     <tr align="center">
        <td  bgcolor="pink" > 7. </td>
        <td  bgcolor="pink" > 19CS418</td>
        <td> Cyber Law And Compliance(Cyber) </td>
     </tr>
     <tr align="center">
        <td  bgcolor="pink"> 8. </td>
        <td  bgcolor="pink" > 19EY708 </td>
        <td> Career Development And Skills(CDS) </td>
      
     </table>
    </body>
</html>
```


## OUTPUT
webpage 

![alt text](<Screenshot (143).png>)
server side 
![alt text](<Screenshot (144).png>)
## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
