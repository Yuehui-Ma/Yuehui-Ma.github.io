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
    color: #f6fbff;
    background:
        radial-gradient(circle at 85% 15%, rgba(255, 196, 240, 0.42), transparent 24%),
        radial-gradient(circle at 70% 75%, rgba(255, 226, 170, 0.18), transparent 32%),
        radial-gradient(circle at 15% 80%, rgba(135, 220, 255, 0.28), transparent 36%),
        radial-gradient(circle at 55% 45%, rgba(255, 255, 255, 0.05), transparent 45%),
        linear-gradient(
            135deg,
            #243b78 0%,
            #3959a6 25%,
            #5e5ab4 52%,
            #8d70c7 76%,
            #c89ed8 100%
        );
    border: 1px solid rgba(255, 255, 255, 0.15);
    backdrop-filter: blur(10px);
    box-shadow:
        0 20px 60px rgba(70, 90, 170, 0.22),
        0 0 40px rgba(210, 170, 255, 0.08);
}

.welcome-card::before {
    content: "";
    position: absolute;
    inset: 0;
    background-image:
        radial-gradient(circle, rgba(255,255,255,0.95) 0 1px, transparent 1.5px),
        radial-gradient(circle, rgba(180,210,255,0.8) 0 1px, transparent 1.5px);
    background-size: 95px 95px, 165px 165px;
    background-position: 0 0, 35px 42px;
    opacity: 0.18;
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
    background: linear-gradient(
        90deg,
        #ffffff,
        #eaf8ff 18%,
        #9ee5ff 45%,
        #c5b4ff 72%,
        #ffd6f4 100%
    );
    -webkit-background-clip: text;
    background-clip: text;
    color: transparent;
    text-shadow:
        0 0 8px rgba(180, 220, 255, 0.25),
        0 0 20px rgba(255, 180, 255, 0.15);
}

.welcome-subtitle {
    color: #eef4ff;
    font-size: 1.03rem;
    margin-bottom: 1.2rem;
    font-style: italic;
    letter-spacing: 0.02em;
}

.welcome-card hr {
    border-color: rgba(180, 215, 255, 0.35);
}

.welcome-card p {
    font-size: 1.02rem;
    line-height: 1.72;
    color: rgba(255, 255, 255, 0.96);
}

.welcome-signature {
    margin-top: 1.8rem;
    color: #ffe4ff !important;
    font-size: 1.15rem !important;
    text-shadow: 0 0 10px rgba(255, 180, 255, 0.45);
}
</style>