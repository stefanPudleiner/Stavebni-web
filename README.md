<!DOCTYPE html>
<html lang="cs">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Štefan Pudleiner – Builder</title>
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', sans-serif;
      background-color: #f4f4f4;
      color: #222;
    }

    header {
      background-color: #1a1a1a;
      color: white;
      padding: 2rem;
      text-align: center;
    }

    header h1 {
      margin: 0;
      font-size: 2.5rem;
    }

    header p {
      font-size: 1.2rem;
      color: #aaa;
    }

    nav {
      background-color: #333;
      display: flex;
      justify-content: center;
    }

    nav a {
      color: white;
      padding: 1rem;
      text-decoration: none;
      transition: background 0.3s;
    }

    nav a:hover {
      background-color: #555;
    }

    section {
      max-width: 900px;
      margin: 2rem auto;
      padding: 1rem;
      background: white;
      box-shadow: 0 0 10px rgba(0,0,0,0.05);
      border-radius: 6px;
    }

    section h2 {
      color: #003366;
      margin-top: 0;
    }

    footer {
      background-color: #1a1a1a;
      color: white;
      text-align: center;
      padding: 1rem;
      margin-top: 3rem;
    }
  </style>
</head>
<body>

  <header>
    <h1>Štefan Pudleiner</h1>
    <p>Builder | Stavební práce</p>
  </header>

  <nav>
    <a href="#vizitka">Vizitka</a>
    <a href="#projekty">Projekty</a>
    <a href="#kontakt">Kontakt</a>
  </nav>

  <section id="vizitka">
    <h2>Vizitka</h2>
    <p>Jsem odborník na stavební práce s důrazem na kvalitu, spolehlivost a estetiku. Nabízím kompletní služby v oblasti výstavby, rekonstrukcí a úprav interiérů i exteriérů.</p>
  </section>

  <section id="projekty">
    <h2>Vybrané Projekty</h2>
    <ul>
      <li>Rodinný dům – Brno (2024)</li>
      <li>Rekonstrukce bytu – Praha (2023)</li>
      <li>Zámková dlažba a terasa – Znojmo (2022)</li>
    </ul>
  </section>

  <section id="kontakt">
    <h2>Kontakt</h2>
    <p>Email: <a href="mailto:info@pudleinerstavby.cz">info@pudleinerstavby.cz</a></p>
    <p>Telefon: +420 777 123 456</p>
  </section>

  <footer>
    &copy; 2025 Štefan Pudleiner. Všechna práva vyhrazena.
  </footer>

</body>
</html>
