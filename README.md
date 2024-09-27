### Flask FoodGo in Flask with HTML, CSS, and JavaScript

```
Created by:
Name: Shreyas B R
```

---

This project demonstrates how to position images at the bottom left of a container using HTML and CSS. The container also includes a centered logo text.

---
## Features

- **Background Color**: The background color of the body is set to a bright red.
- **Container**: The container has a white border, rounded corners, and a gradient background.
- **Logo**: The logo text "FoodGo" is centered within the container.
- **Images**: Two images are positioned at the bottom left of the container.
---

## HTML Structure

The HTML file includes a `div` container with a logo and two images. The images are positioned using absolute positioning.

```html
<!DOCTYPE html>
<html>
<head>
    <title>Image at Bottom Left</title>
    <style>
        body {
            background-color: rgb(252, 9, 9);
            padding: 20px;
            display: flex;
            align-items: center;
            justify-content: center;
        }
        .container {
            border: 5px solid white;
            border-radius: 15px;
            background: linear-gradient(rgba(255, 255, 255, 0.566), red);
            width: 300px;
            text-align: center;
            justify-content: center;
            height: 600px;
            position: relative;
            display: flex;
            align-items: center;
            overflow: hidden;
        }
        .logo {
            color: white;
            font-size: 35px;
            font-family: cursive;
            text-align: center;
            position: absolute;
            top: 50%;
            left: 50%;
            transform: translate(-50%, -50%);
        }
        .image-bottom-left1 {
            position: absolute;
            bottom: -55px;
            left: -35px;
            width: 200px;
            height: 300px;
        }
        .image-bottom-left {
            position: absolute;
            bottom: -35px;
            left: 60px;
            width: 150px;
            height: 200px;
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="logo">FoodGo</div>
        <img src="b3.png" alt="Bottom Left Image" class="image-bottom-left1">
        <img src="b3.png" alt="Bottom Left Image" class="image-bottom-left">
    </div>
</body>
</html>
---
### Key Points:

- Flask allows you to integrate **HTML**, **CSS**, and **JavaScript** to build interactive and styled web applications.
- **CSS** is used to style the content, and **JavaScript** adds interactivity (like responding to button clicks).
- Flask serves these static files from the **static** folder while rendering the HTML from the **templates** folder.

---

**End of Document**
