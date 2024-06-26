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

<style>

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

</style>

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

### 4. `box-model.html`

#### Description:
`box-model.html` this CSS box model describes the rectangular boxes generated for elements in the document tree.

#### Content:

<details>

```html
<style>

button
{
    padding-left: 10px;
    padding-right: 10px;
    padding-top: 7px;
    padding-bottom: 7px;
    vertical-align: top;
    font-weight: bold;
    cursor: pointer;
}
.subscribe-button
{
    color: white;
    background-color: red;
    border: none;
    border-radius: 3px;
    margin-right: 15px;
    transition: opacity 0.15s;

}

.subscribe-button:hover
{
    opacity: 0.75;
}

.subscribe-button:active
{
    opacity: 0.4;
}

.join-button
{
    color: rgb(0, 0, 177);
    background-color: white;
    padding-top: 6px;
    padding-bottom: 6px;
    border-width: 1px;
    border-radius: 3px;
    border-color: rgb(0, 0, 177);
    margin-right: 15px;
    border-style: solid;
    transition: background-color 0.15s, color 0.15s;
}

.join-button:hover
{
    color: white;
    background-color: rgb(0, 0, 177);
}

.tweet-button
{
    border-radius: 20px;
    border-width: 1px;
    color: white;
    background-color: rgb(10, 186, 255);
    border-width: 1px;
    border-color: rgb(10, 186, 255);
    transition: box-shadow 0.15s;
}

.tweet-button:hover
{
    box-shadow: 5px 5px 5px rgba(0, 0, 0, 0.15s);
}

</style>


<button class="subscribe-button"> 
    Subscribe 
</button>

<button class="join-button">
    Join
</button>

<button class="tweet-button">
    Tweet
</button>
```

</details>

### 5. `text-style.html`

#### Description:
`text-style.html` showcases different techniques and CSS properties for styling text in HTML.

#### Content:

<details>

```html
<style>

    p
    {
        font-family: Arial;
        margin-top: 0;
        margin-bottom: 0;
    }

    .head 
    {
        font-weight: bold;
        font-size: 18px;
        width: 300px;
        line-height: 25px;
        margin-bottom: 5px;
    }

    .stats
    {
        color: rgb(96, 96, 96);
        font-size: 14px;
        margin-top: 0;
        margin-bottom: 20px;
    }

    .user
    {
        font-size: 14px;
        color: rgb(32, 32, 32);
        margin-top: 0;
        margin-bottom: 0;
    }

    .description
    {
        font-size: 14px;
        width: 280px;
        color: rgb(32, 32, 32);
        line-height: 20px;
        margin-top: 20px;
        margin-bottom: 100px;
    }

    .tag
    {
        margin-bottom: 50px;
        font-size: 14px;
        background-color: rgb(277, 65, 64);
        color: white;
        text-align: center;
        padding-top: 18px;
        padding-bottom: 18px;
    }

    .shop-now
    {
        transition: underline 0.5s;
        cursor: pointer;
    }

    .shop-now:hover
    {
        text-decoration: underline;
    }

</style>

<p class ="head">
    Talking Tech and AI with Google CEO Sundar Pichai!
</p>

<p class ="stats">
    3.4M views &middot; 6 months ago
</p>

<p class = "user">
    Sahir Ahmed &#10004;
</p>

<p class = "description">
    Talking tech and AI on the heels of GOOGLE I/O. Also a daily driver phone reveal from Google's CEO. Shouout to Sundar!
</p>

<p class ="tag">
    Shop early for the best selection of holiday favourites. 
    <span class="shop-now">
        Shop Now &gt
    </span>
</p>

```

</details>



### End Note
Feel free to customize the content and styling of this README file to better suit your project's specifics and preferences!!!
