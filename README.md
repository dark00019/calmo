<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Calmo Coffee House</title>
    <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@400;700&display=swap" rel="stylesheet">
    <script src="https://kit.fontawesome.com/a076d05399.js" crossorigin="anonymous"></script>
    <style>
        body {
            margin: 0;
            font-family: 'Montserrat', sans-serif;
            background: linear-gradient(to bottom, #fff7ed, #fffae5);
            color: #4b423a;
        }
        header {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 20px 40px;
            background: rgba(255,255,255,0.9);
            backdrop-filter: blur(8px);
            position: sticky;
            top: 0;
            z-index: 10;
            box-shadow: 0 2px 10px rgba(0,0,0,0.1);
        }
        header h1 {
            display: flex;
            align-items: center;
            font-size: 28px;
            color: #b5651d;
        }
        header h1 i {
            margin-right: 10px;
        }
        header a {
            font-size: 24px;
            color: #b5651d;
            text-decoration: none;
        }
        section.hero {
            text-align: center;
            padding: 100px 20px 60px 20px;
        }
        section.hero h2 {
            font-size: 48px;
            margin-bottom: 20px;
            color: #b5651d;
            animation: fadeIn 1s ease-in-out;
        }
        section.hero p {
            font-size: 18px;
            max-width: 600px;
            margin: 0 auto;
            animation: fadeIn 1.5s ease-in-out;
        }
        @keyframes fadeIn {
            0% { opacity: 0; transform: translateY(20px); }
            100% { opacity: 1; transform: translateY(0); }
        }
        section.menu {
            padding: 60px 20px;
            max-width: 600px;
            margin: 0 auto;
        }
        section.menu h3 {
            text-align: center;
            font-size: 36px;
            color: #b5651d;
            margin-bottom: 40px;
        }
        .coffee-item {
            background: #fff;
            border-radius: 15px;
            padding: 15px 20px;
            margin-bottom: 15px;
            box-shadow: 0 6px 15px rgba(0,0,0,0.1);
            transition: transform 0.3s, box-shadow 0.3s;
            cursor: default;
        }
        .coffee-item:hover {
            transform: translateX(10px);
            box-shadow: 0 10px 20px rgba(0,0,0,0.15);
        }
        .coffee-item h4 {
            margin: 0 0 5px 0;
            color: #b5651d;
            font-size: 20px;
        }
        .coffee-item span {
            font-weight: bold;
            color: #4b423a;
        }
        footer {
            text-align: center;
            padding: 30px 20px;
            background: #fff3e0;
            color: #6b5e53;
            margin-top: 40px;
        }
    </style>
</head>
<body>

    <header>
        <h1><i class="fas fa-coffee"></i>Calmo Coffee House</h1>
        <a href="https://instagram.com" target="_blank"><i class="fab fa-instagram"></i></a>
    </header>

    <section class="hero">
        <h2>Welcome to Calmo</h2>
        <p>Discover the finest coffee flavors in Jordan. Every cup is crafted for perfection and calm.</p>
    </section>

    <section class="menu">
        <h3>Our Popular Coffee Selection</h3>
        <div class="coffee-item"><h4>white Mocha</h4><span>$2</span></div>
        <div class="coffee-item"><h4>Cappuccino</h4><span>$2</span></div>
        <div class="coffee-item"><h4>Latte</h4><span>$2</span></div>
        <div class="coffee-item"><h4>Mocha</h4><span>$2</span></div>
        <div class="coffee-item"><h4>Turkish Coffee</h4><span>$1</span></div>
        <div class="coffee-item"><h4>Americano</h4><span>$1</span></div>
        <div class="coffee-item"><h4>Caramel Latte</h4><span>$2</span></div>
        <div class="coffee-item"><h4>Hazelnut Coffee</h4><span>$2.50</span></div>
        <div class="coffee-item"><h4>Flat White</h4><span>$2</span></div>
        <div class="coffee-item"><h4>Mocha</h4><span>$2</span></div>
    </section>

    <footer>
        © 2025 Calmo Coffee House — Crafted with ☕ & passion.
    </footer>

</body>
</html>
