---
show: true
width: 4
date: 2020-01-12 00:01:00 +0800
---

<div class="little-prince-card">
  <div class="little-prince-image-wrap">
    <img src="{{ 'assets/images/etc/rose.jpg' | relative_url }}"
         class="little-prince-image"
         alt="Illustration inspired by The Little Prince and the rose">
  </div>

  <div class="little-prince-body">
    <div class="little-prince-kicker">My Favorite Book</div>
    <h5>The Little Prince</h5>
    <p class="little-prince-author">Antoine de Saint-Exupéry</p>

    <blockquote>
      “It is only with the heart that one can see rightly; what is essential is invisible to the eye.”
    </blockquote>

    <p class="little-prince-note">
      A quiet reminder of love, friendship, and the beauty of seeing beyond appearances.
    </p>
  </div>
</div>

<style>
.little-prince-card {
  overflow: hidden;
  border-radius: 1.25rem;
  background:
    radial-gradient(circle at 12% 12%, rgba(255, 239, 182, 0.44), transparent 26%),
    radial-gradient(circle at 88% 20%, rgba(204, 229, 255, 0.52), transparent 30%),
    radial-gradient(circle at 70% 86%, rgba(242, 215, 255, 0.42), transparent 34%),
    linear-gradient(135deg, #fffaf0 0%, #eef7ff 43%, #f6edff 100%);
  border: 1px solid rgba(255, 255, 255, 0.82);
  box-shadow:
    0 16px 40px rgba(96, 112, 160, 0.14),
    0 6px 18px rgba(255, 255, 255, 0.55) inset;
  position: relative;
}

.little-prince-card::before {
  content: "✦  ✧     ✦        ✧";
  position: absolute;
  top: 0.85rem;
  right: 1rem;
  color: rgba(218, 166, 57, 0.55);
  font-size: 1rem;
  letter-spacing: 0.55rem;
  pointer-events: none;
}

.little-prince-image-wrap {
  padding: 1rem 1rem 0 1rem;
}

.little-prince-image {
  width: 100%;
  display: block;
  border-radius: 1rem;
  object-fit: cover;
  box-shadow: 0 10px 25px rgba(80, 90, 130, 0.14);
}

.little-prince-body {
  padding: 1.1rem 1.25rem 1.25rem 1.25rem;
}

.little-prince-kicker {
  margin-bottom: 0.25rem;
  font-size: 0.78rem;
  letter-spacing: 0.08em;
  text-transform: uppercase;
  color: #8a84c8;
  font-weight: 700;
}

.little-prince-body h5 {
  margin: 0;
  font-weight: 800;
  color: #24365f;
}

.little-prince-author {
  margin: 0.2rem 0 0.9rem 0;
  color: #7c86a8;
  font-size: 0.88rem;
  font-style: italic;
}

.little-prince-body blockquote {
  margin: 0;
  padding: 0.95rem 1rem;
  border-left: 3px solid rgba(132, 121, 218, 0.45);
  border-radius: 0.8rem;
  background: rgba(255, 255, 255, 0.55);
  color: #35456e;
  font-size: 0.96rem;
  line-height: 1.62;
  font-style: italic;
}

.little-prince-note {
  margin: 0.9rem 0 0 0;
  color: #697693;
  font-size: 0.86rem;
  line-height: 1.58;
}
</style>
