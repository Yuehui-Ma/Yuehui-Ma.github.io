
---
show: true
width: 4
date: 2020-01-12 00:01:00 +0800
---

<div class="visitor-map-card">
  <div class="visitor-map-header">
    <h5>Visitors Around the World</h5>
    <p>Places where this homepage has been viewed.</p>
  </div>

  <div class="visitor-map-wrap">
    <svg class="visitor-world-map" viewBox="0 0 1000 520" role="img" aria-label="World map with visitor locations">
      <rect x="0" y="0" width="1000" height="520" rx="22" />

      <!-- Simplified world map silhouettes; decorative, not geographic boundaries. -->
      <path d="M115,185 C150,120 250,105 310,150 C350,180 325,235 275,250 C230,263 198,292 150,275 C105,258 85,225 115,185 Z" />
      <path d="M265,285 C330,255 390,275 420,330 C450,388 420,455 360,465 C310,472 280,425 292,375 C300,338 236,318 265,285 Z" />
      <path d="M455,160 C520,95 645,98 715,160 C760,200 725,255 660,245 C600,235 548,268 500,235 C450,202 420,192 455,160 Z" />
      <path d="M555,265 C610,238 690,258 725,318 C760,380 720,458 650,462 C595,465 560,415 575,365 C588,322 510,290 555,265 Z" />
      <path d="M725,250 C780,210 860,222 910,275 C955,320 940,395 875,410 C820,423 770,392 758,342 C748,304 690,278 725,250 Z" />

      <!-- Visitor dots: adjust left/top values below when real analytics locations are available. -->
      <circle class="visitor-dot" cx="760" cy="205" r="7" />
      <circle class="visitor-dot" cx="735" cy="220" r="6" />
      <circle class="visitor-dot" cx="505" cy="160" r="6" />
      <circle class="visitor-dot" cx="470" cy="135" r="5" />
      <circle class="visitor-dot" cx="825" cy="315" r="5" />
    </svg>
  </div>

  <div class="visitor-map-caption">
    <span class="visitor-pulse"></span>
    A quiet trace of people who stopped by.
  </div>
</div>

<style>
.visitor-map-card {
  overflow: hidden;
  border-radius: 1.25rem;
  background:
    radial-gradient(circle at 80% 20%, rgba(255, 178, 232, 0.20), transparent 28%),
    linear-gradient(135deg, #f8fbff 0%, #eef5ff 45%, #f6efff 100%);
  border: 1px solid rgba(142, 165, 210, 0.22);
  box-shadow: 0 14px 35px rgba(64, 82, 130, 0.12);
}

.visitor-map-header {
  padding: 1.1rem 1.25rem 0.4rem 1.25rem;
}

.visitor-map-header h5 {
  margin: 0;
  font-weight: 750;
  color: #24365f;
}

.visitor-map-header p {
  margin: 0.25rem 0 0 0;
  font-size: 0.86rem;
  color: #6c7894;
}

.visitor-map-wrap {
  padding: 0.5rem 0.9rem 0.6rem 0.9rem;
}

.visitor-world-map {
  width: 100%;
  height: auto;
  display: block;
}

.visitor-world-map rect {
  fill: rgba(255, 255, 255, 0.58);
}

.visitor-world-map path {
  fill: rgba(112, 135, 180, 0.30);
  stroke: rgba(112, 135, 180, 0.38);
  stroke-width: 2;
}

.visitor-dot {
  fill: #ff3b4f;
  stroke: #fff;
  stroke-width: 2.5;
  filter: drop-shadow(0 0 7px rgba(255, 59, 79, 0.55));
}

.visitor-map-caption {
  display: flex;
  align-items: center;
  gap: 0.45rem;
  padding: 0 1.25rem 1.15rem 1.25rem;
  font-size: 0.86rem;
  color: #54627f;
}

.visitor-pulse {
  width: 9px;
  height: 9px;
  border-radius: 50%;
  background: #ff3b4f;
  box-shadow: 0 0 0 6px rgba(255, 59, 79, 0.12);
}
</style>
