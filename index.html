<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Guardianes del Hielo – Glaciares Argentinos</title>
  <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@700;900&family=Inter:wght@300;400;500;600&family=Space+Mono:wght@400;700&display=swap" rel="stylesheet" />
  <style>
    :root {
      --ice-deep:   #0a1628;
      --ice-mid:    #0d2240;
      --glacier:    #1a4a7a;
      --melt:       #3a8fc0;
      --shimmer:    #7fd4f0;
      --snow:       #e8f4fb;
      --white:      #ffffff;
      --gold:       #c8a84b;
      --danger:     #d64a2e;
      --text-muted: #8ab0c8;
    }

    * { margin: 0; padding: 0; box-sizing: border-box; }

    html { scroll-behavior: smooth; }

    body {
      background: var(--ice-deep);
      color: var(--snow);
      font-family: 'Inter', sans-serif;
      font-size: 16px;
      line-height: 1.7;
      overflow-x: hidden;
    }

    /* ── NAV ─────────────────────────────────────────── */
    nav {
      position: fixed; top: 0; left: 0; right: 0; z-index: 100;
      background: rgba(10, 22, 40, 0.92);
      backdrop-filter: blur(10px);
      border-bottom: 1px solid rgba(127, 212, 240, 0.15);
      padding: 14px 40px;
      display: flex; align-items: center; justify-content: space-between;
    }
    .nav-logo {
      font-family: 'Space Mono', monospace;
      font-size: 13px; font-weight: 700;
      color: var(--shimmer);
      letter-spacing: 0.12em; text-transform: uppercase;
    }
    .nav-links { display: flex; gap: 28px; list-style: none; }
    .nav-links a {
      font-size: 12px; font-weight: 500; letter-spacing: 0.08em;
      text-transform: uppercase; color: var(--text-muted);
      text-decoration: none; transition: color 0.2s;
    }
    .nav-links a:hover { color: var(--shimmer); }

    /* ── HERO ─────────────────────────────────────────── */
    .hero {
      min-height: 100vh;
      display: flex; flex-direction: column; align-items: center; justify-content: center;
      text-align: center;
      padding: 120px 40px 80px;
      position: relative; overflow: hidden;
      background: linear-gradient(170deg, var(--ice-deep) 0%, var(--ice-mid) 50%, #0b2d50 100%);
    }

    /* Glacier cracks SVG background */
    .hero::before {
      content: '';
      position: absolute; inset: 0;
      background-image:
        radial-gradient(ellipse 60% 40% at 20% 80%, rgba(26,74,122,0.5) 0%, transparent 70%),
        radial-gradient(ellipse 50% 60% at 80% 20%, rgba(58,143,192,0.2) 0%, transparent 60%);
      pointer-events: none;
    }

    /* Animated ice particles */
    .particles {
      position: absolute; inset: 0; pointer-events: none; overflow: hidden;
    }
    .particle {
      position: absolute;
      width: 3px; height: 3px;
      border-radius: 50%;
      background: var(--shimmer);
      opacity: 0;
      animation: float 8s infinite;
    }
    @keyframes float {
      0%   { opacity: 0; transform: translateY(100vh) scale(0); }
      10%  { opacity: 0.6; }
      90%  { opacity: 0.3; }
      100% { opacity: 0; transform: translateY(-20px) scale(1.5); }
    }

    .hero-eyebrow {
      font-family: 'Space Mono', monospace;
      font-size: 11px; font-weight: 700;
      letter-spacing: 0.2em; text-transform: uppercase;
      color: var(--shimmer);
      margin-bottom: 20px;
      position: relative;
    }
    .hero-eyebrow::before, .hero-eyebrow::after {
      content: '——';
      margin: 0 12px;
      opacity: 0.5;
    }

    .hero h1 {
      font-family: 'Playfair Display', serif;
      font-size: clamp(2.4rem, 6vw, 5.5rem);
      font-weight: 900;
      line-height: 1.05;
      letter-spacing: -0.02em;
      color: var(--white);
      position: relative; z-index: 1;
      max-width: 900px;
    }
    .hero h1 span { color: var(--shimmer); }

    .hero-sub {
      font-size: 1.1rem; font-weight: 300; color: var(--text-muted);
      max-width: 600px; margin: 28px auto 0;
      position: relative; z-index: 1;
    }

    .hero-meta {
      margin-top: 50px;
      display: flex; gap: 40px; justify-content: center; flex-wrap: wrap;
      position: relative; z-index: 1;
    }
    .hero-meta-item {
      text-align: center;
    }
    .hero-meta-item .label {
      font-family: 'Space Mono', monospace;
      font-size: 10px; letter-spacing: 0.15em; text-transform: uppercase;
      color: var(--text-muted);
    }
    .hero-meta-item .value {
      font-size: 1rem; font-weight: 500; color: var(--snow);
    }

    .scroll-hint {
      position: absolute; bottom: 36px; left: 50%; transform: translateX(-50%);
      display: flex; flex-direction: column; align-items: center; gap: 8px;
      font-family: 'Space Mono', monospace; font-size: 10px;
      letter-spacing: 0.12em; color: var(--text-muted);
      animation: bounce 2s ease-in-out infinite;
    }
    @keyframes bounce { 0%,100% { transform: translateX(-50%) translateY(0); } 50% { transform: translateX(-50%) translateY(6px); } }
    .scroll-hint svg { width: 18px; opacity: 0.5; }

    /* ── SECTION BASE ─────────────────────────────────── */
    section { padding: 100px 40px; max-width: 1100px; margin: 0 auto; }
    section + section { padding-top: 60px; }

    .section-tag {
      font-family: 'Space Mono', monospace;
      font-size: 10px; font-weight: 700; letter-spacing: 0.2em;
      text-transform: uppercase; color: var(--shimmer);
      margin-bottom: 12px; display: block;
    }

    h2 {
      font-family: 'Playfair Display', serif;
      font-size: clamp(1.8rem, 3.5vw, 2.8rem);
      font-weight: 700; line-height: 1.15;
      color: var(--white);
      margin-bottom: 24px;
    }

    h3 {
      font-family: 'Playfair Display', serif;
      font-size: 1.35rem; font-weight: 700;
      color: var(--snow);
      margin: 36px 0 12px;
    }

    p { color: #b8d0e0; margin-bottom: 16px; }

    .divider {
      border: none;
      border-top: 1px solid rgba(127, 212, 240, 0.12);
      margin: 0;
    }

    /* ── INTRO STRIP ──────────────────────────────────── */
    .intro-strip {
      background: linear-gradient(90deg, rgba(26,74,122,0.6), rgba(58,143,192,0.15));
      border-left: 3px solid var(--shimmer);
      padding: 32px 40px;
      margin: 0 0 60px;
      border-radius: 0 8px 8px 0;
    }
    .intro-strip p { margin: 0; font-size: 1.05rem; color: var(--snow); }

    /* ── DISCIPLINE CARDS ─────────────────────────────── */
    .discipline-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
      gap: 20px;
      margin-top: 40px;
    }
    .discipline-card {
      background: rgba(255,255,255,0.04);
      border: 1px solid rgba(127,212,240,0.12);
      border-top: 3px solid var(--shimmer);
      border-radius: 4px 4px 8px 8px;
      padding: 28px;
      transition: background 0.2s, transform 0.2s;
    }
    .discipline-card:hover {
      background: rgba(127,212,240,0.06);
      transform: translateY(-4px);
    }
    .discipline-card .area {
      font-family: 'Space Mono', monospace;
      font-size: 11px; font-weight: 700; letter-spacing: 0.15em;
      text-transform: uppercase; color: var(--shimmer);
      margin-bottom: 10px;
    }
    .discipline-card h4 {
      font-family: 'Playfair Display', serif;
      font-size: 1.15rem; font-weight: 700;
      color: var(--white); margin-bottom: 10px;
    }
    .discipline-card p { font-size: 0.9rem; color: var(--text-muted); margin: 0; }

    /* ── TABLE ────────────────────────────────────────── */
    .data-table {
      width: 100%; border-collapse: collapse;
      margin: 24px 0;
      font-size: 0.9rem;
    }
    .data-table thead tr {
      background: rgba(58,143,192,0.2);
      border-bottom: 2px solid rgba(127,212,240,0.25);
    }
    .data-table th {
      padding: 12px 16px; text-align: left;
      font-family: 'Space Mono', monospace;
      font-size: 10px; letter-spacing: 0.1em; text-transform: uppercase;
      color: var(--shimmer); font-weight: 700;
    }
    .data-table td {
      padding: 11px 16px;
      border-bottom: 1px solid rgba(127,212,240,0.08);
      color: #c0d8e8;
    }
    .data-table tbody tr:hover td { background: rgba(127,212,240,0.04); }
    .data-table td strong { color: var(--white); }

    /* ── STAT BLOCKS ──────────────────────────────────── */
    .stat-grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
      gap: 16px; margin: 40px 0;
    }
    .stat-block {
      background: rgba(255,255,255,0.03);
      border: 1px solid rgba(127,212,240,0.1);
      border-radius: 8px; padding: 24px 20px;
      text-align: center;
    }
    .stat-block .number {
      font-family: 'Playfair Display', serif;
      font-size: 2.6rem; font-weight: 900;
      color: var(--shimmer); line-height: 1;
    }
    .stat-block .unit {
      font-family: 'Space Mono', monospace;
      font-size: 11px; color: var(--text-muted);
      letter-spacing: 0.08em; margin-top: 4px;
    }
    .stat-block .desc {
      font-size: 0.82rem; color: #8ab0c8;
      margin-top: 8px;
    }

    /* ── LAW TIMELINE ─────────────────────────────────── */
    .law-timeline {
      position: relative;
      padding-left: 36px;
      margin: 32px 0;
    }
    .law-timeline::before {
      content: '';
      position: absolute; left: 8px; top: 8px; bottom: 8px;
      width: 2px;
      background: linear-gradient(to bottom, var(--shimmer), var(--danger));
    }
    .law-item {
      position: relative;
      margin-bottom: 40px;
    }
    .law-item::before {
      content: '';
      position: absolute; left: -32px; top: 6px;
      width: 12px; height: 12px;
      border-radius: 50%;
      border: 2px solid;
      background: var(--ice-deep);
    }
    .law-item.ok::before { border-color: var(--shimmer); }
    .law-item.warn::before { border-color: var(--danger); }
    .law-item .year {
      font-family: 'Space Mono', monospace;
      font-size: 12px; font-weight: 700; letter-spacing: 0.1em;
      color: var(--shimmer); margin-bottom: 6px;
    }
    .law-item.warn .year { color: var(--danger); }
    .law-item h4 {
      font-family: 'Playfair Display', serif;
      font-size: 1.2rem; color: var(--white); margin-bottom: 10px;
    }
    .law-item p { font-size: 0.92rem; margin-bottom: 8px; }

    /* ── PRO/CON ──────────────────────────────────────── */
    .procon-grid {
      display: grid; grid-template-columns: 1fr 1fr; gap: 20px;
      margin: 28px 0;
    }
    .procon-box {
      border-radius: 8px; padding: 24px;
    }
    .procon-box.pro {
      background: rgba(58,143,192,0.1);
      border: 1px solid rgba(58,143,192,0.25);
    }
    .procon-box.con {
      background: rgba(214,74,46,0.08);
      border: 1px solid rgba(214,74,46,0.25);
    }
    .procon-box h4 {
      font-family: 'Space Mono', monospace;
      font-size: 11px; letter-spacing: 0.12em; text-transform: uppercase;
      margin-bottom: 14px;
    }
    .procon-box.pro h4 { color: var(--shimmer); }
    .procon-box.con h4 { color: var(--danger); }
    .procon-box ul { list-style: none; padding: 0; }
    .procon-box li {
      font-size: 0.88rem; color: #b8d0e0;
      padding: 5px 0; padding-left: 18px;
      position: relative;
    }
    .procon-box.pro li::before { content: '+'; position: absolute; left: 0; color: var(--shimmer); font-weight: 700; }
    .procon-box.con li::before { content: '−'; position: absolute; left: 0; color: var(--danger); font-weight: 700; }

    /* ── QUOTE ────────────────────────────────────────── */
    blockquote {
      border-left: 3px solid var(--gold);
      padding: 20px 28px;
      margin: 28px 0;
      background: rgba(200,168,75,0.06);
      border-radius: 0 8px 8px 0;
    }
    blockquote p {
      font-family: 'Playfair Display', serif;
      font-size: 1.05rem; font-style: italic;
      color: var(--snow); margin: 0 0 8px;
    }
    blockquote cite {
      font-size: 0.8rem; color: var(--gold);
      font-family: 'Space Mono', monospace;
      letter-spacing: 0.08em; font-style: normal;
    }

    /* ── MATH SECTION ─────────────────────────────────── */
    .math-box {
      background: rgba(255,255,255,0.03);
      border: 1px solid rgba(127,212,240,0.15);
      border-radius: 8px; padding: 28px;
      margin: 24px 0;
    }
    .math-box h4 {
      font-family: 'Space Mono', monospace;
      font-size: 12px; letter-spacing: 0.1em; text-transform: uppercase;
      color: var(--shimmer); margin-bottom: 16px;
    }
    .formula {
      font-family: 'Space Mono', monospace;
      font-size: 1.1rem;
      color: var(--gold);
      background: rgba(200,168,75,0.08);
      border-radius: 6px; padding: 14px 20px;
      display: inline-block; margin: 10px 0;
    }
    .math-result {
      font-size: 1rem; font-weight: 600; color: var(--shimmer);
      margin-top: 12px;
    }

    /* ── MUSIC SECTION ────────────────────────────────── */
    .music-section {
      background: linear-gradient(135deg, rgba(26,74,122,0.3), rgba(13,34,64,0.8));
      border-radius: 12px; padding: 50px 40px;
      border: 1px solid rgba(127,212,240,0.15);
      text-align: center; position: relative; overflow: hidden;
    }
    .music-section::before {
      content: '♪';
      position: absolute; font-size: 200px; opacity: 0.03;
      top: -20px; right: 20px; color: var(--shimmer);
      line-height: 1; pointer-events: none;
    }
    .music-section h3 { font-size: 1.8rem; margin: 0 0 14px; }
    .music-section p { color: var(--text-muted); max-width: 580px; margin: 0 auto 32px; }

    /* ── BOTELLOFONO ──────────────────────────────────── */
    .botellofono-grid {
      display: grid; grid-template-columns: 1fr 1fr; gap: 24px; margin: 28px 0;
    }
    .botellofono-info {
      background: rgba(255,255,255,0.03);
      border: 1px solid rgba(127,212,240,0.1);
      border-radius: 8px; padding: 24px;
    }

    /* ── YOUTUBE BUTTON ───────────────────────────────── */
    .yt-btn {
      display: inline-flex; align-items: center; gap: 12px;
      background: #ff0000;
      color: #fff;
      text-decoration: none;
      padding: 16px 32px;
      border-radius: 8px;
      font-family: 'Inter', sans-serif;
      font-size: 1rem; font-weight: 600;
      transition: background 0.2s, transform 0.15s, box-shadow 0.2s;
      box-shadow: 0 4px 20px rgba(255,0,0,0.3);
    }
    .yt-btn:hover {
      background: #cc0000;
      transform: translateY(-2px);
      box-shadow: 0 8px 30px rgba(255,0,0,0.4);
    }
    .yt-btn svg { width: 24px; height: 24px; fill: white; }

    /* ── CONCLUSION ───────────────────────────────────── */
    .conclusion-grid {
      display: grid; grid-template-columns: repeat(auto-fit, minmax(260px, 1fr));
      gap: 20px; margin: 36px 0;
    }
    .conclusion-card {
      background: rgba(255,255,255,0.03);
      border: 1px solid rgba(127,212,240,0.1);
      border-top: 3px solid var(--glacier);
      border-radius: 4px 4px 8px 8px;
      padding: 24px;
    }
    .conclusion-card.geo { border-top-color: var(--shimmer); }
    .conclusion-card.mat { border-top-color: var(--gold); }
    .conclusion-card.art { border-top-color: #a78bd4; }
    .conclusion-card .icon {
      font-size: 1.8rem; margin-bottom: 12px;
    }
    .conclusion-card h4 {
      font-family: 'Space Mono', monospace;
      font-size: 11px; letter-spacing: 0.12em; text-transform: uppercase;
      margin-bottom: 12px;
    }
    .conclusion-card.geo h4 { color: var(--shimmer); }
    .conclusion-card.mat h4 { color: var(--gold); }
    .conclusion-card.art h4 { color: #a78bd4; }
    .conclusion-card ul { list-style: none; padding: 0; }
    .conclusion-card li {
      font-size: 0.88rem; color: #b8d0e0;
      padding: 4px 0; padding-left: 14px;
      position: relative;
    }
    .conclusion-card li::before {
      content: '→'; position: absolute; left: 0;
      font-size: 0.75rem; top: 5px; opacity: 0.6;
    }

    /* ── BIBLIO ───────────────────────────────────────── */
    .biblio-list {
      list-style: none; padding: 0;
    }
    .biblio-list li {
      padding: 10px 0 10px 20px;
      border-bottom: 1px solid rgba(127,212,240,0.06);
      font-size: 0.88rem; color: #8ab0c8;
      position: relative;
    }
    .biblio-list li::before {
      content: '–';
      position: absolute; left: 0; color: var(--shimmer);
    }

    /* ── FULL-WIDTH SEPARATOR ─────────────────────────── */
    .full-divider {
      width: 100%; border: none;
      border-top: 1px solid rgba(127,212,240,0.08);
    }

    /* ── FOOTER ───────────────────────────────────────── */
    footer {
      background: rgba(0,0,0,0.4);
      border-top: 1px solid rgba(127,212,240,0.1);
      padding: 40px;
      text-align: center;
    }
    footer p {
      font-size: 0.82rem; color: var(--text-muted); margin: 0;
    }

    /* ── RESPONSIVE ───────────────────────────────────── */
    @media (max-width: 700px) {
      nav { padding: 14px 20px; }
      .nav-links { display: none; }
      section { padding: 70px 20px; }
      .procon-grid { grid-template-columns: 1fr; }
      .botellofono-grid { grid-template-columns: 1fr; }
      .hero { padding: 100px 24px 70px; }
      .hero-meta { gap: 24px; }
    }
  </style>
</head>
<body>

<!-- NAV -->
<nav>
  <div class="nav-logo">Guardianes del Hielo</div>
  <ul class="nav-links">
    <li><a href="#intro">Introducción</a></li>
    <li><a href="#marco">Marco Teórico</a></li>
    <li><a href="#leyes">Marco Legal</a></li>
    <li><a href="#datos">Datos</a></li>
    <li><a href="#arte">Arte</a></li>
    <li><a href="#conclusion">Conclusión</a></li>
  </ul>
</nav>

<!-- HERO -->
<div class="hero">
  <div class="particles" id="particles"></div>

  <div class="hero-eyebrow">Trabajo de Investigación · Feria de Ciencias 2026</div>

  <h1>Guardianes del <span>Hielo</span></h1>
  <p class="hero-sub">Los Glaciares Argentinos — ¿Por qué es importante cuidar nuestras reservas de agua dulce?</p>

  <div class="hero-meta">
    <div class="hero-meta-item">
      <div class="label">Curso</div>
      <div class="value">4to B</div>
    </div>
    <div class="hero-meta-item">
      <div class="label">Fecha</div>
      <div class="value">Junio 2026</div>
    </div>
  </div>

  <div class="scroll-hint">
    EXPLORAR
    <svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
      <polyline points="6 9 12 15 18 9"/>
    </svg>
  </div>
</div>

<!-- ─ INTRO ─ -->
<section id="intro">
  <span class="section-tag">01 · Introducción</span>
  <h2>Un problema que nos toca de cerca</h2>

  <div class="intro-strip">
    <p>Este proyecto nace de la necesidad de comprender y visibilizar el rol crítico que cumplen los glaciares en nuestro territorio. Lejos de ser estructuras aisladas, son las principales reservas de agua dulce del país y actúan como reguladores climáticos e hídricos fundamentales.</p>
  </div>

  <p>Para abordar una problemática tan compleja y multidimensional, este trabajo se estructuró de manera <strong>interdisciplinaria</strong>, articulando saberes y metodologías desde tres áreas distintas: <strong>Geografía</strong>, <strong>Matemática</strong> y <strong>Lenguaje Artístico (Música)</strong>.</p>

  <div class="discipline-grid">
    <div class="discipline-card">
      <div class="area">Geografía</div>
      <h4>Dimensión socioambiental y política</h4>
      <p>Análisis de la Ley de Glaciares y sus modificaciones. Concepto de "seguridad hídrica".</p>
    </div>
    <div class="discipline-card">
      <div class="area">Matemática</div>
      <h4>Análisis estadístico y cuantitativo</h4>
      <p>Cálculo de porcentajes, tasas de retroceso y proyecciones del deshielo.</p>
    </div>
    <div class="discipline-card">
      <div class="area">Lenguaje Artístico · Música</div>
      <h4>Concientización y expresión artística</h4>
      <p>Composición de canciones y construcción de instrumentos reciclados.</p>
    </div>
  </div>
</section>

<hr class="full-divider" />

<!-- ─ MARCO TEÓRICO ─ -->
<section id="marco">
  <span class="section-tag">02 · Marco Teórico</span>
  <h2>Qué son los glaciares y por qué importan</h2>

  <p>Una <strong>reserva de agua dulce</strong> es el volumen de agua con baja concentración de sales disponible en el planeta. Aunque la Tierra está compuesta en un 70% por agua, solo el <strong>2,5%</strong> es agua dulce, y el resto es agua salada no consumible.</p>

  <div class="stat-grid">
    <div class="stat-block">
      <div class="number">70%</div>
      <div class="unit">del agua dulce</div>
      <div class="desc">almacenada en glaciares</div>
    </div>
    <div class="stat-block">
      <div class="number">~17.000</div>
      <div class="unit">cuerpos de hielo</div>
      <div class="desc">registrados en Argentina</div>
    </div>
    <div class="stat-block">
      <div class="number">39</div>
      <div class="unit">cuencas hídricas</div>
      <div class="desc">alimentadas por glaciares</div>
    </div>
    <div class="stat-block">
      <div class="number">7M</div>
      <div class="unit">personas</div>
      <div class="desc">dependen del agua de deshielo</div>
    </div>
  </div>

  <h3>¿Cómo se formaron los glaciares argentinos?</h3>
  <p>Los glaciares argentinos se formaron durante el <strong>Pleistoceno</strong> (hace aprox. 1.600.000 a 10.000 años), cuando las glaciaciones modelaron la cordillera de los Andes. El avance y retroceso de los hielos excavó profundos valles que, al retirarse, se llenaron de agua formando los lagos que hoy conocemos (Nahuel Huapi, Argentino, Viedma, etc.).</p>

  <p>Hoy, el <strong>Campo de Hielo Patagónico Sur</strong> es la mayor reserva de agua dulce del hemisferio sur después de la Antártida.</p>

  <h3>Localización: Provincias con más glaciares</h3>
  <table class="data-table">
    <thead>
      <tr>
        <th>Provincia</th>
        <th>Cantidad de glaciares</th>
      </tr>
    </thead>
    <tbody>
      <tr><td><strong>San Juan</strong></td><td>4.572</td></tr>
      <tr><td><strong>Mendoza</strong></td><td>4.172</td></tr>
      <tr><td><strong>Santa Cruz</strong></td><td>2.420</td></tr>
    </tbody>
  </table>
  <p>Estos glaciares alimentan 39 cuencas hídricas que abastecen a más de <strong>1.800 localidades</strong>, donde viven aproximadamente <strong>7 millones de personas</strong> (el 18% de la población nacional).</p>

  <h3>El ambiente periglacial: una reserva invisible</h3>
  <p>El <strong>ambiente periglacial</strong> es la zona alrededor de los glaciares donde el suelo permanece congelado gran parte del año. Funciona como una "esponja subterránea" que almacena agua en forma de hielo, pudiendo contener entre un <strong>35% y 70%</strong> de hielo en su interior.</p>

  <blockquote>
    <p>"Existe un gran número de geoformas del ambiente periglacial que cumplen un rol hidrológico, climático y ecológico de gran relevancia al igual que los glaciares."</p>
    <cite>— Marco teórico del proyecto</cite>
  </blockquote>
</section>

<hr class="full-divider" />

<!-- ─ MARCO LEGAL ─ -->
<section id="leyes">
  <span class="section-tag">03 · Marco Legal</span>
  <h2>La Ley de Glaciares: protección en disputa</h2>

  <div class="law-timeline">
    <div class="law-item ok">
      <div class="year">2010 — Ley 26.639</div>
      <h4>Presupuestos mínimos de protección</h4>
      <p>Sancionada el 30 de septiembre de 2010, estableció los presupuestos mínimos para la preservación de los glaciares y del ambiente periglacial en todo el territorio argentino. Considera a ambos como <strong>reservas estratégicas de agua dulce</strong>.</p>
      <ul style="list-style:none;padding:0;">
        <li style="font-size:0.88rem;color:#b8d0e0;padding:3px 0 3px 16px;position:relative;">
          <span style="position:absolute;left:0;color:var(--shimmer)">✓</span> Protección amplia de todos los glaciares
        </li>
        <li style="font-size:0.88rem;color:#b8d0e0;padding:3px 0 3px 16px;position:relative;">
          <span style="position:absolute;left:0;color:var(--shimmer)">✓</span> Principio precautorio pleno
        </li>
        <li style="font-size:0.88rem;color:#b8d0e0;padding:3px 0 3px 16px;position:relative;">
          <span style="position:absolute;left:0;color:var(--shimmer)">✓</span> Prohibición de minería en zonas glaciares
        </li>
        <li style="font-size:0.88rem;color:#b8d0e0;padding:3px 0 3px 16px;position:relative;">
          <span style="position:absolute;left:0;color:var(--shimmer)">✓</span> Inventario Nacional de Glaciares (IANIGLA)
        </li>
      </ul>
    </div>

    <div class="law-item warn">
      <div class="year">2026 — Ley 27.804 ⚠</div>
      <h4>Modificaciones y debate actual</h4>
      <p>En <strong>abril de 2026</strong>, mientras el mundo discute cómo enfrentar la crisis climática, se promulgó en Argentina esta ley que modifica sustancialmente la Ley de Glaciares.</p>

      <table class="data-table" style="margin-top:16px;">
        <thead>
          <tr>
            <th>Aspecto</th>
            <th>Ley 26.639 (2010)</th>
            <th>Ley 27.804 (2026)</th>
          </tr>
        </thead>
        <tbody>
          <tr>
            <td>Objeto de protección</td>
            <td>Todos los glaciares</td>
            <td>Solo los de "función hídrica efectiva"</td>
          </tr>
          <tr>
            <td>Principio precautorio</td>
            <td>Aplicación plena</td>
            <td>Aplicación limitada</td>
          </tr>
          <tr>
            <td>Rol de las provincias</td>
            <td>Cooperación con la Nación</td>
            <td>Decisión central</td>
          </tr>
          <tr>
            <td>Inventario Nacional</td>
            <td>Todos los glaciares</td>
            <td>Solo con función hídrica</td>
          </tr>
        </tbody>
      </table>

      <blockquote style="margin-top:20px;">
        <p>"Es una reforma que está a contramano de la evidencia científica y que gana en inseguridad jurídica."</p>
        <cite>— Especialistas, Facultad de Derecho – UBA</cite>
      </blockquote>
    </div>
  </div>

  <h3>Aspectos positivos y negativos de la reforma</h3>
  <div class="procon-grid">
    <div class="procon-box pro">
      <h4>Postura del Gobierno</h4>
      <ul>
        <li>Promete entrada masiva de capitales al país</li>
        <li>Ajusta la ley a los intereses de inversionistas</li>
        <li>Señala que algunas zonas protegidas estaban "mal controladas"</li>
      </ul>
    </div>
    <div class="procon-box con">
      <h4>Postura de ambientalistas y científicos</h4>
      <ul>
        <li>Riesgo de abuso de territorios glaciares por mineras</li>
        <li>Falta de control en zonas alejadas</li>
        <li>Potencial contaminación a largo plazo</li>
        <li>Violación del Acuerdo de Escazú</li>
      </ul>
    </div>
  </div>
</section>

<hr class="full-divider" />

<!-- ─ PROBLEMÁTICA ─ -->
<section>
  <span class="section-tag">04 · Problemática Central</span>
  <h2>Riesgos del deshielo acelerado</h2>

  <p>El calentamiento global está acelerando el derretimiento de los glaciares a un ritmo sin precedentes. Según datos de la <strong>NASA</strong> y el <strong>IPCC</strong>:</p>

  <table class="data-table">
    <thead>
      <tr><th>Indicador</th><th>Dato</th></tr>
    </thead>
    <tbody>
      <tr><td>Pérdida de masa glaciar en Groenlandia (1985–2022)</td><td><strong>1.140 mil millones de toneladas</strong></td></tr>
      <tr><td>Proyección de pérdida en Andes tropicales para 2100</td><td><strong>80%</strong></td></tr>
      <tr><td>Glaciares que retroceden en el mundo</td><td><strong>90%</strong></td></tr>
    </tbody>
  </table>

  <p>En Argentina, el glaciar <strong>Perito Moreno</strong> —considerado estable durante décadas— comenzó a retroceder aceleradamente, con un adelgazamiento de hasta <strong>8 metros por año</strong>.</p>

  <blockquote>
    <p>"Vamos a recurrir a todas las herramientas necesarias. El Acuerdo de Escazú está vigente y el Estado tiene que cumplirlo."</p>
    <cite>— Legisladora argentina</cite>
  </blockquote>
</section>

<hr class="full-divider" />

<!-- ─ MATEMÁTICA ─ -->
<section id="datos">
  <span class="section-tag">05 · Análisis desde la Matemática</span>
  <h2>Los números detrás del deshielo</h2>

  <table class="data-table">
    <thead>
      <tr><th>Indicador</th><th>Valor</th></tr>
    </thead>
    <tbody>
      <tr><td>Glaciares en Argentina</td><td><strong>~17.000</strong></td></tr>
      <tr><td>Superficie glaciar continental</td><td><strong>5.765 km²</strong></td></tr>
      <tr><td>Cuencas hídricas alimentadas</td><td><strong>39</strong></td></tr>
      <tr><td>Población dependiente</td><td><strong>7.000.000+ (18% del país)</strong></td></tr>
      <tr><td>Pérdida anual Perito Moreno</td><td><strong>Hasta 8 m/año</strong></td></tr>
    </tbody>
  </table>

  <div class="math-box">
    <h4>Ejercicio 1 — Porcentaje de población afectada</h4>
    <p style="font-size:0.9rem;color:#8ab0c8;">Si Argentina tiene 46 millones de habitantes y 7 millones dependen del agua de deshielo:</p>
    <div class="formula">7.000.000 ÷ 46.000.000 × 100 = 15,2%</div>
    <p class="math-result">Más del 15% de la población argentina depende del agua de glaciares.</p>
  </div>

  <div class="math-box">
    <h4>Ejercicio 2 — Proyección de pérdida de agua</h4>
    <p style="font-size:0.9rem;color:#8ab0c8;">Si un glaciar de 1 km² pierde anualmente el 1% de su masa:</p>
    <table class="data-table" style="margin-top:12px;">
      <thead><tr><th>Años</th><th>Pérdida acumulada</th></tr></thead>
      <tbody>
        <tr><td>10 años</td><td><strong>10%</strong></td></tr>
        <tr><td>50 años</td><td><strong>50%</strong></td></tr>
        <tr><td>100 años</td><td><strong>100%</strong></td></tr>
      </tbody>
    </table>
    <p class="math-result" style="margin-top:12px;">Estos modelos matemáticos permiten traducir el fenómeno del derretimiento en datos concretos y objetivos.</p>
  </div>
</section>

<hr class="full-divider" />

<!-- ─ ARTE Y MÚSICA ─ -->
<section id="arte">
  <span class="section-tag">06 · Lenguaje Artístico y Música</span>
  <h2>El arte como herramienta de conciencia</h2>

  <p>El arte se constituyó como el canal fundamental para la sensibilización comunitaria. <strong>La música tiene el poder de emocionar y movilizar</strong> de una manera que los datos estadísticos solos no logran.</p>

  <div class="botellofono-grid">
    <div class="botellofono-info">
      <h3 style="margin-top:0;">🎵 El Botellófono</h3>
      <p style="font-size:0.9rem;">Un instrumento musical construido con botellas de vidrio o plástico que producen diferentes sonidos según la cantidad de agua que contienen. Su construcción con <strong>materiales reciclados</strong> promueve la reutilización de objetos y la reducción de residuos.</p>
      <p style="font-size:0.9rem;">Cuando una botella es golpeada, el material vibra y esas vibraciones se transmiten al agua y al aire interior. Si contiene más agua, las vibraciones son más lentas y el sonido resulta más <strong>grave</strong>; si tiene menos agua, más rápido y <strong>agudo</strong>.</p>
      <p style="font-size:0.82rem;color:var(--text-muted);margin:0;">Fundamento científico: Hermann von Helmholtz</p>
    </div>
    <div class="botellofono-info">
      <h3 style="margin-top:0;">🤖 Canción con IA</h3>
      <p style="font-size:0.9rem;">Utilizamos <strong>Suno</strong>, una herramienta que genera música a partir de instrucciones escritas. La IA fue entrenada con innumerables canciones, aprendiendo estilos, melodías, ritmos y armonías.</p>
      <p style="font-size:0.9rem;">A partir de una idea escrita por nosotros, generamos canciones relacionadas con el cuidado del agua y la protección de los glaciares argentinos. Así unimos <strong>música, tecnología y conciencia ambiental</strong>.</p>
      <p style="font-size:0.82rem;color:var(--text-muted);margin:0;">La IA no reemplaza la creatividad humana, sino que ayuda a comunicar ideas.</p>
    </div>
  </div>

  <!-- Canción de concientización -->
  <div class="music-section" style="margin-top:40px;">
    <h3>🎵 Canción de Concientización</h3>
    <p>Escuchá la canción que creamos para concienciar sobre la importancia de proteger los glaciares argentinos. Arte, tecnología e inteligencia artificial al servicio del medioambiente.</p>
    <a href="https://youtube.com/@feriadeciencias_2026?si=RgRLnWyaf5uS-V5N" target="_blank" rel="noopener noreferrer" class="yt-btn">
      <svg viewBox="0 0 24 24" xmlns="http://www.w3.org/2000/svg">
        <path d="M23.498 6.186a3.016 3.016 0 0 0-2.122-2.136C19.505 3.545 12 3.545 12 3.545s-7.505 0-9.377.505A3.017 3.017 0 0 0 .502 6.186C0 8.07 0 12 0 12s0 3.93.502 5.814a3.016 3.016 0 0 0 2.122 2.136c1.871.505 9.376.505 9.376.505s7.505 0 9.377-.505a3.015 3.015 0 0 0 2.122-2.136C24 15.93 24 12 24 12s0-3.93-.502-5.814zM9.545 15.568V8.432L15.818 12l-6.273 3.568z"/>
      </svg>
      Ver en YouTube
    </a>
  </div>
</section>

<hr class="full-divider" />

<!-- ─ CONCLUSIÓN ─ -->
<section id="conclusion">
  <span class="section-tag">07 · Conclusión</span>
  <h2>Lo que aprendimos</h2>

  <div class="conclusion-grid">
    <div class="conclusion-card geo">
      <div class="icon">🌍</div>
      <h4>Desde la Geografía</h4>
      <ul>
        <li>Los glaciares son reservas estratégicas que abastecen a millones</li>
        <li>La Ley 27.804 fragmenta el federalismo ambiental</li>
        <li>Las cuencas hídricas no reconocen límites políticos</li>
      </ul>
    </div>
    <div class="conclusion-card mat">
      <div class="icon">📊</div>
      <h4>Desde la Matemática</h4>
      <ul>
        <li>~17.000 glaciares, 39 cuencas, 7M de personas dependientes</li>
        <li>El 80% de glaciares andinos puede desaparecer para 2100</li>
        <li>Los datos traducen la urgencia de manera objetiva</li>
      </ul>
    </div>
    <div class="conclusion-card art">
      <div class="icon">🎨</div>
      <h4>Desde el Arte</h4>
      <ul>
        <li>El arte puede sensibilizar y defender el territorio</li>
        <li>El botellófono demuestra ciencia + creatividad</li>
        <li>Arte y ciencia colaboran en conciencia ambiental</li>
      </ul>
    </div>
  </div>

  <blockquote>
    <p>"La protección de los glaciares debe ser una política de Estado de largo plazo. El agua no es un recurso más: es la condición de posibilidad de la vida."</p>
    <cite>— Reflexión final del proyecto</cite>
  </blockquote>
</section>

<hr class="full-divider" />

<!-- ─ BIBLIOGRAFÍA ─ -->
<section>
  <span class="section-tag">08 · Bibliografía</span>
  <h2>Fuentes consultadas</h2>

  <h3>Normativas</h3>
  <ul class="biblio-list">
    <li>Ley 26.639 – Régimen de Presupuestos Mínimos para la Preservación de los Glaciares (2010)</li>
    <li>Ley 27.804 – Modificación de la Ley 26.639 (2026)</li>
    <li>Ley 25.675 – Ley General del Ambiente (2002)</li>
    <li>Ley 27.566 – Acuerdo de Escazú (aprobación)</li>
  </ul>

  <h3>Artículos y Sitios Web</h3>
  <ul class="biblio-list">
    <li>Delalenga.com.ar (2026). <em>Glaciares: La reforma normativa enfría garantías y derrite certezas ambientales.</em></li>
    <li>France 24 (2026). <em>¿Peligra el agua en Argentina? El Congreso de Milei cambia la Ley de Glaciares.</em> YouTube.</li>
    <li>Fundación Vida Silvestre Argentina (2025). <em>No a la reforma de la ley de Glaciares.</em></li>
    <li>Greenpeace Argentina (2025). <em>Glaciares: guardianes del agua del planeta.</em></li>
    <li>Barroso, L. (2026). <em>Ley de Glaciares en Argentina: Minería, agua y la disputa política y económica.</em> Realpolitik.</li>
  </ul>

  <h3>Organismos Científicos</h3>
  <ul class="biblio-list">
    <li>IANIGLA – Inventario Nacional de Glaciares</li>
    <li>IPCC – Panel Intergubernamental sobre Cambio Climático</li>
    <li>NASA – Estudios sobre pérdida de masa glaciar</li>
  </ul>
</section>

<!-- FOOTER -->
<footer>
  <p>Trabajo de Investigación · 4to B · Feria de Ciencias 2026 &nbsp;·&nbsp; Guardianes del Hielo: Los Glaciares Argentinos</p>
  <p style="margin-top:8px;">Docentes: Lourdes Alcaraz (Lenguaje Artístico) · Miguel González (Matemáticas) · Lucía Gorosito (Geografía)</p>
</footer>

<script>
  // Ice particles
  const container = document.getElementById('particles');
  for (let i = 0; i < 40; i++) {
    const p = document.createElement('div');
    p.className = 'particle';
    p.style.cssText = `
      left: ${Math.random() * 100}%;
      width: ${Math.random() * 4 + 2}px;
      height: ${Math.random() * 4 + 2}px;
      animation-delay: ${Math.random() * 8}s;
      animation-duration: ${Math.random() * 6 + 6}s;
    `;
    container.appendChild(p);
  }
</script>
</body>
</html>
