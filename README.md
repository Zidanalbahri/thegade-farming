<!DOCTYPE html><html lang="id">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>The Gade Integrated Farming</title>
  <meta name="description" content="The Gade Integrated Farming – pertanian terpadu berkelanjutan, inovatif, dan ramah lingkungan." />
  <style>
    :root {
      --green-dark: #1f4d2b;
      --green-main: #2f7d3b;
      --green-light: #e9f5ec;
      --white: #ffffff;
    }* {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
  font-family: "Segoe UI", Tahoma, Geneva, Verdana, sans-serif;
}

body {
  background-color: var(--white);
  color: #333;
  line-height: 1.6;
}

header {
  background: linear-gradient(rgba(0,0,0,0.45), rgba(0,0,0,0.45)), url('hero.jpg') center/cover no-repeat;
  color: var(--white);
  min-height: 100vh;
  display: flex;
  align-items: center;
  justify-content: center;
  text-align: center;
  padding: 20px;
}

header h1 {
  font-size: 3rem;
  margin-bottom: 15px;
}

header p {
  font-size: 1.2rem;
  max-width: 700px;
  margin: 0 auto 25px;
}

.btn {
  display: inline-block;
  background-color: var(--green-main);
  color: var(--white);
  padding: 12px 28px;
  border-radius: 30px;
  text-decoration: none;
  font-weight: 600;
  transition: background 0.3s ease;
}

.btn:hover {
  background-color: var(--green-dark);
}

section {
  padding: 70px 20px;
  max-width: 1100px;
  margin: auto;
}

section h2 {
  text-align: center;
  color: var(--green-dark);
  margin-bottom: 40px;
  font-size: 2.2rem;
}

.about p {
  text-align: center;
  max-width: 800px;
  margin: auto;
  font-size: 1.05rem;
}

.services {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
  gap: 25px;
}

.card {
  background: var(--green-light);
  padding: 30px 25px;
  border-radius: 18px;
  text-align: center;
  box-shadow: 0 8px 20px rgba(0,0,0,0.08);
}

.card h3 {
  margin-bottom: 15px;
  color: var(--green-main);
}

.card p {
  font-size: 0.95rem;
}

.contact {
  background-color: var(--green-light);
  border-radius: 24px;
  padding: 50px 25px;
  text-align: center;
}

.contact p {
  margin-bottom: 20px;
  font-size: 1rem;
}

footer {
  background-color: var(--green-dark);
  color: var(--white);
  text-align: center;
  padding: 18px 10px;
  font-size: 0.9rem;
}

@media (max-width: 768px) {
  header h1 {
    font-size: 2.3rem;
  }
  header p {
    font-size: 1rem;
  }
}

  </style>
</head>
<body>  <!-- HERO -->  <header>
    <div>
      <h1>The Gade Integrated Farming</h1>
      <p>Pertanian terpadu yang berkelanjutan, mengintegrasikan inovasi, lingkungan, dan pemberdayaan masyarakat.</p>
      <a href="#about" class="btn">Pelajari Lebih Lanjut</a>
    </div>
  </header>  <!-- ABOUT -->  <section id="about" class="about">
    <h2>Tentang Kami</h2>
    <p>
      The Gade Integrated Farming adalah inisiatif pertanian terpadu yang mengedepankan sistem produksi berkelanjutan,
      ramah lingkungan, dan bernilai ekonomi. Kami mengintegrasikan sektor pertanian, peternakan, dan pengelolaan limbah
      untuk menciptakan ekosistem pertanian yang efisien dan berdampak positif.
    </p>
  </section>  <!-- SERVICES -->  <section>
    <h2>Program & Kegiatan</h2>
    <div class="services">
      <div class="card">
        <h3>Pertanian Terpadu</h3>
        <p>Pengelolaan tanaman berbasis sistem terpadu untuk hasil optimal dan berkelanjutan.</p>
      </div>
      <div class="card">
        <h3>Green House</h3>
        <p>Produksi hortikultura dengan kontrol lingkungan untuk kualitas dan kontinuitas panen.</p>
      </div>
      <div class="card">
        <h3>Pendampingan & Edukasi</h3>
        <p>Pelatihan dan pendampingan bagi petani dan masyarakat sekitar.</p>
      </div>
    </div>
  </section>  <!-- CONTACT -->  <section>
    <div class="contact">
      <h2>Hubungi Kami</h2>
      <p>Tertarik bekerja sama atau ingin tahu lebih lanjut tentang program kami?</p>
      <a href="mailto:info@gadefarming.id" class="btn">Email Kami</a>
    </div>
  </section>  <!-- FOOTER -->  <footer>
    <p>&copy; 2026 The Gade Integrated Farming. All rights reserved.</p>
  </footer></body>
</html>
