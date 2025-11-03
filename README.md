# 👨‍💻 Portfólio – Paulo Isaque  

Bem-vindo ao meu portfólio de projetos!  
Sou um desenvolvedor em transição de carreira, apaixonado por **tecnologia e desenvolvimento front-end**.  
Aqui estão alguns dos projetos que venho criando ao longo da minha jornada de aprendizado, aplicando na prática tudo o que estudo em **HTML**, **CSS**, **JavaScript**, **React.js** e **Styled-components**.  

Cada projeto representa um passo na minha evolução como programador — sempre buscando escrever códigos limpos, responsivos e com boas práticas. 🚀  

---

## 🎬 DevMovies  
Aplicação web para explorar e favoritar filmes utilizando dados de uma API pública.  
Desenvolvido em **React**, o projeto conta com uma interface moderna e intuitiva, permitindo ao usuário pesquisar títulos, visualizar sinopses, notas e salvar seus filmes favoritos.  

**✨ Principais funcionalidades:**  
- Busca dinâmica de filmes por título  
- Exibição de detalhes e notas de avaliação  
- Salvamento de favoritos  

**🧠 Tecnologias utilizadas:**  
- React + Vite  
- JavaScript (ES6+)  
- CSS Modules  
- The Movie Database (TMDB API)  

🔗 [Ver no GitHub](https://github.com/paulo2602/DevMovies)

---

## 🛒 Loja de Produtos Apple  
Landing page de uma loja fictícia de produtos Apple, com **slider automático**, **animações suaves** e **layout totalmente responsivo**.  
Desenvolvido com foco em boas práticas de design e usabilidade.  

**🧠 Tecnologias:** HTML, CSS, JavaScript  
🔗 [Ver no GitHub](https://github.com/paulo2602/Projeto-Loja-App)

---

## 🎮 Landing Page Mario Bross  
Página inspirada no universo do **Mario Bros**, criada para treinar **estrutura HTML**, **posicionamento** e **estilização com CSS**.  
Um projeto divertido e ótimo para reforçar fundamentos visuais e semânticos.  

**🧠 Tecnologias:** HTML, CSS  
🔗 [Ver no GitHub](https://github.com/paulo2602/Site-para-atendimento---Mario-Bros)

---

## 💱 Conversor de Moedas  
Ferramenta simples e funcional para conversão de moedas, com campos dinâmicos e interações em tempo real.  
Excelente exercício de **lógica de programação** e **manipulação do DOM**.  

**🧠 Tecnologias:** HTML, CSS, JavaScript  
🔗 [Ver no GitHub](https://github.com/paulo2602/Conversor-de-moedas)

---

## 📦 MultiDrop – Sistema de Reembolso  
Aplicação web com múltiplas páginas, simulando um **sistema de reembolso corporativo**.  
Possui tela de login com verificação por e-mail, listagem de compras e solicitações de reembolso.  

**🧠 Tecnologias:** Vue.js, PrimeVue, JavaScript  
🔗 [Ver no GitHub](https://github.com/paulo2602/MultiDrop-reembolso)

---

## 🔢 Calculadora Simples  
Projeto prático de uma **calculadora funcional** com operações básicas, desenvolvido para reforçar **conceitos de lógica e manipulação de eventos no DOM**.  

**🧠 Tecnologias:** HTML, CSS, JavaScript  
🔗 [Ver no GitHub](https://github.com/paulo2602/Calculadora)

---

## 🌐 Wide Coverage Location  
Landing page desenvolvida com foco em **responsividade** e **organização visual**, aplicando princípios de **design limpo e layout equilibrado**.  

**🧠 Tecnologias:** HTML, CSS  
🔗 [Ver no GitHub](https://github.com/paulo2602/Projeto-Wide-coverage-location)

---

## 🚀 Sobre mim  
Sou estudante de **programação Front-End** há quase dois anos, apaixonado por criar interfaces modernas e funcionais.  
Sou **organizado, esforçado e comunicativo**, sempre buscando aprender novas tecnologias e aprimorar minhas habilidades para me tornar um desenvolvedor completo.  

---





<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Portfólio – Paulo Isaque</title>
  <style>
    :root {
      --primary: #007bff;
      --background: #0d1117;
      --card-bg: #161b22;
      --text: #e6edf3;
      --accent: #58a6ff;
      --radius: 12px;
    }

    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: 'Poppins', sans-serif;
    }

    body {
      background-color: var(--background);
      color: var(--text);
      line-height: 1.6;
      padding: 20px;
    }

    header {
      text-align: center;
      margin-bottom: 40px;
    }

    header h1 {
      font-size: 2.2rem;
      margin-bottom: 10px;
      color: var(--accent);
    }

    header p {
      color: #c9d1d9;
      font-size: 1rem;
      max-width: 600px;
      margin: 0 auto;
    }

    section {
      margin-bottom: 40px;
    }

    .project {
      background: var(--card-bg);
      border-radius: var(--radius);
      padding: 20px;
      margin-bottom: 20px;
      transition: transform 0.2s, box-shadow 0.2s;
    }

    .project:hover {
      transform: translateY(-5px);
      box-shadow: 0 4px 10px rgba(255,255,255,0.1);
    }

    .project h2 {
      color: var(--accent);
      margin-bottom: 10px;
      font-size: 1.3rem;
    }

    .project p {
      margin-bottom: 10px;
      color: #c9d1d9;
    }

    .technologies {
      font-size: 0.9rem;
      color: #8b949e;
      margin-bottom: 10px;
    }

    a {
      color: var(--primary);
      text-decoration: none;
      font-weight: 500;
    }

    a:hover {
      text-decoration: underline;
    }

    footer {
      text-align: center;
      margin-top: 50px;
      color: #8b949e;
      font-size: 0.9rem;
    }
  </style>
</head>
<body>

  <header>
    <h1>👨‍💻 Portfólio – Paulo Isaque</h1>
    <p>Sou um desenvolvedor em transição de carreira, apaixonado por tecnologia e desenvolvimento front-end.  
    Aqui estão alguns dos projetos que venho criando, aplicando meus estudos em HTML, CSS, JavaScript, React.js e Styled-components.</p>
  </header>

  <section>
    <div class="project">
      <h2>🎬 DevMovies</h2>
      <p>Aplicação web para explorar e favoritar filmes utilizando dados de uma API pública. Desenvolvido em React com uma interface moderna e intuitiva.</p>
      <p><strong>Principais funcionalidades:</strong> Busca dinâmica, exibição de detalhes e salvamento de favoritos.</p>
      <p class="technologies">🧠 Tecnologias: React + Vite, JavaScript (ES6+), CSS Modules, TMDB API</p>
      <a href="https://github.com/paulo2602/DevMovies" target="_blank">🔗 Ver no GitHub</a>
    </div>

    <div class="project">
      <h2>🛒 Loja de Produtos Apple</h2>
      <p>Landing page fictícia com slider automático, animações suaves e layout responsivo.</p>
      <p class="technologies">🧠 Tecnologias: HTML, CSS, JavaScript</p>
      <a href="https://github.com/paulo2602/Projeto-Loja-App" target="_blank">🔗 Ver no GitHub</a>
    </div>

    <div class="project">
      <h2>🎮 Landing Page Mario Bross</h2>
      <p>Página inspirada no universo do Mario Bros, criada para treinar estrutura HTML e estilização com CSS.</p>
      <p class="technologies">🧠 Tecnologias: HTML, CSS</p>
      <a href="https://github.com/paulo2602/Site-para-atendimento---Mario-Bros" target="_blank">🔗 Ver no GitHub</a>
    </div>

    <div class="project">
      <h2>💱 Conversor de Moedas</h2>
      <p>Ferramenta simples para conversão de moedas com campos dinâmicos e interação em tempo real.</p>
      <p class="technologies">🧠 Tecnologias: HTML, CSS, JavaScript</p>
      <a href="https://github.com/paulo2602/Conversor-de-moedas" target="_blank">🔗 Ver no GitHub</a>
    </div>

    <div class="project">
      <h2>📦 MultiDrop – Sistema de Reembolso</h2>
      <p>Aplicação simulando um sistema de reembolso corporativo, com login, listagem de compras e solicitações.</p>
      <p class="technologies">🧠 Tecnologias: Vue.js, PrimeVue, JavaScript</p>
      <a href="https://github.com/paulo2602/MultiDrop-reembolso" target="_blank">🔗 Ver no GitHub</a>
    </div>

    <div class="project">
      <h2>🔢 Calculadora Simples</h2>
      <p>Calculadora funcional com operações básicas, ideal para exercitar lógica e manipulação do DOM.</p>
      <p class="technologies">🧠 Tecnologias: HTML, CSS, JavaScript</p>
      <a href="https://github.com/paulo2602/Calculadora" target="_blank">🔗 Ver no GitHub</a>
    </div>

    <div class="project">
      <h2>🌐 Wide Coverage Location</h2>
      <p>Landing page com foco em responsividade e organização visual, aplicando princípios de design limpo.</p>
      <p class="technologies">🧠 Tecnologias: HTML, CSS</p>
      <a href="https://github.com/paulo2602/Projeto-Wide-coverage-location" target="_blank">🔗 Ver no GitHub</a>
    </div>
  </section>

  <footer>
    <p>🚀 Estudante de Front-End há quase 2 anos | Organizado • Esforçado • Comunicativo</p>
  </footer>

</body>
</html>

