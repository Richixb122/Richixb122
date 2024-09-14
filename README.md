
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Perfume Store</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }

        header {
            background-color: #333;
            color: #fff;
            padding: 10px 0;
            text-align: center;
        }

        nav ul {
            list-style: none;
            padding: 0;
        }

        nav ul li {
            display: inline;
            margin: 0 15px;
        }

        nav ul li a {
            color: #fff;
            text-decoration: none;
            font-weight: bold;
        }

        .hero {
            text-align: center;
            padding: 100px 20px;
            background-color: #444;
            color: #fff;
        }

        .hero h2 {
            margin: 0;
            font-size: 2.5em;
        }

        .cta {
            display: inline-block;
            margin-top: 20px;
            padding: 10px 20px;
            background-color: #ff6347;
            color: #fff;
            text-decoration: none;
            font-size: 1.2em;
        }

        .featured, .catalog {
            padding: 50px 20px;
            text-align: center;
        }

        .perfume-list {
            display: flex;
            justify-content: space-around;
            flex-wrap: wrap;
        }

        .perfume-card {
            background-color: #fff;
            padding: 20px;
            margin: 20px;
            border-radius: 8px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            width: 220px;
            text-align: center;
        }

        .perfume-card img {
            width: 100%;
            height: auto;
            border-radius: 8px;
        }

        .perfume-card h3 {
            margin: 15px 0;
            font-size: 1.2em;
        }

        .perfume-card p {
            font-size: 0.9em;
            color: #555;
        }

        .buy-btn {
            display: inline-block;
            margin-top: 15px;
            padding: 10px 15px;
            background-color: #ff6347;
            color: #fff;
            text-decoration: none;
            border-radius: 5px;
        }

        footer {
            text-align: center;
            padding: 20px;
            background-color: #333;
            color: #fff;
        }
    </style>
</head>
<body>
    <!-- Header -->
    <header>
        <h1>Welcome to the Perfume Store</h1>
        <nav>
            <ul>
                <li><a href="#hero">Home</a></li>
                <li><a href="#catalog">Perfume Catalog</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <!-- Hero Section -->
    <section id="hero" class="hero">
        <h2>Find Your Signature Scent</h2>
        <a href="#catalog" class="cta">Shop Now</a>
    </section>

    <!-- Featured Perfumes -->
    <section class="featured">
        <h2>Best Sellers</h2>
        <div class="perfume-list">
            <!-- Perfume Card 1 -->
            <div class="perfume-card">
                <img src="images/dior-sauvage.jpg" alt="Dior Sauvage">
                <h3>Dior Sauvage</h3>
                <p>Notes: Bergamot, Sichuan pepper, amberwood</p>
                <a href="#" class="buy-btn">More Info</a>
            </div>

            <!-- Perfume Card 2 -->
            <div class="perfume-card">
                <img src="images/versace-eros.jpg" alt="Versace Eros">
                <h3>Versace Eros</h3>
                <p>Notes: Mint, green apple, tonka bean</p>
                <a href="#" class="buy-btn">More Info</a>
            </div>

            <!-- Perfume Card 3 -->
            <div class="perfume-card">
                <img src="images/bleu-de-chanel.jpg" alt="Bleu de Chanel">
                <h3>Bleu de Chanel</h3>
                <p>Notes: Citrus accord, ginger, sandalwood</p>
                <a href="#" class="buy-btn">More Info</a>
            </div>
        </div>
    </section>

    <!-- Catalog Section -->
    <section id="catalog" class="catalog">
        <h2>Fresh & Citrus</h2>
        <div class="perfume-list">
            <!-- Perfume 1 -->
            <div class="perfume-card">
                <img src="images/dior-sauvage.jpg" alt="Dior Sauvage">
                <h3>Dior Sauvage</h3>
                <p>Notes: Bergamot, Sichuan pepper, amberwood</p>
                <a href="#" class="buy-btn">More Info</a>
            </div>

            <!-- Perfume 2 -->
            <div class="perfume-card">
                <img src="images/versace-eros.jpg" alt="Versace Eros">
                <h3>Versace Eros</h3>
                <p>Notes: Mint, green apple, tonka bean</p>
                <a href="#" class="buy-btn">More Info</a>
            </div>

            <!-- Perfume 3 -->
            <div class="perfume-card">
                <img src="images/bleu-de-chanel.jpg" alt="Bleu de Chanel">
                <h3>Bleu de Chanel</h3>
                <p>Notes: Citrus accord, ginger, sandalwood</p>
                <a href="#" class="buy-btn">More Info</a>
            </div>

            <!-- Perfume 4 -->
            <div class="perfume-card">
                <img src="images/tom-ford-oud-wood.jpg" alt="Tom Ford Oud Wood">
                <h3>Tom Ford Oud Wood</h3>
                <p>Notes: Rosewood, cardamom, tonka bean</p>
                <a href="#" class="buy-btn">More Info</a>
            </div>
        </div>

        <!-- Second row of perfumes -->
        <div class="perfume-list">
            <!-- Perfume 5 -->
            <div class="perfume-card">
                <img src="images/paco-rabanne-1-million.jpg" alt="Paco Rabanne 1 Million">
                <h3>Paco Rabanne 1 Million</h3>
                <p>Notes: Grapefruit, cinnamon, leather</p>
                <a href="#" class="buy-btn">More Info</a>
            </div>

            <!-- Perfume 6 -->
            <div class="perfume-card">
                <img src="images/giorgio-armani-acqua-di-gio.jpg" alt="Giorgio Armani Acqua di Giò">
                <h3>Giorgio Armani Acqua di Giò</h3>
                <p>Notes: Sea notes, jasmine, rosemary</p>
                <a href="#" class="buy-btn">More Info</a>
            </div>

            <!-- Perfume 7 -->
            <div class="perfume-card">
                <img src="images/yves-saint-laurent-lhomme.jpg" alt="Yves Saint Laurent L
