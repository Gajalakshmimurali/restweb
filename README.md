# Ex.07 Restaurant Website
## Date:14/12/2024

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
hotel.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Veggies world</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
        }

        header {
            background-color: #b7a207;
            font-family:Georgia, 'Times New Roman', Times, serif;
            padding:0.5rem;
            text-align: center;
            height:auto
        }
        
        nav {
            background-color: #444;
            display: flex;
            justify-content: center;
            padding: 0.5rem;
        }

        nav a {
            color: white;
            margin: 0 1rem;
            text-decoration: none;
        }

        nav a:hover {
            text-decoration: underline;
        }

        .hero {
            background:url( 123334-maharaja-bhog-2.webp);
            height :  400px;
            display: flex;
            justify-content: center;
            padding: 0.5rem;
        }

        nav a {
            color: white;
            margin: 0 1rem;
            text-decoration: none;
        }

        nav a:hover {
            text-decoration: underline;
        }

        .hero {
            
            height:auto;
            width: auto;
            text-decoration: wavy;
            text-transform: uppercase;
            display: flex;
            justify-content: center;
            align-items: center;
            background: #000;
            text-shadow: 2px 2px 4px hsla(0, 88%, 40%, 0.7);
        }

         
        

        .hero h1 {
            font-size: 3rem;
            color: hsl(68, 89%, 52%);
        }

        .container {
            padding: 2rem;
text-align: center;
        }

        .menu {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            gap: 2rem;
        }

        .menu-item {
            border: 1px solid #ddd;
            border-radius: 8px;
            overflow: hidden;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
        }

        .menu-item img {
            width: 100%;
            height: 150px;
            object-fit: cover;
        }

        .menu-item h3 {
            margin: 0.5rem;
        }

        .menu-item p {
            margin: 0.5rem;
            color: #666;
        }
        footer{
            text-align: center;
            color:black;
        }

        
    </style>
</head>
<body>
    <header>
        <h1>veggies world</h1>
        <img src="hotel.jpg"> 

        <p>Have it feel it...</p>
    </header>

    <nav>
        <a href="hotel.html">home</a>
        <a href="menu.html">Menu</a>
        <a href="about.html">About Us</a>
        <a href="contact.html">Contact</a>
    </nav>

    <section class="hero">
           <img src=" 1683699728_image.jpg " height="500px" width="700px">
           <h1>WELCOME</h1>    
           <img src="123334-maharaja-bhog-2.webp" height="500px" width="700px">
    </section>
    <footer>
        <p>&copy; 2024 veggies world. All rights reserved.</p>
        <p>&copy; designed by Gajalakshmi.</p>
    </footer>    
</body>

menu.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Popular Dishes</title>
    <style>
        body {    
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f9f9f9;
        }

        .container {
            max-width: 1200px;
            margin: 20px auto;
            padding: 10px;
            text-align: center;
        }

        .title {
            font-size: 2em;
            margin-bottom: 20px;
            color: #333;
        }

        .grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
            gap: 20px;
        }

        .card {
            background-color: #fff;
            border-radius: 8px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
            overflow: hidden;
            transition: transform 0.3s;
        }

        .card:hover {
            transform: translateY(-5px);
        }

        .card img {
            width: 100%;
            height: 400px;
            object-fit: cover;
        }

        .card-content {
            padding: 15px;
        }

        .card-content h3 {
            font-size: 1.2em;
            margin: 0 0 10px;
            color: #333;
        }

        .card-content p {
            font-size: 0.9em;
            color: #666;
            margin: 0 0 10px;
        }

        .card-content .price {
            font-size: 1em;
            color: #333;
            margin-bottom: 10px;
        }

        .card-content button {
            background-color: #ff9800;
            color: #fff;
            border: none;
            padding: 10px 15px;
            border-radius: 4px;
            cursor: pointer;
            font-size: 0.9em;
            transition: background-color 0.3s;
        }

        .card-content button:hover {
            background-color: #e68a00;
        }
        footer{
            text-align: center;
            color:black;
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="title">Popular Dishes</div>
        <div class="grid">
            <div class="card">
                <img src="sq-scrumptious-tiramisu-cake-cake2636exot-AA.webp" alt="Dish Image">
                <div class="card-content">
                    <h3>Tiramisu Cake</h3>
                    <p>Sample description text for this dish.</p>
                    <div class="price">Rs.100.00</div>
                    <button>Buy Now</button>
                </div>
            </div>
            <div class="card">
                <img src="download (3).jpg" alt="Dish Image">
                <div class="card-content">
                    <h3>mushroom</h3>
                    <div class="price">Rs.200.00</div>
                    <button>Buy Now</button>
                </div>
            </div>
            <div class="card">
                <img src="Veg-Puff-Recipe.jpg" alt="Dish Image">
                <div class="card-content">
                    <h3>veg puffs</h3>
                    <div class="price">Rs.20.00</div>
                    <button>Buy Now</button>
                </div>
            </div>
            <div class="card">
                <img src="Samosas-with-Potatoes-and-Peas-2-1.jpg" alt="Dish Image">
                <div class="card-content">
                    <h3>samosa</h3>
                    <div class="price">Rs.15.00</div>
                    <button>Buy Now</button>
                </div>
            </div>
            <div class="card">
                <img src="naan.jpg" alt="Dish Image">
                <div class="card-content">
                    <h3>naan and paneer butter masala</h3>
                    <p>Sample description text for this dish.</p>
                    <div class="price">Rs.200.00</div>
                    <button>Buy Now</button>
                </div>
            </div>
            <div class="card">
                <img src="images.jpg" alt="Dish Image">
                <div class="card-content">
                    <h3>dosa</h3>
                    <p>Sample description text for this dish.</p>
                    <div class="price">Rs.10.00</div>
                    <button>Buy Now</button>
                </div>
            </div>
            <div class="card">
                <img src="idli.jpg" alt="Dish Image">
                <div class="card-content">
                    <h3>idli</h3>
                    <p>Sample description text for this dish.</p>
                    <div class="price">Rs.10.00</div>
                    <button>Buy Now</button>
                </div>
            </div>
            <div class="card">
                <img src="full meals.jpg" alt="Dish Image">
                <div class="card-content">
                    <h3>full meals</h3>
                    <p>Sample description text for this dish.</p>
                    <div class="price">Rs.100.00</div>
                    <button>Buy Now</button>
                </div>
            </div>
            <div class="card">
                <img src="sweet pongal.jpg" alt="Dish Image">
                <div class="card-content">
                    <h3>sweet pongal</h3>
                    <p>Sample description text for this dish.</p>
                    <div class="price">Rs.50.00</div>
                    <button>Buy Now</button>
                </div>
            </div>
            <div class="card">
                <img src="rosemilk.jpg" alt="Dish Image">
                <div class="card-content">
                    <h3>rosemilk</h3>
                    <p>Sample description text for this dish.</p>
                    <div class="price">Rs.40.00</div>
                    <button>Buy Now</button>
                </div>
            </div>
            <div class="card">
                <img src="soup.jpg" alt="Dish Image">
                <div class="card-content">
                    <h3>soup</h3>
                    <p>Sample description text for this dish.</p>
                    <div class="price">Rs.70.00</div>
                    <button>Buy Now</button>
                </div>
            </div>
            <div class="card">
                <img src="noodles.jpg" alt="Dish Image">
                <div class="card-content">
                    <h3>noodles</h3>
                    <p>Sample description text for this dish.</p>
                    <div class="price">Rs.150.00</div>
                    <button>Buy Now</button>
                </div>
            </div>
        </div>
    </div>
    <footer>
        <p>Designed by GAJALAKSHMI</p>
    </footer>
</body>
</html>

about.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Workers</title>
    <style>
        body {
            margin: 0;
            background-image: url(istockphoto-1428412216-612x612.jpg);
            background-size: cover;
            background-repeat: no-repeat;
            
            font-family: Arial, sans-serif;
        }

        .container {
            text-align: center;
            padding: 50px;
            border-top-left-radius: 50px;
            border-top-right-radius: 50px;
            color: black;
        }

        .container h1 {
            font-size: 2.5em;
            font-weight: bold;
            color: black;
        }

        .workers {
            display: flex;
            justify-content: center;
            gap: 40px;
            
            padding: 50px;
            border-bottom-left-radius: 50px;
            border-bottom-right-radius: 50px;
        }

        .worker {
            text-align: center;
            color:yellow;
        }

        .worker img {
            width: 150px;
            height: 150px;
            border-radius: 50%;
            border: 4px solid black;
            object-fit: cover;
        }

        .worker p {
            margin-top: 10px;
            font-size: 1.2em;
            font-style: italic;
        }
        footer{
            text-align: center;
            color:yellow;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>our employees</h1>
    </div>

    <div class="workers">
        <div class="worker">
            <img src="rangu.jpg" alt="chef Madhampatti Rangarajan">
            <p>chef Madhampatti Rangarajan</p>
        </div>
        <div class="worker">
            <img src="dhamodharan.jpg" alt="Chef dhamodharan">
            <p>Chef dhamodharan</p>
        </div>
        <div class="worker">
            <img src="venkatesh.jpg" alt="Chef Venkatesh Butt">
            <p>Chef Venkatesh Butt</p>
        </div>
        <div class="worker">
            <img src="koushik.jpg" alt="chef Koushik">
            <p>chef Koushik</p>
        </div>
        <div class="worker">
            <img src="dheena.jpeg" alt="chef dheena">
            <p>chef dheena</p>
        </div>
    </div>
    <footer>
        <p>&copy; 2024 veggies world. All rights reserved.</p>
        <p>&copy; designed by Gajalakshmi.</p>
    </footer> 
</body>
</html>

contact.html

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contact Us</title>
    <style>
        body {
            margin: 0;
            font-family: Arial, sans-serif;
            background: url('veg.jpg');
            background-repeat:no-repeat;
            color: #fff;
            background-size: cover;
        }

        .contact-section {
            display: flex;
            flex-direction: column;
            align-items: center;
            text-align: center;
            padding: 50px 20px;
           
            
            
        }

        .contact-section h1 {
            font-size: 2.5rem;
            margin-bottom: 10px;
            font-family: 'Georgia', serif;
        }

        .contact-section h2 {
            font-size: 1.2rem;
            margin-bottom: 30px;
            color: #ccc;
        }

        .contact-details {
            margin-bottom: 30px;
            line-height: 1.8;
        }

        .contact-details p {
            margin: 5px 0;
        }

        .contact-details a {
            color:aliceblue;
            text-decoration: none;
        }

        .contact-form {
            max-width: 600px;
            width: 100%;
            display: grid;
            grid-template-columns: repeat(2, 1fr);
            gap: 10px;
        }

        .contact-form input, 
        .contact-form textarea {
            width: 100%;
            padding: 10px;
            margin: 5px 0;
            border: none;
            border-radius: 5px;
        }

        .contact-form textarea {
            grid-column: span 2;
            resize: none;
            height: 100px;
        }

        .contact-form button {
            grid-column: span 2;
            padding: 10px;
            border: none;
            border-radius: 5px;
            background-color: #ffcc00;
            color: #000;
            font-size: 1rem;
            cursor: pointer;
            transition: background-color 0.3s;
        }

        .contact-form button:hover {
            background-color: #e6b800;
        }

        .social-icons {
            margin-top: 20px;
        }

        .social-icons a {
            margin: 0 10px;
            color: #ffcc00;
            font-size: 1.5rem;
            text-decoration: none;
        }

        .social-icons a:hover {
            color: #e6b800;
        }
        footer{
            text-align: center;
            color:yellow;
        }

    </style>
</head>
<body >
    
    <section class="contact-section">
        
        <h1>Contact Us</h1>

        <h2>HOW TO GET IN TOUCH?</h2>
        <p class="contact-details">
            ADDRESS: 133/20b thenpalani nagar,thiruvannamali<br>
            PHONE NUMBER: <a href="tel:+8668082120">+8668082120</a><br>
            EMAIL ADDRESS: <a href="mailto:gaja23949@gmail.com">gaja23949@gmail.com</a>
        </p>

        <form class="contact-form">
            <input type="text" placeholder="Your Name" required>
            <input type="email" placeholder="Your Email" required>
            <input type="text" placeholder="Subject">
            <textarea placeholder="Message" required></textarea>
            <button type="submit">Book a Table</button>
        </form>

        <div class="social-icons">
            <a href="#">&#xf0d2;</a>
            <a href="#">&#xf09a;</a>
            <a href="#">&#xf099;</a>
            <a href="#">&#xf0d5;</a>
        </div>
    </section>
    <footer>
        <p>
            Designed by GAJALAKSHMI
        </p>
    </footer>
</body>
</html>
```


## Output
![alt text](src1(2).png)
![alt text](src2(2).png)
![alt text](src3(2).png)
![alt text](src4(3).png)
![alt text](src4(2).png)
## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
