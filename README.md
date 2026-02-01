<!DOCTYPE html>
<html lang="uz">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>EMRO Mobile</title>
<style>
:root {
  --neon: #00B7FF;
  --bg: #05080D;
}

* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: 'Segoe UI', sans-serif;
}

body {
  background: var(--bg);
  color: white;
}

/* HERO */
.hero {
  height: 100vh;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  text-align: center;
}

.hero h1 {
  font-size: 3rem;
  color: var(--neon);
  text-shadow: 0 0 25px var(--neon);
}

.hero p {
  margin: 15px 0;
  opacity: 0.8;
}

.btn {
  margin-top: 20px;
  padding: 15px 35px;
  border: 2px solid var(--neon);
  color: var(--neon);
  text-decoration: none;
  border-radius: 50px;
  box-shadow: 0 0 15px var(--neon);
  transition: 0.3s;
}

.btn:hover {
  background: var(--neon);
  color: black;
}

/* SECTION */
.section {
  padding: 80px 10%;
  text-align: center;
}

.icons {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(180px,1fr));
  gap: 30px;
  margin-top: 40px;
}

.icon-box {
  border: 1px solid var(--neon);
  padding: 30px;
  border-radius: 20px;
  box-shadow: 0 0 20px rgba(0,183,255,0.3);
}

.icon-box h3 {
  margin-top: 10px;
  color: var(--neon);
}

/* FOOTER */
footer {
  padding: 40px;
  text-align: center;
  opacity: 0.6;
}
</style>
</head>
<body>

<!-- HERO -->
<section class="hero">
  <h1>EMRO MOBILE</h1>
  <p>iPhone | Samsung | Muddatli to‘lov | Trade-in</p>
  <a href="https://t.me/Emromobile" class="btn">Telegram orqali yozish</a>
</section>

<!-- SERVICES -->
<section class="section">
  <h2>Bizning afzalliklar</h2>
  <div class="icons">
    <div class="icon-box">
      <h3>Original</h3>
      <p>Kafolatlangan mahsulotlar</p>
    </div>
    <div class="icon-box">
      <h3>Muddatli to‘lov</h3>
      <p>Qulay shartlar</p>
    </div>
    <div class="icon-box">
      <h3>Trade-in</h3>
      <p>Eski telefonni topshir</p>
    </div>
    <div class="icon-box">
      <h3>Yetkazib berish</h3>
      <p>Tez va ishonchli</p>
    </div>
  </div>
</section>

<footer>
  © EMRO Mobile — Premium telefonlar do‘koni
</footer>

</body>
</html>
