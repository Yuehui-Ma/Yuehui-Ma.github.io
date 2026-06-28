---
show: true
width: 3
date: 2020-01-12 00:01:00 +0800
group: My Cats
---

<div class="cat-card">

  <img src="{{ 'assets/images/etc/cat3.jpg' | relative_url }}"
       class="cat-photo"
       alt="Xiaomeiqiu">

  <div class="cat-caption">
    <div class="cat-kicker">My Cats</div>
    <h6>Xiaomeiqiu</h6>
    <p>
      Quietly watching the world with bright eyes, always curious about everything happening around her.
    </p>
  </div>

</div>

<style>
.cat-card{
  overflow:hidden;
  border-radius:1.25rem;
  background:
    radial-gradient(circle at 18% 15%, rgba(255,236,178,.42), transparent 28%),
    radial-gradient(circle at 84% 18%, rgba(198,228,255,.45), transparent 30%),
    radial-gradient(circle at 70% 88%, rgba(240,215,255,.38), transparent 35%),
    linear-gradient(135deg,#fffdf7 0%,#eef8ff 45%,#f8efff 100%);
  border:1px solid rgba(255,255,255,.82);
  box-shadow:
    0 14px 36px rgba(90,105,150,.14),
    inset 0 6px 18px rgba(255,255,255,.55);
}

.cat-photo{
  display:block;
  width:100%;
  aspect-ratio:1/1;
  object-fit:cover;
}

.cat-caption{
  padding:1rem 1.1rem 1.15rem;
  background:rgba(255,255,255,.88);
}

.cat-kicker{
  font-size:.75rem;
  text-transform:uppercase;
  letter-spacing:.08em;
  color:#8a84c8;
  font-weight:700;
  margin-bottom:.2rem;
}

.cat-caption h6{
  margin:0;
  font-weight:800;
  color:#24365f;
}

.cat-caption p{
  margin:.45rem 0 0;
  color:#667590;
  font-size:.88rem;
  line-height:1.55;
}
</style>
