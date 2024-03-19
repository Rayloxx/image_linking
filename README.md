# image_linking
image linking in HTML
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Image Links</title>
    <style>
        /* Basic styling for the grid layout */
        .grid-container {
            display: grid;
            grid-template-columns: repeat(3, 1fr);
            gap: 20px;
            padding: 20px;
        }
        .grid-item {
            text-align: center;
        }
    </style>
</head>
<body>

<nav>
    <a href="#home">Home</a> |
    <a href="#gallery">Gallery</a> |
    <a href="#menu">Menu</a>
</nav>

<section id="home">
    <h2>Welcome to our website!</h2>
    <p>Explore our technology-related content below:</p>
    <a href="https://www.example.com/technology">
        <img src="technology.jpg" alt="Technology Image" width="300">
    </a>
</section>

<section id="gallery">
    <h2>Gallery</h2>
    <p>Explore our nature-related images:</p>
    <div class="grid-container">
        <div class="grid-item">
            <a href="https://www.example.com/nature1">
                <img src="nature1.jpg" alt="Nature Image 1">
            </a>
        </div>
        <div class="grid-item">
            <a href="https://www.example.com/nature2">
                <img src="nature2.jpg" alt="Nature Image 2">
            </a>
        </div>
        <div class="grid-item">
            <a href="https://www.example.com/nature3">
                <img src="nature3.jpg" alt="Nature Image 3">
            </a>
        </div>
    </div>
</section>

<section id="menu">
    <h2>Menu</h2>
    <p>Explore our delicious food items:</p>
    <ul>
        <li><a href="https://www.example.com/food1"><img src="food1.jpg" alt="Food 1"> Food Item 1</a></li>
        <li><a href="https://www.example.com/food2"><img src="food2.jpg" alt="Food 2"> Food Item 2</a></li>
        <li><a href="https://www.example.com/food3"><img src="food3.jpg" alt="Food 3"> Food Item 3</a></li>
    </ul>
</section>

</body>
</html>
