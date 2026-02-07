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
