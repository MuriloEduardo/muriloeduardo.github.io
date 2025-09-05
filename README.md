<!-- Bootstrap 5 -->
<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">

<!-- Estilo customizado -->
<style>
  .markdown-body {
    margin: inherit;
    padding: inherit;
    max-width: inherit;
  }
  body {
    font-family: 'Inter', sans-serif;
    background: #f8f9fa;
    color: #212529;
  }
  h1:not(.hero h1) {
    display: none;
  }
  .hero {
    background: linear-gradient(135deg, #4facfe 0%, #00f2fe 100%);
    color: white;
    text-align: center;
    padding: 6rem 2rem;
    border-radius: 0 0 50% 50% / 10%;
  }
  .hero h1 {
    font-size: 3rem;
    font-weight: 800;
  }
  .btn-cta {
    font-size: 1.2rem;
    padding: 0.8rem 2rem;
    border-radius: 50px;
  }
  .card {
    border-radius: 1.5rem;
    box-shadow: 0 8px 20px rgba(0,0,0,0.08);
  }
  .section {
    padding: 5rem 2rem;
  }
  .section-title {
    font-size: 2.2rem;
    font-weight: 700;
    text-align: center;
    margin-bottom: 3rem;
  }
  footer {
    background: #212529;
    color: #fff;
    padding: 2rem;
    text-align: center;
    border-radius: 50% 50% 0 0 / 10%;
  }
</style>

<!-- Hero -->
<div class="hero shadow">
  <h1>🏨 Transforme seu WhatsApp em um atendente 24h com IA</h1>
  <p class="lead mt-3">Mais reservas, hóspedes satisfeitos e menos tempo perdido respondendo perguntas repetitivas.</p>
  <a href="#lead-form" class="btn btn-warning btn-lg btn-cta mt-4">📲 Quero testar grátis agora</a>
</div>

---

<!-- Problema -->
<div class="section">
  <h2 class="section-title">❌ O problema</h2>
  <div class="row text-center">
    <div class="col-md-3">📩 Mensagens sem resposta durante a noite</div>
    <div class="col-md-3">🔁 Perguntas repetitivas todos os dias</div>
    <div class="col-md-3">⏱️ Perda de reservas pela demora</div>
    <div class="col-md-3">⭐ Avaliações negativas pela falta de agilidade</div>
  </div>
</div>

---

<!-- Solução -->
<div class="section bg-light">
  <h2 class="section-title">🚀 Nossa solução</h2>
  <div class="row g-4">
    <div class="col-md-3 text-center">🤖 <br><b>Assistente Virtual</b><br> Responde 24/7 em segundos</div>
    <div class="col-md-3 text-center">📅 <br><b>Reservas diretas</b><br> Sem perder clientes</div>
    <div class="col-md-3 text-center">🌍 <br><b>Múltiplos idiomas</b><br> Ideal para turistas</div>
    <div class="col-md-3 text-center">📊 <br><b>Relatórios</b><br> Insights de hóspedes</div>
  </div>
</div>

---

<!-- Prova Social -->
<div class="section">
  <h2 class="section-title">💬 O que dizem nossos clientes</h2>
  <blockquote class="pt-3 rounded shadow blockquote text-center text-light">
    “Desde que ativamos o assistente, 80% das dúvidas são respondidas automaticamente e aumentamos em 25% nossas reservas diretas.”
    <footer class="blockquote-footer mt-3">Hotel Cliente <cite title="Source Title">Pousada Exemplo</cite></footer>
  </blockquote>
</div>

---

<!-- Planos -->
<div class="section bg-light">
  <h2 class="section-title">💡 Escolha seu plano</h2>
  <div class="row g-4">
    <div class="col-md-4">
      <div class="card p-4 text-center">
        <h4>🔹 Básico</h4>
        <p>WhatsApp automatizado 24h</p>
      </div>
    </div>
    <div class="col-md-4">
      <div class="card p-4 text-center">
        <h4>🔸 Avançado</h4>
        <p>+ Reservas diretas + relatórios</p>
      </div>
    </div>
    <div class="col-md-4">
      <div class="card p-4 text-center">
        <h4>🌟 Premium</h4>
        <p>+ Upsell automático + IA customizada</p>
      </div>
    </div>
  </div>
  <div class="text-center mt-4">
    <a href="#lead-form" class="btn btn-success btn-lg btn-cta">👉 Quero começar agora</a>
  </div>
</div>

---

<!-- Captura de Leads -->
<div id="lead-form" class="section">
  <h2 class="section-title">📩 Receba sua demonstração grátis</h2>
  <form class="row g-3 justify-content-center">
    <div class="col-md-4">
      <input type="text" class="form-control p-3" placeholder="Seu Nome" required>
    </div>
    <div class="col-md-4">
      <input type="email" class="form-control p-3" placeholder="Seu E-mail" required>
    </div>
    <div class="col-md-4">
      <input type="tel" class="form-control p-3" placeholder="WhatsApp" required>
    </div>
    <div class="col-md-4">
      <select class="form-select p-3">
        <option selected>Tipo de negócio</option>
        <option>Hotel</option>
        <option>Pousada</option>
        <option>Airbnb</option>
      </select>
    </div>
    <div class="col-md-4 text-center">
      <button type="submit" class="btn btn-primary btn-lg btn-cta w-100 mt-5">Receber demonstração grátis</button>
    </div>
  </form>
</div>

---

<!-- Rodapé -->
<footer class="shadow">
  <h4>⚡ Não perca mais reservas por falta de atendimento</h4>
  <p>Tenha um número exclusivo no WhatsApp com IA em até 48h.</p>
  <a href="#lead-form" class="btn btn-warning btn-lg btn-cta mt-3">📲 Quero meu assistente agora</a>
</footer>
