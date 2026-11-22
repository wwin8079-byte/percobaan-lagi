<!DOCTYPE html>
<html lang="id">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width,initial-scale=1">
<title>Plan Kerja 5W1H</title>
<style>
:root{--bg:#f4f5f2;--card:#fff;--ink:#1c2420;--mut:#66726b;--line:#dde2dc;--acc:#1f7a4d;--acc2:#e8f3ec;--warn:#b4531a;--warnbg:#fdf0e6;--bad:#b3261e}
@media(prefers-color-scheme:dark){:root{--bg:#141815;--card:#1d231f;--ink:#e8ede9;--mut:#93a097;--line:#2f3832;--acc:#4cc38a;--acc2:#1f3328;--warn:#f0a068;--warnbg:#3a2a1d;--bad:#ff8a80}}
*{box-sizing:border-box}
body{margin:0;background:var(--bg);color:var(--ink);font:15px/1.45 system-ui,-apple-system,"Segoe UI",Roboto,sans-serif}
.wrap{max-width:760px;margin:0 auto;padding:14px 14px 90px}
h1{font-size:20px;margin:6px 0 2px}
.sub{color:var(--mut);margin:0 0 14px;font-size:13px}
.card{background:var(--card);border:1px solid var(--line);border-radius:12px;padding:14px;margin:0 0 12px}
h2{font-size:13px;letter-spacing:.04em;text-transform:uppercase;color:var(--mut);margin:0 0 8px}
textarea,input,select{width:100%;font:inherit;color:inherit;background:var(--bg);border:1px solid var(--line);border-radius:8px;padding:8px 10px}
textarea:focus,input:focus,select:focus{outline:2px solid var(--acc);outline-offset:-1px}
textarea{resize:vertical}
label{display:block;font-size:12px;font-weight:600;color:var(--mut);margin:10px 0 3px}
label b{color:var(--ink)}
.row{display:flex;gap:8px;flex-wrap:wrap;margin-top:10px}
.row>*{flex:1 1 auto}
.grid{display:grid;grid-template-columns:1fr 1fr;gap:8px}
.grid3{display:grid;grid-template-columns:repeat(4,1fr);gap:8px}
@media(max-width:520px){.grid3{grid-template-columns:1fr 1fr}}
@media(max-width:520px){.grid{grid-template-columns:1fr}}
button,a.btn{font:inherit;cursor:pointer;border:1px solid var(--line);background:var(--card);color:var(--ink);border-radius:8px;padding:9px 12px;font-weight:600;text-align:center;text-decoration:none;display:inline-block}
button.p{background:var(--acc);border-color:var(--acc);color:#fff}
button.g{color:var(--mut);font-weight:500}
button.x{color:var(--bad);padding:6px 10px}
button.arm{background:var(--bad);color:#fff;border-color:var(--bad)}
button:active{transform:scale(.98)}
.jobhead{display:flex;gap:8px;align-items:flex-start;justify-content:space-between}
.num{background:var(--acc);color:#fff;border-radius:50%;width:26px;height:26px;flex:0 0 26px;display:grid;place-items:center;font-size:13px;font-weight:700;margin-top:6px}
.jobhead input{font-weight:600}
.miss{margin-top:8px;font-size:12px;color:var(--warn);background:var(--warnbg);border-radius:8px;padding:6px 9px}
.miss.ok{color:var(--acc);background:var(--acc2)}
.how{display:flex;gap:6px;align-items:center;margin-top:6px}
.how input[type=checkbox],.chk input{width:20px;height:20px;flex:0 0 20px;padding:0;accent-color:var(--acc)}
.chk{display:flex;gap:8px;align-items:center;margin:8px 0 0;font-size:14px;color:var(--ink);font-weight:500}
details{margin-top:12px;border-top:1px dashed var(--line);padding-top:8px}
.card>details{margin:0;border:0;padding:0}
summary{cursor:pointer;font-weight:600;color:var(--mut);font-size:13px}
#out{font:13.5px/1.5 ui-monospace,Menlo,Consolas,monospace;min-height:160px;white-space:pre-wrap}
.hist{display:flex;gap:6px;align-items:center;padding:7px 0;border-bottom:1px solid var(--line);font-size:13px}
.hist span{flex:1}
.hist button{padding:5px 9px;font-size:12px}
#toast{position:fixed;left:50%;bottom:22px;transform:translateX(-50%) translateY(30px);background:#1c2420;color:#fff;padding:9px 16px;border-radius:20px;font-size:13px;opacity:0;transition:.25s;pointer-events:none;z-index:9;max-width:90vw;text-align:center}
#toast.on{opacity:1;transform:translateX(-50%)}
.hint{font-size:12px;color:var(--mut);margin-top:6px}
.prev{background:var(--acc2);color:var(--ink);border-radius:8px;padding:8px 10px;font-size:13px;margin-top:8px;white-space:pre-wrap}
.admin{border-color:var(--acc)}
button.jambtn{width:100%;text-align:left;background:var(--bg);font-weight:600;padding:8px 10px}
.modal{position:fixed;inset:0;background:rgba(0,0,0,.45);display:grid;place-items:center;z-index:20;padding:12px}
.mbox{background:var(--card);border-radius:16px;padding:16px;width:min(330px,94vw);border:1px solid var(--line)}
.mhead{display:flex;justify-content:center;align-items:center;gap:6px;font-size:36px;font-weight:700;margin-bottom:6px}
.seg{font-size:36px;line-height:1;padding:6px 12px;border-radius:10px;border:0;background:var(--bg);color:var(--ink)}
.seg.on{background:var(--acc);color:#fff}
#dial{width:100%;display:block;touch-action:none;user-select:none;-webkit-user-select:none}
.dbg{fill:var(--bg);stroke:var(--line)}
.dhand{stroke:var(--acc);stroke-width:2}
.dknob{fill:var(--acc)}
.dl{fill:var(--ink);font-size:15px;font-family:inherit;pointer-events:none}
.dl.in{font-size:12px;fill:var(--mut)}
.dl.dsel{fill:#fff}
.hidden{display:none}
.modal.hidden{display:none}
.chips{display:flex;flex-wrap:wrap;gap:6px;margin-bottom:2px}
.chips label{display:flex;align-items:center;gap:6px;margin:0;padding:7px 12px;border:1px solid var(--line);border-radius:20px;background:var(--bg);font-size:14px;font-weight:500;color:var(--ink);cursor:pointer}
.chips label.on{border-color:var(--acc);background:var(--acc2)}
.chips input{width:18px;height:18px;padding:0;accent-color:var(--acc)}
button:disabled{opacity:.45;cursor:not-allowed}
.hint.warn{color:var(--warn);margin-top:2px}.hint.warn:empty{display:none}
</style>
</head>
<body>
<div class="wrap">
  <h1>📋 Plan Kerja → 5W1H</h1>
  <p class="sub">Tempel pesan WA → cek yang kurang jelas → salin → kirim ke grup.</p>

  <div class="card">
    <h2>1. Tempel pesan WA</h2>
    <textarea id="raw" rows="8" placeholder="Tempel instruksi kerja dari WA di sini…"></textarea>
    <div class="row">
      <button class="p" id="btnParse">Baca &amp; Buat 5W1H</button>
      <button class="g" id="btnSample">Isi contoh</button>
      <button class="g" id="btnReset">Kosongkan</button>
    </div>
  </div>

  <div id="work" class="hidden">
    <div class="card">
      <h2>Pengaturan pesan</h2>
      <label style="margin-top:0">Jenis pekerjaan (boleh pilih lebih dari satu)</label>
      <div class="chips" id="jenis"></div>
      <div class="grid">
        <div><label>Jam (ketuk untuk pilih)</label><button type="button" id="jam" class="jambtn"></button></div>
        <div><label>Tanggal</label><input type="date" id="date"></div>
      </div>
      <p class="hint" id="sesiHint"></p>
    </div>

    <h2 style="margin:4px 2px 8px">2. Periksa &amp; lengkapi</h2>
    <div id="cards"></div>
    <div class="row" style="margin:0 0 12px"><button id="btnAdd">+ Tambah kartu baru (lokasi / pelanggan lain)</button></div>

    <div class="card">
      <h2>3. Hasil — salin &amp; kirim</h2>
      <textarea id="out" readonly></textarea>
      <div class="row">
        <button class="p" id="btnCopy">📄 Salin</button>
        <a class="btn" id="btnWA" href="#" target="_blank" rel="noopener">Buka WhatsApp</a>
      </div>
      <div id="clar" class="hidden"><div class="row"><button id="btnClar">❓ Salin pertanyaan konfirmasi (untuk yang belum jelas)</button></div></div>
      <div class="row"><button class="g" id="btnSave">💾 Simpan ke riwayat (perangkat ini)</button></div>
    </div>
  </div>

  <div class="card"><details><summary>Riwayat di perangkat ini</summary><div id="hist"></div></details></div>

  <div class="card admin hidden" id="adminCard">
    <details open><summary>⚙️ Pengaturan Admin — hanya pemilik</summary><div id="adm"></div></details>
  </div>
  <p class="hint" id="cfgNote"></p>
</div>
<div id="clockModal" class="modal hidden"><div class="mbox">
  <div class="mhead"><button type="button" id="cH" class="seg on">09</button><span>:</span><button type="button" id="cM" class="seg">00</button></div>
  <p class="hint" id="cHint" style="text-align:center;margin:0 0 6px"></p>
  <svg id="dial" viewBox="0 0 260 260" role="img" aria-label="Jam analog"></svg>
  <div class="row"><button type="button" id="cCancel">Batal</button><button type="button" id="cOk" class="p">OK</button></div>
</div></div>
<div id="toast"></div>

<script>
/* ===== PARSER ===== */
const NUM=/^\s*(\d+)\s*[.)]\s*(.+)$/;
const cap=s=>s?s[0].toUpperCase()+s.slice(1):s;
const nm=s=>s.replace(/\S+/g,w=>/^(dan|dgn|dengan|&)$/i.test(w)?w.toLowerCase():cap(w));
const TIME=/(?:jam|pukul|pkl\.?)\s*(\d{1,2})\s*[.:]\s*(\d{2})/i;
const URLRE=/https?:\/\/\S+/;
function sesiFromJam(j){const h=parseInt(j,10);return h<12?'pagi':h<15?'siang':h<18?'sore':'malam'}
function newJob(what){return{what:what||'',who:'',where:'',time:'',why:'',how:[],pic:'',pasang:/pasang|pemasangan|install/i.test(what||''),links:[],more:[]}}
const MAXF=5;
const PASANG=/pasang|pemasangan|install/i;
const whatsStr=j=>[j.what].concat(j.more||[]).map(x=>(x||'').trim()).filter(Boolean).join(' + ');
function norm(jobs){(jobs||[]).forEach(j=>{j.links=Array.isArray(j.links)?j.links:[];j.more=Array.isArray(j.more)?j.more:[];delete j.fotos;j.pasang=!!j.pasang});return jobs}
function parsePic(v){
  const m=v.match(/\+?\d[\d\s.-]{7,}\d/);
  const ph=m?m[0].trim():'';
  const name=v.replace(ph,'').replace(/[()\[\]]/g,' ').replace(/\s+/g,' ').replace(/^[\s:–-]+|[\s:–-]+$/g,'');
  if(ph&&name)return nm(name)+' – '+ph;
  return ph||nm(name);
}
function parse(raw,SESIMAP){
  const lines=raw.replace(/\r/g,'').split('\n').map(s=>s.trim()).filter(Boolean);
  const hasNum=lines.some(l=>NUM.test(l));
  const jobs=[],head=[];let cur=null,mode='',first=true;
  lines.forEach(l=>{
    if(/^(terima\s*kasih|makasih|thanks|trims|matur)/i.test(l))return;
    const m=l.match(NUM);
    if(m||(!hasNum&&first)){cur=newJob(cap(m?m[2]:l));jobs.push(cur);mode='';first=false;return}
    first=false;
    if(!cur){head.push(l);return}
    let k;
    if(k=l.match(/^(?:lokasi|alamat|tempat)\s*:?\s*(.*)$/i)){cur.where=k[1].trim();mode='where';return}
    if(k=l.match(/^pic\s*:?\s*(.*)$/i)){cur.pic=parsePic(k[1]);mode='';return}
    if(k=l.match(/^(?:tim|team|petugas|personil)\s*:?\s*(.*)$/i)){cur.who=nm(k[1].trim());mode='';return}
    if(k=l.match(/^(?:tujuan|alasan|why)\s*:\s*(.*)$/i)){cur.why=cap(k[1].trim());mode='';return}
    if(k=l.match(/^(?:noted?|catatan|note|keterangan)\s*:?\s*(.*)$/i)){mode='how';if(k[1].trim())cur.how.push({t:cap(k[1].trim()),done:false});return}
    if(mode==='where'&&(URLRE.test(l)||!cur.where)){cur.where=(cur.where+' '+l).trim();return}
    const b=l.match(/^[-•*▪–]+\s*(.+)$/);
    cur.how.push({t:cap(b?b[1].trim():l),done:false});
  });
  const hj=head.join(' ');
  const ht=hj.match(TIME);
  const headTime=ht?ht[1].padStart(2,'0')+'.'+ht[2]:'';
  jobs.forEach(j=>{
    const t=(j.what+' '+j.how.map(h=>h.t).join(' ')).match(TIME);
    j.time=t?t[1].padStart(2,'0')+'.'+t[2]:'';
  });
  const all=(hj+' '+jobs.map(j=>j.what).join(' ')).toLowerCase();
  const KW={pengantaran:/pengantar|antar|kirim/,pemasangan:/pemasang|pasang|install/,pembongkaran:/bongkar/};
  const jenis=Object.keys(KW).filter(k=>KW[k].test(all));
  let jam=headTime||(jobs.find(j=>j.time)||{}).time||'';
  let sesi=(hj.toLowerCase().match(/\b(pagi|siang|sore|malam)\b/)||[])[1]||'';
  if(!sesi&&jam)sesi=sesiFromJam(jam);
  if(!jam&&sesi)jam=SESIMAP[sesi];
  jobs.forEach(j=>{if(j.time===jam)j.time=''});
  return{jobs,tomorrow:/\bbesok\b/i.test(hj),jam,sesi,jenis};
}

/* ===== ATURAN (CONFIG) — default; admin bisa mengubah ===== */
const DEF={
  sapaan:'Pak kita ada',
  template:'{sapaan} {jenis} {waktu} {jam}, berikut listnya :',
  zona:'WIB',
  jenis:['pengantaran','pemasangan','pembongkaran'],
  sesi:{pagi:'09.00',siang:'13.00',sore:'16.00',malam:'19.00'},
  labels:{tim:'Tim',lokasi:'Lokasi',waktu:'Waktu',tujuan:'Tujuan',pic:'PIC',catatan:'Catatan',simulasi:'Simulasi'},
  penutup:'',
  wajib:{what:true,who:true,where:true,time:true,why:true,how:true,foto:true}
};
const WAJIB_LBL={what:'What — pekerjaan',who:'Who — tim',where:'Where — lokasi',time:'When — jam',why:'Why — tujuan',how:'How — catatan/langkah',foto:'Link simulasi (khusus pemasangan)'};
const LBL_LBL={tim:'Label Tim',lokasi:'Label Lokasi',waktu:'Label Waktu',tujuan:'Label Tujuan',pic:'Label PIC',catatan:'Label Catatan',simulasi:'Label Simulasi'};
let CFG=JSON.parse(JSON.stringify(DEF));
const isStr=v=>typeof v==='string';
function mergeCfg(d){
  const c=JSON.parse(JSON.stringify(DEF));
  if(!d||typeof d!=='object')return c;
  if(isStr(d.sapaan)&&d.sapaan.length<120)c.sapaan=d.sapaan;
  if(isStr(d.template)&&d.template.length<300)c.template=d.template;
  if(isStr(d.zona)&&d.zona.length<12)c.zona=d.zona;
  if(isStr(d.penutup)&&d.penutup.length<500)c.penutup=d.penutup;
  if(Array.isArray(d.jenis)){const j=d.jenis.filter(x=>isStr(x)&&x.trim()).map(x=>x.trim().toLowerCase()).slice(0,12);if(j.length)c.jenis=j}
  if(d.sesi&&typeof d.sesi==='object')['pagi','siang','sore','malam'].forEach(k=>{if(isStr(d.sesi[k])&&/^\d{1,2}[.:]\d{2}$/.test(d.sesi[k]))c.sesi[k]=d.sesi[k]});
  if(d.labels&&typeof d.labels==='object')Object.keys(c.labels).forEach(k=>{if(isStr(d.labels[k])&&d.labels[k].trim()&&d.labels[k].length<40)c.labels[k]=d.labels[k].trim()});
  if(d.wajib&&typeof d.wajib==='object')Object.keys(c.wajib).forEach(k=>{if(typeof d.wajib[k]==='boolean')c.wajib[k]=d.wajib[k]});
  return c;
}

/* ===== STATE & UTIL ===== */
const $=id=>document.getElementById(id);
const KEY='rf-plan-draft-v2',HKEY='rf-plan-hist-v2';
const DAYS=['Minggu','Senin','Selasa','Rabu','Kamis','Jumat','Sabtu'];
const MON=['Januari','Februari','Maret','April','Mei','Juni','Juli','Agustus','September','Oktober','November','Desember'];
const S={raw:'',date:'',jobs:[],jenis:['pengantaran'],sesi:'pagi',jam:'09.00'};
const iso=d=>d.getFullYear()+'-'+String(d.getMonth()+1).padStart(2,'0')+'-'+String(d.getDate()).padStart(2,'0');
function fmtDate(s){if(!s)return'';const[p,q,r]=s.split('-').map(Number);const d=new Date(p,q-1,r);return DAYS[d.getDay()]+', '+r+' '+MON[q-1]+' '+p}
const esc=s=>String(s==null?'':s).replace(/[&<>"]/g,c=>({'&':'&amp;','<':'&lt;','>':'&gt;','"':'&quot;'}[c]));
const timeTxt=t=>t?t+(/^\d{1,2}[.:]\d{2}$/.test(t)?' '+CFG.zona:''):'';
const cap1=s=>s?s[0].toUpperCase()+s.slice(1):s;
function fillJam(){const e=$('jam');if(e)e.textContent='🕒 '+S.jam+' '+CFG.zona}
function toArr(v){if(Array.isArray(v))return v.filter(Boolean);if(typeof v==='string'&&v)return v.split(/\s*&\s*|\s*,\s*/).filter(Boolean);return[CFG.jenis[0]]}
function jenisStr(){const a=toArr(S.jenis);if(!a.length)return'pekerjaan';if(a.length===1)return a[0];return a.slice(0,-1).join(', ')+' & '+a[a.length-1]}

function toast(m){const t=$('toast');t.textContent=m;t.classList.add('on');clearTimeout(toast.t);toast.t=setTimeout(()=>t.classList.remove('on'),1800)}
function copy(text,sel){
  const ok=()=>toast('Tersalin ✓');
  const fb=()=>{
    const a=document.createElement('textarea');a.value=text;a.style.cssText='position:fixed;opacity:0;top:0';document.body.appendChild(a);a.select();
    let r=false;try{r=document.execCommand('copy')}catch(e){}
    a.remove();
    if(r)ok();else{if(sel){sel.focus();sel.select()}toast('Teks terpilih — salin manual (tahan lalu Salin)')}
  };
  try{if(navigator.clipboard&&navigator.clipboard.writeText){navigator.clipboard.writeText(text).then(ok,fb);return}}catch(e){}
  fb();
}
/* konfirmasi 2 langkah (dialog confirm() diblokir di halaman ini) */
function arm(btn,fn,label){
  if(btn.dataset.armed){clearTimeout(btn._t);btn.classList.remove('arm');btn.textContent=btn.dataset.orig;delete btn.dataset.armed;fn();return}
  btn.dataset.armed='1';btn.dataset.orig=btn.textContent;btn.textContent=label||'Yakin? Tekan lagi';btn.classList.add('arm');
  btn._t=setTimeout(()=>{btn.classList.remove('arm');btn.textContent=btn.dataset.orig;delete btn.dataset.armed},3000);
}

const REQ=[['what','What (Apa)','Pekerjaan apa persisnya?'],['who','Who (Siapa)','Siapa tim yang berangkat?'],['where','Where (Di mana)','Lokasi / alamat tujuannya di mana?'],['time','When (Jam)','Jam berapa pelaksanaannya?'],['why','Why (Mengapa)','Tujuan / hasil yang diharapkan apa?'],['how','How (Bagaimana)','Langkah & hal yang harus dibawa / dilakukan apa?'],['foto','Link simulasi','Link Google Drive simulasi pemasangan (before/after), minimal 1 link?']];
const filled=(j,k)=>k==='foto'?okLinks(j).length>=1:k==='how'?j.how.some(h=>h.t.trim()):k==='time'?!!(j.time||S.jam):!!String(j[k]).trim();
const missing=j=>REQ.filter(r=>CFG.wajib[r[0]]&&(r[0]!=='foto'||j.pasang)&&!filled(j,r[0]));

/* ===== OUTPUT ===== */
function headLine(c){
  c=c||CFG;
  const tm=new Date();tm.setDate(tm.getDate()+1);
  let w=S.sesi||'';
  if(S.date===iso(new Date()))w=S.sesi?S.sesi+' ini':'hari ini';
  else if(S.date===iso(tm))w='besok'+(S.sesi?' '+S.sesi:'');
  const jam=S.jam?'jam '+S.jam+(/^\d{1,2}[.:]\d{2}$/.test(S.jam)?' '+c.zona:''):'';
  return c.template.replace(/\{sapaan\}/g,c.sapaan).replace(/\{jenis\}/g,jenisStr()).replace(/\{waktu\}/g,w).replace(/\{jam\}/g,jam)
    .replace(/[ \t]{2,}/g,' ').replace(/ ,/g,',').trim();
}
function jobBlock(j,n){
  const L=CFG.labels;
  let t='\n*'+n+'. '+((j.what||'').trim()||'-')+'*\n';
  (j.more||[]).filter(x=>x.trim()).forEach(x=>{t+='*+ '+x.trim()+'*\n'});
  if(j.where)t+=L.lokasi+': '+j.where+'\n';
  if(j.time&&j.time!==S.jam)t+=L.waktu+': '+timeTxt(j.time)+'\n';
  if(j.why)t+=L.tujuan+': '+j.why+'\n';
  if(j.pasang&&okLinks(j).length)t+=linkLines(j,L);
  if(j.pic)t+=L.pic+': '+j.pic+'\n';
  const h=j.how.filter(x=>x.t.trim());
  if(h.length)t+=L.catatan+':\n'+h.map(x=>'- '+x.t.trim()).join('\n')+'\n';
  return t;
}
function planText(){
  let t=headLine()+'\n🗓️ '+fmtDate(S.date)+'\n';
  S.jobs.forEach((j,i)=>{t+=jobBlock(j,i+1)});
  t=t.trim();
  if(CFG.penutup.trim())t+='\n\n'+CFG.penutup.trim();
  const teams=[];
  S.jobs.forEach((j,i)=>{const w=(j.who||'').trim();if(!w)return;const key=w.toLowerCase();let g=teams.find(x=>x.key===key);if(!g){g={key,who:w,n:[]};teams.push(g)}g.n.push(i+1)});
  if(teams.length){
    const one=teams.length===1;
    t+='\n\n'+teams.map(g=>'*'+CFG.labels.tim+(one?'':' (pekerjaan '+g.n.join(', ')+')')+': '+g.who+'*').join('\n');
  }
  return t;
}
function clarText(){
  const parts=[];
  S.jobs.forEach((j,i)=>{
    const m=missing(j);if(!m.length)return;
    parts.push('Pekerjaan '+(i+1)+' ('+(whatsStr(j)||'-')+'):\n'+m.map(r=>'- '+r[2]).join('\n'));
  });
  return parts.length?'Izin konfirmasi pak 🙏\nBiar tidak salah, mohon dilengkapi:\n\n'+parts.join('\n\n')+'\n\nTerima kasih pak.':'';
}

/* ===== UI ===== */
function autoPasang(i,v){
  const j=S.jobs[i];
  if(!j||j.pasang||j.pasangOff||!PASANG.test(v))return;
  j.pasang=true;renderFoto(i);
  const c=document.querySelector('input[data-f="pasang"][data-i="'+i+'"]');if(c)c.checked=true;
}
function renderCards(){
  $('cards').innerHTML=S.jobs.map((j,i)=>`
  <div class="card" data-card="${i}">
    <div class="jobhead"><div class="num">${i+1}</div>
      <div style="flex:1"><label style="margin-top:0"><b>What</b> — Pekerjaan</label><input data-i="${i}" data-f="what" value="${esc(j.what)}"></div>
      <button class="x" data-act="deljob" data-i="${i}" title="Hapus kartu">✕</button></div>
    ${(j.more||[]).map((m,k)=>`<div class="how"><input data-i="${i}" data-mk="${k}" value="${esc(m)}" placeholder="Pekerjaan lain (What)…"><button class="x" data-act="delmore" data-i="${i}" data-n="${k}" title="Hapus">✕</button></div>`).join('')}
    <div class="row"><button class="g" data-act="addmore" data-i="${i}">＋ Tambah pekerjaan (What)</button></div>
    <label><b>Who</b> — Tim</label><input data-i="${i}" data-f="who" value="${esc(j.who)}" placeholder="Siapa saja yang berangkat">
    ${j.time?`<div class="hint">🕒 Jam khusus pekerjaan ini: <b>${esc(j.time)}</b> <button class="g" data-act="cleartime" data-i="${i}" style="padding:3px 8px;font-size:12px">pakai jam utama</button></div>`:''}
    <label><b>Where</b> — Lokasi / link maps</label><textarea rows="2" data-i="${i}" data-f="where">${esc(j.where)}</textarea>
    <label><b>Why</b> — Tujuan / alasan</label><input data-i="${i}" data-f="why" value="${esc(j.why)}" placeholder="Biasanya tidak ada di pesan WA — isi / tanyakan">
    <label><b>How</b> — Langkah &amp; catatan (centang saat sudah dikerjakan)</label>
    <div>${j.how.map((h,k)=>`<div class="how"><input type="checkbox" data-i="${i}" data-h="${k}" data-k="d" ${h.done?'checked':''}><input data-i="${i}" data-h="${k}" data-k="t" value="${esc(h.t)}"><button class="x" data-act="delhow" data-i="${i}" data-h="${k}">✕</button></div>`).join('')}</div>
    <div class="row"><button class="g" data-act="addhow" data-i="${i}">+ Tambah langkah</button></div>
    <label class="chk"><input type="checkbox" data-i="${i}" data-f="pasang" ${j.pasang?'checked':''}> Pekerjaan pemasangan — wajib link simulasi Google Drive (min 1, maks 5)</label>
    <div id="foto${i}"></div>
    <label><b>PIC</b> — Kontak di lokasi</label><input data-i="${i}" data-f="pic" value="${esc(j.pic)}" placeholder="Nama – no. HP">
    <div class="miss" id="miss${i}"></div>
  </div>`).join('');
  S.jobs.forEach((j,i)=>renderFoto(i));
  refresh();
}
function refresh(){
  S.jobs.forEach((j,i)=>{
    const el=$('miss'+i);if(!el)return;
    const m=missing(j);
    el.className='miss'+(m.length?'':' ok');
    el.textContent=m.length?'⚠ Belum jelas: '+m.map(r=>r[1].split(' ')[0]).join(', '):'✓ 5W1H lengkap';
  });
  const txt=planText();
  const o=$('out');o.value=txt;
  o.style.height='auto';o.style.height=Math.max(160,o.scrollHeight+4)+'px';
  $('btnWA').href='https://wa.me/?text='+encodeURIComponent(txt);
  $('clar').classList.toggle('hidden',!clarText());
  try{localStorage.setItem(KEY,JSON.stringify(S))}catch(e){}
}
function fillJenis(){
  const sel=toArr(S.jenis),list=CFG.jenis.slice();
  sel.forEach(v=>{if(!list.includes(v))list.push(v)});
  $('jenis').innerHTML=list.map(v=>`<label class="${sel.includes(v)?'on':''}"><input type="checkbox" value="${esc(v)}" ${sel.includes(v)?'checked':''}> ${esc(cap1(v))}</label>`).join('');
  $('sesiHint').textContent='Ketuk jam → pilih jam di jam analog, lalu menitnya. Kata pagi / siang / sore / malam di judul pesan terisi otomatis.';
}
function syncCtl(){S.sesi=sesiFromJam(S.jam);fillJenis();fillJam();$('date').value=S.date}
function load(parsed,raw){
  S.raw=raw;S.jobs=parsed.jobs;
  {const low=raw.toLowerCase();const js=CFG.jenis.filter(j=>parsed.jenis.includes(j)||low.includes(j));S.jenis=js.length?js:(toArr(S.jenis).length?toArr(S.jenis):[CFG.jenis[0]])}
  S.sesi=parsed.sesi||'pagi';S.jam=parsed.jam||CFG.sesi[S.sesi];
  const d=new Date();if(parsed.tomorrow)d.setDate(d.getDate()+1);
  S.date=iso(d);syncCtl();
  $('work').classList.remove('hidden');
  renderCards();
}
$('btnParse').onclick=()=>{
  const raw=$('raw').value.trim();
  if(!raw){toast('Tempel pesan WA dulu');return}
  const p=parse(raw,CFG.sesi);
  if(!p.jobs.length){toast('Tidak ada pekerjaan terbaca');return}
  load(p,raw);
  $('work').scrollIntoView({behavior:'smooth'});
};
$('btnSample').onclick=()=>{
  $('raw').value=`Pak kita ada pekerjaan pagi ini jam 10.00, berikut listnya :

1. Pengantaran Meja Stenlis Kelapa sawit 7 Unit
Lokasi: https://maps.app.goo.gl/contoh123
Pic: 0812-3456-7890 ( Bu Rina )

Noted:
- Untuk Bast jangan Lupa di bawak Kembali
- Penerima Meja Kelapa sawit langsung ke bu rina ya pak

Tim: Pak Budi dan pak Andi
Terima kasih pak 🙏🏻`;
};
$('btnReset').onclick=function(){arm(this,()=>{
  $('raw').value='';S.jobs=[];S.raw='';$('work').classList.add('hidden');
  try{localStorage.removeItem(KEY)}catch(e){}
},'Yakin kosongkan?')};
$('date').oninput=e=>{S.date=e.target.value;refresh()};
$('jenis').addEventListener('change',e=>{
  const t=e.target;if(!t||t.type!=='checkbox')return;
  const set=new Set(toArr(S.jenis));if(t.checked)set.add(t.value);else set.delete(t.value);
  const ord=CFG.jenis;S.jenis=Array.from(set).sort((x,y)=>{const a=ord.indexOf(x),b=ord.indexOf(y);return(a<0?99:a)-(b<0?99:b)});
  t.parentNode.classList.toggle('on',t.checked);refresh();
});
$('jam').onclick=openClock;
$('btnAdd').onclick=()=>{S.jobs.push(newJob(''));renderCards()};

$('cards').addEventListener('input',e=>{
  const t=e.target,i=+t.dataset.i;if(isNaN(i))return;
  if(t.dataset.f){S.jobs[i][t.dataset.f]=t.type==='checkbox'?t.checked:t.value;if(t.dataset.f==='pasang'){if(!t.checked)S.jobs[i].pasangOff=true;renderFoto(i)}if(t.dataset.f==='what')autoPasang(i,t.value)}
  else if(t.dataset.mk!==undefined){S.jobs[i].more[+t.dataset.mk]=t.value;autoPasang(i,t.value)}
  else if(t.dataset.ln!==undefined){const L=S.jobs[i].links[+t.dataset.ln];if(t.dataset.lk==='k')L.k=t.value;else{L.u=t.value.trim();setLinkWarn(i,+t.dataset.ln)}}
  else if(t.dataset.h!==undefined){const h=S.jobs[i].how[+t.dataset.h];if(t.dataset.k==='d')h.done=t.checked;else h.t=t.value}
  refresh();
});
$('cards').addEventListener('click',e=>{
  const b=e.target.closest('button');if(!b||!b.dataset.act)return;
  const i=+b.dataset.i;
  if(b.dataset.act==='addhow'){S.jobs[i].how.push({t:'',done:false});renderCards()}
  if(b.dataset.act==='delhow'){S.jobs[i].how.splice(+b.dataset.h,1);renderCards()}
  if(b.dataset.act==='deljob')arm(b,()=>{S.jobs.splice(i,1);renderCards()},'Yakin?');
  if(b.dataset.act==='cleartime'){S.jobs[i].time='';renderCards()}
  if(b.dataset.act==='addmore'){S.jobs[i].more.push('');renderCards();const el=document.querySelector('input[data-i="'+i+'"][data-mk="'+(S.jobs[i].more.length-1)+'"]');if(el)el.focus()}
  if(b.dataset.act==='delmore'){S.jobs[i].more.splice(+b.dataset.n,1);renderCards()}
  if(b.dataset.act==='ladd'){const j=S.jobs[i];if(j.links.length<MAXF){const has=k=>j.links.some(l=>l.k===k);j.links.push({k:!has('before')?'before':!has('after')?'after':'semua',u:''});renderFoto(i);refresh()}}
  if(b.dataset.act==='ldel'){S.jobs[i].links.splice(+b.dataset.n,1);renderFoto(i);refresh()}
});
$('btnCopy').onclick=()=>copy($('out').value,$('out'));
$('btnClar').onclick=()=>copy(clarText());

function hist(){try{return JSON.parse(localStorage.getItem(HKEY)||'[]')}catch(e){return[]}}
function renderHist(){
  const h=hist();
  $('hist').innerHTML=h.length?h.map((x,i)=>`<div class="hist"><span>${esc(x.title)}</span><button data-hl="${i}">Buka</button><button class="x" data-hd="${i}">✕</button></div>`).join(''):'<p class="hint">Belum ada riwayat.</p>';
}
$('btnSave').onclick=()=>{
  if(!S.jobs.length)return;
  const h=hist();
  h.unshift({title:fmtDate(S.date)+' — '+(S.jobs[0].what||'Pekerjaan')+(S.jobs.length>1?' +'+(S.jobs.length-1):''),data:{raw:S.raw,date:S.date,jobs:S.jobs,jenis:S.jenis,sesi:S.sesi,jam:S.jam}});
  try{localStorage.setItem(HKEY,JSON.stringify(h.slice(0,60)));toast('Disimpan ✓')}catch(e){toast('Penyimpanan di perangkat ini tidak tersedia')}
  renderHist();
};
$('hist').addEventListener('click',e=>{
  const b=e.target.closest('button');if(!b)return;
  const h=hist();
  if(b.dataset.hl!==undefined){const d=h[+b.dataset.hl].data;S.raw=d.raw;S.date=d.date;S.jobs=norm(d.jobs);S.jenis=toArr(d.jenis);S.sesi=d.sesi||'pagi';S.jam=d.jam||CFG.sesi[S.sesi];$('raw').value=d.raw||'';syncCtl();$('work').classList.remove('hidden');renderCards();window.scrollTo({top:0,behavior:'smooth'})}
  if(b.dataset.hd!==undefined)arm(b,()=>{h.splice(+b.dataset.hd,1);try{localStorage.setItem(HKEY,JSON.stringify(h))}catch(e){}renderHist()},'Yakin?');
});

/* ===== JAM ANALOG ===== */
const CK={h:9,m:0,mode:'h',drag:false};
const pad2=n=>String(n).padStart(2,'0');
function polar(r,deg){const a=deg*Math.PI/180;return[130+r*Math.sin(a),130-r*Math.cos(a)]}
function updHead(){
  $('cH').textContent=pad2(CK.h);$('cM').textContent=pad2(CK.m);
  $('cH').classList.toggle('on',CK.mode==='h');$('cM').classList.toggle('on',CK.mode==='m');
  $('cHint').textContent=CK.mode==='h'?'Pilih jam (lingkar luar 1–12, dalam 13–24)':(CK.h===24?'Jam 24 hanya menit 00':'Pilih menit (geser untuk menit tepat)');
}
function drawDial(){
  let o='<circle cx="130" cy="130" r="124" class="dbg"/>',selDeg,selR,labels=[];
  if(CK.mode==='h'){
    for(let i=1;i<=12;i++)labels.push({t:String(i),deg:(i%12)*30,r:100,v:i,c:'dl'});
    for(let j=13;j<=24;j++)labels.push({t:String(j),deg:(j%12)*30,r:66,v:j,c:'dl in'});
    selDeg=(CK.h%12)*30;selR=CK.h>=13?66:100;
    var selV=CK.h;
  }else{
    for(let m=0;m<60;m+=5)labels.push({t:pad2(m),deg:m*6,r:100,v:m,c:'dl'});
    selDeg=CK.m*6;selR=100;var selV=CK.m;
  }
  const[kx,ky]=polar(selR,selDeg);
  o+=`<line x1="130" y1="130" x2="${kx}" y2="${ky}" class="dhand"/><circle cx="130" cy="130" r="4" class="dknob"/><circle cx="${kx}" cy="${ky}" r="${CK.mode==='h'&&selR===66?14:17}" class="dknob"/>`;
  labels.forEach(l=>{const[x,y]=polar(l.r,l.deg);o+=`<text x="${x}" y="${y}" text-anchor="middle" dy=".35em" class="${l.c}${l.v===selV?' dsel':''}">${l.t}</text>`});
  if(CK.mode==='m'&&CK.m%5!==0)o+=`<circle cx="${kx}" cy="${ky}" r="3" fill="#fff"/>`;
  $('dial').innerHTML=o;
}
function dialPick(e,final){
  const r=$('dial').getBoundingClientRect();
  const x=(e.clientX-r.left)/r.width*260-130,y=(e.clientY-r.top)/r.height*260-130;
  let ang=Math.atan2(x,-y)*180/Math.PI;if(ang<0)ang+=360;
  const dist=Math.hypot(x,y);
  if(CK.mode==='h'){
    const idx=Math.round(ang/30)%12;
    CK.h=dist<83?(idx===0?24:idx+12):(idx===0?12:idx);
    if(CK.h===24)CK.m=0;
  }else CK.m=CK.h===24?0:Math.round(ang/6)%60;
  if(final&&CK.mode==='h'&&CK.h!==24)CK.mode='m';
  drawDial();updHead();
}
function openClock(){
  const m=/^(\d{1,2})[.:](\d{2})$/.exec(S.jam||'');
  CK.h=m?+m[1]:9;CK.m=m?+m[2]:0;
  if(CK.h<1)CK.h=24;if(CK.h>24)CK.h=24;if(CK.m>59)CK.m=0;if(CK.h===24)CK.m=0;
  CK.mode='h';drawDial();updHead();$('clockModal').classList.remove('hidden');
}
function closeClock(){$('clockModal').classList.add('hidden')}
(function(){
  const d=$('dial');
  d.addEventListener('pointerdown',e=>{CK.drag=true;try{d.setPointerCapture(e.pointerId)}catch(x){}dialPick(e,false)});
  d.addEventListener('pointermove',e=>{if(CK.drag)dialPick(e,false)});
  d.addEventListener('pointerup',e=>{if(!CK.drag)return;CK.drag=false;dialPick(e,true)});
  d.addEventListener('pointercancel',()=>{CK.drag=false});
  $('cH').onclick=()=>{CK.mode='h';drawDial();updHead()};
  $('cM').onclick=()=>{if(CK.h===24)return;CK.mode='m';drawDial();updHead()};
  $('cCancel').onclick=closeClock;
  $('cOk').onclick=()=>{S.jam=pad2(CK.h)+'.'+pad2(CK.m);S.sesi=sesiFromJam(S.jam);fillJam();refresh();closeClock()};
  $('clockModal').addEventListener('click',e=>{if(e.target===$('clockModal'))closeClock()});
  document.addEventListener('keydown',e=>{if(e.key==='Escape')closeClock()});
})();

/* ===== LINK SIMULASI (Google Drive) ===== */
const KIND={before:'Before',after:'After',semua:'Semua foto'};
const isDrive=u=>/^https?:\/\/(drive|docs)\.google\.com\//i.test(u);
const okLinks=j=>j.links.filter(l=>l.u&&l.u.trim());
function linkLines(j,L){
  const a=okLinks(j);
  if(a.length===1&&a[0].k==='semua')return L.simulasi+': '+a[0].u.trim()+'\n';
  return L.simulasi+':\n'+a.map(l=>'- '+KIND[l.k]+': '+l.u.trim()).join('\n')+'\n';
}
function setLinkWarn(i,n){const e=$('lw'+i+'_'+n),l=S.jobs[i].links[n];if(e&&l)e.textContent=l.u&&!isDrive(l.u)?'⚠ Ini bukan link Google Drive':''}
function renderFoto(i){
  const el=$('foto'+i),j=S.jobs[i];if(!el||!j)return;
  if(!j.pasang){el.innerHTML='';return}
  const full=j.links.length>=MAXF;
  el.innerHTML=`<div class="hint">Link simulasi pemasangan (Google Drive): <b>${okLinks(j).length}/${MAXF}</b> · minimal 1 link. Pastikan akses link sudah “Siapa saja yang memiliki link”.</div>
  ${j.links.map((l,n)=>`<div class="how"><select style="width:112px;flex:0 0 112px" data-i="${i}" data-ln="${n}" data-lk="k">${Object.keys(KIND).map(k=>`<option value="${k}" ${l.k===k?'selected':''}>${KIND[k]}</option>`).join('')}</select><input data-i="${i}" data-ln="${n}" data-lk="u" value="${esc(l.u)}" placeholder="https://drive.google.com/…"><button class="x" data-act="ldel" data-i="${i}" data-n="${n}" title="Hapus">✕</button></div><div class="hint warn" id="lw${i}_${n}">${l.u&&!isDrive(l.u)?'⚠ Ini bukan link Google Drive':''}</div>`).join('')}
  <div class="row"><button class="g" data-act="ladd" data-i="${i}" ${full?'disabled':''}>＋ Tambah link simulasi</button></div>`;
}

/* ===== ADMIN (hanya pemilik) ===== */
let DBREF=null,admBuilt=false;
function buildAdmin(){
  if(admBuilt)return;admBuilt=true;
  $('adminCard').classList.remove('hidden');
  const lblIn=Object.keys(LBL_LBL).map(k=>`<div><label>${LBL_LBL[k]}</label><input id="a_l_${k}"></div>`).join('');
  const wj=Object.keys(WAJIB_LBL).map(k=>`<label class="chk"><input type="checkbox" id="a_w_${k}"> ${WAJIB_LBL[k]}</label>`).join('');
  $('adm').innerHTML=`
    <p class="hint">Perubahan di sini berlaku untuk semua orang yang membuka aplikasi ini. Orang lain tidak melihat panel ini dan tidak bisa mengubahnya.</p>
    <label>Kalimat pembuka ({sapaan})</label><input id="a_sapaan">
    <label>Template kalimat judul — pakai {sapaan} {jenis} {waktu} {jam}</label><input id="a_template">
    <div class="prev" id="a_prev"></div>
    <label>Pilihan jenis pekerjaan (satu per baris)</label><textarea id="a_jenis" rows="4"></textarea>
    <label>Zona waktu (ditulis setelah jam)</label><input id="a_zona">
    <label>Nama label di pesan WA</label><div class="grid">${lblIn}</div>
    <label>Kalimat penutup (opsional, ditaruh di akhir pesan)</label><textarea id="a_penutup" rows="2" placeholder="mis. Terima kasih pak 🙏🏻"></textarea>
    <label>Bagian yang wajib terisi (yang kosong diberi tanda ⚠)</label>${wj}
    <div class="row"><button class="p" id="a_save">Simpan aturan</button><button id="a_def">Kembalikan ke standar</button></div>
    <p class="hint" id="a_msg"></p>`;
  $('adm').addEventListener('input',()=>{$('a_prev').textContent='Contoh judul: '+headLine(readAdmin())});
  $('a_save').onclick=saveAdmin;
  $('a_def').onclick=function(){arm(this,()=>writeCfg(DEF,'Aturan dikembalikan ke standar.'),'Yakin kembalikan?')};
}
function fillAdmin(){
  if(!admBuilt)return;
  const c=CFG;
  $('a_sapaan').value=c.sapaan;$('a_template').value=c.template;$('a_jenis').value=c.jenis.join('\n');
  $('a_zona').value=c.zona;$('a_penutup').value=c.penutup;
  Object.keys(c.labels).forEach(k=>$('a_l_'+k).value=c.labels[k]);
  Object.keys(c.wajib).forEach(k=>$('a_w_'+k).checked=c.wajib[k]);
  $('a_prev').textContent='Contoh judul: '+headLine(c);
}
function readAdmin(){
  const c=JSON.parse(JSON.stringify(CFG));
  c.sapaan=$('a_sapaan').value.trim();c.template=$('a_template').value.trim()||DEF.template;
  c.jenis=$('a_jenis').value.split('\n').map(x=>x.trim().toLowerCase()).filter(Boolean);
  c.zona=$('a_zona').value.trim();c.penutup=$('a_penutup').value;
  Object.keys(c.labels).forEach(k=>c.labels[k]=$('a_l_'+k).value.trim()||DEF.labels[k]);
  Object.keys(c.wajib).forEach(k=>c.wajib[k]=$('a_w_'+k).checked);
  return c;
}
async function writeCfg(obj,okMsg){
  const msg=$('a_msg');
  if(!DBREF){msg.textContent='Belum tersambung ke penyimpanan bersama — coba muat ulang halaman.';return}
  try{
    await DBREF.doc('config/main').set(JSON.parse(JSON.stringify(obj)));
    msg.textContent=okMsg||'Tersimpan ✓ — berlaku untuk semua pengguna.';toast('Aturan tersimpan ✓');
  }catch(e){msg.textContent='Gagal menyimpan ('+((e&&e.code)||'error')+'). Coba lagi.'}
}
function saveAdmin(){
  const c=readAdmin(),msg=$('a_msg');
  if(!c.jenis.length){msg.textContent='Pilihan jenis pekerjaan minimal satu.';return}
  writeCfg(c);
}

/* ===== SAMBUNG KE PENYIMPANAN BERSAMA ===== */
function applyCfg(d){
  CFG=mergeCfg(d);
  fillJenis();refresh();
  if(!admBuilt||!$('adm').contains(document.activeElement))fillAdmin();
}
async function connect(){
  const note=$('cfgNote');note.textContent='Aturan: standar';
  if(typeof claude==='undefined'||!claude.use)return;
  let db=null,user=null;
  try{[db,user]=await Promise.all([claude.use('db'),claude.use('user')])}catch(e){}
  let owner=false;
  try{owner=!!(user&&await user.isOwner())}catch(e){}
  if(!db)return;
  DBREF=db;
  if(owner)buildAdmin();
  let first=true;
  const timer=setTimeout(()=>{note.textContent='Aturan: standar (penyimpanan bersama belum terjangkau)'},10000);
  try{
    db.doc('config/main').onSnapshot(snap=>{
      clearTimeout(timer);
      const d=snap.exists?snap.data():null;
      applyCfg(d);
      note.textContent=d?'Aturan: dari admin':'Aturan: standar';
      if(first&&owner)fillAdmin();first=false;
    },()=>{clearTimeout(timer)});
  }catch(e){}
}

(function init(){
  renderHist();fillJenis();
  try{
    const d=JSON.parse(localStorage.getItem(KEY)||'null');
    if(d&&d.jobs&&d.jobs.length){S.raw=d.raw||'';S.date=d.date||iso(new Date());S.jobs=norm(d.jobs);S.jenis=toArr(d.jenis);S.sesi=d.sesi||'pagi';S.jam=d.jam||CFG.sesi[S.sesi];$('raw').value=S.raw;syncCtl();$('work').classList.remove('hidden');renderCards()}
  }catch(e){}
  connect();
})();
</script>
</body>
</html>
