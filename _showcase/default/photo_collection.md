
---
show: true
width: 8
date: 2021-09-12 00:01:00 +0800
---

<div class="group-memory-card">
  <div class="group-memory-header">
    <div>
      <div class="group-memory-kicker">People & Collaboration</div>
      <h5>Moments Along the Research Journey</h5>
    </div>
    <span class="group-memory-star">✦</span>
  </div>

  <div id="groupMemoryCarousel" class="carousel slide" data-ride="carousel">
    <ol class="carousel-indicators group-memory-indicators">
      <li data-target="#groupMemoryCarousel" data-slide-to="0" class="active"></li>
      <li data-target="#groupMemoryCarousel" data-slide-to="1"></li>
      <li data-target="#groupMemoryCarousel" data-slide-to="2"></li>
    </ol>

    <div class="carousel-inner group-memory-frame">
      <div class="carousel-item active">
        <a href="{{ '/assets/images/photos/group_wang.jpg' | relative_url }}" target="_blank">
          <img src="{{ '/assets/images/photos/group_wang.jpg' | relative_url }}"
               class="d-block w-100 group-memory-image"
               alt="Molecular Clouds and Star Formation Group">
        </a>
        <div class="group-memory-caption">
          <h6>Molecular Clouds and Star Formation Group</h6>
          <p>Working with Prof. Hongchi Wang’s research group.</p>
        </div>
      </div>

      <div class="carousel-item">
        <a href="{{ '/assets/images/photos/group_chen.jpg' | relative_url }}" target="_blank">
          <img src="{{ '/assets/images/photos/group_chen.jpg' | relative_url }}"
               class="d-block w-100 group-memory-image"
               alt="Graduation celebration in the Research Group of Molecular Gas in the Milky Way">
        </a>
        <div class="group-memory-caption">
          <h6>Graduation Celebration</h6>
          <p>Celebrating the graduation of students in Prof. Xuepeng Chen’s research group.</p>
        </div>
      </div>

      <div class="carousel-item">
        <a href="{{ '/assets/images/photos/mwisp_meeting.jpg' | relative_url }}" target="_blank">
          <img src="{{ '/assets/images/photos/mwisp_meeting.jpg' | relative_url }}"
               class="d-block w-100 group-memory-image"
               alt="MWISP collaboration meeting">
        </a>
        <div class="group-memory-caption">
          <h6>MWISP Collaboration</h6>
          <p>Group photo at the 2024 MWISP collaboration meeting.</p>
        </div>
      </div>
    </div>

    <a class="carousel-control-prev group-memory-control" href="#groupMemoryCarousel" role="button" data-slide="prev">
      <span class="carousel-control-prev-icon" aria-hidden="true"></span>
      <span class="sr-only">Previous</span>
    </a>
    <a class="carousel-control-next group-memory-control" href="#groupMemoryCarousel" role="button" data-slide="next">
      <span class="carousel-control-next-icon" aria-hidden="true"></span>
      <span class="sr-only">Next</span>
    </a>
  </div>
</div>

<style>
.group-memory-card {
  overflow: hidden;
  border-radius: 1.25rem;
  background:
    radial-gradient(circle at 12% 12%, rgba(255, 236, 178, 0.45), transparent 26%),
    radial-gradient(circle at 86% 16%, rgba(197, 229, 255, 0.52), transparent 30%),
    radial-gradient(circle at 72% 92%, rgba(238, 214, 255, 0.44), transparent 36%),
    linear-gradient(135deg, #fffdf7 0%, #eef8ff 46%, #f8efff 100%);
  border: 1px solid rgba(255, 255, 255, 0.86);
  box-shadow:
    0 16px 42px rgba(84, 102, 150, 0.14),
    0 6px 18px rgba(255, 255, 255, 0.58) inset;
}

.group-memory-header {
  display: flex;
  justify-content: space-between;
  align-items: flex-start;
  padding: 1.15rem 1.25rem 0.75rem 1.25rem;
}

.group-memory-kicker {
  margin-bottom: 0.25rem;
  font-size: 0.76rem;
  letter-spacing: 0.08em;
  text-transform: uppercase;
  color: #8a84c8;
  font-weight: 700;
}

.group-memory-header h5 {
  margin: 0;
  color: #24365f;
  font-weight: 800;
}

.group-memory-star {
  color: rgba(218, 166, 57, 0.68);
  font-size: 1.25rem;
  line-height: 1;
}

.group-memory-frame {
  margin: 0 1rem 1rem 1rem;
  border-radius: 1rem;
  padding: 0.45rem;
  background:
    linear-gradient(135deg, rgba(255, 221, 150, 0.70), rgba(178, 217, 255, 0.78), rgba(232, 194, 255, 0.72));
  box-shadow: 0 10px 28px rgba(84, 102, 150, 0.14);
}

.group-memory-image {
  height: 380px;
  object-fit: cover;
  border-radius: 0.78rem 0.78rem 0 0;
}

.group-memory-caption {
  padding: 1rem 1.15rem 1.15rem 1.15rem;
  border-radius: 0 0 0.78rem 0.78rem;
  background: rgba(255, 255, 255, 0.88);
  color: #52627d;
}

.group-memory-caption h6 {
  margin: 0 0 0.3rem 0;
  color: #30426f;
  font-weight: 800;
}

.group-memory-caption p {
  margin: 0;
  font-size: 0.92rem;
  line-height: 1.55;
}

.group-memory-control {
  width: 9%;
}

.group-memory-indicators {
  bottom: 7.1rem;
}

.group-memory-indicators li {
  background-color: rgba(255, 255, 255, 0.85);
}

@media (max-width: 768px) {
  .group-memory-image {
    height: 260px;
  }
  .group-memory-indicators {
    bottom: 8rem;
  }
}
</style>
