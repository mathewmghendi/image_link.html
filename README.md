<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Image Links</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f2f2f2;
        }
        header, nav, main, footer {
            padding: 20px;
        }
        header {
            background-color: #333;
            color: #fff;
            text-align: center;
        }
        nav {
            background-color: #666;
            text-align: center;
        }
        nav a {
            color: #fff;
            text-decoration: none;
            margin-right: 20px;
        }
        main {
            padding-top: 50px;
        }
        section {
            margin-bottom: 50px;
        }
        h1, h2 {
            text-align: center;
        }
        .gallery {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
            grid-gap: 20px;
        }
        .gallery img {
            width: 100%;
            height: auto;
            display: block;
        }
        footer {
            background-color: #333;
            color: #fff;
            text-align: center;
            position: fixed;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>
<body>
    <header>
        <h1>Welcome to Image Links</h1>
    </header>
    <nav>
        <a href="#home">Home</a>
        <a href="#gallery">Gallery</a>
        <a href="#menu">Menu</a>
    </nav>
    <main>
        <section id="home">
            <h2>Home</h2>
            <p>Welcome to our website! Here's an image related to technology:</p>
            <a href="https://example.com/technology"><img src="technology.jpg" alt="Technology"></a>
        </section>
        <section id="gallery">
            <h2>Gallery</h2>
            <div class="gallery">
                <a href="https://example.com/nature"><img src="nature1.jpg" alt="Nature 1"></a>
                <a href="https://example.com/nature"><img src="nature2.jpg" alt="Nature 2"></a>
                <a href="https://example.com/nature"><img src="nature3.jpg" alt="Nature 3"></a>
            </div>
        </section>
        <section id="menu">
            <h2>Menu</h2>
            <ul>
                <li><a href="https://example.com/food1"><img src="food1.jpg" alt="Food 1"> Food Item 1</a></li>
                <li><a href="https://example.com/food2"><img src="food2.jpg" alt="Food 2"> Food Item 2</a></li>
                <li><a href="https://example.com/food3"><img src="food3.jpg" alt="Food 3"> Food Item 3</a></li>
            </ul>
        </section>
    </main>
    <footer>
        <p>© 2024 Image Links. All rights reserved.</p>
    </footer>
</body>
</html>

