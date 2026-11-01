
<!DOCTYPE html>
<html lang="bn">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Full Vibes - Anime Wallpapers</title>
<style>
*{box-sizing:border-box}
body{margin:0;background:#0b0b10;color:#fff;font-family:Arial,sans-serif}
header{background:#14141c;padding:18px 5%;display:flex;justify-content:space-between;align-items:center;gap:12px;flex-wrap:wrap}
.logo{font-size:25px;font-weight:bold;color:#ff354d}
nav a{color:white;text-decoration:none;margin-left:14px}
.hero{padding:48px 6%;background:linear-gradient(120deg,#35102c,#15152c,#101018)}
.hero h1{font-size:38px;margin:0 0 12px}
.hero p{color:#ddd;line-height:1.7}
.search{width:100%;padding:15px;border-radius:12px;border:1px solid #383843;background:#1b1b24;color:white;font-size:16px;margin-top:15px}
main{padding:24px 5%}
h2{margin-top:28px}
.gallery{display:grid;grid-template-columns:repeat(2,minmax(0,1fr));gap:14px}
.card{background:#191920;border-radius:12px;overflow:hidden}
.poster{width:100%;aspect-ratio:3/4;display:flex;align-items:center;justify-content:center;text-align:center;padding:12px;font-size:23px;font-weight:bold;background:linear-gradient(145deg,#351044,#e73565)}
.card:nth-child(2) .poster{background:linear-gradient(145deg,#063e5c,#32b6c8)}
.card:nth-child(3) .poster{background:linear-gradient(145deg,#290c17,#ed453c)}
.card:nth-child(4) .poster{background:linear-gradient(145deg,#151d49,#7657cb)}
.card:nth-child(5) .poster{background:linear-gradient(145deg,#17402c,#7bba75)}
.card:nth-child(6) .poster{background:linear-gradient(145deg,#492b0b,#e5a34c)}
.info{padding:12px}
.info h3{font-size:16px;margin:0 0 8px}
.info p{color:#aaa;font-size:13px}
.btn{display:block;text-align:center;background:#ed1734;color:white;text-decoration:none;padding:11px 6px;border-radius:8px;font-weight:bold}
.note{color:#aaa;font-size:13px;line-height:1.6}
footer{text-align:center;padding:25px;background:#14141c;color:#aaa;font-size:13px}
@media(min-width:650px){.gallery{grid-template-columns:repeat(3,minmax(0,1fr))}.hero h1{font-size:48px}}
</style>
</head>
<body>
<header>
  <div class="logo">FULL VIBES</div>
  <nav><a href="#home">হোম</a><a href="#gallery">Anime</a></nav>
</header>

<section class="hero" id="home">
  <h1>Anime Wallpaper World</h1>
  <p>তোমার পছন্দের Anime ওয়ালপেপার খুঁজে নাও।<br>মোবাইলের জন্য সুন্দর ছবি, এক জায়গায়!</p>
  <input class="search" id="search" placeholder="🔎 Anime ছবি খুঁজুন..." oninput="searchImages()">
</section>

<main id="gallery">
  <h2>🔥 Popular Wallpapers</h2>
  <div class="gallery" id="galleryList">
    <article class="card" data-name="shadow legend dark anime">
      <div class="poster">SHADOW<br>LEGEND</div>
      <div class="info"><h3>Shadow Legend</h3><p>Dark Anime</p>
      <a class="btn" href="https://placehold.co/600x900/351044/ffffff?text=Shadow+Legend" download="shadow-legend.png">ছবি ডাউনলোড</a></div>
    </article>
    <article class="card" data-name="ocean soul blue anime">
      <div class="poster">OCEAN<br>SOUL</div>
      <div class="info"><h3>Ocean Soul</h3><p>Blue Anime</p>
      <a class="btn" href="https://placehold.co/600x900/063e5c/ffffff?text=Ocean+Soul" download="ocean-soul.png">ছবি ডাউনলোড</a></div>
    </article>
    <article class="card" data-name="crimson night red anime">
      <div class="poster">CRIMSON<br>NIGHT</div>
      <div class="info"><h3>Crimson Night</h3><p>Fantasy Anime</p>
      <a class="btn" href="https://placehold.co/600x900/650d20/ffffff?text=Crimson+Night" download="crimson-night.png">ছবি ডাউনলোড</a></div>
    </article>
    <article class="card" data-name="purple dream anime">
      <div class="poster">PURPLE<br>DREAM</div>
      <div class="info"><h3>Purple Dream</h3><p>Dream Anime</p>
      <a class="btn" href="https://placehold.co/600x900/302060/ffffff?text=Purple+Dream" download="purple-dream.png">ছবি ডাউনলোড</a></div>
    </article>
    <article class="card" data-name="forest spirit anime">
      <div class="poster">FOREST<br>SPIRIT</div>
      <div class="info"><h3>Forest Spirit</h3><p>Nature Anime</p>
      <a class="btn" href="https://placehold.co/600x900/17402c/ffffff?text=Forest+Spirit" download="forest-spirit.png">ছবি ডাউনলোড</a></div>
    </article>
    <article class="card" data-name="golden flame anime">
      <div class="poster">GOLDEN<br>FLAME</div>
      <div class="info"><h3>Golden Flame</h3><p>Action Anime</p>
      <a class="btn" href="https://placehold.co/600x900/492b0b/ffffff?text=Golden+Flame" download="golden-flame.png">ছবি ডাউনলোড</a></div>
    </article>
  </div>
  <p class="note">নোট: এগুলো আপাতত নমুনা পোস্টার। পরে অনুমতিপ্রাপ্ত আসল Anime ওয়ালপেপার যোগ করতে হবে।</p>
</main>

<footer>© 2026 Full Vibes · Anime Wallpapers</footer>

<script>
function searchImages(){
  const q=document.getElementById('search').value.toLowerCase().trim();
  document.querySelectorAll('.card').forEach(card=>{
    card.style.display=card.dataset.name.includes(q)?'block':'none';
  });
}
</script>
</body>
</html>
