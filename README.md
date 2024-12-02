# Ex03 Time Table
# Date: 30/10/2024
# AIM
To write a html webpage page to display your slot timetable.

# ALGORITHM
## STEP 1
Create a Django-admin Interface.

## STEP 2
Create a static folder and inert HTML code.

## STEP 3
Create a simple table using <table> tag in html.

## STEP 4
Add header row using <th> tag.

## STEP 5
Add your timetable using <td> tag.

## STEP 6
Execute the program using runserver command.

# PROGRAM
'''
<html>
    <head>
        <title>
            Nanesh's time table
        </title><style>  
            table,th,td{
                border:1px solid black;
                border-collapse: collapse;
                font-size: 25px;
                text-align: center;
               background-color: orange;
               color: black;

            }
            td{

                padding:5px;
            }
            .no-border{
                border:none
            } 
            .vertical-align{
                writing-mode: horizontal-tb;
               
            } 
            .center {
                 display: block;
                margin-left: 15%;
            }         
            
           
        </style>
    </head>
    <body style="background-color: aquamarine;">
        {% load static %}
        <img src={% static 'images/saveethaa.png' %} width="65%" height="15%" class="center">

        
                    
        
        <h2 style="text-align: center;">Time Table  </h2>

        <table style="margin-left: 12%; " >
            
            <tr>
                <th>Day</th>
                <th>I<br>8.00am to 10.00am</th>
                <th>II<br>10.00am to 12.00pm</th>
                <th>  12.00pm to 1.00pm</th>
                <th>III<br> 1.00pm to 3.00pm</th>
                <th>VI<br> 3.00pm to 5.00pm</th>
            </tr>
            <tr>
                <td>Monday</td>
                <td>Free slot</td>
                <td>Web</td>
                <td class="no-border vertical-align" rowspan="6">L <br>U <br>N<br> C<br> H<br></td>
                <td>C prog</td>
                <td>Free slot</td>
            </tr>
            <tr>
                <td>Tuesday</td>
                <td>Free slot</td>
                <td>Digital</td>
             
                <td>English</td>
                <td>Free slot</td>
            </tr>
            <tr>
                <td>Wednesday</td>
                <td>C prog</td>
                <td>Career</td>
                
                <td>Mentor session</td>
                <td>Chemistry</td>
            </tr>
            <tr>
                <td>Thursday</td>
                <td> ML</td>
                <td>English</td>
                
                <td>Web</td>
                <td>Free slot</td>
            </tr>
            <tr>
                <td>Friday</td>
                <td>ML</td>
                <td>Free slot</td>
                
                <td>Digital</td>
                <td>Free slot</td>
            </tr>
            <tr>
                <td>Saturday</td>
                <td>Free slot</td>
                <td>Free slot</td>
                
                <td>Chemistry</td>
                <td>Web</td>
            </tr> 
        </table>
       <br/>
        <table style="margin-left: 28%;">
            <tr>
                <th>S.NO
                </th>
                <th> Code</th>
                <th>Name</th>
            </tr>
            <tr>
                <td>1</td>
                <td>
                    19CY205
                </td>
                <td>
                    Principle of Chemistry in Chemistry 
                </td>

            </tr>
            <tr>
                <td>
                    2
                </td>
                <td>
                    19AI414
                </td>
                <td>
                    Fundamentals of Web Application
                    Development
                </td>

            </tr>
            <tr>
                <td>3</td>
                <td>19EE404</td>
                <td>Digital Electronics</td>
            </tr>
            <tr>
                <td>4</td>
                <td>
                    19EN101
                </td>
                <td>
                    Communicative English
                </td>
            </tr>
            <tr>
                <td>
                    5
                </td>
                <td>19EY708</td>
                <td>Career Development Skills</td>

            </tr>
            <tr>
                <td>6</td>
                <td>19AI410</td>
                <td>Introduction to Machine Learning</td>
            </tr>
            <tr>
                <td>7</td>
                <td>
                    19AI304
                </td>
                <td>
                    Fundamentals of C programming
                </td>
            </tr>

            
        </table>
    
    </body>
</html>
```
# OUTPUT

![output03(web)](https://github.com/user-attachments/assets/c3e55842-34eb-4639-891e-6c033d9ad6ee)


# RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
