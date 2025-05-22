<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <meta name="description" content="VM Solutions - Tecnologia com Inteligência e Segurança. Serviços de Pentest, Cibersegurança, SOC e Monitoramento de Rede." />
  <title>VM Solutions</title>
  <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@400;600&display=swap" rel="stylesheet">
  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: 'Montserrat', sans-serif;
    }
    body {
      background-color: #0a0f2c;
      color: #fff;
      line-height: 1.6;
    }
    header {
      background: #091a35;
      padding: 1rem 2rem;
      display: flex;
      justify-content: space-between;
      align-items: center;
    }
    header h1 {
      color: #00aaff;
    }
    nav a {
      color: #fff;
      margin-left: 1rem;
      text-decoration: none;
    }
    .hero {
      text-align: center;
      padding: 4rem 2rem;
      background: linear-gradient(145deg, #091a35, #0a0f2c);
    }
    .hero h2 {
      font-size: 2.5rem;
      margin-bottom: 1rem;
    }
    .hero p {
      font-size: 1.2rem;
      max-width: 700px;
      margin: auto;
    }
    .section {
      padding: 4rem 2rem;
    }
    .section h3 {
      color: #00aaff;
      margin-bottom: 1.5rem;
    }
    .cards {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 2rem;
    }
    .card {
      background: #11173d;
      padding: 1.5rem;
      border-radius: 10px;
      border-left: 4px solid #00aaff;
    }
    footer {
      background: #091a35;
      text-align: center;
      padding: 2rem;
      margin-top: 4rem;
    }
  </style>
</head>
<body>
  <header>
    <h1>VM Solutions</h1>
    <nav>
      <a href="#sobre">Sobre</a>
      <a href="#servicos">Serviços</a>
      <a href="#contato">Contato</a>
    </nav>
  </header>

  <section class="hero">
    <h2>Tecnologia com Inteligência e Segurança</h2>
    <p>Especialistas em Pentest, Cibersegurança, SOC e Monitoramento de Redes. Proteja sua empresa com quem entende do assunto.</p>
  </section>

  <section class="section" id="sobre">
    <h3>Sobre a VM Solutions</h3>
    <p>A VM Solutions é uma empresa especializada em soluções de segurança da informação. Atuamos com serviços estratégicos para garantir a integridade e a proteção dos ativos digitais das organizações.</p>
  </section>

  <section class="section" id="servicos">
    <h3>Serviços</h3>
    <div class="cards">
      <div class="card">
        <h4>Pentest Profissional</h4>
        <p>Identificação de vulnerabilidades através de testes de intrusão controlados.</p>
      </div>
      <div class="card">
        <h4>Cibersegurança</h4>
        <p>Abordagens ofensivas e defensivas para proteger seus sistemas e dados.</p>
      </div>
      <div class="card">
        <h4>SOC 24/7</h4>
        <p>Centro de operações de segurança para monitoramento e resposta a incidentes em tempo real.</p>
      </div>
      <div class="card">
        <h4>Monitoramento de Rede</h4>
        <p>Acompanhamento contínuo de tráfego e integridade de rede com alertas inteligentes.</p>
      </div>
    </div>
  </section>

  <section class="section" id="contato">
    <h3>Contato</h3>
    <p>Entre em contato conosco pelos canais abaixo:</p>
    <p>Email: <a href="mailto:contato@vmsolut.com.br" style="color:#00aaff">contato@vmsolut.com.br</a></p>
    <p>Email de suporte: <a href="mailto:suporte@vmsolut.com.br" style="color:#00aaff">suporte@vmsolut.com.br</a></p>
  </section>

  <footer>
    <p>&copy; 2025 VM Solutions. Todos os direitos reservados.</p>
  </footer>
</body>
</html>
