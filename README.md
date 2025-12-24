# Ex.06 Book Front Cover Page Design
## Date:19/12/25

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
~~~
book.html
{% load static %}
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Book Cover</title>
    <style>
        body {
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            background: #f0f0f0;
            font-family: Arial, sans-serif;
        }

        .book {
            width: 300px;
            height: 450px;
            background: linear-gradient(135deg, #1e3c72, #2a5298);
            color: white;
            padding: 25px;
            box-shadow: 0 15px 30px rgba(0,0,0,0.4);
            border-radius: 10px;
            position: relative;
        }

        .title {
            font-size: 28px;
            font-weight: bold;
            margin-top: 40px;
        }

        .subtitle {
            font-size: 16px;
            margin-top: 10px;
            opacity: 0.9;
        }

        .author {
            position: absolute;
            bottom: 40px;
            font-size: 18px;
            font-weight: bold;
        }
        .photo {
            width: 120px;
        
            height: 120px;
            border-radius:50%;
            object-fit:cover;
            display: block;
            margin: 0 auto 8px auto;
        }

        .year {
            position: absolute;
            bottom: 15px;
            font-size: 14px;
            opacity: 0.8;
        }

        .line {
            width: 60px;
            height: 4px;
            background: white;
            margin-top: 15px;
            border-radius: 2px;
        }
    </style>
</head>
<body>

    <div class="book">
        <div class="title">THE POWER OF CODE</div>
        
        <div class="line"></div>
        <div class="subtitle">A Beginner's Guide to Programming</div>
        <img src="{% static 'coverapp/my_img.jpg' %}" class="photo">
        <div class="author">Tharun N</div>
        <div class="year">2025 Edition</div>
    </div>

</body>
</html>

<img width="1920" height="1080" alt="Screenshot (64)" src="https://github.com/user-attachments/assets/f1c83cb3-8b53-4888-8ca7-ba87f848873f" />
~~~

## OUTPUT:


## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
