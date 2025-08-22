# tiktok
<!doctype html>
<html lang="es">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Cómo ganar dinero en TikTok – Guía completa</title>
  <meta name="description" content="Página educativa y moderna que explica todas las formas de ganar dinero en TikTok: colaboraciones, afiliados, directos, tienda, UGC, servicios y más." />
  <meta name="theme-color" content="#0ea5e9" />
  <style>
    :root{
      --bg:#0b1220; --card:#0f172a; --text:#e5e7eb; --muted:#94a3b8;
      --brand:#22d3ee; --brand2:#38bdf8; --good:#34d399; --warn:#f59e0b; --danger:#ef4444;
      --radius:18px; --shadow:0 10px 25px rgba(0,0,0,.35); --max:1100px;
    }
    *{box-sizing:border-box}
    html,body{margin:0;font-family:system-ui,-apple-system,Segoe UI,Roboto,Ubuntu,Cantarell,Noto Sans,Helvetica,Arial;background:radial-gradient(1200px 600px at 10% -10%, #0b3b5a 0, transparent 60%),radial-gradient(900px 450px at 120% 10%, #10223a 0, transparent 60%), var(--bg);color:var(--text);line-height:1.6}
    a{color:var(--brand2);text-decoration:none}
    a:hover{text-decoration:underline}
    .container{max-width:var(--max);margin-inline:auto;padding:24px}
    .nav{position:sticky;top:0;background:rgba(11,18,32,.7);backdrop-filter:blur(10px);border-bottom:1px solid rgba(56,189,248,.25);z-index:50}
    .nav-inner{display:flex;align-items:center;justify-content:space-between;gap:14px}
    .brand{display:flex;align-items:center;gap:10px;font-weight:900;letter-spacing:.3px}
    .logo{width:36px;height:36px;border-radius:12px;background:linear-gradient(135deg,#22d3ee,#38bdf8);display:grid;place-items:center;box-shadow:var(--shadow)}
    .logo span{font-weight:900;color:#082032}
    .menu{display:flex;gap:14px;align-items:center}
    .btn{padding:10px 16px;border-radius:999px;border:1px solid rgba(255,255,255,.15);background:transparent;color:var(--text);cursor:pointer}
    .btn.primary{background:linear-gradient(135deg,#22d3ee,#38bdf8);border:none;color:#082032;font-weight:800}
    .btn.good{background:linear-gradient(135deg,#34d399,#22c55e);border:none;color:#052e1b;font-weight:800}
    .hamburger{display:none;border:1px solid rgba(255,255,255,.15);border-radius:10px;padding:8px;background:transparent;color:var(--text)}

    header.hero{padding:64px 24px}
    .hero-grid{display:grid;grid-template-columns:1.2fr 1fr;gap:28px;align-items:center}
    h1{font-size:clamp(28px,6vw,54px);line-height:1.05;margin:12px 0 8px}
    .subtitle{color:var(--muted);font-size:clamp(15px,2.4vw,18px)}
    .pill{display:inline-flex;gap:8px;align-items:center;border:1px dashed rgba(56,189,248,.4);color:var(--muted);padding:6px 10px;border-radius:999px}
    .card{background:linear-gradient(180deg,rgba(255,255,255,.05),rgba(255,255,255,.02));border:1px solid rgba(56,189,248,.2);border-radius:var(--radius);box-shadow:var(--shadow);padding:20px}

    section{padding:44px 24px}
    section h2{font-size:clamp(22px,4.5vw,36px);margin:0 0 12px}
    .grid-3{display:grid;grid-template-columns:repeat(3,1fr);gap:20px}
    .grid-2{display:grid;grid-template-columns:repeat(2,1fr);gap:20px}
    .badge{display:inline-block;padding:6px 10px;border-radius:999px;background:rgba(56,189,248,.15);color:#7dd3fc;font-weight:800;font-size:.85rem}
    .warn{background:rgba(245,158,11,.15);color:var(--warn)}
    .ok{background:rgba(52,211,153,.15);color:var(--good)}

    details{background:linear-gradient(180deg,rgba(255,255,255,.04),rgba(255,255,255,.02));border:1px solid rgba(255,255,255,.12);border-radius:14px;padding:14px}
    details+details{margin-top:12px}
    summary{cursor:pointer;font-weight:700}

    ul.checked{list-style:none;margin:0;padding-left:0;display:grid;gap:8px}
    ul.checked li::before{content:"✔";margin-right:8px;color:var(--good)}

    .footer{padding:28px 24px;border-top:1px solid rgba(56,189,248,.2);color:var(--muted);text-align:center}

    @media (max-width: 900px){
      .hero-grid,.grid-3,.grid-2{grid-template-columns:1fr}
      .menu{display:none}
      .hamburger{display:block}
      .menu.open{display:flex;flex-direction:column;gap:12px;padding:12px;background:rgba(15,23,42,.9);position:absolute;top:60px;right:24px;border-radius:12px;border:1px solid rgba(255,255,255,.12)}
    }
  </style>
</head>
<body>
  <!-- Nav -->
  <nav class="nav" aria-label="Navegación">
    <div class="container nav-inner">
      <a class="brand" href="#top">
        <div class="logo" aria-hidden="true"><span>TT</span></div>
        <span>TikTok Money</span>
      </a>
      <button class="hamburger" id="btnMenu" aria-label="Abrir menú">☰</button>
      <div class="menu" id="menu">
        <a href="#formas" class="btn">Formas</a>
        <a href="#pasos" class="btn">Pasos</a>
        <a href="#errores" class="btn">Errores</a>
        <a href="#faq" class="btn">FAQ</a>
        <a href="#recursos" class="btn primary">Recursos</a>
      </div>
    </div>
  </nav>

  <!-- Hero -->
  <header class="hero" id="top">
    <div class="container hero-grid">
      <div>
        <span class="pill">📱 Monetización • Empezar sin dinero</span>
        <h1>Cómo ganar dinero en TikTok</h1>
        <p class="subtitle">Aprende todas las vías para monetizar: colaboraciones con marcas, afiliados, directos con regalos, TikTok Shop, UGC, servicios y más. Consejos claros, checklist y plan de acción.</p>
        <div style="display:flex;gap:12px;flex-wrap:wrap;margin-top:14px">
          <a href="#formas" class="btn primary">Ver formas de ganar</a>
          <a href="#pasos" class="btn">Plan de 7 días</a>
        </div>
      </div>
      <div class="card">
        <h3 style="margin:0 0 8px">Resumen rápido</h3>
        <ul class="checked">
          <li>🎯 Nicho claro + contenido constante.</li>
          <li>🤝 Ofrece valor a marcas (UGC/colabs) aunque tengas pocos seguidores.</li>
          <li>🛒 Incluye links de afiliado o tu tienda.</li>
          <li>🎥 Haz directos y activa regalos cuando puedas.</li>
          <li>🔁 Recicla clips en Reels/Shorts para crecer más rápido.</li>
        </ul>
      </div>
    </div>
  </header>

  <!-- Formas de ganar -->
  <section id="formas">
    <div class="container">
      <h2>Formas reales de ganar dinero en TikTok</h2>
      <p class="subtitle">No todas dependen de tener millones de seguidores. Varias funcionan con audiencias pequeñas pero bien definidas.</p>
      <div class="grid-3">
        <div class="card">
          <span class="badge">Colaboraciones con marcas</span>
          <h3>Patrocinios / menciones</h3>
          <p>Negocia publicaciones patrocinadas, menciones o integraciones en tus videos. Mide tus tarifas según alcance, nicho y derechos de uso.</p>
        </div>
        <div class="card">
          <span class="badge">UGC</span>
          <h3>Contenido generado para marcas</h3>
          <p>Creas videos para que la marca los use en sus cuentas o anuncios. No necesitas gran audiencia, sí habilidades de edición y guion.</p>
        </div>
        <div class="card">
          <span class="badge">Afiliados</span>
          <h3>Comisiones por venta</h3>
          <p>Comparte enlaces de afiliado a productos que recomiendas. Usa landing pages y disclose (aviso de afiliado) en la descripción.</p>
        </div>
        <div class="card">
          <span class="badge">Directos</span>
          <h3>Regalos & suscripciones</h3>
          <p>En vivos, la audiencia puede enviar regalos que se convierten en ingresos. Ofrece dinámicas (Q&A, retos, sorteos) para incentivar.</p>
        </div>
        <div class="card">
          <span class="badge">TikTok Shop</span>
          <h3>Vende productos</h3>
          <p>Integra tu catálogo físico o digital. Crea demos, reseñas y bundles. Si no tienes producto, combina con afiliados.</p>
        </div>
        <div class="card">
          <span class="badge">Servicios</span>
          <h3>Freelance / asesorías</h3>
          <p>Ofrece edición de video, gestión de redes, guiones, miniaturas, consultorías o clases. Usa TikTok para atraer clientes.</p>
        </div>
        <div class="card">
          <span class="badge">Cursos / infoproductos</span>
          <h3>Productos digitales</h3>
          <p>Guías, plantillas, presets, packs de ideas. Véndelos vía Gumroad, Lemon Squeezy, etc., y enlaza desde tu bio.</p>
        </div>
        <div class="card">
          <span class="badge">Tráfico a otras redes</span>
          <h3>Monetiza fuera</h3>
          <p>Lleva a tu audiencia a YouTube, newsletter o web donde tengas anuncios, membresías o ventas directas.</p>
        </div>
        <div class="card">
          <span class="badge warn">Programas internos</span>
          <h3>Cambian a menudo</h3>
          <p>Las reglas/umbral de programas de monetización nativos suelen cambiar por país y fecha. Revisa siempre la app y el sitio oficial.</p>
        </div>
      </div>
    </div>
  </section>

  <!-- Plan de 7 días -->
  <section id="pasos">
    <div class="container">
      <h2>Plan de 7 días para empezar</h2>
      <div class="grid-2">
        <div class="card">
          <h3>Días 1–2: Base</h3>
          <ul>
            <li>Define tu nicho (ej.: gadgets baratos, recetas rápidas, estudio productivo).</li>
            <li>Escribe 20 ideas de videos (ganchos + beneficios).</li>
            <li>Configura biografía con CTA y link a tu landing (Notion/Linktree).</li>
          </ul>
        </div>
        <div class="card">
          <h3>Día 3: Producción</h3>
          <ul>
            <li>Crea 3–5 plantillas de guion (intro, demo, cierre).</li>
            <li>Graba 5–10 clips en batch. Mantén 9–15s si son tips rápidos.</li>
            <li>Sube 1–2 pruebas y mira retención/comentarios.</li>
          </ul>
        </div>
        <div class="card">
          <h3>Día 4: Optimización</h3>
          <ul>
            <li>Usa ganchos fuertes en 1–2s. Texto en pantalla y subtítulos.</li>
            <li>Prueba 2 portadas distintas. Añade 3–5 hashtags relevantes.</li>
            <li>Responde comentarios con video para acelerar ideas.</li>
          </ul>
        </div>
        <div class="card">
          <h3>Día 5: Monetización inicial</h3>
          <ul>
            <li>Afiliados: selecciona 1–2 productos y crea una landing con enlaces.</li>
            <li>UGC: graba 2 demos para marcas de tu nicho y súbelos a un portafolio.</li>
            <li>Servicios: define 2 paquetes (ej.: edición 4 videos/mes, consultoría 30min).</li>
          </ul>
        </div>
        <div class="card">
          <h3>Día 6: Distribución</h3>
          <ul>
            <li>Sube tus mejores clips a Reels y Shorts.</li>
            <li>Conecta con 10 creadores/tiendas en DMs con propuesta clara.</li>
            <li>Programa un directo corto: Q&A o demo.</li>
          </ul>
        </div>
        <div class="card">
          <h3>Día 7: Métricas y mejora</h3>
          <ul>
            <li>Revisa retención, comentarios, CTR del link y conversiones.</li>
            <li>Duplica lo que funcionó; archiva lo que no.</li>
            <li>Planifica 2 semanas con el calendario editorial.</li>
          </ul>
        </div>
      </div>
    </div>
  </section>

  <!-- Errores comunes -->
  <section id="errores">
    <div class="container">
      <h2>Errores comunes que frenan tus ingresos</h2>
      <div class="grid-3">
        <div class="card">
          <span class="badge">Genérico</span>
          <h3>Sin nicho</h3>
          <p>Hablar de todo confunde al algoritmo y a la audiencia. Enfócate en un problema/deseo específico.</p>
        </div>
        <div class="card">
          <span class="badge">Sin CTA</span>
          <h3>Olvidar el siguiente paso</h3>
          <p>Incluye CTA claros: “link en bio”, “código de descuento”, “descarga la guía”.</p>
        </div>
        <div class="card">
          <span class="badge">Corto plazo</span>
          <h3>Abandonar muy pronto</h3>
          <p>La constancia gana. Itera por 30–60 días con métricas, no por sensaciones.</p>
        </div>
      </div>
    </div>
  </section>

  <!-- FAQ -->
  <section id="faq">
    <div class="container">
      <h2>Preguntas frecuentes</h2>
      <details>
        <summary>¿Necesito muchos seguidores para ganar dinero?</summary>
        <p>No siempre. Para UGC, servicios o afiliados bastan audiencias pequeñas pero bien definidas. Para patrocinios grandes, más seguidores ayudan.</p>
      </details>
      <details>
        <summary>¿Cuánto se puede ganar?</summary>
        <p>Depende del nicho, país y formato. Mezclar 2–3 vías (afiliados + UGC + servicios) suele ser más estable que depender de una sola.</p>
      </details>
      <details>
        <summary>¿Qué equipo necesito?</summary>
        <p>Un móvil con buena luz natural, trípode barato (opcional) y apps de edición (CapCut, VN). El contenido y la claridad del mensaje pesan más que el equipo.</p>
      </details>
      <details>
        <summary>¿Cómo contacto marcas?</summary>
        <p>Prepara un portafolio corto (5–8 videos), define tarifas base y envía propuestas por email/DM explicando el beneficio (qué problema resuelves) y pruebas sociales.</p>
      </details>
    </div>
  </section>

  <!-- Recursos -->
  <section id="recursos">
    <div class="container">
      <h2 class="ok">Recursos rápidos</h2>
      <div class="grid-2">
        <div class="card">
          <h3>Checklist de video</h3>
          <ul class="checked">
            <li>Gancho en 2 segundos.</li>
            <li>Texto en pantalla + subtítulos.</li>
            <li>Un beneficio principal por video.</li>
            <li>CTA claro al final.</li>
            <li>Publica cuando tu audiencia esté activa.</li>
          </ul>
        </div>
        <div class="card">
          <h3>Plantilla de propuesta (marca)</h3>
          <pre style="white-space:pre-wrap;margin:0">Hola [Marca],
Soy [Tu Nombre], creo videos de [nicho] que generan [resultado].
Propuesta: 3 videos (UGC) + 2 hooks alternativos.
Incluye: derechos orgánicos 30 días.
Precio: [€]. Ejemplos: [link].
¿Te interesa probar esta semana?</pre>
        </div>
      </div>
      <div class="card" style="margin-top:16px">
        <h3>Aviso importante</h3>
        <p>Las políticas de monetización y programas internos de la plataforma pueden cambiar por país y con el tiempo. Verifica siempre los requisitos actuales en la app o el sitio oficial antes de aplicar. Cumple normas de la comunidad y leyes locales (publicidad y afiliados deben declararse).</p>
      </div>
    </div>
  </section>

  <footer class="footer">
    <div class="container">© <span id="year"></span> TikTok Money – Guía educativa hecha por ti.</div>
  </footer>

  <script>
    // Año dinámico
    document.getElementById('year').textContent = new Date().getFullYear();
    // Menú móvil
    const btnMenu = document.getElementById('btnMenu');
    const menu = document.getElementById('menu');
    btnMenu?.addEventListener('click', () => menu.classList.toggle('open'));
  </script>
</body>
</html>
