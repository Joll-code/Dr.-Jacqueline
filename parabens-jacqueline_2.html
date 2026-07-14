<!DOCTYPE html>
<html lang="pt-BR">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Parabéns, Dra. Jacqueline Ramalho 💕</title>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Playfair+Display:ital,wght@0,600;0,700;1,600;1,700&family=Great+Vibes&family=Quicksand:wght@400;500;600;700&display=swap" rel="stylesheet">
<style>
  :root{
    --cream: #fbf0ea;
    --cream-2: #fff8f4;
    --blush: #f3c9d4;
    --rose: #d98aa8;
    --deep-rose: #a8446b;
    --deep-rose-2: #8a2f54;
    --gold: #c9a15a;
    --gold-light: #e8d4a8;
    --plum: #4a2a38;
    --plum-soft: #6d4658;
    --white: #fffbf9;
  }

  *{ box-sizing: border-box; }

  html, body{
    margin: 0;
    padding: 0;
    min-height: 100%;
    background: radial-gradient(ellipse at top, var(--cream-2) 0%, var(--cream) 55%, #f6e2da 100%);
    font-family: 'Quicksand', sans-serif;
    color: var(--plum);
    overflow-x: hidden;
  }

  #confetti-canvas{
    position: fixed;
    inset: 0;
    width: 100%;
    height: 100%;
    pointer-events: none;
    z-index: 5;
  }

  .stage{
    position: relative;
    min-height: 100vh;
    display: flex;
    align-items: center;
    justify-content: center;
    padding: 48px 20px;
  }

  /* ---- tela de suspense / consulta do resultado ---- */
  #reveal-screen{
    position: fixed;
    inset: 0;
    z-index: 50;
    display: flex;
    align-items: center;
    justify-content: center;
    background: radial-gradient(ellipse at center, #fff8f4 0%, #f6e2da 65%, #f0d3c6 100%);
    transition: opacity 0.8s ease, visibility 0.8s ease;
  }
  #reveal-screen.hidden{
    opacity: 0;
    visibility: hidden;
    pointer-events: none;
  }

  .reveal-box{
    text-align: center;
    max-width: 420px;
    width: 100%;
    padding: 20px;
  }

  .reveal-icon{
    width: 74px;
    height: 74px;
    margin: 0 auto 22px;
    border-radius: 50%;
    background: var(--white);
    display: flex;
    align-items: center;
    justify-content: center;
    box-shadow: 0 8px 26px rgba(168,68,107,0.18);
    font-size: 30px;
  }

  .reveal-title{
    font-family: 'Playfair Display', serif;
    font-style: italic;
    font-weight: 600;
    font-size: clamp(20px, 4.4vw, 26px);
    color: var(--plum-soft);
    margin: 0 0 8px;
  }

  .reveal-sub{
    font-size: 14px;
    color: var(--rose);
    letter-spacing: 0.05em;
    margin: 0 0 30px;
  }

  .start-btn{
    font-family: 'Quicksand', sans-serif;
    font-weight: 700;
    font-size: 15px;
    letter-spacing: 0.04em;
    color: var(--white);
    background: linear-gradient(135deg, var(--deep-rose) 0%, var(--deep-rose-2) 100%);
    border: none;
    padding: 15px 34px;
    border-radius: 999px;
    cursor: pointer;
    box-shadow: 0 10px 24px rgba(168,68,107,0.3);
    transition: transform 0.2s ease, box-shadow 0.2s ease;
  }
  .start-btn:hover{
    transform: translateY(-2px);
    box-shadow: 0 14px 30px rgba(168,68,107,0.36);
  }
  .start-btn:active{ transform: translateY(0); }

  .lawyer-input{
    width: 100%;
    font-family: 'Quicksand', sans-serif;
    font-weight: 600;
    font-size: 13.5px;
    letter-spacing: 0.03em;
    color: var(--plum-soft);
    background: var(--white);
    border: 1.5px solid var(--gold-light);
    border-radius: 999px;
    padding: 15px 20px;
    text-align: center;
    margin-bottom: 18px;
    outline: none;
    box-shadow: inset 0 1px 3px rgba(168,68,107,0.06);
    transition: border-color 0.2s ease, box-shadow 0.2s ease;
  }
  .lawyer-input::placeholder{
    color: var(--rose);
    opacity: 0.65;
    font-size: 12px;
    letter-spacing: 0.08em;
  }
  .lawyer-input:focus{
    border-color: var(--rose);
    box-shadow: 0 0 0 4px rgba(217,138,168,0.15);
  }

  .loading-wrap{
    display: none;
  }
  .loading-wrap.active{
    display: block;
    animation: fade-in 0.4s ease forwards;
  }

  .progress-track{
    width: 100%;
    height: 8px;
    border-radius: 999px;
    background: rgba(168,68,107,0.12);
    overflow: hidden;
    margin: 0 0 18px;
  }
  .progress-fill{
    height: 100%;
    width: 0%;
    border-radius: 999px;
    background: linear-gradient(90deg, var(--rose), var(--deep-rose-2));
    transition: width 0.35s ease;
  }

  .suspense-text{
    font-size: 14.5px;
    color: var(--plum-soft);
    min-height: 20px;
    font-weight: 600;
  }

  #app-content{
    opacity: 0;
  }
  #app-content.ready{
    opacity: 1;
  }

  /* floating ambient hearts */
  .ambient{
    position: fixed;
    inset: 0;
    pointer-events: none;
    z-index: 1;
    overflow: hidden;
  }
  .ambient span{
    position: absolute;
    bottom: -10%;
    font-size: 22px;
    color: var(--blush);
    opacity: 0.55;
    animation: float-up linear infinite;
  }
  @keyframes float-up{
    0%{ transform: translateY(0) translateX(0) rotate(0deg); opacity: 0; }
    10%{ opacity: 0.6; }
    90%{ opacity: 0.4; }
    100%{ transform: translateY(-115vh) translateX(var(--drift, 30px)) rotate(25deg); opacity: 0; }
  }

  .card{
    position: relative;
    z-index: 2;
    max-width: 620px;
    width: 100%;
    background: linear-gradient(180deg, var(--white) 0%, var(--cream-2) 100%);
    border: 1px solid var(--gold-light);
    border-radius: 18px;
    padding: 56px 44px 44px;
    box-shadow:
      0 2px 4px rgba(168, 68, 107, 0.08),
      0 20px 60px rgba(168, 68, 107, 0.18),
      inset 0 0 0 6px var(--cream-2);
    text-align: center;
    opacity: 0;
    transform: translateY(24px) scale(0.98);
    animation: card-in 1s cubic-bezier(.2,.8,.25,1) 0.15s forwards;
  }

  @keyframes card-in{
    to{ opacity: 1; transform: translateY(0) scale(1); }
  }

  .card::before, .card::after{
    content: "";
    position: absolute;
    width: 34px;
    height: 34px;
    border: 2px solid var(--gold);
    opacity: 0.55;
  }
  .card::before{ top: 14px; left: 14px; border-right: none; border-bottom: none; }
  .card::after{ bottom: 14px; right: 14px; border-left: none; border-top: none; }

  .eyebrow{
    display: inline-flex;
    align-items: center;
    gap: 10px;
    font-size: 12.5px;
    letter-spacing: 0.32em;
    text-transform: uppercase;
    color: var(--deep-rose);
    font-weight: 600;
    margin-bottom: 22px;
  }
  .eyebrow .line{
    width: 26px;
    height: 1px;
    background: var(--gold);
    display: inline-block;
  }

  .scales-wrap{
    margin: 0 auto 24px;
    width: 132px;
    height: 108px;
    opacity: 0;
    animation: fade-in 0.9s ease 0.5s forwards;
  }
  @keyframes fade-in{ to{ opacity: 1; } }

  .headline{
    font-family: 'Playfair Display', serif;
    font-style: italic;
    font-weight: 600;
    font-size: clamp(24px, 4.6vw, 32px);
    color: var(--plum-soft);
    margin: 0 0 6px;
    line-height: 1.25;
  }

  .name{
    font-family: 'Great Vibes', cursive;
    font-size: clamp(46px, 9vw, 68px);
    color: var(--deep-rose-2);
    margin: 4px 0 18px;
    line-height: 1.1;
    text-shadow: 0 1px 0 rgba(255,255,255,0.6);
  }

  .stamp-wrap{
    display: flex;
    justify-content: center;
    margin: 6px 0 26px;
  }

  .stamp{
    position: relative;
    width: 148px;
    height: 148px;
    display: flex;
    align-items: center;
    justify-content: center;
    transform: rotate(-8deg) scale(2.6);
    opacity: 0;
    animation: stamp-down 0.55s cubic-bezier(.2,1.4,.4,1) 1.35s forwards;
  }
  @keyframes stamp-down{
    0%{ opacity: 0; transform: rotate(-8deg) scale(2.6); }
    60%{ opacity: 1; }
    100%{ opacity: 1; transform: rotate(-8deg) scale(1); }
  }
  .stamp svg{ width: 100%; height: 100%; }

  .message{
    font-size: 16.5px;
    line-height: 1.85;
    color: var(--plum-soft);
    max-width: 460px;
    margin: 0 auto 28px;
    opacity: 0;
    animation: fade-in 0.9s ease 1.9s forwards;
  }
  .message strong{ color: var(--deep-rose-2); font-weight: 700; }

  .divider{
    width: 70px;
    height: 2px;
    margin: 0 auto 26px;
    background: linear-gradient(90deg, transparent, var(--gold), transparent);
    opacity: 0;
    animation: fade-in 0.9s ease 2.1s forwards;
  }

  .signoff{
    font-family: 'Playfair Display', serif;
    font-style: italic;
    font-size: 15.5px;
    color: var(--rose);
    opacity: 0;
    animation: fade-in 0.9s ease 2.25s forwards;
  }
  .signoff .who{
    display: block;
    margin-top: 6px;
    font-size: 17px;
    color: var(--deep-rose-2);
    font-weight: 600;
  }

  .badge-row{
    margin-top: 30px;
    display: flex;
    justify-content: center;
    gap: 8px;
    opacity: 0;
    animation: fade-in 0.9s ease 2.4s forwards;
  }
  .badge-row span{
    width: 6px; height: 6px; border-radius: 50%;
    background: var(--gold);
    opacity: 0.6;
  }

  @media (max-width: 480px){
    .card{ padding: 44px 24px 34px; }
  }

  @media (prefers-reduced-motion: reduce){
    *{ animation-duration: 0.01ms !important; animation-delay: 0ms !important; }
  }
</style>
</head>
<body>

<div id="reveal-screen">
  <div class="reveal-box">
    <div id="preStart">
      <div class="reveal-icon">⚖️</div>
      <h2 class="reveal-title">O resultado do Exame de Ordem saiu</h2>
      <p class="reveal-sub">&mdash; SOMENTE PARA ADVOGADA JACQUELINE :P</p>
      <button class="start-btn" id="startBtn">TÁ COM OAB AI?</button>
    </div>

    <div class="loading-wrap" id="lawyerIdStep">
      <div class="reveal-icon">🪪</div>
      <h2 class="reveal-title">Confirme sua identidade</h2>
      <p class="reveal-sub" style="margin-bottom:18px;">pode por qualquer número <3 </p>
      <input type="text" id="lawyerIdInput" placeholder="NÚMERO DA CARTEIRINHA DE ADVOGADO" class="lawyer-input">
      <button class="start-btn" id="continueBtn" style="margin-top: 6px;">Continuar</button>
    </div>

    <div class="loading-wrap" id="loadingWrap">
      <div class="reveal-icon">⏳</div>
      <h2 class="reveal-title" id="loadingTitle">CALMA QUE O TIO É LENTO
</h2>
      <div class="progress-track">
        <div class="progress-fill" id="progressFill"></div>
      </div>
      <p class="suspense-text" id="suspenseText">Acessando o sistema</p>
    </div>
  </div>
</div>

<div id="app-content">
<canvas id="confetti-canvas"></canvas>
<div class="ambient" id="ambient"></div>

<div class="stage">
  <div class="card">
    <div class="eyebrow"><span class="line"></span>Aprovada &amp; amada<span class="line"></span></div>

    <div class="scales-wrap">
      <svg viewBox="0 0 140 116" xmlns="http://www.w3.org/2000/svg">
        <!-- balança da justiça com corações nos pratos -->
        <line x1="70" y1="10" x2="70" y2="92" stroke="#c9a15a" stroke-width="3" stroke-linecap="round"/>
        <line x1="24" y1="26" x2="116" y2="26" stroke="#c9a15a" stroke-width="3" stroke-linecap="round"/>
        <circle cx="70" cy="10" r="5" fill="#c9a15a"/>
        <!-- linhas dos pratos -->
        <line x1="24" y1="26" x2="18" y2="58" stroke="#c9a15a" stroke-width="1.6"/>
        <line x1="24" y1="26" x2="30" y2="58" stroke="#c9a15a" stroke-width="1.6"/>
        <line x1="116" y1="26" x2="110" y2="58" stroke="#c9a15a" stroke-width="1.6"/>
        <line x1="116" y1="26" x2="122" y2="58" stroke="#c9a15a" stroke-width="1.6"/>
        <!-- prato esquerdo -->
        <path d="M10 58 Q24 78 38 58 Z" fill="none" stroke="#c9a15a" stroke-width="2.4" stroke-linecap="round" stroke-linejoin="round"/>
        <!-- prato direito -->
        <path d="M102 58 Q116 78 130 58 Z" fill="none" stroke="#c9a15a" stroke-width="2.4" stroke-linecap="round" stroke-linejoin="round"/>
        <!-- coração esquerdo -->
        <path d="M24 44 C21 40 14 41 14 47 C14 52 24 59 24 59 C24 59 34 52 34 47 C34 41 27 40 24 44 Z" fill="#d98aa8"/>
        <!-- coração direito -->
        <path d="M116 44 C113 40 106 41 106 47 C106 52 116 59 116 59 C116 59 126 52 126 47 C126 41 119 40 116 44 Z" fill="#a8446b"/>
        <!-- base -->
        <path d="M50 92 L90 92 L98 106 L42 106 Z" fill="#c9a15a" opacity="0.9"/>
        <rect x="60" y="92" width="20" height="6" fill="#c9a15a"/>
      </svg>
    </div>

    <p class="headline">Hoje a lista saiu, e o nome que apareceu foi</p>
    <h1 class="name">Jacqueline Ramalho</h1>

    <div class="stamp-wrap">
      <div class="stamp">
        <svg viewBox="0 0 160 160" xmlns="http://www.w3.org/2000/svg">
          <circle cx="80" cy="80" r="72" fill="none" stroke="#a8446b" stroke-width="3"/>
          <circle cx="80" cy="80" r="62" fill="none" stroke="#a8446b" stroke-width="1.5" stroke-dasharray="2 4"/>
          <path id="stampCirclePath" d="M80,18 a62,62 0 1,1 -0.1,0" fill="none"/>
          <text font-family="Quicksand, sans-serif" font-size="12.5" font-weight="700" letter-spacing="3" fill="#a8446b">
            <textPath href="#stampCirclePath" startOffset="2%">
              ★ APROVADA ★ ORDEM DOS ADVOGADOS ★
            </textPath>
          </text>
          <text x="80" y="72" text-anchor="middle" font-family="'Great Vibes', cursive" font-size="30" fill="#a8446b">Dra.</text>
          <path d="M80 88 C74 82 62 84 62 94 C62 103 80 116 80 116 C80 116 98 103 98 94 C98 84 86 82 80 88 Z" fill="#d98aa8"/>
        </svg>
      </div>
    </div>

    <p class="message">
      Você estudou, chorou, duvidou e insistiu — e hoje o mundo confirma
      o que eu já sabia desde sempre: <strong>você é brilhante</strong>.
      Parabéns pela aprovação, agora é Doutora!. Cada madrugada
      de estudo valeu a pena, e eu tive a sorte de assistir de camarote.
    </p>

    <div class="divider"></div>

    <p class="signoff">Com todo orgulho e amor do mundo,
      <span class="who">- Joll</span>
    </p>

    <div class="badge-row"><span></span><span></span><span></span></div>
  </div>
</div>
</div>

<script>
  // ---- fluxo de suspense antes de revelar o resultado ----
  const revealScreen = document.getElementById('reveal-screen');
  const preStart = document.getElementById('preStart');
  const lawyerIdStep = document.getElementById('lawyerIdStep');
  const lawyerIdInput = document.getElementById('lawyerIdInput');
  const continueBtn = document.getElementById('continueBtn');
  const loadingWrap = document.getElementById('loadingWrap');
  const startBtn = document.getElementById('startBtn');
  const progressFill = document.getElementById('progressFill');
  const suspenseText = document.getElementById('suspenseText');
  const loadingTitle = document.getElementById('loadingTitle');
  const appContent = document.getElementById('app-content');

  const phrases = [
    'Acessando o sistema da OAB',
    'Localizando inscrição de Jacqueline Ramalho',
    'Conferindo gabarito da 1ª e 2ª fase',
    'Verificando nota de corte',
    'Confirmando resultado final'
  ];

  startBtn.addEventListener('click', () => {
    preStart.style.display = 'none';
    lawyerIdStep.classList.add('active');
  });

  continueBtn.addEventListener('click', () => {
    lawyerIdStep.classList.remove('active');
    lawyerIdStep.style.display = 'none';
    loadingWrap.classList.add('active');
    runSuspense();
  });

  lawyerIdInput.addEventListener('keydown', (e) => {
    if(e.key === 'Enter') continueBtn.click();
  });

  function runSuspense(){
    let progress = 0;
    let phraseIndex = 0;
    suspenseText.textContent = phrases[0];

    const phraseInterval = setInterval(() => {
      phraseIndex++;
      if(phraseIndex < phrases.length){
        suspenseText.textContent = phrases[phraseIndex];
      }
    }, 900);

    const progressInterval = setInterval(() => {
      // avança em passos irregulares para parecer mais real,
      // e trava por um instante em ~92% para gerar suspense
      let step = progress < 70 ? (4 + Math.random()*8) : (1 + Math.random()*2);
      if(progress >= 92 && progress < 96){
        step = 0.3;
      }
      progress = Math.min(progress + step, 100);
      progressFill.style.width = progress + '%';

      if(progress >= 100){
        clearInterval(progressInterval);
        clearInterval(phraseInterval);
        loadingTitle.textContent = 'Resultado encontrado!';
        suspenseText.textContent = 'Preparando a revelação';
        setTimeout(revealResult, 900);
      }
    }, 220);
  }

  function revealResult(){
    revealScreen.classList.add('hidden');
    appContent.classList.add('ready');
    startConfetti();
    startAmbientHearts();
  }

  // ---- corações ambientes flutuando ----
  function startAmbientHearts(){
  const ambient = document.getElementById('ambient');
  const heartChars = ['♥','❤','♡'];
  const AMBIENT_COUNT = 14;
  for(let i=0;i<AMBIENT_COUNT;i++){
    const el = document.createElement('span');
    el.textContent = heartChars[Math.floor(Math.random()*heartChars.length)];
    el.style.left = Math.random()*100 + '%';
    el.style.fontSize = (14 + Math.random()*20) + 'px';
    el.style.setProperty('--drift', (Math.random()*80-40) + 'px');
    el.style.animationDuration = (9 + Math.random()*10) + 's';
    el.style.animationDelay = (Math.random()*10) + 's';
    ambient.appendChild(el);
  }
  }

  // ---- confete (corações + quadradinhos) ----
  function startConfetti(){
  const canvas = document.getElementById('confetti-canvas');
  const ctx = canvas.getContext('2d');
  let w, h;
  function resize(){
    w = canvas.width = window.innerWidth;
    h = canvas.height = window.innerHeight;
  }
  resize();
  window.addEventListener('resize', resize);

  const colors = ['#d98aa8', '#a8446b', '#c9a15a', '#f3c9d4', '#8a2f54'];
  const pieces = [];
  const PIECE_COUNT = 140;

  function makePiece(burst){
    return {
      x: Math.random()*w,
      y: burst ? h*0.3 + Math.random()*h*0.2 : -20 - Math.random()*h,
      vx: (Math.random()-0.5) * (burst ? 6 : 1.2),
      vy: burst ? -(4 + Math.random()*6) : (1 + Math.random()*2.2),
      gravity: 0.14,
      size: 6 + Math.random()*7,
      rotation: Math.random()*360,
      rotSpeed: (Math.random()-0.5) * 8,
      color: colors[Math.floor(Math.random()*colors.length)],
      shape: Math.random() > 0.45 ? 'heart' : 'square',
      opacity: 1,
      life: 0
    };
  }

  for(let i=0;i<PIECE_COUNT;i++) pieces.push(makePiece(false));
  // burst inicial (comemoração)
  for(let i=0;i<90;i++) pieces.push(makePiece(true));

  function drawHeart(p){
    ctx.save();
    ctx.translate(p.x, p.y);
    ctx.rotate(p.rotation * Math.PI/180);
    ctx.scale(p.size/14, p.size/14);
    ctx.beginPath();
    ctx.moveTo(0, 3);
    ctx.bezierCurveTo(-7, -6, -14, 1, 0, 12);
    ctx.bezierCurveTo(14, 1, 7, -6, 0, 3);
    ctx.fillStyle = p.color;
    ctx.globalAlpha = p.opacity;
    ctx.fill();
    ctx.restore();
  }

  function drawSquare(p){
    ctx.save();
    ctx.translate(p.x, p.y);
    ctx.rotate(p.rotation * Math.PI/180);
    ctx.fillStyle = p.color;
    ctx.globalAlpha = p.opacity;
    ctx.fillRect(-p.size/2, -p.size/2, p.size, p.size*0.6);
    ctx.restore();
  }

  function tick(){
    ctx.clearRect(0,0,w,h);
    for(const p of pieces){
      p.vy += p.gravity * 0.05;
      p.x += p.vx;
      p.y += p.vy;
      p.rotation += p.rotSpeed;
      p.life++;

      if(p.y > h + 20){
        p.y = -20;
        p.x = Math.random()*w;
        p.vy = 1 + Math.random()*2.2;
        p.vx = (Math.random()-0.5) * 1.2;
      }
      if(p.x < -20) p.x = w+20;
      if(p.x > w+20) p.x = -20;

      if(p.shape === 'heart') drawHeart(p); else drawSquare(p);
    }
    requestAnimationFrame(tick);
  }
  tick();
  }
</script>

</body>
</html>
