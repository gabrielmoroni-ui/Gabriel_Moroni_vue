<template>
  <section class="help-container">
    <!-- BANNER FULLSCREEN -->
    <header class="hero">
      <div class="hero-content">
        <h1 class="hero-title">
          Entre em <span>Contato</span>
        </h1>
        <p class="hero-sub">Suporte rápido • Atendimento profissional • Compra segura</p>
      </div>
    </header>

    <!-- CARD ORGANIZADO -->
    <main class="main-content">
      <section class="info-card">
        <h2>Informações de Contato</h2>
        <hr />

        <div class="info-block">
          <h3>Horário de Atendimento</h3>
          <p>Segunda — Domingo: <strong>10:00 — 22:00</strong></p>
        </div>

        <div class="info-block">
          <h3>Contatos</h3>
          <ul>
            <li><strong>Instagram:</strong> @GamelyOficial</li>
            <li><strong>Whatsapp:</strong> (11) 91320-5322</li>
            <li><strong>E-mail:</strong> contato@gamely.com</li>
          </ul>
        </div>
      </section>
    </main>

    <!-- RODAPÉ -->
    <footer class="footer">
      <div class="footer-inner">
        <div class="footer-col">
          <h4>Gamely</h4>
          <p>Compra segura e garantida. Entregas rápidas e confiáveis.</p>
        </div>

        <div class="footer-col">
          <h4>Categorias</h4>
          <ul>
            <li>Jogos Steam</li>
            <li>Jogos PS4 / PS5</li>
            <li>Jogos Xbox</li>
            <li>Pacotes de Jogos</li>
          </ul>
        </div>

        <div class="footer-col">
          <h4>Ajuda</h4>
          <ul>
            <li>Dúvidas</li>
            <li>Contato</li>
            <li>Termos de Uso</li>
            <li>Política de Reembolso</li>
          </ul>
        </div>
      </div>

      <div class="footer-bottom">
        <p>© 2025 Gamely – Todos os Direitos Reservados</p>
      </div>
    </footer>
  </section>
</template>

<style scoped>
/* GLOBAL RESET */
:global(html, body) {
  margin: 0;
  padding: 0;
  width: 100%;
  min-height: 100vh;
  background: #050505;
  overflow-x: hidden;
}

/* CONTAINER */
.help-container {
  width: 100%;
  min-height: 100vh;
  background: #050505;
  color: #fff;
  font-family: 'Poppins', sans-serif;
}

/* ============ HERO (Organizado) ============ */
.hero {
  width: 100%;
  height: 60vh;
  min-height: 340px;
  background: linear-gradient(180deg, #0b0b0b 0%, #111 70%);
  display: flex;
  align-items: center;
  justify-content: center;
  text-align: center;
  padding: 0 20px;
}

.hero-title {
  font-size: clamp(2rem, 5vw, 3.4rem);
  font-weight: 700;
  margin: 0;
}

.hero-title span {
  color: #b300ff;
}

.hero-sub {
  margin-top: 10px;
  color: #ccc;
}

/* ============ CARD ORGANIZADO ============ */
.main-content {
  width: 100%;
  padding: 40px 0;
  display: flex;
  justify-content: center;
}

.info-card {
  width: 92%;
  max-width: 800px;
  background: #141414;
  padding: 35px;
  border-radius: 16px;
  box-shadow: 0 4px 20px rgba(179, 0, 255, 0.2);
}

.info-card h2 {
  margin: 0 0 6px 0;
  color: #b300ff;
}

.info-card hr {
  border: none;
  height: 1px;
  background: #333;
  margin: 10px 0 20px 0;
}

/* cada bloco organizado */
.info-block {
  margin-bottom: 30px;
}

.info-block h3 {
  margin: 0 0 8px 0;
}

.info-block ul {
  padding: 0;
  list-style: none;
}

.info-block li {
  margin-bottom: 8px;
  color: #ccc;
}

/* ============ FOOTER ============ */
.footer {
  width: 100%;
  background: #0d0d0d;
  padding-top: 40px;
  margin-top: 30px;
}

.footer-inner {
  max-width: 1100px;
  margin: auto;
  padding: 0 20px;
  display: flex;
  gap: 30px;
  justify-content: space-between;
  flex-wrap: wrap;
}

.footer-col {
  min-width: 180px;
}

.footer-col h4 {
  color: #b300ff;
  margin-bottom: 10px;
}

.footer-col ul {
  list-style: none;
  padding: 0;
}

.footer-col li {
  margin-bottom: 8px;
  color: #ccc;
}

.footer-bottom {
  text-align: center;
  padding: 18px 0;
  color: #777;
  font-size: 0.9rem;
}
</style>
