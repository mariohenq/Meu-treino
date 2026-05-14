<!DOCTYPE html>
<html lang="pt-BR">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0, viewport-fit=cover">
<meta name="apple-mobile-web-app-capable" content="yes">
<meta name="apple-mobile-web-app-status-bar-style" content="black-translucent">
<meta name="apple-mobile-web-app-title" content="💪 Treino">
<meta name="theme-color" content="#0a0a0a">
<title>Ficha de Treino</title>

<!-- Manifest inline via blob (sem arquivo externo) -->
<script>
(function(){
  const manifest = {
    name: "💪 Ficha de Treino",
    short_name: "Treino",
    start_url: "./",
    display: "standalone",
    background_color: "#0a0a0a",
    theme_color: "#0a0a0a",
    icons: [{
      src: "data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAMAAAADACAIAAADdvvtQAAADhklEQVR42u3d0W0bMRAE0P2+ktJ/MekiqSBBAFu5ndk3UAHm8ImEeZQ0j8gXMioQgAQgAUgAEgFIABKABCARgAQgAUgAEgFIABKAgvLz1w8lAPRHHN/1AoiYHzwB9Caam5iGG5IAWu2mW9JwQ9JpQKF0ahgNOhidA1RGJ5rRoIPRCUBH6MQxGnQwagZ0XM9+Q4MORoWAcEkxNOhg1AMIjjhDQw9DDYCACDU09DAUDIiAdEZDD0ORgEx5h6Ghh6EwQKa5ydDQwxBAn50MgLYAqqz7uKG5qccYwwBde1/eGe9caPPyYWk8II8bu0uoBfTsC0AZlT27U9bJNDX15KSmnB5AT1oAokdLnwGEzp26sgE9LQGInqO9pQJ6GgMQPecKzAP0tOcuIHoONpkE6LmUc4DouWkoA9BzNVcA0XPWEEAAvQ2InsuGVgNCZ3/JewFBE9HzWH4sQoWAcElpGyCA3gNED0MAAdQFCJGs2sfyA9BXmh/LD0MAAQQQQKcA0cMQQAABBBBA9OwxBBBACYDsX3YxgAAqAoRC7i4GEEAAAQSQAAQQQAABBBBAAAlAAAEEEEDfD4gehqxA9NjCBCCAAAIIIIAAAggggAQggAACCCCAAPKpDAmZCIAA+u+A7GL2L4AA8u0c9AAEEEAAAcQQPb5kEyCAAAKIoUw9LwCyCFl+Hr/WQw9AAMUCYui4HoAAKgXEUErVfjfe8vN0AmIoouTVgBja3/DUj5Cej3YLEEALADF0U08MoJuGIiqdawOm53vLTAJ0x1BQk3N25PQcBdRtKK7AUQE9FwH1GQrtbXRBz11AHYai65qCUnIZFbQ02qEHoDxDNeVMWU37GZV1MpV97WRUWUUtoFWMikuY+vreZVQ/9jnS43+WdGe8c63TjzZ7YYyvAdrW73cVXTmopYDW1v33mUj8mwHyAoihA/9yvgCIoaYDi3cAMVRz3PUaIIY6DkvfBMRQwVH7y4AwSn/YtwIQQ7mPircAYij0osEiQAwl3nbaBYihuLty6wBhlHXNcikghlLueu8FhFHExwS2A2Jo+ewEADrLKGJeYgCdYhQ0I2GA6hnFzUUkoEpGobMQDKiGUXT/8YCiGRU0XwIoS1JT4W2ANkuq7LkW0B5J3fX2A3oF051KbwH6nKezHZ4G9I/IlACQACQACUAiAAlAApAAJACpQAASgAQgAUgEIAFIUvIbCTV6QOKXRSQAAAAASUVORK5CYII=",
      sizes: "192x192",
      type: "image/png",
      purpose: "any maskable"
    }]
  };
  const blob = new Blob([JSON.stringify(manifest)], {type: 'application/manifest+json'});
  const url = URL.createObjectURL(blob);
  const link = document.createElement('link');
  link.rel = 'manifest';
  link.href = url;
  document.currentScript.after(link);
})();
</script>

<!-- Apple touch icon real (PNG 192x192) -->
<link rel="apple-touch-icon" href="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAMAAAADACAIAAADdvvtQAAADhklEQVR42u3d0W0bMRAE0P2+ktJ/MekiqSBBAFu5ndk3UAHm8ImEeZQ0j8gXMioQgAQgAUgAEgFIABKABCARgAQgAUgAEgFIABKAgvLz1w8lAPRHHN/1AoiYHzwB9Caam5iGG5IAWu2mW9JwQ9JpQKF0ahgNOhidA1RGJ5rRoIPRCUBH6MQxGnQwagZ0XM9+Q4MORoWAcEkxNOhg1AMIjjhDQw9DDYCACDU09DAUDIiAdEZDD0ORgEx5h6Ghh6EwQKa5ydDQwxBAn50MgLYAqqz7uKG5qccYwwBde1/eGe9caPPyYWk8II8bu0uoBfTsC0AZlT27U9bJNDX15KSmnB5AT1oAokdLnwGEzp26sgE9LQGInqO9pQJ6GgMQPecKzAP0tOcuIHoONpkE6LmUc4DouWkoA9BzNVcA0XPWEEAAvQ2InsuGVgNCZ3/JewFBE9HzWH4sQoWAcElpGyCA3gNED0MAAdQFCJGs2sfyA9BXmh/LD0MAAQQQQKcA0cMQQAABBBBA9OwxBBBACYDsX3YxgAAqAoRC7i4GEEAAAQSQAAQQQAABBBBAAAlAAAEEEEDfD4gehqxA9NjCBCCAAAIIIIAAAggggAQggAACCCCAAPKpDAmZCIAA+u+A7GL2L4AA8u0c9AAEEEAAAcQQPb5kEyCAAAKIoUw9LwCyCFl+Hr/WQw9AAMUCYui4HoAAKgXEUErVfjfe8vN0AmIoouTVgBja3/DUj5Cej3YLEEALADF0U08MoJuGIiqdawOm53vLTAJ0x1BQk3N25PQcBdRtKK7AUQE9FwH1GQrtbXRBz11AHYai65qCUnIZFbQ02qEHoDxDNeVMWU37GZV1MpV97WRUWUUtoFWMikuY+vreZVQ/9jnS43+WdGe8c63TjzZ7YYyvAdrW73cVXTmopYDW1v33mUj8mwHyAoihA/9yvgCIoaYDi3cAMVRz3PUaIIY6DkvfBMRQwVH7y4AwSn/YtwIQQ7mPircAYij0osEiQAwl3nbaBYihuLty6wBhlHXNcikghlLueu8FhFHExwS2A2Jo+ewEADrLKGJeYgCdYhQ0I2GA6hnFzUUkoEpGobMQDKiGUXT/8YCiGRU0XwIoS1JT4W2ANkuq7LkW0B5J3fX2A3oF051KbwH6nKezHZ4G9I/IlACQACQACUAiAAlAApAAJACpQAASgAQgAUgEIAFIUvIbCTV6QOKXRSQAAAAASUVORK5CYII=">

<link href="https://fonts.googleapis.com/css2?family=Bebas+Neue&family=DM+Sans:wght@300;400;500;600&display=swap" rel="stylesheet">

<style>
  :root {
    --black: #0a0a0a;
    --dark: #111;
    --card: #181818;
    --accent: #e8ff3a;
    --accent2: #ff6b35;
    --green: #4ade80;
    --text: #f0f0f0;
    --muted: #777;
    --border: #252525;
    --safe-top: env(safe-area-inset-top, 0px);
    --safe-bot: env(safe-area-inset-bottom, 0px);
  }

  * { margin: 0; padding: 0; box-sizing: border-box; -webkit-tap-highlight-color: transparent; }

  html, body {
    background: var(--black);
    color: var(--text);
    font-family: 'DM Sans', sans-serif;
    min-height: 100vh;
    min-height: 100dvh;
    overscroll-behavior: none;
  }

  /* ── HEADER ── */
  .header {
    background: var(--dark);
    border-bottom: 1px solid var(--border);
    padding: calc(16px + var(--safe-top)) 16px 14px;
    position: sticky;
    top: 0;
    z-index: 100;
  }
  .header-top {
    display: flex;
    align-items: center;
    justify-content: space-between;
    gap: 10px;
    margin-bottom: 12px;
  }
  .header h1 {
    font-family: 'Bebas Neue', sans-serif;
    font-size: 1.9rem;
    letter-spacing: 0.05em;
    color: var(--accent);
    text-shadow: 0 0 24px rgba(232,255,58,0.3);
    line-height: 1;
  }
  .header-sub {
    font-size: 0.7rem;
    color: var(--muted);
    letter-spacing: 0.07em;
    text-transform: uppercase;
  }

  /* ── TABS ── */
  .tabs {
    display: flex;
    gap: 6px;
  }
  .tab {
    flex: 1;
    background: var(--border);
    border: 1px solid #2e2e2e;
    border-radius: 8px;
    padding: 8px 4px;
    font-size: 0.65rem;
    font-weight: 700;
    letter-spacing: 0.08em;
    text-transform: uppercase;
    color: var(--muted);
    cursor: pointer;
    transition: all 0.18s;
    text-align: center;
    font-family: inherit;
    line-height: 1.3;
  }
  .tab.active {
    background: var(--accent);
    color: #000;
    border-color: var(--accent);
    box-shadow: 0 0 12px rgba(232,255,58,0.2);
  }

  /* ── PROGRESS ── */
  .progress-wrap {
    padding: 10px 16px 0;
  }
  .progress-info {
    display: flex;
    justify-content: space-between;
    font-size: 0.68rem;
    color: var(--muted);
    margin-bottom: 5px;
    letter-spacing: 0.04em;
  }
  .progress-info #progressCount { color: var(--green); font-weight: 700; }
  .progress-track { height: 3px; background: var(--border); border-radius: 99px; overflow: hidden; }
  .progress-fill {
    height: 100%;
    background: var(--green);
    border-radius: 99px;
    transition: width 0.35s ease;
    box-shadow: 0 0 6px rgba(74,222,128,0.5);
  }

  /* ── CONTENT ── */
  .content {
    padding: 16px 12px calc(16px + var(--safe-bot));
  }

  /* ── FICHA ── */
  .ficha { display: none; }
  .ficha.visible { display: block; }

  .ficha-header {
    display: flex;
    align-items: center;
    gap: 12px;
    margin-bottom: 16px;
    padding-bottom: 14px;
    border-bottom: 1px solid var(--border);
  }
  .ficha-letter {
    font-family: 'Bebas Neue', sans-serif;
    font-size: 3.5rem;
    line-height: 1;
    color: var(--accent);
    opacity: 0.1;
    min-width: 48px;
  }
  .ficha-info .subtitle {
    font-size: 0.65rem;
    color: var(--accent);
    letter-spacing: 0.14em;
    text-transform: uppercase;
    font-weight: 700;
  }
  .ficha-info h2 {
    font-family: 'Bebas Neue', sans-serif;
    font-size: 1.4rem;
    letter-spacing: 0.04em;
    color: var(--text);
    line-height: 1.1;
  }
  .ficha-info .groups { font-size: 0.68rem; color: var(--muted); margin-top: 2px; }

  /* ── EXERCISE LIST ── */
  .exercise-list { display: flex; flex-direction: column; gap: 10px; }

  .ex-wrapper {
    display: flex;
    align-items: stretch;
    gap: 8px;
    animation: fadeUp 0.3s ease both;
  }
  @keyframes fadeUp {
    from { opacity: 0; transform: translateY(8px); }
    to   { opacity: 1; transform: translateY(0); }
  }

  .ex-check-col {
    display: flex;
    align-items: center;
    padding-top: 2px;
    flex-shrink: 0;
  }
  .ex-checkbox {
    appearance: none;
    -webkit-appearance: none;
    width: 28px;
    height: 28px;
    border: 2px solid #333;
    border-radius: 8px;
    background: var(--card);
    cursor: pointer;
    position: relative;
    flex-shrink: 0;
    transition: all 0.18s;
  }
  .ex-checkbox:checked {
    background: var(--green);
    border-color: var(--green);
    box-shadow: 0 0 10px rgba(74,222,128,0.35);
  }
  .ex-checkbox:checked::after {
    content: '✓';
    position: absolute;
    top: 50%; left: 50%;
    transform: translate(-50%, -52%);
    color: #000;
    font-size: 15px;
    font-weight: 800;
    line-height: 1;
  }

  /* ── CARD ── */
  .exercise-card {
    background: var(--card);
    border: 1px solid var(--border);
    border-radius: 12px;
    overflow: hidden;
    display: grid;
    grid-template-columns: 40px 1fr;
    align-items: stretch;
    flex: 1;
    transition: border-color 0.18s, opacity 0.3s;
    height: 80px;
    max-height: 80px;
  }
  .exercise-card:hover { border-color: #444; }

  .ex-wrapper.done .exercise-card {
    opacity: 0.38;
    border-color: rgba(74,222,128,0.3);
    border-style: dashed;
  }
  .ex-wrapper.done .ex-name { text-decoration: line-through; color: var(--muted); }
  .ex-wrapper.done .ex-num { color: var(--green); background: rgba(74,222,128,0.07); }

  .ex-num {
    background: var(--border);
    display: flex;
    align-items: center;
    justify-content: center;
    font-family: 'Bebas Neue', sans-serif;
    font-size: 1.2rem;
    color: var(--accent);
    padding: 12px 4px;
    transition: all 0.2s;
  }

  .ex-body {
    padding: 10px 10px;
    display: flex;
    flex-direction: column;
    justify-content: center;
    gap: 4px;
    overflow: hidden;
  }

  .ex-name {
    font-weight: 600;
    font-size: 0.88rem;
    color: var(--accent);
    line-height: 1.25;
    text-decoration: none;
    transition: opacity 0.15s;
    white-space: nowrap;
    overflow: hidden;
    text-overflow: ellipsis;
  }
  .ex-name:active { opacity: 0.7; }


  .ex-meta { display: flex; gap: 6px; flex-wrap: wrap; }
  .ex-tag {
    background: rgba(232,255,58,0.07);
    border: 1px solid rgba(232,255,58,0.13);
    color: var(--accent);
    font-size: 0.6rem;
    font-weight: 700;
    letter-spacing: 0.08em;
    text-transform: uppercase;
    padding: 2px 7px;
    border-radius: 4px;
  }
  .ex-tag.rep { background: rgba(255,107,53,0.07); border-color: rgba(255,107,53,0.17); color: var(--accent2); }
  .ex-muscles { font-size: 0.62rem; color: var(--muted); line-height: 1.3; }


  /* ── FOOTER ── */
  .ficha-footer {
    margin-top: 16px;
    padding: 12px 14px;
    background: rgba(232,255,58,0.03);
    border: 1px solid rgba(232,255,58,0.07);
    border-radius: 10px;
    font-size: 0.7rem;
    color: var(--muted);
    display: flex;
    gap: 14px;
    align-items: center;
    flex-wrap: wrap;
  }
  .ficha-footer span strong { color: var(--accent); }
  .reset-btn {
    margin-left: auto;
    background: none;
    border: 1px solid #2e2e2e;
    color: var(--muted);
    font-size: 0.65rem;
    font-weight: 600;
    letter-spacing: 0.07em;
    text-transform: uppercase;
    padding: 6px 12px;
    border-radius: 6px;
    cursor: pointer;
    font-family: inherit;
    transition: all 0.18s;
    -webkit-tap-highlight-color: transparent;
  }
  .reset-btn:active { border-color: var(--accent2); color: var(--accent2); }

  /* ── IMPORTAR CSV ── */
  .csv-section {
    margin: 0 12px calc(16px + var(--safe-bot));
    background: var(--card);
    border: 1px solid var(--border);
    border-radius: 12px;
    padding: 14px 16px;
  }
  .csv-title-row {
    display: flex;
    align-items: center;
    gap: 8px;
    margin-bottom: 10px;
  }
  .csv-title {
    font-family: 'Bebas Neue', sans-serif;
    font-size: 1rem;
    letter-spacing: 0.06em;
    color: var(--accent);
    flex: 1;
  }
  .csv-help-btn {
    background: none;
    border: 1px solid #333;
    color: var(--muted);
    border-radius: 50%;
    width: 24px;
    height: 24px;
    font-size: 0.75rem;
    font-weight: 700;
    cursor: pointer;
    display: flex;
    align-items: center;
    justify-content: center;
    font-family: inherit;
    flex-shrink: 0;
    transition: all 0.2s;
    position: relative;
  }
  .csv-help-btn:active { border-color: var(--accent); color: var(--accent); }

  /* balão de ajuda */
  .csv-tooltip {
    display: none;
    position: absolute;
    right: 0;
    bottom: 30px;
    width: 280px;
    background: #1e1e1e;
    border: 1px solid rgba(232,255,58,0.25);
    border-radius: 10px;
    padding: 14px;
    font-size: 0.7rem;
    color: var(--text);
    line-height: 1.6;
    z-index: 200;
    box-shadow: 0 8px 32px rgba(0,0,0,0.6);
  }
  .csv-tooltip.open { display: block; }
  .csv-tooltip strong { color: var(--accent); }
  .csv-tooltip code {
    display: block;
    background: #111;
    border: 1px solid #333;
    border-radius: 6px;
    padding: 8px 10px;
    margin: 8px 0;
    font-family: monospace;
    font-size: 0.65rem;
    color: #aaa;
    white-space: pre;
    overflow-x: auto;
  }
  .csv-tooltip ul { padding-left: 14px; margin-top: 4px; }
  .csv-tooltip li { margin-bottom: 3px; }
  .csv-tooltip .close-tip {
    display: block;
    margin-top: 10px;
    text-align: right;
    color: var(--muted);
    font-size: 0.65rem;
    cursor: pointer;
    background: none;
    border: none;
    font-family: inherit;
  }

  .csv-row {
    display: flex;
    gap: 8px;
    align-items: center;
  }
  .csv-label {
    display: flex;
    align-items: center;
    gap: 8px;
    flex: 1;
    background: #111;
    border: 1px dashed #333;
    border-radius: 8px;
    padding: 10px 12px;
    cursor: pointer;
    transition: border-color 0.2s;
    font-size: 0.75rem;
    color: var(--muted);
  }
  .csv-label:active { border-color: var(--accent); }
  .csv-label input { display: none; }
  .csv-label span { color: var(--text); font-weight: 600; }
  .csv-import-btn {
    background: var(--accent);
    color: #000;
    border: none;
    border-radius: 8px;
    padding: 10px 16px;
    font-size: 0.75rem;
    font-weight: 700;
    letter-spacing: 0.06em;
    text-transform: uppercase;
    cursor: pointer;
    font-family: inherit;
    transition: opacity 0.15s;
    white-space: nowrap;
  }
  .csv-import-btn:active { opacity: 0.8; }
  .csv-status {
    margin-top: 8px;
    font-size: 0.68rem;
    color: var(--muted);
    min-height: 16px;
  }
  .csv-status.ok { color: var(--green); }
  .csv-status.err { color: var(--accent2); }
</style>
</head>
<body>

<header class="header">
  <div class="header-top">
    <div>
      <h1>💪 FICHA DE TREINO</h1>
      <div class="header-sub">Programa de Hipertrofia — 3 Fichas</div>
    </div>
  </div>
  <div class="tabs">
    <button class="tab active" onclick="showFicha('A',this)">Ficha A<br>Superior 1</button>
    <button class="tab" onclick="showFicha('B',this)">Ficha B<br>Inferior</button>
    <button class="tab" onclick="showFicha('C',this)">Ficha C<br>Superior 2</button>
  </div>
</header>

<div class="progress-wrap">
  <div class="progress-info">
    <span id="progressLabel">Progresso — Ficha A</span>
    <span id="progressCount">0 / 0</span>
  </div>
  <div class="progress-track">
    <div class="progress-fill" id="progressFill" style="width:0%"></div>
  </div>
</div>

<div class="content">


<!-- ===== FICHA A ===== -->
<section class="ficha visible" id="fichaA">
  <div class="ficha-header">
    <div class="ficha-letter">A</div>
    <div class="ficha-info">
      <div class="subtitle">Ficha A · Superior 1</div>
      <h2>PEITO + COSTAS + BRAÇOS</h2>
      <div class="groups">11 exercícios · toque no nome para ver no Google Imagens</div>
    </div>
  </div>
  <div class="exercise-list">

    <div class="ex-wrapper" data-f="A" style="animation-delay:.03s">
      <div class="ex-check-col"><input type="checkbox" class="ex-checkbox" onchange="toggleDone(this)"></div>
      <div class="exercise-card">
        <div class="ex-num">1</div>
        <div class="ex-body">
          <a class="ex-name" href="https://www.google.com/search?q=supino+reto+barra+muscula%C3%A7%C3%A3o&tbm=isch" target="_blank" rel="noopener">Supino Reto Barra</a>
          <div class="ex-meta"><span class="ex-tag">3 Séries</span><span class="ex-tag rep">8 Reps</span></div>
          <div class="ex-muscles">Peitoral maior · Deltóide ant. · Tríceps</div>
        </div>
      </div>
    </div>

    <div class="ex-wrapper" data-f="A" style="animation-delay:.06s">
      <div class="ex-check-col"><input type="checkbox" class="ex-checkbox" onchange="toggleDone(this)"></div>
      <div class="exercise-card">
        <div class="ex-num">2</div>
        <div class="ex-body">
          <a class="ex-name" href="https://www.google.com/search?q=supino+inclinado+halteres+muscula%C3%A7%C3%A3o&tbm=isch" target="_blank" rel="noopener">Supino Inclinado Halteres</a>
          <div class="ex-meta"><span class="ex-tag">3 Séries</span><span class="ex-tag rep">8 Reps</span></div>
          <div class="ex-muscles">Peitoral superior · Deltóide ant. · Tríceps</div>
        </div>
      </div>
    </div>

    <div class="ex-wrapper" data-f="A" style="animation-delay:.09s">
      <div class="ex-check-col"><input type="checkbox" class="ex-checkbox" onchange="toggleDone(this)"></div>
      <div class="exercise-card">
        <div class="ex-num">3</div>
        <div class="ex-body">
          <a class="ex-name" href="https://www.google.com/search?q=crucifixo+reto+halteres+muscula%C3%A7%C3%A3o&tbm=isch" target="_blank" rel="noopener">Crucifixo Reto com Halteres</a>
          <div class="ex-meta"><span class="ex-tag">3 Séries</span><span class="ex-tag rep">10 Reps</span></div>
          <div class="ex-muscles">Peitoral maior · Deltóide anterior</div>
        </div>
      </div>
    </div>

    <div class="ex-wrapper" data-f="A" style="animation-delay:.12s">
      <div class="ex-check-col"><input type="checkbox" class="ex-checkbox" onchange="toggleDone(this)"></div>
      <div class="exercise-card">
        <div class="ex-num">4</div>
        <div class="ex-body">
          <a class="ex-name" href="https://www.google.com/search?q=puxada+aberta+neutra+costas+muscula%C3%A7%C3%A3o&tbm=isch" target="_blank" rel="noopener">Puxada Aberta Neutra</a>
          <div class="ex-meta"><span class="ex-tag">3 Séries</span><span class="ex-tag rep">8 Reps</span></div>
          <div class="ex-muscles">Latíssimo · Rombóides · Bíceps</div>
        </div>
      </div>
    </div>

    <div class="ex-wrapper" data-f="A" style="animation-delay:.15s">
      <div class="ex-check-col"><input type="checkbox" class="ex-checkbox" onchange="toggleDone(this)"></div>
      <div class="exercise-card">
        <div class="ex-num">5</div>
        <div class="ex-body">
          <a class="ex-name" href="https://www.google.com/search?q=remada+curvada+pronada+halteres+muscula%C3%A7%C3%A3o&tbm=isch" target="_blank" rel="noopener">Remada Curvada Pronada Halteres</a>
          <div class="ex-meta"><span class="ex-tag">3 Séries</span><span class="ex-tag rep">8 Reps</span></div>
          <div class="ex-muscles">Latíssimo · Trapézio · Rombóides · Bíceps</div>
        </div>
      </div>
    </div>

    <div class="ex-wrapper" data-f="A" style="animation-delay:.18s">
      <div class="ex-check-col"><input type="checkbox" class="ex-checkbox" onchange="toggleDone(this)"></div>
      <div class="exercise-card">
        <div class="ex-num">6</div>
        <div class="ex-body">
          <a class="ex-name" href="https://www.google.com/search?q=remada+baixa+tri%C3%A2ngulo+polia+muscula%C3%A7%C3%A3o&tbm=isch" target="_blank" rel="noopener">Remada Baixa Triângulo</a>
          <div class="ex-meta"><span class="ex-tag">3 Séries</span><span class="ex-tag rep">10 Reps</span></div>
          <div class="ex-muscles">Latíssimo · Trapézio · Rombóides</div>
        </div>
      </div>
    </div>

    <div class="ex-wrapper" data-f="A" style="animation-delay:.21s">
      <div class="ex-check-col"><input type="checkbox" class="ex-checkbox" onchange="toggleDone(this)"></div>
      <div class="exercise-card">
        <div class="ex-num">7</div>
        <div class="ex-body">
          <a class="ex-name" href="https://www.google.com/search?q=tr%C3%ADceps+franc%C3%AAs+halter+muscula%C3%A7%C3%A3o&tbm=isch" target="_blank" rel="noopener">Tríceps Francês com Halter</a>
          <div class="ex-meta"><span class="ex-tag">3 Séries</span><span class="ex-tag rep">10 Reps</span></div>
          <div class="ex-muscles">Tríceps braquial (cabeça longa)</div>
        </div>
      </div>
    </div>

    <div class="ex-wrapper" data-f="A" style="animation-delay:.24s">
      <div class="ex-check-col"><input type="checkbox" class="ex-checkbox" onchange="toggleDone(this)"></div>
      <div class="exercise-card">
        <div class="ex-num">8</div>
        <div class="ex-body">
          <a class="ex-name" href="https://www.google.com/search?q=tr%C3%ADceps+corda+polia+muscula%C3%A7%C3%A3o&tbm=isch" target="_blank" rel="noopener">Tríceps Corda Polia</a>
          <div class="ex-meta"><span class="ex-tag">3 Séries</span><span class="ex-tag rep">10 Reps</span></div>
          <div class="ex-muscles">Tríceps braquial (todas as cabeças)</div>
        </div>
      </div>
    </div>

    <div class="ex-wrapper" data-f="A" style="animation-delay:.27s">
      <div class="ex-check-col"><input type="checkbox" class="ex-checkbox" onchange="toggleDone(this)"></div>
      <div class="exercise-card">
        <div class="ex-num">9</div>
        <div class="ex-body">
          <a class="ex-name" href="https://www.google.com/search?q=rosca+alternada+halteres+b%C3%ADceps+muscula%C3%A7%C3%A3o&tbm=isch" target="_blank" rel="noopener">Rosca Alternada com Halteres</a>
          <div class="ex-meta"><span class="ex-tag">3 Séries</span><span class="ex-tag rep">10 Reps</span></div>
          <div class="ex-muscles">Bíceps braquial · Braquial · Braquiorradial</div>
        </div>
      </div>
    </div>

    <div class="ex-wrapper" data-f="A" style="animation-delay:.30s">
      <div class="ex-check-col"><input type="checkbox" class="ex-checkbox" onchange="toggleDone(this)"></div>
      <div class="exercise-card">
        <div class="ex-num">10</div>
        <div class="ex-body">
          <a class="ex-name" href="https://www.google.com/search?q=rosca+martelo+halteres+b%C3%ADceps+muscula%C3%A7%C3%A3o&tbm=isch" target="_blank" rel="noopener">Rosca Martelo</a>
          <div class="ex-meta"><span class="ex-tag">3 Séries</span><span class="ex-tag rep">10 Reps</span></div>
          <div class="ex-muscles">Braquiorradial · Bíceps · Braquial</div>
        </div>
      </div>
    </div>

    <div class="ex-wrapper" data-f="A" style="animation-delay:.33s">
      <div class="ex-check-col"><input type="checkbox" class="ex-checkbox" onchange="toggleDone(this)"></div>
      <div class="exercise-card">
        <div class="ex-num">11</div>
        <div class="ex-body">
          <a class="ex-name" href="https://www.google.com/search?q=abdominal+supra+polia+alta+muscula%C3%A7%C3%A3o&tbm=isch" target="_blank" rel="noopener">Abdominal Supra Polia Alta</a>
          <div class="ex-meta"><span class="ex-tag">3 Séries</span><span class="ex-tag rep">15 Reps</span></div>
          <div class="ex-muscles">Reto abdominal superior · Oblíquos</div>
        </div>
      </div>
    </div>

  </div>
  <div class="ficha-footer">
    <span>Total: <strong>11</strong></span><span>Séries: <strong>~33</strong></span>
    <button class="reset-btn" onclick="resetFicha('A')">↺ Resetar</button>
  </div>
</section>

<!-- ===== FICHA B ===== -->
<section class="ficha" id="fichaB">
  <div class="ficha-header">
    <div class="ficha-letter">B</div>
    <div class="ficha-info">
      <div class="subtitle">Ficha B · Inferior</div>
      <h2>PERNA COMPLETA + GLÚTEO</h2>
      <div class="groups">10 exercícios · toque no nome para ver no Google Imagens</div>
    </div>
  </div>
  <div class="exercise-list">

    <div class="ex-wrapper" data-f="B" style="animation-delay:.03s">
      <div class="ex-check-col"><input type="checkbox" class="ex-checkbox" onchange="toggleDone(this)"></div>
      <div class="exercise-card">
        <div class="ex-num">1</div>
        <div class="ex-body">
          <a class="ex-name" href="https://www.google.com/search?q=leg+press+45+muscula%C3%A7%C3%A3o&tbm=isch" target="_blank" rel="noopener">Leg Press 45°</a>
          <div class="ex-meta"><span class="ex-tag">4 Séries</span><span class="ex-tag rep">8 Reps</span></div>
          <div class="ex-muscles">Quadríceps · Glúteo máximo · Isquiotibiais</div>
        </div>
      </div>
    </div>

    <div class="ex-wrapper" data-f="B" style="animation-delay:.06s">
      <div class="ex-check-col"><input type="checkbox" class="ex-checkbox" onchange="toggleDone(this)"></div>
      <div class="exercise-card">
        <div class="ex-num">2</div>
        <div class="ex-body">
          <a class="ex-name" href="https://www.google.com/search?q=afundo+halteres+muscula%C3%A7%C3%A3o&tbm=isch" target="_blank" rel="noopener">Afundo com Halteres</a>
          <div class="ex-meta"><span class="ex-tag">3 Séries</span><span class="ex-tag rep">8 Reps</span></div>
          <div class="ex-muscles">Quadríceps · Glúteo máximo · Isquiotibiais</div>
        </div>
      </div>
    </div>

    <div class="ex-wrapper" data-f="B" style="animation-delay:.09s">
      <div class="ex-check-col"><input type="checkbox" class="ex-checkbox" onchange="toggleDone(this)"></div>
      <div class="exercise-card">
        <div class="ex-num">3</div>
        <div class="ex-body">
          <a class="ex-name" href="https://www.google.com/search?q=cadeira+extensora+quadric%C3%ADceps+muscula%C3%A7%C3%A3o&tbm=isch" target="_blank" rel="noopener">Extensora (Cadeira)</a>
          <div class="ex-meta"><span class="ex-tag">3 Séries</span><span class="ex-tag rep">10 Reps</span></div>
          <div class="ex-muscles">Quadríceps (reto femoral, vastos)</div>
        </div>
      </div>
    </div>

    <div class="ex-wrapper" data-f="B" style="animation-delay:.12s">
      <div class="ex-check-col"><input type="checkbox" class="ex-checkbox" onchange="toggleDone(this)"></div>
      <div class="exercise-card">
        <div class="ex-num">4</div>
        <div class="ex-body">
          <a class="ex-name" href="https://www.google.com/search?q=levantamento+terra+m%C3%A1quina+muscula%C3%A7%C3%A3o&tbm=isch" target="_blank" rel="noopener">Levantamento Terra Máquina</a>
          <div class="ex-meta"><span class="ex-tag">3 Séries</span><span class="ex-tag rep">8 Reps</span></div>
          <div class="ex-muscles">Isquiotibiais · Glúteo máximo · Eretores</div>
        </div>
      </div>
    </div>

    <div class="ex-wrapper" data-f="B" style="animation-delay:.15s">
      <div class="ex-check-col"><input type="checkbox" class="ex-checkbox" onchange="toggleDone(this)"></div>
      <div class="exercise-card">
        <div class="ex-num">5</div>
        <div class="ex-body">
          <a class="ex-name" href="https://www.google.com/search?q=stiff+barra+muscula%C3%A7%C3%A3o&tbm=isch" target="_blank" rel="noopener">Stiff Barra</a>
          <div class="ex-meta"><span class="ex-tag">3 Séries</span><span class="ex-tag rep">8 Reps</span></div>
          <div class="ex-muscles">Isquiotibiais · Glúteo máximo · Lombares</div>
        </div>
      </div>
    </div>

    <div class="ex-wrapper" data-f="B" style="animation-delay:.18s">
      <div class="ex-check-col"><input type="checkbox" class="ex-checkbox" onchange="toggleDone(this)"></div>
      <div class="exercise-card">
        <div class="ex-num">6</div>
        <div class="ex-body">
          <a class="ex-name" href="https://www.google.com/search?q=cadeira+abdutora+gl%C3%BAteo+m%C3%A9dio+muscula%C3%A7%C3%A3o&tbm=isch" target="_blank" rel="noopener">Abdutor (Máquina)</a>
          <div class="ex-meta"><span class="ex-tag">3 Séries</span><span class="ex-tag rep">12 Reps</span></div>
          <div class="ex-muscles">Glúteo médio · Glúteo mínimo · TFL</div>
        </div>
      </div>
    </div>

    <div class="ex-wrapper" data-f="B" style="animation-delay:.21s">
      <div class="ex-check-col"><input type="checkbox" class="ex-checkbox" onchange="toggleDone(this)"></div>
      <div class="exercise-card">
        <div class="ex-num">7</div>
        <div class="ex-body">
          <a class="ex-name" href="https://www.google.com/search?q=hip+thrust+eleva%C3%A7%C3%A3o+quadril+barra+gl%C3%BAteo&tbm=isch" target="_blank" rel="noopener">Elevação de Quadril Barra (Hip Thrust)</a>
          <div class="ex-meta"><span class="ex-tag">4 Séries</span><span class="ex-tag rep">10 Reps</span></div>
          <div class="ex-muscles">Glúteo máximo · Isquiotibiais · Abdutores</div>
        </div>
      </div>
    </div>

    <div class="ex-wrapper" data-f="B" style="animation-delay:.24s">
      <div class="ex-check-col"><input type="checkbox" class="ex-checkbox" onchange="toggleDone(this)"></div>
      <div class="exercise-card">
        <div class="ex-num">8</div>
        <div class="ex-body">
          <a class="ex-name" href="https://www.google.com/search?q=abdu%C3%A7%C3%A3o+quadril+p%C3%A9+polia+baixa&tbm=isch" target="_blank" rel="noopener">Abdução em Pé na Polia Baixa</a>
          <div class="ex-meta"><span class="ex-tag">3 Séries</span><span class="ex-tag rep">12 Reps</span></div>
          <div class="ex-muscles">Glúteo médio · Glúteo mínimo · TFL</div>
        </div>
      </div>
    </div>

    <div class="ex-wrapper" data-f="B" style="animation-delay:.27s">
      <div class="ex-check-col"><input type="checkbox" class="ex-checkbox" onchange="toggleDone(this)"></div>
      <div class="exercise-card">
        <div class="ex-num">9</div>
        <div class="ex-body">
          <a class="ex-name" href="https://www.google.com/search?q=panturrilha+em+p%C3%A9+m%C3%A1quina+muscula%C3%A7%C3%A3o&tbm=isch" target="_blank" rel="noopener">Panturrilha em Pé Máquina</a>
          <div class="ex-meta"><span class="ex-tag">4 Séries</span><span class="ex-tag rep">12 Reps</span></div>
          <div class="ex-muscles">Gastrocnêmio · Sóleo</div>
        </div>
      </div>
    </div>

    <div class="ex-wrapper" data-f="B" style="animation-delay:.30s">
      <div class="ex-check-col"><input type="checkbox" class="ex-checkbox" onchange="toggleDone(this)"></div>
      <div class="exercise-card">
        <div class="ex-num">10</div>
        <div class="ex-body">
          <a class="ex-name" href="https://www.google.com/search?q=abdominal+infra+paralela+muscula%C3%A7%C3%A3o&tbm=isch" target="_blank" rel="noopener">Abdominal Infra Paralela</a>
          <div class="ex-meta"><span class="ex-tag">4 Séries</span><span class="ex-tag rep">20 Reps</span></div>
          <div class="ex-muscles">Reto abdominal inferior · Iliopsoas</div>
        </div>
      </div>
    </div>

  </div>
  <div class="ficha-footer">
    <span>Total: <strong>10</strong></span><span>Séries: <strong>~34</strong></span>
    <button class="reset-btn" onclick="resetFicha('B')">↺ Resetar</button>
  </div>
</section>

<!-- ===== FICHA C ===== -->
<section class="ficha" id="fichaC">
  <div class="ficha-header">
    <div class="ficha-letter">C</div>
    <div class="ficha-info">
      <div class="subtitle">Ficha C · Superior 2</div>
      <h2>OMBRO + COSTAS + BRAÇOS</h2>
      <div class="groups">11 exercícios · toque no nome para ver no Google Imagens</div>
    </div>
  </div>
  <div class="exercise-list">

    <div class="ex-wrapper" data-f="C" style="animation-delay:.03s">
      <div class="ex-check-col"><input type="checkbox" class="ex-checkbox" onchange="toggleDone(this)"></div>
      <div class="exercise-card">
        <div class="ex-num">1</div>
        <div class="ex-body">
          <a class="ex-name" href="https://www.google.com/search?q=desenvolvimento+halteres+ombro+muscula%C3%A7%C3%A3o&tbm=isch" target="_blank" rel="noopener">Desenvolvimento Halteres</a>
          <div class="ex-meta"><span class="ex-tag">4 Séries</span><span class="ex-tag rep">8 Reps</span></div>
          <div class="ex-muscles">Deltóide ant./médio · Trapézio · Tríceps</div>
        </div>
      </div>
    </div>

    <div class="ex-wrapper" data-f="C" style="animation-delay:.06s">
      <div class="ex-check-col"><input type="checkbox" class="ex-checkbox" onchange="toggleDone(this)"></div>
      <div class="exercise-card">
        <div class="ex-num">2</div>
        <div class="ex-body">
          <a class="ex-name" href="https://www.google.com/search?q=eleva%C3%A7%C3%A3o+lateral+halteres+ombro+muscula%C3%A7%C3%A3o&tbm=isch" target="_blank" rel="noopener">Elevação Lateral Halteres</a>
          <div class="ex-meta"><span class="ex-tag">3 Séries</span><span class="ex-tag rep">10 Reps</span></div>
          <div class="ex-muscles">Deltóide médio · Supraspinal · Trapézio sup.</div>
        </div>
      </div>
    </div>

    <div class="ex-wrapper" data-f="C" style="animation-delay:.09s">
      <div class="ex-check-col"><input type="checkbox" class="ex-checkbox" onchange="toggleDone(this)"></div>
      <div class="exercise-card">
        <div class="ex-num">3</div>
        <div class="ex-body">
          <a class="ex-name" href="https://www.google.com/search?q=eleva%C3%A7%C3%A3o+lateral+inclinada+ombro+muscula%C3%A7%C3%A3o&tbm=isch" target="_blank" rel="noopener">Elevação Lateral Inclinada</a>
          <div class="ex-meta"><span class="ex-tag">3 Séries</span><span class="ex-tag rep">10 Reps</span></div>
          <div class="ex-muscles">Deltóide médio (amplitude maior)</div>
        </div>
      </div>
    </div>

    <div class="ex-wrapper" data-f="C" style="animation-delay:.12s">
      <div class="ex-check-col"><input type="checkbox" class="ex-checkbox" onchange="toggleDone(this)"></div>
      <div class="exercise-card">
        <div class="ex-num">4</div>
        <div class="ex-body">
          <a class="ex-name" href="https://www.google.com/search?q=crucifixo+inverso+ombro+delt%C3%B3ide+posterior+muscula%C3%A7%C3%A3o&tbm=isch" target="_blank" rel="noopener">Crucifixo Inverso</a>
          <div class="ex-meta"><span class="ex-tag">3 Séries</span><span class="ex-tag rep">12 Reps</span></div>
          <div class="ex-muscles">Deltóide posterior · Rombóides · Trapézio</div>
        </div>
      </div>
    </div>

    <div class="ex-wrapper" data-f="C" style="animation-delay:.15s">
      <div class="ex-check-col"><input type="checkbox" class="ex-checkbox" onchange="toggleDone(this)"></div>
      <div class="exercise-card">
        <div class="ex-num">5</div>
        <div class="ex-body">
          <a class="ex-name" href="https://www.google.com/search?q=puxada+fechada+supinada+costas+b%C3%ADceps+muscula%C3%A7%C3%A3o&tbm=isch" target="_blank" rel="noopener">Puxada Fechada Supinada</a>
          <div class="ex-meta"><span class="ex-tag">3 Séries</span><span class="ex-tag rep">8 Reps</span></div>
          <div class="ex-muscles">Latíssimo · Bíceps · Rombóides</div>
        </div>
      </div>
    </div>

    <div class="ex-wrapper" data-f="C" style="animation-delay:.18s">
      <div class="ex-check-col"><input type="checkbox" class="ex-checkbox" onchange="toggleDone(this)"></div>
      <div class="exercise-card">
        <div class="ex-num">6</div>
        <div class="ex-body">
          <a class="ex-name" href="https://www.google.com/search?q=remada+cavalinho+T-bar+row+costas+muscula%C3%A7%C3%A3o&tbm=isch" target="_blank" rel="noopener">Remada Cavalinho (T-Bar Row)</a>
          <div class="ex-meta"><span class="ex-tag">3 Séries</span><span class="ex-tag rep">8 Reps</span></div>
          <div class="ex-muscles">Latíssimo · Rombóides · Trapézio · Bíceps</div>
        </div>
      </div>
    </div>

    <div class="ex-wrapper" data-f="C" style="animation-delay:.21s">
      <div class="ex-check-col"><input type="checkbox" class="ex-checkbox" onchange="toggleDone(this)"></div>
      <div class="exercise-card">
        <div class="ex-num">7</div>
        <div class="ex-body">
          <a class="ex-name" href="https://www.google.com/search?q=tr%C3%ADceps+testa+barra+W+skull+crusher+muscula%C3%A7%C3%A3o&tbm=isch" target="_blank" rel="noopener">Tríceps Testa Barra W</a>
          <div class="ex-meta"><span class="ex-tag">3 Séries</span><span class="ex-tag rep">10 Reps</span></div>
          <div class="ex-muscles">Tríceps braquial (cabeça longa e medial)</div>
        </div>
      </div>
    </div>

    <div class="ex-wrapper" data-f="C" style="animation-delay:.24s">
      <div class="ex-check-col"><input type="checkbox" class="ex-checkbox" onchange="toggleDone(this)"></div>
      <div class="exercise-card">
        <div class="ex-num">8</div>
        <div class="ex-body">
          <a class="ex-name" href="https://www.google.com/search?q=mergulho+paralelas+tr%C3%ADceps+muscula%C3%A7%C3%A3o&tbm=isch" target="_blank" rel="noopener">Mergulho Máquina / Paralelas</a>
          <div class="ex-meta"><span class="ex-tag">3 Séries</span><span class="ex-tag rep">10 Reps</span></div>
          <div class="ex-muscles">Tríceps · Peitoral inferior · Deltóide ant.</div>
        </div>
      </div>
    </div>

    <div class="ex-wrapper" data-f="C" style="animation-delay:.27s">
      <div class="ex-check-col"><input type="checkbox" class="ex-checkbox" onchange="toggleDone(this)"></div>
      <div class="exercise-card">
        <div class="ex-num">9</div>
        <div class="ex-body">
          <a class="ex-name" href="https://www.google.com/search?q=rosca+scott+b%C3%ADceps+preacher+curl+muscula%C3%A7%C3%A3o&tbm=isch" target="_blank" rel="noopener">Rosca Scott</a>
          <div class="ex-meta"><span class="ex-tag">3 Séries</span><span class="ex-tag rep">10 Reps</span></div>
          <div class="ex-muscles">Bíceps braquial (cabeça curta) · Braquial</div>
        </div>
      </div>
    </div>

    <div class="ex-wrapper" data-f="C" style="animation-delay:.30s">
      <div class="ex-check-col"><input type="checkbox" class="ex-checkbox" onchange="toggleDone(this)"></div>
      <div class="exercise-card">
        <div class="ex-num">10</div>
        <div class="ex-body">
          <a class="ex-name" href="https://www.google.com/search?q=rosca+direta+barra+W+EZ+b%C3%ADceps+muscula%C3%A7%C3%A3o&tbm=isch" target="_blank" rel="noopener">Rosca Direta Barra W</a>
          <div class="ex-meta"><span class="ex-tag">3 Séries</span><span class="ex-tag rep">10 Reps</span></div>
          <div class="ex-muscles">Bíceps braquial · Braquial · Braquiorradial</div>
        </div>
      </div>
    </div>

    <div class="ex-wrapper" data-f="C" style="animation-delay:.33s">
      <div class="ex-check-col"><input type="checkbox" class="ex-checkbox" onchange="toggleDone(this)"></div>
      <div class="exercise-card">
        <div class="ex-num">11</div>
        <div class="ex-body">
          <a class="ex-name" href="https://www.google.com/search?q=face+pull+polia+ombro+delt%C3%B3ide+posterior+muscula%C3%A7%C3%A3o&tbm=isch" target="_blank" rel="noopener">Face Pull</a>
          <div class="ex-meta"><span class="ex-tag">3 Séries</span><span class="ex-tag rep">12 Reps</span></div>
          <div class="ex-muscles">Deltóide posterior · Manguito rotador · Trapézio</div>
        </div>
      </div>
    </div>

  </div>
  <div class="ficha-footer">
    <span>Total: <strong>11</strong></span><span>Séries: <strong>~34</strong></span>
    <button class="reset-btn" onclick="resetFicha('C')">↺ Resetar</button>
  </div>
</section>
</div><!-- /content -->

<!-- IMPORTAR CSV -->
<div class="csv-section">
  <div class="csv-title-row">
    <div class="csv-title">📂 Importar Treino (CSV)</div>
    <div style="position:relative">
      <button class="csv-help-btn" onclick="toggleTooltip()">?</button>
      <div class="csv-tooltip" id="csvTooltip">
        <strong>Como montar seu CSV</strong>
        <p>O arquivo deve ter <strong>5 colunas</strong> nessa ordem:</p>
        <code>ficha,exercicio,series,reps,musculos</code>
        <strong>Exemplo:</strong>
        <code>A,Supino Reto Barra,3,8,Peitoral · Tríceps
A,Crucifixo,3,10,Peitoral
B,Leg Press 45°,4,8,Quadríceps
C,Desenvolvimento,4,8,Deltóide</code>
        <strong>Regras:</strong>
        <ul>
          <li><strong>ficha</strong>: A, B ou C</li>
          <li><strong>exercicio</strong>: nome do exercício</li>
          <li><strong>series</strong>: número (ex: 3)</li>
          <li><strong>reps</strong>: número (ex: 10)</li>
          <li><strong>musculos</strong>: texto livre</li>
          <li>Primeira linha = cabeçalho (ignorada)</li>
          <li>Separador: vírgula</li>
          <li>Salve como .csv (UTF-8)</li>
          <li>Ao clicar no exercício abre Google Imagens automaticamente</li>
        </ul>
        <button class="close-tip" onclick="toggleTooltip()">✕ Fechar</button>
      </div>
    </div>
  </div>
  <div class="csv-row">
    <label class="csv-label">
      <input type="file" accept=".csv" id="csvFile" onchange="onFileChosen(this)">
      📄 <span id="csvFileName">Escolher arquivo .csv</span>
    </label>
    <button class="csv-import-btn" onclick="importCSV()">Importar</button>
  </div>
  <div class="csv-status" id="csvStatus"></div>
</div>

<footer style="text-align:center; padding: 20px 16px calc(20px + var(--safe-bot)); font-size:0.68rem; color:#444; letter-spacing:0.06em;">
  Desenvolvido por <a href="https://www.instagram.com/mariohenq" target="_blank" rel="noopener" style="color:#666; text-decoration:none;">@mariohenq</a>
</footer>

<script>
  // Service Worker removido (arquivo externo não disponível no GitHub Pages single-file)

  let activeTab = 'A';

  function showFicha(id, btn) {
    document.querySelectorAll('.ficha').forEach(f => f.classList.remove('visible'));
    document.querySelectorAll('.tab').forEach(b => b.classList.remove('active'));
    document.getElementById('ficha' + id).classList.add('visible');
    btn.classList.add('active');
    activeTab = id;
    updateProgress();
    window.scrollTo({ top: 0, behavior: 'smooth' });
  }

  function toggleDone(cb) {
    cb.closest('.ex-wrapper').classList.toggle('done', cb.checked);
    updateProgress();
  }

  function updateProgress() {
    const s = document.getElementById('ficha' + activeTab);
    const all  = s.querySelectorAll('.ex-checkbox');
    const done = s.querySelectorAll('.ex-checkbox:checked').length;
    const total = all.length;
    const pct  = total > 0 ? Math.round((done / total) * 100) : 0;
    document.getElementById('progressFill').style.width = pct + '%';
    document.getElementById('progressCount').textContent = done + ' / ' + total;
    document.getElementById('progressLabel').textContent =
      done === total && total > 0 ? '🎉 Treino concluído!' : 'Progresso — Ficha ' + activeTab;
  }

  function resetFicha(id) {
    document.getElementById('ficha' + id).querySelectorAll('.ex-checkbox').forEach(cb => {
      cb.checked = false;
      cb.closest('.ex-wrapper').classList.remove('done');
    });
    updateProgress();
  }

  // ── TOOLTIP ──
  function toggleTooltip() {
    document.getElementById('csvTooltip').classList.toggle('open');
  }
  document.addEventListener('click', function(e) {
    const tip = document.getElementById('csvTooltip');
    if (!tip.contains(e.target) && !e.target.classList.contains('csv-help-btn')) {
      tip.classList.remove('open');
    }
  });

  // ── CSV ──
  function onFileChosen(input) {
    const name = input.files[0] ? input.files[0].name : 'Escolher arquivo .csv';
    document.getElementById('csvFileName').textContent = name;
    document.getElementById('csvStatus').textContent = '';
    document.getElementById('csvStatus').className = 'csv-status';
  }

  function importCSV() {
    const file = document.getElementById('csvFile').files[0];
    const status = document.getElementById('csvStatus');
    if (!file) {
      status.textContent = '⚠️ Selecione um arquivo CSV primeiro.';
      status.className = 'csv-status err';
      return;
    }
    const reader = new FileReader();
    reader.onload = function(e) {
      try {
        const lines = e.target.result.split(/\r?\n/).filter(l => l.trim());
        const rows = lines.slice(1); // pula cabeçalho
        if (!rows.length) throw new Error('Arquivo vazio ou sem dados.');

        // Limpa fichas existentes
        ['A','B','C'].forEach(f => {
          const list = document.querySelector('#ficha' + f + ' .exercise-list');
          if (list) list.innerHTML = '';
        });

        let counts = {A:0, B:0, C:0};
        rows.forEach((line, idx) => {
          const cols = line.split(',');
          if (cols.length < 4) return;
          const [ficha, exercicio, series, reps, musculos=''] = cols.map(c => c.trim());
          const f = ficha.toUpperCase();
          if (!['A','B','C'].includes(f)) return;
          counts[f]++;
          const list = document.querySelector('#ficha' + f + ' .exercise-list');
          if (!list) return;
          const delay = (counts[f] * 0.03).toFixed(2);
          const href = `https://www.google.com/search?q=${encodeURIComponent(exercicio)}+muscula%C3%A7%C3%A3o&tbm=isch`;
          const wrapper = document.createElement('div');
          wrapper.className = 'ex-wrapper';
          wrapper.dataset.f = f;
          wrapper.style.animationDelay = delay + 's';
          wrapper.innerHTML = `
            <div class="ex-check-col"><input type="checkbox" class="ex-checkbox" onchange="toggleDone(this)"></div>
            <div class="exercise-card">
              <div class="ex-num">${counts[f]}</div>
              <div class="ex-body">
                <a class="ex-name" href="${href}" target="_blank" rel="noopener">${exercicio}</a>
                <div class="ex-meta"><span class="ex-tag">${series} Séries</span><span class="ex-tag rep">${reps} Reps</span></div>
                <div class="ex-muscles">${musculos}</div>
              </div>
            </div>`;
          list.appendChild(wrapper);
        });

        const total = counts.A + counts.B + counts.C;
        status.textContent = `✅ ${total} exercícios importados (A:${counts.A} B:${counts.B} C:${counts.C})`;
        status.className = 'csv-status ok';
        updateProgress();
      } catch(err) {
        status.textContent = '❌ Erro ao ler CSV: ' + err.message;
        status.className = 'csv-status err';
      }
    };
    reader.readAsText(file, 'UTF-8');
  }

  updateProgress();
</script>
</body>
</html>
