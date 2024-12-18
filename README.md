# Ex.06 Book Front Cover Page Design
## Date: 3.12.2024

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
<html>
    <head>
        <style type="text/css">
            .container{
                position: relative;
                height:800px;
                width:700px;
                margin:auto;
               background-image: url(cover3.png);
                background-size: cover;
                align-content: center;

                
            }
            .topic{
                position: relative;
                letter-spacing: 4;
                left:80px ;
                bottom: 500px;
                font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
                font-weight: 2000;
                font-size:50px ;
                color: beige;

            }
       
           .name {
               position: absolute;
               letter-spacing: 4;
               bottom: 18px;
               left: 22px;
               text-align: right;
               font-family: Georgia, 'Times New Roman', Times, serif;
               font-weight: bolder;
               font-size: 30px;
               color: blanchedalmond;
               margin: 0%;
           }
           .image{
            position: absolute;
            bottom:90px ;
            right: 21px;
            width: 120px;
            border-radius: 10%;


           }
           .edition{
            position: relative;
            letter-spacing: 3;
            text-align: right;
            font-size: medium;
            font-weight: 8;
            margin: 0%;

           }
           .picture{
            position: absolute;
            top: 350px;;
            left: 250px;
            bottom:0px;
            transform: translateY(-50%);
            width:250px;
            height: 250px;
            
           }

           .publisher{
            position:absolute;
            letter-spacing: 3;
            bottom:5px;
            font-family: 'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode', Geneva, Verdana, sans-serif;
            text-align: left;
            left: 600px;
            font-size: 30px;
            font-weight: bolder;
            color: blanchedalmond;

           }

            .sub{
                position: relative;
                letter-spacing: 4;
                top: auto;
                left:80px;
               bottom: 65%;
                font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
                font-weight: 200;
                font-size:30px ;
                color: beige;
            }
        
        </style>
       
           
    </head>
    <body>
        <div class="container">
         <img src="cover3.png" />
        <h1 class="topic">AUTOMATION AND AI</h1>
        <h3 class="sub">Revolutionizing the Future of Work</h3>
        
        <h3 class="name">Indhu Priya.T</h3>
       <img src="profile.jpg" class="image"/>
       <img src="Screenshot 2024-12-03 092730.png" class="picture"/>
       <h1 class="publisher">SEC</h1>
        </div>
    </body>
 </html>
 ```


## OUTPUT:
![alt text](<admin/bookapp/static/Screenshot (38).png>)

## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
