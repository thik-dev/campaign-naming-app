<!DOCTYPE html>

<html lang="da">

<head>

&nbsp; <meta charset="utf-8" />

&nbsp; <meta name="viewport" content="width=device-width, initial-scale=1" />

&nbsp; <title>Kampagnenavn-generator</title>

&nbsp; <style>

&nbsp;   :root{

&nbsp;     --bg:#0b0f14;

&nbsp;     --panel:#111822;

&nbsp;     --panel-2:#0e1520;

&nbsp;     --text:#e6edf3;

&nbsp;     --muted:#9fb0c0;

&nbsp;     --accent:#4ea1ff;

&nbsp;     --border:#1f2a38;

&nbsp;     --shadow:0 10px 30px rgba(0,0,0,.35);

&nbsp;     --radius:12px;

&nbsp;     --gap:14px;

&nbsp;   }

&nbsp;   \*{box-sizing:border-box}

&nbsp;   body{

&nbsp;     margin:0;

&nbsp;     font-family:Segoe UI, Roboto, Helvetica, Arial, sans-serif;

&nbsp;     background:radial-gradient(1200px 800px at 70% -10%, #16314f 0%, transparent 60%),var(--bg);

&nbsp;     color:var(--text);

&nbsp;     line-height:1.4;

&nbsp;     padding:24px;

&nbsp;   }

&nbsp;   .app{max-width:980px;margin:0 auto}

&nbsp;   header{display:flex;justify-content:space-between;align-items:center;margin-bottom:20px}

&nbsp;   h1{font-size:1.6rem;margin:0}

&nbsp;   .card{background:linear-gradient(180deg,var(--panel) 0%,var(--panel-2) 100%);

&nbsp;     border:1px solid var(--border);border-radius:var(--radius);box-shadow:var(--shadow);padding:18px}

&nbsp;   label{display:block;font-weight:600;margin:4px 0 6px;color:var(--muted)}

&nbsp;   input,select{width:100%;padding:10px;border-radius:8px;border:1px solid var(--border);

&nbsp;     background:#0b1320;color:var(--text)}

&nbsp;   button{border:1px solid var(--border);background:#1a2a40;color:var(--text);

&nbsp;     border-radius:8px;padding:10px 14px;cursor:pointer;font-weight:600;margin-right:6px}

&nbsp;   button.primary{background:#0f5bd6}

&nbsp;   .output{font-family:monospace;background:#08101a;border:1px solid var(--border);

&nbsp;     border-radius:8px;padding:12px;margin-top:8px;min-height:2.5rem}

&nbsp;   .error{color:#ffd166;display:none}

&nbsp;   .error.show{display:block}

&nbsp; </style>

</head>

<body>

<div class="app">

&nbsp; <header><h1>🧩 Kampagnenavn-generator</h1></header>



&nbsp; <div class="card">

&nbsp;   <label>Struktur</label>

&nbsp;   <label><input type="radio" name="level" value="1" checked> Niveau 1 – Standard</label>

&nbsp;   <label><input type="radio" name="level" value="2"> Niveau 2 – Udvidet</label>



&nbsp;   <label>Brand</label>

&nbsp;   <select id="brand">

&nbsp;     <option value="">– vælg –</option>

&nbsp;     <option>Oticon</option><option>Bernafon</option><option>Philips</option>

&nbsp;   </select>



&nbsp;   <label>Country</label>

      <input id="country" type="text" placeholder="fx. SMB, IT Leaders"/>



&nbsp;   <label>B2B/B2C</label>

&nbsp;   <select id="b2">

&nbsp;     <option value="">– vælg –</option>

&nbsp;     <option>B2B</option><option>B2C</option>

&nbsp;   </select>



&nbsp;   <label>Campaign Name</label>

&nbsp;   <input id="campaign" type="text" placeholder="fx. Spring Sale"/>



&nbsp;   <label>Purpose</label>

&nbsp;   <input id="purpose" type="text" placeholder="fx. Awareness"/>



&nbsp;   <div id="extra" style="display:none">

&nbsp;     <label>Topic</label>

&nbsp;     <input id="topic" type="text" placeholder="fx. AI, Compliance"/>



&nbsp;     <label>Audience</label>

&nbsp;     <input id="audience" type="text" placeholder="fx. SMB, IT Leaders"/>



&nbsp;     <label>Need segmentation (valgfri)</label>

&nbsp;     <input id="need" type="text" placeholder="fx. Problem-aware"/>



&nbsp;     <label>Content type (valgfri)</label>

&nbsp;     <input id="ctype" type="text" placeholder="fx. Webinar"/>



&nbsp;     <label>Funnel Step Number</label>

&nbsp;     <select id="funnel">

&nbsp;       <option value="">– vælg –</option>

&nbsp;       <option>1</option><option>2</option><option>3</option><option>4</option><option>5</option>

&nbsp;     </select>

&nbsp;   </div>



&nbsp;   <p class="error" id="err">Udfyld alle obligatoriske felter.</p>



&nbsp;   <button class="primary" id="gen">Generér navn</button>

&nbsp;   <button id="copy">Kopiér</button>



&nbsp;   <div class="output" id="out"></div>

&nbsp; </div>

</div>



<script>

const $=id=>document.getElementById(id);

function build(){

&nbsp; const lvl=document.querySelector('input\[name="level"]:checked').value;

&nbsp; const parts=\[

&nbsp;   $("#brand").value,

&nbsp;   $("#country").value,

1. &nbsp;   $("#b2").value,

&nbsp;   $("#campaign").value,

&nbsp;   $("#purpose").value

&nbsp; ];

&nbsp; if(lvl==="2"){

&nbsp;   parts.push($("#topic").value,$("#audience").value);

&nbsp;   if($("#need").value)parts.push($("#need").value);

&nbsp;   if($("#ctype").value)parts.push($("#ctype").value);

&nbsp;   parts.push($("#funnel").value);

&nbsp; }

&nbsp; return parts.filter(Boolean).join(" - ");

}

function validate(){

&nbsp; const lvl=document.querySelector('input\[name="level"]:checked').value;

&nbsp; const base=$("#brand").value\&\&$("#country").value\&\&$("#b2").value\&\&$("#campaign").value\&\&$("#purpose").value;

&nbsp; if(lvl==="1")return base;

&nbsp; return base\&\&$("#topic").value\&\&$("#audience").value\&\&$("#funnel").value;

}

function toggleExtra(){

&nbsp; $("#extra").style.display=document.querySelector('input\[name="level"]:checked').value==="2"?"block":"none";

}

document.querySelectorAll('input\[name="level"]').forEach(r=>r.addEventListener("change",toggleExtra));

toggleExtra();



$("#gen").onclick=()=>{

&nbsp; if(!validate()){ $("#err").classList.add("show"); $("#out").textContent=""; return; }

&nbsp; $("#err").classList.remove("show");

&nbsp; $("#out").textContent=build();

};

$("#copy").onclick=async()=>{

&nbsp; const txt=$("#out").textContent.trim();

&nbsp; if(!txt)return;

&nbsp; try{await navigator.clipboard.writeText(txt); alert("Kopieret ✅");}

&nbsp; catch(e){alert("Kunne ikke kopiere automatisk – marker og kopier manuelt.");}

};

</script>

</body>

</html>



