# Ex.06 Book Front Cover Page Design
## Date:2.11.2025

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
        <style>
            body 
            {
                margin: 0;
                padding: 0;
                background-color: rgb(147, 144, 144);
                
            }
            .container 
            {
                position: relative; 
                width: 400px; 
                height: 600px; 
                margin: 5px auto; 
                background-image: url('webbg.jpg');
                background-size: contain; 
               
            }
            .heading
             {
                position: absolute;
                top: 130px;
                left: 5px;
                text-align: center;
                letter-spacing: 3;
                font-family:Impact,'Haettenschweiler','Arial Narrow Bold', sans-serif;
                font-weight: 225;
                margin: 1;
                border-top: 6px rgb(19, 24, 21);
                border-bottom: 6px solid rgb(13, 14, 13);
                box-shadow: 0 4px 6px rgb(17, 18, 17);
                padding-bottom: 5px;
            }
            .sideheading
            {
                position: absolute;
                top: 50px;
                right: 30px;
                text-align: right;
                letter-spacing: 3;
                font-size: 8;
                margin: 0;

            }
            .authorimage
             {
                position: absolute; 
                bottom: 130px; 
                right: 40px; 
                width: 80px; 
            }
            .authorname
             {
                position: absolute;
                bottom: 100px;
                right: 45px; 
                font-size: 15px;
                font-family:'Gill Sans', 'Gill Sans MT','Calibri','Trebuchet MS','sans-serif';
                color: rgb(28, 26, 25);
                margin: 0;
            }
            .edition
            {
              position: absolute;
                bottom: 50px;
                left:20px;
                text-align: left;
                letter-spacing: 3;
                font-size:15;
                margin: 0;
            }
            .regno
            {
              position:absolute;
              bottom:5px;
              right: 50px;
              font-size: small;
              font-family:'Lucida Sans', 'Lucida Sans Regular', 'Lucida Grande', 'Lucida Sans Unicode','Geneva','Verdana','sans-serif';
              font-style: normal;
              color: rgb(207, 8, 8);
              margin: auto;
            }
        </style>
        <title>BOOK COVER</title>
    </head>
    <body>
        <div class="container">
            <h1 class="heading">WEB APPLICATION DEVELOPMENT</h1>
            <h2 class="authorname">Tharun Kumar V</h2>
            <h3 class="sideheading">Best Web sight</h3>
            <img src="c:\Users\admin\Downloads\WhatsApp Image 2025-10-29 at 10.44.55_7bc16ac5.jpg" class="authorimage">
            <h5 class="edition">2025 EDITION</h5>
        </div>
    </body>
</html>
```


## OUTPUT:

<img width="1279" height="1044" alt="Screenshot 2025-11-02 205521" src="https://github.com/user-attachments/assets/4b6c0e6e-7f8a-43f3-b628-e77def8d238a" />



## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
