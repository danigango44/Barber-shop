# Barber-shop<!DOCTYPE html>
<html lang="it">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Barber Shop Elegance</title>
  <link rel="stylesheet" href="style.css" />
</head>
<body>
  <header>
    <h1>Barber Shop Elegance</h1>
    <nav>
      <ul>
        <li><a href="#home">Home</a></li>
        <li><a href="#about">Chi Siamo</a></li>
        <li><a href="#services">Servizi</a></li>
        <li><a href="#gallery">Galleria</a></li>
        <li><a href="#booking">Prenota</a></li>
        <li><a href="#contact">Contatti</a></li>
      </ul>
    </nav>
  </header>

  <section id="home" class="hero">
    <h2>Tagli di Classe, Stile Unico</h2>
    <p>Benvenuto nel tuo nuovo barber shop di fiducia.</p>
  </section>

  <section id="about">
    <h2>Chi Siamo</h2>
    <p>Siamo professionisti con passione per lo stile maschile, da oltre 10 anni al servizio del tuo look.</p>
  </section>

  <section id="services">
    <h2>Servizi</h2>
    <ul>
      <li>Taglio Classico</li>
      <li>Rasatura Tradizionale</li>
      <li>Regolazione Barba</li>
      <li>Trattamenti Viso</li>
    </ul>
  </section>

  <section id="gallery">
    <h2>Galleria</h2>
    <p>[Inserisci qui immagini dei tuoi lavori o del negozio]</p>
  </section>

  <section id="booking">
    <h2>Prenota il tuo Appuntamento</h2>
    <form>
      <input type="text" placeholder="Nome" required />
      <input type="tel" placeholder="Telefono" required />
      <input type="datetime-local" required />
      <button type="submit">Prenota</button>
    </form>
  </section>

  <section id="contact">
    <h2>Contatti</h2>
    <p>Email: info@barbershopelegance.it</p>
    <p>Telefono: +39 333 1234567</p>
    <p>Via Roma 123, Milano</p>
  </section>

  <footer>
    <p>&copy; 2025 Barber Shop Elegance</p>
  </footer>
</body>
</html>
body {
  font-family: 'Arial', sans-serif;
  margin: 0;
  padding: 0;
  background: #f5f5f5;
  color: #333;
}

header {
  background: #222;
  color: white;
  padding: 20px;
  text-align: center;
}

nav ul {
  list-style: none;
  padding: 0;
  display: flex;
  justify-content: center;
  margin-top: 10px;
}

nav ul li {
  margin: 0 15px;
}

nav ul li a {
  color: #fff;
  text-decoration: none;
  font-weight: bold;
}

.hero {
  background: url('barber-bg.jpg') center/cover no-repeat;
  color: white;
  text-align: center;
  padding: 100px 20px;
}

section {
  padding: 40px 20px;
  max-width: 1000px;
  margin: auto;
}

form input, form button {
  display: block;
  width: 100%;
  padding: 10px;
  margin-top: 10px;
  font-size: 16px;
}

footer {
  text-align: center;
  background: #222;
  color: white;
  padding: 20px;
}
