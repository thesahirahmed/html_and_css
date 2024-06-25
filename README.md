# 🌐 Basic HTML and CSS Programs

Welcome to my web project! This repository contains two HTML files that demonstrate different aspects of web development using HTML and CSS.

## 📁 Project Files

### 1. `website.html`

#### Description:
This file showcases a basic HTML structure with paragraphs, buttons, and a link.

#### Code:

<details>

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

</details>

### 2. `button.html`

#### Description:
`buttons.html` showcases different styled buttons using CSS classes.

#### Code:

<details>

```html

/* CSS for Subscribe button */
.subscribe-button 
    {
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
.join-button 
    {
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
.tweet-button 
    {
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

    <!-- Subscribe Button -->
    <button class="subscribe-button">SUBSCRIBE</button>
    
    <!-- Join Button -->
    <button class="join-button">JOIN</button>
    
    <!-- Tweet Button -->
    <button class="tweet-button">Tweet</button>

```

</details>


### 3. `hover_shadow_transition.html`

#### Description:
`hover_shadow_transition.html` file likely demonstrates how to achieve a hover effect, shadow and transition in HTML.

#### Content:
<details>

```html
<style>

    .subscribe-button
    {
        background-color:rgb(200, 0, 0);
        color:white;
        border: none;
        height: 35px;
        width: 105px;
        border-radius: 4px;
        cursor: pointer;
        margin-right: 8px;
        transition: opacity 0.15s;
    }

    .subscribe-button:hover
    {
        opacity: 0.75;
    }

    .suscribe-button:active
    {
        opacity: 0.4;
    }


    .join-button
    {
        background-color:rgb(255, 255, 255);
        color: rgb(41, 118, 211);
        border-color: rgb(41, 118, 211);
        border-style: solid;
        border-width: 1px;
        height: 35px;
        width: 70px;
        border-radius: 4px;
        cursor: pointer;
        transition: background-color 0.15s;
        transition: color 0.15s;
    }

    .join-button:hover
    {
        background-color: rgb(41, 118, 211);
        color:white;
    }

    .join button:active
    {
        opacity: 0.7;
    }


    .tweet-button
    {
        background-color:rgb(0, 132, 255);
        color: rgb(255, 255, 255);
        border: none;
        height: 35px;
        width: 75px;
        border-radius: 20px;
        cursor: pointer;
        font-weight: bold;
        font-size: 15;
        margin-left: 8px;
        transition: box-shadow 0.15s;
    }

    .tweet-button:hover
    {
        box-shadow: 5px 5px 10px rgba(0, 0, 0, 0.15);
    }


</style>

<button class="subscribe-button">
    SUBSCRIBE
</button>

<button class="join-button">
    JOIN
</button>

<button class="tweet-button">
    Tweet
</button>
```

</details>


### End Note
Feel free to customize the content and styling of this README file to better suit your project's specifics and preferences!
