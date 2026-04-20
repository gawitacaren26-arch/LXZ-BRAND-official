<!DOCTYPE html>
<html>
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>LEXIZ BRAND - Promo Shopee</title>
<link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@600;700&family=Nunito:wght@400;600;700;900&display=swap" rel="stylesheet">
<style>
  * { margin: 0; padding: 0; box-sizing: border-box; }
  body { font-family: 'Nunito', sans-serif; background: #fff8fb; color: #3a1a2e; max-width: 480px; margin: 0 auto; }

  .header { background: linear-gradient(135deg, #e8638c 0%, #f4a0bf 60%, #ffd6e8 100%); padding: 20px 24px 32px; position: relative; overflow: hidden; }
  .header::before { content: ''; position: absolute; top: -50px; right: -30px; width: 180px; height: 180px; background: rgba(255,255,255,0.1); border-radius: 50%; }
  .header::after { content: ''; position: absolute; bottom: -40px; left: 20%; width: 130px; height: 130px; background: rgba(255,255,255,0.07); border-radius: 50%; }
  .deco-dot { position: absolute; top: 16px; right: 60px; width: 8px; height: 8px; border-radius: 50%; background: rgba(255,255,255,0.4); }
  .deco-dot2 { position: absolute; top: 30px; right: 80px; width: 5px; height: 5px; border-radius: 50%; background: rgba(255,255,255,0.3); }

  .logo-bar { display: flex; align-items: center; gap: 10px; margin-bottom: 16px; }
  .logo { background: white; color: #e8638c; font-family: 'Nunito', sans-serif; font-weight: 900; font-size: 19px; padding: 4px 13px; border-radius: 8px; letter-spacing: -0.5px; }
  .store-name { color: white; font-weight: 800; font-size: 14px; letter-spacing: 1.5px; opacity: 0.97; }

  .hero-text h1 { font-family: 'Playfair Display', serif; font-size: 27px; font-weight: 700; color: white; line-height: 1.2; margin-bottom: 7px; }
  .hero-text p { font-size: 13px; color: rgba(255,255,255,0.9); margin-bottom: 15px; font-weight: 400; }
  .badge-row { display: flex; gap: 7px; flex-wrap: wrap; }
  .badge { background: rgba(255,255,255,0.22); color: white; font-size: 11px; font-weight: 700; padding: 4px 11px; border-radius: 20px; border: 1px solid rgba(255,255,255,0.4); }
  .badge.hot { background: white; color: #c44d7a; border-color: white; }

  .countdown-bar { background: #fff0f6; border-bottom: 1px solid #fcd6e8; padding: 10px 24px; display: flex; align-items: center; justify-content: space-between; }
  .flash-label { display: flex; align-items: center; gap: 6px; font-size: 12px; font-weight: 800; color: #c44d7a; letter-spacing: 0.4px; }
  .flash-dot { width: 7px; height: 7px; background: #e8638c; border-radius: 50%; animation: pulse 1.2s infinite; }
  @keyframes pulse { 0%,100%{opacity:1;transform:scale(1)} 50%{opacity:0.5;transform:scale(0.7)} }
  .timer { display: flex; gap: 4px; align-items: center; }
  .time-box { background: #e8638c; color: white; font-size: 14px; font-weight: 700; padding: 3px 8px; border-radius: 6px; min-width: 32px; text-align: center; }
  .time-sep { color: #e8638c; font-weight: 800; font-size: 14px; }

  .section { padding: 16px 20px; }
  .section-title { font-size: 12px; font-weight: 800; color: #b06080; margin-bottom: 12px; display: flex; align-items: center; gap: 8px; letter-spacing: 1px; text-transform: uppercase; }
  .section-title::after { content: ''; flex: 1; height: 1px; background: #fcd6e8; }

  .cat-grid { display: grid; grid-template-columns: repeat(5, 1fr); gap: 8px; }
  .cat-item { display: flex; flex-direction: column; align-items: center; gap: 5px; cursor: pointer; }
  .cat-icon { width: 50px; height: 50px; border-radius: 14px; display: flex; align-items: center; justify-content: center; font-size: 22px; background: white; border: 1.5px solid #fcd6e8; transition: transform 0.15s, border-color 0.15s; }
  .cat-icon:hover { transform: scale(1.1); border-color: #e8638c; }
  .cat-label { font-size: 10px; font-weight: 700; color: #9a4068; text-align: center; }

  .banner-row { padding: 0 20px 16px; display: grid; grid-template-columns: 1fr 1fr; gap: 10px; }
  .banner { border-radius: 14px; padding: 15px 14px; min-height: 84px; display: flex; flex-direction: column; justify-content: center; }
  .banner.a { background: linear-gradient(130deg, #f48fb1, #f06292); }
  .banner.b { background: linear-gradient(130deg, #ce93d8, #ba68c8); }
  .banner h3 { color: white; font-size: 13px; font-weight: 800; margin-bottom: 3px; font-family: 'Playfair Display', serif; }
  .banner p { color: rgba(255,255,255,0.88); font-size: 11px; }
  .cta-mini { margin-top: 8px; background: white; color: #c44d7a; font-size: 10px; font-weight: 800; border-radius: 20px; padding: 3px 10px; display: inline-block; width: fit-content; }
  .banner.b .cta-mini { color: #7b1fa2; }

  .freeship-bar { margin: 0 20px 16px; background: linear-gradient(90deg, #f8bbd0, #fce4ec); border: 1px solid #f48fb1; border-radius: 12px; padding: 10px 14px; display: flex; align-items: center; gap: 10px; }
  .freeship-bar .icon { font-size: 20px; }
  .freeship-bar h4 { font-size: 12px; font-weight: 800; color: #ad1457; }
  .freeship-bar p { font-size: 11px; color: #c2185b; }

  .products-grid { padding: 0 20px 20px; display: grid; grid-template-columns: repeat(2, 1fr); gap: 12px; }
  .product-card { background: white; border-radius: 14px; border: 1px solid #fce4ec; overflow: hidden; cursor: pointer; transition: box-shadow 0.15s, transform 0.15s; }
  .product-card:hover { box-shadow: 0 6px 20px rgba(232,99,140,0.15); transform: translateY(-2px); }
  .product-img { width: 100%; aspect-ratio: 1; background: linear-gradient(135deg, #fce4ec, #fff0f6); display: flex; align-items: center; justify-content: center; font-size: 52px; position: relative; }
  .discount-tag { position: absolute; top: 8px; left: 8px; background: #e8638c; color: white; font-size: 10px; font-weight: 800; padding: 2px 8px; border-radius: 6px; }
  .liked-tag { position: absolute; top: 8px; right: 8px; width: 27px; height: 27px; background: white; border-radius: 50%; display: flex; align-items: center; justify-content: center; font-size: 13px; border: 1px solid #fcd6e8; }
  .product-info { padding: 10px 10px 12px; }
  .product-name { font-size: 12px; color: #4a2040; font-weight: 600; line-height: 1.4; margin-bottom: 6px; display: -webkit-box; -webkit-line-clamp: 2; -webkit-box-orient: vertical; overflow: hidden; }
  .price-row { display: flex; align-items: center; gap: 6px; flex-wrap: wrap; }
  .price-now { color: #e8638c; font-size: 15px; font-weight: 800; }
  .price-orig { color: #cca8bb; font-size: 11px; text-decoration: line-through; }
  .sold-bar { margin-top: 8px; }
  .sold-track { height: 4px; background: #fce4ec; border-radius: 4px; overflow: hidden; margin-bottom: 3px; }
  .sold-fill { height: 100%; background: linear-gradient(90deg, #f48fb1, #e8638c); border-radius: 4px; }
  .sold-label { font-size: 10px; color: #b06080; }

  .cta-section { padding: 8px 20px 28px; }
  .cta-btn { width: 100%; background: linear-gradient(135deg, #e8638c, #c44d7a); color: white; border: none; font-family: 'Nunito', sans-serif; font-size: 15px; font-weight: 800; padding: 14px; border-radius: 12px; cursor: pointer; letter-spacing: 0.3px; transition: opacity 0.15s, transform 0.1s; }
  .cta-btn:hover { opacity: 0.9; transform: scale(0.99); }

  .footer { background: #fff0f6; border-top: 1px solid #fcd6e8; padding: 12px 24px; text-align: center; }
  .footer p { font-size: 11px; color: #c2185b; }
  .footer strong { color: #e8638c; }
</style>
</head>
<body>

<!-- HEADER -->
<div class="header">
  <div class="deco-dot"></div>
  <div class="deco-dot2"></div>
  <div class="logo-bar">
    <div class="logo">shopee</div>
    <span class="store-name">✨ LEXIZ BRAND Official</span>
  </div>
  <div class="hero-text">
    <h1>Promo Spesial<br>Hari Ini 🌸</h1>
    <p>Diskon hingga 70% + Gratis Ongkir ke seluruh Indonesia</p>
    <div class="badge-row">
      <span class="badge hot">🌸 FLASH SALE</span>
      <span class="badge">✅ COD Tersedia</span>
      <span class="badge">⭐ 4.9 Rating</span>
    </div>
  </div>
</div>

<!-- COUNTDOWN TIMER -->
<div class="countdown-bar">
  <div class="flash-label">
    <div class="flash-dot"></div>
    BERAKHIR DALAM
  </div>
  <div class="timer">
    <div class="time-box" id="hours">02</div>
    <span class="time-sep">:</span>
    <div class="time-box" id="mins">47</div>
    <span class="time-sep">:</span>
    <div class="time-box" id="secs">30</div>
  </div>
</div>

<!-- KATEGORI -->
<div class="section">
  <div class="section-title">Kategori Produk</div>
  <div class="cat-grid">
    <div class="cat-item"><div class="cat-icon">👗</div><div class="cat-label">Fashion</div></div>
    <div class="cat-item"><div class="cat-icon">💄</div><div class="cat-label">Kecantikan</div></div>
    <div class="cat-item"><div class="cat-icon">💅</div><div class="cat-label">Nail Care</div></div>
    <div class="cat-item"><div class="cat-icon">🌸</div><div class="cat-label">Skincare</div></div>
    <div class="cat-item"><div class="cat-icon">👜</div><div class="cat-label">Tas</div></div>
  </div>
</div>

<!-- BANNER PROMO -->
<div class="banner-row">
  <div class="banner a">
    <h3>Beli 2<br>Gratis 1! 🎀</h3>
    <p>Semua produk pilihan</p>
    <div class="cta-mini">Lihat →</div>
  </div>
  <div class="banner b">
    <h3>Voucher<br>Rp50.000! 💜</h3>
    <p>Min. belanja Rp200rb</p>
    <div class="cta-mini">Klaim →</div>
  </div>
</div>

<!-- GRATIS ONGKIR -->
<div class="freeship-bar">
  <div class="icon">🚚</div>
  <div>
    <h4>GRATIS ONGKOS KIRIM</h4>
    <p>Berlaku untuk semua produk LEXIZ BRAND</p>
  </div>
</div>

<!-- PRODUK TERLARIS -->
<div class="section-title" style="padding: 0 20px 10px;">Produk Terlaris</div>
<div class="products-grid">

  <div class="product-card">
    <div class="product-img">
      👗
      <div class="discount-tag">-65%</div>
      <div class="liked-tag">🤍</div>
    </div>
    <div class="product-info">
      <div class="product-name">Dress Korean Style Wanita Terbaru 2025</div>
      <div class="price-row">
        <span class="price-now">Rp89.000</span>
        <span class="price-orig">Rp255.000</span>
      </div>
      <div class="sold-bar">
        <div class="sold-track"><div class="sold-fill" style="width:82%"></div></div>
        <div class="sold-label">Terjual 1.200+</div>
      </div>
    </div>
  </div>

  <div class="product-card">
    <div class="product-img">
      💄
      <div class="discount-tag">-50%</div>
      <div class="liked-tag">💗</div>
    </div>
    <div class="product-info">
      <div class="product-name">Lipstik Matte Tahan Lama 12 Jam Anti Luntur</div>
      <div class="price-row">
        <span class="price-now">Rp45.000</span>
        <span class="price-orig">Rp90.000</span>
      </div>
      <div class="sold-bar">
        <div class="sold-track"><div class="sold-fill" style="width:67%"></div></div>
        <div class="sold-label">Terjual 890+</div>
      </div>
    </div>
  </div>

  <div class="product-card">
    <div class="product-img">
      👜
      <div class="discount-tag">-40%</div>
      <div class="liked-tag">🤍</div>
    </div>
    <div class="product-info">
      <div class="product-name">Tas Selempang Mini Wanita Aesthetic Cute</div>
      <div class="price-row">
        <span class="price-now">Rp129.000</span>
        <span class="price-orig">Rp215.000</span>
      </div>
      <div class="sold-bar">
        <div class="sold-track"><div class="sold-fill" style="width:55%"></div></div>
        <div class="sold-label">Terjual 540+</div>
      </div>
    </div>
  </div>

  <div class="product-card">
    <div class="product-img">
      🌸
      <div class="discount-tag">-70%</div>
      <div class="liked-tag">🤍</div>
    </div>
    <div class="product-info">
      <div class="product-name">Skincare Serum Brightening Glowing All Skin</div>
      <div class="price-row">
        <span class="price-now">Rp59.000</span>
        <span class="price-orig">Rp195.000</span>
      </div>
      <div class="sold-bar">
        <div class="sold-track"><div class="sold-fill" style="width:91%"></div></div>
        <div class="sold-label">Terjual 2.300+</div>
      </div>
    </div>
  </div>

</div>

<!-- TOMBOL CTA -->
<div class="cta-section">
  <button class="cta-btn">🛍️ Belanja Sekarang di LEXIZ BRAND</button>
</div>

<!-- FOOTER -->
<div class="footer">
  <p><strong>LEXIZ BRAND</strong> · Official Shopee Store · Pink Elegant Collection 🌸</p>
</div>

<script>
  let totalSeconds = 2 * 3600 + 47 * 60 + 30;
  function updateTimer() {
    if (totalSeconds <= 0) return;
    totalSeconds--;
    const h = Math.floor(totalSeconds / 3600);
    const m = Math.floor((totalSeconds % 3600) / 60);
    const s = totalSeconds % 60;
    document.getElementById('hours').textContent = String(h).padStart(2, '0');
    document.getElementById('mins').textContent = String(m).padStart(2, '0');
    document.getElementById('secs').textContent = String(s).padStart(2, '0');
  }
  setInterval(updateTimer, 1000);
</script>

</body>
</html>
