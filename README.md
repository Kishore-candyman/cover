# Ex.06 Book Front Cover Page Design
## Date:08-12-2024

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
        <meta name="viewport"
        content="width=device-width, initial-scale=1.0">
        <style>
            .bookpage{
                width:400px;
                height: 600px;
                color:white;
                margin-left: auto;
                margin-right: auto;
                padding: 20px;
                font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
                background-image: url(exp6img.jpg);
                background-size: cover;
            }

            .insight{
                color:rgb(22, 183, 175);
            }

            .hrstyle{
                width:100px;
            }

            .author{
                display: inline;
                position: relative;
                color: white;
                top:190px;

                font-family: Georgia;
                font-size: medium;
            }

            .booktitle{

                font-family: 'Courier New', Courier, monospace;
                font-size: larger;
                text-align: center;
                position: relative;
                top: 30px;

            }

            .id{
                width: 400px;
                position: relative;
                top:180px;
            }

            .pub{
                font-size: medium;
                position: relative;
                top: 155px;
                left: 270px;
            }

            .ed{
                color: rgb(49, 160, 97);
                font-size: medium;
                font-family: Verdana;
                position: relative;
                top: 85px;
            }

            .subtitle{
                font-family: Tahoma;
                font-size: large;
                position: relative;
                top: 40px;
            }

            .mypic{
                position: relative;
                top: 135px;
                left: 260px;
                width: 100px;
                height: 100px;
                background-size: cover;

            }
        </style>
        <title> Book Cover Page</title>
    </head>
    <body>
        <div class="bookpage">
            <div class="insight">THE PHYSICS</div>
            <div class="hrstyle"> <hr style="color:yellow;"></div>
            <div class="booktitle"> <h1>The Universe in a Nutshell</h1></div>
            <div class="subtitle"> expantion on modern physics concepts with illustrations</div>
            <div class="mypic"> <img src="Stephen Hawking.png" width="130" height=" 145" alt=""></div>
            <div class="id"> <hr style="color: orange;"></div>
            <div class="author"><p><b>Stephen Hawking</b></p></div>
            <div class="pub">Bantam Spectra</div>
            <div class="ed"><b>Limited Edition</b></div>
        </div>
    </body>
</html>
```

## OUTPUT:
![alt text](<bookfront/bookapp/static/Screenshot 2024-12-08 090255.png>)


## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
