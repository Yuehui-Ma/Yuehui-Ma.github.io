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
        and the beauty of looking up at the night sky, etc. 
    </p>

    <p>
        I believe that good science grows also from curiosity, kindness, collaboration, 
        and the joy of discovering something beautiful.
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
    color: #33456b;
    background:
        radial-gradient(circle at 88% 15%, rgba(255, 236, 178, 0.45), transparent 20%),
        radial-gradient(circle at 72% 82%, rgba(255, 208, 245, 0.28), transparent 28%),
        radial-gradient(circle at 18% 18%, rgba(189, 233, 255, 0.45), transparent 35%),
        radial-gradient(circle at 55% 48%, rgba(255, 255, 255, 0.35), transparent 55%),
        linear-gradient(
            135deg,
            #eef7ff 0%,
            #dff2ff 25%,
            #e8ecff 55%,
            #f4e8ff 82%,
            #fff6fb 100%
        );
    border: 1px solid rgba(255, 255, 255, 0.75);
    backdrop-filter: blur(16px);
    box-shadow:
        0 18px 45px rgba(130, 150, 210, 0.15),
        0 6px 18px rgba(255, 255, 255, 0.45) inset;
}

.welcome-card::before {
    content: "";
    position: absolute;
    inset: 0;
    background-image:
        radial-gradient(circle, rgba(255, 220, 120, 0.95) 0 1px, transparent 1.8px),
        radial-gradient(circle, rgba(255, 250, 210, 0.8) 0 1px, transparent 1.6px),
        radial-gradient(circle, rgba(255, 255, 255, 0.6) 0 0.8px, transparent 1.4px);
    background-size: 120px 120px, 180px 180px, 75px 75px;
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
    background: linear-gradient(120deg, transparent 0%, rgba(255, 224, 160, 0.18) 34%, rgba(170, 210, 255, 0.20) 50%, rgba(245, 190, 255, 0.16) 66%, transparent 100%);
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
    background: linear-gradient(
        90deg,
        #4d79d8,
        #5ea7ff,
        #8d82e8,
        #b884dd
    );
    -webkit-background-clip: text;
    background-clip: text;
    color: transparent;
    text-shadow: none;
}

.welcome-subtitle {
    color: #6f7fa5;
    font-size: 1.03rem;
    margin-bottom: 1.2rem;
    font-style: italic;
    letter-spacing: 0.02em;
}

.welcome-card hr {
    border-color: rgba(130, 155, 210, 0.28);
}

.welcome-card p {
    font-size: 1.02rem;
    line-height: 1.72;
    color: #52627d;
}

.welcome-signature {
    margin-top: 1.8rem;
    color: #7d6fd8 !important;
    font-size: 1.15rem !important;
    text-shadow: none;
}
</style>