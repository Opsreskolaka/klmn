<!DOCTYPE html>
<html lang="id">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0, viewport-fit=cover">
<title>Daftar Hadir Pengajian Digital</title>
<link rel="manifest" id="manifestLink">
<meta name="theme-color" content="#0f5132">
<script src="https://cdnjs.cloudflare.com/ajax/libs/qrcodejs/1.0.0/qrcode.min.js"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/jsQR/1.4.0/jsQR.min.js"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/Chart.js/4.4.1/chart.umd.min.js"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/jsbarcode/3.11.5/JsBarcode.all.min.js"></script>
<script src="https://cdnjs.cloudflare.com/ajax/libs/jspdf/2.5.1/jspdf.umd.min.js"></script>
<style>
:root{
  --hijau-tua:#0f5132;
  --hijau:#146c43;
  --hijau-muda:#1d8a52;
  --emas:#d4af37;
  --emas-muda:#f0d97d;
  --krem:#faf7f0;
  --abu:#6b7280;
  --abu-muda:#e5e7eb;
  --merah:#dc3545;
  --kuning:#f0a500;
  --biru:#2563eb;
  --radius:14px;
  --shadow:0 4px 16px rgba(15,81,50,.10);
  font-size:16px;
}
*{box-sizing:border-box;}
body{margin:0;padding:0;}
body,input,select,textarea,button{
  font-family:'Segoe UI',-apple-system,BlinkMacSystemFont,Roboto,Arial,sans-serif;
}
body{
  background:var(--krem);
  color:#1f2937;
  min-height:100vh;
}
h1,h2,h3,h4{margin:0 0 4px;font-weight:700;}
button{cursor:pointer;font-family:inherit;}
.app{max-width:480px;margin:0 auto;min-height:100vh;background:#fff;position:relative;box-shadow:0 0 40px rgba(0,0,0,.06);display:flex;flex-direction:column;}
@media(min-width:560px){.app{margin:16px auto;min-height:calc(100vh - 32px);border-radius:24px;overflow:hidden;}}

/* ---------- TOPBAR ---------- */
.topbar{
  background:linear-gradient(135deg,var(--hijau-tua),var(--hijau));
  color:#fff;padding:16px 18px;display:flex;align-items:center;gap:12px;
  position:sticky;top:0;z-index:50;
}
.topbar h2{font-size:1.05rem;color:#fff;}
.topbar .icon-btn{background:rgba(255,255,255,.15);border:none;color:#fff;width:36px;height:36px;border-radius:10px;display:flex;align-items:center;justify-content:center;font-size:1.1rem;}
.topbar .spacer{flex:1;}

/* ---------- SCREENS ---------- */
.screen{display:none;flex:1;flex-direction:column;padding-bottom:90px;animation:fadeIn .25s ease;}
.screen.active{display:flex;}
@keyframes fadeIn{from{opacity:0;transform:translateY(6px);}to{opacity:1;transform:none;}}
.content{padding:16px 18px;flex:1;}

/* ---------- LOGIN ---------- */
#screen-login{padding-bottom:0;}
.login-wrap{
  background:linear-gradient(160deg,var(--hijau-tua) 0%,var(--hijau) 55%,var(--hijau-muda) 100%);
  min-height:100vh;color:#fff;display:flex;flex-direction:column;align-items:center;padding:40px 24px;position:relative;overflow:hidden;
}
.login-wrap::after{
  content:"";position:absolute;bottom:0;left:0;right:0;height:120px;
  background:repeating-linear-gradient(90deg,transparent 0 30px, rgba(255,255,255,.06) 30px 32px);
  opacity:.5;
}
.login-logo{width:84px;height:84px;border-radius:50%;background:rgba(255,255,255,.12);display:flex;align-items:center;justify-content:center;font-size:2.4rem;margin:20px 0 14px;border:2px solid var(--emas-muda);overflow:hidden;}
.login-logo img{width:100%;height:100%;object-fit:cover;}
.login-wrap h1{font-size:1.3rem;text-align:center;}
.login-wrap p.sub{color:var(--emas-muda);margin:2px 0 28px;font-size:.85rem;text-align:center;}
.login-card{background:#fff;border-radius:18px;padding:24px 20px;width:100%;max-width:340px;color:#1f2937;box-shadow:0 10px 30px rgba(0,0,0,.25);z-index:2;}
.field{margin-bottom:14px;}
.field label{display:block;font-size:.78rem;color:var(--abu);margin-bottom:5px;font-weight:600;}
.input-icon{position:relative;}
.input-icon input,input.basic,select.basic,textarea.basic{
  width:100%;padding:11px 12px;border:1.5px solid var(--abu-muda);border-radius:10px;font-size:.92rem;background:#fafafa;
}
.input-icon input{padding-right:38px;}
.input-icon button{position:absolute;right:8px;top:50%;transform:translateY(-50%);background:none;border:none;color:var(--abu);font-size:.95rem;}
input:focus,select:focus,textarea:focus{outline:2px solid var(--hijau-muda);background:#fff;}
.btn{
  display:flex;align-items:center;justify-content:center;gap:8px;
  width:100%;padding:12px;border-radius:10px;border:none;font-weight:700;font-size:.93rem;
}
.btn-primary{background:var(--hijau-tua);color:#fff;}
.btn-primary:active{background:var(--hijau);}
.btn-outline{background:#fff;border:1.5px solid var(--abu-muda);color:#374151;}
.btn-danger{background:#fff;color:var(--merah);border:1.5px solid #f1c2c8;}
.btn-gold{background:linear-gradient(135deg,var(--emas),#b8902a);color:#fff;}
.btn-sm{padding:8px 10px;font-size:.8rem;border-radius:8px;}
.row-check{display:flex;align-items:center;justify-content:space-between;margin:6px 0 18px;font-size:.8rem;color:var(--abu);}
.row-check a{color:var(--hijau);text-decoration:none;font-weight:600;}
.login-foot{margin-top:auto;padding-top:24px;color:rgba(255,255,255,.6);font-size:.72rem;text-align:center;z-index:2;}

/* ---------- BOTTOM NAV ---------- */
.bottomnav{
  position:fixed;bottom:0;left:0;right:0;max-width:480px;margin:0 auto;
  background:#fff;border-top:1px solid var(--abu-muda);display:flex;align-items:center;justify-content:space-between;
  padding:8px 10px 10px;z-index:60;
}
.app:not(:has(.bottomnav.show)) .bottomnav{display:none;}
.bottomnav.show{display:flex;}
.navbtn{flex:1;display:flex;flex-direction:column;align-items:center;gap:3px;background:none;border:none;color:var(--abu);font-size:.66rem;font-weight:600;padding:4px 0;}
.navbtn .ic{font-size:1.15rem;}
.navbtn.active{color:var(--hijau-tua);}
.navbtn.fab{margin-top:-22px;}
.navbtn.fab .ic{
  width:50px;height:50px;border-radius:50%;background:var(--hijau-tua);color:#fff;display:flex;align-items:center;justify-content:center;font-size:1.5rem;box-shadow:0 6px 14px rgba(15,81,50,.4);
}

/* ---------- CARDS / COMMON ---------- */
.card{background:#fff;border:1px solid var(--abu-muda);border-radius:var(--radius);padding:14px;margin-bottom:14px;box-shadow:var(--shadow);}
.greet{font-size:1.05rem;margin-bottom:2px;}
.greet-sub{color:var(--abu);font-size:.84rem;margin-bottom:16px;}
.badge{display:inline-block;padding:3px 9px;border-radius:20px;font-size:.68rem;font-weight:700;}
.badge-green{background:#dcfce7;color:#15803d;}
.badge-red{background:#fee2e2;color:#b91c1c;}
.badge-yellow{background:#fef3c7;color:#92400e;}
.badge-blue{background:#dbeafe;color:#1d4ed8;}
.badge-gray{background:#f3f4f6;color:#4b5563;}
.stat-grid{display:grid;grid-template-columns:1fr 1fr;gap:10px;margin-bottom:14px;}
.stat-grid.cols3{grid-template-columns:1fr 1fr 1fr;}
.stat-card{background:#fff;border:1px solid var(--abu-muda);border-radius:12px;padding:10px;text-align:center;}
.stat-card .num{font-size:1.25rem;font-weight:800;color:var(--hijau-tua);}
.stat-card .lbl{font-size:.68rem;color:var(--abu);margin-top:2px;}
.section-title{display:flex;align-items:center;justify-content:space-between;margin:18px 0 10px;}
.section-title h3{font-size:.95rem;}
.link-more{font-size:.78rem;color:var(--hijau);font-weight:600;text-decoration:none;}
.list-item{display:flex;align-items:center;gap:12px;padding:11px 0;border-bottom:1px solid #f1f1f1;}
.list-item:last-child{border-bottom:none;}
.avatar{width:40px;height:40px;border-radius:50%;background:var(--hijau-muda);color:#fff;display:flex;align-items:center;justify-content:center;font-weight:700;flex-shrink:0;font-size:.85rem;}
.list-item .meta{flex:1;min-width:0;}
.list-item .meta .name{font-weight:700;font-size:.88rem;}
.list-item .meta .sub{font-size:.74rem;color:var(--abu);}
.searchbar{display:flex;align-items:center;gap:8px;background:#f3f4f6;border-radius:10px;padding:9px 12px;margin-bottom:10px;}
.searchbar input{flex:1;border:none;background:none;font-size:.86rem;outline:none;}
.chips{display:flex;gap:8px;overflow-x:auto;padding-bottom:4px;margin-bottom:12px;}
.chip{padding:7px 14px;border-radius:20px;background:#f3f4f6;font-size:.78rem;font-weight:600;white-space:nowrap;border:none;color:#374151;}
.chip.active{background:var(--hijau-tua);color:#fff;}
.empty-state{text-align:center;color:var(--abu);padding:40px 10px;font-size:.85rem;}
.fab-add{position:fixed;bottom:80px;right:calc(50% - 240px + 18px);width:52px;height:52px;border-radius:50%;background:var(--hijau-tua);color:#fff;border:none;font-size:1.6rem;box-shadow:0 6px 16px rgba(15,81,50,.4);z-index:55;}
@media(max-width:560px){.fab-add{right:18px;}}
.modal-bg{position:fixed;inset:0;background:rgba(0,0,0,.45);display:none;align-items:flex-end;justify-content:center;z-index:200;}
.modal-bg.show{display:flex;}
.modal{background:#fff;border-radius:18px 18px 0 0;max-width:480px;width:100%;max-height:88vh;overflow-y:auto;padding:18px 18px 24px;animation:slideUp .25s ease;}
@keyframes slideUp{from{transform:translateY(30px);opacity:0;}to{transform:none;opacity:1;}}
.modal-head{display:flex;align-items:center;justify-content:space-between;margin-bottom:14px;}
.modal-head h3{font-size:1rem;}
.modal-head button{background:#f3f4f6;border:none;width:30px;height:30px;border-radius:8px;font-size:1rem;}
.toast{position:fixed;bottom:100px;left:50%;transform:translateX(-50%);background:#1f2937;color:#fff;padding:10px 18px;border-radius:10px;font-size:.82rem;z-index:300;opacity:0;transition:.25s;pointer-events:none;}
.toast.show{opacity:1;}
.gender-toggle{display:flex;gap:10px;}
.gender-toggle label{flex:1;display:flex;align-items:center;justify-content:center;gap:6px;border:1.5px solid var(--abu-muda);border-radius:10px;padding:10px;font-size:.85rem;font-weight:600;}
.gender-toggle input{accent-color:var(--hijau-tua);}
.gender-toggle label.checked{border-color:var(--hijau-tua);background:#ecfdf5;color:var(--hijau-tua);}
canvas.sig-canvas{width:100%;height:220px;border:1.5px dashed var(--abu-muda);border-radius:12px;background:#fff;touch-action:none;}
.tabs{display:flex;gap:6px;margin-bottom:12px;background:#f3f4f6;border-radius:10px;padding:4px;}
.tabs button{flex:1;border:none;background:none;padding:8px;border-radius:8px;font-size:.78rem;font-weight:700;color:var(--abu);}
.tabs button.active{background:#fff;color:var(--hijau-tua);box-shadow:0 1px 3px rgba(0,0,0,.1);}
.qr-box{background:#fff;border:1px solid var(--abu-muda);border-radius:14px;padding:18px;text-align:center;}
.qr-box img,.qr-box canvas{max-width:200px;}
.kv{display:flex;justify-content:space-between;font-size:.84rem;padding:6px 0;border-bottom:1px solid #f4f4f4;}
.kv:last-child{border-bottom:none;}
.kv .k{color:var(--abu);}
.kv .v{font-weight:700;}
.divider{border:none;border-top:1px solid var(--abu-muda);margin:14px 0;}
.copy-row{display:flex;gap:8px;align-items:center;background:#f3f4f6;border-radius:10px;padding:8px 10px;font-size:.78rem;overflow:hidden;}
.copy-row span{flex:1;overflow:hidden;text-overflow:ellipsis;white-space:nowrap;}
.small-muted{font-size:.74rem;color:var(--abu);}
.grid2{display:grid;grid-template-columns:1fr 1fr;gap:10px;}
.upload-box{border:1.5px dashed var(--abu-muda);border-radius:12px;padding:16px;text-align:center;color:var(--abu);font-size:.8rem;cursor:pointer;position:relative;overflow:hidden;}
.upload-box img{max-width:100%;max-height:90px;border-radius:8px;}
.upload-box input{position:absolute;inset:0;opacity:0;cursor:pointer;}
.swatch-row{display:flex;gap:8px;margin-top:6px;}
.swatch{width:26px;height:26px;border-radius:50%;border:2px solid #fff;box-shadow:0 0 0 1px var(--abu-muda);cursor:pointer;}
.swatch.sel{box-shadow:0 0 0 2px var(--hijau-tua);}
.banner-canvas-wrap{background:#111;border-radius:14px;overflow:hidden;display:flex;align-items:center;justify-content:center;margin-bottom:14px;}
table.report-table{width:100%;border-collapse:collapse;font-size:.72rem;}
table.report-table th,table.report-table td{border:1px solid #ddd;padding:5px 6px;text-align:left;}
.hidden{display:none !important;}
.pubwrap{min-height:100vh;background:linear-gradient(160deg,var(--hijau-tua),var(--hijau-muda));padding:24px 16px;}
.pubcard{max-width:440px;margin:0 auto;background:#fff;border-radius:18px;padding:20px;box-shadow:0 10px 30px rgba(0,0,0,.25);}
.pub-head{text-align:center;color:#fff;margin-bottom:18px;}
.pub-head img{width:60px;height:60px;border-radius:50%;background:#fff;padding:4px;margin-bottom:8px;}
.steplabel{font-size:.72rem;color:var(--abu);font-weight:700;text-transform:uppercase;letter-spacing:.04em;margin-bottom:10px;}
.signpad-actions{display:flex;gap:10px;margin-top:10px;}
.lock-banner{background:#fef3c7;color:#92400e;border-radius:10px;padding:10px 12px;font-size:.78rem;text-align:center;margin-bottom:12px;}
.expired-box{text-align:center;padding:60px 20px;color:#fff;}
.expired-box .ic{font-size:3rem;margin-bottom:10px;}
::-webkit-scrollbar{width:0;height:0;}
@media print{
  .app,.bottomnav,.topbar,.fab-add{box-shadow:none !important;}
}
</style>
</head>
<body>

<div class="app" id="app">

  <!-- ================= LOGIN ================= -->
  <div class="screen active" id="screen-login">
    <div class="login-wrap">
      <div class="login-logo" id="loginLogoBox">🕌</div>
      <h1 id="loginOrgName">Majelis Al-Ikhlas</h1>
      <p class="sub" id="loginAppName">Sistem Daftar Hadir Pengajian</p>
      <div class="login-card">
        <div class="field">
          <label>Username</label>
          <div class="input-icon">
            <input type="text" id="loginUser" class="basic" placeholder="Masukkan username" autocomplete="username">
          </div>
        </div>
        <div class="field">
          <label>Password</label>
          <div class="input-icon">
            <input type="password" id="loginPass" class="basic" placeholder="Masukkan password" autocomplete="current-password">
            <button type="button" onclick="togglePass()">👁</button>
          </div>
        </div>
        <div class="row-check">
          <label style="display:flex;align-items:center;gap:6px;"><input type="checkbox" id="rememberMe"> Ingat saya</label>
        </div>
        <button class="btn btn-primary" onclick="doLogin()">Masuk</button>
        <p class="small-muted" style="text-align:center;margin-top:12px;">Default: <b>admin</b> / <b>admin123</b></p>
      </div>
      <div class="login-foot" id="loginFooter">© 2026 Majelis Al-Ikhlas</div>
    </div>
  </div>

  <!-- ================= DASHBOARD ================= -->
  <div class="screen" id="screen-dashboard">
    <div class="topbar">
      <h2>Dashboard</h2>
      <div class="spacer"></div>
      <button class="icon-btn" onclick="goto('settings')">⚙️</button>
    </div>
    <div class="content">
      <div class="greet" id="greetText">Assalamu'alaikum 👋</div>
      <div class="greet-sub">Selamat datang kembali, semoga hari ini penuh berkah</div>

      <div class="card" id="kegiatanHariIniCard"></div>

      <div class="stat-grid">
        <div class="stat-card"><div class="num" id="stTotalKegiatan">0</div><div class="lbl">Kegiatan</div></div>
        <div class="stat-card"><div class="num" id="stTotalPeserta">0</div><div class="lbl">Peserta</div></div>
        <div class="stat-card"><div class="num" id="stHadir">0</div><div class="lbl">Hadir</div></div>
        <div class="stat-card"><div class="num" id="stIzin">0</div><div class="lbl">Izin/Berhalangan</div></div>
        <div class="stat-card"><div class="num" id="stSakit">0</div><div class="lbl">Sakit</div></div>
        <div class="stat-card"><div class="num" id="stAlfa">0</div><div class="lbl">Alfa</div></div>
      </div>

      <div class="card" style="background:linear-gradient(135deg,var(--hijau-tua),var(--hijau));color:#fff;">
        <div style="display:flex;justify-content:space-between;align-items:center;">
          <div>
            <div style="font-size:.78rem;opacity:.85;">Total Infaq</div>
            <div style="font-size:1.4rem;font-weight:800;" id="stInfaqTotal">Rp 0</div>
            <div style="font-size:.74rem;opacity:.8;" id="stInfaqCount">0 Transaksi</div>
          </div>
          <div style="background:rgba(255,255,255,.2);width:46px;height:46px;border-radius:12px;display:flex;align-items:center;justify-content:center;font-size:1.3rem;">💰</div>
        </div>
      </div>

      <div class="card">
        <h4 style="font-size:.88rem;">Grafik Kehadiran (7 Kegiatan Terakhir)</h4>
        <canvas id="chartKehadiran" height="160"></canvas>
      </div>
      <div class="card">
        <h4 style="font-size:.88rem;">Jenis Kelamin</h4>
        <canvas id="chartGender" height="160"></canvas>
      </div>
      <div class="card">
        <h4 style="font-size:.88rem;">Status Peserta</h4>
        <canvas id="chartStatus" height="160"></canvas>
      </div>
    </div>
  </div>

  <!-- ================= KEGIATAN LIST ================= -->
  <div class="screen" id="screen-kegiatan">
    <div class="topbar"><h2>Daftar Kegiatan</h2><div class="spacer"></div><button class="icon-btn" onclick="openKegiatanModal()">＋</button></div>
    <div class="content">
      <div class="searchbar">🔍<input id="searchKegiatan" placeholder="Cari nama kegiatan..." oninput="renderKegiatanList()"></div>
      <div class="chips" id="kategoriChips"></div>
      <div id="kegiatanListWrap"></div>
    </div>
  </div>

  <!-- ================= DETAIL KEGIATAN / ABSENSI ================= -->
  <div class="screen" id="screen-kegiatan-detail">
    <div class="topbar"><button class="icon-btn" onclick="goto('kegiatan')">←</button><h2 id="detailKegiatanName">Detail Kegiatan</h2><div class="spacer"></div><button class="icon-btn" onclick="shareKegiatan()">📤</button></div>
    <div class="content">
      <div class="card" id="detailKegiatanInfo"></div>
      <div class="tabs">
        <button class="active" data-tab="peserta" onclick="switchDetailTab('peserta')">Peserta</button>
        <button data-tab="qr" onclick="switchDetailTab('qr')">QR & Link</button>
        <button data-tab="infaq" onclick="switchDetailTab('infaq')">Infaq</button>
        <button data-tab="laporan" onclick="switchDetailTab('laporan')">Laporan</button>
      </div>
      <div id="tab-peserta">
        <div class="chips" id="filterHadirChips"></div>
        <div id="pesertaListWrap"></div>
      </div>
      <div id="tab-qr" class="hidden"></div>
      <div id="tab-infaq" class="hidden"></div>
      <div id="tab-laporan" class="hidden"></div>
    </div>
  </div>

  <!-- ================= INFAQ GLOBAL ================= -->
  <div class="screen" id="screen-infaq">
    <div class="topbar"><h2>Infaq</h2><div class="spacer"></div><button class="icon-btn" onclick="openInfaqModal()">＋</button></div>
    <div class="content">
      <div class="card" style="background:linear-gradient(135deg,var(--hijau-tua),var(--hijau));color:#fff;">
        <div style="font-size:.78rem;opacity:.85;">Total Infaq</div>
        <div style="font-size:1.5rem;font-weight:800;" id="infaqTotalGlobal">Rp 0</div>
        <div class="grid2" style="margin-top:10px;">
          <div><div style="font-size:.7rem;opacity:.8;">Transaksi</div><div style="font-weight:700;" id="infaqCountGlobal">0</div></div>
          <div><div style="font-size:.7rem;opacity:.8;">Rata-rata</div><div style="font-weight:700;" id="infaqAvgGlobal">Rp 0</div></div>
        </div>
      </div>
      <div class="chips" id="infaqMetodeChips"></div>
      <div id="infaqListWrap"></div>
    </div>
  </div>

  <!-- ================= MENU ================= -->
  <div class="screen" id="screen-menu">
    <div class="topbar"><h2>Menu</h2></div>
    <div class="content">
      <div class="card" style="display:flex;align-items:center;gap:12px;">
        <div class="avatar" style="width:48px;height:48px;font-size:1.1rem;" id="menuUserAvatar">A</div>
        <div><div style="font-weight:700;" id="menuUserName">admin</div><div class="small-muted">Administrator</div></div>
      </div>
      <div class="card" style="padding:0;">
        <div class="list-item" style="padding:14px 14px;cursor:pointer;" onclick="goto('settings')"><span style="font-size:1.1rem;">⚙️</span><div class="meta"><div class="name">Identitas Organisasi</div></div><span>›</span></div>
        <div class="list-item" style="padding:14px 14px;cursor:pointer;" onclick="goto('kategori')"><span style="font-size:1.1rem;">🏷️</span><div class="meta"><div class="name">Kategori Pengajian</div></div><span>›</span></div>
        <div class="list-item" style="padding:14px 14px;cursor:pointer;" onclick="goto('banner')"><span style="font-size:1.1rem;">🖼️</span><div class="meta"><div class="name">Banner & Spanduk</div></div><span>›</span></div>
        <div class="list-item" style="padding:14px 14px;cursor:pointer;" onclick="goto('whatsapp')"><span style="font-size:1.1rem;">💬</span><div class="meta"><div class="name">Kirim WhatsApp</div></div><span>›</span></div>
        <div class="list-item" style="padding:14px 14px;cursor:pointer;" onclick="openAccountModal()"><span style="font-size:1.1rem;">🔐</span><div class="meta"><div class="name">Ubah Username / Password</div></div><span>›</span></div>
        <div class="list-item" style="padding:14px 14px;cursor:pointer;" onclick="exportBackup()"><span style="font-size:1.1rem;">📦</span><div class="meta"><div class="name">Cadangkan Data (Backup JSON)</div></div><span>›</span></div>
        <div class="list-item" style="padding:14px 14px;cursor:pointer;" onclick="document.getElementById('restoreInput').click()"><span style="font-size:1.1rem;">📥</span><div class="meta"><div class="name">Pulihkan Data (Restore JSON)</div></div><span>›</span></div>
        <input type="file" id="restoreInput" accept="application/json" class="hidden" onchange="importBackup(event)">
      </div>
      <button class="btn btn-danger" onclick="doLogout()">🚪 Logout</button>
    </div>
  </div>

  <!-- ================= SETTINGS / IDENTITAS ================= -->
  <div class="screen" id="screen-settings">
    <div class="topbar"><button class="icon-btn" onclick="goto('menu')">←</button><h2>Identitas Organisasi</h2></div>
    <div class="content">
      <div class="field"><label>Logo Organisasi</label><div class="upload-box" id="logoUploadBox">Ketuk untuk unggah logo<input type="file" accept="image/*" onchange="uploadImage(event,'logoOrganisasi','logoUploadBox')"></div></div>
      <div class="field"><label>Lambang Organisasi</label><div class="upload-box" id="lambangUploadBox">Ketuk untuk unggah lambang<input type="file" accept="image/*" onchange="uploadImage(event,'lambangOrganisasi','lambangUploadBox')"></div></div>
      <div class="field"><label>Stempel Organisasi</label><div class="upload-box" id="stempelUploadBox">Ketuk untuk unggah stempel<input type="file" accept="image/*" onchange="uploadImage(event,'stempel','stempelUploadBox')"></div></div>
      <div class="field"><label>Nama Organisasi</label><input class="basic" id="setNamaOrganisasi"></div>
      <div class="field"><label>Nama Masjid</label><input class="basic" id="setNamaMasjid"></div>
      <div class="field"><label>Nama Kelompok</label><input class="basic" id="setNamaKelompok"></div>
      <div class="field"><label>Nama Aplikasi</label><input class="basic" id="setNamaAplikasi"></div>
      <div class="field"><label>Footer</label><input class="basic" id="setFooter"></div>
      <div class="field"><label>Warna Tema</label>
        <div class="swatch-row" id="themeSwatches"></div>
      </div>
      <button class="btn btn-primary" onclick="saveIdentitas()">💾 Simpan Identitas</button>
    </div>
  </div>

  <!-- ================= KATEGORI ================= -->
  <div class="screen" id="screen-kategori">
    <div class="topbar"><button class="icon-btn" onclick="goto('menu')">←</button><h2>Kategori Pengajian</h2><div class="spacer"></div><button class="icon-btn" onclick="openKategoriModal()">＋</button></div>
    <div class="content"><div id="kategoriListWrap"></div></div>
  </div>

  <!-- ================= BANNER ================= -->
  <div class="screen" id="screen-banner">
    <div class="topbar"><button class="icon-btn" onclick="goto('menu')">←</button><h2>Banner & Spanduk</h2></div>
    <div class="content">
      <div class="field"><label>Pilih Kegiatan</label><select class="basic" id="bannerKegiatanSelect" onchange="renderBanner()"></select></div>
      <div class="tabs">
        <button class="active" data-tpl="banner" onclick="switchBannerTpl('banner')">Banner WA</button>
        <button data-tpl="poster" onclick="switchBannerTpl('poster')">Poster</button>
        <button data-tpl="story" onclick="switchBannerTpl('story')">Story</button>
        <button data-tpl="spanduk" onclick="switchBannerTpl('spanduk')">Spanduk</button>
      </div>
      <div class="banner-canvas-wrap"><canvas id="bannerCanvas"></canvas></div>
      <div class="grid2">
        <button class="btn btn-outline" onclick="downloadBanner()">⬇️ Download PNG</button>
        <button class="btn btn-primary" onclick="shareBannerWA()">💬 Bagikan WA</button>
      </div>
    </div>
  </div>

  <!-- ================= WHATSAPP ================= -->
  <div class="screen" id="screen-whatsapp">
    <div class="topbar"><button class="icon-btn" onclick="goto('menu')">←</button><h2>Kirim ke WhatsApp</h2></div>
    <div class="content">
      <div class="field"><label>Pilih Kegiatan</label><select class="basic" id="waKegiatanSelect"></select></div>
      <div class="field"><label>Kirim laporan ke</label>
        <select class="basic" id="waTargetSelect">
          <option value="grup">Grup WhatsApp (link absensi)</option>
          <option value="pj">Penanggung Jawab</option>
          <option value="semua">Semua Peserta (satu per satu)</option>
          <option value="peserta">Peserta Tertentu</option>
        </select>
      </div>
      <div class="field hidden" id="waPesertaSelectWrap"><label>Pilih Peserta</label><select class="basic" id="waPesertaSelect"></select></div>
      <div class="card" id="waPreviewCard"><div class="small-muted" style="white-space:pre-wrap;" id="waPreviewText"></div></div>
      <button class="btn btn-primary" onclick="sendWhatsApp()">💬 Kirim via WhatsApp</button>
    </div>
  </div>

  <!-- ================= LAPORAN GLOBAL ================= -->
  <div class="screen" id="screen-laporan">
    <div class="topbar"><button class="icon-btn" onclick="goto('kegiatan-detail')">←</button><h2>Laporan</h2></div>
    <div class="content" id="laporanContent"></div>
  </div>

  <div class="bottomnav" id="bottomnav">
    <button class="navbtn" data-go="dashboard" onclick="goto('dashboard')"><span class="ic">🏠</span>Dashboard</button>
    <button class="navbtn" data-go="kegiatan" onclick="goto('kegiatan')"><span class="ic">📅</span>Kegiatan</button>
    <button class="navbtn fab" onclick="openKegiatanModal()"><span class="ic">＋</span></button>
    <button class="navbtn" data-go="infaq" onclick="goto('infaq')"><span class="ic">💰</span>Infaq</button>
    <button class="navbtn" data-go="menu" onclick="goto('menu')"><span class="ic">☰</span>Menu</button>
  </div>

</div>

<!-- ============== MODALS ============== -->
<div class="modal-bg" id="modalKegiatan"><div class="modal">
  <div class="modal-head"><h3 id="kegiatanModalTitle">Tambah Kegiatan</h3><button onclick="closeModal('modalKegiatan')">✕</button></div>
  <input type="hidden" id="kegiatanEditId">
  <div class="field"><label>Nama Kegiatan</label><input class="basic" id="fNamaKegiatan"></div>
  <div class="field"><label>Kategori</label><select class="basic" id="fKategori"></select></div>
  <div class="field"><label>Tema</label><input class="basic" id="fTema"></div>
  <div class="grid2">
    <div class="field"><label>Tanggal</label><input type="date" class="basic" id="fTanggal"></div>
    <div class="field"><label>Tempat</label><input class="basic" id="fTempat"></div>
  </div>
  <div class="grid2">
    <div class="field"><label>Jam Mulai</label><input type="time" class="basic" id="fJamMulai"></div>
    <div class="field"><label>Jam Selesai</label><input type="time" class="basic" id="fJamSelesai"></div>
  </div>
  <div class="field"><label>Pemateri</label><input class="basic" id="fPemateri"></div>
  <div class="field"><label>Penanggung Jawab</label><input class="basic" id="fPJ"></div>
  <div class="grid2">
    <div class="field"><label>Dapukan PJ</label><input class="basic" id="fDapukanPJ"></div>
    <div class="field"><label>No. WA PJ</label><input class="basic" id="fWaPJ" placeholder="08xxxxxxxxxx"></div>
  </div>
  <div class="field"><label>Catatan</label><textarea class="basic" id="fCatatan" rows="2"></textarea></div>
  <button class="btn btn-primary" onclick="saveKegiatan()">💾 Simpan Kegiatan</button>
</div></div>

<div class="modal-bg" id="modalKategori"><div class="modal">
  <div class="modal-head"><h3>Kategori</h3><button onclick="closeModal('modalKategori')">✕</button></div>
  <input type="hidden" id="kategoriEditId">
  <div class="field"><label>Nama Kategori</label><input class="basic" id="fNamaKategori"></div>
  <button class="btn btn-primary" onclick="saveKategori()">💾 Simpan</button>
</div></div>

<div class="modal-bg" id="modalInfaq"><div class="modal">
  <div class="modal-head"><h3>Catat Infaq</h3><button onclick="closeModal('modalInfaq')">✕</button></div>
  <input type="hidden" id="infaqEditId">
  <div class="field"><label>Kegiatan</label><select class="basic" id="fInfaqKegiatan"></select></div>
  <div class="field"><label>Nama Peserta</label><input class="basic" id="fInfaqNama"></div>
  <div class="field"><label>Nominal</label><input type="number" class="basic" id="fInfaqNominal"></div>
  <div class="field"><label>Metode</label>
    <select class="basic" id="fInfaqMetode"><option>Tunai</option><option>Transfer</option><option>QRIS</option><option>Lainnya</option></select>
  </div>
  <div class="field"><label>Keterangan</label><input class="basic" id="fInfaqKet"></div>
  <button class="btn btn-primary" onclick="saveInfaq()">💾 Simpan Infaq</button>
</div></div>

<div class="modal-bg" id="modalAccount"><div class="modal">
  <div class="modal-head"><h3>Ubah Akun</h3><button onclick="closeModal('modalAccount')">✕</button></div>
  <div class="field"><label>Username Baru</label><input class="basic" id="newUsername"></div>
  <div class="field"><label>Password Saat Ini</label><input type="password" class="basic" id="curPassword"></div>
  <div class="field"><label>Password Baru (opsional)</label><input type="password" class="basic" id="newPassword"></div>
  <button class="btn btn-primary" onclick="saveAccount()">💾 Simpan</button>
</div></div>

<div class="modal-bg" id="modalQrFull"><div class="modal" style="text-align:center;">
  <div class="modal-head"><h3>QR Code</h3><button onclick="closeModal('modalQrFull')">✕</button></div>
  <div id="qrFullContent"></div>
</div></div>

<div class="modal-bg" id="modalScanner"><div class="modal" style="text-align:center;">
  <div class="modal-head"><h3>Scan QR Peserta</h3><button onclick="closeScanner()">✕</button></div>
  <video id="scannerVideo" playsinline style="width:100%;border-radius:12px;background:#000;max-height:320px;object-fit:cover;"></video>
  <canvas id="scannerCanvas" class="hidden"></canvas>
  <div id="scannerStatus" class="small-muted" style="margin-top:10px;">Arahkan kamera ke QR pribadi peserta...</div>
  <div id="scannerResult"></div>
</div></div>

<div class="toast" id="toast"></div>

<!-- ============== PUBLIC ABSENSI PAGE (shown only via #absen route) ============== -->
<div class="pubwrap hidden" id="publicAbsenPage">
  <div class="pubcard">
    <div id="publicAbsenInner"></div>
  </div>
</div>

<script>
/* ====================================================================
   DAFTAR HADIR PENGAJIAN DIGITAL — Vanilla JS, LocalStorage
   ==================================================================== */
const DB_KEY = 'pengajianDB_v1';
const THEMES = ['#0f5132','#1e3a8a','#7c2d12','#581c87','#0c4a6e','#78350f'];

function defaultDB(){
  return {
    login:{ username:'admin', password:'admin123' },
    identitas:{
      namaOrganisasi:'Majelis Al-Ikhlas', namaMasjid:'Masjid Al-Ikhlas', namaKelompok:'Kelompok Pengajian',
      namaAplikasi:'Daftar Hadir Pengajian Digital', footer:'© 2026 Majelis Al-Ikhlas',
      logoOrganisasi:'', lambangOrganisasi:'', stempel:'', theme:'#0f5132'
    },
    kategori:[
      {id:'k1',nama:'Ngaji Kelompok'},{id:'k2',nama:'Pengajian Muda-Mudi'},
      {id:'k3',nama:'Pengajian Ibu-Ibu'},{id:'k4',nama:'Pengajian Turba'}
    ],
    kegiatan:[],
    peserta:[],
    infaq:[],
    session:{loggedIn:false, remember:false}
  };
}

let DB = loadDB();
function loadDB(){
  try{
    const raw = localStorage.getItem(DB_KEY);
    if(!raw) { const d=defaultDB(); localStorage.setItem(DB_KEY, JSON.stringify(d)); return d; }
    return JSON.parse(raw);
  }catch(e){ return defaultDB(); }
}
function saveDB(){ localStorage.setItem(DB_KEY, JSON.stringify(DB)); }
function uid(p){ return p+'_'+Math.random().toString(36).slice(2,9)+Date.now().toString(36).slice(-4); }
function toast(msg){
  const t=document.getElementById('toast'); t.textContent=msg; t.classList.add('show');
  clearTimeout(window._toastTimer); window._toastTimer=setTimeout(()=>t.classList.remove('show'),2200);
}
function fmtRupiah(n){ return 'Rp '+ (n||0).toLocaleString('id-ID'); }
function fmtTanggal(dstr){
  if(!dstr) return '-';
  const d=new Date(dstr+'T00:00:00');
  return d.toLocaleDateString('id-ID',{weekday:'long',day:'numeric',month:'long',year:'numeric'});
}
function escapeHtml(s){ return (s||'').toString().replace(/[&<>"']/g, c=>({'&':'&amp;','<':'&lt;','>':'&gt;','"':'&quot;',"'":'&#39;'}[c])); }

/* ---------------- ROUTER / NAV ---------------- */
const PUBLIC_NAV_SCREENS = ['dashboard','kegiatan','infaq','menu'];
function goto(screenName, opt){
  document.querySelectorAll('.screen').forEach(s=>s.classList.remove('active'));
  const el = document.getElementById('screen-'+screenName);
  if(el) el.classList.add('active');
  document.getElementById('bottomnav').classList.toggle('show', PUBLIC_NAV_SCREENS.includes(screenName));
  document.querySelectorAll('.navbtn[data-go]').forEach(b=>b.classList.toggle('active', b.dataset.go===screenName));
  window.scrollTo(0,0);
  if(screenName==='dashboard') renderDashboard();
  if(screenName==='kegiatan') renderKegiatanList();
  if(screenName==='infaq') renderInfaqGlobal();
  if(screenName==='settings') fillSettingsForm();
  if(screenName==='kategori') renderKategoriList();
  if(screenName==='menu') renderMenu();
  if(screenName==='banner') initBannerScreen();
  if(screenName==='whatsapp') initWhatsappScreen();
}
window._currentKegiatanId = null;

/* ---------------- AUTH ---------------- */
function togglePass(){
  const inp=document.getElementById('loginPass');
  inp.type = inp.type==='password' ? 'text':'password';
}
function doLogin(){
  const u=document.getElementById('loginUser').value.trim();
  const p=document.getElementById('loginPass').value;
  if(u===DB.login.username && p===DB.login.password){
    DB.session.loggedIn=true;
    DB.session.remember = document.getElementById('rememberMe').checked;
    saveDB();
    enterApp();
  }else{
    toast('Username atau password salah');
  }
}
function doLogout(){
  if(!confirm('Yakin ingin logout?')) return;
  DB.session.loggedIn=false; saveDB();
  document.getElementById('loginUser').value=''; document.getElementById('loginPass').value='';
  document.getElementById('bottomnav').classList.remove('show');
  document.querySelectorAll('.screen').forEach(s=>s.classList.remove('active'));
  document.getElementById('screen-login').classList.add('active');
}
function enterApp(){
  applyIdentitasToUI();
  goto('dashboard');
}

/* ---------------- IDENTITAS ---------------- */
function applyIdentitasToUI(){
  const id = DB.identitas;
  document.getElementById('loginOrgName').textContent = id.namaOrganisasi;
  document.getElementById('loginAppName').textContent = id.namaAplikasi;
  document.getElementById('loginFooter').textContent = id.footer;
  const lb = document.getElementById('loginLogoBox');
  lb.innerHTML = id.logoOrganisasi ? `<img src="${id.logoOrganisasi}">` : '🕌';
  document.documentElement.style.setProperty('--hijau-tua', id.theme||'#0f5132');
  const c2 = shadeColor(id.theme||'#0f5132', 15);
  document.documentElement.style.setProperty('--hijau', c2);
  document.title = id.namaAplikasi;
}
function shadeColor(hex, percent){
  try{
    let [r,g,b] = hex.replace('#','').match(/.{2}/g).map(x=>parseInt(x,16));
    r=Math.min(255,r+percent); g=Math.min(255,g+percent); b=Math.min(255,b+percent);
    return '#'+[r,g,b].map(x=>Math.round(x).toString(16).padStart(2,'0')).join('');
  }catch(e){ return hex; }
}
function fillSettingsForm(){
  const id=DB.identitas;
  document.getElementById('setNamaOrganisasi').value=id.namaOrganisasi||'';
  document.getElementById('setNamaMasjid').value=id.namaMasjid||'';
  document.getElementById('setNamaKelompok').value=id.namaKelompok||'';
  document.getElementById('setNamaAplikasi').value=id.namaAplikasi||'';
  document.getElementById('setFooter').value=id.footer||'';
  document.getElementById('logoUploadBox').innerHTML = id.logoOrganisasi? `<img src="${id.logoOrganisasi}">` : 'Ketuk untuk unggah logo';
  document.getElementById('logoUploadBox').innerHTML += '<input type="file" accept="image/*" onchange="uploadImage(event,\'logoOrganisasi\',\'logoUploadBox\')">';
  document.getElementById('lambangUploadBox').innerHTML = (id.lambangOrganisasi? `<img src="${id.lambangOrganisasi}">` : 'Ketuk untuk unggah lambang') + '<input type="file" accept="image/*" onchange="uploadImage(event,\'lambangOrganisasi\',\'lambangUploadBox\')">';
  document.getElementById('stempelUploadBox').innerHTML = (id.stempel? `<img src="${id.stempel}">` : 'Ketuk untuk unggah stempel') + '<input type="file" accept="image/*" onchange="uploadImage(event,\'stempel\',\'stempelUploadBox\')">';
  const sw=document.getElementById('themeSwatches'); sw.innerHTML='';
  THEMES.forEach(c=>{
    const d=document.createElement('div'); d.className='swatch'+(id.theme===c?' sel':''); d.style.background=c;
    d.onclick=()=>{ id.theme=c; document.querySelectorAll('#themeSwatches .swatch').forEach(s=>s.classList.remove('sel')); d.classList.add('sel'); };
    sw.appendChild(d);
  });
}
function uploadImage(ev, field, boxId){
  const file = ev.target.files[0]; if(!file) return;
  const reader = new FileReader();
  reader.onload = ()=>{
    DB.identitas[field] = reader.result; saveDB();
    document.getElementById(boxId).innerHTML = `<img src="${reader.result}">` + `<input type="file" accept="image/*" onchange="uploadImage(event,'${field}','${boxId}')">`;
    if(field==='logoOrganisasi') applyIdentitasToUI();
  };
  reader.readAsDataURL(file);
}
function saveIdentitas(){
  const id=DB.identitas;
  id.namaOrganisasi=document.getElementById('setNamaOrganisasi').value;
  id.namaMasjid=document.getElementById('setNamaMasjid').value;
  id.namaKelompok=document.getElementById('setNamaKelompok').value;
  id.namaAplikasi=document.getElementById('setNamaAplikasi').value;
  id.footer=document.getElementById('setFooter').value;
  saveDB(); applyIdentitasToUI();
  toast('Identitas tersimpan'); goto('menu');
}
function openAccountModal(){ document.getElementById('newUsername').value=DB.login.username; openModal('modalAccount'); }
function saveAccount(){
  const cur=document.getElementById('curPassword').value;
  if(cur!==DB.login.password){ toast('Password saat ini salah'); return; }
  const nu=document.getElementById('newUsername').value.trim();
  const np=document.getElementById('newPassword').value;
  if(nu) DB.login.username=nu;
  if(np) DB.login.password=np;
  saveDB(); closeModal('modalAccount'); toast('Akun diperbarui'); renderMenu();
}

/* ---------------- MODAL HELPERS ---------------- */
function openModal(id){ document.getElementById(id).classList.add('show'); }
function closeModal(id){ document.getElementById(id).classList.remove('show'); }

/* ---------------- KATEGORI ---------------- */
function openKategoriModal(editId){
  document.getElementById('kategoriEditId').value = editId||'';
  document.getElementById('fNamaKategori').value = editId ? DB.kategori.find(k=>k.id===editId).nama : '';
  openModal('modalKategori');
}
function saveKategori(){
  const editId=document.getElementById('kategoriEditId').value;
  const nama=document.getElementById('fNamaKategori').value.trim();
  if(!nama){ toast('Nama kategori wajib diisi'); return; }
  if(editId){ DB.kategori.find(k=>k.id===editId).nama=nama; }
  else { DB.kategori.push({id:uid('kat'),nama}); }
  saveDB(); closeModal('modalKategori'); renderKategoriList(); toast('Kategori disimpan');
}
function deleteKategori(id){
  if(!confirm('Hapus kategori ini?')) return;
  DB.kategori = DB.kategori.filter(k=>k.id!==id); saveDB(); renderKategoriList();
}
function renderKategoriList(){
  const wrap=document.getElementById('kategoriListWrap');
  if(!DB.kategori.length){ wrap.innerHTML='<div class="empty-state">Belum ada kategori</div>'; return; }
  wrap.innerHTML = DB.kategori.map(k=>`
    <div class="card" style="display:flex;align-items:center;justify-content:space-between;">
      <div style="font-weight:700;">${escapeHtml(k.nama)}</div>
      <div style="display:flex;gap:6px;">
        <button class="btn btn-outline btn-sm" onclick="openKategoriModal('${k.id}')">✏️</button>
        <button class="btn btn-danger btn-sm" onclick="deleteKategori('${k.id}')">🗑️</button>
      </div>
    </div>`).join('');
}

/* ---------------- KEGIATAN ---------------- */
function fillKategoriSelect(selectId, selected){
  const sel=document.getElementById(selectId);
  sel.innerHTML = DB.kategori.map(k=>`<option value="${k.id}" ${k.id===selected?'selected':''}>${escapeHtml(k.nama)}</option>`).join('');
}
function openKegiatanModal(editId){
  document.getElementById('kegiatanModalTitle').textContent = editId ? 'Edit Kegiatan' : 'Tambah Kegiatan';
  document.getElementById('kegiatanEditId').value = editId||'';
  fillKategoriSelect('fKategori');
  if(editId){
    const k = DB.kegiatan.find(x=>x.id===editId);
    fKegiatanForm(k);
  } else {
    ['fNamaKegiatan','fTema','fTanggal','fJamMulai','fJamSelesai','fTempat','fPemateri','fPJ','fDapukanPJ','fWaPJ','fCatatan'].forEach(id=>document.getElementById(id).value='');
    document.getElementById('fTanggal').value = new Date().toISOString().slice(0,10);
  }
  openModal('modalKegiatan');
}
function fKegiatanForm(k){
  document.getElementById('fNamaKegiatan').value=k.namaKegiatan;
  document.getElementById('fKategori').value=k.kategoriId;
  document.getElementById('fTema').value=k.tema;
  document.getElementById('fTanggal').value=k.tanggal;
  document.getElementById('fJamMulai').value=k.jamMulai;
  document.getElementById('fJamSelesai').value=k.jamSelesai;
  document.getElementById('fTempat').value=k.tempat;
  document.getElementById('fPemateri').value=k.pemateri;
  document.getElementById('fPJ').value=k.pj;
  document.getElementById('fDapukanPJ').value=k.dapukanPJ;
  document.getElementById('fWaPJ').value=k.waPJ;
  document.getElementById('fCatatan').value=k.catatan;
}
function genToken(){ return Math.random().toString(36).slice(2)+Date.now().toString(36); }
function saveKegiatan(){
  const editId=document.getElementById('kegiatanEditId').value;
  const namaKegiatan=document.getElementById('fNamaKegiatan').value.trim();
  if(!namaKegiatan){ toast('Nama kegiatan wajib diisi'); return; }
  const tanggal=document.getElementById('fTanggal').value;
  const jamMulai=document.getElementById('fJamMulai').value||'00:00';
  const jamSelesai=document.getElementById('fJamSelesai').value||'23:59';
  const data = {
    namaKegiatan, kategoriId:document.getElementById('fKategori').value,
    tema:document.getElementById('fTema').value, tanggal, jamMulai, jamSelesai,
    tempat:document.getElementById('fTempat').value, pemateri:document.getElementById('fPemateri').value,
    pj:document.getElementById('fPJ').value, dapukanPJ:document.getElementById('fDapukanPJ').value,
    waPJ:document.getElementById('fWaPJ').value, catatan:document.getElementById('fCatatan').value,
    mulaiISO: tanggal? tanggal+'T'+jamMulai+':00' : null,
    berakhirISO: tanggal? tanggal+'T'+jamSelesai+':00' : null
  };
  if(editId){
    const k=DB.kegiatan.find(x=>x.id===editId); Object.assign(k,data);
  } else {
    data.id = uid('PGJ'); data.token = genToken(); data.createdAt = new Date().toISOString();
    DB.kegiatan.push(data);
  }
  saveDB(); closeModal('modalKegiatan'); renderKegiatanList(); toast('Kegiatan disimpan');
  if(typeof renderDashboard==='function' && document.getElementById('screen-dashboard').classList.contains('active')) renderDashboard();
}
function deleteKegiatan(id){
  if(!confirm('Hapus kegiatan ini beserta data absensinya?')) return;
  DB.kegiatan = DB.kegiatan.filter(k=>k.id!==id);
  DB.peserta = DB.peserta.filter(p=>p.kegiatanId!==id);
  DB.infaq = DB.infaq.filter(i=>i.kegiatanId!==id);
  saveDB(); renderKegiatanList();
}
function kategoriNama(id){ const k=DB.kategori.find(x=>x.id===id); return k?k.nama:'-'; }
let activeKategoriFilter='all';
function renderKategoriChips(){
  const wrap=document.getElementById('kategoriChips');
  let html = `<button class="chip ${activeKategoriFilter==='all'?'active':''}" onclick="setKategoriFilter('all')">Semua</button>`;
  html += DB.kategori.map(k=>`<button class="chip ${activeKategoriFilter===k.id?'active':''}" onclick="setKategoriFilter('${k.id}')">${escapeHtml(k.nama)}</button>`).join('');
  wrap.innerHTML = html;
}
function setKategoriFilter(id){ activeKategoriFilter=id; renderKategoriChips(); renderKegiatanList(); }
function statusKegiatan(k){
  const now=new Date();
  const mulai = k.mulaiISO? new Date(k.mulaiISO): null;
  const akhir = k.berakhirISO? new Date(k.berakhirISO): null;
  if(mulai && now < mulai) return {label:'Mendatang', cls:'badge-blue'};
  if(akhir && now > akhir) return {label:'Selesai', cls:'badge-gray'};
  if(mulai && akhir && now>=mulai && now<=akhir) return {label:'Berlangsung', cls:'badge-green'};
  return {label:'Aktif', cls:'badge-green'};
}
function renderKegiatanList(){
  renderKategoriChips();
  const q=(document.getElementById('searchKegiatan')?.value||'').toLowerCase();
  const wrap=document.getElementById('kegiatanListWrap');
  let list = DB.kegiatan.slice().sort((a,b)=> (b.tanggal+b.jamMulai).localeCompare(a.tanggal+a.jamMulai));
  if(activeKategoriFilter!=='all') list=list.filter(k=>k.kategoriId===activeKategoriFilter);
  if(q) list=list.filter(k=>k.namaKegiatan.toLowerCase().includes(q));
  if(!list.length){ wrap.innerHTML='<div class="empty-state">Belum ada kegiatan. Ketuk + untuk menambah.</div>'; return; }
  wrap.innerHTML = list.map(k=>{
    const st=statusKegiatan(k);
    const peserta = DB.peserta.filter(p=>p.kegiatanId===k.id);
    return `<div class="card" style="cursor:pointer;" onclick="openKegiatanDetail('${k.id}')">
      <div style="display:flex;justify-content:space-between;align-items:flex-start;">
        <div>
          <div style="font-weight:700;font-size:.95rem;">${escapeHtml(k.namaKegiatan)}</div>
          <div class="small-muted">${fmtTanggal(k.tanggal)} • ${k.jamMulai} WIB</div>
          <div class="small-muted">📍 ${escapeHtml(k.tempat||'-')}</div>
        </div>
        <span class="badge ${st.cls}">${st.label}</span>
      </div>
      <hr class="divider">
      <div style="display:flex;justify-content:space-between;font-size:.78rem;color:var(--abu);">
        <span>🏷️ ${escapeHtml(kategoriNama(k.kategoriId))}</span>
        <span>👥 ${peserta.length} peserta</span>
      </div>
      <div style="display:flex;gap:6px;margin-top:10px;">
        <button class="btn btn-outline btn-sm" style="flex:1;" onclick="event.stopPropagation();openKegiatanModal('${k.id}')">✏️ Edit</button>
        <button class="btn btn-danger btn-sm" style="flex:1;" onclick="event.stopPropagation();deleteKegiatan('${k.id}')">🗑️ Hapus</button>
      </div>
    </div>`;
  }).join('');
}

/* ---------------- DETAIL KEGIATAN ---------------- */
function openKegiatanDetail(id){
  window._currentKegiatanId = id;
  goto('kegiatan-detail');
  renderKegiatanDetail();
}
function renderKegiatanDetail(){
  const k = DB.kegiatan.find(x=>x.id===window._currentKegiatanId);
  if(!k){ goto('kegiatan'); return; }
  document.getElementById('detailKegiatanName').textContent = k.namaKegiatan;
  const st = statusKegiatan(k);
  document.getElementById('detailKegiatanInfo').innerHTML = `
    <div style="display:flex;justify-content:space-between;align-items:flex-start;">
      <div>
        <div style="font-weight:800;font-size:1.02rem;">${escapeHtml(k.namaKegiatan)}</div>
        <div class="small-muted">${escapeHtml(k.tema||'')}</div>
      </div>
      <span class="badge ${st.cls}">${st.label}</span>
    </div>
    <hr class="divider">
    <div class="kv"><span class="k">Tanggal</span><span class="v">${fmtTanggal(k.tanggal)}</span></div>
    <div class="kv"><span class="k">Waktu</span><span class="v">${k.jamMulai} - ${k.jamSelesai} WIB</span></div>
    <div class="kv"><span class="k">Tempat</span><span class="v">${escapeHtml(k.tempat||'-')}</span></div>
    <div class="kv"><span class="k">Pemateri</span><span class="v">${escapeHtml(k.pemateri||'-')}</span></div>
    <div class="kv"><span class="k">Penanggung Jawab</span><span class="v">${escapeHtml(k.pj||'-')}</span></div>
    <div class="kv"><span class="k">Kategori</span><span class="v">${escapeHtml(kategoriNama(k.kategoriId))}</span></div>
  `;
  switchDetailTab('peserta');
}
function switchDetailTab(tab){
  ['peserta','qr','infaq','laporan'].forEach(t=>{
    document.getElementById('tab-'+t).classList.toggle('hidden', t!==tab);
  });
  document.querySelectorAll('#screen-kegiatan-detail .tabs button').forEach(b=>b.classList.toggle('active', b.dataset.tab===tab));
  if(tab==='peserta') renderPesertaTab();
  if(tab==='qr') renderQrTab();
  if(tab==='infaq') renderInfaqTab();
  if(tab==='laporan') renderLaporanTab();
}

let activeHadirFilter='semua';
function renderPesertaTab(){
  const k = DB.kegiatan.find(x=>x.id===window._currentKegiatanId);
  let list = DB.peserta.filter(p=>p.kegiatanId===k.id);
  const counts = {semua:list.length, Hadir:0, 'Izin/Berhalangan':0, Sakit:0, Alfa:0};
  list.forEach(p=>{ if(counts[p.kehadiran]!==undefined) counts[p.kehadiran]++; });
  const chipsWrap = document.getElementById('filterHadirChips');
  const opts=[['semua','Semua ('+counts.semua+')'],['Hadir','Hadir ('+counts.Hadir+')'],['Izin/Berhalangan','Izin ('+counts['Izin/Berhalangan']+')'],['Sakit','Sakit ('+counts.Sakit+')'],['Alfa','Alfa ('+counts.Alfa+')']];
  chipsWrap.innerHTML = opts.map(([v,l])=>`<button class="chip ${activeHadirFilter===v?'active':''}" onclick="setHadirFilter('${v}')">${l}</button>`).join('');
  if(activeHadirFilter!=='semua') list=list.filter(p=>p.kehadiran===activeHadirFilter);
  list = list.slice().sort((a,b)=> (a.waktuDatang||'').localeCompare(b.waktuDatang||''));
  const wrap=document.getElementById('pesertaListWrap');
  if(!list.length){ wrap.innerHTML='<div class="empty-state">Belum ada peserta absen.</div>'; return; }
  const badgeMap={Hadir:'badge-green','Izin/Berhalangan':'badge-blue',Sakit:'badge-yellow',Alfa:'badge-red'};
  wrap.innerHTML = `<div class="card" style="padding:6px 14px;">` + list.map((p,i)=>`
    <div class="list-item">
      <div class="avatar">${(p.nama||'?').charAt(0).toUpperCase()}</div>
      <div class="meta">
        <div class="name">${escapeHtml(p.nama)} ${p.verified?'<span class="badge badge-blue" style="margin-left:4px;">✔ Terverifikasi</span>':''}</div>
        <div class="sub">Dapukan: ${escapeHtml(p.dapukan||'-')} • ${p.waktuDatang? new Date(p.waktuDatang).toLocaleTimeString('id-ID',{hour:'2-digit',minute:'2-digit'}):'-'}</div>
      </div>
      <button class="btn btn-outline btn-sm" style="margin-right:6px;" onclick="showPesertaQr('${p.id}')" title="Lihat QR pribadi">⬛</button>
      <span class="badge ${badgeMap[p.kehadiran]||'badge-gray'}">${p.kehadiran||'-'}</span>
    </div>`).join('') + `</div>
    <div class="grid2">
      <button class="btn btn-outline" onclick="openPublicAbsen('${k.id}', true)">➕ Tambah Peserta (Admin)</button>
      <button class="btn btn-primary" onclick="goto('laporan');renderLaporanTab(true)">📄 Buat Laporan</button>
    </div>`;
}
function setHadirFilter(v){ activeHadirFilter=v; renderPesertaTab(); }

function renderQrTab(){
  const k = DB.kegiatan.find(x=>x.id===window._currentKegiatanId);
  const link = absensiLink(k);
  document.getElementById('tab-qr').innerHTML = `
    <div class="card">
      <h4 style="font-size:.88rem;">Link Absensi</h4>
      <p class="small-muted">Bagikan link ini ke grup atau peserta untuk mengisi daftar hadir.</p>
      <div class="copy-row"><span id="linkAbsensiText">${link}</span><button class="btn btn-sm btn-outline" onclick="copyText('${link}')">Copy</button></div>
    </div>
    <div class="qr-box">
      <h4 style="font-size:.88rem;">QR Code Absensi</h4>
      <p class="small-muted">Scan untuk membuka form absensi.</p>
      <div id="qrCanvasWrap" style="display:flex;justify-content:center;margin:14px 0;"></div>
      <div class="small-muted" id="qrValidityText"></div>
      <div class="grid2" style="margin-top:12px;">
        <button class="btn btn-outline" onclick="downloadQr()">⬇️ Download QR</button>
        <button class="btn btn-primary" onclick="refreshToken()">🔄 Refresh Token</button>
      </div>
    </div>
    <div class="qr-box" style="margin-top:14px;">
      <h4 style="font-size:.88rem;">Barcode Kegiatan</h4>
      <svg id="barcodeKegiatan"></svg>
    </div>
    <div class="card" style="margin-top:14px;">
      <h4 style="font-size:.88rem;">Verifikasi / Check-in Peserta</h4>
      <p class="small-muted">Scan QR pribadi peserta (yang sudah mengisi absensi) untuk menandai kehadiran terverifikasi secara langsung di pintu masuk.</p>
      <button class="btn btn-primary" onclick="openScanner('${k.id}')">📷 Scan QR Peserta</button>
    </div>`;
  renderQrCanvas(k);
}
function absensiLink(k){
  return location.origin + location.pathname + '#absen=' + k.id + '&t=' + k.token;
}
function renderQrCanvas(k){
  const wrap=document.getElementById('qrCanvasWrap'); wrap.innerHTML='';
  const payload = JSON.stringify({id:k.id, token:k.token, mulai:k.mulaiISO, berakhir:k.berakhirISO, url:absensiLink(k)});
  new QRCode(wrap, { text: payload, width:200, height:200, colorDark:'#0f5132', colorLight:'#ffffff' });
  const now=new Date();
  const mulai=k.mulaiISO?new Date(k.mulaiISO):null, akhir=k.berakhirISO?new Date(k.berakhirISO):null;
  let txt='';
  if(mulai && akhir){
    if(now<mulai) txt='⏳ QR aktif mulai '+mulai.toLocaleString('id-ID');
    else if(now>akhir) txt='⛔ QR sudah tidak berlaku (berakhir '+akhir.toLocaleString('id-ID')+')';
    else txt='✅ QR aktif sampai '+akhir.toLocaleTimeString('id-ID');
  }
  document.getElementById('qrValidityText').textContent = txt;
  try{
    JsBarcode('#barcodeKegiatan', k.id, {height:50, displayValue:true, fontSize:12, margin:6});
  }catch(e){}
}
function downloadQr(){
  const canvas = document.querySelector('#qrCanvasWrap canvas');
  if(!canvas){ toast('QR belum siap'); return; }
  const a=document.createElement('a'); a.href=canvas.toDataURL('image/png'); a.download='qr-absensi.png'; a.click();
}
function refreshToken(){
  const k = DB.kegiatan.find(x=>x.id===window._currentKegiatanId);
  k.token = genToken(); saveDB(); renderQrTab(); toast('Token QR diperbarui');
}
function copyText(t){
  navigator.clipboard?.writeText(t).then(()=>toast('Disalin ke clipboard')).catch(()=>toast('Gagal menyalin'));
}
function shareKegiatan(){
  const k = DB.kegiatan.find(x=>x.id===window._currentKegiatanId);
  if(!k) return;
  const text = `Assalamu'alaikum, mengundang hadir pada:\n*${k.namaKegiatan}*\n${fmtTanggal(k.tanggal)} • ${k.jamMulai} WIB\n📍 ${k.tempat}\nIsi daftar hadir: ${absensiLink(k)}`;
  window.open('https://wa.me/?text='+encodeURIComponent(text),'_blank');
}

/* ---------------- QR PESERTA (PERSONAL) & VERIFIKASI / CHECK-IN ---------------- */
function pesertaQrPayload(p){
  return JSON.stringify({pid:p.id, kid:p.kegiatanId, token:p.qrToken||''});
}
function showPesertaQr(pid){
  const p = DB.peserta.find(x=>x.id===pid);
  if(!p) return;
  const k = DB.kegiatan.find(x=>x.id===p.kegiatanId);
  const badgeMap={Hadir:'badge-green','Izin/Berhalangan':'badge-blue',Sakit:'badge-yellow',Alfa:'badge-red'};
  document.getElementById('qrFullContent').innerHTML = `
    <div class="qr-box" style="border:none;padding:6px;">
      <div class="avatar" style="width:56px;height:56px;font-size:1.3rem;margin:0 auto 8px;">${(p.nama||'?').charAt(0).toUpperCase()}</div>
      <div style="font-weight:800;">${escapeHtml(p.nama)}</div>
      <div class="small-muted">Dapukan: ${escapeHtml(p.dapukan||'-')}</div>
      <div style="margin:6px 0;"><span class="badge ${badgeMap[p.kehadiran]||'badge-gray'}">${p.kehadiran||'-'}</span> ${p.verified?'<span class="badge badge-blue">✔ Terverifikasi</span>':''}</div>
      <div id="pesertaQrCanvasWrap" style="display:flex;justify-content:center;margin:12px 0;"></div>
      <svg id="barcodePeserta"></svg>
      <div class="small-muted" style="margin-top:8px;">Tunjukkan QR/Barcode ini kepada panitia, atau panitia dapat scan untuk memverifikasi kehadiran.</div>
      <div class="grid2" style="margin-top:12px;">
        <button class="btn btn-outline" onclick="downloadPesertaQr()">⬇️ Download</button>
        <button class="btn btn-primary" onclick="sharePesertaQr('${p.id}')">💬 Bagikan WA</button>
      </div>
    </div>`;
  document.getElementById('pesertaQrCanvasWrap').innerHTML='';
  new QRCode(document.getElementById('pesertaQrCanvasWrap'), {text: pesertaQrPayload(p), width:180, height:180, colorDark:'#0f5132', colorLight:'#ffffff'});
  try{ JsBarcode('#barcodePeserta', p.id, {height:40, displayValue:true, fontSize:11, margin:6}); }catch(e){}
  openModal('modalQrFull');
}
function downloadPesertaQr(){
  const canvas = document.querySelector('#pesertaQrCanvasWrap canvas');
  if(!canvas){ toast('QR belum siap'); return; }
  const a=document.createElement('a'); a.href=canvas.toDataURL('image/png'); a.download='qr-peserta.png'; a.click();
}
function sharePesertaQr(pid){
  const p = DB.peserta.find(x=>x.id===pid);
  const k = DB.kegiatan.find(x=>x.id===p.kegiatanId);
  const text = `QR Pribadi Daftar Hadir\nNama: ${p.nama}\nKegiatan: ${k?k.namaKegiatan:'-'}\nID Peserta: ${p.id}\nTunjukkan QR ini saat verifikasi kehadiran.`;
  window.open('https://wa.me/?text='+encodeURIComponent(text),'_blank');
}

let _scanStream=null, _scanRAF=null;
function openScanner(kegiatanId){
  window._scanKegiatanId = kegiatanId;
  document.getElementById('scannerResult').innerHTML='';
  document.getElementById('scannerStatus').textContent='Mengaktifkan kamera...';
  openModal('modalScanner');
  navigator.mediaDevices.getUserMedia({video:{facingMode:'environment'}})
    .then(stream=>{
      _scanStream = stream;
      const video = document.getElementById('scannerVideo');
      video.srcObject = stream; video.setAttribute('playsinline', true); video.play();
      document.getElementById('scannerStatus').textContent='Arahkan kamera ke QR pribadi peserta...';
      _scanRAF = requestAnimationFrame(scanLoop);
    })
    .catch(()=>{
      document.getElementById('scannerStatus').textContent='⚠️ Tidak dapat mengakses kamera. Pastikan izin kamera diaktifkan, atau gunakan HTTPS.';
    });
}
function closeScanner(){
  closeModal('modalScanner');
  if(_scanRAF) cancelAnimationFrame(_scanRAF);
  if(_scanStream){ _scanStream.getTracks().forEach(t=>t.stop()); _scanStream=null; }
}
function scanLoop(){
  const video = document.getElementById('scannerVideo');
  const canvas = document.getElementById('scannerCanvas');
  if(video.readyState === video.HAVE_ENOUGH_DATA){
    canvas.width = video.videoWidth; canvas.height = video.videoHeight;
    const ctx = canvas.getContext('2d');
    ctx.drawImage(video, 0, 0, canvas.width, canvas.height);
    const imgData = ctx.getImageData(0,0,canvas.width,canvas.height);
    const code = jsQR(imgData.data, imgData.width, imgData.height);
    if(code){
      handleScanResult(code.data);
      return; // stop loop until re-opened or retried
    }
  }
  _scanRAF = requestAnimationFrame(scanLoop);
}
function handleScanResult(raw){
  let data;
  try{ data = JSON.parse(raw); }catch(e){
    document.getElementById('scannerStatus').textContent='QR tidak dikenali, coba lagi...';
    _scanRAF = requestAnimationFrame(scanLoop);
    return;
  }
  // QR Peserta: {pid, kid, token}
  if(data.pid){
    const p = DB.peserta.find(x=>x.id===data.pid);
    if(!p){
      document.getElementById('scannerResult').innerHTML = `<div class="lock-banner">❌ Peserta tidak ditemukan di basis data ini.</div>`;
      _scanRAF = requestAnimationFrame(scanLoop);
      return;
    }
    if(window._scanKegiatanId && p.kegiatanId !== window._scanKegiatanId){
      document.getElementById('scannerResult').innerHTML = `<div class="lock-banner">⚠️ Peserta ini terdaftar pada kegiatan lain: ${escapeHtml(DB.kegiatan.find(x=>x.id===p.kegiatanId)?.namaKegiatan||'-')}.</div>`;
      _scanRAF = requestAnimationFrame(scanLoop);
      return;
    }
    p.verified = true; p.verifiedAt = new Date().toISOString(); saveDB();
    document.getElementById('scannerStatus').textContent='✅ Terverifikasi!';
    document.getElementById('scannerResult').innerHTML = `
      <div class="card" style="text-align:left;margin-top:10px;">
        <div style="font-weight:800;">${escapeHtml(p.nama)}</div>
        <div class="small-muted">Dapukan: ${escapeHtml(p.dapukan||'-')} • ${p.status||''}</div>
        <div class="small-muted">Kehadiran: ${p.kehadiran||'-'}</div>
        <div class="badge badge-blue" style="margin-top:6px;">✔ Check-in tercatat ${new Date(p.verifiedAt).toLocaleTimeString('id-ID')}</div>
      </div>
      <button class="btn btn-primary" style="margin-top:10px;" onclick="document.getElementById('scannerResult').innerHTML='';document.getElementById('scannerStatus').textContent='Arahkan kamera ke QR pribadi peserta...';_scanRAF=requestAnimationFrame(scanLoop);">📷 Scan Berikutnya</button>`;
    if(document.getElementById('screen-kegiatan-detail').classList.contains('active')) renderPesertaTab();
  }
  // QR Kegiatan (kalau panitia salah scan QR kegiatan, arahkan untuk dibuka sebagai link absensi)
  else if(data.id && data.token){
    document.getElementById('scannerResult').innerHTML = `<div class="lock-banner">ℹ️ Ini adalah QR Kegiatan (bukan QR peserta). Gunakan untuk membuka form absensi, bukan verifikasi.</div>`;
    _scanRAF = requestAnimationFrame(scanLoop);
  } else {
    document.getElementById('scannerStatus').textContent='QR tidak dikenali, coba lagi...';
    _scanRAF = requestAnimationFrame(scanLoop);
  }
}

/* ---------------- INFAQ ---------------- */
function fillKegiatanSelect(selectId, selected){
  const sel=document.getElementById(selectId);
  const list = DB.kegiatan.slice().sort((a,b)=>(b.tanggal+b.jamMulai).localeCompare(a.tanggal+a.jamMulai));
  sel.innerHTML = list.map(k=>`<option value="${k.id}" ${k.id===selected?'selected':''}>${escapeHtml(k.namaKegiatan)} - ${fmtTanggal(k.tanggal)}</option>`).join('') || '<option value="">Belum ada kegiatan</option>';
}
function openInfaqModal(){
  fillKegiatanSelect('fInfaqKegiatan', window._currentKegiatanId);
  document.getElementById('infaqEditId').value='';
  ['fInfaqNama','fInfaqNominal','fInfaqKet'].forEach(id=>document.getElementById(id).value='');
  document.getElementById('fInfaqMetode').value='Tunai';
  openModal('modalInfaq');
}
function saveInfaq(){
  const kegiatanId=document.getElementById('fInfaqKegiatan').value;
  const nama=document.getElementById('fInfaqNama').value.trim();
  const nominal=Number(document.getElementById('fInfaqNominal').value)||0;
  if(!kegiatanId){ toast('Pilih kegiatan terlebih dahulu'); return; }
  if(!nama || !nominal){ toast('Nama & nominal wajib diisi'); return; }
  DB.infaq.push({
    id:uid('inf'), kegiatanId, nama, nominal,
    metode:document.getElementById('fInfaqMetode').value,
    keterangan:document.getElementById('fInfaqKet').value,
    waktu:new Date().toISOString()
  });
  saveDB(); closeModal('modalInfaq'); toast('Infaq tercatat');
  if(document.getElementById('screen-infaq').classList.contains('active')) renderInfaqGlobal();
  if(document.getElementById('screen-kegiatan-detail').classList.contains('active')) renderInfaqTab();
}
function deleteInfaq(id){
  if(!confirm('Hapus catatan infaq ini?')) return;
  DB.infaq = DB.infaq.filter(i=>i.id!==id); saveDB(); renderInfaqGlobal(); renderInfaqTab();
}
let activeInfaqMetode='Semua';
function renderInfaqMetodeChips(targetId, listScope){
  const wrap=document.getElementById(targetId);
  const opts=['Semua','Tunai','Transfer','QRIS','Lainnya'];
  wrap.innerHTML = opts.map(o=>`<button class="chip ${activeInfaqMetode===o?'active':''}" onclick="activeInfaqMetode='${o}';${listScope}()">${o}</button>`).join('');
}
function renderInfaqGlobal(){
  renderInfaqMetodeChips('infaqMetodeChips','renderInfaqGlobal');
  let list=DB.infaq.slice();
  if(activeInfaqMetode!=='Semua') list=list.filter(i=>i.metode===activeInfaqMetode);
  const total=list.reduce((a,b)=>a+b.nominal,0);
  document.getElementById('infaqTotalGlobal').textContent=fmtRupiah(DB.infaq.reduce((a,b)=>a+b.nominal,0));
  document.getElementById('infaqCountGlobal').textContent=DB.infaq.length;
  document.getElementById('infaqAvgGlobal').textContent=fmtRupiah(DB.infaq.length? Math.round(DB.infaq.reduce((a,b)=>a+b.nominal,0)/DB.infaq.length):0);
  list.sort((a,b)=> b.waktu.localeCompare(a.waktu));
  const wrap=document.getElementById('infaqListWrap');
  if(!list.length){ wrap.innerHTML='<div class="empty-state">Belum ada catatan infaq.</div>'; return; }
  wrap.innerHTML = list.map(i=>{
    const k=DB.kegiatan.find(x=>x.id===i.kegiatanId);
    return `<div class="card" style="display:flex;justify-content:space-between;align-items:center;">
      <div>
        <div style="font-weight:700;">${escapeHtml(i.nama)}</div>
        <div class="small-muted">${k?escapeHtml(k.namaKegiatan):'-'} • ${new Date(i.waktu).toLocaleString('id-ID')}</div>
      </div>
      <div style="text-align:right;">
        <div style="font-weight:800;color:var(--hijau-tua);">${fmtRupiah(i.nominal)}</div>
        <span class="badge badge-gray">${i.metode}</span>
      </div>
    </div>`;
  }).join('');
}
function renderInfaqTab(){
  const k=DB.kegiatan.find(x=>x.id===window._currentKegiatanId);
  const list = DB.infaq.filter(i=>i.kegiatanId===k.id).sort((a,b)=>b.waktu.localeCompare(a.waktu));
  const total = list.reduce((a,b)=>a+b.nominal,0);
  document.getElementById('tab-infaq').innerHTML = `
    <div class="card" style="background:linear-gradient(135deg,var(--hijau-tua),var(--hijau));color:#fff;">
      <div style="font-size:.78rem;opacity:.85;">Total Infaq Kegiatan Ini</div>
      <div style="font-size:1.3rem;font-weight:800;">${fmtRupiah(total)}</div>
      <div class="small-muted" style="color:rgba(255,255,255,.8);">${list.length} transaksi</div>
    </div>
    <button class="btn btn-primary" style="margin-bottom:10px;" onclick="openInfaqModal()">＋ Catat Infaq</button>
    ${list.length? list.map(i=>`
      <div class="card" style="display:flex;justify-content:space-between;align-items:center;">
        <div><div style="font-weight:700;">${escapeHtml(i.nama)}</div><div class="small-muted">${new Date(i.waktu).toLocaleString('id-ID')} • ${i.metode}</div></div>
        <div style="display:flex;align-items:center;gap:8px;">
          <div style="font-weight:800;color:var(--hijau-tua);">${fmtRupiah(i.nominal)}</div>
          <button class="btn btn-danger btn-sm" onclick="deleteInfaq('${i.id}')">🗑️</button>
        </div>
      </div>`).join('') : '<div class="empty-state">Belum ada infaq untuk kegiatan ini.</div>'}
  `;
}

/* ---------------- LAPORAN ---------------- */
function renderLaporanTab(){
  const k=DB.kegiatan.find(x=>x.id===window._currentKegiatanId);
  const peserta=DB.peserta.filter(p=>p.kegiatanId===k.id);
  const infaq=DB.infaq.filter(i=>i.kegiatanId===k.id);
  const hadir=peserta.filter(p=>p.kehadiran==='Hadir').length;
  document.getElementById('tab-laporan').innerHTML = `
    <div class="card">
      <h4 style="font-size:.88rem;">Ringkasan</h4>
      <div class="kv"><span class="k">Total Peserta</span><span class="v">${peserta.length}</span></div>
      <div class="kv"><span class="k">Hadir</span><span class="v">${hadir}</span></div>
      <div class="kv"><span class="k">Total Infaq</span><span class="v">${fmtRupiah(infaq.reduce((a,b)=>a+b.nominal,0))}</span></div>
    </div>
    <div class="field"><label>Format Ekspor</label>
      <div class="grid2">
        <button class="btn btn-outline" onclick="exportLaporan('pdf')">📄 PDF</button>
        <button class="btn btn-outline" onclick="exportLaporan('xlsx')">📊 Excel (CSV)</button>
        <button class="btn btn-outline" onclick="exportLaporan('txt')">📝 Teks</button>
        <button class="btn btn-outline" onclick="exportLaporan('docx')">📃 Word (HTML)</button>
      </div>
    </div>
    <div class="card" id="laporanPreviewWrap" style="overflow-x:auto;"></div>
    <button class="btn btn-gold" onclick="goto('whatsapp')">💬 Kirim Laporan via WhatsApp</button>
  `;
  renderLaporanPreview(k, peserta, infaq);
}
function buildLaporanHTML(k, peserta, infaq){
  const id=DB.identitas;
  const totalInfaq = infaq.reduce((a,b)=>a+b.nominal,0);
  const rows = peserta.map((p,i)=>`<tr>
    <td>${i+1}</td><td>${escapeHtml(p.nama)}</td><td>${p.jenisKelamin==='P'?'Pria':'Wanita'}</td>
    <td>${escapeHtml(p.status||'-')}</td><td>${escapeHtml(p.dapukan||'-')}</td>
    <td>${p.waktuDatang? new Date(p.waktuDatang).toLocaleTimeString('id-ID'):'-'}</td>
    <td>${p.kehadiran||'-'}</td><td>${escapeHtml(p.keterangan||'-')}</td>
    <td>${p.infaq?fmtRupiah(p.infaq):'-'}</td>
    <td>${p.tandaTangan?'<img src="'+p.tandaTangan+'" style="height:24px;">':'-'}</td>
  </tr>`).join('');
  return `
    <div style="text-align:center;margin-bottom:10px;">
      ${id.logoOrganisasi?`<img src="${id.logoOrganisasi}" style="height:50px;">`:''}
      <h3 style="margin:6px 0 0;">${escapeHtml(id.namaOrganisasi)}</h3>
      <div style="font-size:.8rem;">DAFTAR HADIR PENGAJIAN</div>
      <div style="font-size:.8rem;">${escapeHtml(id.namaMasjid)}</div>
    </div>
    <table class="report-table">
      <tr><td><b>Kegiatan</b></td><td>${escapeHtml(k.namaKegiatan)}</td></tr>
      <tr><td><b>Tema</b></td><td>${escapeHtml(k.tema||'-')}</td></tr>
      <tr><td><b>Tanggal</b></td><td>${fmtTanggal(k.tanggal)}</td></tr>
      <tr><td><b>Tempat</b></td><td>${escapeHtml(k.tempat||'-')}</td></tr>
      <tr><td><b>Pemateri</b></td><td>${escapeHtml(k.pemateri||'-')}</td></tr>
    </table>
    <br>
    <table class="report-table">
      <tr><th>No</th><th>Nama</th><th>JK</th><th>Status</th><th>Dapukan</th><th>Waktu</th><th>Kehadiran</th><th>Ket</th><th>Infaq</th><th>TTD</th></tr>
      ${rows || '<tr><td colspan="10" style="text-align:center;">Belum ada peserta</td></tr>'}
    </table>
    <br>
    <div>Total Hadir: ${peserta.filter(p=>p.kehadiran==='Hadir').length} orang &nbsp;|&nbsp; Total Infaq: ${fmtRupiah(totalInfaq)}</div>
    <br><br>
    <table style="width:100%;"><tr><td style="text-align:center;width:50%;">
      <div>Mengetahui,</div><div>Penanggung Jawab</div><br><br><br>
      <div>(${escapeHtml(k.pj||'_______________')})</div><div>${escapeHtml(k.dapukanPJ||'')}</div>
    </td><td style="text-align:center;width:50%;">
      ${id.stempel?`<img src="${id.stempel}" style="height:60px;">`:'<br><br><br>'}
    </td></tr></table>
  `;
}
function renderLaporanPreview(k, peserta, infaq){
  document.getElementById('laporanPreviewWrap').innerHTML = buildLaporanHTML(k, peserta, infaq);
}
function exportLaporan(type){
  const k=DB.kegiatan.find(x=>x.id===window._currentKegiatanId);
  const peserta=DB.peserta.filter(p=>p.kegiatanId===k.id);
  const infaq=DB.infaq.filter(i=>i.kegiatanId===k.id);
  const fname = `Laporan_${k.namaKegiatan.replace(/\s+/g,'_')}_${k.tanggal}`;
  if(type==='txt'){
    let txt = `DAFTAR HADIR PENGAJIAN\n${DB.identitas.namaOrganisasi}\n${k.namaKegiatan}\n${fmtTanggal(k.tanggal)} - ${k.tempat}\n\n`;
    peserta.forEach((p,i)=> txt += `${i+1}. ${p.nama} | ${p.status||''} | ${p.kehadiran} | ${p.dapukan||''}\n`);
    txt += `\nTotal Hadir: ${peserta.filter(p=>p.kehadiran==='Hadir').length}\nTotal Infaq: ${fmtRupiah(infaq.reduce((a,b)=>a+b.nominal,0))}`;
    downloadBlob(txt, fname+'.txt','text/plain');
  } else if(type==='xlsx'){
    let csv='No,Nama,Jenis Kelamin,Status,Dapukan,No WA,Alamat,Waktu Datang,Kehadiran,Keterangan,Infaq\n';
    peserta.forEach((p,i)=>{
      csv += [i+1,p.nama,p.jenisKelamin==='P'?'Pria':'Wanita',p.status,p.dapukan,p.noWa,p.alamat,p.waktuDatang,p.kehadiran,p.keterangan,p.infaq||0]
        .map(v=>`"${(v||'').toString().replace(/"/g,'""')}"`).join(',') + '\n';
    });
    downloadBlob(csv, fname+'.csv','text/csv');
    toast('File CSV diunduh (kompatibel dibuka di Excel)');
  } else if(type==='docx'){
    const html = `<html><head><meta charset="utf-8"></head><body>${buildLaporanHTML(k,peserta,infaq)}</body></html>`;
    downloadBlob(html, fname+'.doc','application/msword');
    toast('File Word (.doc) diunduh');
  } else if(type==='pdf'){
    const node = document.createElement('div');
    node.style.padding='10px';
    node.innerHTML = buildLaporanHTML(k,peserta,infaq);
    document.body.appendChild(node);
    try{
      const {jsPDF}=window.jspdf;
      const doc = new jsPDF({unit:'pt',format:'a4'});
      doc.html(node, { callback: function(d){ d.save(fname+'.pdf'); document.body.removeChild(node); }, x:20, y:20, width:550, windowWidth:700 });
    }catch(e){
      document.body.removeChild(node); window.print(); 
    }
  }
}
function downloadBlob(content, filename, mime){
  const blob=new Blob([content],{type:mime});
  const a=document.createElement('a'); a.href=URL.createObjectURL(blob); a.download=filename; a.click();
}

/* ---------------- DASHBOARD ---------------- */
let _charts={};
function renderDashboard(){
  const now=new Date();
  document.getElementById('greetText').textContent = "Assalamu'alaikum 👋";
  const kegiatanList = DB.kegiatan.slice().sort((a,b)=>(b.tanggal+b.jamMulai).localeCompare(a.tanggal+a.jamMulai));
  const today = now.toISOString().slice(0,10);
  const todays = kegiatanList.filter(k=>k.tanggal===today);
  const cardHtml = todays.length ? todays.map(k=>`
    <div style="margin-bottom:8px;">
      <div class="small-muted">Kegiatan Hari Ini</div>
      <div style="font-weight:800;">${escapeHtml(k.namaKegiatan)}</div>
      <div class="small-muted">${fmtTanggal(k.tanggal)} • ${k.jamMulai} WIB</div>
      <div class="small-muted">📍 ${escapeHtml(k.tempat||'-')} <span class="badge badge-green" style="margin-left:6px;">${escapeHtml(kategoriNama(k.kategoriId))}</span></div>
      <button class="btn btn-primary btn-sm" style="margin-top:8px;" onclick="openKegiatanDetail('${k.id}')">Lihat Detail</button>
    </div>`).join('<hr class="divider">') : `<div class="small-muted">Tidak ada kegiatan terjadwal hari ini.</div>`;
  document.getElementById('kegiatanHariIniCard').innerHTML = cardHtml;

  document.getElementById('stTotalKegiatan').textContent = DB.kegiatan.length;
  document.getElementById('stTotalPeserta').textContent = DB.peserta.length;
  document.getElementById('stHadir').textContent = DB.peserta.filter(p=>p.kehadiran==='Hadir').length;
  document.getElementById('stIzin').textContent = DB.peserta.filter(p=>p.kehadiran==='Izin/Berhalangan').length;
  document.getElementById('stSakit').textContent = DB.peserta.filter(p=>p.kehadiran==='Sakit').length;
  document.getElementById('stAlfa').textContent = DB.peserta.filter(p=>p.kehadiran==='Alfa').length;
  const totalInfaq = DB.infaq.reduce((a,b)=>a+b.nominal,0);
  document.getElementById('stInfaqTotal').textContent = fmtRupiah(totalInfaq);
  document.getElementById('stInfaqCount').textContent = DB.infaq.length+' Transaksi';

  const last7 = kegiatanList.slice(0,7).reverse();
  drawChart('chartKehadiran','bar', last7.map(k=>k.namaKegiatan.slice(0,10)), [
    {label:'Hadir', data:last7.map(k=>DB.peserta.filter(p=>p.kegiatanId===k.id&&p.kehadiran==='Hadir').length), color:'#15803d'},
    {label:'Tidak Hadir', data:last7.map(k=>DB.peserta.filter(p=>p.kegiatanId===k.id&&p.kehadiran!=='Hadir').length), color:'#dc3545'}
  ]);
  const pria = DB.peserta.filter(p=>p.jenisKelamin==='P').length;
  const wanita = DB.peserta.filter(p=>p.jenisKelamin==='W').length;
  drawChart('chartGender','doughnut', ['Pria','Wanita'], [{data:[pria,wanita], colors:['#2563eb','#db2777']}]);

  const statusKeys=['Bapak-Bapak','Ibu-Ibu','Muda-Mudi','Remaja','Pra Remaja','Caberawit'];
  drawChart('chartStatus','doughnut', statusKeys, [{data:statusKeys.map(s=>DB.peserta.filter(p=>p.status===s).length), colors:['#0f5132','#1e3a8a','#f0a500','#7c2d12','#581c87','#0c4a6e']}]);
}
function drawChart(id, type, labels, datasets){
  const ctx=document.getElementById(id); if(!ctx) return;
  if(_charts[id]) _charts[id].destroy();
  let config;
  if(type==='bar'){
    config={type:'bar', data:{labels, datasets:datasets.map(d=>({label:d.label,data:d.data,backgroundColor:d.color}))}, options:{responsive:true, plugins:{legend:{position:'bottom'}}}};
  } else {
    config={type:'doughnut', data:{labels, datasets:[{data:datasets[0].data, backgroundColor:datasets[0].colors}]}, options:{responsive:true, plugins:{legend:{position:'bottom'}}}};
  }
  _charts[id] = new Chart(ctx, config);
}

/* ---------------- MENU ---------------- */
function renderMenu(){
  document.getElementById('menuUserName').textContent = DB.login.username;
  document.getElementById('menuUserAvatar').textContent = DB.login.username.charAt(0).toUpperCase();
}
function exportBackup(){
  downloadBlob(JSON.stringify(DB,null,2), 'backup-pengajian-'+Date.now()+'.json','application/json');
}
function importBackup(ev){
  const file=ev.target.files[0]; if(!file) return;
  const reader=new FileReader();
  reader.onload=()=>{
    try{
      const data=JSON.parse(reader.result);
      DB=data; saveDB(); toast('Data berhasil dipulihkan'); applyIdentitasToUI(); renderMenu();
    }catch(e){ toast('File backup tidak valid'); }
  };
  reader.readAsText(file);
}

/* ---------------- BANNER GENERATOR ---------------- */
let activeBannerTpl='banner';
function initBannerScreen(){
  fillKegiatanSelect('bannerKegiatanSelect', DB.kegiatan[0]?.id);
  renderBanner();
}
function switchBannerTpl(tpl){
  activeBannerTpl=tpl;
  document.querySelectorAll('#screen-banner .tabs button').forEach(b=>b.classList.toggle('active', b.dataset.tpl===tpl));
  renderBanner();
}
const BANNER_SIZES = { banner:[1000,560], poster:[900,1200], story:[900,1600], spanduk:[1500,500] };
function renderBanner(){
  const kid = document.getElementById('bannerKegiatanSelect').value;
  const k = DB.kegiatan.find(x=>x.id===kid);
  const canvas=document.getElementById('bannerCanvas');
  const [w,h] = BANNER_SIZES[activeBannerTpl];
  canvas.width=w; canvas.height=h;
  canvas.style.width='100%'; canvas.style.maxHeight='420px'; canvas.style.height='auto'; canvas.style.objectFit='contain';
  const ctx=canvas.getContext('2d');
  const grad=ctx.createLinearGradient(0,0,w,h);
  grad.addColorStop(0,'#0f5132'); grad.addColorStop(1,'#1d8a52');
  ctx.fillStyle=grad; ctx.fillRect(0,0,w,h);
  ctx.fillStyle='rgba(212,175,55,0.15)';
  for(let i=0;i<6;i++){ ctx.beginPath(); ctx.arc(w*0.1*i, h*0.15, 60,0,7); ctx.fill(); }
  if(!k){
    ctx.fillStyle='#fff'; ctx.font='28px sans-serif'; ctx.textAlign='center';
    ctx.fillText('Belum ada kegiatan. Tambah kegiatan dulu.', w/2, h/2);
    return;
  }
  ctx.fillStyle='#fff'; ctx.textAlign='center';
  ctx.font='bold '+Math.round(w*0.045)+'px sans-serif';
  wrapText(ctx, k.namaKegiatan, w/2, h*0.32, w*0.85, w*0.05);
  ctx.font=Math.round(w*0.022)+'px sans-serif'; ctx.fillStyle='#f0d97d';
  ctx.fillText(k.tema||'', w/2, h*0.42);
  ctx.fillStyle='#fff'; ctx.font=Math.round(w*0.02)+'px sans-serif';
  ctx.fillText('📅 '+fmtTanggal(k.tanggal)+' • '+k.jamMulai+' WIB', w/2, h*0.50);
  ctx.fillText('📍 '+(k.tempat||''), w/2, h*0.55);
  if(k.pemateri) ctx.fillText('🎙️ '+k.pemateri, w/2, h*0.60);
  ctx.font='bold '+Math.round(w*0.022)+'px sans-serif';
  ctx.fillText('Scan QR Code untuk Mengisi Daftar Hadir', w/2, h*0.78);

  const qrTmp = document.createElement('div'); qrTmp.style.display='none'; document.body.appendChild(qrTmp);
  new QRCode(qrTmp, {text: absensiLink(k), width:200, height:200});
  setTimeout(()=>{
    const qrCanvas = qrTmp.querySelector('canvas') || qrTmp.querySelector('img');
    const size=w*0.22, x=w/2-size/2, y=h*0.82-size*0.0;
    const draw=()=>{ try{ ctx.drawImage(qrCanvas, x, h*0.80, size, size); }catch(e){} document.body.removeChild(qrTmp); };
    if(qrCanvas && qrCanvas.complete!==false) draw(); else if(qrCanvas) qrCanvas.onload=draw; else document.body.removeChild(qrTmp);
  },150);
}
function wrapText(ctx, text, x, y, maxWidth, lineHeight){
  const words=(text||'').split(' '); let line=''; let yy=y;
  for(let n=0;n<words.length;n++){
    const test=line+words[n]+' ';
    if(ctx.measureText(test).width>maxWidth && n>0){ ctx.fillText(line,x,yy); line=words[n]+' '; yy+=lineHeight; }
    else line=test;
  }
  ctx.fillText(line,x,yy);
}
function downloadBanner(){
  const canvas=document.getElementById('bannerCanvas');
  const a=document.createElement('a'); a.href=canvas.toDataURL('image/png'); a.download='banner-'+activeBannerTpl+'.png'; a.click();
}
function shareBannerWA(){
  const kid = document.getElementById('bannerKegiatanSelect').value;
  const k = DB.kegiatan.find(x=>x.id===kid);
  if(!k){ toast('Pilih kegiatan dulu'); return; }
  const text=`Mengundang hadir pada *${k.namaKegiatan}*\n${fmtTanggal(k.tanggal)} • ${k.jamMulai} WIB\n📍 ${k.tempat}\nAbsensi: ${absensiLink(k)}`;
  window.open('https://wa.me/?text='+encodeURIComponent(text),'_blank');
  toast('Unduh gambar banner lalu lampirkan manual di chat WhatsApp');
}

/* ---------------- WHATSAPP ---------------- */
function initWhatsappScreen(){
  fillKegiatanSelect('waKegiatanSelect', window._currentKegiatanId || DB.kegiatan[0]?.id);
  document.getElementById('waTargetSelect').onchange = updateWaPreview;
  document.getElementById('waKegiatanSelect').onchange = updateWaPreview;
  updateWaPreview();
}
function updateWaPreview(){
  const target=document.getElementById('waTargetSelect').value;
  document.getElementById('waPesertaSelectWrap').classList.toggle('hidden', target!=='peserta');
  const kid=document.getElementById('waKegiatanSelect').value;
  const k=DB.kegiatan.find(x=>x.id===kid);
  if(target==='peserta' && k){
    const sel=document.getElementById('waPesertaSelect');
    const peserta=DB.peserta.filter(p=>p.kegiatanId===kid);
    sel.innerHTML = peserta.map(p=>`<option value="${p.id}">${escapeHtml(p.nama)}</option>`).join('') || '<option value="">Belum ada peserta</option>';
  }
  if(!k){ document.getElementById('waPreviewText').textContent='Pilih kegiatan terlebih dahulu.'; return; }
  let text='';
  if(target==='grup'){
    text=`Assalamu'alaikum, mengundang hadir pada:\n*${k.namaKegiatan}*\n${fmtTanggal(k.tanggal)} • ${k.jamMulai} WIB\n📍 ${k.tempat}\nSilakan isi daftar hadir melalui link:\n${absensiLink(k)}`;
  } else if(target==='pj'){
    const hadir=DB.peserta.filter(p=>p.kegiatanId===kid&&p.kehadiran==='Hadir').length;
    const infaq=DB.infaq.filter(i=>i.kegiatanId===kid).reduce((a,b)=>a+b.nominal,0);
    text=`Assalamu'alaikum Bpk/Ibu ${k.pj||''},\nRekap pengajian *${k.namaKegiatan}*\n${fmtTanggal(k.tanggal)}\nTotal Hadir: ${hadir} orang\nTotal Infaq: ${fmtRupiah(infaq)}\nTerima kasih.`;
  } else if(target==='semua'){
    text=`(Akan dikirim satu per satu ke setiap peserta)\nContoh pesan:\nAssalamu'alaikum [Nama], terima kasih telah hadir pada *${k.namaKegiatan}*. Semoga ilmu yang didapat berkah.`;
  } else if(target==='peserta'){
    text=`Assalamu'alaikum, terima kasih telah hadir pada *${k.namaKegiatan}* tanggal ${fmtTanggal(k.tanggal)}.`;
  }
  document.getElementById('waPreviewText').textContent=text;
}
function sendWhatsApp(){
  const target=document.getElementById('waTargetSelect').value;
  const kid=document.getElementById('waKegiatanSelect').value;
  const k=DB.kegiatan.find(x=>x.id===kid);
  if(!k){ toast('Pilih kegiatan dulu'); return; }
  if(target==='grup'){
    window.open('https://wa.me/?text='+encodeURIComponent(document.getElementById('waPreviewText').textContent),'_blank');
  } else if(target==='pj'){
    const phone=(k.waPJ||'').replace(/\D/g,'').replace(/^0/,'62');
    window.open('https://wa.me/'+phone+'?text='+encodeURIComponent(document.getElementById('waPreviewText').textContent),'_blank');
  } else if(target==='peserta'){
    const pid=document.getElementById('waPesertaSelect').value;
    const p=DB.peserta.find(x=>x.id===pid);
    if(!p){ toast('Pilih peserta'); return; }
    const phone=(p.noWa||'').replace(/\D/g,'').replace(/^0/,'62');
    const text=`Assalamu'alaikum ${p.nama}, terima kasih telah hadir pada *${k.namaKegiatan}* tanggal ${fmtTanggal(k.tanggal)}.`;
    window.open('https://wa.me/'+phone+'?text='+encodeURIComponent(text),'_blank');
  } else if(target==='semua'){
    const peserta=DB.peserta.filter(p=>p.kegiatanId===kid);
    if(!peserta.length){ toast('Belum ada peserta'); return; }
    toast('Membuka WhatsApp untuk peserta pertama. Ulangi untuk peserta lain.');
    const p=peserta[0];
    const phone=(p.noWa||'').replace(/\D/g,'').replace(/^0/,'62');
    const text=`Assalamu'alaikum ${p.nama}, terima kasih telah hadir pada *${k.namaKegiatan}*.`;
    window.open('https://wa.me/'+phone+'?text='+encodeURIComponent(text),'_blank');
  }
}

/* ====================================================================
   PUBLIC ABSENSI FORM (peserta isi sendiri via QR/link, atau admin)
   ==================================================================== */
let _pubKegiatanId=null, _pubIsAdmin=false, _sigCtx=null, _sigDrawing=false;
function openPublicAbsen(kid, isAdmin){
  _pubKegiatanId = kid; _pubIsAdmin = !!isAdmin;
  document.getElementById('app').style.display='none';
  document.getElementById('publicAbsenPage').classList.remove('hidden');
  renderPublicAbsen();
}
function closePublicAbsen(){
  document.getElementById('publicAbsenPage').classList.add('hidden');
  document.getElementById('app').style.display='block';
  location.hash='';
  if(_pubIsAdmin && window._currentKegiatanId) renderPesertaTab();
}
function renderPublicAbsen(){
  const k = DB.kegiatan.find(x=>x.id===_pubKegiatanId);
  const inner = document.getElementById('publicAbsenInner');
  const id = DB.identitas;
  if(!k){
    inner.innerHTML = `<div class="expired-box"><div class="ic">🔍</div>Kegiatan tidak ditemukan.</div>`;
    return;
  }
  const now=new Date();
  const mulai = k.mulaiISO?new Date(k.mulaiISO):null, akhir=k.berakhirISO?new Date(k.berakhirISO):null;
  const expired = (mulai && now<mulai) || (akhir && now>akhir);
  if(expired && !_pubIsAdmin){
    inner.innerHTML = `
      <div class="pub-head">${id.logoOrganisasi?`<img src="${id.logoOrganisasi}">`:''}<h3 style="color:#fff;">${escapeHtml(id.namaOrganisasi)}</h3></div>
      <div style="text-align:center;padding:30px 10px;">
        <div style="font-size:2.4rem;">⏰</div>
        <h3>QR Code Tidak Berlaku</h3>
        <p class="small-muted">Waktu absensi untuk kegiatan ini sudah berakhir atau belum dimulai.</p>
        <div class="kv"><span class="k">Kegiatan</span><span class="v">${escapeHtml(k.namaKegiatan)}</span></div>
        <div class="kv"><span class="k">Berlaku</span><span class="v">${mulai?mulai.toLocaleString('id-ID'):''} - ${akhir?akhir.toLocaleString('id-ID'):''}</span></div>
      </div>`;
    return;
  }
  inner.innerHTML = `
    <div class="pub-head" style="color:var(--hijau-tua);">
      ${id.logoOrganisasi?`<img src="${id.logoOrganisasi}" style="background:none;padding:0;">`:''}
      <h3 style="color:var(--hijau-tua);">${escapeHtml(id.namaOrganisasi)}</h3>
    </div>
    ${_pubIsAdmin?`<div class="lock-banner">Mode admin: menambahkan peserta langsung</div>`:''}
    ${(!_pubIsAdmin && !_pubLinkTokenValid)?`<div class="lock-banner">⚠️ Link/QR ini sudah diperbarui oleh admin. Anda tetap bisa mengisi, namun sebaiknya gunakan QR/link terbaru.</div>`:''}
    <div class="card" style="margin-bottom:14px;">
      <div style="font-weight:800;">${escapeHtml(k.namaKegiatan)}</div>
      <div class="small-muted">${fmtTanggal(k.tanggal)} • ${k.jamMulai}-${k.jamSelesai} WIB</div>
      <div class="small-muted">📍 ${escapeHtml(k.tempat||'-')}</div>
    </div>
    <div class="steplabel">Form Absensi Peserta</div>
    <div class="field"><label>Nama Lengkap *</label><input class="basic" id="pNama"></div>
    <div class="field"><label>Jenis Kelamin *</label>
      <div class="gender-toggle">
        <label id="lblPria"><input type="radio" name="jk" value="P" onchange="updateGenderUI()"> Pria</label>
        <label id="lblWanita"><input type="radio" name="jk" value="W" onchange="updateGenderUI()"> Wanita</label>
      </div>
    </div>
    <div class="field"><label>Status Peserta *</label>
      <select class="basic" id="pStatus">
        <option value="Bapak-Bapak">Bapak-Bapak</option><option value="Ibu-Ibu">Ibu-Ibu</option>
        <option value="Muda-Mudi">Muda-Mudi</option><option value="Remaja">Remaja</option>
        <option value="Pra Remaja">Pra Remaja</option><option value="Caberawit">Caberawit</option>
      </select>
    </div>
    <div class="field"><label>Dapukan</label><input class="basic" id="pDapukan"></div>
    <div class="field"><label>No. WhatsApp *</label><input class="basic" id="pNoWa" placeholder="08xxxxxxxxxx"></div>
    <div class="field"><label>Alamat</label><input class="basic" id="pAlamat"></div>
    <div class="field"><label>Kehadiran *</label>
      <select class="basic" id="pKehadiran">
        <option value="Hadir">Hadir</option><option value="Izin/Berhalangan">Izin/Berhalangan</option>
        <option value="Sakit">Sakit</option><option value="Alfa">Alfa</option>
      </select>
    </div>
    <div class="field"><label>Keterangan</label><input class="basic" id="pKeterangan"></div>
    <div class="field"><label>Nominal Infaq (opsional)</label><input type="number" class="basic" id="pInfaq" placeholder="0"></div>
    <div class="field"><label>Tanda Tangan Digital *</label>
      <canvas class="sig-canvas" id="sigCanvas"></canvas>
      <div class="signpad-actions">
        <button class="btn btn-outline btn-sm" style="flex:1;" onclick="clearSignature()">🗑️ Hapus</button>
      </div>
    </div>
    <button class="btn btn-primary" style="margin-top:16px;" onclick="submitAbsensi()">✅ Simpan Daftar Hadir</button>
    ${_pubIsAdmin?`<button class="btn btn-outline" style="margin-top:10px;" onclick="closePublicAbsen()">← Kembali ke Admin</button>`:''}
    <div class="small-muted" style="text-align:center;margin-top:14px;">${escapeHtml(id.footer)}</div>
  `;
  setupSignaturePad();
}
function updateGenderUI(){
  document.getElementById('lblPria').classList.toggle('checked', document.querySelector('input[name=jk][value=P]').checked);
  document.getElementById('lblWanita').classList.toggle('checked', document.querySelector('input[name=jk][value=W]').checked);
}
function setupSignaturePad(){
  const canvas=document.getElementById('sigCanvas');
  const ratio = window.devicePixelRatio||1;
  canvas.width = canvas.clientWidth*ratio; canvas.height=220*ratio;
  const ctx = canvas.getContext('2d'); ctx.scale(ratio,ratio);
  ctx.strokeStyle='#1f2937'; ctx.lineWidth=2.4; ctx.lineCap='round';
  _sigCtx=ctx;
  let last=null;
  const pos=(e)=>{
    const r=canvas.getBoundingClientRect();
    const p = e.touches? e.touches[0]:e;
    return {x:p.clientX-r.left, y:p.clientY-r.top};
  };
  const start=(e)=>{ _sigDrawing=true; last=pos(e); };
  const move=(e)=>{
    if(!_sigDrawing) return; e.preventDefault();
    const p=pos(e); ctx.beginPath(); ctx.moveTo(last.x,last.y); ctx.lineTo(p.x,p.y); ctx.stroke(); last=p;
  };
  const end=()=>{ _sigDrawing=false; };
  canvas.onmousedown=start; canvas.onmousemove=move; canvas.onmouseup=end; canvas.onmouseleave=end;
  canvas.ontouchstart=start; canvas.ontouchmove=move; canvas.ontouchend=end;
}
function clearSignature(){
  const canvas=document.getElementById('sigCanvas');
  _sigCtx.clearRect(0,0,canvas.width,canvas.height);
}
function isCanvasBlank(canvas){
  const ctx=canvas.getContext('2d');
  const data=ctx.getImageData(0,0,canvas.width,canvas.height).data;
  for(let i=3;i<data.length;i+=4){ if(data[i]!==0) return false; }
  return true;
}
function submitAbsensi(){
  const nama=document.getElementById('pNama').value.trim();
  const jk=document.querySelector('input[name=jk]:checked')?.value;
  const noWa=document.getElementById('pNoWa').value.trim();
  const canvas=document.getElementById('sigCanvas');
  if(!nama){ toast('Nama lengkap wajib diisi'); return; }
  if(!jk){ toast('Pilih jenis kelamin'); return; }
  if(!noWa){ toast('Nomor WhatsApp wajib diisi'); return; }
  if(isCanvasBlank(canvas)){ toast('Tanda tangan digital wajib diisi'); return; }
  const peserta={
    id: uid('psr'), kegiatanId: _pubKegiatanId, nama,
    jenisKelamin: jk, status: document.getElementById('pStatus').value,
    dapukan: document.getElementById('pDapukan').value, noWa,
    alamat: document.getElementById('pAlamat').value,
    waktuDatang: new Date().toISOString(),
    kehadiran: document.getElementById('pKehadiran').value,
    keterangan: document.getElementById('pKeterangan').value,
    infaq: Number(document.getElementById('pInfaq').value)||0,
    tandaTangan: canvas.toDataURL('image/png'),
    qrToken: genToken()
  };
  DB.peserta.push(peserta);
  peserta.qrTokenUsed = location.hash.includes('t=') ? (location.hash.split('t=')[1]||'').split('&')[0] : null;
  if(peserta.infaq>0){
    DB.infaq.push({id:uid('inf'), kegiatanId:_pubKegiatanId, nama, nominal:peserta.infaq, metode:'Tunai', keterangan:'Infaq saat absensi', waktu:new Date().toISOString()});
  }
  saveDB();
  toast('Daftar hadir tersimpan, terima kasih!');
  if(_pubIsAdmin){ renderPublicAbsen(); }
  else {
    document.getElementById('publicAbsenInner').innerHTML = `
      <div style="text-align:center;padding:40px 10px;">
        <div style="font-size:3rem;">✅</div>
        <h3>Terima kasih, ${escapeHtml(nama)}!</h3>
        <p class="small-muted">Daftar hadir Anda telah tercatat.</p>
      </div>`;
  }
}

/* ---------------- HASH ROUTER FOR PUBLIC ABSEN LINK ---------------- */
function checkHashRoute(){
  const hash = location.hash;
  if(hash.startsWith('#absen=')){
    const params = hash.slice(1);
    const parts = Object.fromEntries(params.split('&').map(p=>{ const [k,v]=p.split('='); return [k,v]; }));
    const k = DB.kegiatan.find(x=>x.id===parts.absen);
    if(k){
      // Validasi token: jika link dibuat dari QR/Barcode lama (token sudah di-refresh admin), tetap izinkan akses
      // tapi tandai sebagai link tidak resmi pada catatan peserta agar bisa ditelusuri.
      _pubLinkTokenValid = !parts.t || parts.t === k.token;
      openPublicAbsen(k.id, false);
      return true;
    }
  }
  return false;
}
let _pubLinkTokenValid = true;

/* ---------------- INIT ---------------- */
window.addEventListener('DOMContentLoaded', ()=>{
  if(!checkHashRoute()){
    if(DB.session.loggedIn){ enterApp(); }
    applyIdentitasToUI();
  }
});
window.addEventListener('hashchange', ()=>{
  if(location.hash.startsWith('#absen=')) checkHashRoute();
});
</script>
</body>
</html>
