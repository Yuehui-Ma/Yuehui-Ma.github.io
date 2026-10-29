---
show: true
width: 4
date: 2020-01-12 00:01:00 +0800
---

<div class="movie-carousel-card">
  <div class="movie-carousel-header">
    <div class="movie-carousel-kicker">Favorite Movies</div>
    <h5>Stories That Touched Me</h5>
  </div>

  <div id="movieCarousel" class="carousel slide" data-ride="carousel">
    <ol class="carousel-indicators movie-carousel-indicators">
      <li data-target="#movieCarousel" data-slide-to="0" class="active"></li>
      <li data-target="#movieCarousel" data-slide-to="1"></li>
      <li data-target="#movieCarousel" data-slide-to="2"></li>
      <li data-target="#movieCarousel" data-slide-to="3"></li>
      <li data-target="#movieCarousel" data-slide-to="4"></li>
      <li data-target="#movieCarousel" data-slide-to="5"></li>
    </ol>

    <div class="carousel-inner movie-carousel-frame">
      <div class="carousel-item active">
        <div class="movie-poster-wrap">
          <img src="{{ 'assets/images/etc/movie1.jpg' | relative_url }}"
               class="movie-poster"
               alt="Coco">
        </div>
        <div class="movie-caption">
          <h6>Coco</h6>
          <p>Remembering love, family, and the songs that keep people close.</p>
        </div>
      </div>

      <div class="carousel-item">
        <div class="movie-poster-wrap">
          <img src="{{ 'assets/images/etc/movie2.jpg' | relative_url }}"
               class="movie-poster"
               alt="Frozen">
        </div>
        <div class="movie-caption">
          <h6>Frozen</h6>
          <p>A story about courage, sisterhood, and learning to embrace oneself.</p>
        </div>
      </div>

      <div class="carousel-item">
        <div class="movie-poster-wrap">
          <img src="{{ 'assets/images/etc/movie3.jpg' | relative_url }}"
               class="movie-poster"
               alt="Hotel Transylvania">
        </div>
        <div class="movie-caption">
          <h6>Hotel Transylvania</h6>
          <p>A playful reminder that family can be wonderfully unexpected.</p>
        </div>
      </div>

      <div class="carousel-item">
        <div class="movie-poster-wrap">
          <img src="{{ 'assets/images/etc/movie4.jpg' | relative_url }}"
               class="movie-poster"
               alt="La La Land">
        </div>
        <div class="movie-caption">
          <h6>La La Land</h6>
          <p>For the fools who dream, and for the tenderness of paths not taken.</p>
        </div>
      </div>

      <div class="carousel-item">
        <div class="movie-poster-wrap">
          <img src="{{ 'assets/images/etc/movie5.jpg' | relative_url }}"
               class="movie-poster"
               alt="Interstellar">
        </div>
        <div class="movie-caption">
          <h6>Interstellar</h6>
          <p>A journey through space, time, love, and the longing to understand the Universe.</p>
        </div>
      </div>

      <div class="carousel-item">
        <div class="movie-poster-wrap">
          <img src="{{ 'assets/images/etc/movie6.jpg' | relative_url }}"
               class="movie-poster"
               alt="The Martian">
        </div>
        <div class="movie-caption">
          <h6>The Martian</h6>
          <p>Solving one problem, then the next — with science, humor, and hope.</p>
        </div>
      </div>
    </div>

    <a class="carousel-control-prev movie-carousel-control" href="#movieCarousel" role="button" data-slide="prev">
      <span class="carousel-control-prev-icon" aria-hidden="true"></span>
      <span class="sr-only">Previous</span>
    </a>
    <a class="carousel-control-next movie-carousel-control" href="#movieCarousel" role="button" data-slide="next">
      <span class="carousel-control-next-icon" aria-hidden="true"></span>
      <span class="sr-only">Next</span>
    </a>
  </div>
</div>

<style>
.movie-carousel-card {
  overflow: hidden;
  border-radius: 1.25rem;
  background:
    radial-gradient(circle at 15% 15%, rgba(255, 235, 180, 0.45), transparent 28%),
    radial-gradient(circle at 82% 20%, rgba(198, 228, 255, 0.45), transparent 30%),
    radial-gradient(circle at 72% 86%, rgba(240, 215, 255, 0.40), transparent 34%),
    linear-gradient(135deg, #fffdf7 0%, #eef8ff 45%, #f7efff 100%);
  border: 1px solid rgba(255, 255, 255, 0.82);
  box-shadow:
    0 16px 40px rgba(90, 105, 150, 0.14),
    0 6px 18px rgba(255, 255, 255, 0.55) inset;
  position: relative;
}

.movie-carousel-card::before {
  content: "✦  ✧     ✦";
  position: absolute;
  right: 1rem;
  top: 0.9rem;
  color: rgba(218, 166, 57, 0.55);
  letter-spacing: 0.45rem;
  pointer-events: none;
  z-index: 2;
}

.movie-carousel-header {
  padding: 1.15rem 1.25rem 0.75rem 1.25rem;
}

.movie-carousel-kicker {
  margin-bottom: 0.25rem;
  font-size: 0.76rem;
  letter-spacing: 0.08em;
  text-transform: uppercase;
  color: #8a84c8;
  font-weight: 700;
}

.movie-carousel-header h5 {
  margin: 0;
  color: #24365f;
  font-weight: 800;
}

.movie-carousel-frame {
  margin: 0 1rem 1rem 1rem;
  border-radius: 1rem;
  padding: 0.45rem;
  background:
    linear-gradient(135deg, rgba(255, 221, 150, 0.68), rgba(178, 217, 255, 0.76), rgba(232, 194, 255, 0.70));
  box-shadow: 0 10px 28px rgba(84, 102, 150, 0.14);
}

.movie-poster-wrap {
  height: 320px;
  display: flex;
  align-items: center;
  justify-content: center;
  border-radius: 0.78rem 0.78rem 0 0;
  background: rgba(255, 255, 255, 0.86);
  overflow: hidden;
}

.movie-poster {
  max-width: 100%;
  max-height: 100%;
  width: auto;
  height: auto;
  object-fit: contain;
  display: block;
}

.movie-caption {
  padding: 1rem 1.15rem 1.15rem 1.15rem;
  border-radius: 0 0 0.78rem 0.78rem;
  background: rgba(255, 255, 255, 0.90);
  color: #52627d;
  min-height: 118px;
}

.movie-caption h6 {
  margin: 0 0 0.3rem 0;
  color: #30426f;
  font-weight: 800;
}

.movie-caption p {
  margin: 0;
  font-size: 0.9rem;
  line-height: 1.55;
}

.movie-carousel-control {
  width: 12%;
}

.movie-carousel-indicators {
  bottom: 7.1rem;
}

.movie-carousel-indicators li {
  background-color: rgba(255, 255, 255, 0.90);
}

@media (max-width: 768px) {
  .movie-poster-wrap {
    height: 260px;
  }
  .movie-caption {
    min-height: 132px;
  }
  .movie-carousel-indicators {
    bottom: 8.2rem;
  }
}
</style>
