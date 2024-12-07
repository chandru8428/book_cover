# Ex.06 Book Front Cover Page Design
# Date:04-12-2024
# AIM:
To design a book front cover page using HTML and CSS.

# DESIGN STEPS:
## Step 1:
Create a Django Admin project.

## Step 2:
Create an app in the Django interface.

## Step 3:
Create a folder named 'static' in the app folder.

## Step 4:
Create a new HTML file in the static folder.

## Step 5:
Write the HTML code with relevant CSS properties.

## Step 6:
Choose the appropriate style and color scheme.

## Step 7:
Insert the images in their appropriate places.

## Step 8:
Publish the website in the LocalHost.

# PROGRAM:
```
 <!DOCTYPE html>
<html lang="en">
     <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Book Cover</title>
    <style>
        body {
            margin: 0;
            padding: 0;
            height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;
            font-family: Arial, sans-serif;
             }
      .cover {
            width: 440px;
            height: 656px;
            border: 5px solid #000;
            border-radius: 10px;
            background-color: #fff;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            text-align: center;
            padding: 20px;
            background-image: url(hills.jpg);
        }
        .title {
            font-size: 36px;
            font-weight: bold;
            margin-bottom: 20px;
            font-family: cursive;
            color: #e3145c;
        }
        .subtitle {
            font-size: 18px;
            margin-bottom: 40px;
            color: c;
        }
        .author {
            font-size: 20px;
            font-style: italic;
            color: #f90546;
            margin-top: 300px;
            font-weight: bolder;
            font-weight: bolder;
            font-family: cursive;}
        .bottom-text {
            margin-top: auto;
            font-size: 24px;
            color: #fc0941;
            font-weight: bolder;
            font-family: cursive;
     }
        img{border-radius: 10px
            ;border-width: 3px
        }
        hr{
            color: #e3145c;
        }

        
        
        
 </style>
     </head>
     <body>
    <div class="cover">
       <header> <div class="title">The Great Adventure of Himalayas<hr></div>
        <div class="subtitle">A Journey Beyond</div> </header>
        <hr style="color: #fc0941;">
      <footer >  <div class="img"><img src="jhon.jpg" style="width: 80px;height: 80px ;border-width: 3px;padding-top: 10px;;border-radius: 50%;"></div> <div class="author"><hr width="400px">-By John Doe </div>
        <hr style="line-break: initial;color: #fc0941;">
        <div  class="bottom-text">Published by Fiction House </div></footer>
    </div>
     </body>
    </html>

```
# OUTPUT:
![image](https://github.com/user-attachments/assets/907a9a1b-d73b-4d42-bda6-719e5212d09a)

# RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
