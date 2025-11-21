**# Ex.07 Restuarant Website
## Date:21.11.2025

## AIM:
To develop a static Resturant website to display the menu and services provided by the resturant.

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
```html
home.html



<html>
<head>
    <title>MOONLIGHT TWINS</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: white;
        }
        header {
            background-color: wheat;
            text-align: center;
            padding: 20px;
        }
        header img {
            width: 50px;
        }
        nav {
            background-color: grey;
            color: white;
            display: flex;
            justify-content: center;
            padding: 10px 0;
        }
        nav a {
            text-decoration: none;
            color: white;
            margin: 0 15px;
        }
        .banner {
            text-align: right;
            background-image: url('banner.png');
            background-size: cover;
            background-position: center;
            color: white;
            padding: 50px;
        }
        .banner h2 {
            margin: 0;
        }
        .banner p {
            margin-top: 10px;
        }
        .sections {
            display: flex;
            justify-content: space-around;
            padding: 20px;
            gap: 10px;
        }
        .section {
            background-color: wheat;
            padding: 15px;
            border-radius: 10px;
            text-align: center;
            width: 30%;
        }
        .section img {
            width: 100%;
            border-radius: 10px;
        }
        footer {
            text-align: center;
            background-color: white;
            padding: 10px;
            margin-top: 20px;
        }
        footer a {
            text-decoration: none;
            color: blanchedalmond;
        }
    </style>
</head>
<body>

<header>
     
    <h2>MOONLIGHT TWINS</h2>
</header>

<nav>
    <a href="home.html">Home</a>
    <a href="menu.html">Menu</a>
    <a href="chef.html">Chef</a>
    <a href="contact.html">Contact Us</a>
</nav>

<img src="Moonlight.jpg" alt="background-image" style="width:100%;height:100vh;object-fit:cover;">"
</body>
</html>

menu.html



<html>
<head>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: lightgray;
        }
        nav {
            background-color: darkslategray;
            color: white;
            display: flex;
            justify-content: center;
            padding: 10px 0;
        }
        nav a {
            text-decoration: none;
            color: white;
            margin: 0 15px;
        }
        header {
            text-align: center;
            background-color: lightsteelblue;
            padding: 20px;
        }
        .menu-section {
            padding: 30px;
            max-width: 1000px;
            margin: auto;
        }
        .menu-title {
            text-align: center;
            color: darkslateblue;
            margin-bottom: 20px;
        }
        .menu-items {
            display: flex;
            flex-wrap: wrap;
            gap: 20px;
            justify-content: center;
        }
        .menu-item {
            background-color: white;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
            text-align: center;
            padding: 15px;
            width: 250px;
        }
        .menu-item img {
            width: 100%;
            border-radius: 10px;
            margin-bottom: 10px;
        }
        .menu-item h3 {
            color: darkslateblue;
            margin: 10px 0;
        }
        .menu-item p {
            color: gray;
            font-size: 14px;
        }
        .menu-item span {
            display: block;
            font-size: 18px;
            font-weight: bold;
            color: darkslategray;
            margin-top: 10px;
        }
    </style>
</head>
<body>

<nav>
    <a href="home.html">Home</a>
    <a href="menu.html">Menu</a>
    <a href="chef.html">Chef</a>
    <a href="contact.html">Contact Us</a>
</nav>

<header>
    <h1>Our Menu</h1>
</header>

    <h2 class="menu-title">Explore Our Delicious Dishes</h2>
    <div class="menu-items">
        <div class="menu-item">
            <img src="burger.png" alt="Dish 1">
            <h3>Classic Burger</h3>
            <p>A juicy beef patty with fresh lettuce, tomatoes, and cheese in a sesame seed bun.</p>
            <span>Rs. 220</span>
        </div>
        <div class="menu-item">
            <img src="kimbap.png" alt="Dish 2">
            <h3> Kimbap </h3>
            <p>Made from cooked rice and various fillings like vegetables, meat, or egg, rolled in dried seaweed (gim) and then sliced into bite-sized pieces.</p>
        <span>Rs. 290</span>
        </div>
        <div class="menu-item">
            <img src="ramen.png" alt="Dish 3">
            <h3>Korean Ramen</h3>
            <p>Noodle dish consisting of wheat noodles served in a hot broth, often topped with ingredients like sliced pork, seaweed, and scallions. .</p>
            <span>Rs. 260</span>
        </div>
        
    </div>
</div>

</body>
</html>

chef.html



<html>
<head>
    <title>CHEFS</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: lightgray;
        }
        nav {
            background-color: darkslategray;
            color: white;
            display: flex;
            justify-content: center;
            padding: 10px 0;
        }
        nav a {
            text-decoration: none;
            color: white;
            margin: 0 15px;
        }
        header {
            text-align: center;
            background-color: lightsteelblue;
            padding: 20px;
        }
        .admin-section {
            padding: 30px;
            max-width: 800px;
            margin: auto;
            background-color: white;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
        }
        .admin-section h2 {
            text-align: center;
            color: darkslateblue;
            margin-bottom: 20px;
        }
        .admin-team {
            display: flex;
            flex-wrap: wrap;
            gap: 20px;
            justify-content: center;
        }
        .team-member {
            background-color: lightblue;
            border-radius: 10px;
            padding: 15px;
            text-align: center;
            width: 200px;
        }
        .team-member img {
            width: 100%;
            border-radius: 10px;
            margin-bottom: 10px;
        }
        .admin-login {
            margin-top: 30px;
            text-align: center;
        }
        .admin-login input {
            padding: 10px;
            margin: 10px 5px;
            border: 1px solid gray;
            border-radius: 5px;
            font-size: 14px;
        }
        .admin-login button {
            padding: 10px 20px;
            background-color: darkslateblue;
            color: white;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }
        .admin-login button:hover {
            background-color: slateblue;
        }
    </style>
</head>
<body>

<nav>
    <a href="Home.html">Home</a>
    <a href="menu.html">Menu</a>
    <a href="chef.html">Chef</a>
    <a href="contact.html">Contact Us</a>
</nav>

<header>
    <h1>MOONLIGHT TWINS CHEFS</h1>
</header>

<div class="admin-section">
    <h2>Meet the Team</h2>
    <div class="admin-team">
        <div class="team-member">
            <h3>John Doe</h3>
            <p>Manager</p>
        </div>
        <div class="team-member">
            <h3>Jane Smith</h3>
            <p>Assistant Manager</p>
        </div>
        <div class="team-member">
            <h3>Emily Johnson</h3>
            <p>HR Head</p>
        </div>
    </div>

    <div class="admin-login">
        <h2>Admin Login</h2>
        <form>
            <input type="text" placeholder="Username" required>
            <input type="password" placeholder="Password" required>
            <button type="submit">Login</button>
        </form>
    </div>
</div>

</body>
</html>

contact.html


<html>
<head>
    <title>Contact Us</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: white;
        }
        nav {
            background-color: grey;
            color: white;
            display: flex;
            justify-content: center;
            padding: 10px 0;
        }
        nav a {
            text-decoration: none;
            color: white;
            margin: 0 15px;
        }
        header {
            text-align: center;
            background-color: white;
            padding: 20px;
        }
        .contact-section {
            padding: 30px;
            max-width: 600px;
            margin: auto;
            background: white;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        .contact-section h2 {
            text-align: center;
            margin-bottom: 20px;
        }
        .contact-section form {
            display: flex;
            flex-direction: column;
            gap: 15px;
        }
        .contact-section input, .contact-section textarea, .contact-section button {
            padding: 10px;
            font-size: 16px;
            border: 1px solid whitesmoke;
            border-radius: 5px;
        }
        .contact-section textarea {
            resize: none;
            height: 100px;
        }
        .contact-section button {
            background-color: #4a4a4a;
            color: white;
            cursor: pointer;
        }
    </style>
</head>
<body>

<nav>
    <a href="home.html">Home</a>
    <a href="menu.html">Menu</a>
    <a href="Chef.html">Chef</a>
    <a href="contact.html">Contact Us</a>
</nav>

<header>
    <h1>Contact Us</h1>
</header>

<div class="contact-section">
    <h2>We'd Love to Hear from You!</h2>
    <form>
        <input type="text" name="name" placeholder="Your Full Name" required>
        <input type="email" name="email" placeholder="Your Email" required>
        <input type="tel" name="phone" placeholder="Your Phone Number (optional)">
        <textarea name="message" placeholder="Your Message..." required></textarea>
        <button type="submit">Send Message</button>
    </form>
</div>

</body>
</html>


```

## OUTPUT:
![alt text](<Screenshot 2025-10-31 094051.png>)
![alt text](<Screenshot 2025-10-31 094222.png>)
![alt text](<Screenshot 2025-10-31 094338.png>)
![alt text](<Screenshot 2025-10-31 094408.png>)

## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
**# Ex.07 Restuarant Website
## Date:
## AIM:
To develop a static Resturant website to display the menu and services provided by the resturant.

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
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Play Bae Cafe - Colorful Fusion Cuisine</title>
    <style>
        /* Reset and base styles */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Arial', sans-serif;
            line-height: 1.6;
            color: #333;
            background: linear-gradient(45deg, #ff6b6b, #feca57, #48dbfb, #0abde3, #a55eea, #ff9ff3);
            background-attachment: fixed;
            min-height: 100vh;
        }

        /* Header and Navigation */
        header {
            background: rgba(255, 255, 255, 0.9);
            position: fixed;
            width: 100%;
            top: 0;
            z-index: 100;
            box-shadow: 0 2px 10px rgba(0,0,0,0.1);
        }

        nav {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 1rem 2rem;
        }

        .logo {
            font-size: 2rem;
            font-weight: bold;
            background: linear-gradient(45deg, #ff6b6b, #feca57);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
        }

        nav ul {
            list-style: none;
            display: flex;
        }

        nav ul li {
            margin-left: 2rem;
        }

        nav ul li a {
            text-decoration: none;
            color: #333;
            font-weight: bold;
            transition: color 0.3s;
        }

        nav ul li a:hover {
            color: #ff6b6b;
        }

        /* Hero Section */
        .hero {
            text-align: center;
            padding: 10rem 2rem 5rem;
            position: relative;
        }

        .hero-img {
            width: 100%;
            height: 400px;
            object-fit: cover;
            border-radius: 10px;
            box-shadow: 0 4px 20px rgba(0,0,0,0.2);
            margin-bottom: 2rem;
        }

        .hero h1 {
            font-size: 3rem;
            margin-bottom: 1rem;
            animation: rainbow 3s infinite;
        }

        @keyframes rainbow {
            0% { color: red; }
            16% { color: orange; }
            33% { color: yellow; }
            50% { color: lightgreen; }
            66% { color: rgb(0, 171, 251); }
            83% { color: rgb(255, 15, 255); }
            100% { color: rgb(255, 0, 200); }
        }

        .btn {
            display: inline-block;
            padding: 0.8rem 2rem;
            background: linear-gradient(45deg, #ff6b6b, #feca57);
            color: white;
            text-decoration: none;
            border-radius: 50px;
            transition: transform 0.3s;
        }

        .btn:hover {
            transform: scale(1.1);
        }

        /* Menu Section */
        #menu {
            padding: 4rem 2rem;
            background: rgba(255, 255, 255, 0.9);
            text-align: center;
        }

        .menu-items {
            display: flex;
            justify-content: space-around;
            flex-wrap: wrap;
            margin-top: 2rem;
        }
        .item {
            padding: 2rem;
            margin: 1rem;
            border-radius: 10px;
            width: 300px;
            transition: transform 0.3s;
        }

        
        .item:hover {
            transform: translateY(-10px);
        }

        .item img {
            width: 500%;
            height: 900px;
            object-fit: cover;
            border-radius: 5px;
            margin-bottom: 1rem;
        }

        .price {
            font-weight: bold;
            color: #ff6b6b;
        }

        /* About and Contact Sections */
        #about, #contact {
            padding: 4rem 2rem;
            background: rgba(255, 255, 255, 0.9);
            text-align: center;
        }

        /* Footer */
        footer {
            background: #333;
            color: white;
            text-align: center;
            padding: 1rem;
        }

        /* Responsive Design */
        @media (max-width: 768px) {
            nav ul {
                flex-direction: column;
                margin-top: 1rem;
            }
            nav ul li {
                margin: 0.5rem 0;
            }
            .menu-items {
                flex-direction: column;
                align-items: center;
            }
        }
    </style>
</head>
<body>
    <header>
        <nav>
            <div class="logo">Play Bae</div>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#menu">Menu</a></li>
                <li><a href="#about">About</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <section id="home" class="hero">
        <img src="c:\Users\admin\Pictures\Screenshots\Screenshot 2025-11-10 203657.png" alt="Colorful restaurant interior" class="hero-img">
        <h1>Welcome to Play Bae!</h1>
        <p>Where flavors explode in a spectrum of colors. Dive into our creative fusion dishes!</p>
        <a href="#menu" class="btn">Explore Menu</a>
    </section>

    <section id="menu">
        <h2>Our Features</h2>
        <div class="Speciality">
            <div class="Fresh food with games">
                <img src="c:\Users\admin\Pictures\Screenshots\Screenshot 2025-11-10 210127.png">
               
            </div>

             <h3>OUR MENU</h3>
            <div class="item">
                <img src="c:\Users\admin\Downloads\menu.png">
                
               
            </div>
            <div class="item">
                <img src="c:\Users\admin\Downloads\drinks.png">
                
                
            </div>
        </div>
    </section>

    <section id="about">
        <h2>About Us</h2>
        <p>At Plat Bae, we blend cultures and colors to create unforgettable dining experiences. Our chefs experiment with bold flavors and vibrant presentations to make every meal a feast for the senses.</p>
    </section>

    <section id="contact">
        <h2>Contact Us</h2>
        <p>Address: 123 Colorful Lane, Vibrant City<br>
        Phone: 9876543210<br>
        Email: info@playbae.com</p>
    </section>

    <footer>
        <p>&copy; 2025 Play Bae. All rights reserved.</p>
    </footer>
</body>
</html>
```
## OUTPUT:
<img width="1917" height="1140" alt="image" src="https://github.com/user-attachments/assets/0f1e7ace-327d-4e14-a22b-fc9cdd46e500" />
<img width="1915" height="1145" alt="image" src="https://github.com/user-attachments/assets/b36dd2ae-1e2a-4731-958e-ba9d719ffa43" />
<img width="1919" height="1140" alt="image" src="https://github.com/user-attachments/assets/dbba97ae-d2ba-4325-879e-d4b0c68c5d93" />
<img width="1909" height="1138" alt="image" src="https://github.com/user-attachments/assets/d87a8f9b-28b4-47b5-8abe-f131c799628f" />


## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
