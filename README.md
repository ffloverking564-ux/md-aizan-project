# md-aizan-project
This is MD Aizan's first project website.<!-- Advanced Criminal Database Demo (single-file) - paste entire content here -->
<!doctype html>
<html lang="en" itemscope itemtype="https://schema.org/WebPage">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Criminal Database Demo Portal | By MD AIZAN</title>
  <meta name="description" content="Advanced criminal records demo portal with police login (OTP simulation), court-verified entry, searchable records, and audit log. Created by MD AIZAN." />
  <meta name="keywords" content="Criminal Database Demo, Court Verified, Police Portal, OTP Login, Audit Log, MD AIZAN" />
  <meta name="author" content="MD AIZAN" />
  <meta name="robots" content="index, follow" />
  <link rel="canonical" href="CANONICAL_URL_HERE" />
  <meta property="og:type" content="website" />
  <meta property="og:title" content="Criminal Database Demo Portal | By MD AIZAN" />
  <meta property="og:description" content="Police login (OTP simulation), court-verified records, searchable table, audit log. Demo by MD AIZAN." />
  <meta property="og:url" content="CANONICAL_URL_HERE" />
  <meta property="og:image" content="CANONICAL_URL_HERE/og-image.jpg" />
  <meta name="twitter:card" content="summary_large_image" />
  <meta name="twitter:title" content="Criminal Database Demo Portal | By MD AIZAN" />
  <meta name="twitter:description" content="Advanced criminal database demo. Created by MD AIZAN." />
  <meta name="twitter:image" content="CANONICAL_URL_HERE/og-image.jpg" />
  <script type="application/ld+json">
  {
    "@context": "https://schema.org",
    "@type": "WebSite",
    "name": "Criminal Database Demo Portal",
    "url": "CANONICAL_URL_HERE",
    "creator": {"@type": "Person", "name": "MD AIZAN"},
    "description": "Advanced criminal records demo with OTP login simulation and court-verified entries. Created by MD AIZAN.",
    "inLanguage": "en",
    "potentialAction": {
      "@type": "SearchAction",
      "target": "CANONICAL_URL_HERE/?q={search_term}",
      "query-input": "required name=search_term"
    }
  }
  </script>
  <style>
    :root{ --bg:#0b1220; --card:#0f172a; --muted:#94a3b8; --text:#e5e7eb; --accent:#22d3ee; --ok:#10b981; --warn:#f59e0b; --danger:#ef4444; --ring:#38bdf8; }
    @media (prefers-color-scheme: light){ :root{ --bg:#f7fafc; --card:#ffffff; --muted:#334155; --text:#0f172a; --accent:#0ea5e9; --ok:#16a34a; --warn:#b45309; --danger:#dc2626; --ring:#38bdf8; } }
    *{box-sizing:border-box} html,body{height:100%} body{margin:0; font:500 16px/1.5 ui-sans-serif, system-ui, -apple-system, Segoe UI, Roboto, Helvetica, Arial; background:linear-gradient(120deg,var(--bg),#0b0f1a 60%); color:var(--text);}
    a{color:var(--accent); text-decoration:none} header{position:sticky; top:0; z-index:20; background:rgba(15,23,42,.85); backdrop-filter: blur(8px); border-bottom:1px solid rgba(148,163,184,.2)}
    .container{width:min(1100px,92vw); margin-inline:auto;} .bar{display:flex; gap:16px; align-items:center; justify-content:space-between; padding:12px 0}
    .brand{display:flex; align-items:center; gap:12px} .badge{width:38px; height:38px; border-radius:10px; background:linear-gradient(135deg,var(--accent),#8b5cf6); display:grid; place-items:center; font-weight:800; color:#0b1220}
    nav{display:flex; gap:10px; flex-wrap:wrap} nav button{background:transparent; border:1px solid rgba(148,163,184,.3); color:var(--text); padding:8px 12px; border-radius:10px; cursor:pointer} nav button.active{border-color:var(--ring); box-shadow:0 0 0 3px rgba(56,189,248,.3)}
    main{padding:24px 0 80px} .grid{display:grid; gap:16px} .card{background:var(--card); border:1px solid rgba(148,163,184,.2); border-radius:18px; padding:18px; box-shadow: 0 10px 35px rgba(2,6,23,.35)} .two{grid-template-columns:1.2fr .8fr}
    .controls{display:flex; gap:12px; flex-wrap:wrap} input, select{background:#0b1220; color:var(--text); border:1px solid rgba(148,163,184,.3); padding:10px 12px; border-radius:10px; outline:none} input:focus, select:focus{border-color:var(--ring); box-shadow:0 0 0 3px rgba(56,189,248,.3)} label{font-size:.9rem; color:var(--muted)} .btn{background:var(--accent); color:#071018; border:0; padding:10px 14px; border-radius:10px; font-weight:700; cursor:pointer} .btn.ghost{background:transparent; color:var(--text); border:1px solid rgba(148,163,184,.35)} .btn.ok{background:var(--ok); color:white} .btn.warn{background:var(--warn); color:black} .btn.danger{background:var(--danger); color:white} .flex{display:flex; gap:12px; align-items:center} .spacer{flex:1}
    table{width:100%; border-collapse:collapse} th,td{padding:10px 8px; border-bottom:1px solid rgba(148,163,184,.2); text-align:left} th{color:var(--muted); font-weight:700} .pill{display:inline-block; padding:4px 8px; border-radius:999px; font-size:.8rem} .pill.ok{background:rgba(16,185,129,.15); color:#34d399} .pill.warn{background:rgba(245,158,11,.15); color:#fbbf24} .pill.danger{background:rgba(239,68,68,.15); color:#f87171}
    footer{border-top:1px solid rgba(148,163,184,.2); background:rgba(15,23,42,.85); backdrop-filter: blur(8px); padding:18px 0;} .foot{display:flex; gap:16px; flex-wrap:wrap; align-items:center; justify-content:space-between} .small{font-size:.9rem; color:var(--muted)}
    .notice{background:rgba(56,189,248,.12); border:1px dashed var(--ring); padding:10px 12px; border-radius:10px;} .hidden{display:none}
  </style>
</head>
<body>
  <header role="banner" aria-label="Top Navigation">
    <div class="container bar">
      <div class="brand" aria-label="Site identity">
        <div class="badge" aria-hidden="true">MD</div>
        <div>
          <div style="font-weight:800; font-size:1.05rem">Criminal Database Demo Portal</div>
          <div class="small">Created by <strong>MD AIZAN</strong> • Demo for presentation only</div>
        </div>
      </div>
      <nav aria-label="Primary">
        <button class="active" data-route="home">Home</button>
        <button data-route="records">Records</button>
        <button data-route="admin">Admin</button>
        <button data-route="about">About</button>
      </nav>
    </div>
  </header>

  <main class="container" id="app" role="main">
    <section id="route-home" class="grid two">
      <div class="card" aria-labelledby="welcomeTitle">
        <h1 id="welcomeTitle" style="margin:0 0 8px">Welcome to the Demo Portal</h1>
        <p class="small">This educational project demonstrates a secure-looking criminal records workflow. <strong>No real data is stored.</strong></p>
        <div class="notice" role="note" aria-label="Legal disclaimer"><strong>Legal Disclaimer:</strong> A person’s details appear here only after a <em>court-verified conviction</em>. This is a demo prototype and must not be used for real identity or FIR management.</div>
        <div style="height:10px"></div>
        <div class="controls">
          <input id="globalSearch" type="search" placeholder="Search records by name, case ID, crime…" aria-label="Search records" />
          <select id="statusFilter" aria-label="Filter by status">
            <option value="">All Status</option>
            <option value="in_jail">In Jail</option>
            <option value="on_bail">On Bail</option>
            <option value="absconding">Absconding</option>
          </select>
          <button class="btn ghost" id="goRecords">Open Records</button>
        </div>
      </div>

      <div class="card" aria-labelledby="loginTitle">
        <h2 id="loginTitle" style="margin:0 0 8px">Police Login (Demo)</h2>
        <p class="small">Use mobile number + OTP simulation. Fingerprint/Face UI are simulated for presentation.</p>
        <form id="loginForm" autocomplete="off">
          <label for="mobile">Registered Mobile Number</label>
          <input id="mobile" inputmode="numeric" pattern="[0-9]{10,}" placeholder="Enter mobile number" required />

          <div class="flex">
            <button type="button" class="btn" id="sendOtpBtn">Send OTP</button>
            <div id="otpSent" class="small hidden" aria-live="polite"></div>
          </div>

          <div id="otpArea" class="hidden">
            <label for="otp">Enter OTP</label>
            <input id="otp" inputmode="numeric" maxlength="6" placeholder="6-digit OTP" />
            <div class="flex">
              <button type="button" class="btn ok" id="verifyOtpBtn">Verify OTP</button>
              <button type="button" class="btn ghost" id="biometricBtn">Use Fingerprint / Face</button>
              <div id="bioMsg" class="small"></div>
            </div>
          </div>

          <div id="loginState" class="small" style="margin-top:8px"></div>
        </form>
      </div>
    </section>

    <section id="route-records" class="grid hidden">
      <div class="card">
        <div class="flex">
          <h2 style="margin:0">Criminal Records (Demo)</h2>
          <div class="spacer"></div>
          <input id="recordsSearch" type="search" placeholder="Search records…" aria-label="Search records" />
        </div>
        <table aria-describedby="recordsHelp">
          <thead>
            <tr>
              <th>Case ID</th>
              <th>Name</th>
              <th>Crime</th>
              <th>Court Verified</th>
              <th>Status</th>
              <th>Added By</th>
              <th>Added On</th>
            </tr>
          </thead>
          <tbody id="recordsBody"></tbody>
        </table>
        <div id="recordsHelp" class="small">Only court-verified convictions are eligible to be listed in this demo.</div>
      </div>
    </section>

    <section id="route-admin" class="grid two hidden">
      <div class="card">
        <h2 style="margin-top:0">Add New Record (Admin)</h2>
        <form id="addForm" autocomplete="off">
          <label for="caseId">Case ID *</label>
          <input id="caseId" required placeholder="e.g., CR-2025-001" />

          <label for="fullName">Full Name *</label>
          <input id="fullName" required placeholder="Person’s full name" />

          <label for="crime">Crime *</label>
          <input id="crime" required placeholder="e.g., Theft" />

          <label for="status">Status *</label>
          <select id="status" required>
            <option value="">Select…</option>
            <option value="in_jail">In Jail</option>
            <option value="on_bail">On Bail</option>
            <option value="absconding">Absconding</option>
          </select>

          <div class="notice">
            <label class="flex" for="courtVerified">
              <input id="courtVerified" type="checkbox" />
              <span><strong>Confirm court-verified conviction</strong> (required to register).</span>
            </label>
          </div>

          <div class="flex">
            <button type="submit" class="btn ok">Add Record</button>
            <button type="reset" class="btn ghost">Reset</button>
            <div id="formMsg" class="small"></div>
          </div>
        </form>
      </div>

      <div class="card">
        <h3 style="margin-top:0">Audit Log</h3>
        <div id="auditLog" class="small" style="max-height:300px; overflow:auto"></div>
        <div class="flex" style="margin-top:8px">
          <button class="btn warn" id="exportBtn">Export JSON</button>
          <button class="btn danger" id="wipeBtn">Wipe Demo Data</button>
          <div class="spacer"></div>
          <span class="small">Logged in as: <span id="loggedUser">Guest</span></span>
        </div>
      </div>
    </section>

    <section id="route-about" class="grid hidden">
      <div class="card">
        <h2 style="margin:0 0 8px">About this Demo</h2>
        <p>This project is an educational prototype that demonstrates user flows for law enforcement portals. It is <strong>not</strong> connected to any government database and must not be used for real records.</p>
        <ul>
          <li>Owner/Developer: <strong>MD AIZAN</strong></li>
          <li>Features: Police login (OTP simulation), biometric UI, court-verified entry, searchable records, audit log.</li>
          <li>Tech: HTML, CSS, Vanilla JavaScript (single file, CodePen-ready).</li>
        </ul>
      </div>
      <div class="card">
        <h3 style="margin:0 0 8px">How indexing on Google works (summary)</h3>
        <ol class="small">
          <li>Host this page on your own domain (or GitHub Pages/Netlify) and set the <code>&lt;link rel="canonical"&gt;</code> to your live URL.</li>
          <li>Ensure <code>&lt;meta name="robots" content="index, follow"&gt;</code> is present (already added).</li>
          <li>Create a basic <code>robots.txt</code> and <code>sitemap.xml</code> on your domain (example added below as text).</li>
          <li>Verify your domain in Google Search Console and submit the sitemap.</li>
          <li>Add clear textual content (done), unique title/description (done), and internal links (nav).</li>
        </ol>
        <details>
          <summary>robots.txt (sample)</summary>
          <pre>User-agent: *\nAllow: /\nSitemap: https://your-domain.example/sitemap.xml</pre>
        </details>
        <details>
          <summary>sitemap.xml (sample)</summary>
          <pre>&lt;?xml version="1.0" encoding="UTF-8"?&gt;\n&lt;urlset xmlns="http://www.sitemaps.org/schemas/sitemap/0.9"&gt;\n  &lt;url&gt;&lt;loc&gt;https://your-domain.example/&lt;/loc&gt;&lt;changefreq&gt;weekly&lt;/changefreq&gt;&lt;priority&gt;1.0&lt;/priority&gt;&lt;/url&gt;\n&lt;/urlset&gt;</pre>
        </details>
      </div>
    </section>
  </main>

  <footer role="contentinfo">
    <div class="container foot">
      <div class="small">© <span id="year"></span> Criminal Database Demo • Created by <strong>MD AIZAN</strong>. All names/data shown here are fictional for demonstration.</div>
      <a class="small" href="#about" data-route-link="about">About</a>
    </div>
  </footer>

  <script>
  const $=(s)=>document.querySelector(s),$$=(s)=>document.querySelectorAll(s);
  const store={get key(){return 'demo_crdb_v1';},read(){try{return JSON.parse(localStorage.getItem(this.key))||{users:[],records:[],audit:[]};}catch(e){return {users:[],records:[],audit:[]};}},write(d){localStorage.setItem(this.key,JSON.stringify(d));},wipe(){localStorage.removeItem(this.key);}};
  const nowStr=()=>new Date().toLocaleString();
  function audit(msg){const d=store.read();d.audit.unshift(`[${nowStr()}] ${msg}`);store.write(d);renderAudit();}
  function ensureSeed(){const d=store.read();if(!d.users.length){d.users.push({mobile:'9999999999',name:'Demo Officer',role:'police'});store.write(d);}if(!d.records.length){d.records.push({caseId:'CR-2025-000',name:'Sample Person',crime:'Theft (demo)',courtVerified:true,status:'in_jail',addedBy:'System',addedOn:new Date().toISOString()});store.write(d);}}
  function showRoute(id){$$('nav button').forEach(b=>b.classList.remove('active'));$$('section[id^="route-"]').forEach(s=>s.classList.add('hidden'));$(`#route-${id}`).classList.remove('hidden');$$(`nav button[data-route="${id}"]`).forEach(b=>b.classList.add('active'));if(id==='records') renderRecords();if(id==='admin') renderAudit();history.replaceState(null,'',`#${id}`);}
  $$('nav button').forEach(btn=> btn.addEventListener('click', ()=> showRoute(btn.dataset.route)));
  $$('[data-route-link]').forEach(a=> a.addEventListener('click', (e)=>{e.preventDefault();showRoute(a.getAttribute('data-route-link'));}));
  $('#goRecords').addEventListener('click', ()=> showRoute('records'));
  function routeFromHash(){const r=location.hash.replace('#','')||'home';showRoute(r);}
  let session={logged:false,mobile:null,officer:'Guest'},currentOtp=null;
  $('#sendOtpBtn').addEventListener('click', ()=>{const mobile=$('#mobile').value.trim();if(!/^[0-9]{10,}$/.test(mobile)){$('#loginState').textContent='Enter a valid 10+ digit mobile number.';return;}const data=store.read();const user=data.users.find(u=>u.mobile===mobile);if(!user){$('#loginState').textContent='No police account found for this number (demo).';return;}currentOtp=String(Math.floor(100000+Math.random()*900000));$('#otpSent').classList.remove('hidden');$('#otpSent').textContent=`OTP sent (demo): ${currentOtp}`;$('#otpArea').classList.remove('hidden');$('#loginState').textContent='';});
  $('#verifyOtpBtn').addEventListener('click', ()=>{const code=$('#otp').value.trim();if(code && currentOtp && code===currentOtp){const mobile=$('#mobile').value.trim();const data=store.read();const user=data.users.find(u=>u.mobile===mobile);session={logged:true,mobile,officer: user?.name || 'Officer'};$('#loggedUser').textContent=session.officer;$('#loginState').textContent='Login success.';audit(`Login success for ${session.officer} (${mobile}).`);} else {$('#loginState').textContent='Invalid OTP (demo).';audit('Failed OTP attempt.');}});
  $('#biometricBtn').addEventListener('click', async ()=>{$('#bioMsg').textContent='Attempting biometric verification…';setTimeout(()=>{$('#bioMsg').textContent='Fingerprint/Face verified (demo). You may proceed to enter OTP.';audit('Biometric UI verified (demo).');},900);});
  function renderRecords(){const data=store.read();const q=($('#recordsSearch').value||$('#globalSearch').value||'').toLowerCase();const f=$('#statusFilter').value;const rows=data.records.filter(r=>{const hit=`${r.caseId} ${r.name} ${r.crime} ${r.status}`.toLowerCase().includes(q);const okStatus=f? r.status===f:true;return hit && okStatus;}).map(r=>{const court=r.courtVerified?'<span class="pill ok">Yes</span>':'<span class="pill danger">No</span>';const statusClass=r.status==='in_jail'?'ok':r.status==='on_bail'?'warn':'danger';const statusText=r.status==='in_jail'?'In Jail':r.status==='on_bail'?'On Bail':'Absconding';return `<tr><td>${r.caseId}</td><td>${r.name}</td><td>${r.crime}</td><td>${court}</td><td><span class="pill ${statusClass}">${statusText}</span></td><td>${r.addedBy||'—'}</td><td>${new Date(r.addedOn).toLocaleString()}</td></tr>`;}).join('');$('#recordsBody').innerHTML=rows||'<tr><td colspan="7" class="small">No matching records.</td></tr>';}
  $('#recordsSearch').addEventListener('input', renderRecords);
  $('#globalSearch').addEventListener('input', renderRecords);
  $('#statusFilter').addEventListener('change', ()=>{ renderRecords(); showRoute('records'); });
  $('#addForm').addEventListener('submit', (e)=>{e.preventDefault();if(!session.logged){$('#formMsg').textContent='Login required (Police only).';return;}if(!$('#courtVerified').checked){$('#formMsg').textContent='Court-verified checkbox is required.';return;}const rec={caseId:$('#caseId').value.trim(),name:$('#fullName').value.trim(),crime:$('#crime').value.trim(),status:$('#status').value,courtVerified:true,addedBy:session.officer,addedOn:new Date().toISOString()};if(!rec.caseId||!rec.name||!rec.crime||!rec.status){$('#formMsg').textContent='All fields are required.';return;}const data=store.read();data.records.unshift(rec);store.write(data);audit(`Record added by ${session.officer}: ${rec.caseId} / ${rec.name}`);$('#addForm').reset();$('#courtVerified').checked=false;$('#formMsg').textContent='Record added (demo).';renderRecords();});
  function renderAudit(){const data=store.read();$('#auditLog').innerHTML=data.audit.map(a=>`<div>• ${a}</div>`).join('');}
  $('#exportBtn').addEventListener('click', ()=>{const data=store.read();const blob=new Blob([JSON.stringify(data,null,2)],{type:'application/json'});const url=URL.createObjectURL(blob);const a=document.createElement('a');a.href=url;a.download='demo_criminal_db_export.json';a.click();URL.revokeObjectURL(url);});
  $('#wipeBtn').addEventListener('click', ()=>{if(confirm('This will clear demo data from this browser. Continue?')){store.wipe(); ensureSeed(); renderRecords(); renderAudit();}});
  (function init(){ensureSeed();document.getElementById('year').textContent=new Date().getFullYear();routeFromHash();window.addEventListener('hashchange', routeFromHash);renderRecords();})();
  </script>
</body>
</html>
