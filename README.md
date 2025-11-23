
<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Shadowmistress — Premium Page</title>
  <style>
    :root{
      --bg1:#1b0f18;
      --bg2:#2a1824;
      --accent:#b42c6f;
      --accent2:#e04f9e;
      --muted:#c8b6c8;
      --card:rgba(255,255,255,0.08);
      --glass:rgba(255,255,255,0.15);
      --border:rgba(255,255,255,0.2);
      --shadow:0 12px 28px rgba(0,0,0,0.5);
      --radius:16px;
    }
    *{box-sizing:border-box;}
    body{
      margin:0;
      font-family:"Inter",Arial,sans-serif;
      background:linear-gradient(180deg,var(--bg1),var(--bg2));
      color:white;
      padding:24px;
      display:flex;
      justify-content:center;
      min-height:100vh;
    }
    .container{
      width:100%;
      max-width:960px;
      display:grid;
      grid-template-columns:360px 1fr;
      background:rgba(0,0,0,0.28);
      border:1px solid var(--border);
      border-radius:20px;
      box-shadow:var(--shadow);
      overflow:hidden;
    }
    .hero{
      padding:30px;
      background:rgba(255,255,255,0.04);
      backdrop-filter:blur(8px);
      display:flex;
      flex-direction:column;
      gap:16px;
      align-items:center;
    }
    .avatar{
      width:160px;
      height:160px;
      border-radius:20px;
      background:linear-gradient(135deg,#431f36,#291221);
      display:flex;
      justify-content:center;
      align-items:center;
      font-size:62px;
      border:2px solid var(--accent);
    }
    .name{font-size:24px;font-weight:700;}
    .tagline{font-size:14px;color:var(--muted);text-align:center;}
    .btn{
      padding:10px 16px;
      border-radius:12px;
      font-weight:600;
      cursor:pointer;
      border:0;
      transition:0.15s;
      text-decoration:none;
      display:inline-block;
      text-align:center;
    }
    .btn-main{
      background:linear-gradient(90deg,var(--accent),var(--accent2));
      color:white;
      box-shadow:0 8px 20px rgba(178,39,107,0.5);
    }
    .btn-ghost{
      background:transparent;
      border:1px solid var(--accent);
      color:var(--accent2);
    }
    .content{padding:30px;display:flex;flex-direction:column;gap:20px;}
    .intro h1{margin:0;font-size:22px;}
    .intro p{margin:4px 0;color:var(--muted);}
    .tiers{
      display:grid;
      grid-template-columns:repeat(2,1fr);
      gap:14px;
    }
    .card{
      background:var(--card);
      border:1px solid var(--border);
      padding:14px;
      border-radius:14px;
      min-height:110px;
    }
    .card h3{margin:0;font-size:16px;color:#ffb4dc;}
    .card p{margin:6px 0 0;color:var(--muted);font-size:13px;}
    .price{color:var(--accent2);font-weight:700;}
    .actions{display:flex;align-items:center;margin-top:10px;gap:10px;}
    .expand{background:transparent;border:0;color:var(--accent2);cursor:pointer;font-weight:600;}
    .details{display:none;font-size:13px;color:#e8d4e8;margin-top:8px;}
    .legal{font-size:12px;color:#c2a8c2;margin-top:10px;}

    @media(max-width:880px){
      .container{grid-template-columns:1fr;}
    }
  </style>
</head>
<body>

<div class="container">

  <!-- LEFT COLUMN -->
  <aside class="hero">
    <div class="avatar">😈</div>

    <div class="name">Shadowmistress</div>
    <div class="tagline">Seductive • Dominant • Addictive.  
      Step into my world… if you dare.</div>

    <!-- TELEGRAM FIRST -->
    <a class="btn btn-main" href="https://t.me/YOURCHANNEL" target="_blank">Join My Telegram</a>
    <a class="btn btn-ghost" href="https://example.com/subscribe" target="_blank">Subscribe</a>

    <div style="margin-top:auto;text-align:center;font-size:12px;color:var(--muted)">
      <div style="font-weight:700">DISCLAIMER</div>
      All content is copyrighted.  
      Do not save or share under any circumstances.
    </div>
  </aside>

  <!-- RIGHT COLUMN -->
  <section class="content">

    <div class="intro">
      <h1>Choose Your Tier</h1>
      <p>Tap a tier to expand details. All links are clickable.</p>
    </div>

    <div class="tiers">

      <!-- PET -->
      <div class="card">
        <h3>♡ Pet Tier</h3>
        <p>Lewds • petplay • outfits • teasing</p>
        <div class="actions">
          <span class="price">$6 / wk</span>
          <button class="expand" onclick="toggleDetails('d1')">View</button>
          <a class="btn btn-main" href="https://example.com/pet" target="_blank">Buy</a>
        </div>
        <div id="d1" class="details">Soft, sweet, playful. Daily content drops.</div>
      </div>

      <!-- GFE -->
      <div class="card">
        <h3>♡ GFE Tier</h3>
        <p>Fully nude • PPVs • cosplays • gamer tag</p>
        <div class="actions">
          <span class="price">$15 / wk</span>
          <button class="expand" onclick="toggleDetails('d2')">View</button>
          <a class="btn btn-main" href="https://example.com/gfe" target="_blank">Buy</a>
        </div>
        <div id="d2" class="details">The closest, sweetest version of me. Daily chats + intimate vibes.</div>
      </div>

      <!-- FETISH -->
      <div class="card">
        <h3>♡ Fetish Tier</h3>
        <p>Feet • bondage • anal • creamy • roleplay</p>
        <div class="actions">
          <span class="price">$35 / wk</span>
          <button class="expand" onclick="toggleDetails('d3')">View</button>
          <a class="btn btn-main" href="https://example.com/fetish" target="_blank">Buy</a>
        </div>
        <div id="d3" class="details">My wildest side. Extended clips. Taboo-friendly.</div>
      </div>

      <!-- MASTER -->
      <div class="card">
        <h3>♡ Master Tier</h3>
        <p>Domination • humiliation • lifestyle access</p>
        <div class="actions">
          <span class="price">$80 / wk</span>
          <button class="expand" onclick="toggleDetails('d4')">View</button>
          <a class="btn btn-main" href="https://example.com/master" target="_blank">Buy</a>
        </div>
        <div id="d4" class="details">For my chosen ones. Full-length videos + premium Snapchat.</div>
      </div>

      <!-- SUB TIER FULL WIDTH -->
      <div class="card" style="grid-column:1/-1;">
        <h3>♡ Sub Tier</h3>
        <p>Needy • submissive content • premium snap</p>
        <div class="actions">
          <span class="price">$50 / wk</span>
          <button class="expand" onclick="toggleDetails('d5')">View</button>
          <a class="btn btn-main" href="https://example.com/sub" target="_blank">Buy</a>
        </div>
        <div id="d5" class="details">Perfect for good boys who want direction and attention.</div>
      </div>

    </div>

    <div class="legal">
      By joining you agree not to distribute or save content.  
      Violations result in immediate legal action.
    </div>
  </section>

</div>

<script>
function toggleDetails(id){
  let el = document.getElementById(id);
  let open = el.style.display === 'block';
  document.querySelectorAll('.details').forEach(d => d.style.display='none');
  el.style.display = open ? 'none' : 'block';
}
</script>

</body>
</html>
