# Rovsat-site
Rovsat.com
<!doctype html>
<html lang="az">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>RoVsaT</title>
  <meta name="description" content="RoVsaT — rəsmi sayt." />
  <!-- robotlara icazə verin -->
  <meta name="robots" content="index,follow" />
  <style>
    /* Tam qara ekran, mərkəzləşmiş yaşıl yazı */
    html,body{
      height:100%;
      margin:0;
      background:#000; /* qara */
      font-family: Inter, system-ui, -apple-system, "Segoe UI", Roboto, "Helvetica Neue", Arial;
    }
    .center{
      height:100%;
      display:flex;
      align-items:center;
      justify-content:center;
      text-align:center;
      user-select:none;
    }
    .logo{
      color:#00ff33; /* canlı yaşıl */
      font-size:clamp(48px, 12vw, 160px);
      letter-spacing:6px;
      font-weight:700;
      text-transform:none;
      text-shadow: 0 6px 18px rgba(0,255,51,0.08);
    }
    /* İstəsən animasiya */
    @keyframes glow {
      0% { filter: drop-shadow(0 0 4px rgba(0,255,51,0.15)); transform: translateY(0); }
      50% { filter: drop-shadow(0 0 18px rgba(0,255,51,0.25)); transform: translateY(-4px); }
      100% { filter: drop-shadow(0 0 4px rgba(0,255,51,0.15)); transform: translateY(0); }
    }
    .logo { animation: glow 3.5s ease-in-out infinite; }
  </style>
</head>
<body>
  <div class="center">
    <div class="logo">RoVsaT</div>
  </div>
</body>
</html>
