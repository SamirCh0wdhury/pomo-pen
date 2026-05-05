<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>PomoPen — Reclaim Productivity. Restore Focus.</title>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link href="https://fonts.googleapis.com/css2?family=Playfair+Display:ital,wght@0,400;0,700;0,900;1,400;1,700&family=DM+Mono:wght@300;400;500&family=Inter:wght@300;400;500&display=swap" rel="stylesheet">
<style>
  :root {
    --ink: #1e3a2f;
    --cream: #f5efe3;
    --warm-white: #faf6ee;
    --sage: #2d5443;
    --sage-light: #4a7c5f;
    --terra: #c8452a;
    --terra-light: #e07055;
    --sand: #d6c9b0;
    --mist: #e8f0eb;
    --charcoal: #2a4035;
    --forest: #1a3028;
    --font-display: 'Playfair Display', serif;
    --font-mono: 'DM Mono', monospace;
    --font-body: 'Inter', sans-serif;
  }

  *, *::before, *::after { margin: 0; padding: 0; box-sizing: border-box; }

  html { scroll-behavior: smooth; font-size: 16px; }

  body {
    background: var(--warm-white);
    color: var(--ink);
    font-family: var(--font-body);
    font-weight: 300;
    overflow-x: hidden;
    cursor: none;
  }

  /* Custom cursor */
  .cursor {
    position: fixed;
    width: 10px; height: 10px;
    background: var(--terra);
    border-radius: 50%;
    pointer-events: none;
    z-index: 10000;
    transition: transform 0.15s ease, opacity 0.2s;
    transform: translate(-50%, -50%);
  }
  .cursor-ring {
    position: fixed;
    width: 36px; height: 36px;
    border: 1px solid var(--terra);
    border-radius: 50%;
    pointer-events: none;
    z-index: 9999;
    transition: transform 0.4s cubic-bezier(0.25,0.46,0.45,0.94), opacity 0.3s;
    transform: translate(-50%, -50%);
    opacity: 0.5;
  }

  /* NAV */
  nav {
    position: fixed; top: 0; left: 0; right: 0;
    z-index: 1000;
    padding: 1.5rem 3rem;
    display: flex; align-items: center; justify-content: space-between;
    background: rgba(30,58,47,0.92);
    backdrop-filter: blur(12px);
    border-bottom: 1px solid rgba(245,239,227,0.1);
    animation: fadeDown 0.8s ease both;
  }
  @keyframes fadeDown {
    from { opacity: 0; transform: translateY(-20px); }
    to { opacity: 1; transform: translateY(0); }
  }
  .nav-logo {
    font-family: var(--font-display);
    font-size: 1.6rem;
    font-weight: 700;
    letter-spacing: 0.02em;
    color: var(--cream);
    text-decoration: none;
    display: flex; align-items: center; gap: 0.5rem;
  }
  .nav-logo span { color: var(--terra); }
  .nav-links {
    display: flex; gap: 2.5rem; list-style: none;
  }
  .nav-links a {
    font-family: var(--font-mono);
    font-size: 0.75rem;
    font-weight: 400;
    letter-spacing: 0.1em;
    text-transform: uppercase;
    color: rgba(245,239,227,0.65);
    text-decoration: none;
    transition: color 0.25s;
  }
  .nav-links a:hover { color: var(--terra-light); }
  .nav-cta {
    font-family: var(--font-mono);
    font-size: 0.72rem;
    letter-spacing: 0.12em;
    text-transform: uppercase;
    background: var(--terra);
    color: var(--cream);
    padding: 0.65rem 1.5rem;
    border: none;
    text-decoration: none;
    transition: background 0.25s, transform 0.2s;
  }
  .nav-cta:hover { background: var(--terra-light); transform: translateY(-1px); }

  /* HERO */
  .hero {
    min-height: 100vh;
    display: grid;
    grid-template-columns: 1fr 1fr;
    position: relative;
    overflow: hidden;
    background: var(--ink);
  }
  .hero-left {
    padding: 9rem 3rem 4rem 3rem;
    display: flex; flex-direction: column; justify-content: center;
    position: relative;
    z-index: 2;
    background: var(--ink);
  }
  .hero-eyebrow {
    font-family: var(--font-mono);
    font-size: 0.7rem;
    letter-spacing: 0.2em;
    text-transform: uppercase;
    color: var(--terra-light);
    margin-bottom: 2rem;
    animation: fadeUp 0.9s 0.3s ease both;
  }
  .hero-headline {
    font-family: var(--font-display);
    font-size: clamp(3.2rem, 5vw, 5.5rem);
    font-weight: 900;
    line-height: 1.05;
    letter-spacing: -0.01em;
    color: var(--cream);
    animation: fadeUp 0.9s 0.5s ease both;
  }
  .hero-headline em {
    font-style: italic;
    color: var(--terra);
  }
  .hero-sub {
    margin-top: 1.8rem;
    font-size: 1.05rem;
    font-weight: 300;
    line-height: 1.7;
    color: rgba(245,239,227,0.7);
    max-width: 420px;
    animation: fadeUp 0.9s 0.7s ease both;
  }
  .hero-actions {
    margin-top: 3rem;
    display: flex; gap: 1.2rem; align-items: center;
    animation: fadeUp 0.9s 0.9s ease both;
  }
  .btn-primary {
    font-family: var(--font-mono);
    font-size: 0.72rem;
    letter-spacing: 0.12em;
    text-transform: uppercase;
    background: var(--terra);
    color: var(--warm-white);
    padding: 1rem 2.2rem;
    text-decoration: none;
    border: none;
    cursor: none;
    transition: background 0.25s, transform 0.2s, box-shadow 0.25s;
    box-shadow: 0 4px 20px rgba(196,113,74,0.3);
  }
  .btn-primary:hover {
    background: var(--ink);
    transform: translateY(-2px);
    box-shadow: 0 8px 30px rgba(196,113,74,0.2);
  }
  .btn-ghost {
    font-family: var(--font-mono);
    font-size: 0.72rem;
    letter-spacing: 0.12em;
    text-transform: uppercase;
    background: transparent;
    color: var(--cream);
    padding: 1rem 2.2rem;
    text-decoration: none;
    border: 1px solid rgba(245,239,227,0.3);
    cursor: none;
    transition: border-color 0.25s, color 0.25s;
  }
  .btn-ghost:hover { border-color: var(--cream); color: var(--cream); }
  .hero-right {
    background: var(--sage);
    position: relative;
    display: flex; align-items: center; justify-content: center;
    overflow: hidden;
  }
  .hero-right::before {
    content: '';
    position: absolute;
    width: 320px; height: 320px;
    border-radius: 50%;
    background: var(--terra);
    top: -80px; right: -80px;
    opacity: 0.9;
  }
  .hero-right::after {
    content: '';
    position: absolute;
    width: 200px; height: 200px;
    border-radius: 50%;
    background: var(--sage-light);
    top: -60px; right: -20px;
    opacity: 0.6;
  }
  .hero-visual {
    width: 280px;
    position: relative;
    animation: floatPen 4s ease-in-out infinite;
  }
  @keyframes floatPen {
    0%, 100% { transform: translateY(0) rotate(-15deg); }
    50% { transform: translateY(-18px) rotate(-15deg); }
  }
  .pen-svg { width: 100%; height: auto; }
  .hero-haptic-ring {
    position: absolute;
    width: 60px; height: 60px;
    border: 1px solid var(--sage-light);
    border-radius: 50%;
    top: 50%; left: 50%;
    transform: translate(-50%, -50%);
    animation: ringPulse 2.5s ease-out infinite;
    opacity: 0;
  }
  .hero-haptic-ring:nth-child(2) { animation-delay: 0.8s; }
  .hero-haptic-ring:nth-child(3) { animation-delay: 1.6s; }
  @keyframes ringPulse {
    0% { transform: translate(-50%, -50%) scale(1); opacity: 0.8; }
    100% { transform: translate(-50%, -50%) scale(5); opacity: 0; }
  }
  .hero-noise {
    position: absolute; inset: 0;
    background-image: url("data:image/svg+xml,%3Csvg viewBox='0 0 256 256' xmlns='http://www.w3.org/2000/svg'%3E%3Cfilter id='noise'%3E%3CfeTurbulence type='fractalNoise' baseFrequency='0.9' numOctaves='4' stitchTiles='stitch'/%3E%3C/filter%3E%3Crect width='100%25' height='100%25' filter='url(%23noise)' opacity='0.04'/%3E%3C/svg%3E");
    pointer-events: none;
  }
  .hero-stat-bar {
    display: flex; gap: 3rem;
    border-top: 1px solid rgba(245,239,227,0.15);
    padding-top: 2rem;
    margin-top: 3rem;
    animation: fadeUp 0.9s 1.2s ease both;
  }
  .stat-item { display: flex; flex-direction: column; gap: 0.3rem; }
  .stat-num {
    font-family: var(--font-display);
    font-size: 2.2rem;
    font-weight: 700;
    color: var(--cream);
  }
  .stat-label {
    font-family: var(--font-mono);
    font-size: 0.65rem;
    letter-spacing: 0.12em;
    text-transform: uppercase;
    color: rgba(245,239,227,0.45);
  }

  @keyframes fadeUp {
    from { opacity: 0; transform: translateY(30px); }
    to { opacity: 1; transform: translateY(0); }
  }

  /* SECTION SHARED */
  section { position: relative; }
  .section-label {
    font-family: var(--font-mono);
    font-size: 0.65rem;
    letter-spacing: 0.2em;
    text-transform: uppercase;
    color: var(--sage);
    margin-bottom: 1.2rem;
  }

  /* PROBLEM / SOLUTION */
  .problem-solution {
    display: grid;
    grid-template-columns: 1fr 1fr;
    min-height: 80vh;
  }
  .problem-col {
    background: var(--forest);
    padding: 6rem 4rem;
    display: flex; flex-direction: column; justify-content: center;
    position: relative;
    overflow: hidden;
  }
  .problem-col::before {
    content: '';
    position: absolute;
    width: 300px; height: 300px;
    background: radial-gradient(circle, rgba(196,113,74,0.15) 0%, transparent 70%);
    top: -50px; right: -50px;
    border-radius: 50%;
  }
  .problem-col .section-label { color: var(--terra-light); }
  .problem-headline {
    font-family: var(--font-display);
    font-size: clamp(2.5rem, 3.5vw, 3.8rem);
    font-weight: 700;
    line-height: 1.1;
    color: var(--cream);
    margin-bottom: 1.8rem;
  }
  .problem-headline em { font-style: italic; color: var(--terra-light); }
  .problem-body {
    font-size: 0.95rem;
    line-height: 1.8;
    color: rgba(245,240,232,0.65);
    max-width: 400px;
    margin-bottom: 2.5rem;
  }
  .distraction-list {
    list-style: none;
    display: flex; flex-direction: column; gap: 0.8rem;
  }
  .distraction-list li {
    font-family: var(--font-mono);
    font-size: 0.78rem;
    letter-spacing: 0.05em;
    color: rgba(245,240,232,0.4);
    display: flex; align-items: center; gap: 0.8rem;
  }
  .distraction-list li::before {
    content: '✗';
    color: var(--terra);
    font-size: 0.9rem;
  }
  .solution-col {
    background: var(--cream);
    padding: 6rem 4rem;
    display: flex; flex-direction: column; justify-content: center;
  }
  .solution-headline {
    font-family: var(--font-display);
    font-size: clamp(2.5rem, 3.5vw, 3.8rem);
    font-weight: 700;
    line-height: 1.1;
    color: var(--ink);
    margin-bottom: 1.8rem;
  }
  .solution-headline em { font-style: italic; color: var(--sage-light); }
  .solution-body {
    font-size: 0.95rem;
    line-height: 1.8;
    color: var(--charcoal);
    max-width: 400px;
    margin-bottom: 2.5rem;
  }
  .solution-list {
    list-style: none;
    display: flex; flex-direction: column; gap: 0.8rem;
  }
  .solution-list li {
    font-family: var(--font-mono);
    font-size: 0.78rem;
    letter-spacing: 0.05em;
    color: var(--charcoal);
    display: flex; align-items: center; gap: 0.8rem;
  }
  .solution-list li::before {
    content: '✓';
    color: var(--sage);
    font-size: 0.9rem;
  }

  /* HOW IT WORKS */
  .how-it-works {
    padding: 8rem 3rem;
    background: var(--warm-white);
    max-width: 1200px;
    margin: 0 auto;
  }
  .how-header {
    text-align: center;
    margin-bottom: 5rem;
  }
  .section-title {
    font-family: var(--font-display);
    font-size: clamp(2.5rem, 4vw, 4rem);
    font-weight: 700;
    line-height: 1.1;
    color: var(--ink);
  }
  .section-title em { font-style: italic; color: var(--terra); }
  .steps-grid {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    gap: 0;
    position: relative;
  }
  .steps-grid::before {
    content: '';
    position: absolute;
    top: 2.5rem;
    left: calc(16.66% + 1rem);
    right: calc(16.66% + 1rem);
    height: 1px;
    background: linear-gradient(90deg, var(--sand), var(--terra), var(--sand));
  }
  .step {
    padding: 0 2.5rem 2.5rem;
    display: flex; flex-direction: column; align-items: center; text-align: center;
  }
  .step-num {
    width: 5rem; height: 5rem;
    border: 1px solid var(--sand);
    border-radius: 50%;
    display: flex; align-items: center; justify-content: center;
    font-family: var(--font-display);
    font-size: 1.8rem;
    font-weight: 300;
    color: var(--terra);
    background: var(--warm-white);
    margin-bottom: 2rem;
    position: relative;
    z-index: 1;
    transition: border-color 0.3s, background 0.3s;
  }
  .step:hover .step-num { border-color: var(--terra); background: var(--mist); }
  .step-title {
    font-family: var(--font-display);
    font-size: 1.4rem;
    font-weight: 400;
    color: var(--ink);
    margin-bottom: 0.8rem;
  }
  .step-body {
    font-size: 0.9rem;
    line-height: 1.7;
    color: var(--charcoal);
  }

  /* FEATURES */
  .features {
    background: var(--ink);
    padding: 8rem 3rem;
    overflow: hidden;
  }
  .features-inner {
    max-width: 1200px;
    margin: 0 auto;
  }
  .features-header {
    margin-bottom: 5rem;
  }
  .features-header .section-label { color: var(--sage-light); }
  .features-header .section-title { color: var(--cream); }
  .features-header .section-title em { color: var(--terra-light); }
  .features-grid {
    display: grid;
    grid-template-columns: repeat(2, 1fr);
    gap: 1.5px;
    background: rgba(255,255,255,0.06);
  }
  .feature-card {
    background: var(--ink);
    padding: 3rem;
    position: relative;
    overflow: hidden;
  }
  .feature-card::after {
    content: '';
    position: absolute;
    bottom: 0; left: 3rem;
    width: 0; height: 1px;
    background: var(--terra);
    transition: width 0.4s ease;
  }
  .feature-card:hover::after { width: calc(100% - 6rem); }
  .feature-icon {
    width: 3rem; height: 3rem;
    margin-bottom: 1.5rem;
    color: var(--terra-light);
  }
  .feature-title {
    font-family: var(--font-display);
    font-size: 1.5rem;
    font-weight: 400;
    color: var(--cream);
    margin-bottom: 0.8rem;
  }
  .feature-tag {
    font-family: var(--font-mono);
    font-size: 0.6rem;
    letter-spacing: 0.15em;
    text-transform: uppercase;
    color: var(--sage-light);
    margin-bottom: 1rem;
    display: inline-block;
  }
  .feature-body {
    font-size: 0.88rem;
    line-height: 1.75;
    color: rgba(245,240,232,0.55);
  }

  /* COLORS */
  .colors-section {
    padding: 6rem 3rem;
    max-width: 1200px;
    margin: 0 auto;
    text-align: center;
  }
  .colors-section .section-title { margin-bottom: 1rem; }
  .colors-sub {
    font-size: 0.95rem;
    color: var(--charcoal);
    margin-bottom: 3.5rem;
    max-width: 500px;
    margin-left: auto; margin-right: auto;
  }
  .color-swatches {
    display: flex; gap: 1.5rem; justify-content: center; flex-wrap: wrap;
  }
  .swatch {
    display: flex; flex-direction: column; align-items: center; gap: 1rem;
    cursor: none;
    transition: transform 0.3s;
  }
  .swatch:hover { transform: translateY(-8px); }
  .swatch-circle {
    width: 80px; height: 80px;
    border-radius: 50%;
    box-shadow: 0 8px 24px rgba(0,0,0,0.12);
  }
  .swatch-name {
    font-family: var(--font-mono);
    font-size: 0.68rem;
    letter-spacing: 0.08em;
    color: var(--charcoal);
  }

  /* IMPACT */
  .impact {
    background: var(--sage);
    padding: 8rem 3rem;
    position: relative;
    overflow: hidden;
  }
  .impact::before {
    content: '';
    position: absolute;
    top: -200px; right: -200px;
    width: 500px; height: 500px;
    background: radial-gradient(circle, rgba(255,255,255,0.08) 0%, transparent 60%);
    border-radius: 50%;
  }
  .impact-inner {
    max-width: 1200px;
    margin: 0 auto;
  }
  .impact-header .section-label { color: rgba(255,255,255,0.6); }
  .impact-header .section-title {
    color: var(--warm-white);
    margin-bottom: 1.5rem;
  }
  .impact-header .section-title em { color: var(--terra-light); font-style: italic; }
  .impact-intro {
    font-size: 1rem;
    line-height: 1.8;
    color: rgba(250,248,244,0.75);
    max-width: 580px;
    margin-bottom: 4rem;
  }
  .sdg-grid {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    gap: 2rem;
  }
  .sdg-card {
    background: rgba(255,255,255,0.1);
    backdrop-filter: blur(8px);
    border: 1px solid rgba(255,255,255,0.15);
    padding: 2.5rem;
    position: relative;
    transition: background 0.3s, transform 0.3s;
  }
  .sdg-card:hover { background: rgba(255,255,255,0.16); transform: translateY(-4px); }
  .sdg-number {
    font-family: var(--font-display);
    font-size: 3.5rem;
    font-weight: 300;
    color: rgba(255,255,255,0.2);
    line-height: 1;
    margin-bottom: 0.5rem;
  }
  .sdg-title {
    font-family: var(--font-mono);
    font-size: 0.68rem;
    letter-spacing: 0.12em;
    text-transform: uppercase;
    color: var(--terra-light);
    margin-bottom: 0.8rem;
  }
  .sdg-desc {
    font-size: 0.88rem;
    line-height: 1.7;
    color: rgba(250,248,244,0.8);
  }

  /* ABOUT */
  .about {
    padding: 8rem 3rem;
    max-width: 1200px;
    margin: 0 auto;
  }
  .about-header { margin-bottom: 5rem; }
  .about-intro {
    font-size: 1rem;
    line-height: 1.8;
    color: var(--charcoal);
    max-width: 600px;
    margin-top: 1.5rem;
  }
  .founders-grid {
    display: grid;
    grid-template-columns: repeat(2, 1fr);
    gap: 1.5rem;
  }
  .founder-card {
    background: var(--warm-white);
    border: 1px solid var(--sand);
    padding: 2rem;
    display: flex;
    gap: 1.5rem;
    align-items: flex-start;
  }
  .founder-avatar {
    width: 110px;
    min-width: 110px;
    height: 130px;
    background: var(--mist);
    overflow: hidden;
    display: flex; align-items: center; justify-content: center;
    flex-shrink: 0;
  }
  .founder-initials {
    font-family: var(--font-display);
    font-size: 2.5rem;
    font-weight: 700;
    color: var(--ink);
    letter-spacing: 0.05em;
  }
  .founder-info { display: flex; flex-direction: column; }
  .founder-name {
    font-family: var(--font-display);
    font-size: 1.4rem;
    font-weight: 700;
    color: var(--ink);
    margin-bottom: 0.2rem;
  }
  .founder-role {
    font-family: var(--font-mono);
    font-size: 0.65rem;
    letter-spacing: 0.12em;
    text-transform: uppercase;
    color: var(--terra);
    margin-bottom: 0.8rem;
  }
  .founder-bio {
    font-size: 0.88rem;
    line-height: 1.65;
    color: var(--charcoal);
  }
  .founder-name {
    font-family: var(--font-display);
    font-size: 1.2rem;
    font-weight: 400;
    color: var(--ink);
    margin-bottom: 0.2rem;
  }
  .founder-role {
    font-family: var(--font-mono);
    font-size: 0.65rem;
    letter-spacing: 0.12em;
    text-transform: uppercase;
    color: var(--terra);
    margin-bottom: 0.8rem;
  }
  .founder-bio {
    font-size: 0.82rem;
    line-height: 1.65;
    color: var(--charcoal);
  }
  .story-block {
    margin-top: 6rem;
    padding: 4rem;
    background: var(--ink);
    border-left: 3px solid var(--terra);
    display: grid;
    grid-template-columns: 1fr 2fr;
    gap: 4rem;
    align-items: center;
  }
  .story-title {
    font-family: var(--font-display);
    font-size: 2.5rem;
    font-weight: 700;
    line-height: 1.15;
    color: var(--cream);
  }
  .story-title em { font-style: italic; color: var(--terra-light); }
  .story-text {
    font-size: 0.95rem;
    line-height: 1.85;
    color: rgba(245,239,227,0.7);
  }

  /* SHOP / CTA */
  .shop-cta {
    padding: 10rem 3rem;
    text-align: center;
    background: var(--ink);
    position: relative;
    overflow: hidden;
  }
  .shop-cta::before {
    content: 'PomoPen';
    position: absolute;
    font-family: var(--font-display);
    font-size: 20vw;
    font-weight: 900;
    color: rgba(255,255,255,0.04);
    top: 50%; left: 50%;
    transform: translate(-50%, -50%);
    white-space: nowrap;
    pointer-events: none;
    letter-spacing: -0.02em;
  }
  .shop-label { margin-bottom: 1.5rem; }
  .shop-headline {
    font-family: var(--font-display);
    font-size: clamp(3rem, 6vw, 6rem);
    font-weight: 900;
    line-height: 1.05;
    color: var(--cream);
    margin-bottom: 1.5rem;
    position: relative;
    z-index: 1;
  }
  .shop-headline em { font-style: italic; color: var(--terra); }
  .shop-sub {
    font-size: 1rem;
    line-height: 1.7;
    color: rgba(245,239,227,0.65);
    max-width: 480px;
    margin: 0 auto 3rem;
    position: relative;
    z-index: 1;
  }
  .shop-actions {
    display: flex; gap: 1.2rem; justify-content: center;
    position: relative; z-index: 1;
  }
  .price-tag {
    display: inline-flex; flex-direction: column; align-items: flex-start;
    margin-top: 2rem;
    position: relative; z-index: 1;
  }
  .price-note {
    font-family: var(--font-mono);
    font-size: 0.65rem;
    letter-spacing: 0.12em;
    text-transform: uppercase;
    color: rgba(245,239,227,0.5);
    margin-bottom: 0.3rem;
  }
  .price-amount {
    font-family: var(--font-display);
    font-size: 2.8rem;
    font-weight: 700;
    color: var(--cream);
  }
  .price-amount sup { font-size: 1.2rem; vertical-align: super; }

  /* FOOTER */
  footer {
    background: var(--forest);
    padding: 5rem 3rem 3rem;
    color: rgba(245,239,227,0.5);
  }
  .footer-inner {
    max-width: 1200px;
    margin: 0 auto;
    display: grid;
    grid-template-columns: 2fr 1fr 1fr 1fr;
    gap: 4rem;
    margin-bottom: 4rem;
  }
  .footer-brand { display: flex; flex-direction: column; gap: 1rem; }
  .footer-logo {
    font-family: var(--font-display);
    font-size: 1.8rem;
    font-weight: 300;
    color: var(--cream);
    letter-spacing: 0.02em;
  }
  .footer-logo span { color: var(--terra); }
  .footer-tagline {
    font-size: 0.85rem;
    line-height: 1.6;
    max-width: 260px;
  }
  .footer-col h4 {
    font-family: var(--font-mono);
    font-size: 0.65rem;
    letter-spacing: 0.15em;
    text-transform: uppercase;
    color: var(--cream);
    margin-bottom: 1.5rem;
  }
  .footer-col ul { list-style: none; display: flex; flex-direction: column; gap: 0.6rem; }
  .footer-col ul a {
    font-size: 0.85rem;
    color: rgba(245,240,232,0.45);
    text-decoration: none;
    transition: color 0.2s;
  }
  .footer-col ul a:hover { color: var(--terra-light); }
  .footer-bottom {
    max-width: 1200px;
    margin: 0 auto;
    padding-top: 2rem;
    border-top: 1px solid rgba(255,255,255,0.08);
    display: flex; justify-content: space-between; align-items: center;
    font-family: var(--font-mono);
    font-size: 0.65rem;
    letter-spacing: 0.08em;
  }
  .footer-sdgs { display: flex; gap: 0.8rem; }
  .sdg-badge {
    background: rgba(255,255,255,0.08);
    border: 1px solid rgba(255,255,255,0.12);
    padding: 0.3rem 0.6rem;
    font-family: var(--font-mono);
    font-size: 0.6rem;
    letter-spacing: 0.1em;
    color: var(--sage-light);
  }

  /* Reveal animations */
  .reveal {
    opacity: 0;
    transform: translateY(30px);
    transition: opacity 0.7s ease, transform 0.7s ease;
  }
  .reveal.visible {
    opacity: 1;
    transform: translateY(0);
  }
  .reveal-delay-1 { transition-delay: 0.15s; }
  .reveal-delay-2 { transition-delay: 0.3s; }
  .reveal-delay-3 { transition-delay: 0.45s; }
  .reveal-delay-4 { transition-delay: 0.6s; }

  /* Responsive */
  @media (max-width: 900px) {
    body { cursor: auto; }
    .cursor, .cursor-ring { display: none; }
    nav { padding: 1.2rem 1.5rem; }
    .nav-links { display: none; }
    .hero { grid-template-columns: 1fr; }
    .hero-right { height: 50vh; }
    .hero-left { padding: 8rem 1.5rem 3rem; }
    .hero-stat-bar { left: 1.5rem; right: 1.5rem; gap: 1.5rem; }
    .problem-solution { grid-template-columns: 1fr; }
    .problem-col, .solution-col { padding: 4rem 1.5rem; }
    .steps-grid { grid-template-columns: 1fr; }
    .steps-grid::before { display: none; }
    .features-grid { grid-template-columns: 1fr; }
    .sdg-grid { grid-template-columns: 1fr; }
    .founders-grid { grid-template-columns: 1fr; }
    .story-block { grid-template-columns: 1fr; gap: 2rem; }
    .footer-inner { grid-template-columns: 1fr 1fr; gap: 2rem; }
    .how-it-works, .colors-section, .about { padding: 5rem 1.5rem; }
    .features, .impact, .shop-cta { padding: 5rem 1.5rem; }
  }
</style>
</head>
<body>

<!-- Custom cursor -->
<div class="cursor" id="cursor"></div>
<div class="cursor-ring" id="cursorRing"></div>

<!-- NAVIGATION -->
<nav>
  <a href="#" class="nav-logo">Pomo<span>Pen</span></a>
  <ul class="nav-links">
    <li><a href="#how">How It Works</a></li>
    <li><a href="#features">Features</a></li>
    <li><a href="#impact">Impact</a></li>
    <li><a href="#about">Our Story</a></li>
  </ul>
  <a href="#shop" class="nav-cta">Reserve Yours</a>
</nav>

<!-- HERO -->
<section class="hero">
  <div class="hero-left">
    <p class="hero-eyebrow">Introducing PomoPen — The Focus Instrument</p>
    <h1 class="hero-headline">
      Reclaim<br>
      <em>Productivity.</em><br>
      Restore Focus.
    </h1>
    <p class="hero-sub">A haptic-powered writing pen that silently structures your work sessions — no screen required. Designed for students and professionals who refuse to let distraction win.</p>
    <div class="hero-actions">
      <a href="#shop" class="btn-primary">Reserve Your Pen</a>
      <a href="#how" class="btn-ghost">See How It Works</a>
    </div>
    <div class="hero-stat-bar">
      <div class="stat-item">
        <span class="stat-num">25<em style="font-size:1.2rem;color:var(--terra)">min</em></span>
        <span class="stat-label">Pomodoro intervals</span>
      </div>
      <div class="stat-item">
        <span class="stat-num">0</span>
        <span class="stat-label">Screens needed</span>
      </div>
      <div class="stat-item">
        <span class="stat-num">3</span>
        <span class="stat-label">SDG goals aligned</span>
      </div>
    </div>
  </div>
  <div class="hero-right">
    <div class="hero-noise"></div>
    <div class="hero-haptic-ring"></div>
    <div class="hero-haptic-ring"></div>
    <div class="hero-haptic-ring"></div>
    <div class="hero-visual">
      <!-- Stylized pen SVG -->
      <svg class="pen-svg" viewBox="0 0 120 520" fill="none" xmlns="http://www.w3.org/2000/svg">
        <!-- Pen clip -->
        <rect x="76" y="60" width="8" height="220" rx="4" fill="#6b7f6e" opacity="0.7"/>
        <!-- Pen body -->
        <rect x="38" y="20" width="44" height="360" rx="22" fill="#1e3a2f"/>
        <!-- Pen grip section -->
        <rect x="38" y="280" width="44" height="80" rx="10" fill="#152b22"/>
        <!-- Grip lines -->
        <line x1="38" y1="295" x2="82" y2="295" stroke="#4a7c5f" stroke-width="1" opacity="0.4"/>
        <line x1="38" y1="308" x2="82" y2="308" stroke="#4a7c5f" stroke-width="1" opacity="0.4"/>
        <line x1="38" y1="321" x2="82" y2="321" stroke="#4a7c5f" stroke-width="1" opacity="0.4"/>
        <line x1="38" y1="334" x2="82" y2="334" stroke="#4a7c5f" stroke-width="1" opacity="0.4"/>
        <line x1="38" y1="347" x2="82" y2="347" stroke="#4a7c5f" stroke-width="1" opacity="0.4"/>
        <!-- Haptic indicator light -->
        <circle cx="60" cy="150" r="5" fill="#c4714a" opacity="0.9">
          <animate attributeName="opacity" values="0.9;0.2;0.9" dur="2s" repeatCount="indefinite"/>
        </circle>
        <!-- USB-C port -->
        <rect x="48" y="370" width="24" height="8" rx="4" fill="#1a1814"/>
        <rect x="52" y="372" width="16" height="4" rx="2" fill="#6b7f6e" opacity="0.5"/>
        <!-- Pen tip taper -->
        <path d="M38 358 L60 430 L82 358 Z" fill="#152b22"/>
        <!-- Pen tip -->
        <path d="M55 428 L60 450 L65 428 Z" fill="#c8452a"/>
        <!-- Top cap -->
        <rect x="42" y="10" width="36" height="20" rx="10" fill="#2d5443"/>
        <!-- Brand text area -->
        <rect x="44" y="200" width="32" height="60" rx="4" fill="#152b22" opacity="0.3"/>
        <!-- Pen sheen/highlight -->
        <rect x="44" y="30" width="6" height="300" rx="3" fill="white" opacity="0.06"/>
      </svg>
    </div>
  </div>
</section>

<!-- PROBLEM / SOLUTION -->
<section class="problem-solution" id="problem">
  <div class="problem-col">
    <p class="section-label">The Problem</p>
    <h2 class="problem-headline">Your phone was<br><em>never your ally</em><br>in deep work.</h2>
    <p class="problem-body">Every timer app, productivity tool, and notification system lives inside the same device that fragments your attention. You reach for focus — and get a feed instead.</p>
    <ul class="distraction-list">
      <li>Notification overload mid-session</li>
      <li>App-switching kills flow states instantly</li>
      <li>Screen time compounds cognitive fatigue</li>
      <li>Constant connectivity erodes deep work</li>
      <li>Digital tools designed to keep you engaged — not productive</li>
    </ul>
  </div>
  <div class="solution-col">
    <p class="section-label">The Solution</p>
    <h2 class="solution-headline">A physical tool<br><em>built for silence</em><br>and structure.</h2>
    <p class="solution-body">PomoPen removes focus from the digital arena entirely. A silent haptic vibration — felt only by you — signals work intervals and breaks, keeping you in the zone without ever touching a screen.</p>
    <ul class="solution-list">
      <li>Silent haptic pulse — zero visual interruption</li>
      <li>No app, no WiFi, no distraction vector</li>
      <li>Pomodoro timing embedded in the pen itself</li>
      <li>Physical writing deepens cognitive retention</li>
      <li>Companion app for optional analytics — on your terms</li>
    </ul>
  </div>
</section>

<!-- HOW IT WORKS -->
<div style="background: var(--warm-white); padding: 1px 0;" id="how">
<section class="how-it-works">
  <div class="how-header reveal">
    <p class="section-label">How It Works</p>
    <h2 class="section-title">Three steps to<br><em>uninterrupted flow</em></h2>
  </div>
  <div class="steps-grid">
    <div class="step reveal reveal-delay-1">
      <div class="step-num">I</div>
      <h3 class="step-title">Press & Begin</h3>
      <p class="step-body">Press the single side button to start your session. PomoPen activates a 25-minute Pomodoro interval — no setup, no screen, no fuss. Just click and write.</p>
    </div>
    <div class="step reveal reveal-delay-2">
      <div class="step-num">II</div>
      <h3 class="step-title">Feel the Signal</h3>
      <p class="step-body">When your interval ends, a gentle haptic pulse travels through the pen barrel — perceptible only to you. A brief pause vibration signals your 5-minute break. No sound, no screen.</p>
    </div>
    <div class="step reveal reveal-delay-3">
      <div class="step-num">III</div>
      <h3 class="step-title">Track & Improve</h3>
      <p class="step-body">Sync with our optional companion app at the end of your day to review completed sessions, streak data, and long-term focus trends. Analytics on your schedule, not your distraction's.</p>
    </div>
  </div>
</section>
</div>

<!-- FEATURES -->
<section class="features" id="features">
  <div class="features-inner">
    <div class="features-header reveal">
      <p class="section-label">Product Features</p>
      <h2 class="section-title">Precision <em>hardware.</em><br>Purposeful design.</h2>
    </div>
    <div class="features-grid">
      <div class="feature-card reveal">
        <svg class="feature-icon" viewBox="0 0 48 48" fill="none" stroke="currentColor" stroke-width="1.5">
          <path d="M24 4 L44 24 L24 44 L4 24 Z"/>
          <circle cx="24" cy="24" r="6"/>
          <path d="M24 12 L24 18 M24 30 L24 36 M12 24 L18 24 M30 24 L36 24"/>
        </svg>
        <span class="feature-tag">Hardware</span>
        <h3 class="feature-title">Precision Haptic Engine</h3>
        <p class="feature-body">Our miniaturized linear resonant actuator delivers crisp, distinct vibration patterns that signal interval changes — distinguishable even during deep writing without breaking your hand's rhythm.</p>
      </div>
      <div class="feature-card reveal reveal-delay-1">
        <svg class="feature-icon" viewBox="0 0 48 48" fill="none" stroke="currentColor" stroke-width="1.5">
          <rect x="8" y="8" width="32" height="32" rx="4"/>
          <path d="M16 24 L21 29 L32 18"/>
        </svg>
        <span class="feature-tag">Design</span>
        <h3 class="feature-title">Ergonomic Barrel</h3>
        <p class="feature-body">Sculpted for extended writing sessions, the PomoPen's weighted grip distributes pressure evenly across the fingers. Offered in five matte finishes: Obsidian, Sage, Dune, Terra, and Ash.</p>
      </div>
      <div class="feature-card reveal reveal-delay-2">
        <svg class="feature-icon" viewBox="0 0 48 48" fill="none" stroke="currentColor" stroke-width="1.5">
          <path d="M24 40 C14 36 8 28 8 20 A16 16 0 0 1 40 20 C40 28 34 36 24 40Z"/>
          <path d="M24 20 L24 12 M20 24 L28 24"/>
        </svg>
        <span class="feature-tag">Power</span>
        <h3 class="feature-title">USB-C Rechargeable</h3>
        <p class="feature-body">A single 45-minute charge via USB-C delivers up to 30 full Pomodoro sessions — approximately 15 hours of structured work. The charging port is flush-set into the barrel, preserving the clean silhouette.</p>
      </div>
      <div class="feature-card reveal reveal-delay-3">
        <svg class="feature-icon" viewBox="0 0 48 48" fill="none" stroke="currentColor" stroke-width="1.5">
          <rect x="8" y="16" width="32" height="24" rx="3"/>
          <path d="M16 16 L16 12 A8 8 0 0 1 32 12 L32 16"/>
          <circle cx="24" cy="28" r="4"/>
        </svg>
        <span class="feature-tag">Software</span>
        <h3 class="feature-title">Companion Analytics App</h3>
        <p class="feature-body">Optional — never intrusive. Sync at session's end to visualize your focus streaks, identify your peak productivity windows, and build weekly habit data. Available on iOS and Android, with no ads or tracking.</p>
      </div>
    </div>
  </div>
</section>

<!-- COLOR FINISHES -->
<section class="colors-section">
  <div class="reveal">
    <p class="section-label" style="text-align:center">Available Finishes</p>
    <h2 class="section-title">A pen <em>worth keeping</em><br>on your desk.</h2>
    <p class="colors-sub">PomoPen is a tool you'll want to reach for. Five matte-finish colorways — each one a considered choice, not an afterthought.</p>
    <div class="color-swatches">
      <div class="swatch">
        <div class="swatch-circle" style="background:#1a1814"></div>
        <span class="swatch-name">Obsidian</span>
      </div>
      <div class="swatch">
        <div class="swatch-circle" style="background:#6b7f6e"></div>
        <span class="swatch-name">Sage</span>
      </div>
      <div class="swatch">
        <div class="swatch-circle" style="background:#c4a882"></div>
        <span class="swatch-name">Dune</span>
      </div>
      <div class="swatch">
        <div class="swatch-circle" style="background:#c4714a"></div>
        <span class="swatch-name">Terra</span>
      </div>
      <div class="swatch">
        <div class="swatch-circle" style="background:#8f8c87"></div>
        <span class="swatch-name">Ash</span>
      </div>
    </div>
  </div>
</section>

<!-- IMPACT -->
<section class="impact" id="impact">
  <div class="impact-inner">
    <div class="impact-header reveal">
      <p class="section-label">Social Impact</p>
      <h2 class="section-title">Focus is a <em>right,</em><br>not a privilege.</h2>
      <p class="impact-intro">PomoPen was built with a conscience. We believe every student — regardless of background, neurotype, or resources — deserves access to tools that help them think clearly and work deeply. Our venture is aligned with three United Nations Sustainable Development Goals.</p>
    </div>
    <div class="sdg-grid">
      <div class="sdg-card reveal">
        <div class="sdg-number">03</div>
        <div class="sdg-title">SDG 3 · Good Health & Well-Being</div>
        <p class="sdg-desc">By reducing screen dependency during study and work, PomoPen helps lower cognitive overload, digital anxiety, and the chronic stress associated with always-on connectivity. We're building a calmer way to work.</p>
      </div>
      <div class="sdg-card reveal reveal-delay-1">
        <div class="sdg-number">04</div>
        <div class="sdg-title">SDG 4 · Quality Education</div>
        <p class="sdg-desc">Structured focus intervals have a proven impact on learning retention and academic performance. PomoPen gives students — from top universities to community colleges — a tangible edge in their academic journeys.</p>
      </div>
      <div class="sdg-card reveal reveal-delay-2">
        <div class="sdg-number">10</div>
        <div class="sdg-title">SDG 10 · Reduced Inequalities</div>
        <p class="sdg-desc">We are committed to campus access programs and neurodivergent-inclusive design. Haptic feedback provides a non-visual, non-auditory focus signal that works for ADHD, autism spectrum, and sensory processing differences.</p>
      </div>
    </div>
  </div>
</section>

<!-- ABOUT / FOUNDERS -->
<section class="about" id="about">
  <div class="about-header reveal">
    <p class="section-label">Our Story</p>
    <h2 class="section-title">Built by students<br>who <em>felt the problem.</em></h2>
    <p class="about-intro">PomoPen began in a university library at 11pm, with four co-founders staring at their phones instead of their notes. We didn't need another app. We needed something physical — something that worked with us, not against us. So we built it.</p>
  </div>
  <div class="founders-grid">
    <div class="founder-card reveal">
      <div class="founder-avatar"><span class="founder-initials">JP</span></div>
      <div class="founder-info">
        <h3 class="founder-name">Jay Patel</h3>
        <p class="founder-role">Co-Founder</p>
        <p class="founder-bio">I am here to turn my experiences into action — helping others overcome barriers, access essential resources, and find a stronger sense of stability and belonging.</p>
      </div>
    </div>
    <div class="founder-card reveal reveal-delay-1">
      <div class="founder-avatar"><span class="founder-initials">SC</span></div>
      <div class="founder-info">
        <h3 class="founder-name">Samir Chowdhury</h3>
        <p class="founder-role">Co-Founder</p>
        <p class="founder-bio">I am here to leverage my academic background and ambition to develop innovative solutions that expand equal opportunity and support marginalized communities in achieving personal success.</p>
      </div>
    </div>
    <div class="founder-card reveal reveal-delay-2">
      <div class="founder-avatar"><span class="founder-initials">RK</span></div>
      <div class="founder-info">
        <h3 class="founder-name">Ria Kakar</h3>
        <p class="founder-role">Co-Founder</p>
        <p class="founder-bio">I am here because I have personally struggled with focus and productivity, and I know this is a challenge many others face. My mission is to use my lived experience to build solutions that help individuals overcome these barriers and thrive together.</p>
      </div>
    </div>
    <div class="founder-card reveal reveal-delay-3">
      <div class="founder-avatar"><span class="founder-initials">ZZ</span></div>
      <div class="founder-info">
        <h3 class="founder-name">Zehan Zhao</h3>
        <p class="founder-role">Co-Founder</p>
        <p class="founder-bio">I am here because I'm interested in how social entrepreneurship can translate complex social challenges into sustainable, scalable solutions. I want to better understand how to balance mission with execution in building ventures that create real impact.</p>
      </div>
    </div>
  </div>
  <div class="story-block reveal">
    <h3 class="story-title">From a <em>library desk</em> to your hands.</h3>
    <p class="story-text">We're four university students who lived through digital burnout — the kind where you spend three hours "studying" and absorb nothing, because your focus was hijacked by the very tools meant to help you. We tried every app, every extension, every subscription service. None of them solved the root problem: the phone itself is the distraction. PomoPen is our answer to that problem. A physical instrument that structures your time, respects your attention, and gets out of your way. We are not building another productivity app. We are building a new relationship between people and their focus.</p>
  </div>
</section>

<!-- SHOP / CTA -->
<section class="shop-cta" id="shop">
  <p class="section-label shop-label" style="color:var(--terra-light)">Reserve Your PomoPen</p>
  <h2 class="shop-headline">Your focus<br><em>starts here.</em></h2>
  <p class="shop-sub">Join the early access waitlist and be among the first to hold a PomoPen. Founding members receive a 20% launch discount and early access to the companion app.</p>
  <div class="shop-actions">
    <a href="#" class="btn-primary">Join the Waitlist</a>
    <a href="#" class="btn-ghost">Campus Partnership Inquiry</a>
  </div>
  <div style="display:flex;justify-content:center;margin-top:3rem;">
    <div class="price-tag">
      <span class="price-note">Founding Member Price</span>
      <span class="price-amount"><sup>$</sup>79</span>
    </div>
  </div>
</section>

<!-- FOOTER -->
<footer>
  <div class="footer-inner">
    <div class="footer-brand">
      <div class="footer-logo">Pomo<span>Pen</span></div>
      <p class="footer-tagline">A haptic focus instrument for students and professionals who refuse to let distraction win. Built with purpose. Backed by science.</p>
      <div class="footer-sdgs">
        <span class="sdg-badge">SDG 3</span>
        <span class="sdg-badge">SDG 4</span>
        <span class="sdg-badge">SDG 10</span>
      </div>
    </div>
    <div class="footer-col">
      <h4>Product</h4>
      <ul>
        <li><a href="#how">How It Works</a></li>
        <li><a href="#features">Features</a></li>
        <li><a href="#shop">Reserve</a></li>
        <li><a href="#">Campus Program</a></li>
      </ul>
    </div>
    <div class="footer-col">
      <h4>Company</h4>
      <ul>
        <li><a href="#about">Our Story</a></li>
        <li><a href="#impact">Impact</a></li>
        <li><a href="#">Press Kit</a></li>
        <li><a href="#">Contact</a></li>
      </ul>
    </div>
    <div class="footer-col">
      <h4>Connect</h4>
      <ul>
        <li><a href="#">Instagram</a></li>
        <li><a href="#">LinkedIn</a></li>
        <li><a href="#">Newsletter</a></li>
        <li><a href="#">hello@pomopen.co</a></li>
      </ul>
    </div>
  </div>
  <div class="footer-bottom">
    <span>© 2025 PomoPen. All rights reserved. Made with intention.</span>
    <span>Privacy · Terms · Accessibility</span>
  </div>
</footer>

<script>
  // Custom cursor
  const cursor = document.getElementById('cursor');
  const cursorRing = document.getElementById('cursorRing');
  let mx = 0, my = 0, rx = 0, ry = 0;

  document.addEventListener('mousemove', e => {
    mx = e.clientX; my = e.clientY;
    cursor.style.left = mx + 'px';
    cursor.style.top = my + 'px';
  });

  function animateRing() {
    rx += (mx - rx) * 0.12;
    ry += (my - ry) * 0.12;
    cursorRing.style.left = rx + 'px';
    cursorRing.style.top = ry + 'px';
    requestAnimationFrame(animateRing);
  }
  animateRing();

  document.querySelectorAll('a, button').forEach(el => {
    el.addEventListener('mouseenter', () => {
      cursor.style.transform = 'translate(-50%, -50%) scale(2)';
      cursorRing.style.transform = 'translate(-50%, -50%) scale(1.5)';
      cursorRing.style.opacity = '0.8';
    });
    el.addEventListener('mouseleave', () => {
      cursor.style.transform = 'translate(-50%, -50%) scale(1)';
      cursorRing.style.transform = 'translate(-50%, -50%) scale(1)';
      cursorRing.style.opacity = '0.5';
    });
  });

  // Scroll reveal
  const reveals = document.querySelectorAll('.reveal');
  const observer = new IntersectionObserver((entries) => {
    entries.forEach(entry => {
      if (entry.isIntersecting) {
        entry.target.classList.add('visible');
      }
    });
  }, { threshold: 0.1 });
  reveals.forEach(el => observer.observe(el));

  // Smooth nav highlight
  const sections = document.querySelectorAll('section[id]');
  const navLinks = document.querySelectorAll('.nav-links a');

  window.addEventListener('scroll', () => {
    let current = '';
    sections.forEach(s => {
      if (window.scrollY >= s.offsetTop - 200) current = s.id;
    });
    navLinks.forEach(a => {
      a.style.color = a.getAttribute('href') === '#' + current ? 'var(--terra)' : '';
    });
  });
</script>
</body>
</html>
