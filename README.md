<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>Delicious Foods</title>
    <link rel="stylesheet" href="styles.css">
    <script src="script.js" defer></script>
</head>
<body>

    <!-- Header Section -->
    <header>
        <div class="logo">
            <h1>Delicious Foods</h1>
        </div>
        <nav>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#menu">Menu</a></li>
                <li><a href="#recipes">Recipes</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <!-- Main Banner Section -->
    <section class="banner" id="home">
        <div class="banner-content">
            <h2>Welcome to Delicious Foods!</h2>
            <p>Explore our collection of mouth-watering dishes.</p>
            <a href="#menu" class="cta-button">See the Menu</a>
        </div>
    </section>

    <!-- Food Categories Section -->
    <section class="categories">
        <h2>Food Categories</h2>
        <div class="category-cards">
            <div class="card">
                <img src="images/burger.jpg" alt="Burgers">
                <h3>Burgers</h3>
                <p>Juicy and delicious burgers for every craving.</p>
                <a href="#burgers">See Recipes</a>
            </div>
            <div class="card">
                <img src="images/pasta.jpg" alt="Pasta">
                <h3>Pasta</h3>
                <p>Perfectly cooked pasta with a variety of sauces.</p>
                <a href="#pasta">See Recipes</a>
            </div>
            <div class="card">
                <img src="images/sushi.jpg" alt="Sushi">
                <h3>Sushi</h3>
                <p>Fresh, delightful sushi made with the finest ingredients.</p>
                <a href="#sushi">See Recipes</a>
            </div>
        </div>
    </section>

    <!-- Featured Dishes Section -->
    <section class="featured-dishes" id="menu">
        <h2>Featured Dishes</h2>
        <div class="dish-gallery">
            <div class="dish">
                <img src="images/dish1.jpg" alt="Dish 1">
                <h3>Grilled Chicken</h3>
                <p>A perfectly grilled chicken with spices and herbs.</p>
                <button class="recipe-btn" onclick="showRecipe('recipe1')">View Recipe</button>
            </div>
            <div class="dish">
                <img src="images/dish2.jpg" alt="Dish 2">
                <h3>Seafood Paella</h3>
                <p>A flavorful paella filled with shrimp, mussels, and calamari.</p>
                <button class="recipe-btn" onclick="showRecipe('recipe2')">View Recipe</button>
            </div>
        </div>
    </section>

    <!-- Recipe Modal Section -->
    <div id="recipe-modal" class="modal">
        <div class="modal-content">
            <span class="close-btn" onclick="closeRecipe()">&times;</span>
            <h2 id="recipe-title"></h2>
            <p id="recipe-details"></p>
        </div>
    </div>

    <!-- Footer Section -->
    <footer id="contact">
        <div class="footer-content">
            <p>&copy; 2025 Delicious Foods. All Rights Reserved.</p>
            <p>Contact us at: <a href="mailto:info@deliciousfoods.com">info@deliciousfoods.com</a></p>
        </div>
    </footer>

</body>
</html>
# Mightysitu.to
