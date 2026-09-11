<!doctype html>
<html lang="pt-BR">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width,initial-scale=1,maximum-scale=1,user-scalable=no">
<!-- PWA CONFIG -->
<link rel="manifest" href="manifest.json">
<meta name="theme-color" content="#a855f7">
<title>Moto Manager • V4.1</title>
<style>
*{box-sizing:border-box;margin:0;padding:0;-webkit-tap-highlight-color:transparent}
:root{--accent:#a855f7;--accent2:#6d28d9;--glow:#c084fc;--bg:#050507;--card:#0d0d13;--line:#292331;--text:#f5f3f7;--muted:#9991a3;--ok:#67e8a5;--warn:#fbbf24;--danger:#ef4444}
html,body{height:100%;overflow:hidden}
body{background:radial-gradient(ellipse at top,#1a0f2e 0%,#0b0910 40%,#050507 100%);color:var(--text);font-family:system-ui,-apple-system,sans-serif;font-size:14px}
.app{display:flex;flex-direction:column;height:100vh;max-width:480px;margin:0 auto;position:relative}
.header{padding:12px 16px 8px;border-bottom:1px solid var(--line);background:#0a0a0fcc;backdrop-filter:blur(10px)}
.header-top{display:flex;justify-content:space-between;align-items:center}
.logo{display:flex;align-items:center;gap:8px}
.logo-icon{width:28px;height:28px;background:linear-gradient(135deg,var(--accent),var(--accent2));border-radius:8px;display:flex;align-items:center;justify-content:center;font-weight:900;font-size:16px}
.logo-text{font-size:13px;font-weight:800;letter-spacing:.5px}
.logo-sub{font-size:9px;color:var(--muted);letter-spacing:1px}
.main{flex:1;overflow-y:auto;overflow-x:hidden;padding-bottom:80px}
.main::-webkit-scrollbar{width:0}
.stage{position:relative;height:260px;margin:12px;border-radius:20px;background:radial-gradient(ellipse at center,#1f1230 0%,#0d0a14 50%,#050507 100%);border:1px solid #2a1f3a;overflow:hidden}
.stage-floor{position:absolute;bottom:40px;left:12%;right:12%;height:1px;background:linear-gradient(90deg,transparent,var(--accent),transparent);box-shadow:0 0 20px var(--accent);opacity:.6}
.bike{position:absolute;left:50%;top:50%;transform:translate(-50%,-50%);width:85%;height:180px;filter:drop-shadow(0 0 15px var(--glow))}
.wheel{position:absolute;width:72px;height:72px;border:6px solid #1a1a22;border-radius:50%;background:radial-gradient(circle,#444 0 8%,#1a1a22 9% 30%,#666 31% 34%,#121218 35%);bottom:5px}
.wheel-rear{left:2%}.wheel-front{right:2%}
.bike-body{position:absolute;left:22%;top:55px;width:55%;height:50px;background:linear-gradient(135deg,var(--accent) 0%,#1a0f2e 50%,var(--accent2) 100%);clip-path:polygon(5% 40%,20% 10%,65% 5%,95% 50%,80% 95%,10% 88%);border:1px solid var(--glow)}
.bike-tank{position:absolute;left:38%;top:25px;width:26%;height:45px;background:linear-gradient(145deg,var(--glow),var(--accent2));border-radius:50% 45% 35% 45%;transform:rotate(-8deg)}
.bike-seat{position:absolute;left:28%;top:22px;width:24%;height:18px;background:#0a0a0f;border-radius:14px 6px 6px 10px}
.bike-handle{position:absolute;right:10%;top:20px;width:14%;height:5px;background:#aaa;border-radius:8px;transform:rotate(-15deg)}
.bike-exhaust{position:absolute;left:40%;bottom:25px;width:22%;height:6px;background:linear-gradient(90deg,#666,#999);border-radius:6px;transform:rotate(8deg)}
.bike-head{position:absolute;right:13%;top:40px;width:20px;height:20px;border-radius:6px;background:#fff;box-shadow:0 0 20px var(--glow),0 0 40px var(--accent)}
.hotspot{position:absolute;width:36px;height:36px;border-radius:50%;border:2px solid var(--glow);background:rgba(168,85,247,.2);backdrop-filter:blur(8px);display:flex;align-items:center;justify-content:center;font-size:14px;cursor:pointer;z-index:5;transition:transform .2s}
.hotspot:active{transform:scale(.9)}
.hs-tank{left:45%;top:60px}.hs-front{right:8%;top:95px}.hs-engine{left:48%;top:120px}.hs-wheel{right:10%;bottom:25px}.hs-rear{left:8%;bottom:25px}.hs-seat{left:30%;top:50px}
.section{padding:14px 16px}
.section-title{font-size:11px;font-weight:800;letter-spacing:1.5px;color:var(--glow);margin-bottom:10px;text-transform:uppercase}
.info-card{background:var(--card);border:1px solid var(--line);border-radius:16px;padding:14px;margin-bottom:10px}
.info-row{display:flex;justify-content:space-between;align-items:center;padding:8px 0;border-bottom:1px solid #1a1525}
.info-row:last-child{border-bottom:0}
.info-label{font-size:12px;color:var(--muted)}.info-value{font-size:14px;font-weight:700}.info-value.big{font-size:20px;color:var(--glow)}
.status-item{display:flex;align-items:center;gap:10px;padding:10px 0;border-bottom:1px solid #1a1525}
.status-item:last-child{border-bottom:0}
.status-icon{width:28px;height:28px;border-radius:8px;display:flex;align-items:center;justify-content:center;font-size:14px;flex-shrink:0}
.status-icon.ok{background:rgba(103,232,165,.15);color:var(--ok)}.status-icon.warn{background:rgba(251,191,36,.15);color:var(--warn)}.status-icon.danger{background:rgba(239,68,68,.15);color:var(--danger)}
.status-info{flex:1}.status-name{font-size:13px;font-weight:600}
.status-bar{height:4px;background:#1a1525;border-radius:2px;margin-top:4px;overflow:hidden}
.status-fill{height:100%;border-radius:2px}.status-fill.ok{background:var(--ok)}.status-fill.warn{background:var(--warn)}.status-fill.danger{background:var(--danger)}
.status-text{font-size:11px;font-weight:700;flex-shrink:0}.status-text.ok{color:var(--ok)}.status-text.warn{color:var(--warn)}.status-text.danger{color:var(--danger)}
.maint-item{background:var(--card);border:1px solid var(--line);border-radius:14px;padding:12px;margin-bottom:8px;display:flex;justify-content:space-between;align-items:center}
.maint-info{flex:1}.maint-name{font-size:13px;font-weight:700}.maint-meta{font-size:11px;color:var(--muted);margin-top:2px}.maint-km{font-size:11px;color:var(--glow);font-weight:700}
.parts-item{background:var(--card);border:1px solid var(--line);border-radius:14px;padding:12px;margin-bottom:8px}
.parts-item h4{margin:0 0 6px 0;font-size:14px;color:var(--glow);font-weight:700}
.color-grid{display:grid;grid-template-columns:repeat(5,1fr);gap:8px}
.color-btn{height:40px;border-radius:12px;border:2px solid transparent;cursor:pointer;transition:transform .2s}
.color-btn:active{transform:scale(.95)}.color-btn.active{border-color:#fff;box-shadow:0 0 15px var(--glow)}
.bottom-nav{position:fixed;bottom:0;left:50%;transform:translateX(-50%);width:100%;max-width:480px;display:grid;grid-template-columns:repeat(5,1fr);background:#0a0a0fee;backdrop-filter:blur(15px);border-top:1px solid var(--line);padding:8px 4px 12px;z-index:100}
.nav-btn{border:0;background:none;color:var(--muted);font-size:10px;cursor:pointer;display:flex;flex-direction:column;align-items:center;gap:3px;padding:4px}
.nav-btn b{font-size:18px;font-weight:400}.nav-btn.active{color:var(--glow)}.nav-btn.active b{filter:drop-shadow(0 0 8px var(--accent))}
.modal{position:fixed;inset:0;background:rgba(0,0,0,.85);backdrop-filter:blur(5px);display:none;align-items:flex-end;justify-content:center;z-index:200}
.modal.show{display:flex}
.modal-sheet{width:100%;max-width:480px;background:#0d0d13;border:1px solid var(--line);border-radius:24px 24px 0 0;padding:20px;max-height:70vh;overflow-y:auto}
.modal-header{display:flex;justify-content:space-between;align-items:center;margin-bottom:16px}
.modal-title{font-size:18px;font-weight:800}.modal-close{width:32px;height:32px;border-radius:10px;background:#1a1525;border:1px solid var(--line);color:var(--text);font-size:16px;cursor:pointer}
.modal-body{display:grid;gap:10px}
.modal-item{padding:12px;background:var(--card);border:1px solid var(--line);border-radius:12px;font-size:13px}
.modal-item h4{margin:0 0 4px 0;font-size:14px;color:var(--glow)}
.toast{position:fixed;top:60px;left:50%;transform:translateX(-50%);background:var(--accent);color:#fff;padding:10px 20px;border-radius:12px;font-weight:700;font-size:13px;z-index:300;display:none;box-shadow:0 4px 20px rgba(168,85,247,.4)}
.toast.show{display:block;animation:slideDown .3s}
@keyframes slideDown{from{opacity:0;transform:translateX(-50%) translateY(-20px)}to{opacity:1;transform:translateX(-50%) translateY(0)}}
.form-group{margin-bottom:12px}
.form-label{display:block;font-size:11px;color:var(--muted);margin-bottom:6px;font-weight:600;letter-spacing:.5px}
.form-input,.form-select{width:100%;background:#0a0a0f;border:1px solid var(--line);border-radius:10px;padding:12px;color:var(--text);font-size:14px;outline:none}
.btn{width:100%;background:linear-gradient(135deg,var(--accent),var(--accent2));color:#fff;border:0;border-radius:12px;padding:14px;font-weight:700;font-size:14px;cursor:pointer;margin-top:8px}
.btn-secondary{background:var(--card);border:1px solid var(--line)}.btn-sm{padding:6px 10px;font-size:11px;width:auto;border-radius:8px;margin-left:4px}
.chart-container{display:flex;align-items:flex-end;gap:8px;height:120px;padding:10px 0;margin-bottom:10px}
.chart-bar-wrapper{flex:1;display:flex;flex-direction:column;align-items:center;gap:4px;height:100%}
.chart-bar{width:100%;border-radius:6px 6px 0 0;background:var(--accent);transition:height .5s ease;min-height:2px}
.chart-label{font-size:9px;color:var(--muted);text-align:center;word-break:break-word;line-height:1.1}
.chart-value{font-size:10px;font-weight:700;color:var(--text)}
.saved-bike-item{display:flex;justify-content:space-between;align-items:center;padding:12px;background:var(--card);border:1px solid var(--line);border-radius:12px;margin-bottom:8px}
.saved-bike-info{flex:1;cursor:pointer}.saved-bike-name{font-size:14px;font-weight:700}.saved-bike-meta{font-size:11px;color:var(--muted)}
.saved-bike-actions{display:flex;gap:4px}
.photo-preview{width:60px;height:60px;border-radius:8px;object-fit:cover;border:1px solid var(--line);margin-top:6px}
.timeline{position:relative;padding-left:20px;border-left:2px solid var(--line);margin:10px 0}
.timeline-item{position:relative;padding-bottom:16px}
.timeline-item::before{content:'';position:absolute;left:-25px;top:4px;width:10px;height:10px;border-radius:50%;background:var(--accent);border:2px solid var(--bg)}
.timeline-km{font-size:11px;color:var(--glow);font-weight:700}
.timeline-date{font-size:10px;color:var(--muted)}
</style>
</head>
<body>
<div class="app">
  <div class="header">
    <div class="header-top">
      <div class="logo"><div class="logo-icon">M</div><div><div class="logo-text">MOTO MANAGER</div><div class="logo-sub">V4.1 • TEMA ESCURO</div></div></div>
    </div>
  </div>
  <div class="main" id="mainContent"></div>
  <nav class="bottom-nav">
    <button class="nav-btn active" onclick="showPage('home')" id="nav-home"><b>🏠</b>Início</button>
    <button class="nav-btn" onclick="showPage('maint')" id="nav-maint"><b>🔧</b>Manutenção</button>
    <button class="nav-btn" onclick="showPage('expenses')" id="nav-expenses"><b>💰</b>Gastos</button>
    <button class="nav-btn" onclick="showPage('parts')" id="nav-parts"><b>🛠️</b>Peças</button>
    <button class="nav-btn" onclick="showPage('bike')" id="nav-bike"><b>🏍️</b>Motos</button>
  </nav>
</div>
<div class="modal" id="modal"><div class="modal-sheet"><div class="modal-header"><div class="modal-title" id="modalTitle">Peças</div><button class="modal-close" onclick="closeModal()">✕</button></div><div class="modal-body" id="modalBody"></div></div></div>
<div class="toast" id="toast"></div>

<script>
// ===== CATÁLOGO DE MOTOS =====
const BIKE_CATALOG = {
  'Yamaha': ['Factor 125','Factor 150','YBR 125','YBR 150','Crosser 125','Crosser 150','Fazer 150','Fazer 250','XTZ 125','Lander 250','MT-03','R3'],
  'Honda': ['CG 99','CG 125 Fan','CG 125 KS','CG 160','Biz 125','Pop 110i','Elite 125','PCX 150','CB 250F Twister','CB 300F','Bros 160','XRE 190','XRE 300'],
  'Suzuki': ['Yes 125','Intruder 125','GS 500','GSX-S150','Burgman 125'],
  'Kawasaki': ['Ninja 250','Ninja 300','Ninja 400','Z250','Z300','Z400','Versys-X 300']
};

// ===== GUIA TÉCNICO COMPLETO =====
const PARTS_GUIDE = {
  'Honda CG 99': {
    Motor: [{name:'Vela NGK D8EA',compat:'CG 125 Titan/KS/Fan (1999-2004)',price:'R$ 12–18',type:'Original'},{name:'Óleo 20W50 Mineral API SF',compat:'CG 125 Carburada',price:'R$ 25–35',type:'Original'},{name:'Kit Reparo Carburador PZ27',compat:'CG 125 Titan/KS',price:'R$ 35–60',type:'Compatível'}],
    Tanque: [{name:'Tampa Tanque Cromada',compat:'CG 125 Titan/KS/Fan',price:'R$ 35–55',type:'Compatível'}],
    Frente: [{name:'Lâmpada Halógena H6 35/35W',compat:'CG 125 Titan/Fan/KS',price:'R$ 15–25',type:'Original'},{name:'Guidão Original Cromado',compat:'CG 125 (1999-2008)',price:'R$ 70–110',type:'Compatível'}],
    Rodas: [{name:'Pneu 80/100-18 Dianteiro',compat:'CG 125/Titan/Bros',price:'R$ 150–210',type:'Compatível'},{name:'Lonas de Freio Tambor',compat:'CG 125 (1999-2008)',price:'R$ 25–40',type:'Compatível'}],
    Traseira: [{name:'Kit Relação 428 (14x42)',compat:'CG 125 Titan/KS/Fan',price:'R$ 70–110',type:'Original'}]
  },
  'Yamaha Factor 125': {
    Motor: [{name:'Vela NGK CR7E',compat:'Factor/YBR/Crosser 125',price:'R$ 12–18',type:'Compatível'},{name:'Óleo Yamalube 10W40',compat:'Todas Yamaha 125cc',price:'R$ 35–50',type:'Original'}],
    Tanque: [{name:'Capa Tanque PVC',compat:'Factor/YBR 125',price:'R$ 50–80',type:'Compatível'}],
    Frente: [{name:'LED H6 35W',compat:'Universal 12V',price:'R$ 25–45',type:'Compatível'},{name:'Painel Digital',compat:'Factor 125 (2010+)',price:'R$ 250–380',type:'Original'}],
    Rodas: [{name:'Pneu 80/100-17',compat:'Factor/CG/Titan',price:'R$ 160–220',type:'Compatível'}],
    Traseira: [{name:'Kit Relação 420',compat:'Factor/YBR/Crosser',price:'R$ 90–130',type:'Original'}]
  },
  'Honda CG 160': {
    Motor: [{name:'Vela NGK BPR6ES',compat:'CG 160/150/125/Biz',price:'R$ 10–15',type:'Compatível'},{name:'Óleo Honda 20W50',compat:'CG/Titan/Bros',price:'R$ 28–40',type:'Original'}],
    Frente: [{name:'LED H6 Bifoco',compat:'CG 160/125',price:'R$ 25–40',type:'Compatível'}],
    Rodas: [{name:'Pneu 80/100-18',compat:'CG/Titan/Bros',price:'R$ 150–210',type:'Compatível'}],
    Traseira: [{name:'Kit Relação 428',compat:'CG 160/150/125',price:'R$ 80–120',type:'Original'}]
  }
};

// ===== ESTADO GLOBAL =====
const KEY = 'motoManagerV4_1';
let db = JSON.parse(localStorage.getItem(KEY)) || { 
  currentBikeId: null, 
  motos: {},
  workshops: [],
  oilConfig: { intervalDays: 90, intervalKm: 3000, lastDate: '', lastKm: 0 }
};

function getBikeId(b,m,y){return `${b}-${m}-${y}`.replace(/\s+/g,'-').toLowerCase()}
function getCurrentBike(){
  if(!db.currentBikeId||!db.motos[db.currentBikeId]){
    const id=getBikeId('Yamaha','Factor 125','2012');
    if(!db.motos[id]) db.motos[id]={brand:'Yamaha',model:'Factor 125',year:'2012',km:'42350',color:'purple',theme:'system',plate:'',maint:[],expenses:[],status:{motor:95,pneus:75,freios:70,relacao:40}};
    db.currentBikeId=id;save();
  }
  return db.motos[db.currentBikeId];
}
function save(){localStorage.setItem(KEY,JSON.stringify(db));applyTheme()}
function applyTheme(){
  const b=getCurrentBike(),p={purple:['#a855f7','#6d28d9','#c084fc'],blue:['#2563eb','#1d4ed8','#93c5fd'],red:['#ef4444','#991b1b','#fca5a5'],black:['#64748b','#1e293b','#cbd5e1'],white:['#e5e7eb','#6b7280','#fff'],green:['#22c55e','#15803d','#86efac']}[b.color]||['#a855f7','#6d28d9','#c084fc'];
  document.documentElement.style.setProperty('--accent',p[0]);document.documentElement.style.setProperty('--accent2',p[1]);document.documentElement.style.setProperty('--glow',p[2]);
}
function toast(m){const t=document.getElementById('toast');t.textContent=m;t.classList.add('show');setTimeout(()=>t.classList.remove('show'),2000)}

function showPage(id){
  document.querySelectorAll('.nav-btn').forEach(b=>b.classList.remove('active'));
  document.getElementById('nav-'+id).classList.add('active');
  const m=document.getElementById('mainContent');
  ({home:renderHome,maint:renderMaint,expenses:renderExpenses,parts:renderPartsCatalog,bike:renderBikeConfig})[id]?.(m);
  m.scrollTop=0;
}

// ===== HOME SEM CHECKLIST + ALERTAS + CONSUMO =====
function renderHome(el){
  const b=getCurrentBike(),te=b.expenses.reduce((s,x)=>s+Number(x.value||0),0);
  
  // Calcular consumo médio
  const fuelExpenses = b.expenses.filter(e => e.category === 'Combustível' && e.km);
  let consumptionHtml = '';
  if(fuelExpenses.length >= 2){
    const sorted = fuelExpenses.sort((a,b) => Number(a.km) - Number(b.km));
    const last = sorted[sorted.length-1];
    const prev = sorted[sorted.length-2];
    const kmDiff = Number(last.km) - Number(prev.km);
    const liters = Number(last.value) / 5.5; 
    const kmL = (kmDiff / liters).toFixed(1);
    consumptionHtml = `<div class="info-row"><span class="info-label">Consumo Médio</span><span class="info-value big">${kmL} km/L</span></div>`;
  }

  // Alerta de óleo
  let oilAlert = '';
  if(db.oilConfig.lastDate){
    const last = new Date(db.oilConfig.lastDate);
    const next = new Date(last);
    next.setDate(next.getDate() + db.oilConfig.intervalDays);
    const today = new Date();
    const daysLeft = Math.ceil((next - today)/(1000*60*60*24));
    const kmLeft = (db.oilConfig.lastKm + db.oilConfig.intervalKm) - Number(b.km);
    
    if(daysLeft <= 7 || kmLeft <= 200){
      oilAlert = `<div class="info-card" style="border-color:var(--danger)">
        <div class="info-row"><span class="info-label" style="color:var(--danger)">⚠ TROCA DE ÓLEO</span><span class="info-value" style="color:var(--danger)">${daysLeft <= 0 ? 'ATRASADA' : daysLeft + ' dias'}</span></div>
        <div class="info-row"><span class="info-label">Ou em</span><span class="info-value">${kmLeft} km</span></div>
      </div>`;
    }
  }

  el.innerHTML=`
    <div class="stage"><div class="bike"><div class="wheel wheel-rear"></div><div class="wheel wheel-front"></div><div class="bike-body"></div><div class="bike-tank"></div><div class="bike-seat"></div><div class="bike-handle"></div><div class="bike-exhaust"></div><div class="bike-head"></div></div>
      <div class="hotspot hs-tank" onclick="openParts('Tanque')">⛽</div><div class="hotspot hs-front" onclick="openParts('Frente')">💡</div><div class="hotspot hs-engine" onclick="openParts('Motor')">⚙</div><div class="hotspot hs-wheel" onclick="openParts('Rodas')">🛞</div><div class="hotspot hs-rear" onclick="openParts('Traseira')">🔧</div><div class="hotspot hs-seat" onclick="openParts('Assento')">💺</div>
    </div>
    <div class="section">
      ${oilAlert}
      <div class="section-title">Informações</div>
      <div class="info-card">
        <div class="info-row"><span class="info-label">Placa</span><span class="info-value">${b.plate||'—'}</span></div>
        <div class="info-row"><span class="info-label">KM Atual</span><span class="info-value big">${Number(b.km||0).toLocaleString()} km</span></div>
        ${consumptionHtml}
      </div>

      <div class="section-title">Status Geral</div>
      <div class="info-card">${['Motor','Pneus','Freios','Relação'].map((n,i)=>{const k=['motor','pneus','freios','relacao'][i],v=b.status[k],s=v>70?'ok':v>40?'warn':'danger';return `<div class="status-item"><div class="status-icon ${s}">●</div><div class="status-info"><div class="status-name">${n}</div><div class="status-bar"><div class="status-fill ${s}" style="width:${v}%"></div></div></div><div class="status-text ${s}">${v>70?'Excelente':v>40?'Bom':'Atenção'}</div></div>`}).join('')}</div>
    </div>`;
}

// ===== MANUTENÇÃO COM TIMELINE + FOTO =====
function renderMaint(el){
  const b=getCurrentBike();
  el.innerHTML=`<div class="section"><div class="section-title">Registrar Manutenção</div><div class="info-card"><div class="form-group"><label class="form-label">Serviço</label><input class="form-input" id="mName"></div><div class="form-group"><label class="form-label">Data</label><input class="form-input" type="date" id="mDate"></div><div class="form-group"><label class="form-label">KM</label><input class="form-input" type="number" id="mKm"></div><div class="form-group"><label class="form-label">Próxima (km)</label><input class="form-input" type="number" id="mNext"></div><div class="form-group"><label class="form-label">Foto (opcional)</label><input class="form-input" type="file" accept="image/*" id="mPhoto"></div><button class="btn" onclick="addMaint()">Adicionar</button></div><div class="section-title">Histórico (Timeline)</div><div class="timeline">${b.maint.slice().reverse().map((m,i)=>`<div class="timeline-item"><div class="maint-name">${m.name}</div><div class="timeline-km">${Number(m.km).toLocaleString()} km</div><div class="timeline-date">${m.date}</div>${m.photo?`<img src="${m.photo}" class="photo-preview">`:''}<button class="btn btn-secondary btn-sm" style="margin-top:6px;color:var(--danger)" onclick="removeMaint(${b.maint.length-1-i})">Excluir</button></div>`).join('')||'<div style="padding:16px;text-align:center;color:var(--muted)">Vazio.</div>'}</div></div>`;
}
function addMaint(){
  const b=getCurrentBike(),n=document.getElementById('mName').value,k=document.getElementById('mKm').value;
  if(n&&k){
    const fileInput = document.getElementById('mPhoto');
    const reader = new FileReader();
    const maintData = {name:n,date:document.getElementById('mDate').value,km:k,next:document.getElementById('mNext').value,photo:null};
    
    if(fileInput.files && fileInput.files[0]){
      reader.onload = function(e){
        maintData.photo = e.target.result;
        b.maint.push(maintData);
        save();toast('Salvo!');showPage('maint');
      };
      reader.readAsDataURL(fileInput.files[0]);
    } else {
      b.maint.push(maintData);
      save();toast('Salvo!');showPage('maint');
    }
  } else toast('Preencha serviço e KM');
}
function removeMaint(i){getCurrentBike().maint.splice(i,1);save();showPage('maint')}

// ===== GASTOS COM GRÁFICO COMPARATIVO + FOTO =====
function renderExpenses(el){
  const b=getCurrentBike(),total=b.expenses.reduce((s,x)=>s+Number(x.value||0),0);
  const cats={};b.expenses.forEach(e=>{const c=e.category||'Outros';cats[c]=(cats[c]||0)+Number(e.value||0)});
  const max=Math.max(...Object.values(cats),1);
  const colors={'Combustível':'#a855f7','Manutenção':'#22c55e','Peças':'#2563eb','Acessórios':'#fbbf24','Lavagem':'#ec4899','Documentação':'#64748b','Outros':'#9991a3'};
  let chart='';Object.entries(cats).forEach(([c,v])=>{chart+=`<div class="chart-bar-wrapper"><div class="chart-value">R$${v.toFixed(0)}</div><div class="chart-bar" style="height:${Math.max(v/max*100,5)}%;background:${colors[c]||'#a855f7'}"></div><div class="chart-label">${c.substring(0,6)}</div></div>`});
  
  // Comparativo mensal
  const now = new Date();
  const thisMonth = b.expenses.filter(e=>e.date&&e.date.startsWith(now.toISOString().slice(0,7))).reduce((s,x)=>s+Number(x.value||0),0);
  const lastMonth = new Date(now.getFullYear(),now.getMonth()-1,1).toISOString().slice(0,7);
  const prevTotal = b.expenses.filter(e=>e.date&&e.date.startsWith(lastMonth)).reduce((s,x)=>s+Number(x.value||0),0);
  const compMax = Math.max(thisMonth,prevTotal,1);
  
  el.innerHTML=`<div class="section"><div class="info-card"><div class="info-row"><span class="info-label">Total</span><span class="info-value big">R$ ${total.toFixed(2).replace('.',',')}</span></div></div>
    ${Object.keys(cats).length?`<div class="section-title">Por Categoria</div><div class="info-card"><div class="chart-container">${chart}</div></div>`:''}
    <div class="section-title">Comparativo Mensal</div>
    <div class="info-card"><div class="chart-container">
      <div class="chart-bar-wrapper"><div class="chart-value">R$${prevTotal.toFixed(0)}</div><div class="chart-bar" style="height:${Math.max(prevTotal/compMax*100,5)}%;background:var(--muted)"></div><div class="chart-label">Anterior</div></div>
      <div class="chart-bar-wrapper"><div class="chart-value">R$${thisMonth.toFixed(0)}</div><div class="chart-bar" style="height:${Math.max(thisMonth/compMax*100,5)}%;background:var(--accent)"></div><div class="chart-label">Atual</div></div>
    </div></div>
    <div class="section-title">Novo Gasto</div><div class="info-card"><div class="form-group"><label class="form-label">Categoria</label><select class="form-select" id="eCat"><option>Combustível</option><option>Manutenção</option><option>Peças</option><option>Acessórios</option><option>Lavagem</option><option>Documentação</option><option>Outros</option></select></div><div class="form-group"><label class="form-label">Valor</label><input class="form-input" type="number" step="0.01" id="eVal"></div><div class="form-group"><label class="form-label">KM Atual (para consumo)</label><input class="form-input" type="number" id="eKm" placeholder="Opcional"></div><div class="form-group"><label class="form-label">Desc</label><input class="form-input" id="eDesc"></div><div class="form-group"><label class="form-label">Foto</label><input class="form-input" type="file" accept="image/*" id="ePhoto"></div><button class="btn" onclick="addExp()">Adicionar</button></div>
    <div class="section-title">Histórico</div>${b.expenses.slice().reverse().map((e,i)=>`<div class="maint-item"><div class="maint-info"><div class="maint-name">${e.category}</div><div class="maint-meta">${e.date} • ${e.desc||''}</div>${e.photo?`<img src="${e.photo}" class="photo-preview">`:''}</div><div style="text-align:right"><div class="maint-km">R$ ${Number(e.value).toFixed(2)}</div><div style="margin-top:4px"><button class="btn btn-secondary btn-sm" onclick="editExp(${b.expenses.length-1-i})">✏️</button><button class="btn btn-secondary btn-sm" style="color:var(--danger)" onclick="removeExp(${b.expenses.length-1-i})">🗑️</button></div></div></div>`).join('')||'<div style="padding:16px;text-align:center;color:var(--muted)">Vazio.</div>'}</div>`;
}
function addExp(){
  const b=getCurrentBike(),v=document.getElementById('eVal').value;
  if(v){
    const fileInput = document.getElementById('ePhoto');
    const expData = {category:document.getElementById('eCat').value,value:v,desc:document.getElementById('eDesc').value,km:document.getElementById('eKm').value,date:new Date().toISOString().slice(0,10),photo:null};
    
    if(fileInput.files && fileInput.files[0]){
      const reader = new FileReader();
      reader.onload = function(e){
        expData.photo = e.target.result;
        b.expenses.push(expData);
        save();toast('Salvo!');showPage('expenses');
      };
      reader.readAsDataURL(fileInput.files[0]);
    } else {
      b.expenses.push(expData);
      save();toast('Salvo!');showPage('expenses');
    }
  } else toast('Preencha valor');
}
function editExp(i){const b=getCurrentBike(),e=b.expenses[i],v=prompt('Novo valor:',e.value);if(v!==null&&!isNaN(v)){e.value=v;const d=prompt('Nova descrição:',e.desc);if(d!==null)e.desc=d;save();toast('Editado!');showPage('expenses')}}
function removeExp(i){if(confirm('Excluir?')){getCurrentBike().expenses.splice(i,1);save();showPage('expenses')}}

// ===== PEÇAS =====
function renderPartsCatalog(el){
  const b=getCurrentBike(),areas=['Motor','Tanque','Frente','Rodas','Traseira','Assento'],icons={'Motor':'⚙️','Tanque':'⛽','Frente':'💡','Rodas':'🛞','Traseira':'🔧','Assento':'💺'};
  el.innerHTML=`<div class="section"><div class="section-title">Catálogo • ${b.brand} ${b.model}</div>${areas.map(a=>`<div class="parts-item" onclick="openParts('${a}')"><h4>${icons[a]} ${a}</h4><div style="font-size:11px;color:var(--muted)">Ver peças →</div></div>`).join('')}</div>`;
}
function openParts(area){
  const b=getCurrentBike(),data=PARTS_GUIDE[`${b.brand} ${b.model}`];
  document.getElementById('modalTitle').textContent=`${area} — ${b.model}`;
  const body=document.getElementById('modalBody');body.innerHTML='';
  if(!data||!data[area]){body.innerHTML='<div class="modal-item" style="text-align:center;color:var(--muted)">Nenhuma peça cadastrada para este modelo nesta categoria.</div>';}
  else{data[area].forEach(p=>{const d=document.createElement('div');d.className='modal-item';d.innerHTML=`<h4>${p.name} <span style="font-size:10px;padding:2px 6px;border-radius:4px;background:${p.type==='Original'?'rgba(168,85,247,.2)':'rgba(103,232,165,.2)'};color:${p.type==='Original'?'var(--glow)':'var(--ok)'}">${p.type}</span></h4><div style="font-size:11px;color:var(--accent);margin:4px 0">🔗 ${p.compat}</div><div style="font-weight:700;color:var(--muted)">Preço médio: ${p.price}</div>`;body.appendChild(d)})}
  document.getElementById('modal').classList.add('show');
}
function closeModal(){document.getElementById('modal').classList.remove('show')}

// ===== CONFIG MULTI-MOTO + OFICINAS + BACKUP + ÓLEO =====
function renderBikeConfig(el){
  const b=getCurrentBike(),pal={purple:'#a855f7',blue:'#2563eb',red:'#ef4444',black:'#64748b',white:'#e5e7eb',green:'#22c55e'};
  let cols='';for(let k in pal)cols+=`<div class="color-btn ${b.color===k?'active':''}" style="background:${pal[k]}" onclick="setColor('${k}')"></div>`;
  let list='';Object.keys(db.motos).forEach(id=>{const m=db.motos[id],cur=id===db.currentBikeId;list+=`<div class="saved-bike-item" style="${cur?'border-color:var(--glow)':''}"><div class="saved-bike-info" onclick="switchBike('${id}')"><div class="saved-bike-name">${m.brand} ${m.model} ${m.year}</div><div class="saved-bike-meta">${m.km} km ${cur?'• ATIVA':''}</div></div><div class="saved-bike-actions"><button class="btn btn-secondary btn-sm" onclick="deleteBike('${id}')">🗑️</button></div></div>`});
  
  // Oficinas
  let workshopsHtml = db.workshops.map((w,i)=>`<div class="maint-item"><div class="maint-info"><div class="maint-name">${w.name}</div><div class="maint-meta">${w.phone} • ${w.service}</div></div><button class="btn btn-secondary btn-sm" style="color:var(--danger)" onclick="removeWorkshop(${i})">🗑️</button></div>`).join('') || '<div style="padding:10px;color:var(--muted);text-align:center">Nenhuma oficina salva.</div>';
  
  el.innerHTML=`<div class="section"><div class="section-title">Minhas Motos</div>${list}<div class="section-title">Cor</div><div class="info-card"><div class="color-grid">${cols}</div></div>
  
    <div class="section-title">Alerta de Óleo</div>
    <div class="info-card">
      <div class="form-group"><label class="form-label">Última Troca (Data)</label><input class="form-input" type="date" id="oilDate" value="${db.oilConfig.lastDate}"></div>
      <div class="form-group"><label class="form-label">Última Troca (KM)</label><input class="form-input" type="number" id="oilKm" value="${db.oilConfig.lastKm}"></div>
      <div class="form-group"><label class="form-label">Intervalo (dias)</label><select class="form-select" id="oilDays"><option value="30">30 dias</option><option value="60">60 dias</option><option value="90" selected>90 dias</option><option value="180">180 dias</option></select></div>
      <div class="form-group"><label class="form-label">Intervalo (km)</label><input class="form-input" type="number" id="oilInterval" value="${db.oilConfig.intervalKm}"></div>
      <button class="btn" onclick="saveOilConfig()">Salvar Alerta</button>
    </div>

    <div class="section-title">Oficinas Favoritas</div>
    <div class="info-card">
      <div class="form-group"><label class="form-label">Nome</label><input class="form-input" id="wsName"></div>
      <div class="form-group"><label class="form-label">Telefone</label><input class="form-input" id="wsPhone"></div>
      <div class="form-group"><label class="form-label">Especialidade</label><input class="form-input" id="wsService" placeholder="Ex: Elétrica, Motor"></div>
      <button class="btn" onclick="addWorkshop()">Adicionar Oficina</button>
    </div>
    ${workshopsHtml}

    <div class="section-title">Dados da Moto</div>
    <div class="info-card"><div class="form-group"><label class="form-label">Marca</label><select class="form-select" id="bBrand" onchange="updateModels()">${Object.keys(BIKE_CATALOG).map(b=>`<option>${b}</option>`).join('')}</select></div><div class="form-group"><label class="form-label">Modelo</label><select class="form-select" id="bModel"></select></div><div class="form-group"><label class="form-label">Ano</label><select class="form-select" id="bYear"></select></div><div class="form-group"><label class="form-label">KM</label><input class="form-input" type="number" id="bKm" value="${b.km}"></div><div class="form-group"><label class="form-label">Placa</label><input class="form-input" id="bPlate" value="${b.plate||''}"></div><button class="btn" onclick="saveBike()">Salvar / Criar</button></div>
    
    <div class="section-title">Backup</div>
    <div class="info-card">
      <button class="btn" onclick="exportBackup()">💾 Baixar Backup (.json)</button>
      <div class="form-group" style="margin-top:12px"><label class="form-label">Restaurar Backup</label><input class="form-input" type="file" accept=".json" onchange="importBackup(this)"></div>
    </div>
  </div>`;
  
  document.getElementById('bBrand').value=b.brand;updateModels();document.getElementById('bModel').value=b.model;
  document.getElementById('oilDays').value=db.oilConfig.intervalDays;
  const ys=document.getElementById('bYear');ys.innerHTML='';for(let y=2026;y>=1997;y--){const o=document.createElement('option');o.value=y;o.textContent=y;if(y==b.year)o.selected=true;ys.appendChild(o)}
}
function updateModels(){const b=document.getElementById('bBrand').value,s=document.getElementById('bModel');s.innerHTML='';(BIKE_CATALOG[b]||[]).forEach(m=>s.add(new Option(m,m)))}
function setColor(c){getCurrentBike().color=c;save();renderBikeConfig(document.getElementById('mainContent'))}
function switchBike(id){db.currentBikeId=id;save();toast('Moto trocada!');showPage('home')}
function deleteBike(id){if(Object.keys(db.motos).length<=1){toast('Não pode excluir a última');return}if(confirm('Excluir moto?')){delete db.motos[id];if(db.currentBikeId===id)db.currentBikeId=Object.keys(db.motos)[0];save();renderBikeConfig(document.getElementById('mainContent'))}}
function saveBike(){
  const b=getCurrentBike(),br=document.getElementById('bBrand').value,mo=document.getElementById('bModel').value,yr=document.getElementById('bYear').value,km=document.getElementById('bKm').value,pl=document.getElementById('bPlate').value;
  const old=db.currentBikeId,nw=getBikeId(br,mo,yr);
  if(old!==nw){if(!db.motos[nw])db.motos[nw]={...b,brand:br,model:mo,year:yr,km:km,plate:pl};else{db.motos[nw].km=km;db.motos[nw].plate=pl}delete db.motos[old];db.currentBikeId=nw}else{b.km=km;b.plate=pl}
  save();toast('Salvo!');showPage('home');
}

// ===== OFICINAS =====
function addWorkshop(){
  const n=document.getElementById('wsName').value,p=document.getElementById('wsPhone').value,s=document.getElementById('wsService').value;
  if(n&&p){db.workshops.push({name:n,phone:p,service:s});save();toast('Oficina salva!');renderBikeConfig(document.getElementById('mainContent'))}
  else toast('Preencha nome e telefone');
}
function removeWorkshop(i){db.workshops.splice(i,1);save();renderBikeConfig(document.getElementById('mainContent'))}

// ===== ALERTA DE ÓLEO =====
function saveOilConfig(){
  db.oilConfig.lastDate=document.getElementById('oilDate').value;
  db.oilConfig.lastKm=Number(document.getElementById('oilKm').value);
  db.oilConfig.intervalDays=Number(document.getElementById('oilDays').value);
  db.oilConfig.intervalKm=Number(document.getElementById('oilInterval').value);
  save();toast('Alerta configurado!');renderBikeConfig(document.getElementById('mainContent'));
}

// ===== BACKUP =====
function exportBackup(){
  const blob=new Blob([JSON.stringify(db,null,2)],{type:'application/json'});
  const url=URL.createObjectURL(blob);
  const a=document.createElement('a');
  a.href=url;a.download=`moto-manager-backup-${new Date().toISOString().slice(0,10)}.json`;
  a.click();URL.revokeObjectURL(url);toast('Backup baixado!');
}
function importBackup(input){
  const file=input.files[0];
  if(!file)return;
  const reader=new FileReader();
  reader.onload=function(e){
    try{
      const imported=JSON.parse(e.target.result);
      if(imported.motos&&imported.currentBikeId){
        db=imported;save();toast('Backup restaurado!');showPage('home');
      }else{toast('Arquivo inválido');}
    }catch(err){toast('Erro ao ler arquivo');}
  };
  reader.readAsText(file);
}

applyTheme();showPage('home');
</script>

<!-- PWA SERVICE WORKER REGISTRATION -->
<script>
if ('serviceWorker' in navigator) {
  navigator.serviceWorker.register('./sw.js');
}
</script>
</body>
</html>