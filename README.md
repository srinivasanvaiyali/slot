# Ex03 Time Table
## Date:25/03/2024

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
```c
<html>
    <head>
        <title>Slot Timetable</title>
    </head>
    <body>
        <center>
            {% load static %}
            <img src='logo.png'"height="100" width="500">
        </center>
        <br>
        <table align="center" width="540">
            <caption><b>SLOT TIMETABLE SRINIVASAN(212222043008)</b></caption>
            <table border="1px" cellpadding="6px"> 
            <tr align="center">
                <th bgcolor="brown">Day/Time</th>
                <th bgcolor="brown">Monday</th>
                <th bgcolor="brown">Tuesday</th>
                <th bgcolor="brown">Wednesday</th>
                <th bgcolor="brown">Thursday</th>
                <th bgcolor="brown">Friday</th>
            </tr>
            <tr align="center">
                <th bgcolor="red">8-10</th>
                <td bgcolor="yellow">FUNDAMENTALS OF WEB APPLICATION DEVLOPMENT</td>
                <td bgcolor="yellow">ETHICAL HACKING TECHNIQUES</td>
                <td bgcolor="yellow">INTRODUCTION TO IOT</td>
                <td bgcolor="pink">FREE SLOT</td>
                <td bgcolor="yellow">INTRODUCTION TO IOT</td>
            </tr>
            <tr align="centre">
                <th bgcolor="red">10-12</th>
                <td bgcolor="brown">FREE SLOT</td>
                <td bgcolor="green">COMPUTER NETWORKS</td>
                <td bgcolor="brown">FREE SLOT</td>
                <td bgcolor="green">COMPUTER NETWORKS</td>
                <td bgcolor="brown">FREE SLOT</td>
            </tr>
            <tr bgcolor="cyan" align="center">
                <th bgcolor="cyan">12-1</th>
                <td colspan="5" align="center"> L U N C H </td>
            <tr align="centre">
                <th bgcolor="blue">1-3</th>
                <td bgcolor="blue">FREE SLOT</td>
                <td bgcolor="blue">FREE SLOT</td>
                <td bgcolor="green">Programming in C</td>
                <td bgcolor="green">FUNDAMENTALS OF WEB APPLICATION DEVLOPMENT</td>
                <td bgcolor="green">FUNDAMENTALS OF WEB APPLICATION DEVLOPMENT</td>
            </tr>
            <tr bgcolor="pink" align="center">
                <th bgcolor="red">1-5</th>
                <td colspan="3" align="center"> FREE SLOT </td>
                <td bgcolor="brown">Soft Skills</td>
                <td bgcolor="pink">FREE SLOT</td>
            </tr>
        </table>
        <br>
        <table align="center" cellspacing="2" cellpadding="4" border="2">
            <tr align="center">
                <th>S.No.</th>
                <th>Subject Code</th>
                <th>Subject Name</th>
            </tr> 
            <tr>
                <td align="center">1.</td>
                <td align="center">19AI414</td>
                <td>FUNDAMENTALS OF WEB DEVLOPMENT (FWAD)</td>
            </tr>
            <tr>
                <td align="center">2.</td>
                <td align="center">19AM508</td>
                <td>INTRODUCTION TO IOT(IOT)</td>
            </tr>
            <tr>
                <td align="center">3.</td>
                <td align="center">19CS417</td>
                <td>ETHICAL HACKING TECHNIQUES(EHT)</td>
            </tr>
            <tr>
                <td align="center">4.</td>
                <td align="center">19CS406</td>
                <td>COMPUTER NETWORKS(CN)</td>
            </tr>
            <tr>
                <td align="center">5.</td>
                <td align="center">19CS302</td>
                <td>C PROGRAMMING(C)</td>
            </tr>
            <tr>
                <td align="center">6.</td>
                <td align="center">19EY701</td>
                <td>SOFT SKILLS (SS)</td>
            </tr>
        </table>
    </body>
</html>
```

## OUTPUT
![Screenshot (14)](https://github.com/srinivasanvaiyali/slot/assets/145117665/d886c0a5-81ef-49aa-9fce-f0da29dac8a9)


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
