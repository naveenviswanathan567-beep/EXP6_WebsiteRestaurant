# Ex.06 Restaurant Website
## Date:
20.12.2025
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
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Royal Dine</title>
    <style>
        body {
            margin: 0;
            font-family: Arial, sans-serif;
            background-color: #000;
            color: #FFD700;
        }

        /* Navbar */
        .navbar {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 20px 40px;
            border-bottom: 2px solid #FFD700;
        }

        .logo {
            font-size: 28px;
            font-weight: bold;
            letter-spacing: 2px;
        }

        .nav-links {
            list-style: none;
            display: flex;
            gap: 30px;
        }

        .nav-links li a {
            text-decoration: none;
            color: #FFD700;
            font-size: 16px;
            transition: 0.3s;
        }

        .nav-links li a:hover {
            color: #fff;
        }

        /* Hero Section */
        .hero {
            text-align: center;
            padding: 100px 20px;
        }

        .hero h1 {
            font-size: 48px;
            margin-bottom: 20px;
        }

        .hero p {
            font-size: 18px;
            max-width: 600px;
            margin: auto;
        }

        /* Section */
        .section {
            padding: 60px 40px;
            text-align: center;
        }

        .section h2 {
            font-size: 32px;
            margin-bottom: 20px;
        }

        .section p {
            max-width: 700px;
            margin: auto;
            font-size: 16px;
        }

        /* Footer */
        footer {
            text-align: center;
            padding: 20px;
            border-top: 2px solid #FFD700;
            font-size: 14px;
        }
    </style>
</head>
<body>

    <!-- Navbar -->
    <div class="navbar">
        <div class="logo">ROYAL DINE</div>
        <ul class="nav-links">
            <li><a href="#">Home</a></li>
            <li><a href="#">Menu</a></li>
            <li><a href="#">About Us</a></li>
            <li><a href="#">Contact</a></li>
        </ul>
    </div>

    <!-- Hero -->
    <div class="hero">
        <h1>Welcome to Royal Dine</h1>
        <p>Experience the taste of luxury with our royal recipes crafted with passion and perfection.</p>
    </div>

    <!-- Menu Section -->
    <div class="section">
        <h2>Our Menu</h2>
        <p>Delicious royal cuisines, handcrafted desserts, and signature drinks made just for you.</p>
    </div>

    <!-- About Section -->
    <div class="section">
        <h2>About Us</h2>
        <p>Royal Dine blends tradition and elegance to give you an unforgettable dining experience.</p>
    </div>

    <!-- Contact Section -->
    <div class="section">
        <h2>Contact Us</h2>
        <p>Email: royaldine@email.com<br>Phone: +91 98765 43210</p>
    </div>

    <!-- Footer -->
    <footer>
        Naveen © 2024
    </footer>

</body>
</html>
```

## OUTPUT:
<img width="1920" height="1080" alt="Screenshot 2025-12-24 093209" src="https://github.com/user-attachments/assets/8725ee51-74d1-42cc-b4f6-0f7f074ede4b" />
<img width="1920" height="1080" alt="Screenshot 2025-12-24 093202" src="https://github.com/user-attachments/assets/7e00ae92-04e5-40ce-a60c-07bc39a31611" />


## RESULT:
The program for designing software company website using HTML and CSS is completed successfully.
