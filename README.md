<!DOCTYPE html>
<html lang="pl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Książki vs Gry - Prezentacja</title>
    <style>
        body {
            font-family: 'Georgia', serif;
            background: linear-gradient(to right, #f0e5d8, #f4e1d2);
            color: #333;
            margin: 0;
            padding: 0;
        }
        .navbar {
            background-color: #2c3e50;
            padding: 15px;
            display: flex;
            justify-content: center;
            gap: 20px;
            position: fixed;
            width: 100%;
            top: 0;
            left: 0;
            box-shadow: 0px 4px 8px rgba(0, 0, 0, 0.2);
            z-index: 1000;
            border-radius: 0 0 20px 20px;
        }
        .navbar a {
            color: white;
            text-decoration: none;
            font-size: 18px;
            font-weight: bold;
            padding: 10px 20px;
            border-radius: 5px;
            transition: background-color 0.3s;
        }
        .navbar a:hover {
            background-color: #1a252f;
        }
        .header {
            background: linear-gradient(135deg, #d35400, #e67e22);
            color: white;
            text-align: center;
            padding: 50px 30px;
            font-size: 32px;
            font-weight: bold;
            text-transform: uppercase;
            letter-spacing: 2px;
            box-shadow: 0px 4px 8px rgba(0, 0, 0, 0.2);
            margin-top: 60px;
            border-radius: 20px;
        }
        .section {
            height: 100vh;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            text-align: center;
            padding: 40px;
            font-size: 24px;
            border-bottom: 5px solid #d35400;
            position: relative;
            border-radius: 30px;
            margin: 20px;
            box-shadow: 0px 4px 10px rgba(0, 0, 0, 0.2);
        }
        .image-section {
            background-size: cover;
            background-position: center;
            border-radius: 30px;
        }
        .decorative-line {
            width: 100px;
            height: 5px;
            background: linear-gradient(90deg, #c0392b, #f39c12);
            margin: 20px auto;
            border-radius: 10px;
        }
        .rounded-image {
            width: 80%;
            max-width: 600px;
            border-radius: 30px;
            box-shadow: 0px 4px 10px rgba(0, 0, 0, 0.3);
            margin: 20px 0;
        }
        ul {
            text-align: left;
            max-width: 600px;
            font-size: 22px;
        }
    </style>
</head>
<body>
    <div class="navbar">
        <a href="https://docs.google.com/forms/d/1kh43p-UwWmAmzgxVVvQyeZQXGBOshLdkyt3SL0mU1Ho/edit" target="_blank">Kontakt</a>
        <a href="linki.html">Linki</a>
        <a href="kontakt.html">O mnie</a>
    </div>
    
    <div class="header">Książki vs Gry</div>
    
    <div class="section">
        <h1>Wprowadzenie</h1>
        <div class="decorative-line"></div>
        <p>Czy książki są lepsze niż gry komputerowe? Choć gry wideo mają swoje atuty, to książki oferują głębsze, bardziej angażujące doświadczenie.</p>
        <img src="books.jpg" alt="Obraz książek" class="rounded-image">
    </div>
    
    <div class="section">
        <h2>Dlaczego książki są lepsze?</h2>
        <div class="decorative-line"></div>
        <ul>
            <li><strong>Rozwój wyobraźni</strong> - Książki zmuszają do wyobrażenia sobie świata, postaci i wydarzeń.</li>
            <li><strong>Głębia treści</strong> - Książki oferują bogate historie i głębokie przemyślenia.</li>
            <li><strong>Relaksacja</strong> - Czytanie sprzyja relaksowi i pomaga odpocząć od technologii.</li>
            <li><strong>Emocjonalne zaangażowanie</strong> - Książki potrafią poruszyć i zmienić sposób myślenia.</li>
            <li><strong>Poszerzanie wiedzy</strong> - Książki to źródło wiedzy na niemal każdy temat, od nauki po literaturę klasyczną.</li>
        </ul>
    </div>
    
    <div class="section image-section" style="background-image: url('library.jpg');">
        <h2>Podsumowanie</h2>
        <div class="decorative-line"></div>
        <p>Chociaż gry komputerowe mogą być wciągające, to książki oferują nieporównywalnie głębsze przeżycia, które rozwijają naszą wyobraźnię i umiejętności intelektualne.</p>
        <img src="reading_graphic.jpg" alt="Porównanie książek i gier" class="rounded-image">
    </div>
    
    <div class="section">
        <h2>Linki</h2>
        <div class="decorative-line"></div>
        <ul>
            <li><a href="https://www.empik.com" target="_blank">Empik - Książki online</a></li>
            <li><a href="https://lubimyczytac.pl" target="_blank">Lubimyczytać - Społeczność książkowa</a></li>
            <li><a href="https://www.booklovers.pl" target="_blank">Booklovers - Recenzje książek</a></li>
            <li><a href="https://www.biblioteka.pl" target="_blank">Biblioteka - Katalog książek</a></li>
        </ul>
    </div>

    <footer>
        <p>&copy; 2025 Barbara Dajka. Wszelkie prawa zastrzeżone.</p>
        <p><strong>Kontakt:</strong> 890653256</p>
    </footer>
</body>
</html>
