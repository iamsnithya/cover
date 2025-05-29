# Ex.06 Book Front Cover Page Design
## Date:02/05/2025

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

    <!DOCTYPE html>
    <html lang="en">
    <head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Book Cover Display</title>
    <style>
        body {
            background-color: #2c3e50;
            margin: 0;
            padding: 0;
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
            font-family: Arial, Helvetica, sans-serif;
        }
        
        .container {
            width: 90%;
            max-width: 450px;
            margin: 20px auto;
        }
        
        .book-cover {
            background: linear-gradient(135deg, #021B79 0%, #0575E6 100%);
            border: 8px solid #e3d9b5;
            border-radius: 5px;
            box-shadow: 0 10px 30px rgba(0, 0, 0, 0.5);
            padding: 20px;
            position: relative;
            overflow: hidden;
        }
        
        .geometric-pattern {
            position: absolute;
            top: 0;
            left: 0;
            right: 0;
            bottom: 0;
            opacity: 0.1;
            z-index: 1;
            background-image: url('data:image/svg+xml;utf8,<svg xmlns="http://www.w3.org/2000/svg" width="100" height="100" viewBox="0 0 100 100"><rect x="0" y="0" width="100" height="100" fill="none" stroke="white" stroke-width="1"/><line x1="0" y1="0" x2="100" y2="100" stroke="white" stroke-width="1"/><line x1="100" y1="0" x2="0" y2="100" stroke="white" stroke-width="1"/></svg>');
            background-size: 50px 50px;
        }
        
        .title-section {
            background-color: #b71c1c;
            padding: 20px;
            margin-bottom: 20px;
            text-align: center;
            position: relative;
            z-index: 2;
            border-radius: 5px;
        }
        
        .title {
            color: white;
            font-size: 24px;
            font-weight: bold;
            margin: 0;
            padding: 0;
            letter-spacing: 1px;
        }
        
        .subtitle {
            color: #FFD700;
            font-size: 16px;
            margin: 15px 0 0 0;
            font-style: italic;
        }
        
        .author {
            color: white;
            font-size: 18px;
            margin: 20px 0 0 0;
            font-weight: normal;
            opacity: 0.8;
        }
        
        .content {
            position: relative;
            z-index: 2;
            text-align: center;
        }
        
        .profile-img {
            width: 180px;
            height: 180px;
            object-fit: cover;
            border-radius: 5px;
            margin: 10px auto;
            display: block;
            border: 3px solid white;
        }
        
        .topics {
            color: white;
            font-size: 14px;
            margin: 20px 0;
            text-align: left;
            padding-left: 30px;
            list-style-type: none;
        }
        
        .topics li {
            margin-bottom: 8px;
            position: relative;
        }
        
        .topics li:before {
            content: "»";
            position: absolute;
            left: -20px;
            color: #FFD700;
        }
        
        .tagline {
            font-style: italic;
            color: white;
            font-size: 14px;
            margin: 20px 0;
            padding: 10px;
            border-top: 1px solid rgba(255, 255, 255, 0.2);
            border-bottom: 1px solid rgba(255, 255, 255, 0.2);
        }
        
        .quote {
            font-style: italic;
            color: white;
            font-size: 14px;
            margin: 20px 0;
            text-align: center;
        }
        
        .quote-author {
            color: #FFD700;
            font-size: 14px;
            margin: 5px 0 0 0;
            text-align: right;
        }
        
        .banner {
            background-color: #b71c1c;
            color: white;
            padding: 5px 0;
            text-align: center;
            font-size: 14px;
            font-weight: bold;
            margin-top: 20px;
            border-radius: 3px;
        }
        
        .id-number {
            position: absolute;
            bottom: 10px;
            right: 10px;
            color: rgba(255, 255, 255, 0.3);
            font-size: 12px;
        }
    </style>
    </head>
    <body>
    <div class="container">
        <div class="book-cover">
            <div class="geometric-pattern"></div>
            
            <div class="title-section">
                <h1 class="title">MODERN WEB DEVELOPMENT</h1>
                <p class="subtitle">FROM FUNDAMENTALS TO ADVANCED TECHNIQUES</p>
            </div>
            
            <div class="content">
                <img src="https://ik.imagekit.io/0tydz7atd/WhatsApp%20Ima.jpg?updatedAt=1746163095734" alt="Author Photo" class="profile-img">
                
                <ul class="topics">
                    <li>Frontend Development with HTML, CSS & JavaScript</li>
                    <li>Backend Development with Node.js & Express</li>
                    <li>Full-Stack Applications & Responsive Design</li>
                </ul>
                
                <p class="tagline">A comprehensive guide for beginners and professionals alike</p>
                
                <p class="quote">"The web is not just about code, it's about creating experiences that connect people."</p>
                <p class="quote-author">- NITHYA</p>
                
                <div class="banner">BESTSELLER IN WEB DEVELOPMENT</div>
            </div>
            
            <div class="id-number">TDC-48392857</div>
        </div>
    </div>
    </body>
    </html>


## OUTPUT:
![Screenshot 2025-05-02 105134](https://github.com/user-attachments/assets/d87b9016-f695-4d73-86cf-f75bcddf74f8)


## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
