<html lang="ru">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <meta name="description" content="Павел — финансовый аналитик + AI. Финансовые модели, инвестиционный анализ, NPV, IRR, дашборды и AI-решения для бизнеса." />
  <title>Павел — Финансовый аналитик + AI</title>
  <style>
    :root {
      --bg: #07111f;
      --bg2: #0c1930;
      --card: rgba(8, 18, 34, 0.72);
      --line: rgba(126, 197, 255, 0.16);
      --text: #edf6ff;
      --muted: #9fb6d3;
      --accent: #73bfff;
      --accent2: #8bf3ff;
      --success: #8fffe4;
      --danger: #ff9eb2;
      --shadow: 0 20px 60px rgba(0,0,0,.34);
      --radius: 24px;
      --max: 1220px;
    }

    * { box-sizing: border-box; margin: 0; padding: 0; }
    html { scroll-behavior: smooth; }
    body {
      font-family: Inter, Arial, sans-serif;
      color: var(--text);
      background:
        radial-gradient(circle at 10% 10%, rgba(115,191,255,.16), transparent 26%),
        radial-gradient(circle at 85% 20%, rgba(139,243,255,.10), transparent 20%),
        linear-gradient(135deg, #05101d, #0c1930 55%, #081423);
      min-height: 100vh;
      overflow-x: hidden;
    }

    body::before,
    body::after {
      content: "";
      position: fixed;
      inset: 0;
      pointer-events: none;
      z-index: 0;
    }

    body::before {
      background-image:
        linear-gradient(rgba(255,255,255,.03) 1px, transparent 1px),
        linear-gradient(90deg, rgba(255,255,255,.03) 1px, transparent 1px);
      background-size: 40px 40px;
      mask-image: radial-gradient(circle at center, black 40%, transparent 88%);
    }

    body::after {
      background: radial-gradient(circle at 50% 0%, rgba(115,191,255,.16), transparent 40%);
      filter: blur(30px);
      opacity: .85;
      animation: pulseGlow 7s ease-in-out infinite;
    }

    @keyframes pulseGlow {
      0%,100% { transform: scale(1); opacity: .65; }
      50% { transform: scale(1.08); opacity: .95; }
    }

    @keyframes floatCard {
      0%,100% { transform: translateY(0); }
      50% { transform: translateY(-8px); }
    }

    .container {
      width: min(var(--max), calc(100% - 28px));
      margin: 0 auto;
      position: relative;
      z-index: 1;
    }

    .nav {
      display: flex;
      justify-content: space-between;
      align-items: center;
      gap: 16px;
      padding: 22px 0;
      position: sticky;
      top: 0;
      z-index: 10;
      backdrop-filter: blur(14px);
    }

    .brand {
      display: flex;
      align-items: center;
      gap: 12px;
      font-weight: 800;
      letter-spacing: -.02em;
    }

    .brand-badge {
      width: 40px;
      height: 40px;
      border-radius: 14px;
      display: grid;
      place-items: center;
      background: linear-gradient(135deg, var(--accent), var(--accent2));
      color: #05101d;
      box-shadow: 0 10px 30px rgba(115,191,255,.28);
    }

    .nav-links {
      display: flex;
      flex-wrap: wrap;
      gap: 12px;
      align-items: center;
    }

    .nav-links a {
      color: var(--muted);
      text-decoration: none;
      padding: 10px 14px;
      border-radius: 999px;
      transition: .2s ease;
    }

    .nav-links a:hover { color: var(--text); background: rgba(255,255,255,.05); }

    .hero {
      display: grid;
      grid-template-columns: 430px 1fr;
      gap: 34px;
      align-items: center;
      padding: 26px;
      border: 1px solid var(--line);
      border-radius: 34px;
      background: linear-gradient(180deg, rgba(11,22,42,.82), rgba(7,15,29,.72));
      box-shadow: var(--shadow);
      backdrop-filter: blur(18px);
      overflow: hidden;
    }

    .hero-media {
      position: relative;
      min-height: 640px;
      border-radius: 28px;
      border: 1px solid rgba(255,255,255,.08);
      overflow: hidden;
      background:
        linear-gradient(rgba(7,17,31,.10), rgba(7,17,31,.20)),
        url('data:image/jpeg;base64,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P6Pj+M7a27Nscu8Unuikd/g2tzsd7xupgP6eNtZ7dcD7H9eh9V/gtw8/7rM7vcLphHn7eS41ludS3b9bxtn1FuOUtF0P8A6GvHf4L/AOX5jAOOcs85Z5yxzrnnLPOWecs8555yn3OOOecp9zjnnHKOec8555yxznnnLPOWec8555yzzlnnLPOWec8555z7nHPOOeecs8555zznnnnnnPOeec+5xzzjnnnPOeec8555zzznnnnPOeec+5xzzjnnnPOeec8555zzznnnnPOeec+5xzzjnnnPOeec8555zzznnnnPOeec+5xzzjnnnPOeec8555zzznnnnPOeec+5xzzjnnnPOeec8555zzznnnnPOeec+5xzzjnnnPOeec8555zzznnnnPOeec+5xzzjnnnPOeec8555zzznnnnPOeec+5xzzjnnnPOeec8555zzznnnnPOeec+5xzzjnnnPOeec8555zzznnnnPOeec+5xzzjnnnPOeec8555zzznnnnPOeec+5xzzjnnnPOeec8555zzznnnnPOeec+5xzzjnnnPOeec8555zzznnnnPOeec+5xzzjnnnPOeec8555zzznnnnPOeec+5xzzjnnnPOeec8555zzznnnnPOeec+5xzzjnnnPOeec8555zzznnnnPOeec+5xzzjnnnPOeec8555zzznnnnPOeec+5xzzjnnnPOeec8555zzznnnnPOeec+5xzzjnnnPOeec8555zzznnnnPOeec+5xzzjnnnPOeec8555zzznnnnPOeec+5xzzjnnnPOeec8555zzznnnnPOeec+5xzzjnnnPOeec8555zzznnnnPOeec+5xzzjnnnPOeec8555zzznnnnPOeec+5xzzjnnnPOeec8555zzznnnnPOeec+5xzzjnnnPOeec8555zzznnnnPOeec+5xzzjnnnPOeec8555zzznnnnPOeec+5xzzjnnnPOeec8555zzznnnnPOeec+5xzzjnnnPOeec8555zzznnnnPOeec+5xzzjnnnPOeec8555zzznnnnPOeec+5xzzjnnnPOeec8555zzznnnnPOeec+5xzzjnnnPOeec8555zzznnnnPOeec+5xzzjnnnPOeec8555zzznnnnPOeec+5xzzjnnnPOeec8555zzznnnnPOeec+5xzzjnnnPOeec8555zzznnnnPOeec+5xzzjnnnPOeec8555zzznnnnPOeec+5xzzjnnnPOeec8555zzznnnnPOeec+5xzzjnnnPOeec8555zzznnnnPOeec+5xzzjnnnPOeec8555zzznnnnPOeec+5xzzjnnnPOeec8555zzznnnnPOeec+5xzzjnnnPOeec8555zzznnnnPOeec+5xzzjnnnPOeec8555zzznnnnPOeec+5xzzjnnnPOeec8555zzznnnnPOeec+5xzzjnnnPOeec8555zzznnnnPOeec+5xzzjnnnPOeec8555zzznnnnPOeec+5xzzjnnnPOeec8555zzznnnnPOeec+5xzzjnnnPOeec8555zzznnnnPOeec+5xzzjnnnPOeec8555zzznnnnPOeec+5xzzjnnnPOeec8555zzznnnnPOeec+5xzzjnnnPOeec8555zzznnnnPOeec+5xzzjnnnPOeec8555zzznnnnPOeec+5xzzjnnnPOeec8555zzznnnnPOeec+5xzzjnnnPOeec8555zzznnnnPOeec+5xzzjnnnPOeec8555zzznnnnPOeec+5xzzjnnnPOeec8555zzznnnnPOeec+5xzzjnnnPOeec8555zzznnnnPOeec+5xzzjnnnPOeec8555zzznnnnPOeec+5xzzjnnnPOeec8555zzznnnnPOeec+5xzzjnnnPOeec8555zzznnnnPOeec+5xzzjnnnPOeec8555zzznnnnPOeec+5xzzjnnnPOeec8555zzznnnnPOeec+5xzzjnnnPOeec8555zzznnnnPOeec+5xzzjnnnPOeec8555zzznnnnPOeec+5xzzjnnnPOeec8555zzznnnnPOeec+5xzzjnnnPOeec8555zzznnnnPOeec+5xzzjnnnPOeec8555zzznnnnPOeec+5xzzjnnnPOeec8555zzznnnnPOeec+5xzzjnnnPOeec8555zzznnnnPOeec+5xzzjnnnPOeec8555zzznnnnPOeec+5xzzjnnnPOeec8555zzznnnnPOeec+5xzzjnnnPOeec8555zzznnnnPOeec+5xzzjnnnPOeec8555zzznnnnPOeec+5xzzjnnnPOeec8555zzznnnnPOeec+5xzzjnnnPOeec8555zzznnnnPOeec+5xzzjnnnPOeec8555zzznnnnPOeec+5xzzjnnnPOeec8555zzznnnnPOeec+5xzzjnnnPOeec8555zzznnnnPOeec+5xzzjnnnPOeec8555zzznnnnPOeec+5xzzjnnnPOeec8555zzznnnnPOeec+5xzzjnnnPOeec8555zzznnnnPOeec+5xzzjnnnPOeec8555zzznnnnPOeec+5xzzjnnnPOeec8555zzznnnnPOeec+5xzzjnnnPOeec8555zzznnnnPOeec+5xzzjnnnPOeec8555zzznnnnPOeec+5xzzjnnnPOeec8555zzznnnnPOeec+5xzzjnnnPOeec8555zzznnnnPOeec+5xzzjnnnPOeec8555zzznnnnPOeec+5xzzjnnnPOeec8555zzznnnnPOeec+5xzzjnnnPOeec8555zzznnnnPOeec+5xzzjnnnPOeec8555zzznnnnPOeec+5xzzjnnnPOeec8555zzznnnnPOeec+5xzzjnnnPOeec8555zzznnnnPOeec+5xzzjnnnPOeec8555zzznnnnPOeec+5xzzjnnnPOeec8555zzznnnnPOeec+5xzzjnnnPOeec8555zzznnnnPOeec+5xzzjnnnPOeec8555zzznnnnPOeec+5xzzjnnnPOeec8555zzznnnnPOeec+5xzzjnnnPOeec8555zzznnnnPOeec+5xzzjnnnPOeec8555zzznnnnPOeec+5xzzjnnnPOeec8555zzznnnnPOeec+5xzzjnnnPOeec8555zzznnnnPOeec+5xzzjnnnPOeec8555zzznnnnPOeec+5xzzjnnnPOeec8555zzznnnnPOeec+5xzzjnnnPOeec8555zzznnnnPOeec+5xzzjnnnPOeec8555zzznnnnPOeec+5xzzjnnnPOeec8555zzznnnnPOeec+5xzzjnnnPOeec8555zzznnnnPOeec+5xzzjnnnPOeec8555zzznnnnPOeec+5xzzjnnnPOeec8555zzznnnnPOeec+5xzzjnnnPOeec8555zzznnnnPOeec+5xzzjnnnPOeec8555zzznnnnPOeec+5xzzjnnnPOeec8555zzznnnnPOeec+5xzzjnnnPOeec8555zzznnnnPOeec+5xzzjnnnPOeec8555zzznnnnPOeec+5xzzjnnnPOeec8555zzznnnnPOeec+5xzzjnnnPOeec8555zzznnnnPOeec+5xzzjnnnPOeec8555zzznnnnPOeec+5xzzjnnnPOeec8555zzznnnnPOeec+5xzzjnnnPOeec8555zzznnnnPOeec+5xzzjnnnPOeec8555zzznnnnPOeec+5xzzjnnnPOeec8555zzznnnnPOeec+5xzzjnnnPOeec8555zzznnnnPOeec+5xzzjnnnPOeec8555zzznnnnPOeec+5xzzjnnnPOeec8555zzznnnnPOeec+5xzzjnnnPOeec8555zzznnnnPOeec+5xzzjnnnPOeec8555zzznnnnPOeec+5xzzjnnnPOeec8555zzznnnnPOeec+5xzzjnnnPOeec8555zzznnnnPOeec+5xzzjnnnPOeec8555zzznnnnPOeec+5xzzjnnnPOeec8555zzznnnnPOeec+5xzzjnnnPOeec8555zzznnnnPOeec+5xzzjnnnPOeec8555zzznnnnPOeec+5xzzjnnnPOeec8555zzznnnnPOeec+5xzzjnnnPOeec8555zzznnnnPOeec+5xzzjnnnPOeec8555zzznnnnPOeec+5xzzjnnnPOeec8555zzznnnnPOeec+5xzzjnnnPOeec8555zzznnnnPOeec+5xzzjnnnPOeec8555zzznnnnPOeec+5xzzjnnnPOeec8555zzznnnnPOeec+5xzzjnnnPOeec8555zzznnnnPOeec+5xzzjnnnPOeec8555zzznnnnPOeec+5xzzjnnnPOeec8555zzznnnnPOeec+5xzzjnnnPOeec8555zzznnnnPOeec+5xzzjnnnPOeec8555zzznnnnPOeec+5xzzjnnnPOeec8555zzznnnnPOeec+5xzzjnnnPOeec8555zzznnnnPOeec+5xzzjnnnPOeec8555zzznnnnPOeec+5xzzjnnnPOeec8555zzznnnnPOeec+5xzzjnnnPOeec8555zzznnnnPOeec+5xzzjnnnPOeec8555zzznnnnPOeec+5xzzjnnnPOeec8555zzznnnnPOeec+5xzzjnnnPOeec8555zzznnnnPOeec+5xzzjnnnPOeec8555zzznnnnPOeec+5xzzjnnnPOeec8555zzznnnnPOeec+5xzzjnnnPOeec8555zzznnnnPOeec+5xzzjnnnPOeec8555z7nHHPOeecs85Z5zjnnHOfc4555yn3OOOecp9zjnnKOecp9zjnnKfe4555yn3OOecp9zjnnH6PJ8+6dnDKbZVjSWrdr8bT9xrjlKxdD/AOhq+f4b/lnP/2Q==') center top / cover no-repeat;
      box-shadow: inset 0 0 0 1px rgba(255,255,255,.03), 0 18px 40px rgba(0,0,0,.24);
      animation: floatCard 7s ease-in-out infinite;
    }

    .hero-media::before {
      content: 'AI • FINANCE • STRATEGY';
      position: absolute;
      top: 18px;
      left: 18px;
      font-size: 12px;
      letter-spacing: .22em;
      color: #eafcff;
      padding: 8px 12px;
      border-radius: 999px;
      background: rgba(7,17,31,.58);
      border: 1px solid rgba(255,255,255,.08);
      backdrop-filter: blur(10px);
    }

    .hero-media::after {
      content: '';
      position: absolute;
      inset: auto -40px -40px auto;
      width: 180px;
      height: 180px;
      border-radius: 50%;
      background: radial-gradient(circle, rgba(139,243,255,.30), transparent 70%);
      filter: blur(18px);
    }

    .hero-copy { display: flex; flex-direction: column; gap: 22px; }

    .eyebrow {
      display: inline-flex;
      width: fit-content;
      padding: 10px 16px;
      border-radius: 999px;
      border: 1px solid rgba(139,243,255,.22);
      background: rgba(115,191,255,.08);
      color: var(--accent2);
      font-size: 13px;
      text-transform: uppercase;
      letter-spacing: .15em;
    }

    h1 {
      font-size: clamp(40px, 5vw, 72px);
      line-height: .98;
      letter-spacing: -.05em;
    }

    .gradient {
      background: linear-gradient(90deg, #fff 0%, #9ff7ff 45%, #76c3ff 100%);
      -webkit-background-clip: text;
      -webkit-text-fill-color: transparent;
      background-clip: text;
      color: transparent;
    }

    .lead {
      color: var(--muted);
      line-height: 1.8;
      font-size: 18px;
      max-width: 760px;
    }

    .chips, .tags { display: flex; flex-wrap: wrap; gap: 12px; }

    .chip, .tag {
      padding: 10px 14px;
      border-radius: 999px;
      border: 1px solid rgba(255,255,255,.08);
      background: rgba(255,255,255,.04);
      color: #dbeeff;
      font-size: 14px;
    }

    .cta-row { display: flex; gap: 14px; flex-wrap: wrap; padding-top: 4px; }

    .btn {
      border: 0;
      text-decoration: none;
      display: inline-flex;
      align-items: center;
      justify-content: center;
      min-height: 56px;
      padding: 0 22px;
      border-radius: 18px;
      font-weight: 800;
      cursor: pointer;
      transition: .22s ease;
    }

    .btn-primary {
      color: #05101d;
      background: linear-gradient(135deg, var(--accent), var(--accent2));
      box-shadow: 0 14px 36px rgba(115,191,255,.30);
    }

    .btn-secondary {
      color: var(--text);
      background: rgba(255,255,255,.05);
      border: 1px solid rgba(255,255,255,.10);
    }

    .btn:hover { transform: translateY(-2px); }
    .section { padding: 70px 0 0; }

    .section-title {
      font-size: clamp(28px, 3vw, 42px);
      letter-spacing: -.04em;
      margin-bottom: 10px;
    }

    .section-subtitle {
      color: var(--muted);
      line-height: 1.8;
      max-width: 760px;
      margin-bottom: 24px;
    }

    .grid-3, .grid-2 { display: grid; gap: 20px; }
    .grid-3 { grid-template-columns: repeat(3, 1fr); }
    .grid-2 { grid-template-columns: repeat(2, 1fr); }

    .card {
      background: var(--card);
      border: 1px solid var(--line);
      border-radius: var(--radius);
      padding: 24px;
      box-shadow: var(--shadow);
      backdrop-filter: blur(16px);
      transition: .22s ease;
      position: relative;
      overflow: hidden;
    }

    .card:hover { transform: translateY(-6px); border-color: rgba(139,243,255,.24); }
    .card::before {
      content: '';
      position: absolute;
      inset: 0;
      background: linear-gradient(180deg, rgba(255,255,255,.02), transparent 28%);
      pointer-events: none;
    }

    .card h3 { font-size: 22px; margin-bottom: 14px; letter-spacing: -.03em; }
    .card p, .card li, .card label { color: var(--muted); line-height: 1.75; }

    .list { list-style: none; display: grid; gap: 12px; }
    .list li {
      padding: 14px 16px;
      border-radius: 16px;
      background: rgba(255,255,255,.03);
      border: 1px solid rgba(255,255,255,.05);
    }

    .steps { display: grid; grid-template-columns: repeat(4, 1fr); gap: 16px; }
    .step strong {
      display: inline-grid;
      place-items: center;
      width: 44px;
      height: 44px;
      border-radius: 14px;
      margin-bottom: 14px;
      background: linear-gradient(135deg, rgba(115,191,255,.18), rgba(139,243,255,.18));
      color: #fff;
    }

    .case-kpi { display: grid; grid-template-columns: repeat(3, 1fr); gap: 12px; margin-top: 16px; }
    .mini {
      padding: 14px;
      border-radius: 18px;
      background: rgba(255,255,255,.03);
      border: 1px solid rgba(255,255,255,.06);
    }
    .mini span {
      display: block;
      font-size: 12px;
      color: var(--muted);
      margin-bottom: 8px;
      text-transform: uppercase;
      letter-spacing: .12em;
    }
    .mini strong { font-size: 24px; }

    .calc { display: grid; grid-template-columns: 1.1fr .9fr; gap: 20px; }
    .form-grid { display: grid; grid-template-columns: repeat(2, 1fr); gap: 14px; }
    .field { display: flex; flex-direction: column; gap: 8px; }
    .field.full { grid-column: 1 / -1; }

    input, textarea {
      width: 100%;
      border: 1px solid rgba(255,255,255,.10);
      background: rgba(255,255,255,.04);
      color: var(--text);
      border-radius: 16px;
      padding: 16px;
      outline: none;
      font: inherit;
      transition: .2s ease;
    }

    input:focus, textarea:focus {
      border-color: rgba(139,243,255,.45);
      box-shadow: 0 0 0 4px rgba(115,191,255,.10);
    }

    textarea { min-height: 132px; resize: vertical; }
    .result { display: grid; gap: 14px; }
    .result-box {
      padding: 18px;
      border-radius: 18px;
      background: rgba(255,255,255,.04);
      border: 1px solid rgba(255,255,255,.08);
    }
    .result-box strong { font-size: 28px; display: block; margin-top: 8px; }

    .contact-items { list-style: none; display: grid; gap: 12px; }
    .contact-items a { color: #dff8ff; text-decoration: none; }
    .contact-items a:hover { color: var(--accent2); }

    .footer {
      padding: 50px 0 34px;
      color: rgba(225,236,255,.72);
      text-align: center;
      font-size: 14px;
    }

    .status { margin-top: 14px; font-size: 14px; color: var(--muted); }
    .ok { color: var(--success); }
    .err { color: var(--danger); }

    @media (max-width: 1080px) {
      .hero, .calc { grid-template-columns: 1fr; }
      .hero-media { min-height: 520px; }
      .grid-3, .steps { grid-template-columns: 1fr 1fr; }
    }

    @media (max-width: 760px) {
      .container { width: min(calc(100% - 18px), var(--max)); }
      .nav { padding: 14px 0; }
      .nav-links { display: none; }
      .hero, .card { padding: 18px; }
      .hero-media { min-height: 420px; }
      .grid-3, .grid-2, .steps, .form-grid, .case-kpi { grid-template-columns: 1fr; }
      .cta-row .btn { width: 100%; }
      h1 { font-size: 38px; }
      .lead { font-size: 16px; }
    }
  </style>
</head>
<body>
  <div class="container">
    <header class="nav">
      <div class="brand">
        <div class="brand-badge">AI</div>
        <div>Павел • Финансовый аналитик</div>
      </div>
      <nav class="nav-links">
        <a href="#services">Услуги</a>
        <a href="#cases">Кейсы</a>
        <a href="#calculator">Калькулятор</a>
        <a href="#contact">Контакты</a>
      </nav>
    </header>

    <section class="hero">
      <div class="hero-media" aria-label="Портрет Павла"></div>
      <div class="hero-copy">
        <div class="eyebrow">Финансовый аналитик + AI</div>
        <h1>Финансовые решения, <span class="gradient">которые помогают принимать решения быстрее</span></h1>
        <p class="lead">Помогаю бизнесу, предпринимателям и инвесторам принимать решения на основе цифр: финансовые модели, инвестиционный анализ, сценарии, чувствительность, отчёты и AI-инструменты для ускорения аналитики.</p>
        <div class="chips">
          <span class="chip">NPV / IRR / DPP</span>
          <span class="chip">DCF и cash flow</span>
          <span class="chip">Инвесткомитет</span>
          <span class="chip">AI-аналитика</span>
          <span class="chip">Dashboard & KPI</span>
          <span class="chip">Excel / Power BI / ChatGPT</span>
        </div>
        <div class="cta-row">
          <a class="btn btn-primary" href="#contact">Обратная связь</a>
          <a class="btn btn-secondary" href="mailto:pavelhra@yandex.ru">Почта</a>
          <a class="btn btn-secondary" href="https://t.me/Pavel5X" target="_blank" rel="noopener noreferrer">Telegram</a>
        </div>
      </div>
    </section>

    <section class="section" id="services">
      <h2 class="section-title">Что вы получаете</h2>
      <p class="section-subtitle">Не просто расчёты, а понятную финансовую логику, оформленную в виде, удобном для собственника, руководителя или инвестора.</p>
      <div class="grid-3">
        <article class="card"><h3>Инвестиционный анализ</h3><ul class="list"><li>NPV, IRR, дисконтированный срок окупаемости</li><li>Сценарии base / best / worst</li><li>Анализ чувствительности к цене, объёму и затратам</li></ul></article>
        <article class="card"><h3>Финансовые модели</h3><ul class="list"><li>Модели по годам и месяцам</li><li>Прогноз денежных потоков и прибыли</li><li>Дашборды для контроля KPI</li></ul></article>
        <article class="card"><h3>AI для аналитики</h3><ul class="list"><li>Ускорение подготовки отчётов и презентаций</li><li>Структурирование больших массивов данных</li><li>Быстрые выводы и управленческие рекомендации</li></ul></article>
      </div>
    </section>

    <section class="section">
      <h2 class="section-title">Как я работаю</h2>
      <p class="section-subtitle">Понятный и управляемый процесс без лишней сложности.</p>
      <div class="steps">
        <article class="card step"><strong>01</strong><h3>Собираю данные</h3><p>Фиксирую исходные параметры, ограничения и бизнес-цель.</p></article>
        <article class="card step"><strong>02</strong><h3>Проверяю логику</h3><p>Убираю разрывы между исходными данными, гипотезами и расчётами.</p></article>
        <article class="card step"><strong>03</strong><h3>Строю модель</h3><p>Формирую расчёты, сценарии и чувствительность к ключевым драйверам.</p></article>
        <article class="card step"><strong>04</strong><h3>Упаковываю вывод</h3><p>Готовлю понятный результат: решение, риски и действия.</p></article>
      </div>
    </section>

    <section class="section" id="cases">
      <h2 class="section-title">Кейсы</h2>
      <p class="section-subtitle">Блок добавлен как продающий элемент. Числа в кейсах можно заменить на ваши реальные проекты.</p>
      <div class="grid-3">
        <article class="card"><h3>Оценка инвестиционного проекта</h3><p>Построение модели денежных потоков, расчёт NPV / IRR, сценарный анализ и вывод для инвесткомитета.</p><div class="case-kpi"><div class="mini"><span>Результат</span><strong>NPV+</strong></div><div class="mini"><span>Фокус</span><strong>IRR</strong></div><div class="mini"><span>Вывод</span><strong>Go / No-Go</strong></div></div></article>
        <article class="card"><h3>Финмодель для бизнеса</h3><p>Прогноз выручки, затрат, прибыли и денежных потоков с управлением ключевыми драйверами через сценарии.</p><div class="case-kpi"><div class="mini"><span>Горизонт</span><strong>3–5 лет</strong></div><div class="mini"><span>Сценарии</span><strong>3</strong></div><div class="mini"><span>Формат</span><strong>Dashboard</strong></div></div></article>
        <article class="card"><h3>AI-ускорение аналитики</h3><p>Автоматизация подготовки аналитических материалов, быстрые выводы по данным и упаковка результата для клиента.</p><div class="case-kpi"><div class="mini"><span>Скорость</span><strong>Быстрее</strong></div><div class="mini"><span>Формат</span><strong>Отчёт</strong></div><div class="mini"><span>Эффект</span><strong>Фокус</strong></div></div></article>
      </div>
    </section>

    <section class="section" id="calculator">
      <h2 class="section-title">Интерактивный калькулятор NPV / IRR</h2>
      <p class="section-subtitle">Введите ставку дисконтирования и денежные потоки через запятую. Первый поток обычно отрицательный — это инвестиции.</p>
      <div class="calc">
        <article class="card">
          <div class="form-grid">
            <div class="field"><label for="rate">Ставка дисконтирования, %</label><input id="rate" type="number" step="0.01" value="15" /></div>
            <div class="field"><label for="guess">Стартовая оценка IRR, %</label><input id="guess" type="number" step="0.01" value="20" /></div>
            <div class="field full"><label for="cashflows">Денежные потоки</label><input id="cashflows" type="text" value="-1000000, 350000, 420000, 480000, 520000" /></div>
            <div class="field full"><button class="btn btn-primary" type="button" id="calcBtn">Рассчитать</button></div>
          </div>
        </article>
        <article class="card result">
          <div class="result-box"><div>NPV</div><strong id="npvValue">—</strong></div>
          <div class="result-box"><div>IRR</div><strong id="irrValue">—</strong></div>
          <div class="result-box"><div>Вывод</div><strong id="verdictValue">Введите данные</strong></div>
        </article>
      </div>
    </section>

    <section class="section" id="contact">
      <h2 class="section-title">Контакты и форма обратной связи</h2>
      <p class="section-subtitle">Форма подключена к FormSubmit. После размещения сайта подтвердите email один раз, и заявки будут приходить на почту.</p>
      <div class="grid-2">
        <article class="card">
          <h3>Связаться со мной</h3>
          <ul class="contact-items">
            <li><strong>Email:</strong> <a href="mailto:pavelhra@yandex.ru">pavelhra@yandex.ru</a></li>
            <li><strong>Telegram:</strong> <a href="https://t.me/Pavel5X" target="_blank" rel="noopener noreferrer">@Pavel5X</a></li>
            <li><strong>Формат работы:</strong> консультации, анализ проектов, финмодели, отчёты, AI-решения</li>
          </ul>
          <div class="tags" style="margin-top:18px;"><span class="tag">Для бизнеса</span><span class="tag">Для инвестора</span><span class="tag">Для собственника</span></div>
        </article>
        <article class="card">
          <h3>Отправить запрос</h3>
          <form action="https://formsubmit.co/pavelhra@yandex.ru" method="POST" id="leadForm">
            <input type="hidden" name="_subject" value="Новая заявка с сайта финансового аналитика" />
            <input type="hidden" name="_captcha" value="false" />
            <input type="hidden" name="_template" value="table" />
            <div class="form-grid">
              <div class="field"><label for="name">Имя</label><input id="name" name="name" type="text" placeholder="Ваше имя" required /></div>
              <div class="field"><label for="email">Email</label><input id="email" name="email" type="email" placeholder="name@email.com" required /></div>
              <div class="field full"><label for="message">Задача</label><textarea id="message" name="message" placeholder="Опишите проект, задачу или запрос" required></textarea></div>
              <div class="field full"><button class="btn btn-primary" type="submit">Отправить заявку</button></div>
            </div>
          </form>
          <div id="formStatus" class="status">Форма готова к отправке.</div>
        </article>
      </div>
    </section>

    <section class="section">
      <h2 class="section-title">Готово для размещения</h2>
      <p class="section-subtitle">Это статический сайт: один HTML-файл без зависимостей. Его можно разместить на GitHub Pages или обычном хостинге.</p>
      <div class="grid-3">
        <article class="card"><h3>GitHub Pages</h3><p>Подходит для бесплатной публикации статического сайта и быстрого обновления через Git.</p></article>
        <article class="card"><h3>Обычный хостинг</h3><p>Достаточно загрузить HTML-файл на сервер. Отдельная сборка не требуется.</p></article>
        <article class="card"><h3>Домен и HTTPS</h3><p>Можно подключить свой домен и включить HTTPS после публикации сайта.</p></article>
      </div>
    </section>

    <footer class="footer">© 2026 Павел • Финансовый аналитик + AI</footer>
  </div>

  <script>
    const calcBtn = document.getElementById('calcBtn');
    const rateInput = document.getElementById('rate');
    const guessInput = document.getElementById('guess');
    const flowsInput = document.getElementById('cashflows');
    const npvValue = document.getElementById('npvValue');
    const irrValue = document.getElementById('irrValue');
    const verdictValue = document.getElementById('verdictValue');
    const leadForm = document.getElementById('leadForm');
    const formStatus = document.getElementById('formStatus');

    function parseFlows(text) {
      return text.split(',').map(v => Number(String(v).trim().replace(/\s+/g, ''))).filter(v => !Number.isNaN(v));
    }

    function calcNPV(rate, cashflows) {
      const r = rate / 100;
      return cashflows.reduce((sum, cf, i) => sum + cf / Math.pow(1 + r, i), 0);
    }

    function calcIRR(cashflows, guess = 20) {
      let x = guess / 100;
      for (let i = 0; i < 200; i++) {
        let f = 0;
        let df = 0;
        for (let t = 0; t < cashflows.length; t++) {
          const denom = Math.pow(1 + x, t);
          f += cashflows[t] / denom;
          if (t > 0) {
            df += (-t * cashflows[t]) / Math.pow(1 + x, t + 1);
          }
        }
        if (!isFinite(f) || !isFinite(df) || Math.abs(df) < 1e-10) return null;
        const nx = x - f / df;
        if (!isFinite(nx) || nx <= -0.9999) return null;
        if (Math.abs(nx - x) < 1e-7) return nx * 100;
        x = nx;
      }
      return null;
    }

    function formatMoney(num) {
      return new Intl.NumberFormat('ru-RU', { maximumFractionDigits: 0 }).format(num) + ' ₽';
    }

    function updateCalc() {
      const rate = Number(rateInput.value);
      const guess = Number(guessInput.value);
      const cashflows = parseFlows(flowsInput.value);
      if (cashflows.length < 2 || Number.isNaN(rate)) {
        npvValue.textContent = 'Ошибка';
        irrValue.textContent = 'Ошибка';
        verdictValue.textContent = 'Проверьте ввод';
        return;
      }
      const npv = calcNPV(rate, cashflows);
      const irr = calcIRR(cashflows, guess);
      npvValue.textContent = formatMoney(npv);
      irrValue.textContent = irr === null ? 'нет решения' : irr.toFixed(2) + ' %';
      verdictValue.textContent = npv > 0 ? 'Проект создаёт стоимость' : 'Требует пересмотра';
    }

    calcBtn.addEventListener('click', updateCalc);
    updateCalc();

    leadForm.addEventListener('submit', function () {
      formStatus.textContent = 'Отправка...';
      formStatus.className = 'status';
      setTimeout(() => {
        formStatus.textContent = 'Если это первая отправка, сервис попросит подтвердить email.';
        formStatus.className = 'status ok';
      }, 500);
    });
  </script>
</body>
</html>
