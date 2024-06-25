# 🌐 Basic HTML and CSS Programs

Welcome to my web project! This repository contains two HTML files that demonstrate different aspects of web development using HTML and CSS.

## 📁 Project Files

### 1. `website.html`

#### Description:
This file showcases a basic HTML structure with paragraphs, buttons, and a link.

#### Content:
```html
<p>
    This is a paragraph of text.
</p>

<button>
    Hello
</button>

<a href="https://www.youtube.com/" target="_blank">
    Link to YouTube
</a>
```

### 2. `button.html`

#### Description:
`buttons.html` showcases different styled buttons using CSS classes.

#### Content:
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Styled Buttons</title>
    <style>
        /* CSS for Subscribe button */
        .subscribe-button {
            background-color: rgb(200, 0, 0);
            color: white;
            border: none;
            height: 35px;
            width: 105px;
            border-radius: 4px;
            cursor: pointer;
            margin-right: 8px;
        }

        /* CSS for Join button */
        .join-button {
            background-color: rgb(255, 255, 255);
            color: blue;
            border-color: blue;
            border-style: solid;
            border-width: 1px;
            height: 35px;
            width: 70px;
            border-radius: 4px;
            cursor: pointer;
        }

        /* CSS for Tweet button */
        .tweet-button {
            background-color: rgb(0, 132, 255);
            color: rgb(255, 255, 255);
            border: none;
            height: 35px;
            width: 75px;
            border-radius: 20px;
            cursor: pointer;
            font-weight: bold;
            font-size: 15px;
            margin-left: 8px;
        }
    </style>
</head>
<body>
    <!-- Subscribe Button -->
    <button class="subscribe-button">SUBSCRIBE</button>
    
    <!-- Join Button -->
    <button class="join-button">JOIN</button>
    
    <!-- Tweet Button -->
    <button class="tweet-button">Tweet</button>
</body>
</html>
```

### End Note
Feel free to customize the content and styling of this README file to better suit your project's specifics and preferences!
