# Ex.06 Book Front Cover Page Design
## Date:8/12/2024

## AIM:
To design a book front cover page using HTML and CSS.

## DESIGN STEPS:

### Step 1:
Create a Django Admin project.

### Step 2:
Create an app in the Django interface.

### Step 3:
Create a folder named 'static' in the app folder.

### Step 4:
Create a new HTML file in the static folder.

### Step 5:
Write the HTML code with relevant CSS properties.

### Step 6:
Choose the appropriate style and color scheme.

### Step 7:
Insert the images in their appropriate places.

### Step 8:
Publish the website in the LocalHost.

## PROGRAM:
```
<!DOCTYPE html>
<html>

<head>
    <title>Book cover</title>
    <style>
        .bookpage{

            width: 400px;
            height: 600px;
            color:black;
            margin-left: auto;
            margin-right: auto;
            padding: 20px;
            font-family: ' Arial, sans-serif';
            background-image:"Screenshot 2024-12-08 131323.png";
            background-size: cover;
        }
            
        
        .insight{
            color:rgb(76, 169, 169);
        
        }
        
        
        .hrstyle{
            width:100px;
        }
        .author{
        
            display: inline;
            position: relative;
            color:rgb(13, 125, 230);
            top:190px;
            
            font-family:Georgia;
            font-size: medium;
        }
        .booktitle{
            color:rgb(199, 22, 22);
            font-family: Roquen;
            font-size: larger;
            text-align: center;
            position: relative;
            top: 30px;
        
        }
        .id {
            width:400px;
            position: relative;
            top:180px;
            
        }
        .pub{
            color:rgb(118, 179, 5);
            font-size: medium;
            position: relative;
            top:155px;
            left:330px;
        }
        .ed{
            color:rgb(11, 104, 104);
            font-size: medium;
            font-family: Verdana;
            position:relative;
            top:85px;
        
        }
        .subtitle{
            color:rgb(16, 228, 228);
            font-family:unicorn;
            font-size: large;
            position: relative;
            top:40px;
        }
        .mypic{
            position: relative;
            top: 135px;
            left: 260px;
            width: 90px;
            height: 80px;
            background-size:contain;
        }
        body {
            background-image: url('Screenshot 2024-12-08 131323.png');
            background-size:contain; /* or contain */
            background-position:center;
            background-repeat: no-repeat;
        }
        </style>
        <title>Book Cover Page</title>
        </head>
        <body>
        <div class="bookpage">
            <div class="insight">
                LIFE
            </div>
            <div class="hrstyle">
                <hr style="color:rgb(16, 116, 230)">
            </div>
            <div class="booktitle">
                <h1 style="font-family: cursive; color:rgb(16, 13, 5);">ONE DAY LIFE WILL CHANGE</h1></div>
            <div class="subtitle" style="text-align: center;color: rgb(214, 29, 103);">
                 Secret of happy life
            </div>
            <div class="subtitle" style="color: rgb(17, 5, 62);text-align: center;">
                 Top seller of 2024
            </div>

            <div class="mypic">
                <img src="photo.jpg" width="120" height="100" >
            </div>
            <div class="id">
                <hr style="color:rgb(238, 17, 68)">
            </div>
            <div class="author">
               <p><b>PRIYADHARSHINI</b></p>
            </div>
            <div class="pub">
              ⭐⭐⭐⭐ 
            </div>
            <div class="ed">
                <b>SPECIAL EDITION</b>
            </div>
        </div>
        </body>
 </html>
 ```

## OUTPUT:
![alt text](<Screenshot 2024-12-08 133240.png>)

## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
