# -Hello_game-
Web
<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Le Délice Italien</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #fff8f0;
            color: #333;
        }
        header {
            background-color: #d35400;
            color: white;
            padding: 20px;
            text-align: center;
        }
        header h1 {
            margin: 0;
        }
        nav {
            display: flex;
            justify-content: center;
            background-color: #e67e22;
        }
        nav a {
            color: white;
            padding: 14px 20px;
            text-decoration: none;
            transition: background 0.3s;
        }
        nav a:hover {
            background-color: #d35400;
        }
        section {
            padding: 40px 20px;
            max-width: 1000px;
            margin: auto;
        }
        h2 {
            color: #d35400;
        }
        .menu {
            display: flex;
            flex-wrap: wrap;
            gap: 20px;
        }
        .dish {
            flex: 1 1 calc(33% - 40px);
            background-color: #fff1e0;
            padding: 15px;
            border-radius: 8px;
            box-shadow: 0 2px 8px rgba(0,0,0,0.1);
        }
        .dish img {
            max-width: 100%;
            border-radius: 8px;
        }
        footer {
            background-color: #d35400;
            color: white;
            text-align: center;
            padding: 20px;
        }
        @media(max-width: 768px) {
            .menu {
                flex-direction: column;
            }
            .dish {
                flex: 1 1 100%;
            }
        }
    </style>
</head>
<body>

<header>
    <h1>Le Délice Italien</h1>
    <p>Le meilleur restaurant italien en ville</p>
</header>

<nav>
    <a href="#menu">Menu</a>
    <a href="#photos">Photos</a>
    <a href="#contact">Contact</a>
</nav>

<section id="menu">
    <h2>Notre Menu</h2>
    <div class="menu">
        <div class="dish">
            <img src="https://images.unsplash.com/photo-1608151561064-0b395d8a2f10?ixlib=rb-4.0.3&auto=format&fit=crop&w=800&q=80" alt="Pizza Margherita" />
            <h3>Pizza Margherita</h3>
            <p>Sauce tomate, mozzarella, basil frais. Un classique italien.</p>
        </div>
        <div class="dish">
            <img src="https://images.unsplash.com/photo-1604191707588-0d7db6c8f4f2?ixlib=rb-4.0.3&auto=format&fit=crop&w=800&q=80" alt="Pâtes Carbonara" />
            <h3>Pâtes Carbonara</h3>
            <p>Pâtes fraîches avec sauce à la crème, œuf, pancetta et parmesan.</p>
        </div>
        <div class="dish">
            <img src="https://images.unsplash.com/photo-1602572788492-5f0f6f9d1e5f?ixlib=rb-4.0.3&auto=format&fit=crop&w=800&q=80" alt="Tiramisu" />
            <h3>Tiramisu</h3>
            <p>Un dessert italien traditionnel avec café, mascarpone et cacao.</p>
        </div>
    </div>
</section>

<section id="photos">
    <h2>Photos du restaurant</h2>
    <img src="https://images.unsplash.com/photo-1577125766382-7f8f1f0b37f4" alt="Restaurant italien" style="width:100%; max-width:800px; border-radius:8px;">
</section>

<section id="contact">
    <h2>Contactez-nous</h2>
    <p>Adresse : 123 Rue dela gloire' Ville</p>
    <p>Téléphone : 01 23 45 67 89</p>
    <p>Email : contact@deliceitalien.fr</p>
    <p>Horaires : 12h - 22h, tous les jours</p>
</section>

<footer>
    <p>&copy; 2024 Le Délice Italien. Tous droits réservés.</p>
</footer>

</body>
</html>
