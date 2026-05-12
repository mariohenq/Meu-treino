<!DOCTYPE html>
<html lang="pt-BR">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0, viewport-fit=cover">
<meta name="apple-mobile-web-app-capable" content="yes">
<meta name="apple-mobile-web-app-status-bar-style" content="black-translucent">
<meta name="apple-mobile-web-app-title" content="Treino">
<meta name="theme-color" content="#0a0a0a">
<title>Ficha de Treino</title>
<link rel="manifest" href="./manifest.json">

<!-- Apple touch icon inline SVG via data URI -->
<link rel="apple-touch-icon" href="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAMAAAADACAYAAABS3GwHAAAABHNCSVQICAgIfAhkiAAAAAlwSFlzAAADdgAAA3YBfdWCzAAAABl0RVh0U29mdHdhcmUAd3d3Lmlua3NjYXBlLm9yZ5vuPBoAAAMeSURBVHic7cExAQAAAMKg9U9tDB+gAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAAeAMBuAABHgAAAABJRU5ErkJggg==">

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
    text-decoration: none;
    color: inherit;
    transition: border-color 0.18s, opacity 0.3s;
    height: 80px;
    max-height: 80px;
    -webkit-touch-callout: none;
  }
  .exercise-card:active { opacity: 0.75; }

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
    color: var(--text);
    line-height: 1.25;
    transition: color 0.2s;
  }


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

  /* ── INSTALL BANNER (iOS) ── */
  .install-banner {
    background: rgba(232,255,58,0.08);
    border: 1px solid rgba(232,255,58,0.18);
    border-radius: 10px;
    padding: 12px 14px;
    margin: 0 12px 14px;
    font-size: 0.72rem;
    color: var(--text);
    line-height: 1.5;
    display: flex;
    align-items: flex-start;
    gap: 10px;
  }
  .install-banner .icon { font-size: 1.4rem; flex-shrink: 0; }
  .install-banner strong { color: var(--accent); display: block; margin-bottom: 2px; }
  .install-banner .close-btn {
    margin-left: auto;
    background: none;
    border: none;
    color: var(--muted);
    font-size: 1rem;
    cursor: pointer;
    padding: 0 0 0 8px;
    flex-shrink: 0;
    font-family: inherit;
  }
  .install-banner.hidden { display: none; }
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

<!-- iOS install hint -->
<div class="install-banner" id="installBanner">
  <span class="icon">📲</span>
  <div>
    <strong>Adicionar à tela inicial</strong>
    Toque em <b>Compartilhar</b> (□↑) no Safari e depois em <b>"Adicionar à Tela de Início"</b> para usar como app offline.
  </div>
  <button class="close-btn" onclick="document.getElementById('installBanner').classList.add('hidden');localStorage.setItem('bannerDismissed','1')">✕</button>
</div>

<div class="content">

<!-- ===== FICHA A ===== -->
<section class="ficha visible" id="fichaA">
  <div class="ficha-header">
    <div class="ficha-letter">A</div>
    <div class="ficha-info">
      <div class="subtitle">Ficha A · Superior 1</div>
      <h2>PEITO + COSTAS + BRAÇOS</h2>
      <div class="groups">11 exercícios · toque para ver no Google Imagens</div>
    </div>
  </div>
  <div class="exercise-list">

    <div class="ex-wrapper" data-f="A" style="animation-delay:.03s">
      <div class="ex-check-col"><input type="checkbox" class="ex-checkbox" onchange="toggleDone(this)"></div>
      <a class="exercise-card" href="https://www.google.com/search?q=supino+reto+barra+muscula%C3%A7%C3%A3o&tbm=isch" target="_blank" rel="noopener">
        <div class="ex-num">1</div>
        <div class="ex-body">
          <div class="ex-name">Supino Reto Barra</div>
          
          <div class="ex-meta"><span class="ex-tag">3 Séries</span><span class="ex-tag rep">8 Reps</span></div>
          <div class="ex-muscles">Peitoral maior · Deltóide ant. · Tríceps</div>
        </div>
        
      </a>
    </div>

    <div class="ex-wrapper" data-f="A" style="animation-delay:.06s">
      <div class="ex-check-col"><input type="checkbox" class="ex-checkbox" onchange="toggleDone(this)"></div>
      <a class="exercise-card" href="https://www.google.com/search?q=supino+inclinado+halteres+muscula%C3%A7%C3%A3o&tbm=isch" target="_blank" rel="noopener">
        <div class="ex-num">2</div>
        <div class="ex-body">
          <div class="ex-name">Supino Inclinado Halteres</div>
          
          <div class="ex-meta"><span class="ex-tag">3 Séries</span><span class="ex-tag rep">8 Reps</span></div>
          <div class="ex-muscles">Peitoral superior · Deltóide ant. · Tríceps</div>
        </div>
        
      </a>
    </div>

    <div class="ex-wrapper" data-f="A" style="animation-delay:.09s">
      <div class="ex-check-col"><input type="checkbox" class="ex-checkbox" onchange="toggleDone(this)"></div>
      <a class="exercise-card" href="https://www.google.com/search?q=crucifixo+reto+halteres+muscula%C3%A7%C3%A3o&tbm=isch" target="_blank" rel="noopener">
        <div class="ex-num">3</div>
        <div class="ex-body">
          <div class="ex-name">Crucifixo Reto com Halteres</div>
          
          <div class="ex-meta"><span class="ex-tag">3 Séries</span><span class="ex-tag rep">10 Reps</span></div>
          <div class="ex-muscles">Peitoral maior · Deltóide anterior</div>
        </div>
        
      </a>
    </div>

    <div class="ex-wrapper" data-f="A" style="animation-delay:.12s">
      <div class="ex-check-col"><input type="checkbox" class="ex-checkbox" onchange="toggleDone(this)"></div>
      <a class="exercise-card" href="https://www.google.com/search?q=puxada+aberta+neutra+costas+muscula%C3%A7%C3%A3o&tbm=isch" target="_blank" rel="noopener">
        <div class="ex-num">4</div>
        <div class="ex-body">
          <div class="ex-name">Puxada Aberta Neutra</div>
          
          <div class="ex-meta"><span class="ex-tag">3 Séries</span><span class="ex-tag rep">8 Reps</span></div>
          <div class="ex-muscles">Latíssimo · Rombóides · Bíceps</div>
        </div>
        
      </a>
    </div>

    <div class="ex-wrapper" data-f="A" style="animation-delay:.15s">
      <div class="ex-check-col"><input type="checkbox" class="ex-checkbox" onchange="toggleDone(this)"></div>
      <a class="exercise-card" href="https://www.google.com/search?q=remada+curvada+pronada+halteres+muscula%C3%A7%C3%A3o&tbm=isch" target="_blank" rel="noopener">
        <div class="ex-num">5</div>
        <div class="ex-body">
          <div class="ex-name">Remada Curvada Pronada Halteres</div>
          
          <div class="ex-meta"><span class="ex-tag">3 Séries</span><span class="ex-tag rep">8 Reps</span></div>
          <div class="ex-muscles">Latíssimo · Trapézio · Rombóides · Bíceps</div>
        </div>
        
      </a>
    </div>

    <div class="ex-wrapper" data-f="A" style="animation-delay:.18s">
      <div class="ex-check-col"><input type="checkbox" class="ex-checkbox" onchange="toggleDone(this)"></div>
      <a class="exercise-card" href="https://www.google.com/search?q=remada+baixa+tri%C3%A2ngulo+polia+muscula%C3%A7%C3%A3o&tbm=isch" target="_blank" rel="noopener">
        <div class="ex-num">6</div>
        <div class="ex-body">
          <div class="ex-name">Remada Baixa Triângulo</div>
          
          <div class="ex-meta"><span class="ex-tag">3 Séries</span><span class="ex-tag rep">10 Reps</span></div>
          <div class="ex-muscles">Latíssimo · Trapézio · Rombóides</div>
        </div>
        
      </a>
    </div>

    <div class="ex-wrapper" data-f="A" style="animation-delay:.21s">
      <div class="ex-check-col"><input type="checkbox" class="ex-checkbox" onchange="toggleDone(this)"></div>
      <a class="exercise-card" href="https://www.google.com/search?q=tr%C3%ADceps+franc%C3%AAs+halter+muscula%C3%A7%C3%A3o&tbm=isch" target="_blank" rel="noopener">
        <div class="ex-num">7</div>
        <div class="ex-body">
          <div class="ex-name">Tríceps Francês com Halter</div>
          
          <div class="ex-meta"><span class="ex-tag">3 Séries</span><span class="ex-tag rep">10 Reps</span></div>
          <div class="ex-muscles">Tríceps braquial (cabeça longa)</div>
        </div>
        
      </a>
    </div>

    <div class="ex-wrapper" data-f="A" style="animation-delay:.24s">
      <div class="ex-check-col"><input type="checkbox" class="ex-checkbox" onchange="toggleDone(this)"></div>
      <a class="exercise-card" href="https://www.google.com/search?q=tr%C3%ADceps+corda+polia+muscula%C3%A7%C3%A3o&tbm=isch" target="_blank" rel="noopener">
        <div class="ex-num">8</div>
        <div class="ex-body">
          <div class="ex-name">Tríceps Corda Polia</div>
          
          <div class="ex-meta"><span class="ex-tag">3 Séries</span><span class="ex-tag rep">10 Reps</span></div>
          <div class="ex-muscles">Tríceps braquial (todas as cabeças)</div>
        </div>
        
      </a>
    </div>

    <div class="ex-wrapper" data-f="A" style="animation-delay:.27s">
      <div class="ex-check-col"><input type="checkbox" class="ex-checkbox" onchange="toggleDone(this)"></div>
      <a class="exercise-card" href="https://www.google.com/search?q=rosca+alternada+halteres+b%C3%ADceps+muscula%C3%A7%C3%A3o&tbm=isch" target="_blank" rel="noopener">
        <div class="ex-num">9</div>
        <div class="ex-body">
          <div class="ex-name">Rosca Alternada com Halteres</div>
          
          <div class="ex-meta"><span class="ex-tag">3 Séries</span><span class="ex-tag rep">10 Reps</span></div>
          <div class="ex-muscles">Bíceps braquial · Braquial · Braquiorradial</div>
        </div>
        
      </a>
    </div>

    <div class="ex-wrapper" data-f="A" style="animation-delay:.30s">
      <div class="ex-check-col"><input type="checkbox" class="ex-checkbox" onchange="toggleDone(this)"></div>
      <a class="exercise-card" href="https://www.google.com/search?q=rosca+martelo+halteres+b%C3%ADceps+muscula%C3%A7%C3%A3o&tbm=isch" target="_blank" rel="noopener">
        <div class="ex-num">10</div>
        <div class="ex-body">
          <div class="ex-name">Rosca Martelo</div>
          
          <div class="ex-meta"><span class="ex-tag">3 Séries</span><span class="ex-tag rep">10 Reps</span></div>
          <div class="ex-muscles">Braquiorradial · Bíceps · Braquial</div>
        </div>
        
      </a>
    </div>

    <div class="ex-wrapper" data-f="A" style="animation-delay:.33s">
      <div class="ex-check-col"><input type="checkbox" class="ex-checkbox" onchange="toggleDone(this)"></div>
      <a class="exercise-card" href="https://www.google.com/search?q=abdominal+supra+polia+alta+muscula%C3%A7%C3%A3o&tbm=isch" target="_blank" rel="noopener">
        <div class="ex-num">11</div>
        <div class="ex-body">
          <div class="ex-name">Abdominal Supra Polia Alta</div>
          
          <div class="ex-meta"><span class="ex-tag">3 Séries</span><span class="ex-tag rep">15 Reps</span></div>
          <div class="ex-muscles">Reto abdominal superior · Oblíquos</div>
        </div>
        
      </a>
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
      <div class="groups">10 exercícios · toque para ver no Google Imagens</div>
    </div>
  </div>
  <div class="exercise-list">

    <div class="ex-wrapper" data-f="B" style="animation-delay:.03s">
      <div class="ex-check-col"><input type="checkbox" class="ex-checkbox" onchange="toggleDone(this)"></div>
      <a class="exercise-card" href="https://www.google.com/search?q=leg+press+45+muscula%C3%A7%C3%A3o&tbm=isch" target="_blank" rel="noopener">
        <div class="ex-num">1</div>
        <div class="ex-body">
          <div class="ex-name">Leg Press 45°</div>
          <div class="ex-meta"><span class="ex-tag">4 Séries</span><span class="ex-tag rep">8 Reps</span></div>
          <div class="ex-muscles">Quadríceps · Glúteo máximo · Isquiotibiais</div>
        </div>
      </a>
    </div>

    <div class="ex-wrapper" data-f="B" style="animation-delay:.06s">
      <div class="ex-check-col"><input type="checkbox" class="ex-checkbox" onchange="toggleDone(this)"></div>
      <a class="exercise-card" href="https://www.google.com/search?q=afundo+halteres+muscula%C3%A7%C3%A3o&tbm=isch" target="_blank" rel="noopener">
        <div class="ex-num">2</div>
        <div class="ex-body">
          <div class="ex-name">Afundo com Halteres</div>
          <div class="ex-meta"><span class="ex-tag">3 Séries</span><span class="ex-tag rep">8 Reps</span></div>
          <div class="ex-muscles">Quadríceps · Glúteo máximo · Isquiotibiais</div>
        </div>
      </a>
    </div>

    <div class="ex-wrapper" data-f="B" style="animation-delay:.09s">
      <div class="ex-check-col"><input type="checkbox" class="ex-checkbox" onchange="toggleDone(this)"></div>
      <a class="exercise-card" href="https://www.google.com/search?q=cadeira+extensora+quadric%C3%ADceps+muscula%C3%A7%C3%A3o&tbm=isch" target="_blank" rel="noopener">
        <div class="ex-num">3</div>
        <div class="ex-body">
          <div class="ex-name">Extensora (Cadeira)</div>
          <div class="ex-meta"><span class="ex-tag">3 Séries</span><span class="ex-tag rep">10 Reps</span></div>
          <div class="ex-muscles">Quadríceps (reto femoral, vastos)</div>
        </div>
      </a>
    </div>

    <div class="ex-wrapper" data-f="B" style="animation-delay:.12s">
      <div class="ex-check-col"><input type="checkbox" class="ex-checkbox" onchange="toggleDone(this)"></div>
      <a class="exercise-card" href="https://www.google.com/search?q=levantamento+terra+m%C3%A1quina+muscula%C3%A7%C3%A3o&tbm=isch" target="_blank" rel="noopener">
        <div class="ex-num">4</div>
        <div class="ex-body">
          <div class="ex-name">Levantamento Terra Máquina</div>
          <div class="ex-meta"><span class="ex-tag">3 Séries</span><span class="ex-tag rep">8 Reps</span></div>
          <div class="ex-muscles">Isquiotibiais · Glúteo máximo · Eretores</div>
        </div>
      </a>
    </div>

    <div class="ex-wrapper" data-f="B" style="animation-delay:.15s">
      <div class="ex-check-col"><input type="checkbox" class="ex-checkbox" onchange="toggleDone(this)"></div>
      <a class="exercise-card" href="https://www.google.com/search?q=stiff+barra+muscula%C3%A7%C3%A3o&tbm=isch" target="_blank" rel="noopener">
        <div class="ex-num">5</div>
        <div class="ex-body">
          <div class="ex-name">Stiff Barra</div>
          <div class="ex-meta"><span class="ex-tag">3 Séries</span><span class="ex-tag rep">8 Reps</span></div>
          <div class="ex-muscles">Isquiotibiais · Glúteo máximo · Lombares</div>
        </div>
      </a>
    </div>

    <div class="ex-wrapper" data-f="B" style="animation-delay:.18s">
      <div class="ex-check-col"><input type="checkbox" class="ex-checkbox" onchange="toggleDone(this)"></div>
      <a class="exercise-card" href="https://www.google.com/search?q=cadeira+abdutora+gl%C3%BAteo+m%C3%A9dio+muscula%C3%A7%C3%A3o&tbm=isch" target="_blank" rel="noopener">
        <div class="ex-num">6</div>
        <div class="ex-body">
          <div class="ex-name">Abdutor (Máquina)</div>
          <div class="ex-meta"><span class="ex-tag">3 Séries</span><span class="ex-tag rep">12 Reps</span></div>
          <div class="ex-muscles">Glúteo médio · Glúteo mínimo · TFL</div>
        </div>
      </a>
    </div>

    <div class="ex-wrapper" data-f="B" style="animation-delay:.21s">
      <div class="ex-check-col"><input type="checkbox" class="ex-checkbox" onchange="toggleDone(this)"></div>
      <a class="exercise-card" href="https://www.google.com/search?q=hip+thrust+eleva%C3%A7%C3%A3o+quadril+barra+gl%C3%BAteo&tbm=isch" target="_blank" rel="noopener">
        <div class="ex-num">7</div>
        <div class="ex-body">
          <div class="ex-name">Elevação de Quadril Barra (Hip Thrust)</div>
          <div class="ex-meta"><span class="ex-tag">4 Séries</span><span class="ex-tag rep">10 Reps</span></div>
          <div class="ex-muscles">Glúteo máximo · Isquiotibiais · Abdutores</div>
        </div>
      </a>
    </div>

    <div class="ex-wrapper" data-f="B" style="animation-delay:.24s">
      <div class="ex-check-col"><input type="checkbox" class="ex-checkbox" onchange="toggleDone(this)"></div>
      <a class="exercise-card" href="https://www.google.com/search?q=abdu%C3%A7%C3%A3o+quadril+p%C3%A9+polia+baixa&tbm=isch" target="_blank" rel="noopener">
        <div class="ex-num">8</div>
        <div class="ex-body">
          <div class="ex-name">Abdução em Pé na Polia Baixa</div>
          <div class="ex-meta"><span class="ex-tag">3 Séries</span><span class="ex-tag rep">12 Reps</span></div>
          <div class="ex-muscles">Glúteo médio · Glúteo mínimo · TFL</div>
        </div>
      </a>
    </div>

    <div class="ex-wrapper" data-f="B" style="animation-delay:.27s">
      <div class="ex-check-col"><input type="checkbox" class="ex-checkbox" onchange="toggleDone(this)"></div>
      <a class="exercise-card" href="https://www.google.com/search?q=panturrilha+em+p%C3%A9+m%C3%A1quina+muscula%C3%A7%C3%A3o&tbm=isch" target="_blank" rel="noopener">
        <div class="ex-num">9</div>
        <div class="ex-body">
          <div class="ex-name">Panturrilha em Pé Máquina</div>
          <div class="ex-meta"><span class="ex-tag">4 Séries</span><span class="ex-tag rep">12 Reps</span></div>
          <div class="ex-muscles">Gastrocnêmio · Sóleo</div>
        </div>
      </a>
    </div>

    <div class="ex-wrapper" data-f="B" style="animation-delay:.30s">
      <div class="ex-check-col"><input type="checkbox" class="ex-checkbox" onchange="toggleDone(this)"></div>
      <a class="exercise-card" href="https://www.google.com/search?q=abdominal+infra+paralela+muscula%C3%A7%C3%A3o&tbm=isch" target="_blank" rel="noopener">
        <div class="ex-num">10</div>
        <div class="ex-body">
          <div class="ex-name">Abdominal Infra Paralela</div>
          <div class="ex-meta"><span class="ex-tag">4 Séries</span><span class="ex-tag rep">20 Reps</span></div>
          <div class="ex-muscles">Reto abdominal inferior · Iliopsoas</div>
        </div>
      </a>
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
      <div class="groups">11 exercícios · toque para ver no Google Imagens</div>
    </div>
  </div>
  <div class="exercise-list">

    <div class="ex-wrapper" data-f="C" style="animation-delay:.03s">
      <div class="ex-check-col"><input type="checkbox" class="ex-checkbox" onchange="toggleDone(this)"></div>
      <a class="exercise-card" href="https://www.google.com/search?q=desenvolvimento+halteres+ombro+muscula%C3%A7%C3%A3o&tbm=isch" target="_blank" rel="noopener">
        <div class="ex-num">1</div>
        <div class="ex-body">
          <div class="ex-name">Desenvolvimento Halteres</div>
          <div class="ex-meta"><span class="ex-tag">4 Séries</span><span class="ex-tag rep">8 Reps</span></div>
          <div class="ex-muscles">Deltóide ant./médio · Trapézio · Tríceps</div>
        </div>
      </a>
    </div>

    <div class="ex-wrapper" data-f="C" style="animation-delay:.06s">
      <div class="ex-check-col"><input type="checkbox" class="ex-checkbox" onchange="toggleDone(this)"></div>
      <a class="exercise-card" href="https://www.google.com/search?q=eleva%C3%A7%C3%A3o+lateral+halteres+ombro+muscula%C3%A7%C3%A3o&tbm=isch" target="_blank" rel="noopener">
        <div class="ex-num">2</div>
        <div class="ex-body">
          <div class="ex-name">Elevação Lateral Halteres</div>
          <div class="ex-meta"><span class="ex-tag">3 Séries</span><span class="ex-tag rep">10 Reps</span></div>
          <div class="ex-muscles">Deltóide médio · Supraspinal · Trapézio sup.</div>
        </div>
      </a>
    </div>

    <div class="ex-wrapper" data-f="C" style="animation-delay:.09s">
      <div class="ex-check-col"><input type="checkbox" class="ex-checkbox" onchange="toggleDone(this)"></div>
      <a class="exercise-card" href="https://www.google.com/search?q=eleva%C3%A7%C3%A3o+lateral+inclinada+ombro+muscula%C3%A7%C3%A3o&tbm=isch" target="_blank" rel="noopener">
        <div class="ex-num">3</div>
        <div class="ex-body">
          <div class="ex-name">Elevação Lateral Inclinada</div>
          <div class="ex-meta"><span class="ex-tag">3 Séries</span><span class="ex-tag rep">10 Reps</span></div>
          <div class="ex-muscles">Deltóide médio (amplitude maior)</div>
        </div>
      </a>
    </div>

    <div class="ex-wrapper" data-f="C" style="animation-delay:.12s">
      <div class="ex-check-col"><input type="checkbox" class="ex-checkbox" onchange="toggleDone(this)"></div>
      <a class="exercise-card" href="https://www.google.com/search?q=crucifixo+inverso+ombro+delt%C3%B3ide+posterior+muscula%C3%A7%C3%A3o&tbm=isch" target="_blank" rel="noopener">
        <div class="ex-num">4</div>
        <div class="ex-body">
          <div class="ex-name">Crucifixo Inverso</div>
          <div class="ex-meta"><span class="ex-tag">3 Séries</span><span class="ex-tag rep">12 Reps</span></div>
          <div class="ex-muscles">Deltóide posterior · Rombóides · Trapézio</div>
        </div>
      </a>
    </div>

    <div class="ex-wrapper" data-f="C" style="animation-delay:.15s">
      <div class="ex-check-col"><input type="checkbox" class="ex-checkbox" onchange="toggleDone(this)"></div>
      <a class="exercise-card" href="https://www.google.com/search?q=puxada+fechada+supinada+costas+b%C3%ADceps+muscula%C3%A7%C3%A3o&tbm=isch" target="_blank" rel="noopener">
        <div class="ex-num">5</div>
        <div class="ex-body">
          <div class="ex-name">Puxada Fechada Supinada</div>
          <div class="ex-meta"><span class="ex-tag">3 Séries</span><span class="ex-tag rep">8 Reps</span></div>
          <div class="ex-muscles">Latíssimo · Bíceps · Rombóides</div>
        </div>
      </a>
    </div>

    <div class="ex-wrapper" data-f="C" style="animation-delay:.18s">
      <div class="ex-check-col"><input type="checkbox" class="ex-checkbox" onchange="toggleDone(this)"></div>
      <a class="exercise-card" href="https://www.google.com/search?q=remada+cavalinho+T-bar+row+costas+muscula%C3%A7%C3%A3o&tbm=isch" target="_blank" rel="noopener">
        <div class="ex-num">6</div>
        <div class="ex-body">
          <div class="ex-name">Remada Cavalinho (T-Bar Row)</div>
          <div class="ex-meta"><span class="ex-tag">3 Séries</span><span class="ex-tag rep">8 Reps</span></div>
          <div class="ex-muscles">Latíssimo · Rombóides · Trapézio · Bíceps</div>
        </div>
      </a>
    </div>

    <div class="ex-wrapper" data-f="C" style="animation-delay:.21s">
      <div class="ex-check-col"><input type="checkbox" class="ex-checkbox" onchange="toggleDone(this)"></div>
      <a class="exercise-card" href="https://www.google.com/search?q=tr%C3%ADceps+testa+barra+W+skull+crusher+muscula%C3%A7%C3%A3o&tbm=isch" target="_blank" rel="noopener">
        <div class="ex-num">7</div>
        <div class="ex-body">
          <div class="ex-name">Tríceps Testa Barra W</div>
          <div class="ex-meta"><span class="ex-tag">3 Séries</span><span class="ex-tag rep">10 Reps</span></div>
          <div class="ex-muscles">Tríceps braquial (cabeça longa e medial)</div>
        </div>
      </a>
    </div>

    <div class="ex-wrapper" data-f="C" style="animation-delay:.24s">
      <div class="ex-check-col"><input type="checkbox" class="ex-checkbox" onchange="toggleDone(this)"></div>
      <a class="exercise-card" href="https://www.google.com/search?q=mergulho+paralelas+tr%C3%ADceps+muscula%C3%A7%C3%A3o&tbm=isch" target="_blank" rel="noopener">
        <div class="ex-num">8</div>
        <div class="ex-body">
          <div class="ex-name">Mergulho Máquina / Paralelas</div>
          <div class="ex-meta"><span class="ex-tag">3 Séries</span><span class="ex-tag rep">10 Reps</span></div>
          <div class="ex-muscles">Tríceps · Peitoral inferior · Deltóide ant.</div>
        </div>
      </a>
    </div>

    <div class="ex-wrapper" data-f="C" style="animation-delay:.27s">
      <div class="ex-check-col"><input type="checkbox" class="ex-checkbox" onchange="toggleDone(this)"></div>
      <a class="exercise-card" href="https://www.google.com/search?q=rosca+scott+b%C3%ADceps+preacher+curl+muscula%C3%A7%C3%A3o&tbm=isch" target="_blank" rel="noopener">
        <div class="ex-num">9</div>
        <div class="ex-body">
          <div class="ex-name">Rosca Scott</div>
          <div class="ex-meta"><span class="ex-tag">3 Séries</span><span class="ex-tag rep">10 Reps</span></div>
          <div class="ex-muscles">Bíceps braquial (cabeça curta) · Braquial</div>
        </div>
      </a>
    </div>

    <div class="ex-wrapper" data-f="C" style="animation-delay:.30s">
      <div class="ex-check-col"><input type="checkbox" class="ex-checkbox" onchange="toggleDone(this)"></div>
      <a class="exercise-card" href="https://www.google.com/search?q=rosca+direta+barra+W+EZ+b%C3%ADceps+muscula%C3%A7%C3%A3o&tbm=isch" target="_blank" rel="noopener">
        <div class="ex-num">10</div>
        <div class="ex-body">
          <div class="ex-name">Rosca Direta Barra W</div>
          <div class="ex-meta"><span class="ex-tag">3 Séries</span><span class="ex-tag rep">10 Reps</span></div>
          <div class="ex-muscles">Bíceps braquial · Braquial · Braquiorradial</div>
        </div>
      </a>
    </div>

    <div class="ex-wrapper" data-f="C" style="animation-delay:.33s">
      <div class="ex-check-col"><input type="checkbox" class="ex-checkbox" onchange="toggleDone(this)"></div>
      <a class="exercise-card" href="https://www.google.com/search?q=face+pull+polia+ombro+delt%C3%B3ide+posterior+muscula%C3%A7%C3%A3o&tbm=isch" target="_blank" rel="noopener">
        <div class="ex-num">11</div>
        <div class="ex-body">
          <div class="ex-name">Face Pull</div>
          <div class="ex-meta"><span class="ex-tag">3 Séries</span><span class="ex-tag rep">12 Reps</span></div>
          <div class="ex-muscles">Deltóide posterior · Manguito rotador · Trapézio</div>
        </div>
      </a>
    </div>

  </div>
  <div class="ficha-footer">
    <span>Total: <strong>11</strong></span><span>Séries: <strong>~34</strong></span>
    <button class="reset-btn" onclick="resetFicha('C')">↺ Resetar</button>
  </div>
</section>

</div><!-- /content -->

<script>
  // Hide banner if dismissed
  if (localStorage.getItem('bannerDismissed')) {
    document.getElementById('installBanner').classList.add('hidden');
  }

  // Register Service Worker for offline
  if ('serviceWorker' in navigator) {
    navigator.serviceWorker.register('./sw.js').catch(() => {});
  }

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
    const all   = s.querySelectorAll('.ex-checkbox');
    const done  = s.querySelectorAll('.ex-checkbox:checked').length;
    const total = all.length;
    const pct   = total > 0 ? Math.round((done / total) * 100) : 0;

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

  updateProgress();
</script>

</body>
</html>
