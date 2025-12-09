<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width,initial-scale=1">
  <title>𝚂𝚎𝚛𝚟𝚒𝚌𝚒𝚘𝚜 𝚍𝚎 𝚁𝚎𝚌𝚊𝚛𝚐𝚊𝚜 𝚢 𝚁𝚎𝚊𝚌𝚝𝚒𝚟𝚊𝚌𝚒𝚘𝚗𝚎𝚜—𝙿𝚛𝚘𝚏𝚎𝚜𝚒𝚘𝚗𝚊𝚕</title>
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;800&display=swap" rel="stylesheet">

  <style>
:root{
  --bg:#0d0f14;
  --card:#0f1720;
  --muted:#bfc8d6;
  --accent-1:#6e00ff;
  --accent-2:#1a73e8;
  --glass: rgba(255,255,255,0.04);
  --glass-2: rgba(255,255,255,0.02);
  --radius: 14px;
  --maxw: 1100px;
}
*{box-sizing:border-box}
html,body{height:100%}
body{
  margin:0;
  font-family: "Poppins", system-ui, -apple-system, "Segoe UI", Roboto, "Helvetica Neue", Arial;
  background: linear-gradient(180deg,var(--bg) 0%, #050608 120%);
  color:#e6eef8;
  -webkit-font-smoothing:antialiased;
  -moz-osx-font-smoothing:grayscale;
  line-height:1.5;
}
/* Header */
header{
  background: linear-gradient(135deg,var(--accent-2),var(--accent-1));
  padding:28px 20px;
  color:#fff;
  box-shadow: 0 8px 30px rgba(12,15,30,0.6);
  border-bottom: 1px solid rgba(255,255,255,0.04);
  position:sticky;top:0;z-index:90;
}
.header-inner{max-width:var(--maxw);margin:0 auto;display:flex;align-items:center;gap:20px;justify-content:space-between}
.brand{display:flex;gap:12px;align-items:center}
.logo{width:54px;height:54px;border-radius:12px;background:linear-gradient(135deg,#fff8, #ffffff11);display:flex;align-items:center;justify-content:center;font-weight:800;color:white}
.brand h1{margin:0;font-size:1.25rem;letter-spacing:0.6px}
.brand p{margin:0;font-size:0.85rem;opacity:0.95}
.nav{display:flex;gap:12px;align-items:center}
.nav a{color:rgba(255,255,255,0.95);text-decoration:none;padding:8px 12px;border-radius:10px;font-weight:600}
.nav a:hover{background:rgba(255,255,255,0.06)}
/* Main */
.container{max-width:var(--maxw);margin:30px auto;padding:0 20px 80px}
.hero{display:grid;grid-template-columns:1fr 380px;gap:26px;align-items:stretch}
@media (max-width:980px){.hero{grid-template-columns:1fr}.nav{display:none}}
.card-hero{background:linear-gradient(180deg, rgba(255,255,255,0.02), rgba(255,255,255,0.01));padding:26px;border-radius:14px;border:1px solid rgba(255,255,255,0.03);box-shadow:0 12px 40px rgba(0,0,0,0.6)}
.hero h2{margin:0 0 8px;font-size:1.6rem;color:#fff}
.hero p{margin:0 0 12px;color:var(--muted)}
.kv{display:flex;gap:8px;align-items:center}
.pulse{display:inline-block;width:10px;height:10px;border-radius:50%;background:#7bf6a4;box-shadow:0 0 10px rgba(123,246,164,0.22);animation:pulse 1.8s infinite}
@keyframes pulse{0%{transform:scale(.9);opacity:.9}70%{transform:scale(1.3);opacity:.2}100%{transform:scale(.9);opacity:.9}}
/* grid */
.grid{display:grid;grid-template-columns:repeat(3,1fr);gap:20px;margin-top:22px}
@media (max-width:1000px){.grid{grid-template-columns:repeat(2,1fr)}}
@media (max-width:640px){.grid{grid-template-columns:1fr}}
.plan{background: linear-gradient(180deg,var(--card), rgba(14,17,23,0.9));border-radius:var(--radius);padding:18px;border:1px solid var(--glass);box-shadow:0 10px 30px rgba(3,6,12,0.6), inset 0 1px 0 rgba(255,255,255,0.02);transition:transform .28s cubic-bezier(.2,.9,.2,1),box-shadow .28s ease;position:relative;overflow:hidden;min-height:140px}
.plan:hover{transform:translateY(-10px) scale(1.01);box-shadow:0 20px 50px rgba(3,6,12,0.75)}
.plan h3{margin:0 0 8px;color:#dff0ff;font-size:1.05rem;display:flex;align-items:center;gap:10px}
.plan .meta{display:flex;gap:8px;align-items:center;margin-bottom:10px;color:var(--muted);font-size:0.92rem}
.badge{position:absolute;right:16px;top:16px;background:linear-gradient(90deg,var(--accent-1),var(--accent-2));color:white;padding:8px 12px;border-radius:12px;font-weight:700;font-size:0.95rem;box-shadow:0 6px 18px rgba(110,0,255,0.22)}
.plan ul{margin:8px 0 0;padding-left:18px;color:var(--muted)}
.plan p{margin:6px 0;color:rgba(255,255,255,0.9)}
.highlight{color:var(--accent-2);font-weight:700}
.cta-row{display:flex;gap:12px;margin-top:14px;align-items:center;flex-wrap:wrap}
.btn{display:inline-flex;align-items:center;gap:10px;background:linear-gradient(90deg,var(--accent-1),var(--accent-2));border:none;color:#fff;padding:10px 14px;font-weight:700;border-radius:12px;cursor:pointer;box-shadow:0 10px 30px rgba(26,115,232,0.12);text-decoration:none;transition:transform .18s ease,box-shadow .18s ease,opacity .12s ease}
.btn:active{transform:translateY(1px)}
.btn.ghost{background:transparent;color:var(--muted);border:1px solid rgba(255,255,255,0.06);box-shadow:none}
.whatsapp-fab{position:fixed;right:18px;bottom:18px;z-index:999;display:inline-flex;align-items:center;gap:10px;padding:12px 16px;border-radius:999px;background:linear-gradient(90deg,#25D366,#128C7E);color:#fff;font-weight:700;box-shadow:0 10px 30px rgba(18,140,126,0.18);text-decoration:none;border:0}
.searchbar{display:flex;gap:10px;margin-top:14px}
.searchbar input{flex:1;padding:10px;border-radius:10px;border:1px solid rgba(255,255,255,0.04);background:transparent;color:inherit}
.select{padding:10px;border-radius:10px;border:1px solid rgba(255,255,255,0.04);background:transparent;color:inherit}
/* accordion */
.accordion{margin-top:18px;border-radius:12px;overflow:hidden;border:1px solid rgba(255,255,255,0.03)}
.ac-item{border-bottom:1px solid rgba(255,255,255,0.03)}
.ac-item button{width:100%;text-align:left;padding:14px;background:transparent;border:0;color:inherit;font-weight:700;display:flex;align-items:center;justify-content:space-between}
.ac-item .panel{padding:14px;background:linear-gradient(180deg, rgba(255,255,255,0.01), transparent);color:var(--muted)}
/* modal */
.modal{position:fixed;inset:0;background:rgba(0,0,0,0.6);display:none;align-items:center;justify-content:center;padding:20px;z-index:110}
.modal.show{display:flex}
.modal .box{width:100%;max-width:520px;background:#07101a;padding:20px;border-radius:12px;border:1px solid rgba(255,255,255,0.04)}
.input{width:100%;padding:10px;border-radius:10px;border:1px solid rgba(255,255,255,0.04);background:transparent;color:inherit;margin-bottom:10px}
.site-footer{max-width:var(--maxw);margin:30px auto 60px;padding:18px 20px;color:var(--muted);text-align:center;border-top:1px solid rgba(255,255,255,0.03);font-size:0.95rem;background:linear-gradient(180deg, transparent, var(--glass-2));border-radius:12px}
.small{font-size:0.9rem;color:var(--muted)}
.copy{cursor:pointer;padding:6px 8px;border-radius:8px;border:1px solid rgba(255,255,255,0.04);background:transparent}
.badge-new{background:#ffea; padding:6px 8px;border-radius:8px;font-weight:700;color:#fff}
</style>
</head>
<body>

<header>
  <div class="header-inner">
    <div class="brand">
      <div class="logo">PB</div>
      <div>
        <h1>Ｐａｑｕｅｔｅｓ ＆ Ｓｅｒｖｉｃｉｏｓ</h1>
        <p class="small">Recargas, reactivaciones y pagos — Legal y Garantizado</p>
      </div>
    </div>

    <nav class="nav" aria-label="navegacion">
      <a href="#planes">Planes</a>
      <a href="#servicios">Servicios</a>
      <a href="#recargas">Recargas</a>
      <a href="#contacto">Contacto</a>
    </nav>

    <div class="kv">
      <div class="pulse" aria-hidden="true"></div>
      <div class="small">Atención 24/7</div>
    </div>
  </div>
</header>

<main class="container">
  <section class="hero">
    <div class="card-hero">
      <h2>Servicios profesionales y seguros — Disponible ahora</h2>
      <p class="small">Ofrecemos reactivaciones, renovaciones, recargas con descuento y pagos de recibos para Movistar, Claro, Entel y Bitel. Servicio con garantía y atención inmediata.</p>

      <div class="searchbar" role="search">
        <input id="search" placeholder="Buscar plan o servicio (ej: Bitel, Recarga 20, Reactivación)" aria-label="Buscar servicios">
        <select id="filter" class="select" aria-label="filtrar">
          <option value="all">Todos</option>
          <option value="bitel">Bitel</option>
          <option value="entel">Entel</option>
          <option value="movistar">Movistar</option>
          <option value="recibo">Recibos</option>
        </select>
        <button id="clear" class="btn ghost">Limpiar</button>
      </div>

      <div class="accordion" id="faq">
        <div class="ac-item">
          <button aria-expanded="false">¿Necesito dar mi contraseña de app? <span>▼</span></button>
          <div class="panel">Para activar algunos servicios por app se requiere número y clave. Trabajamos con seguridad y confidencialidad. Nunca pedimos datos extras innecesarios.</div>
        </div>
        <div class="ac-item">
          <button aria-expanded="false">¿La reactivación tiene garantía? <span>▼</span></button>
          <div class="panel">Sí: garantía mínima indicada en cada servicio. Si hay algún inconveniente lo solucionamos inmediatamente.</div>
        </div>
      </div>

    </div>

    <aside class="card-hero">
      <h3 class="small">Contacto Rápido</h3>
      <p class="small">WhatsApp directo para atención inmediata. También puedes enviar tu número y solicitar cotización.</p>
      <div style="display:flex;gap:10px;margin-top:12px">
        <a class="btn" id="waTop" href="https://wa.me/51939553846?text=Hola%20quisiera%20info" target="_blank" rel="noreferrer">WhatsApp</a>
        <button class="btn ghost" id="openContact">Enviar mensaje</button>
      </div>

      <div style="margin-top:16px">
        <div class="small">Horario:</div>
        <div class="small">Atendemos 24/7 — Respuesta en minutos</div>
        <div style="margin-top:12px"><span class="badge-new">Legal • Garantizado</span></div>
      </div>
    </aside>
  </section>

  <section id="planes">
    <h2 style="margin:12px 0 6px">Planes y Ofertas</h2>
    <p class="small">Todos los servicios en una sola página — revisa, busca y contáctanos al instante.</p>

    <div class="grid" id="plansGrid">

      <!-- Plan 1 -->
      <article class="plan" data-tags="reactivacion">
        <div class="badge">S/.18</div>
        <h3>🔧 Reactivación y Renovación</h3>
        <p class="meta">Chips Movistar • Claro • Entel — Líneas suspendidas por deuda</p>
        <p>Reactivación inmediata con garantía. Servicio seguro y profesional.</p>
        <div class="cta-row">
          <a class="btn" href="https://wa.me/51939553846?text=Hola%20quiero%20reactivar%20mi%20linea">WhatsApp</a>
          <button class="btn ghost" data-action="more" data-id="1">Más detalles</button>
        </div>
      </article>

      <!-- Plan 2 -->
      <article class="plan" data-tags="reactivacion">
        <div class="badge">S/.18</div>
        <h3>🔥 Reactivación Chip Blanco</h3>
        <p class="meta">Renovamos meses — hasta 1 año</p>
        <p>Servicio con garantía 100% — pagas después de verificar que funcione.</p>
        <div class="cta-row">
          <a class="btn" href="https://wa.me/51939553846?text=Hola%20quiero%20reactivar%20mi%20chip%20blanco">WhatsApp</a>
          <button class="btn ghost" data-action="more" data-id="2">Más detalles</button>
        </div>
      </article>

      <!-- Plan 3 Bitel -->
      <article class="plan" data-tags="bitel">
        <div class="badge">S/.13</div>
        <h3>📦 Bitel — 18GB</h3>
        <p class="meta">18GB + llamadas — 10 días</p>
        <p>Excelente para uso diario. Requiere número y contraseña de la app.</p>
        <div class="cta-row"><a class="btn" href="https://wa.me/51939553846?text=Quiero%2018GB%20Bitel">WhatsApp</a></div>
      </article>

      <!-- Plan 4 Bitel -->
      <article class="plan" data-tags="bitel">
        <div class="badge">S/.16</div>
        <h3>📦 Bitel — 20GB</h3>
        <p class="meta">20GB + llamadas — 13 días</p>
        <p>Ideal para redes y streaming ligero.</p>
        <div class="cta-row"><a class="btn" href="https://wa.me/51939553846?text=Quiero%2020GB%20Bitel">WhatsApp</a></div>
      </article>

      <!-- Plan 5 Bitel -->
      <article class="plan" data-tags="bitel">
        <div class="badge">S/.30</div>
        <h3>📦 Bitel — 45GB</h3>
        <p class="meta">45GB + llamadas — 30 días</p>
        <p>Consumo alto — streaming y redes sin preocupaciones.</p>
        <div class="cta-row"><a class="btn" href="https://wa.me/51939553846?text=Quiero%2045GB%20Bitel">WhatsApp</a></div>
      </article>

      <!-- Plan 6 Bitel -->
      <article class="plan" data-tags="bitel">
        <div class="badge">S/.45</div>
        <h3>📦 Bitel — 60GB</h3>
        <p class="meta">60GB + llamadas — 30 días</p>
        <p>Perfecto para 2–3 usuarios o consumo intensivo.</p>
        <div class="cta-row"><a class="btn" href="https://wa.me/51939553846?text=Quiero%2060GB%20Bitel">WhatsApp</a></div>
      </article>

      <!-- Plan 7 Bitel -->
      <article class="plan" data-tags="bitel">
        <div class="badge">S/.60</div>
        <h3>📦 Bitel — 140GB</h3>
        <p class="meta">140GB + llamadas — 30 días</p>
        <p>Pack masivo: gaming, streaming y descargas.</p>
        <div class="cta-row"><a class="btn" href="https://wa.me/51939553846?text=Quiero%20140GB%20Bitel">WhatsApp</a></div>
      </article>

      <!-- Recargas Entel -->
      <article class="plan" data-tags="entel">
        <div class="badge">DESC</div>
        <h3>🌟 Recargas Entel - Descuento</h3>
        <p class="meta">Recarga 10 / 20 / 30 / 40 / 50</p>
        <ul>
          <li>10 → S/.7.5</li>
          <li>20 → S/.15</li>
          <li>30 → S/.22</li>
          <li>40 → S/.30</li>
          <li>50 → S/.37</li>
        </ul>
        <div class="cta-row"><a class="btn" href="https://wa.me/51939553846?text=Recarga%20Entel">WhatsApp</a></div>
      </article>

      <!-- Recargas Movistar -->
      <article class="plan" data-tags="movistar">
        <div class="badge">DESC</div>
        <h3>🌟 Recargas Movistar - Descuento</h3>
        <p class="meta">Recarga 20 / 30 / 40 / 50</p>
        <ul>
          <li>20 → S/.15</li>
          <li>30 → S/.22</li>
          <li>40 → S/.30</li>
          <li>50 → S/.37</li>
        </ul>
        <div class="cta-row"><a class="btn" href="https://wa.me/51939553846?text=Recarga%20Movistar">WhatsApp</a></div>
      </article>

      <!-- Pagos recibos Entel -->
      <article class="plan" data-tags="recibo">
        <div class="badge">ENTEL</div>
        <h3>🔰 Pagos Recibos — Entel</h3>
        <ul>
          <li>29.90 → Paga S/.22</li>
          <li>35.00 → Paga S/.26</li>
          <li>39.90 → Paga S/.30</li>
          <li>45.00 → Paga S/.33</li>
          <li>49.90 → Paga S/.37</li>
        </ul>
        <div class="cta-row"><a class="btn" href="https://wa.me/51939553846?text=Pago%20recibo%20Entel">WhatsApp</a></div>
      </article>

      <!-- Pagos recibos Movistar -->
      <article class="plan" data-tags="recibo">
        <div class="badge">MOV</div>
        <h3>🔰 Pagos Recibos — Movistar</h3>
        <ul>
          <li>29.90 → Paga S/.22</li>
          <li>35.00 → Paga S/.26</li>
          <li>39.90 → Paga S/.30</li>
          <li>45.00 → Paga S/.33</li>
          <li>49.90 → Paga S/.37</li>
        </ul>
        <div class="cta-row"><a class="btn" href="https://wa.me/51939553846?text=Pago%20recibo%20Movistar">WhatsApp</a></div>
      </article>

      <!-- Pagos recibos Bitel -->
      <article class="plan" data-tags="recibo">
        <div class="badge">BITEL</div>
        <h3>🇵🇪 Pagos Recibos — Bitel</h3>
        <ul>
          <li>29.90 → Paga S/.23</li>
          <li>35.00 → Paga S/.26</li>
          <li>39.90 → Paga S/.30</li>
          <li>44.00 → Paga S/.34</li>
          <li>49.90 → Paga S/.38</li>
        </ul>
        <p class="small">Requiere número y clave de la app.</p>
        <div class="cta-row"><a class="btn" href="https://wa.me/51939553846?text=Pago%20recibo%20Bitel">WhatsApp</a></div>
      </article>

      <!-- Fidelización Claro -->
      <article class="plan" data-tags="movistar">
        <div class="badge">50%</div>
        <h3>📀 Fidelización Claro Pospago</h3>
        <p class="meta">Descuento 50% por 3 a 6 meses (desde plan S/.49.90)</p>
        <p>Servicio garantizado y legal. Pagas solo la mitad del recibo.</p>
        <div class="cta-row"><a class="btn" href="https://wa.me/51939553846?text=Fidelizacion%20Claro">WhatsApp</a></div>
      </article>

    </div>

  </section>

  <section id="servicios" style="margin-top:26px">
    <h2 style="margin:0 0 10px">Servicios destacados</h2>
    <div class="card-hero">
      <h3 class="small">Paquetes & Servicios</h3>
      <ul class="small">
        <li>✔ Operaciones legales y verificables.</li>
        <li>✔ Respeto a la privacidad: usamos solo el número y clave necesarios.</li>
        <li>✔ Garantía mínima en cada procedimiento.</li>
      </ul>

      <div style="margin-top:12px" class="small">Si necesitas factura o comprobante, indica en el chat y evaluamos la opción.</div>
    </div>
  </section>

  <section id="recargas" style="margin-top:26px">
    <h2 style="margin:0 0 10px">Recargas y pagos</h2>
    <div class="card-hero">
      <p class="small">Recargas con descuento y pagos de recibos — procesos seguros y rápidos.</p>
      <div style="display:flex;gap:10px;margin-top:12px">
        <button class="btn" onclick="openModal()">Solicitar servicio</button>
        <a class="btn ghost" href="#plansGrid" onclick="document.getElementById('search').focus()">Ver planes</a>
      </div>
    </div>
  </section>

  <section id="contacto" style="margin-top:30px">
    <h2>Contacto</h2>
    <div class="card-hero">
      <p class="small">Contáctanos por WhatsApp o deja tu mensaje.</p>
      <div style="display:flex;gap:10px;margin-top:10px">
        <a class="btn" href="https://wa.me/51939553846?text=Hola%20quiero%20informacion" id="waBottom">WhatsApp</a>
        <button class="btn ghost" onclick="openModal()">Enviar mensaje</button>
      </div>
      <div style="margin-top:14px" class="small">Número público: <span class="copy" data-copy="+51939553846">+51 939 553 846 (copiar)</span></div>
    </div>
  </section>

</main>

<!-- WhatsApp fixed -->
<a class="whatsapp-fab" href="https://wa.me/51939553846?text=Hola%20quisiera%20info" target="_blank" rel="noreferrer">WhatsApp</a>

<!-- Modal -->
<div class="modal" id="modal">
  <div class="box" role="dialog" aria-modal="true" aria-labelledby="modalTitle">
    <h3 id="modalTitle">Enviar mensaje</h3>
    <p class="small">Deja tu nombre, número y mensaje. No compartiremos información extra.</p>
    <input class="input" id="name" placeholder="Nombre" required>
    <input class="input" id="phone" placeholder="Número (ej: 939553846)" required>
    <textarea class="input" id="message" placeholder="Tu mensaje" rows="4"></textarea>
    <div style="display:flex;gap:8px;margin-top:8px">
      <button class="btn" id="send">Enviar</button>
      <button class="btn ghost" id="closeModal">Cancelar</button>
    </div>
    <div id="modalMsg" class="small" style="margin-top:8px;display:none"></div>
  </div>
</div>

<footer class="site-footer">
  <div>© <strong>Ｐａｑｕｅｔｅｓ＆Ｓｅｒｖｉｃｉｏｓ</strong> — Atención y soporte. <span class="small">Operador independiente. Siempre actúa con tu consentimiento.</span></div>
</footer>

<script>
// Smooth scroll for nav
document.querySelectorAll('a[href^="#"]').forEach(a=>{
  a.addEventListener('click',function(e){
    const target = document.querySelector(this.getAttribute('href'));
    if(target){e.preventDefault();target.scrollIntoView({behavior:'smooth',block:'start'});} 
  });
});

// Accordion
document.querySelectorAll('.ac-item button').forEach(btn=>{
  btn.addEventListener('click',()=>{
    const expanded = btn.getAttribute('aria-expanded') === 'true';
    btn.setAttribute('aria-expanded', String(!expanded));
    const panel = btn.nextElementSibling;
    if(panel.style.display === 'block'){panel.style.display='none'} else {panel.style.display='block'}
  });
});

// Modal
const modal = document.getElementById('modal');
const openContact = document.getElementById('openContact');
const closeModal = document.getElementById('closeModal');
openContact && openContact.addEventListener('click', openModal);
closeModal && closeModal.addEventListener('click', closeModalFn);
function openModal(){ modal.classList.add('show'); }
function closeModalFn(){ modal.classList.remove('show'); }

// Send (fake, demonstration)
document.getElementById('send').addEventListener('click', ()=>{
  const name = document.getElementById('name').value.trim();
  const phone = document.getElementById('phone').value.trim();
  const msg = document.getElementById('message').value.trim();
  const modalMsg = document.getElementById('modalMsg');
  if(!name || !phone){ modalMsg.style.display='block'; modalMsg.textContent='Por favor completa nombre y teléfono.'; return; }
  modalMsg.style.display='block'; modalMsg.textContent='Mensaje enviado. Te responderemos por WhatsApp.';
  // Simula apertura de chat con prefill
  const text = encodeURIComponent(`Hola, soy ${name} - ${phone}: ${msg}`);
  window.open('https://wa.me/51939553846?text='+text,'_blank');
  setTimeout(()=>{ modal.classList.remove('show'); modalMsg.style.display='none'; document.getElementById('name').value=''; document.getElementById('phone').value=''; document.getElementById('message').value=''; },800);
});

// Copy number
document.querySelectorAll('[data-copy]').forEach(el=>{
  el.addEventListener('click',()=>{
    const val = el.getAttribute('data-copy');
    navigator.clipboard && navigator.clipboard.writeText(val).then(()=>{
      el.textContent='Copiado ✓';
      setTimeout(()=>el.textContent=val.replace('+51','+51 '),1500);
    }).catch(()=>alert('Copia manual: '+val));
  });
});

// Filter & search
const searchEl = document.getElementById('search');
const filterEl = document.getElementById('filter');
const clearBtn = document.getElementById('clear');
function filterPlans(){
  const q = (searchEl.value||'').toLowerCase();
  const tag = filterEl.value;
  document.querySelectorAll('#plansGrid .plan').forEach(card=>{
    const text = card.innerText.toLowerCase();
    const tags = card.getAttribute('data-tags')||'';
    const matchText = !q || text.includes(q);
    const matchTag = tag==='all' || tags.includes(tag);
    card.style.display = (matchText && matchTag) ? 'block' : 'none';
  });
}
searchEl.addEventListener('input', filterPlans);
filterEl.addEventListener('change', filterPlans);
clearBtn.addEventListener('click', ()=>{searchEl.value=''; filterEl.value='all'; filterPlans();});

// Details buttons
document.querySelectorAll('button[data-action="more"]').forEach(b=>{
  b.addEventListener('click', ()=>{
    const id = b.getAttribute('data-id');
    alert('Detalles rápidos: Para más información abre chat de WhatsApp o envía tu número. (Detalle id:'+id+')');
  });
});

// Accessibility: close modal with Escape
document.addEventListener('keydown', e=>{ if(e.key==='Escape') modal.classList.remove('show'); });

</script>
</body>
</html>

