# cover-page-design

## AIM:

To develop a website to display the cover page design of a book

## Design Steps:

### Step 1:

Write your own steps here.

### Step 2:

Create a static file directory and mention the changes in settings.

## step 3:

Make a new folder templates inside your app and create a html and map them using views and url.

## step 4:

Write down the code for book cover using HTML and CSS.

## step 5:

Add images and other contents using CSS record a screenshot of it.

## Code:

cover.html
```
<!DOCTYPE html>
html lang="en">
    <head>
         <meta name="viewport" 
         content="width=device-width, initial-scale=1.0">
         <style>

        .bookpage{
            width: 400px;
            height: 600px;
            background-color: #3d3a3a;
            color:white;
            margin-left: auto;
            margin-right: auto;
            padding: 20px;
            font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
            background-image: url(/static/images/back.jpeg);
            background-size: cover;
        }
            

        .toptext{
            color:white;

        }

        
        .tophr{
            width:140px;
        }
        .author{
            color: white;
            display: inline;
            position: relative;
            color:lightblue;
            top:190px;
            
            font-family:Georgia;
            font-size: medium;
        }
        .booktitle{
            font-family: 'Courier New', Courier, monospace;
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
        .publisher{
            font-size: medium;
            position: relative;
            top:155px;
            left:330px;
        }
        .edition{
            color:red;
            font-size: medium;
            font-family: Verdana;
            position:relative;
            top:85px;

        }
        .subtitle{
            font-family:Tahoma;
            font-size: large;
            position: relative;
            top:40px;
        }
        .photo{
            position: relative;
            top: 135px;
            left: 260px;
            width: 100px;
            height: 100px;
            background-size: cover;
        }
        </style>
        <title>Book Cover Page</title>
    </head>
    <body>
        <div class="bookpage">
            <div class="toptext">
                EXPERT INSIGHT
            </div>
            <div class="tophr">
                <hr style="color: red;">
            </div>
            <div class="booktitle">
                <h1>Responsive Web Design With HTML5 and CSS</h1></div>
            <div class="subtitle">
                Develop future-proof responsive websites using the latest HTML5 and CSS Techniques
            </div>
            <div class="photo">
                <img src="/static/images/my.jpeg" width="130" height="145" alt="">
            </div>
            <div class="id">
                <hr style="color: orange;">
            </div>
            <div class="author">
               <p><b>PAVITHRA.M</b></p>
            </div>
            <div class="publisher">
                Packt>
            </div>
            <div class="edition">
                <b>First Edition</b>
            </div>
            
        </div>
    </body>
</html>
```
## Output:

 CLIENT OUTPUT:

![EX061](https://github.com/22008686/cover-page-design/assets/118916413/0c78ab03-5a2a-4a79-8bfd-010784e2b13e)

SERVER OUTPUT:

![EX062](https://github.com/22008686/cover-page-design/assets/118916413/cdbae45c-0a75-4cb6-90f0-3afdd9979494)

HTML VALIDATOR:

![EX063](https://github.com/22008686/cover-page-design/assets/118916413/e76e272f-d218-4efd-81ce-6823accf183d)

## Result:

Thus a website to display the cover page design of a book was successfully created.
