---
show: true
width: 8
date: 2024-01-12 00:01:00 +0800
---

<div class="p-5 welcome-card">
    <h2>Beyond Research</h2>
    <p class="welcome-subtitle">Looking beyond the papers, beneath the same Milky Way.</p>
    <hr />

    <p>
        Welcome to a small corner of my world.
    </p>

    <p>
        As an astronomer, I spend much of my time studying molecular clouds,
        interstellar turbulence, and the structure of our Milky Way.
        But science is only one part of the journey.
    </p>

    <p>
        This page is where I share the people, places, and moments that have shaped me —
        research groups that became family, conferences that inspired new ideas,
        books worth remembering, curious cats waiting at home,
        and the beauty of looking up at the night sky.
    </p>

    <p>
        I believe that good science grows not only from equations and observations,
        but also from curiosity, kindness, collaboration, and the joy of discovering
        something beautiful.
    </p>

    <p class="welcome-signature">
        <em>Keep looking up. ✨</em>
    </p>
</div>

<style>
.welcome-card {
    position: relative;
    overflow: hidden;
    min-height: 360px;
    border-radius: 1.25rem;
    color: #f6fbff;
    background:
        radial-gradient(circle at 85% 20%, rgba(149, 118, 255, 0.32), transparent 28%),
        radial-gradient(circle at 20% 85%, rgba(62, 170, 255, 0.20), transparent 30%),
        linear-gradient(135deg, rgba(5, 12, 30, 0.96), rgba(9, 24, 55, 0.92) 50%, rgba(30, 18, 60, 0.88));
    box-shadow: 0 18px 45px rgba(5, 12, 30, 0.28);
}

.welcome-card::before {
    content: "";
    position: absolute;
    inset: 0;
    background-image:
        radial-gradient(circle, rgba(255,255,255,0.95) 0 1px, transparent 1.5px),
        radial-gradient(circle, rgba(180,210,255,0.8) 0 1px, transparent 1.5px);
    background-size: 72px 72px, 118px 118px;
    background-position: 0 0, 35px 42px;
    opacity: 0.28;
    pointer-events: none;
}

.welcome-card::after {
    content: "";
    position: absolute;
    right: -12%;
    top: -8%;
    width: 62%;
    height: 120%;
    background: linear-gradient(120deg, transparent 0%, rgba(120, 180, 255, 0.10) 34%, rgba(210, 160, 255, 0.18) 50%, rgba(120, 180, 255, 0.08) 66%, transparent 100%);
    transform: rotate(-16deg);
    filter: blur(0.5px);
    pointer-events: none;
}

.welcome-card > * {
    position: relative;
    z-index: 1;
    max-width: 760px;
}

.welcome-card h2 {
    margin-bottom: 0.25rem;
    font-size: 2.35rem;
    font-weight: 800;
    letter-spacing: -0.03em;
    background: linear-gradient(90deg, #ffffff, #8fd3ff 45%, #d9a2ff 82%);
    -webkit-background-clip: text;
    background-clip: text;
    color: transparent;
}

.welcome-subtitle {
    color: #b8d9ff;
    font-size: 1.03rem;
    margin-bottom: 1.2rem;
}

.welcome-card hr {
    border-color: rgba(180, 215, 255, 0.35);
}

.welcome-card p {
    font-size: 1.02rem;
    line-height: 1.72;
    color: rgba(246, 251, 255, 0.92);
}

.welcome-signature {
    margin-top: 1.8rem;
    color: #d8c2ff !important;
    font-size: 1.08rem !important;
}
</style>