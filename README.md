# Ex.07 Restaurant Website
# Date: 04/10/2025
# AIM:
To develop a static Restaurant website to display the food items and services provided by them.

# DESIGN STEPS:
## Step 1:
Requirement collection.

## Step 2:
Creating the layout using HTML and CSS.

## Step 3:
Updating the sample content.

## Step 4:
Choose the appropriate style and color scheme.

## Step 5:
Validate the layout in various browsers.

## Step 6:
Validate the HTML code.

## Step 7:
Publish the website in the given URL.

# PROGRAM:
```

<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Foodie Delight - Home</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>

  <header>
    <h1>FOODIE DELIGHT</h1>
    <nav>
      <ul>
        <li><a href="index.html">Home</a></li>
        <li><a href="menu.html">Menu</a></li>
        <li><a href="admin.html">Administration</a></li>
        <li><a href="contact.html">Contact Us</a></li>
      </ul>
    </nav>
  </header>

  <section class="banner">
    <img src="banner.jpg" alt="Banner">

    <div class="banner-text">
      <h2>30% Off This Weekend!</h2>
      <p>Come enjoy delicious food and great ambiance at Foodie Delight. Limited time offer!</p>
    </div>
  </section>

  <section class="info">
    <div class="info-card">
      <img src="newmenu.webp" alt="Menu">
      <h3>Our New Menu</h3>
      <p>Check out our freshly updated menu filled with tasty delights made just for you.</p>
      <a href="menu.html">See our menu</a>
    </div>

    <div class="info-card">
      <img src="table.jpg" alt="Table">
      <h3>Book a Table</h3>
      <p>Reserve your seat for a perfect dining experience with friends and family.</p>
      <a href="contact.html">Book now</a>
    </div>

    <div class="info-card">
      <img src="hours.jpg" alt="Hours">
      <h3>Opening Hours</h3>
      <p>Mon - Fri: 2pm - 10pm<br>Sat: 12pm - 11pm<br>Sun: 2pm - 9pm</p>
    </div>
  </section>

  <footer>
    <p>Designed and Developed by <strong>Vanathi</strong></p>
  </footer>

</body>
</html>

style1.css
body {
  font-family: Arial, sans-serif;
  margin: 0;
  padding: 0;
  background: #d8e37f;
}
header {
  background: #565653;
  color: white;
  padding: 15px;
  text-align: center;
}
nav {
  background: #6855d6;
  display: flex;
  justify-content: center;
}
nav a {
  color: white;
  padding: 14px 20px;
  text-decoration: none;
  display: block;
}
nav a:hover {
  background: #333;
}
section {
  padding: 20px;
}
h2 {
  text-align: center;
  margin-bottom: 20px;
}
.food-grid, .admin-grid {
  display: grid;
  grid-template-columns: repeat(4, 1fr);
  gap: 20px;
  margin: 20px;
}
.food-item, .admin-item {
  background: white;
  padding: 10px;
  border-radius: 8px;
  box-shadow: 0 2px 5px rgba(0,0,0,0.2);
  text-align: center;
}
.food-item img, .admin-item img {
  width: 100%;
  height: 150px;
  object-fit: cover;
  border-radius: 8px;
}
footer {
  background: #333;
  color: white;
  text-align: center;
  padding: 10px;
}

menu.html


<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Foodie Delight - Menu</title>
  <link rel="stylesheet" href="style1.css">
</head>
<body>
  <header>
    <h1>🍴 Foodie Delight 🍴</h1>
  </header>
  <nav>
    <a href="index.html">Home</a>
    <a href="menu.html">Menu</a>
    <a href="admin.html">Administration</a>
    <a href="contact.html">Contact Us</a>
  </nav>

  <section>
    <h2>Our Menu</h2>
    <div class="food-grid">
      <div class="food-item"><img src="pizza.avif" alt="Pizza"><p>Pizza</p></div>
      <div class="food-item"><img src="burger.webp" alt="Burger"><p>Burger</p></div>
      <div class="food-item"><img src="pasta.webp" alt="Pasta"><p>Pasta</p></div>
      <div class="food-item"><img src="sandwich.jpg" alt="Sandwich"><p>Sandwich</p></div>
      <div class="food-item"><img src="friedrice.webp" alt="Fried Rice"><p>Fried Rice</p></div>
      <div class="food-item"><img src="noodles.webp" alt="Noodles"><p>Noodles</p></div>
      <div class="food-item"><img src="icecream.jpg" alt="Ice Cream"><p>Ice Cream</p></div>
      <div class="food-item"><img src="salad.webp" alt="Salad"><p>Salad</p></div>
      <div class="food-item"><img src="soup.jpg" alt="Soup"><p>Soup</p></div>
      <div class="food-item"><img src="cake.webp" alt="Cake"><p>Cake</p></div>
      <div class="food-item"><img src="friedchicken.jpg" alt="Fried Chicken"><p>friedchicken</p></div>
      <div class="food-item"><img src="briyani.webp" alt="Briyani"><p>briyani</p></div>
    </div>
  </section>

  <footer>
    <p>Designed by Vanathi Thirumavalavan</p>
  </footer>
</body>
</html>

admin.html


<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Foodie Delight - Administration</title>
  <link rel="stylesheet" href="style1.css">
</head>
<body>
  <header>
    <h1>🍴 Foodie Delight 🍴</h1>
  </header>
  <nav>
    <a href="index.html">Home</a>
    <a href="menu.html">Menu</a>
    <a href="admin.html">Administration</a>
    <a href="contact.html">Contact Us</a>
  </nav>

  <section>
    <h2>Our Administration</h2>
    <div class="admin-grid">
      <div class="admin-item"><img src="manager.jpg" alt="Manager"><p><b>Mrs. Amritha</b><br>Manager</p></div>
      <div class="admin-item"><img src="ass manager.webp" alt="Asst Manager"><p><b>Ms. Bella</b><br>Assistant Manager</p></div>
      <div class="admin-item"><img src="chef.avif" alt="Chef"><p><b>Mr. Catherine</b><br>Head Chef</p></div>
      <div class="admin-item"><img src="hr.webp" alt="HR"><p><b>Ms. Diya</b><br>HR</p></div>
      <div class="admin-item"><img src="supervisor.jpg" alt="Supervisor"><p><b>Mr. Edward</b><br>Supervisor</p></div>
      <div class="admin-item"><img src="receptionist.webp" alt="Receptionist"><p><b>Ms. Inaya</b><br>Receptionist</p></div>
    </div>
  </section>

  <footer>
    <p>Designed by Vanathi Thirumavalavan</p>
  </footer>
</body>
</html>

contact.html


<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Foodie Delight - Contact Us</title>
  <link rel="stylesheet" href="style1.css">
</head>
<body>
  <header>
    <h1>🍴 Foodie Delight 🍴</h1>
  </header>
  <nav>
    <a href="index.html">Home</a>
    <a href="menu.html">Menu</a>
    <a href="admin.html">Administration</a>
    <a href="contact.html">Contact Us</a>
  </nav>

  <section>
    <h2>Contact Us</h2>
    <p style="text-align:center;">
      📍 Address: Wonder Food Street,Chennai, Tamil Nadu <br>
      ☎ Phone: +91 9876543219 <br>
      📧 Email: info@foodiedelight.com
    </p>
  </section>

  <footer>
    <p>Designed by Vanathi Thirumavalavan</p>
  </footer>
</body>
</html>
```
# OUTPUT:

![alt text](<Screenshot 2025-10-04 213553.png>)

![alt text](<Screenshot 2025-10-04 214918.png>)

![alt text](<Screenshot 2025-10-04 215015.png>)

![alt text](<Screenshot 2025-10-04 215043.png>)
# RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
