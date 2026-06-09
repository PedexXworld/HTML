# HTML
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>PedexX Wear</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

    <header>
        <nav>
            <h1 class="logo">PEDEXX</h1>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#products">Products</a></li>
                <li><a href="#about">About</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <section id="home" class="hero">
        <h2>Streetwear Beyond Limits</h2>
        <p>Premium fashion designed for trendsetters.</p>
        <button onclick="shopNow()">Shop Now</button>
    </section>

    <section id="products">
        <h2>Featured Collection</h2>

        <div class="products">
            <div class="card">
                <img src="tanktop.jpg" alt="PedexX Tank Top">
                <h3>PedexX Tank Top</h3>
                <p>GH₵150</p>
            </div>

            <div class="card">
                <img src="hoodie.jpg" alt="PedexX Hoodie">
                <h3>PedexX Hoodie</h3>
                <p>GH₵250</p>
            </div>

            <div class="card">
                <img src="cap.jpg" alt="PedexX Cap">
                <h3>PedexX Cap</h3>
                <p>GH₵80</p>
            </div>
        </div>
    </section>

    <section id="about">
        <h2>About PedexX</h2>
        <p>
            PedexX Wear is a modern streetwear brand focused on
            bold fashion, creativity, and self-expression.
        </p>
    </section>

    <section id="contact">
        <h2>Contact Us</h2>
        <p>Phone: +233 25 635 5743</p>
        <p>Email: pedexxwear@gmail.com</p>
    </section>

    <footer>
        <p>© 2026 PedexX Wear. All Rights Reserved.</p>
    </footer>

    <script src="script.js"></script>

</body>
</html>
