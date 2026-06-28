---
show: true
width: 12
date: 2017-01-14 00:01:00 +0800
---

<div class="equation-card">

  <div class="equation-kicker">One of the Millennium Problems</div>

  <h5>The Equation Behind Chaos</h5>

  <div class="equation-box">
  $$
  \rho\left(\frac{\partial \mathbf{u}}{\partial t}+\mathbf{u}\cdot\nabla\mathbf{u}\right)
  =-\nabla p
  +\mu\nabla^{2}\mathbf{u}
  +\rho\mathbf{f}
  $$
  </div>

  <p class="equation-caption">
    From a cup of coffee to hurricanes, from ocean currents to the turbulent molecular clouds of the Milky Way, the Navier–Stokes equations govern fluid motion. Yet whether smooth solutions always exist in three dimensions remains one of the seven Millennium Prize Problems—an unsolved question at the frontier of modern mathematics.
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
  content:"✦  Millennium  ✦";
  position:absolute;
  top:0.9rem;
  right:1rem;
  color:rgba(218,166,57,.55);
  letter-spacing:.45rem;
}

.equation-kicker{
  font-size:.76rem;
  text-transform:uppercase;
  letter-spacing:.08em;
  color:#b57a00;
  font-weight:700;
}

.equation-card h5{
  margin:.2rem 0 1rem;
  color:#24365f;
  font-weight:800;
}

.equation-box{
  padding:1.1rem;
  border-radius:1rem;
  background:rgba(255,255,255,.72);
  box-shadow:0 6px 16px rgba(100,110,160,.08);
  font-size:1.12rem;
}

.equation-caption{
  margin-top:1rem;
  color:#667590;
  font-size:.9rem;
  line-height:1.6;
  font-style:italic;
}
</style>