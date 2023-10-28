# Portfolio

## Overview
This is a portfolio website to display some services of the company "Something something". 
This is currently under development. We will continue to add the features discussed in the readme to the website. 

You will notice that I am not a designer ／人◕ __ ◕人＼

## Components: 

### Header: 
Header is the component at the top of the website. It contains logo, name, and navigation bar. 
Here is the code for the header we have: 

```html
<header>
        <div class="logo-name">
            <a href="./index.html">
                <img src="https://nexted.com.au/wp-content/uploads/2023/07/CODR_Logo_Black-_-Green_RGB.png"
                alt="Coder Academy Logo">
            </a>
            <p class="name">
                <span class="coder-text">Coder</span>
                <span class="academy-text">Academy</span>
            </p>
        </div>

        <nav id="nav-items">
            <a href="./index.html">Home</a>
            <a href="./pages/about.html">About</a>
            <a href="./pages/contact.html">Contact</a>
        </nav>

</header>
```