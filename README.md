# Portifolio-site
index.html
<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Luis Gustavo | Desenvolvedor Web</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>

  <nav class="navbar">
    <div class="container">
      <span class="logo">LuisDev</span>
      <ul class="nav-links">
        <li><a href="#sobre">Sobre</a></li>
        <li><a href="#projetos">Projetos</a></li>
        <li><a href="#contato">Contato</a></li>
      </ul>
    </div>
  </nav>

  <header class="hero">
    <div class="container">
      <h1>Luis Gustavo</h1>
      <p>Desenvolvedor Web Júnior &bull; PHP &bull; JavaScript &bull; Python</p>
      <a href="#projetos" class="btn">Ver Projetos</a>
    </div>
  </header>

  <main class="container">
    <section id="sobre">
      <h2>Sobre Mim</h2>
      <p>Olá! Sou um desenvolvedor focado em criar soluções web eficientes. Tenho experiência com PHP para backend, JavaScript para interfaces dinâmicas e Python para automação e análise de dados. Estou sempre buscando aprender novas tecnologias e escrever código limpo.</p>
    </section>

    <section id="projetos">
      <h2>Projetos</h2>
      <div class="projects-grid">
        <article class="card">
          <h3>Sistema CRUD em PHP</h3>
          <p>Gerenciamento de dados com MySQL e interface responsiva.</p>
        </article>
        <article class="card">
          <h3>API REST com Slim</h3>
          <p>Construção de endpoints seguros e eficientes para aplicações web.</p>
        </article>
        <article class="card">
          <h3>Análise de Dados com Python</h3>
          <p>Processamento de dados e visualização de informações com Pandas e Matplotlib.</p>
        </article>
      </div>
    </section>
  </main>

  <footer id="contato">
    <div class="container">
      <p>&copy; <span id="year"></span> Luis Gustavo. Todos os direitos reservados.</p>
      <p>Contato: <a href="mailto:gustavoluis.v.c.1016@gmail.com">gustavoluis.v.c.1016@gmail.com</a></p>
    </div>
  </footer>

  <script src="script.js"></script>
</body>
</html>

style.css
:root {
  --primary-color: #2563eb; /* Azul moderno */
  --bg-color: #f8f9fa;
  --text-color: #333;
  --card-bg: #ffffff;
  --nav-bg: #1f2937;
}

* {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
}

body {
  font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
  background-color: var(--bg-color);
  color: var(--text-color);
  line-height: 1.6;
}

.container {
  width: 90%;
  max-width: 1000px;
  margin: 0 auto;
}

/* Navegação */
.navbar {
  background-color: var(--nav-bg);
  color: white;
  padding: 1rem 0;
  position: sticky;
  top: 0;
  z-index: 100;
}

.navbar .container {
  display: flex;
  justify-content: space-between;
  align-items: center;
}

.nav-links {
  list-style: none;
  display: flex;
  gap: 20px;
}

.nav-links a {
  color: white;
  text-decoration: none;
  font-weight: bold;
  transition: color 0.3s;
}

.nav-links a:hover {
  color: var(--primary-color);
}

/* Header / Hero */
.hero {
  background: linear-gradient(135deg, #1f2937 0%, #111827 100%);
  color: white;
  text-align: center;
  padding: 80px 20px;
}

.hero h1 {
  font-size: 2.5rem;
  margin-bottom: 10px;
}

.hero p {
  font-size: 1.2rem;
  color: #d1d5db;
  margin-bottom: 30px;
}

.btn {
  display: inline-block;
  background-color: var(--primary-color);
  color: white;
  padding: 10px 25px;
  text-decoration: none;
  border-radius: 5px;
  font-weight: bold;
  transition: background 0.3s;
}

.btn:hover {
  background-color: #1d4ed8;
}

/* Seções */
section {
  padding: 60px 0;
}

h2 {
  border-bottom: 3px solid var(--primary-color);
  display: inline-block;
  margin-bottom: 30px;
  padding-bottom: 5px;
}

/* Projetos Grid */
.projects-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
  gap: 20px;
}

.card {
  background: var(--card-bg);
  padding: 20px;
  border-radius: 8px;
  box-shadow: 0 4px 6px rgba(0,0,0,0.1);
  transition: transform 0.2s;
}

.card:hover {
  transform: translateY(-5px);
}

.card h3 {
  color: var(--primary-color);
  margin-bottom: 10px;
}

/* Footer */
footer {
  background-color: #1f2937;
  color: white;
  text-align: center;
  padding: 20px 0;
  margin-top: 40px;
}

footer a {
  color: var(--primary-color);
  text-decoration: none;
}

/* Responsividade simples */
@media (max-width: 600px) {
  .hero h1 { font-size: 2rem; }
  .nav-links { display: none; } /* Oculta links em telas muito pequenas para simplificar */
}

script.js

:root {
  --primary-color: #2563eb; /* Azul moderno */
  --bg-color: #f8f9fa;
  --text-color: #333;
  --card-bg: #ffffff;
  --nav-bg: #1f2937;
}

* {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
}

body {
  font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
  background-color: var(--bg-color);
  color: var(--text-color);
  line-height: 1.6;
}

.container {
  width: 90%;
  max-width: 1000px;
  margin: 0 auto;
}

/* Navegação */
.navbar {
  background-color: var(--nav-bg);
  color: white;
  padding: 1rem 0;
  position: sticky;
  top: 0;
  z-index: 100;
}

.navbar .container {
  display: flex;
  justify-content: space-between;
  align-items: center;
}

.nav-links {
  list-style: none;
  display: flex;
  gap: 20px;
}

.nav-links a {
  color: white;
  text-decoration: none;
  font-weight: bold;
  transition: color 0.3s;
}

.nav-links a:hover {
  color: var(--primary-color);
}

/* Header / Hero */
.hero {
  background: linear-gradient(135deg, #1f2937 0%, #111827 100%);
  color: white;
  text-align: center;
  padding: 80px 20px;
}

.hero h1 {
  font-size: 2.5rem;
  margin-bottom: 10px;
}

.hero p {
  font-size: 1.2rem;
  color: #d1d5db;
  margin-bottom: 30px;
}

.btn {
  display: inline-block;
  background-color: var(--primary-color);
  color: white;
  padding: 10px 25px;
  text-decoration: none;
  border-radius: 5px;
  font-weight: bold;
  transition: background 0.3s;
}

.btn:hover {
  background-color: #1d4ed8;
}

/* Seções */
section {
  padding: 60px 0;
}

h2 {
  border-bottom: 3px solid var(--primary-color);
  display: inline-block;
  margin-bottom: 30px;
  padding-bottom: 5px;
}

/* Projetos Grid */
.projects-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
  gap: 20px;
}

.card {
  background: var(--card-bg);
  padding: 20px;
  border-radius: 8px;
  box-shadow: 0 4px 6px rgba(0,0,0,0.1);
  transition: transform 0.2s;
}

.card:hover {
  transform: translateY(-5px);
}

.card h3 {
  color: var(--primary-color);
  margin-bottom: 10px;
}

/* Footer */
footer {
  background-color: #1f2937;
  color: white;
  text-align: center;
  padding: 20px 0;
  margin-top: 40px;
}

footer a {
  color: var(--primary-color);
  text-decoration: none;
}

/* Responsividade simples */
@media (max-width: 600px) {
  .hero h1 { font-size: 2rem; }
  .nav-links { display: none; } /* Oculta links em telas muito pequenas para simplificar */
}

script.js

document.addEventListener('DOMContentLoaded', () => {
    console.log("Portfólio carregado com sucesso!");

    // Atualizar o ano automaticamente no rodapé
    const yearSpan = document.getElementById('year');
    if (yearSpan) {
        yearSpan.textContent = new Date().getFullYear();
    }

    // Exemplo: Log de informações do usuário
    const owner = "Luis Gustavo";
    console.log(`Bem-vindo ao portfólio de ${owner}`);
});
