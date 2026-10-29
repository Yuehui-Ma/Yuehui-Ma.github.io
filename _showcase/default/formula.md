---
show: true
width: 12
date: 2017-01-14 00:01:00 +0800
---

<div class="equation-card">

  <div class="equation-kicker">One of the Millennium Problems</div>

  <h5>The Equation That Keeps Me Curious</h5>

  <div class="equation-box">
  $$
  \rho\left(\frac{\partial \mathbf{u}}{\partial t}+\mathbf{u}\cdot\nabla\mathbf{u}\right)
  =-\nabla p
  +\mu\nabla^{2}\mathbf{u}
  +\rho\mathbf{f}
  $$
  </div>

  <p class="equation-caption">
    From a cup of coffee to hurricanes, from ocean currents to the turbulent molecular clouds of the Milky Way, the Navier–Stokes equations describe fluid motion across an astonishing range of scales. Yet whether smooth solutions always exist in three dimensions remains one of the seven Millennium Prize Problems—a question that continues to inspire mathematicians, physicists, and anyone fascinated by turbulence.
  </p>

</div>

<style>
.equation-card{
  padding:1.4rem;
  border-radius:1.25rem;
  text-align:center;
  background:
    radial-gradient(circle at 15% 15%, rgba(255,235,180,.40), transparent 28%),
    radial-gradient(circle at 82% 20%, rgba(198,228,255,.45), transparent 30%),
    radial-gradient(circle at 70% 86%, rgba(240,215,255,.38), transparent 34%),
    linear-gradient(135deg,#fffdf8 0%,#eef8ff 45%,#f7efff 100%);
  border:1px solid rgba(255,255,255,.82);
  box-shadow:
    0 16px 40px rgba(90,105,150,.14),
    inset 0 6px 18px rgba(255,255,255,.55);
  position:relative;
}

.equation-card::before{
  content:"✦  curiosity  ✦";
  position:absolute;
  top:0.9rem;
  right:1rem;
  color:rgba(218,166,57,.55);
  letter-spacing:.45rem;
}

.equation-kicker{
  display:inline-block;
  margin-bottom:.45rem;
  padding:.32rem .72rem;
  border-radius:999px;
  background:rgba(255,236,178,.70);
  border:1px solid rgba(218,166,57,.35);
  box-shadow:0 4px 12px rgba(218,166,57,.12);
  font-size:.72rem;
  text-transform:uppercase;
  letter-spacing:.08em;
  color:#9b6b00;
  font-weight:800;
}

.equation-card h5{
  margin:.2rem 0 1rem;
  color:#24365f;
  font-weight:800;
}

.equation-box{
  padding:1.25rem 1.1rem;
  border-radius:1rem;
  background:rgba(255,255,255,.78);
  border-left:4px solid rgba(218,166,57,.48);
  box-shadow:0 8px 20px rgba(100,110,160,.10);
  font-size:1.24rem;
  transition:box-shadow .25s ease, transform .25s ease;
}

.equation-box:hover{
  transform:translateY(-2px);
  box-shadow:0 12px 28px rgba(100,110,160,.16);
}

.equation-caption{
  margin-top:1rem;
  color:#667590;
  font-size:.9rem;
  line-height:1.6;
  font-style:italic;
}
</style>