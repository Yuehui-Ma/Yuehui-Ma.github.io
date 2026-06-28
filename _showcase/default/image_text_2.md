---
show: true
width: 4
date: 2020-01-12 00:01:00 +0800
---

<div class="favorite-movies-card">

  <div class="favorite-movies-body">

    <div class="favorite-movies-kicker">Favorite Movies</div>

    <h5>Stories That Stay With Me</h5>

    <p class="favorite-intro">
      Some films are more than entertainment—they quietly shape how we see the world.
    </p>

    <ul class="favorite-movie-list">
      <li>🌌 <strong>Interstellar</strong></li>
      <li>🚀 <strong>The Martian</strong></li>
      <li>🎹 <strong>La La Land</strong></li>
      <li>🚢 <strong>Titanic</strong></li>
      <li>❄️ <strong>Frozen</strong></li>
      <li>🎸 <strong>Coco</strong></li>
      <li>🧛 <strong>Hotel Transylvania</strong></li>
    </ul>

    <blockquote>
      "Stories help us travel farther than we ever could on our own."
    </blockquote>

  </div>
</div>

<style>
.favorite-movies-card{
  border-radius:1.25rem;
  overflow:hidden;
  background:
    radial-gradient(circle at 15% 15%, rgba(255,235,180,.45), transparent 28%),
    radial-gradient(circle at 82% 20%, rgba(198,228,255,.45), transparent 30%),
    radial-gradient(circle at 72% 86%, rgba(240,215,255,.40), transparent 34%),
    linear-gradient(135deg,#fffdf7 0%,#eef8ff 45%,#f7efff 100%);
  border:1px solid rgba(255,255,255,.82);
  box-shadow:0 16px 40px rgba(90,105,150,.14),0 6px 18px rgba(255,255,255,.55) inset;
  position:relative;
}
.favorite-movies-card::before{
  content:"✦ ✧ ✦";
  position:absolute;
  right:1rem;
  top:.9rem;
  color:rgba(218,166,57,.55);
  letter-spacing:.5rem;
}
.favorite-movies-body{padding:1.3rem;}
.favorite-movies-kicker{font-size:.78rem;font-weight:700;letter-spacing:.08em;text-transform:uppercase;color:#8a84c8;margin-bottom:.25rem;}
.favorite-movies-body h5{margin:0;color:#24365f;font-weight:800;}
.favorite-intro{margin:.6rem 0 1rem;color:#6c7894;font-size:.9rem;line-height:1.55;}
.favorite-movie-list{list-style:none;padding:0;margin:0 0 1rem 0;}
.favorite-movie-list li{padding:.32rem 0;color:#40506f;font-size:.96rem;}
.favorite-movies-body blockquote{margin:0;padding:.9rem 1rem;border-left:3px solid rgba(132,121,218,.45);background:rgba(255,255,255,.55);border-radius:.8rem;font-style:italic;color:#4c5d82;font-size:.9rem;}
</style>
