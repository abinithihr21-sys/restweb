# Ex.06 Restaurant Website
## Date:29-12-2025

## AIM:
To develop a static Restaurant website to display the food items and services provided by them.

## DESIGN STEPS:

### Step 1:
Requirement collection.

### Step 2:
Creating the layout using HTML and CSS.

### Step 3:
Updating the sample content.

### Step 4:
Choose the appropriate style and color scheme.

### Step 5:
Validate the layout in various browsers.

### Step 6:
Validate the HTML code.

### Step 7:
Publish the website in the given URL.

## PROGRAM:
```
admin.html

<html>
<head>
    <title>Administration Team</title>
    <link rel="stylesheet" href="admin.css">
</head>
<body>
<div class="container">
    <div class="box">
        <div class="item">
            <a href="home.html">HOME</a>
            <a href="menu.html">MENU</a>
            <a href="admin.html">ADMIN</a>
            <a href="contact.html">CONTACT</a>
        </div>
    </div>
    <h1 class="admin-title">ADMIN'S</h1>
    <div class="team-container">

        <div class="team-card">
            <img src="ceo.png">
            <h3>Abinithi.H</h3>
            <p>CEO</p>
        </div>

        <div class="team-card">
            <img src="pic3.jpg">
            <h3>Choi Hyun-wook</h3>
            <p>Marketing Manager</p>
        </div>

        <div class="team-card">
            <img src="pic 1.1.jpg">
            <h3>Kim Tae-ri</h3>
            <p>Operations Manager</p>
        </div>

        <div class="team-card">
            <img src="pic2.jpg">
            <h3>Nam Joo-hyuk</h3>
            <p>HR Manager</p>
        </div>

        <div class="team-card">
            <img src="pic6.jpg">
            <h3>Jeon Jungkook</h3>
            <p>Executive Chef</p>
        </div>

        <div class="team-card">
            <img src="pic.5.jpg">
            <h3>kim Ji-yeon</h3>
            <p>Customer Service Manager</p>
        </div>

        <div class="team-card">
            <img src="pic4.jpg">
            <h3>kim Irene</h3>
            <p>Managing Director</p>
        </div>

    </div>
</div>
<div class="footer">
    <p>&copy;ABINITHI(25009178)</p>
</body>
</html>

admin.css
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}
body {
    font-family: Georgia, serif;
}
.container {
    background: url("adminbg.jpg") no-repeat center center/cover;
    min-height: 100vh;
    width: 100%;
    padding: 30px 40px;
    border: 4px solid cyan;
    border-radius: 10px;
}
.box {
    display: flex;
    justify-content: flex-end;
    margin-bottom: 30px;
}
.item {
    background-color: #eef7fb;
    padding: 15px 30px;
}
.item a {
    margin: 0 18px;
    font-weight: bold;
    color: hotpink;
    text-decoration: underline;
}
.admin-title {
    font-size: 80px;
    color: greenyellow;
    letter-spacing: 6px;
    margin-bottom: 40px;
    text-align: center;
    text-decoration: underline;
}
.team-container {
    display: flex;
    justify-content: center;
    gap: 20px;
}
.team-card {
    background-color: blanchedalmond;
    width: 200px;
    padding: 15px;
    border-radius: 15px;
    text-align: center;
    box-shadow: 0 8px 18px rgba(0,0,0,0.35);
}
.team-card img {
    width: 140px;
    height: 140px;
    object-fit: cover;
    border-radius: 50%;
    margin-bottom: 15px;
}
.team-card h3 {
    font-size: 18px;
    margin-bottom: 5px;
}
.team-card p {
    font-size: 14px;
}
.footer {
    background-color: cyan;
    width: 100%;
    text-align: center;
    color: black;
    font-size: 14px;
    bottom: 0%;
}

home.html
<html>
<head>
    <title>Restaurant WebPage</title>
    <link href="home.css" rel="stylesheet">
</head>
<body>
<div class="container">
    <div class="box">
        <div class="item">
            <a href="home.html">HOME</a>
            <a href="menu.html">MENU</a>
            <a href="admin.html">ADMIN</a>
            <a href="contact.html">CONTACT</a>
        </div>
    </div>
    <div class="main">
        <h1>Welcome to our Restaurant</h1>
        <h1 class="brand">2125</h1>
        <h2>Experience the secret of Mexican cuisine</h2>
        <p>
            Discover the authentic flavors of mexico which offers a vibrant and flavorful dining experience inspired by the rich culture and traditions</p>
    </div>
    <div class="images">
        <img src="cook.jpg" alt="Image1">
        <img src="kitchen.jpg" alt="Image2">
        <img src="front.jpg" alt="Image3">
    </div>
</div>
<div class="footer">
    <h4>ABINITHI.H (25009178)</h4>
</div>
</body>
</html>

home.css
 {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}
body {
    font-family: Georgia, serif;
}
.container {
    background: url("back.jpg") no-repeat center center/cover;
    min-height: 100vh;
    width: 100%;
    padding: 30px 40px;
    border: 4px solid cyan;
    border-radius: 10px;
}
.box {
    display: flex;
    justify-content: flex-end;
    margin-bottom: 40px;
}
.item {
    background-color: #eef7fb;
    padding: 15px 30px;
}
.item a {
    margin: 0 18px;
    text-decoration: underline;
    font-weight: bold;
    color: hotpink;
    font-size: 16px;
}
.main {
    text-align: center;
    color: white;
    margin-bottom: 40px;
}
.main h1 {
    font-size: 50px;
}
.main .brand {
    font-size: 70px;
    color: red;
    letter-spacing: 4px;
}
.main h2 {
    margin: 15px 0;
    font-weight: normal;
}
.main p {
    width: 70%;
    margin: 20px auto;
    font-size: 18px;
    line-height: 1.6;
}
.images {
    display: flex;
    justify-content: center;
    gap: 20px;
    margin-bottom: 40px;
}
.images img {
    width: 220px;
    height: 160px;
    object-fit: cover;
    border: 5px solid white;
    border-radius: 10px;
}
.footer {
    background-color: cyan;
    width: 100%;
    text-align: center;
    color: black;
    font-size: 14px;
    bottom: 0;
}

menu.html
<html>
<head>
    <title>Menu Page</title>
    <link href="menu.css" rel="stylesheet">
</head>
<body>
<div class="container">
    <div class="box">
        <div class="item">
            <a href="home.html">HOME</a>
            <a href="menu.html">MENU</a>
            <a href="admin.html">ADMIN</a>
            <a href="contact.html">CONTACT</a>
        </div>
    </div>
    <div class="menu-container">
        <h1>MENU</h1>
        <div class="menu-items">

            <div class="menu-card">
                <img src="chessy nachos.jpg">
                <h3>Chessy nachos</h3>
                <p>Rs. 550</p>
            </div>

            <div class="menu-card">
                <img src="tacos.jpg">
                <h3>Fish tacos</h3>
                <p>Rs. 450</p>
            </div>

            <div class="menu-card">
                <img src="borito.jpg">
                <h3>Borito</h3>
                <p>Rs. 475</p>
            </div>

            <div class="menu-card">
                <img src="BBQ Chicken Quesadilla_ A Delicious Tex-Mex___.jpg">
                <h3>Quesadilla</h3>
                <p>Rs. 400</p>
            </div>

            <div class="menu-card">
                <img src="Beef and Cheese Empanadas Recipe for Family Dinners - Perfect Savory 450.jpg">
                <h3>Empanadas</h3>
                <p>Rs. 510</p>
            </div>

            <div class="menu-card">
                <img src="churro.jpg">
                <h3>churros</h3>
                <p>Rs. 310</p>
            </div>

            </div>
        </div>
    </div>

</div>
<div class="footer">
    <h4>ABINITHI.H(25009178)</h4>
</div>

</body>
</html>

menu.css
 {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: Georgia, serif;
}

.container {
    background: url("menbg.jpg") no-repeat center center/cover;
    min-height: 100vh;
    width: 100%;
    padding: 30px 40px;
    border: 4px solid cyan;
    border-radius: 10px;
}

.box {
    display: flex;
    justify-content: flex-end;
    margin-bottom: 30px;
}

.item {
    background-color: #eef7fb;
    padding: 15px 30px;
}

.item a {
    margin: 0 18px;
    font-weight: bold;
    color: hotpink;
    text-decoration: underline;
    font-size: 16px;
}

.menu-container {
    width: 100%;
}

.menu-container h1 {
    font-size: 80px;
    color: yellow;
    letter-spacing: 6px;
    margin-bottom: 35px;
    text-align: center;
    text-decoration: underline;
}

.menu-items {
    display: flex;
    gap: 20px;
    justify-content: center;   
    align-items: flex-start;
    flex-wrap: nowrap;
}

.menu-card {
    background-color: blanchedalmond;
    width: 180px;
    padding: 12px;
    border-radius: 15px;
    text-align: center;
    box-shadow: 0 8px 18px rgba(0, 0, 0, 0.35);
}

.menu-card img {
    width: 100%;
    height: 140px;
    object-fit: cover;
    border-radius: 12px;
    margin-bottom: 10px;
}

.menu-card h3 {
    font-size: 18px;
    font-weight: bold;
    margin-bottom: 5px;
}

.menu-card p {
    font-size: 14px;
    color: black;
}
@media (max-width: 1200px) {
    .menu-items {
        flex-wrap: wrap;
        justify-content: center;
    }
}
.footer {
    background-color: cyan;
    width: 100%;
    text-align: center;
    color: black;
    font-size: 14px;
    bottom: 0%;
}

contact.html
<html>
<head>
    <title>Contact Us</title>
    <link rel="stylesheet" href="contact.css">
</head>
<body>

<div class="container">
    <div class="box">
        <div class="item">
            <a href="home.html">HOME</a>
            <a href="menu.html">MENU</a>
            <a href="admin.html">ADMIN</a>
            <a href="contact.html">CONTACT</a>
        </div>
    </div>
    <div class="contact-content">
        <h1 class="contact-title">CONTACT</h1>
        <div class="contact-details">
            <h2>Come And Visit us at:</h2>
            <p>
                2125<br>
                42 Hangang-daero,Yongsan-gu<br>
                Seoul, 04389,South korea.<br>
                
            </p>
            <h2>Phone:</h2>
            <p>070-7078-6438</p>
            <h2>Email ID:</h2>
            <p>twentyonetwentyfiveoffcial@gmail.com</p>
        </div>
    </div>
</div>
<div class="footer">
    <p>&copy;ABINITHI.H (25009178)</p>
</div>
</body>
</html>

contact.css
{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}
body {
    font-family: Georgia, serif;
}
.container {
    background: url("contactbg.jpg") no-repeat center center/cover;
    min-height: 100vh;
    width: 100%;
    padding: 30px 40px;
    border: 4px solid cyan;
    border-radius: 10px;
}
.box {
    display: flex;
    justify-content: flex-end;
    margin-bottom: 40px;
}
.item {
    background-color: #eef7fb;
    padding: 15px 30px;
}
.item a {
    margin: 0 18px;
    font-weight: bold;
    color: hotpink;
    text-decoration: underline;
}
.contact-content {
    color: white;
    margin-top: 40px;
}
.contact-title {
    font-size: 90px;
    color: orange;
    letter-spacing: 6px;
    margin-bottom: 40px;
    text-align: center;
    text-decoration: underline;
}
.contact-details h2 {
    font-size: 26px;
    margin: 25px 0 10px;
    text-align: center;
}
.contact-details p {
    font-size: 18px;
    line-height: 1.6;
    text-align: center;
}
.footer {
    background-color: cyan;
    width: 100%;
    text-align: center;
    color: black;
    font-size: 14px;
    bottom: 0%;
}
```


## OUTPUT:

![alt text](<Screenshot 2025-12-29 081942.png>)
![alt text](<Screenshot 2025-12-29 082009.png>)
![alt text](<Screenshot 2025-12-29 082000.png>)
![alt text](<Screenshot 2025-12-29 082017.png>)
## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
