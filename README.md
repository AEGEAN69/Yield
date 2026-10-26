<!DOCTYPE html>
<html lang="th">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1, viewport-fit=cover">
<title>AEGEAN ต้นทุนผลไม้</title>
<link href="https://fonts.googleapis.com/css2?family=IBM+Plex+Sans+Thai:wght@400;500;700&display=swap" rel="stylesheet">
<style>
:root{--bg:#EDF5EE;--card:#fff;--ink:#12301E;--mut:#5C7364;--line:#D3E3D7;--pri:#1B7F4F;--onpri:#fff;--bad:#B3261E;--badbg:#FBE4E2;--ok:#17653F;--okbg:#DDF3E5;--inp:#F6F8FC;
color-scheme:light dark;box-sizing:border-box;padding-top:env(safe-area-inset-top,0px);padding-bottom:env(safe-area-inset-bottom,0px)}
@media (prefers-color-scheme:dark){:root:not([data-theme="light"]){--bg:#0C1426;--card:#142038;--ink:#E7ECF7;--mut:#9AA8C6;--line:#27355A;--pri:#7FA2F5;--onpri:#0A1228;--bad:#FF9A92;--badbg:#3A1C1E;--ok:#7BDBA5;--okbg:#17372A;--inp:#0F1A30}}
:root[data-theme="dark"]{--bg:#0C1426;--card:#142038;--ink:#E7ECF7;--mut:#9AA8C6;--line:#27355A;--pri:#7FA2F5;--onpri:#0A1228;--bad:#FF9A92;--badbg:#3A1C1E;--ok:#7BDBA5;--okbg:#17372A;--inp:#0F1A30}
html{scroll-padding-top:env(safe-area-inset-top,0px)}
*{box-sizing:border-box}
body{margin:0;background:var(--bg);color:var(--ink);font:16px/1.5 "IBM Plex Sans Thai",system-ui,sans-serif;padding-bottom:84px}
.hd{max-width:640px;margin:0 auto;padding:12px 14px 0;display:flex;align-items:center;gap:10px}
.hd>div{flex:1}.lg{width:46px;height:46px;border-radius:50%;background:#fff;object-fit:contain;border:1px solid var(--line)}
.br{font-size:22px;letter-spacing:.14em;font-weight:700}
main{max-width:640px;margin:0 auto;padding:12px 14px}
h1{font-size:20px;margin:4px 0 2px}h2{font-size:17px;margin:0 0 10px}
.sub{color:var(--mut);font-size:14px;margin:0 0 12px}
.card{background:var(--card);border:1px solid var(--line);border-radius:14px;padding:14px;margin-bottom:12px}
.grid{display:grid;grid-template-columns:1fr 1fr;gap:10px;margin-top:10px}
label{display:block;font-size:13px;color:var(--mut)}
input,select{width:100%;margin-top:3px;padding:10px;font:inherit;color:var(--ink);background:var(--inp);border:1px solid var(--line);border-radius:9px}
input:focus,select:focus,button:focus-visible{outline:2px solid var(--pri);outline-offset:1px}
.top{display:flex;gap:10px;align-items:center}.top input{font-weight:700;font-size:17px;margin:0}
.ph{width:64px;height:64px;border-radius:12px;object-fit:cover;border:1px solid var(--line);flex:none}
.pb{width:64px;height:64px;border-radius:12px;border:1px dashed var(--mut);display:flex;align-items:center;justify-content:center;font-size:12px;color:var(--mut);text-align:center;cursor:pointer;flex:none;overflow:hidden;position:relative}
.pb input{position:absolute;inset:0;opacity:0;cursor:pointer;margin:0;height:100%}
.res{margin-top:12px;border-radius:12px;padding:12px;background:var(--inp);border:1px solid var(--line)}
.big{font-size:30px;font-weight:700;line-height:1.1}.u{font-size:14px;font-weight:400;color:var(--mut)}
.row{display:flex;justify-content:space-between;gap:8px;padding:5px 0;border-bottom:1px dashed var(--line);font-size:15px}.row:last-child{border:0}
.chip{display:inline-block;padding:3px 10px;border-radius:99px;font-size:13px;font-weight:500}.ok{background:var(--okbg);color:var(--ok)}.bad{background:var(--badbg);color:var(--bad)}
.neg{color:var(--bad)}.pos{color:var(--ok)}
button{font:inherit;border:0;border-radius:10px;padding:10px 14px;cursor:pointer;background:var(--pri);color:var(--onpri);font-weight:500}
button.g{background:transparent;color:var(--mut);border:1px solid var(--line)}button.x{background:transparent;color:var(--bad);padding:4px 8px}
.ic{padding:9px;display:flex}.ic svg{width:24px;height:24px}
.bar{display:flex;gap:8px;margin-top:10px;flex-wrap:wrap}
nav{position:fixed;left:0;right:0;bottom:0;display:flex;background:var(--card);border-top:1px solid var(--line);padding:6px 6px calc(6px + env(safe-area-inset-bottom,0px));overflow:x;align-items:flex-end}
nav button{flex:1 1 0;min-width:0;background:transparent;color:var(--mut);padding:8px 2px;font-size:12px;white-space:nowrap}
nav button.on{background:var(--okbg);color:var(--ok);font-weight:700}
.empty{text-align:center;color:var(--mut);padding:18px 8px}.note{font-size:13px;color:var(--mut);margin-top:8px}
.ent{display:flex;justify-content:space-between;align-items:center;gap:8px;padding:8px 0;border-bottom:1px dashed var(--line);font-size:15px}.ent:last-child{border:0}
.ov{position:fixed;inset:0;background:rgba(0,0,0,.6);z-index:20;display:flex;flex-direction:column;align-items:center;padding:16px;overflow:auto}
.paper{background:#fff;color:#111;width:min(100%,520px);margin:auto 0;padding:18px;font-size:14px;border-radius:6px;text-align:center}
.paper .rl{display:flex;justify-content:space-between;text-align:left;gap:8px;margin:4px 0}.paper hr{border:0;border-top:1px dashed #111}
.bk{border-radius:50%;width:40px;height:40px;padding:0;display:flex;align-items:center;justify-content:center;flex:none}.bk svg{width:22px;height:22px}
@media print{body *{visibility:hidden}.paper,.paper *{visibility:visible}.ov{position:absolute;inset:auto;left:0;top:0;overflow:visible;background:none;padding:0}.paper{width:100%;margin:0}}
</style>
<script src="https://cdn.jsdelivr.net/npm/qrcode-generator@1.4.4/qrcode.js"></script>
</head>
<body>
<header class="hd">
  <button class="g bk" id="bk" onclick="goBack()" aria-label="ย้อนกลับ"><svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2.5" stroke-linecap="round" stroke-linejoin="round"><path d="M15 5l-7 7 7 7"/></svg></button>
  <div class="lg" style="display:flex;align-items:center;justify-content:center;font-weight:bold;color:var(--pri)">A</div>
  <div><div class="br">AEGEAN</div><div class="note" id="sv" style="margin:0"></div></div>
  <button class="g ic" id="dbtn" onclick="showDoc()" aria-label="สรุปยอดรวม"><svg viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round"><path d="M4 20V10M10 20V4M16 20v-7M22 20H2"/></svg></button>
</header>
<main id="app"></main>
<nav id="nav"></nav>
<script>
var KEY="aegean.v3", tab="fruit", unlocked=true, S={mult:3,dmult:1.5,items:[],log:[],saved:""}, ov="", cart=[];
try{var r0=localStorage.getItem(KEY);if(r0)S=JSON.parse(r0)}catch(e){}

function today(){var d=new Date();return d.getFullYear()+"-"+String(d.getMonth()+1).padStart(2,"0")+"-"+String(d.getDate()).padStart(2,"0")}
function esc(s){return String(s==null?"":s).replace(/[&<>"]/g,function(c){return{"&":"&amp;","<":"&lt;",">":"&gt;",'"':"&quot;"}[c]})}
function fmt(n){return isFinite(n)?Number(n).toLocaleString("th-TH",{maximumFractionDigits:2}):"-"}
function B(n){return(n<0?"-":"")+"฿"+fmt(Math.abs(n))}
function num(v){var n=parseFloat(v);return isFinite(n)?n:0}
function find(id){return S.items.filter(function(x){return x.id===id})[0]}

function save(){
  S.saved=new Date().toLocaleTimeString("th-TH");
  try{
    localStorage.setItem(KEY,JSON.stringify(S));
    document.getElementById("sv").textContent="บันทึกอัตโนมัติล่าสุด "+S.saved;
  }catch(e){
    document.getElementById("sv").textContent="บันทึกไม่ได้ พื้นที่เต็ม (รูปภาพใหญ่เกินไป)";
  }
}

function calc(p){
  var yld=p.wB>0?p.wA/p.wB*100:0,boxes=p.boxG>0?p.wA/p.boxG:0,cpb=boxes>0?(p.buy+(p.inb||0))/boxes:0;
  var shop=p.sellOv>0?p.sellOv:Math.ceil(cpb*S.mult),del=Math.ceil(shop*S.dmult),be=cpb+p.extra+(p.ovh||0),prof=shop-be;
  return{yld:yld,boxes:boxes,cpb:cpb,shop:shop,del:del,be:be,prof:prof,lot:prof*boxes}
}

function pkg(p){return p.boxG>0?calc(p).shop*1000/p.boxG:0}
function R(a,b){return'<div class="row"><span>'+a+'</span><b>'+b+'</b></div>'}

function resHTML(p){
  var c=calc(p);
  if(!c.boxes)return'<div class="note" style="margin:0">กรอกราคาซื้อ น้ำหนักก่อน-หลังปอก และน้ำหนักต่อกล่อง ระบบจะคำนวณให้</div>';
  return'<div class="big">'+B(c.shop)+'<span class="u"> ต่อกล่อง หน้าร้าน</span></div>'
    +R("ได้เนื้อหลังปอก (yield)",fmt(c.yld)+"%")
    +R("น้ำหนักหลังปอก",fmt(p.wA)+" กรัม")
    +R("แบ่งขายได้","≈ "+fmt(c.boxes)+" กล่อง (กล่องละ "+fmt(p.boxG)+" กรัม)")
    +R("ต้นทุนรวมต่อกล่อง",B(c.be))
    +R("กำไรต่อกล่อง",'<span class="'+(c.prof<0?"neg":"pos")+'">'+B(c.prof)+'</span>')
    +R("กำไรรวมทั้งชุด",'<span class="'+(c.prof<0?"neg":"pos")+'">'+B(c.lot)+'</span>');
}

function fN(p,k,l){return'<label>'+l+'<input type="number" inputmode="decimal" min="0" step="any" value="'+(p[k]||"")+'" oninput="up(\''+p.id+'\',\''+k+'\',this.value)"></label>'}
function fT(p,k,l){return'<label>'+l+'<input value="'+esc(p[k])+'" oninput="ups(\''+p.id+'\',\''+k+'\',this.value)"></label>'}

function ups(id,k,v){var p=find(id);if(p){p[k]=v;save()}}
function up(id,k,v){var p=find(id);if(!p)return;p[k]=num(v);save();var r=document.getElementById("r-"+id);if(r)r.innerHTML=resHTML(p)}
function gset(k,v){S[k]=num(v);save();render()}

function addItem(){
  S.items.push({id:"i"+Date.now(),name:"",code:String(Date.now()).slice(-4),buy:0,wB:0,wA:0,boxG:0,extra:0,ovh:0});
  save(); render();
}
function delItem(id){if(!confirm("ลบผลไม้นี้?"))return;S.items=S.items.filter(function(x){return x.id!==id});save();render()}

function fruitTab(){
  var h='<h1>ต้นทุนและราคาผลไม้</h1>'
    +'<div class="card"><h2>ตัวคูณราคา</h2><div class="grid" style="margin:0">'
    +'<label>ราคาหน้าร้าน<input type="number" inputmode="decimal" value="'+S.mult+'" oninput="gset(\'mult\',this.value)"></label>'
    +'<label>ราคาเดลิเวอรี<input type="number" inputmode="decimal" value="'+S.dmult+'" oninput="gset(\'dmult\',this.value)"></label>'
    +'</div></div>';
  if(!S.items.length)h+='<div class="empty">ยังไม่มีผลไม้ กด "เพิ่มผลไม้" ด้านล่าง</div>';
  S.items.forEach(function(p){
    h+='<div class="card"><div class="top">'
      +'<input value="'+esc(p.name)+'" placeholder="ชื่อผลไม้" oninput="ups(\''+p.id+'\',\'name\',this.value)"></div>'
      +'<div class="grid">'+fN(p,"buy","ราคาซื้อรวม (บาท)")+fN(p,"wB","น้ำหนักก่อนปอก (กรัม)")+fN(p,"wA","น้ำหนักหลังปอก (กรัม)")+fN(p,"boxG","น้ำหนักต่อกล่อง (กรัม)")+fN(p,"extra","ค่ากล่อง/อุปกรณ์ (บาท)")+fN(p,"ovh","ค่าใช้จ่ายอื่นๆ (บาท)")+'</div>'
      +'<div class="res" id="r-'+p.id+'">'+resHTML(p)+'</div>'
      +'<div class="bar"><button class="x" onclick="delItem(\''+p.id+'\')">ลบ</button></div></div>';
  });
  return h+'<button onclick="addItem()" style="width:100%">เพิ่มผลไม้</button>';
}

function posTab(){
  var h='<h1>ขายหน้าร้าน</h1><div class="card"><p class="sub">เลือกผลไม้เพื่อจำหน่าย</p>';
  S.items.forEach(function(p){
    if(!p.boxG)return;
    h+='<div class="ent"><div><b>'+esc(p.name||"ไม่ระบุชื่อ")+'</b><div class="note">ราคา ฿'+fmt(pkg(p))+'/กก.</div></div>'
      +'<button onclick="addCart(\''+p.id+'\')">หยิบใส่บิล</button></div>';
  });
  h+='</div><div class="card"><h2>บิลปัจจุบัน</h2>';
  if(!cart.length)return h+'<div class="empty">ยังไม่มีสินค้าในบิล</div></div>';
  var t=0;
  cart.forEach(function(c,i){t+=c.price;h+='<div class="ent"><div>'+esc(c.name)+'</div><div><b>'+B(c.price)+'</b><button class="x" onclick="cart.splice('+i,1);render()">ลบ</button></div></div>'});
  return h+'<div class="big" style="margin-top:10px">'+B(t)+'</div><div class="bar"><button onclick="checkout()">ชำระเงิน</button><button class="g" onclick="cart=[];render()">ล้าง</button></div></div>';
}

function addCart(id){
  var p=find(id); if(!p)return;
  cart.push({name:p.name||"ผลไม้",price:pkg(p)});
  render();
}

function checkout(){
  if(!cart.length)return;
  cart.forEach(function(c){S.log.push({date:today(),name:c.name,price:c.price})});
  cart=[]; save(); alert("บันทึกการขายเรียบร้อย"); render();
}

function repTab(){
  var rev=0; S.log.forEach(function(e){rev+=e.price});
  return'<h1>รายงานยอดขาย</h1><div class="card"><div class="big">'+B(rev)+'</div><div class="note">ยอดขายสะสมทั้งหมด</div></div>';
}

function showDoc(){
  ov='<b style="font-size:18px">AEGEAN</b><br>สรุปภาพรวมระบบ<hr><p>จำนวนรายการผลไม้: '+S.items.length+' รายการ</p>';
  render();
}

function goBack(){ov=""; render();}

function render(){
  var html="";
  if(tab==="fruit") html=fruitTab();
  else if(tab==="pos") html=posTab();
  else if(tab==="rep") html=repTab();
  else html=fruitTab();

  if(ov) html+='<div class="ov"><div class="paper">'+ov+'</div><div class="bar"><button onclick="goBack()">ปิด</button></div></div>';
  
  document.getElementById("app").innerHTML=html;
  document.getElementById("nav").innerHTML='<button class="'+(tab==="fruit"?"on":"")+'" onclick="tab=\'fruit\';render()">ผลไม้</button>'
    +'<button class="'+(tab==="pos"?"on":"")+'" onclick="tab=\'pos\';render()">ขาย</button>'
    +'<button class="'+(tab==="rep"?"on":"")+'" onclick="tab=\'rep\';render()">รายงาน</button>';
}

render();
</script>
</body>
</html>
