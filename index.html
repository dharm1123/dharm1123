<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8"/>
<meta name="viewport" content="width=device-width,initial-scale=1.0"/>
<title>Dharm Dudhagara · Galaxy</title>
<meta name="description" content="AI / ML · Data Science · GenAI · Explorer · Builder"/>
<meta property="og:title" content="Dharm Dudhagara — Galaxy Portfolio"/>
<meta property="og:description" content="Interactive constellation of projects by Dharm Dudhagara — AI/ML and Data Science explorer."/>
<style>
  *{margin:0;padding:0;box-sizing:border-box;}
  html,body{width:100%;height:100%;overflow:hidden;background:#020813;font-family:'JetBrains Mono','Courier New',monospace;}

  #cv{position:fixed;inset:0;width:100%;height:100%;}

  /* ── LEFT PANEL ── */
  #panel{
    position:fixed;top:0;left:0;height:100%;width:300px;
    background:rgba(1,8,20,0.92);
    border-right:1px solid rgba(30,80,160,0.22);
    display:flex;flex-direction:column;
    padding:28px 22px 22px;
    backdrop-filter:blur(12px);
    z-index:10;
    transition:transform .45s cubic-bezier(.22,1,.36,1);
  }
  #panel.hidden{transform:translateX(-100%);}

  .p-logo{display:flex;align-items:center;gap:13px;margin-bottom:22px;}
  .p-avatar{
    width:48px;height:48px;border-radius:50%;
    background:rgba(4,18,48,0.9);
    border:1.5px solid rgba(42,100,200,0.45);
    display:flex;align-items:center;justify-content:center;
    font-size:13px;font-weight:600;color:#5a9fdd;flex-shrink:0;
    position:relative;
  }
  .p-avatar::after{
    content:'';position:absolute;inset:-4px;border-radius:50%;
    border:1px solid rgba(42,100,200,0.18);
    animation:spin 8s linear infinite;
  }
  @keyframes spin{to{transform:rotate(360deg);}}
  .p-name{font-size:15px;font-weight:600;color:#c5ddf5;letter-spacing:.02em;}
  .p-role{font-size:10px;color:#2a5070;letter-spacing:.15em;margin-top:3px;}

  .p-bio{
    font-size:11px;color:#1e4060;line-height:1.7;
    padding-left:10px;border-left:2px solid rgba(30,70,160,0.2);
    margin-bottom:20px;
  }

  .p-divider{height:1px;background:rgba(20,55,130,0.2);margin-bottom:20px;}

  /* project detail card */
  #p-default{display:flex;flex-direction:column;align-items:center;justify-content:center;flex:1;gap:10px;text-align:center;}
  #p-default .hint-ring{
    width:38px;height:38px;border-radius:50%;
    border:1px solid rgba(20,55,130,0.28);
    display:flex;align-items:center;justify-content:center;
  }
  #p-default .hint-dot{width:7px;height:7px;border-radius:50%;background:rgba(15,40,80,0.7);}
  #p-default .hint-label{font-size:10px;color:#1a3a52;letter-spacing:.15em;}
  #p-default .hint-sub{font-size:10px;color:#112030;line-height:1.6;}

  #p-detail{display:none;flex-direction:column;gap:10px;flex:1;min-height:0;}
  #p-bar{width:100%;height:2px;border-radius:1px;flex-shrink:0;}
  #p-lbl{font-size:10px;letter-spacing:.12em;flex-shrink:0;}
  #p-name{font-size:16px;font-weight:600;color:#b5d5f0;line-height:1.3;flex-shrink:0;}
  #p-desc{font-size:11px;color:#2a5068;line-height:1.7;flex:1;min-height:0;}
  #p-tech{display:flex;flex-wrap:wrap;gap:5px;flex-shrink:0;}
  #p-link{
    display:inline-flex;align-items:center;gap:5px;
    margin-top:4px;font-size:11px;text-decoration:none;
    letter-spacing:.06em;padding:6px 12px;
    border-radius:3px;background:rgba(15,45,110,0.2);
    border:1px solid rgba(30,80,180,0.2);
    transition:background .2s,border-color .2s;
    flex-shrink:0;
  }
  #p-link:hover{background:rgba(20,60,140,0.35);border-color:rgba(40,100,220,0.4);}
  #p-back{
    margin-top:6px;font-size:11px;color:#1a3a55;background:none;
    border:1px solid rgba(15,45,100,0.22);border-radius:3px;
    padding:5px 10px;cursor:pointer;letter-spacing:.05em;
    width:fit-content;transition:color .2s,border-color .2s;flex-shrink:0;
  }
  #p-back:hover{color:#4a8fcc;border-color:rgba(30,80,180,0.4);}

  /* stats row */
  .p-stats{display:flex;justify-content:space-around;padding:14px 0;border-top:1px solid rgba(20,55,130,0.2);border-bottom:1px solid rgba(20,55,130,0.2);margin-bottom:16px;}
  .p-stat-val{font-size:17px;font-weight:600;color:#3a7fcc;font-family:monospace;}
  .p-stat-lbl{font-size:10px;color:#162840;margin-top:2px;}

  /* social links */
  .p-socials{display:flex;flex-wrap:wrap;gap:6px;}
  .p-social{
    font-size:10px;color:#1e4060;text-decoration:none;
    padding:4px 9px;border:1px solid rgba(15,45,100,0.25);
    border-radius:3px;letter-spacing:.04em;
    transition:color .2s,border-color .2s;
  }
  .p-social:hover{color:#5a9fdd;border-color:rgba(30,90,200,0.45);}

  /* ── TOGGLE BUTTON ── */
  #toggle{
    position:fixed;top:20px;left:20px;z-index:20;
    width:38px;height:38px;border-radius:50%;
    background:rgba(2,10,28,0.85);
    border:1px solid rgba(30,80,160,0.35);
    cursor:pointer;display:flex;align-items:center;justify-content:center;
    transition:opacity .2s;display:none;
  }
  #toggle span{display:block;width:14px;height:1px;background:#3a7fcc;margin:2px auto;}
  #toggle:hover{border-color:rgba(40,100,220,0.55);}

  /* ── CORNER BADGE ── */
  #badge{
    position:fixed;bottom:18px;right:18px;z-index:10;
    font-size:10px;color:rgba(20,60,130,0.55);
    letter-spacing:.12em;pointer-events:none;
    text-align:right;line-height:1.6;
  }

  /* ── HINT ── */
  #hint{
    position:fixed;bottom:18px;left:50%;transform:translateX(-50%);
    font-size:10px;color:rgba(22,60,130,0.4);letter-spacing:.12em;
    pointer-events:none;white-space:nowrap;z-index:10;
    transition:opacity .5s;
  }

  /* ── MOBILE ── */
  @media(max-width:700px){
    #panel{width:100%;height:auto;bottom:0;top:auto;border-right:none;border-top:1px solid rgba(30,80,160,0.22);}
    #panel.hidden{transform:translateY(100%);}
    #toggle{display:flex;}
    #hint{display:none;}
  }
  @media(min-width:701px){
    #toggle{display:none;}
  }
</style>
</head>
<body>

<canvas id="cv"></canvas>

<div id="panel">
  <div class="p-logo">
    <div class="p-avatar">DD</div>
    <div>
      <div class="p-name">Dharm Dudhagara</div>
      <div class="p-role">♐ &nbsp;MSC DATA SCIENCE &nbsp;·&nbsp; AI / ML</div>
    </div>
  </div>

  <div class="p-bio">
    Transforming raw data into intelligent systems. Urban innovation · Generative AI · Explainable ML · Always aiming further than visible.
  </div>

  <div class="p-divider"></div>

  <div id="ddcard" style="flex:1;min-height:0;display:flex;flex-direction:column;">
    <div id="p-default">
      <div class="hint-ring"><div class="hint-dot"></div></div>
      <div class="hint-label">SELECT A PROJECT</div>
      <div class="hint-sub">Click any orbiting node in the constellation to explore project details.</div>
    </div>
    <div id="p-detail">
      <div id="p-bar"></div>
      <div id="p-lbl"></div>
      <div id="p-name"></div>
      <div id="p-desc"></div>
      <div id="p-tech"></div>
      <a id="p-link" href="#" target="_blank">View on GitHub &nbsp;↗</a>
      <button id="p-back">← back</button>
    </div>
  </div>

  <div class="p-stats">
    <div style="text-align:center"><div class="p-stat-val">5</div><div class="p-stat-lbl">repos</div></div>
    <div style="text-align:center"><div class="p-stat-val">3</div><div class="p-stat-lbl">followers</div></div>
    <div style="text-align:center"><div class="p-stat-val">2</div><div class="p-stat-lbl">stars</div></div>
    <div style="text-align:center"><div class="p-stat-val">6</div><div class="p-stat-lbl">following</div></div>
  </div>

  <div class="p-socials">
    <a class="p-social" href="https://linkedin.com/in/dharmdudhagara" target="_blank">LinkedIn ↗</a>
    <a class="p-social" href="https://kaggle.com/dharmdudhagara" target="_blank">Kaggle ↗</a>
    <a class="p-social" href="https://github.com/dharm1123" target="_blank">GitHub ↗</a>
    <a class="p-social" href="mailto:dharmdudhagara11@gmail.com">Email ↗</a>
  </div>
</div>

<button id="toggle" onclick="togglePanel()" title="Menu">
  <span></span><span></span><span></span>
</button>

<div id="badge">DHARM · GALAXY v2<br/>♐ AHMEDABAD · 2025</div>
<div id="hint">CLICK NODE · HOVER TO PREVIEW · SCROLL TO ZOOM</div>

<script>
(function(){
"use strict";

const cv = document.getElementById('cv');
const ctx = cv.getContext('2d');
const PANEL_W = () => window.innerWidth > 700 ? 300 : 0;

const PROJECTS = [
  {
    id:0, name:'GenAI Codes', lbl:'LLM EXPERIMENTS',
    tech:['Python','LLMs','GenAI','API'],
    col:'#c0436e', rf:.30, spd:.50, ph:1.1, sz:8,
    url:'https://github.com/dharm1123/GenAI_codes',
    desc:'Living archive of Generative AI experiments — LLM prompting patterns pushed to breaking point, API integrations stress-tested, prototypes built to answer specific questions.'
  },
  {
    id:1, name:'Resume Ranker', lbl:'GENAI APPLICATION',
    tech:['Azure OpenAI','Streamlit','Python','PDF'],
    col:'#7060cc', rf:.50, spd:.28, ph:3.6, sz:12, stars:1,
    url:'https://github.com/dharm1123/Resume_Ranker_App_GenAI-App',
    desc:'Production Streamlit app using Azure OpenAI to semantically score & rank up to 10 PDF resumes against any job description. Not keyword matching — true LLM reasoning.'
  },
  {
    id:2, name:'Wildlife XAI', lbl:'COMPUTER VISION · XAI',
    tech:['Python','XAI','Jupyter','CV'],
    col:'#1a9068', rf:.66, spd:.19, ph:5.5, sz:10,
    url:'https://github.com/dharm1123/wildlife-species-recognition-xai',
    desc:'Species recognition paired with Explainable AI — because in ecological conservation, why a model decided matters as much as what it decided. Interpretability-first design.'
  },
  {
    id:3, name:'Urban City ML', lbl:'MACHINE LEARNING',
    tech:['Scikit-learn','Random Forest','Pandas','NumPy'],
    col:'#c88818', rf:.82, spd:.13, ph:0.9, sz:14, stars:1,
    url:'https://github.com/dharm1123/Urban-City-Analysis-ML',
    desc:'End-to-end ensemble ML on urban data — predicting crime occurrence, accident severity & passenger counts. Full pipelines, GridSearchCV tuning, stacking classifiers, interactive CLI.'
  },
  {
    id:4, name:'Profile README', lbl:'OPEN SOURCE',
    tech:['Markdown','GitHub Actions'],
    col:'#2875c5', rf:.98, spd:.08, ph:2.8, sz:7,
    url:'https://github.com/dharm1123/dharm1123',
    desc:'The command center — an open-source GitHub profile showcasing Dharm\'s AI/ML projects, constellation portfolio, and creative identity as a data science explorer.'
  }
];

const CONNS = [[0,1],[1,2],[2,3],[0,3],[1,3]];

// Generate background stars
const BG_STARS = Array.from({length:340}, () => ({
  x: Math.random(), y: Math.random(),
  r: Math.random() * 1.4 + .25,
  a: Math.random() * .45 + .06,
  tw: Math.random() * Math.PI * 2,
  speed: Math.random() * .6 + .4
}));

// Nebula clouds (soft colored blobs)
const NEBULAE = [
  {x:.72,y:.28,rx:.22,ry:.14,col:'rgba(60,40,120,0.055)'},
  {x:.25,y:.72,rx:.18,ry:.12,col:'rgba(20,60,120,0.04)'},
  {x:.82,y:.7, rx:.14,ry:.1, col:'rgba(80,30,100,0.04)'},
];

// Shooting stars
const SHOOTS = [];
function spawnShoot(){
  if(SHOOTS.length < 3 && Math.random() < .003){
    const y0 = Math.random() * .5;
    SHOOTS.push({x:Math.random()*.6+.2, y:y0, vx:-.006, vy:.003, life:1, maxLife:1});
  }
}

function rgb(h){
  return[parseInt(h.slice(1,3),16),parseInt(h.slice(3,5),16),parseInt(h.slice(5,7),16)].join(',');
}

let W = 0, H = 0, dpr = 1;
let cx = 0, cy = 0, base = 0;
let t = 0, selId = -1, hovId = -1, mx = -9999, my = -9999;
let zoom = 1, zoomTarget = 1;
let panelOpen = true;

function nodePos(p){
  const a = p.ph + t * p.spd;
  const r = base * p.rf;
  return { x: cx + Math.cos(a)*r, y: cy + Math.sin(a)*r*.6 };
}

function resize(){
  ctx.resetTransform();
  dpr = Math.min(window.devicePixelRatio || 1, 2.5);
  W = window.innerWidth; H = window.innerHeight;
  cv.width = W * dpr; cv.height = H * dpr;
  cv.style.width = W + 'px'; cv.style.height = H + 'px';
  ctx.scale(dpr, dpr);
  const pw = PANEL_W();
  cx = pw + (W - pw) * .52;
  cy = H * .48;
  base = Math.min((W - pw) * .36, H * .3) * zoom;
}

function draw(){
  ctx.clearRect(0, 0, W, H);

  // Deep space background
  ctx.fillStyle = '#020813';
  ctx.fillRect(0, 0, W, H);

  // Nebula blobs
  NEBULAE.forEach(n => {
    ctx.save();
    ctx.translate(n.x * W, n.y * H);
    ctx.scale(1, n.ry/n.rx);
    ctx.beginPath();
    ctx.arc(0, 0, n.rx * W, 0, Math.PI*2);
    ctx.fillStyle = n.col;
    ctx.fill();
    ctx.restore();
  });

  // Grid dots
  const gStep = 38;
  for(let gx = gStep; gx < W; gx += gStep){
    for(let gy = gStep; gy < H; gy += gStep){
      ctx.beginPath(); ctx.arc(gx, gy, .55, 0, Math.PI*2);
      ctx.fillStyle = 'rgba(12,38,100,.16)'; ctx.fill();
    }
  }

  // Background stars
  BG_STARS.forEach(s => {
    const tw = Math.sin(t * s.speed + s.tw) * .2;
    ctx.beginPath(); ctx.arc(s.x*W, s.y*H, s.r, 0, Math.PI*2);
    ctx.fillStyle = `rgba(130,175,255,${s.a + tw})`; ctx.fill();
  });

  // Shooting stars
  spawnShoot();
  for(let i = SHOOTS.length-1; i >= 0; i--){
    const s = SHOOTS[i];
    s.x += s.vx; s.y += s.vy; s.life -= .018;
    if(s.life <= 0){ SHOOTS.splice(i,1); continue; }
    const sx = s.x*W, sy = s.y*H;
    ctx.save();
    ctx.strokeStyle = `rgba(180,210,255,${s.life*.7})`;
    ctx.lineWidth = 1.2;
    ctx.beginPath();
    ctx.moveTo(sx, sy);
    ctx.lineTo(sx - s.vx*W*18, sy - s.vy*H*18);
    ctx.stroke();
    ctx.restore();
  }

  // Scan line
  const sc = (t * 22) % H;
  ctx.fillStyle = 'rgba(8,30,90,.04)';
  ctx.fillRect(0, sc-36, W, 36);
  ctx.beginPath(); ctx.moveTo(0, sc); ctx.lineTo(W, sc);
  ctx.strokeStyle = 'rgba(16,50,140,.055)'; ctx.lineWidth = 1; ctx.stroke();

  // Orbit ellipses
  const pw = PANEL_W();
  PROJECTS.forEach(p => {
    const r = base * p.rf;
    const act = hovId===p.id || selId===p.id;
    ctx.save(); ctx.translate(cx, cy); ctx.scale(1,.6);
    ctx.beginPath(); ctx.arc(0, 0, r, 0, Math.PI*2);
    ctx.strokeStyle = `rgba(${rgb(p.col)},${act?.30:.08})`;
    ctx.lineWidth = act ? .8 : .35;
    ctx.setLineDash([4, 10]); ctx.stroke(); ctx.setLineDash([]);
    ctx.restore();
  });

  // Connection beams (on hover/select)
  const aid = selId >= 0 ? selId : hovId;
  CONNS.forEach(([a,b]) => {
    if(hovId !== a && hovId !== b && selId !== a && selId !== b) return;
    const pa = nodePos(PROJECTS[a]), pb = nodePos(PROJECTS[b]);
    ctx.beginPath(); ctx.moveTo(pa.x, pa.y); ctx.lineTo(pb.x, pb.y);
    ctx.strokeStyle = `rgba(50,100,220,.22)`;
    ctx.lineWidth = .6; ctx.setLineDash([2,8]); ctx.stroke(); ctx.setLineDash([]);
  });

  // Active beam + data flow dots
  if(aid >= 0){
    const p = PROJECTS[aid], pos = nodePos(p);
    ctx.beginPath(); ctx.moveTo(cx, cy); ctx.lineTo(pos.x, pos.y);
    ctx.strokeStyle = `rgba(${rgb(p.col)},.38)`; ctx.lineWidth = .9;
    ctx.setLineDash([2,7]); ctx.stroke(); ctx.setLineDash([]);
    for(let i = 0; i < 4; i++){
      const f = ((t*.75 + i*.25) % 1);
      ctx.beginPath();
      ctx.arc(cx+(pos.x-cx)*f, cy+(pos.y-cy)*f, 1.8, 0, Math.PI*2);
      ctx.fillStyle = `rgba(${rgb(p.col)},${.9-f*.6})`; ctx.fill();
    }
  }

  // Ripple rings from center
  for(let i = 0; i < 5; i++){
    const ph = ((t*.18 + i*.2) % 1), pr = ph * 62;
    ctx.beginPath(); ctx.arc(cx, cy, pr, 0, Math.PI*2);
    ctx.strokeStyle = `rgba(40,95,220,${(1-ph)*.18})`;
    ctx.lineWidth = .7; ctx.stroke();
  }

  // Project nodes
  PROJECTS.forEach(p => {
    const pos = nodePos(p);
    const isH = hovId===p.id, isS = selId===p.id, act = isH||isS;

    // Comet trail
    for(let tr = 1; tr <= 7; tr++){
      const ta = p.ph + (t - tr*.04)*p.spd;
      const tx = cx + Math.cos(ta)*base*p.rf;
      const ty = cy + Math.sin(ta)*base*p.rf*.6;
      ctx.beginPath(); ctx.arc(tx, ty, p.sz*(1 - tr*.13), 0, Math.PI*2);
      ctx.fillStyle = `rgba(${rgb(p.col)},${.10 - tr*.013})`; ctx.fill();
    }

    // Glow halo
    if(act){
      for(let g = 5; g >= 1; g--){
        ctx.beginPath(); ctx.arc(pos.x, pos.y, p.sz + g*5, 0, Math.PI*2);
        ctx.fillStyle = `rgba(${rgb(p.col)},${.045*g})`; ctx.fill();
      }
    }

    // Node body
    ctx.beginPath(); ctx.arc(pos.x, pos.y, p.sz, 0, Math.PI*2);
    ctx.fillStyle = p.col; ctx.fill();
    ctx.strokeStyle = `rgba(255,255,255,${act?.55:.18})`;
    ctx.lineWidth = act ? 1.4 : .8; ctx.stroke();

    // Inner highlight
    ctx.beginPath(); ctx.arc(pos.x - p.sz*.28, pos.y - p.sz*.28, p.sz*.28, 0, Math.PI*2);
    ctx.fillStyle = `rgba(255,255,255,${act?.18:.07})`; ctx.fill();

    // Star badge
    if(p.stars){
      ctx.beginPath(); ctx.arc(pos.x + p.sz*.75, pos.y - p.sz*.75, 2.5, 0, Math.PI*2);
      ctx.fillStyle = '#eea030'; ctx.fill();
    }

    // Labels
    const ly = pos.y + p.sz + 14;
    ctx.textAlign = 'center'; ctx.textBaseline = 'top';
    ctx.font = `${act?'600':'400'} 11px monospace`;
    ctx.fillStyle = act ? '#8ec0e0' : '#2a506a';
    ctx.fillText(p.name, pos.x, ly);
    if(act){
      ctx.font = '400 10px monospace';
      ctx.fillStyle = p.col;
      ctx.fillText(p.lbl, pos.x, ly+15);
    }
  });

  // Center hub — dual rotating rings
  ctx.save(); ctx.translate(cx,cy); ctx.rotate(t*.25);
  ctx.beginPath(); ctx.arc(0,0,34,0,Math.PI*2);
  ctx.strokeStyle='rgba(28,78,180,.35)'; ctx.lineWidth=.8; ctx.setLineDash([2,8]); ctx.stroke(); ctx.setLineDash([]);
  ctx.restore();
  ctx.save(); ctx.translate(cx,cy); ctx.rotate(-t*.12);
  ctx.beginPath(); ctx.arc(0,0,44,0,Math.PI*2);
  ctx.strokeStyle='rgba(18,55,140,.18)'; ctx.lineWidth=.5; ctx.setLineDash([1,12]); ctx.stroke(); ctx.setLineDash([]);
  ctx.restore();

  // Hub disk
  ctx.beginPath(); ctx.arc(cx,cy,26,0,Math.PI*2);
  ctx.fillStyle='rgba(1,8,24,.92)'; ctx.fill();
  ctx.strokeStyle='rgba(48,110,210,.55)'; ctx.lineWidth=1.4; ctx.stroke();

  // Hub pulse dot
  const pulse = .4 + Math.sin(t*2.6)*.38;
  ctx.beginPath(); ctx.arc(cx,cy,5.5,0,Math.PI*2);
  ctx.fillStyle=`rgba(65,140,255,${pulse})`; ctx.fill();

  // Hub initials
  ctx.font='600 12px monospace'; ctx.textAlign='center'; ctx.textBaseline='middle';
  ctx.fillStyle=`rgba(90,160,240,${.6+pulse*.28})`;
  ctx.fillText('DD', cx, cy+.5);

  // Floating tech labels (inner ring)
  const IR = base * .24;
  ['Python','ML','GenAI','XAI','Data'].forEach((lbl,i) => {
    const a = t*.08 + (i/5)*Math.PI*2;
    ctx.font='400 10px monospace'; ctx.textAlign='center'; ctx.textBaseline='middle';
    ctx.fillStyle=`rgba(18,58,138,${.28+Math.sin(a+t*.45)*.1})`;
    ctx.fillText(lbl, cx+Math.cos(a)*IR, cy+Math.sin(a)*IR*.6);
  });

  // Sagittarius archer arrow (decorative)
  const ax = cx + base*.15, ay = cy - base*.35;
  ctx.save(); ctx.translate(ax, ay); ctx.rotate(-.55);
  ctx.strokeStyle='rgba(200,130,20,.15)'; ctx.lineWidth=1;
  ctx.beginPath(); ctx.moveTo(-22,0); ctx.lineTo(22,0); ctx.stroke();
  // arrowhead
  ctx.beginPath(); ctx.moveTo(18,-5); ctx.lineTo(24,0); ctx.lineTo(18,5);
  ctx.strokeStyle='rgba(200,130,20,.22)'; ctx.stroke();
  // fletching
  ctx.beginPath(); ctx.moveTo(-22,0); ctx.lineTo(-16,-4);
  ctx.moveTo(-22,0); ctx.lineTo(-16,4);
  ctx.strokeStyle='rgba(200,130,20,.14)'; ctx.stroke();
  ctx.restore();
}

function selectProj(id){
  selId = id;
  const p = PROJECTS[id];
  document.getElementById('p-default').style.display='none';
  document.getElementById('p-detail').style.display='flex';
  document.getElementById('p-bar').style.background = p.col;
  document.getElementById('p-lbl').style.color = p.col;
  document.getElementById('p-lbl').textContent = p.lbl;
  document.getElementById('p-name').textContent = p.name;
  document.getElementById('p-desc').textContent = p.desc;
  const te = document.getElementById('p-tech'); te.innerHTML='';
  p.tech.forEach(tk => {
    const s = document.createElement('span'); s.textContent = tk;
    s.style.cssText = `font-size:10px;padding:2px 8px;border:1px solid rgba(${rgb(p.col)},.3);border-radius:3px;color:${p.col};letter-spacing:.04em;font-family:monospace;`;
    te.appendChild(s);
  });
  document.getElementById('p-link').href = p.url;
  document.getElementById('p-link').style.color = p.col;
  document.getElementById('p-link').style.borderColor = `rgba(${rgb(p.col)},.3)`;
}

document.getElementById('p-back').addEventListener('click',()=>{
  selId = -1;
  document.getElementById('p-default').style.display='flex';
  document.getElementById('p-detail').style.display='none';
});

function loop(){
  requestAnimationFrame(loop);
  t += .011;
  zoomTarget = Math.max(.6, Math.min(1.6, zoomTarget));
  zoom += (zoomTarget - zoom) * .06;

  const prev = hovId; hovId = -1;
  PROJECTS.forEach(p => {
    const pos = nodePos(p);
    if(Math.sqrt((mx-pos.x)**2+(my-pos.y)**2) < p.sz+12) hovId = p.id;
  });
  if(hovId !== prev) cv.style.cursor = hovId >= 0 ? 'pointer' : 'default';

  base = Math.min((W - PANEL_W()) * .36, H * .3) * zoom;
  draw();
}

// Events
cv.addEventListener('mousemove', e => { mx = e.clientX; my = e.clientY; });
cv.addEventListener('mouseleave', () => { mx=-9999; my=-9999; });
cv.addEventListener('click', () => { if(hovId >= 0) selectProj(hovId); });
cv.addEventListener('wheel', e => { zoomTarget -= e.deltaY * .0008; e.preventDefault(); },{passive:false});

cv.addEventListener('touchstart', e => {
  const t0 = e.touches[0];
  mx = t0.clientX; my = t0.clientY;
}, {passive:true});
cv.addEventListener('touchmove', e => {
  const t0 = e.touches[0];
  mx = t0.clientX; my = t0.clientY;
}, {passive:true});
cv.addEventListener('touchend', e => {
  PROJECTS.forEach(p => {
    const pos = nodePos(p);
    if(Math.sqrt((mx-pos.x)**2+(my-pos.y)**2) < p.sz+18) selectProj(p.id);
  });
  mx=-9999; my=-9999;
}, {passive:true});

// Panel toggle for mobile
window.togglePanel = function(){
  panelOpen = !panelOpen;
  document.getElementById('panel').classList.toggle('hidden', !panelOpen);
};

window.addEventListener('resize', resize);
resize(); loop();

// Fade out hint after 5s
setTimeout(()=>{
  const h=document.getElementById('hint');
  if(h) h.style.opacity='0';
},5000);

})();
</script>
</body>
</html>
