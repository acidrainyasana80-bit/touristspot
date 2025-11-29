<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Sarangani Adventure — Paragliding, Whitewater Tubing & Tuka Marine Park</title>
  <style>
    :root{--accent:#ffb300;--dark:#0b1a2b;--muted:#667788}
    *{box-sizing:border-box}
    body{margin:0;font-family:Inter,system-ui,Segoe UI,Roboto,Arial;background:#f7fafc;color:#122;line-height:1.5}
    header{background:linear-gradient(90deg,var(--dark),#123347);color:white;padding:18px 24px}
    .container{max-width:1100px;margin:0 auto;padding:24px}
    nav{display:flex;align-items:center;justify-content:space-between;gap:12px}
    .brand{font-weight:700;letter-spacing:0.6px}
    .nav-links{display:flex;gap:14px}
    .nav-links a{color:rgba(255,255,255,0.9);text-decoration:none;padding:8px 10px;border-radius:8px}
    .nav-links a:hover{background:rgba(255,255,255,0.06)}
    .hero{display:grid;grid-template-columns:1fr;gap:18px;align-items:center;padding:28px 0}
    .hero .intro{background:linear-gradient(180deg,rgba(255,255,255,0.04),transparent);padding:20px;border-radius:12px}
    h1{margin:0 0 8px;font-size:28px}
    p.lead{margin:0;color:var(--muted)}

    /* grid for cards */
    .grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(280px,1fr));gap:18px;margin-top:20px}
    .card{background:white;border-radius:12px;box-shadow:0 6px 18px rgba(6,22,34,0.08);overflow:hidden}
    .card img{width:100%;height:220px;object-fit:cover;display:block}
    .card-body{padding:16px}
    .card h3{margin:0 0 8px}
    .meta{font-size:13px;color:var(--muted);margin-bottom:8px}
    ul.activities{padding-left:18px;margin:8px 0}
    footer{padding:18px 0;color:var(--muted);text-align:center}

    /* simple responsive nav for mobile */
    @media (max-width:640px){
      h1{font-size:22px}
      .hero{grid-template-columns:1fr}
    }
    .badge{display:inline-block;background:var(--accent);color:#082335;padding:6px 10px;border-radius:999px;font-weight:700;font-size:13px}
    .map{height:200px;border-radius:8px;background:linear-gradient(180deg,#e6f7ff,#fff);display:flex;align-items:center;justify-content:center;color:var(--muted);font-weight:600}
  </style>
</head>
<body>
  <header>
    <div class="container">
      <nav>
        <div class="brand">Sarangani<span style="color:var(--accent)">Adventure</span></div>
        <div class="nav-links">
          <a href="#paragliding">Paragliding</a>
          <a href="#tuka">Tuka Marine Park</a>
          <a href="#tubing">Whitewater Tubing</a>
          <a href="#plan">Plan a Trip</a>
        </div>
      </nav>
    </div>
  </header>

  <main class="container">
    <section class="hero">
      <div class="intro">
        <h1>Explore Sarangani Province — Thrill, Nature & Beach Escapes</h1>
        <p class="lead">This mini-site features three must-visit experiences in Sarangani Province: paragliding in Maasim, Tuka Marine Park in Kiamba, and whitewater tubing in Maitum. Use the navigation above to jump between spots.</p>
      </div>
    </section>

    <section id="paragliding" class="grid">
      <article class="card">
        <!-- Image: paragliding (place file named 1000011163.jpg in the same folder or in images/) -->
        <img src="1000011163.jpg" alt="Paragliding in Maasim, Sarangani">
        <div class="card-body">
          <h3>Paragliding — Maasim</h3>
          <div class="meta">Location: Maasim, Sarangani Province</div>
          <p>Soar above coastal cliffs and turquoise seas. Paragliding in Maasim offers breathtaking aerial views of Sarangani Bay and the surrounding islands.</p>
          <strong>Activities</strong>
          <ul class="activities">
            <li>Tandem paragliding flights with certified pilots</li>
            <li>Photography and aerial videography</li>
            <li>Short hikes to launch points / cliffside viewpoints</li>
          </ul>
          <div class="meta">Best time: Dry season (November–May). Bring a windbreaker and sun protection.</div>
        </div>
      </article>

      <article class="card" id="tuka">
        <!-- Image: tuka marine park (place file named 1000011161.png) -->
        <img src="1000011161.png" alt="Tuka Marine Park, Kiamba">
        <div class="card-body">
          <h3>Tuka Marine Park — Kiamba</h3>
          <div class="meta">Location: Kiamba, Sarangani Province</div>
          <p>Tuka Marine Park is a tropical beach lined with coconut trees, clear water, and sheltered bays ideal for swimming and snorkeling.</p>
          <strong>Activities</strong>
          <ul class="activities">
            <li>Beach lounging, swimming and snorkeling</li>
            <li>Island hopping and boat tours</li>
            <li>Picnics, campfires and local seafood stalls</li>
          </ul>
          <div class="meta">Tip: Pack reef-safe sunscreen and a snorkel set if you have one.</div>
        </div>
      </article>

      <article class="card" id="tubing">
        <!-- Image: whitewater tubing (place file named 1000011162.jpg) -->
        <img src="1000011162.jpg" alt="Whitewater Tubing in Maitum, Sarangani">
        <div class="card-body">
          <h3>Whitewater Tubing — Maitum</h3>
          <div class="meta">Location: Maitum, Sarangani Province</div>
          <p>Ride the rapids on an inner tube through scenic river canyons. Whitewater tubing in Maitum is fun for adventurous groups and families (routes vary in intensity).</p>
          <strong>Activities</strong>
          <ul class="activities">
            <li>Guided tubing trips with safety gear</li>
            <li>Cliff-side picnics and riverside rest stops</li>
            <li>Short swims and rock-jumping at calmer pools</li>
          </ul>
          <div class="meta">Safety: Use a life jacket, follow your guide's instructions, and avoid tubing during heavy rains.</div>
        </div>
      </article>
    </section>

    <section id="plan" style="margin-top:26px;">
      <div class="card" style="padding:18px">
        <div style="display:flex;gap:18px;flex-wrap:wrap;align-items:center">
          <div style="flex:1;min-width:260px">
            <h3>Plan a Trip</h3>
            <p class="meta">How to use this page on GitHub Pages</p>
            <ol>
              <li>Save this file as <code>sarangani_tourist_spots.html</code>.</li>
              <li>Place the three images in the same folder as the HTML file (or in an <code>images/</code> folder and update the <code>src</code> paths accordingly). The filenames used here are: <code>1000011163.jpg</code>, <code>1000011161.png</code>, and <code>1000011162.jpg</code>.</li>
              <li>Create a GitHub repository and push the files. In the repo <strong>Settings &gt; Pages</strong>, set the source to the main branch (or <code>gh-pages</code>) and the root folder. GitHub will publish your page — the URL will usually be <code>https://&lt;your-username&gt;.github.io/&lt;repo-name&gt;/sarangani_tourist_spots.html</code>.</li>
              <li>Optional: Replace the images with higher-resolution photos and add a <code>README</code> describing credits and photo sources.</li>
            </ol>
          </div>
          <div style="flex:1;min-width:220px">
            <div class="map">Map placeholder — add a Google Maps iframe here if you want</div>
          </div>
        </div>
      </div>
    </section>

  </main>

  <footer>
    <div class="container">Made with ❤️ for Sarangani tourism • Photos: local contributors</div>
  </footer>
</body>
</html>
