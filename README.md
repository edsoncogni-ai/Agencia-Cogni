<!DOCTYPE html>
<html lang="pt-BR">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Agência Cogni | Google Meu Negócio</title>

<style>
:root {
    --azul-principal: #1A73E8;
    --azul-escuro: #0B4FA3;
    --laranja: #F57C00;
    --amarelo: #FBC02D;
    --cinza-bg: #F4F6F8;
    --texto: #333333;
    --whatsapp: #25D366;
}

* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: 'Arial', sans-serif;
}

body {
    background-color: var(--cinza-bg);
    color: var(--texto);
}

/* HEADER */
header {
    background: linear-gradient(135deg, var(--azul-principal), var(--azul-escuro));
    color: #fff;
    padding: 60px 20px;
    text-align: center;
}

header img {
    max-width: 220px;
    margin-bottom: 25px;
}

header h1 {
    font-size: 2.4rem;
    margin-bottom: 10px;
}

header p {
    font-size: 1.2rem;
    margin-bottom: 30px;
}

/* BOTÃO WHATSAPP */
.btn-whatsapp {
    background-color: var(--whatsapp);
    color: #fff;
    padding: 15px 35px;
    border-radius: 50px;
    text-decoration: none;
    font-size: 1.1rem;
    font-weight: bold;
    transition: 0.3s;
    display: inline-block;
}

.btn-whatsapp:hover {
    transform: scale(1.05);
    background-color: #1ebe5d;
}

/* SEÇÕES */
section {
    padding: 60px 20px;
    max-width: 1100px;
    margin: auto;
}

section h2 {
    text-align: center;
    margin-bottom: 40px;
    color: var(--azul-principal);
}

/* CARDS */
.cards {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
    gap: 25px;
}

.card {
    background-color: #fff;
    padding: 30px;
    border-radius: 14px;
    box-shadow: 0 8px 20px rgba(0,0,0,0.08);
    text-align: center;
    border-top: 6px solid var(--laranja);
}

.card h3 {
    color: var(--azul-escuro);
    margin-bottom: 15px;
}

/* CTA */
.cta {
    background: linear-gradient(135deg, var(--laranja), var(--amarelo));
    color: #fff;
    text-align: center;
    padding: 60px 20px;
    border-radius: 16px;
}

.cta h2 {
    color: #fff;
}

.cta p {
    margin: 20px 0;
    font-size: 1.1rem;
}

/* FOOTER */
footer {
    background-color: var(--azul-escuro);
    color: #fff;
    text-align: center;
    padding: 20px;
}

/* WHATSAPP FLOAT */
.whatsapp-float {
    position: fixed;
    bottom: 25px;
    right: 25px;
    background-color: var(--whatsapp);
    color: #fff;
    width: 60px;
    height: 60px;
    border-radius: 50%;
    display: flex;
    align-items: center;
    justify-content: center;
    font-size: 30px;
    text-decoration: none;
    box-shadow: 0 5px 15px rgba(0,0,0,0.3);
    transition: 0.3s;
}

.whatsapp-float:hover {
    transform: scale(1.1);
}
</style>
</head>

<body>

<header>
    <img src="logo-cogni.png" alt="Agência Cogni">
    <h1>Especialistas em Google Meu Negócio</h1>
    <p>Posicione sua empresa no topo do Google e atraia mais clientes</p>

    <a class="btn-whatsapp"
       href="https://wa.me/5511932057575?text=Olá!%20Quero%20informações%20sobre%20Google%20Meu%20Negócio."
       target="_blank">
       📲 Falar no WhatsApp
    </a>
</header>

<section>
    <h2>O que a Agência Cogni faz</h2>

    <div class="cards">
        <div class="card">
            <h3>Criação do Perfil</h3>
            <p>Configuração profissional do seu Google Meu Negócio.</p>
        </div>

        <div class="card">
            <h3>Otimização Local</h3>
            <p>Mais visibilidade, cliques e clientes da sua região.</p>
        </div>

        <div class="card">
            <h3>Gestão de Avaliações</h3>
            <p>Estratégias para conquistar confiança e autoridade.</p>
        </div>

        <div class="card">
            <h3>Postagens Estratégicas</h3>
            <p>Conteúdo que gera engajamento e conversões.</p>
        </div>
    </div>
</section>

<section class="cta">
    <h2>Quer sua empresa no topo do Google?</h2>
    <p>Fale agora com a Agência Cogni pelo WhatsApp</p>

    <a class="btn-whatsapp"
       href="https://wa.me/5511932057575"
       target="_blank">
       🚀 Chamar no WhatsApp
    </a>
</section>

<footer>
    <p>© 2026 Agência Cogni | Google Meu Negócio</p>
</footer>

<a class="whatsapp-float"
   href="https://wa.me/5511932057575"
   target="_blank">
   💬
</a>

</body>
</html>
