<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1.0" />
<title>Learn With Yoni | Jewish Education & Tutoring in Denver, CO</title>
<meta name="description" content="Expert Jewish tutoring in Denver, CO and online. B'nai Mitzvah prep, Hebrew, Torah, Jewish identity education for youth and adults. Offered by Senior Educator Yoni, nationally recognized with OpenDor Media/Unpacked." />
<meta name="keywords" content="Jewish tutor Denver, bar mitzvah tutor Denver, bat mitzvah tutor Denver, Hebrew tutor Denver, Jewish education Denver, adult Jewish learning Denver, Torah study Denver, B'nai mitzvah prep Colorado, Jewish enrichment Denver, virtual Jewish tutor" />

<link rel="preconnect" href="https://fonts.googleapis.com" />
<link href="https://fonts.googleapis.com/css2?family=EB+Garamond:ital,wght@0,400;0,500;0,600;0,700;1,400;1,500&family=DM+Sans:wght@300;400;500;600&display=swap" rel="stylesheet" />

<style>
  /* ─── Design Tokens ──────────────────────────────── */
  :root {
    --ink:       #1c1714;
    --deep:      #1e2d40;
    --midnight:  #0f1c2e;
    --gold:      #c9963e;
    --gold-lt:   #e8c577;
    --cream:     #f7f3ec;
    --warm-white:#fdfbf7;
    --parchment: #efe8d8;
    --rust:      #8c3a2b;
    --sage:      #4a6741;
    --text-muted:#5c5347;

    --serif: 'EB Garamond', Georgia, serif;
    --sans:  'DM Sans', system-ui, sans-serif;

    --max: 1120px;
    --r: 4px;
  }

  *, *::before, *::after { box-sizing: border-box; margin: 0; padding: 0; }

  html { scroll-behavior: smooth; }

  body {
    font-family: var(--sans);
    background: var(--warm-white);
    color: var(--ink);
    line-height: 1.7;
    font-size: 17px;
  }

  /* ─── Utilities ──────────────────────────────────── */
  .container { max-width: var(--max); margin: 0 auto; padding: 0 2rem; }

  .serif { font-family: var(--serif); }

  .gold { color: var(--gold); }

  section { padding: 5rem 0; }

  h1, h2, h3, h4 { font-family: var(--serif); line-height: 1.2; }

  /* ─── Nav ────────────────────────────────────────── */
  nav {
    position: sticky; top: 0; z-index: 100;
    background: var(--midnight);
    border-bottom: 1px solid rgba(201,150,62,.25);
    padding: .9rem 0;
  }
  .nav-inner {
    display: flex; align-items: center; justify-content: space-between;
    max-width: var(--max); margin: 0 auto; padding: 0 2rem;
  }
  .nav-logo {
    font-family: var(--serif);
    font-size: 1.35rem;
    color: var(--cream);
    letter-spacing: .01em;
    text-decoration: none;
  }
  .nav-logo span { color: var(--gold); }
  .nav-links { display: flex; gap: 1.8rem; align-items: center; list-style: none; }
  .nav-links a { color: rgba(247,243,236,.75); text-decoration: none; font-size: .9rem; font-weight: 500; letter-spacing: .03em; transition: color .2s; }
  .nav-links a:hover { color: var(--gold-lt); }
  .nav-cta {
    background: var(--gold);
    color: var(--midnight) !important;
    padding: .45rem 1.1rem;
    border-radius: 2px;
    font-weight: 600 !important;
    letter-spacing: .04em;
    font-size: .85rem !important;
    transition: background .2s !important;
  }
  .nav-cta:hover { background: var(--gold-lt) !important; }

  /* ─── Hero ───────────────────────────────────────── */
  .hero {
    background: var(--midnight);
    position: relative;
    overflow: hidden;
    padding: 6.5rem 0 5rem;
    min-height: 88vh;
    display: flex; align-items: center;
  }
  .hero::before {
    content: '';
    position: absolute; inset: 0;
    background:
      radial-gradient(ellipse 70% 60% at 65% 45%, rgba(201,150,62,.09) 0%, transparent 70%),
      radial-gradient(ellipse 50% 40% at 20% 70%, rgba(30,45,64,.9) 0%, transparent 80%);
  }
  .hero-grid {
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 4rem;
    align-items: center;
    position: relative; z-index: 2;
  }
  .hero-eyebrow {
    display: inline-block;
    font-size: .8rem;
    font-weight: 600;
    letter-spacing: .15em;
    text-transform: uppercase;
    color: var(--gold);
    border-bottom: 1px solid rgba(201,150,62,.4);
    padding-bottom: .35rem;
    margin-bottom: 1.4rem;
  }
  .hero h1 {
    font-size: clamp(2.4rem, 4.5vw, 3.6rem);
    color: var(--cream);
    font-weight: 500;
    line-height: 1.15;
    margin-bottom: 1.5rem;
  }
  .hero h1 em {
    font-style: italic;
    color: var(--gold-lt);
  }
  .hero-sub {
    color: rgba(247,243,236,.72);
    font-size: 1.1rem;
    margin-bottom: 2.2rem;
    line-height: 1.7;
    max-width: 44ch;
  }
  .hero-btns { display: flex; gap: 1rem; flex-wrap: wrap; }
  .btn-primary {
    display: inline-block;
    background: var(--gold);
    color: var(--midnight);
    padding: .85rem 2rem;
    border-radius: 2px;
    font-weight: 700;
    font-size: 1rem;
    text-decoration: none;
    letter-spacing: .03em;
    transition: background .2s, transform .15s;
  }
  .btn-primary:hover { background: var(--gold-lt); transform: translateY(-1px); }
  .btn-ghost {
    display: inline-block;
    border: 1px solid rgba(247,243,236,.35);
    color: var(--cream);
    padding: .85rem 1.8rem;
    border-radius: 2px;
    font-weight: 500;
    font-size: 1rem;
    text-decoration: none;
    transition: border-color .2s, color .2s;
  }
  .btn-ghost:hover { border-color: var(--gold); color: var(--gold-lt); }

  /* Decorative Hebrew letter */
  .hero-visual {
    display: flex; align-items: center; justify-content: center;
    position: relative;
  }
  .hebrew-deco {
    font-family: var(--serif);
    font-size: clamp(14rem, 22vw, 22rem);
    color: rgba(201,150,62,.07);
    line-height: 1;
    user-select: none;
    letter-spacing: -.05em;
    position: absolute;
    right: -2rem;
  }
  .hero-card {
    position: relative; z-index: 1;
    background: rgba(247,243,236,.05);
    border: 1px solid rgba(201,150,62,.2);
    border-radius: 3px;
    padding: 2.2rem 2rem;
    backdrop-filter: blur(4px);
  }
  .hero-stat {
    display: flex; flex-direction: column;
    margin-bottom: 1.4rem;
    padding-bottom: 1.4rem;
    border-bottom: 1px solid rgba(201,150,62,.15);
  }
  .hero-stat:last-child { margin-bottom: 0; padding-bottom: 0; border-bottom: none; }
  .stat-num {
    font-family: var(--serif);
    font-size: 2.8rem;
    color: var(--gold-lt);
    line-height: 1;
  }
  .stat-label {
    font-size: .88rem;
    color: rgba(247,243,236,.6);
    letter-spacing: .04em;
    margin-top: .3rem;
  }

  /* ─── Trust Bar ──────────────────────────────────── */
  .trust-bar {
    background: var(--parchment);
    padding: 1.4rem 0;
    border-bottom: 1px solid rgba(28,23,20,.1);
  }
  .trust-items {
    display: flex; align-items: center; justify-content: center;
    gap: 3rem; flex-wrap: wrap;
    font-size: .88rem;
    color: var(--text-muted);
    font-weight: 500;
    letter-spacing: .03em;
  }
  .trust-items span { display: flex; align-items: center; gap: .5rem; }
  .trust-icon { font-size: 1.1rem; }

  /* ─── Problem / Hero's Journey ───────────────────── */
  .section-problem { background: var(--warm-white); }
  .problem-intro {
    text-align: center;
    max-width: 660px;
    margin: 0 auto 3.5rem;
  }
  .section-eyebrow {
    display: inline-block;
    font-size: .78rem;
    font-weight: 600;
    letter-spacing: .16em;
    text-transform: uppercase;
    color: var(--gold);
    margin-bottom: 1rem;
  }
  .problem-intro h2 {
    font-size: clamp(2rem, 3.5vw, 2.8rem);
    color: var(--deep);
    margin-bottom: 1.2rem;
  }
  .problem-intro p { color: var(--text-muted); font-size: 1.05rem; }

  .problem-cards {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    gap: 1.5rem;
    margin-top: 2rem;
  }
  .prob-card {
    background: var(--cream);
    border: 1px solid rgba(28,23,20,.08);
    border-top: 3px solid var(--rust);
    padding: 1.8rem 1.6rem;
    border-radius: 3px;
  }
  .prob-card h3 { font-size: 1.15rem; color: var(--deep); margin-bottom: .7rem; }
  .prob-card p { font-size: .93rem; color: var(--text-muted); }

  /* ─── Guide / About ──────────────────────────────── */
  .section-guide { background: var(--midnight); }
  .guide-grid {
    display: grid; grid-template-columns: 1fr 1.4fr;
    gap: 5rem; align-items: center;
  }
  .guide-avatar {
    width: 100%;
    aspect-ratio: 3/4;
    background: linear-gradient(135deg, rgba(201,150,62,.15), rgba(30,45,64,.8));
    border-radius: 3px;
    border: 1px solid rgba(201,150,62,.2);
    display: flex; align-items: center; justify-content: center;
    font-family: var(--serif);
    font-size: 6rem;
    color: rgba(201,150,62,.3);
    position: relative;
    overflow: hidden;
  }
  .guide-avatar::after {
    content: 'י';
    position: absolute;
    bottom: -1rem; right: -.5rem;
    font-size: 18rem;
    color: rgba(201,150,62,.05);
    line-height: 1;
  }
  .guide-eyebrow { color: var(--gold); }
  .guide-content h2 {
    font-size: clamp(1.9rem, 3vw, 2.7rem);
    color: var(--cream);
    margin-bottom: 1.3rem;
  }
  .guide-content h2 em { font-style: italic; color: var(--gold-lt); }
  .guide-content p { color: rgba(247,243,236,.75); margin-bottom: 1.1rem; font-size: 1.03rem; }
  .creds {
    display: grid; grid-template-columns: 1fr 1fr;
    gap: .7rem; margin-top: 2rem;
  }
  .cred-item {
    display: flex; align-items: flex-start; gap: .7rem;
    padding: .9rem; background: rgba(247,243,236,.04);
    border: 1px solid rgba(201,150,62,.12);
    border-radius: 2px;
  }
  .cred-icon { font-size: 1.2rem; flex-shrink: 0; margin-top: .1rem; }
  .cred-text { font-size: .87rem; color: rgba(247,243,236,.65); line-height: 1.5; }
  .cred-text strong { color: var(--gold-lt); display: block; font-size: .9rem; margin-bottom: .15rem; }

  /* ─── Plan / How It Works ────────────────────────── */
  .section-plan { background: var(--cream); }
  .plan-intro { text-align: center; max-width: 580px; margin: 0 auto 3.5rem; }
  .plan-intro h2 { font-size: clamp(1.9rem, 3vw, 2.6rem); color: var(--deep); margin-bottom: 1rem; }
  .plan-intro p { color: var(--text-muted); }

  .steps {
    display: grid; grid-template-columns: repeat(3, 1fr);
    gap: 0;
    position: relative;
  }
  .steps::before {
    content: '';
    position: absolute;
    top: 2.3rem; left: calc(16.66% + 1rem); right: calc(16.66% + 1rem);
    height: 1px;
    background: linear-gradient(90deg, var(--gold) 0%, rgba(201,150,62,.2) 50%, var(--gold) 100%);
  }
  .step {
    text-align: center;
    padding: 2rem 1.5rem;
    position: relative;
  }
  .step-num {
    width: 4rem; height: 4rem;
    border-radius: 50%;
    background: var(--deep);
    border: 2px solid var(--gold);
    display: flex; align-items: center; justify-content: center;
    font-family: var(--serif);
    font-size: 1.6rem;
    color: var(--gold);
    margin: 0 auto 1.2rem;
    position: relative; z-index: 1;
  }
  .step h3 { font-size: 1.1rem; color: var(--deep); margin-bottom: .6rem; }
  .step p { font-size: .92rem; color: var(--text-muted); }

  /* ─── Services ───────────────────────────────────── */
  .section-services { background: var(--warm-white); }
  .services-intro { text-align: center; max-width: 620px; margin: 0 auto 3rem; }
  .services-intro h2 { font-size: clamp(1.9rem, 3vw, 2.6rem); color: var(--deep); margin-bottom: 1rem; }
  .services-intro p { color: var(--text-muted); }

  .services-grid {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    gap: 1.5rem;
  }
  .service-card {
    background: var(--cream);
    border: 1px solid rgba(28,23,20,.08);
    border-radius: 3px;
    padding: 1.8rem 1.6rem;
    transition: box-shadow .2s, transform .2s;
    position: relative;
    overflow: hidden;
  }
  .service-card:hover { transform: translateY(-3px); box-shadow: 0 12px 40px rgba(28,23,20,.1); }
  .service-card::before {
    content: attr(data-heb);
    position: absolute; top: -.5rem; right: .5rem;
    font-family: var(--serif); font-size: 5rem;
    color: rgba(201,150,62,.07);
    line-height: 1;
    pointer-events: none;
  }
  .service-tag {
    display: inline-block;
    font-size: .72rem; font-weight: 600;
    letter-spacing: .12em; text-transform: uppercase;
    padding: .2rem .7rem; border-radius: 2px;
    margin-bottom: 1rem;
  }
  .tag-youth { background: rgba(74,103,65,.12); color: var(--sage); }
  .tag-adult { background: rgba(30,45,64,.1); color: var(--deep); }
  .tag-all   { background: rgba(201,150,62,.12); color: #7a5c1e; }
  .service-card h3 { font-size: 1.15rem; color: var(--deep); margin-bottom: .7rem; }
  .service-card p { font-size: .9rem; color: var(--text-muted); line-height: 1.6; margin-bottom: 1rem; }
  .service-rate {
    font-family: var(--serif);
    font-size: 1.1rem;
    color: var(--gold);
    font-weight: 600;
  }

  /* ─── Pricing ────────────────────────────────────── */
  .section-pricing { background: var(--deep); padding: 5rem 0; }
  .pricing-intro { text-align: center; max-width: 580px; margin: 0 auto 3rem; }
  .pricing-intro h2 { font-size: clamp(1.9rem, 3vw, 2.5rem); color: var(--cream); margin-bottom: 1rem; }
  .pricing-intro p { color: rgba(247,243,236,.65); }

  .pricing-grid {
    display: grid; grid-template-columns: repeat(3, 1fr);
    gap: 1.5rem;
  }
  .price-card {
    background: rgba(247,243,236,.05);
    border: 1px solid rgba(201,150,62,.15);
    border-radius: 3px;
    padding: 2rem 1.8rem;
    text-align: center;
    transition: border-color .2s;
  }
  .price-card:hover { border-color: rgba(201,150,62,.4); }
  .price-card.featured {
    border-color: var(--gold);
    background: rgba(201,150,62,.07);
    position: relative;
  }
  .featured-badge {
    position: absolute; top: -1px; left: 50%; transform: translateX(-50%);
    background: var(--gold); color: var(--midnight);
    font-size: .72rem; font-weight: 700; letter-spacing: .1em; text-transform: uppercase;
    padding: .25rem .9rem;
    border-radius: 0 0 3px 3px;
  }
  .price-card h3 { font-size: 1.1rem; color: var(--cream); margin-bottom: .5rem; }
  .price-amount {
    font-family: var(--serif);
    font-size: 2.8rem;
    color: var(--gold-lt);
    line-height: 1.1;
    margin: .8rem 0 .3rem;
  }
  .price-amount span { font-size: 1rem; color: rgba(247,243,236,.5); vertical-align: middle; }
  .price-desc { font-size: .88rem; color: rgba(247,243,236,.55); margin-bottom: 1.4rem; }
  .price-features { list-style: none; text-align: left; margin-bottom: 1.5rem; }
  .price-features li {
    font-size: .88rem; color: rgba(247,243,236,.7);
    padding: .3rem 0;
    border-bottom: 1px solid rgba(247,243,236,.06);
    padding-left: 1.2rem;
    position: relative;
  }
  .price-features li::before { content: '✦'; position: absolute; left: 0; color: var(--gold); font-size: .6rem; top: .55rem; }
  .btn-price {
    display: block;
    border: 1px solid rgba(201,150,62,.4);
    color: var(--gold-lt);
    text-align: center;
    padding: .65rem;
    border-radius: 2px;
    text-decoration: none;
    font-size: .9rem;
    font-weight: 600;
    transition: background .2s, color .2s;
  }
  .btn-price:hover { background: rgba(201,150,62,.15); }
  .price-card.featured .btn-price {
    background: var(--gold);
    color: var(--midnight);
    border-color: var(--gold);
  }
  .price-card.featured .btn-price:hover { background: var(--gold-lt); }

  .pricing-note {
    text-align: center; margin-top: 2rem;
    font-size: .88rem; color: rgba(247,243,236,.45);
    font-style: italic;
    font-family: var(--serif);
  }

  /* ─── Group Learning ─────────────────────────────── */
  .group-banner {
    background: var(--gold);
    padding: 3rem 0;
    text-align: center;
  }
  .group-banner h2 { font-size: clamp(1.6rem, 2.5vw, 2.2rem); color: var(--midnight); margin-bottom: .7rem; }
  .group-banner p { color: rgba(15,28,46,.75); max-width: 580px; margin: 0 auto 1.5rem; }
  .group-banner .btn-dark {
    display: inline-block;
    background: var(--midnight);
    color: var(--gold-lt);
    padding: .85rem 2rem;
    border-radius: 2px;
    font-weight: 700;
    text-decoration: none;
    font-size: .95rem;
    letter-spacing: .03em;
    transition: background .2s;
  }
  .group-banner .btn-dark:hover { background: var(--deep); }

  /* ─── Testimonials ───────────────────────────────── */
  .section-testimonials { background: var(--cream); }
  .testimonials-intro { text-align: center; max-width: 520px; margin: 0 auto 3rem; }
  .testimonials-intro h2 { font-size: clamp(1.8rem, 2.8vw, 2.4rem); color: var(--deep); margin-bottom: .8rem; }
  .testimonials-grid { display: grid; grid-template-columns: repeat(3, 1fr); gap: 1.5rem; }
  .testimonial {
    background: var(--warm-white);
    border: 1px solid rgba(28,23,20,.08);
    border-radius: 3px;
    padding: 1.8rem 1.6rem;
  }
  .testimonial-stars { color: var(--gold); font-size: 1rem; margin-bottom: .8rem; }
  .testimonial-text {
    font-family: var(--serif);
    font-style: italic;
    font-size: 1.07rem;
    color: var(--deep);
    line-height: 1.65;
    margin-bottom: 1.2rem;
  }
  .testimonial-author { font-size: .85rem; font-weight: 600; color: var(--text-muted); }
  .testimonial-role { font-size: .82rem; color: var(--text-muted); opacity: .7; }

  /* ─── Success Vision ─────────────────────────────── */
  .section-success {
    background: var(--midnight);
    text-align: center;
    padding: 5.5rem 0;
  }
  .section-success h2 {
    font-size: clamp(2rem, 3.5vw, 3rem);
    color: var(--cream);
    max-width: 760px;
    margin: 0 auto 1.5rem;
    line-height: 1.2;
  }
  .section-success h2 em { font-style: italic; color: var(--gold-lt); }
  .section-success p {
    color: rgba(247,243,236,.65);
    max-width: 580px;
    margin: 0 auto 2.5rem;
    font-size: 1.05rem;
  }

  /* ─── FAQ ────────────────────────────────────────── */
  .section-faq { background: var(--warm-white); }
  .faq-intro { text-align: center; max-width: 520px; margin: 0 auto 3rem; }
  .faq-intro h2 { font-size: clamp(1.8rem, 2.8vw, 2.4rem); color: var(--deep); margin-bottom: .8rem; }
  .faq-grid { display: grid; grid-template-columns: 1fr 1fr; gap: 1.5rem; max-width: 900px; margin: 0 auto; }
  .faq-item {
    background: var(--cream);
    border: 1px solid rgba(28,23,20,.07);
    border-radius: 3px;
    padding: 1.5rem 1.4rem;
  }
  .faq-item h4 { font-family: var(--sans); font-size: .98rem; font-weight: 600; color: var(--deep); margin-bottom: .5rem; }
  .faq-item p { font-size: .9rem; color: var(--text-muted); }

  /* ─── Contact / CTA ──────────────────────────────── */
  .section-contact { background: var(--parchment); }
  .contact-inner {
    display: grid; grid-template-columns: 1fr 1fr;
    gap: 5rem; align-items: start;
  }
  .contact-left h2 { font-size: clamp(1.8rem, 2.8vw, 2.4rem); color: var(--deep); margin-bottom: 1rem; }
  .contact-left p { color: var(--text-muted); margin-bottom: .7rem; font-size: 1rem; }
  .contact-meta {
    margin-top: 2rem;
    display: flex; flex-direction: column; gap: .8rem;
  }
  .meta-item { display: flex; align-items: center; gap: .7rem; font-size: .95rem; color: var(--ink); }
  .meta-icon { font-size: 1.2rem; }

  .contact-form { display: flex; flex-direction: column; gap: 1rem; }
  .form-row { display: grid; grid-template-columns: 1fr 1fr; gap: 1rem; }
  label { display: block; font-size: .82rem; font-weight: 600; color: var(--ink); margin-bottom: .35rem; letter-spacing: .03em; }
  input, select, textarea {
    width: 100%;
    padding: .7rem .9rem;
    border: 1px solid rgba(28,23,20,.2);
    border-radius: 2px;
    font-family: var(--sans);
    font-size: .95rem;
    background: var(--warm-white);
    color: var(--ink);
    transition: border-color .2s;
    outline: none;
  }
  input:focus, select:focus, textarea:focus { border-color: var(--gold); }
  textarea { resize: vertical; min-height: 100px; }
  .btn-submit {
    background: var(--deep);
    color: var(--cream);
    border: none;
    padding: .9rem 2rem;
    border-radius: 2px;
    font-family: var(--sans);
    font-weight: 700;
    font-size: 1rem;
    cursor: pointer;
    letter-spacing: .03em;
    transition: background .2s;
    align-self: flex-start;
  }
  .btn-submit:hover { background: var(--midnight); }
  .form-note { font-size: .8rem; color: var(--text-muted); font-style: italic; }

  /* ─── Footer ─────────────────────────────────────── */
  footer {
    background: var(--ink);
    padding: 2.5rem 0;
    text-align: center;
  }
  footer p { font-size: .85rem; color: rgba(247,243,236,.35); }
  footer a { color: rgba(201,150,62,.6); text-decoration: none; }
  footer a:hover { color: var(--gold); }
  .footer-top {
    display: flex; justify-content: space-between; align-items: center;
    margin-bottom: 1.5rem; flex-wrap: wrap; gap: 1rem;
  }
  .footer-logo { font-family: var(--serif); font-size: 1.2rem; color: rgba(247,243,236,.5); }
  .footer-logo span { color: var(--gold); }
  .footer-links { display: flex; gap: 1.5rem; flex-wrap: wrap; }
  .footer-links a { font-size: .85rem; color: rgba(247,243,236,.35); text-decoration: none; }
  .footer-links a:hover { color: var(--gold); }

  /* ─── Responsive ─────────────────────────────────── */
  @media (max-width: 900px) {
    .hero-grid, .guide-grid, .contact-inner { grid-template-columns: 1fr; gap: 2.5rem; }
    .hebrew-deco { display: none; }
    .hero-visual { display: none; }
    .problem-cards, .services-grid, .pricing-grid, .testimonials-grid { grid-template-columns: 1fr; }
    .steps { grid-template-columns: 1fr; }
    .steps::before { display: none; }
    .creds { grid-template-columns: 1fr; }
    .faq-grid { grid-template-columns: 1fr; }
    .form-row { grid-template-columns: 1fr; }
    .nav-links { display: none; }
  }

  /* ─── Animations ─────────────────────────────────── */
  @keyframes fadeUp {
    from { opacity: 0; transform: translateY(24px); }
    to   { opacity: 1; transform: translateY(0); }
  }
  .hero-eyebrow { animation: fadeUp .7s .1s both; }
  .hero h1       { animation: fadeUp .7s .25s both; }
  .hero-sub      { animation: fadeUp .7s .4s both; }
  .hero-btns     { animation: fadeUp .7s .55s both; }
</style>
</head>
<body>

<!-- ══════════ NAV ══════════ -->
<nav>
  <div class="nav-inner">
    <a href="#" class="nav-logo">Learn<span>WithYoni</span></a>
    <ul class="nav-links">
      <li><a href="#services">Services</a></li>
      <li><a href="#pricing">Pricing</a></li>
      <li><a href="#about">About</a></li>
      <li><a href="#faq">FAQ</a></li>
      <li><a href="#contact" class="nav-cta">Book a Free Call</a></li>
    </ul>
  </div>
</nav>

<!-- ══════════ HERO ══════════ -->
<!-- SEO: Aspirational identity — you become the hero, I'm the guide -->
<section class="hero">
  <div class="container">
    <div class="hero-grid">
      <div class="hero-copy">
        <div class="hero-eyebrow">Jewish Education &amp; Tutoring · Denver, CO &amp; Virtual</div>
        <h1>
          Become the <em>Jewish person<br>you've always wanted to be.</em>
        </h1>
        <p class="hero-sub">
          Whether your child is preparing for a B'nai Mitzvah, you're an adult ready to go deeper into Torah and Jewish identity, or you simply want to reconnect — you deserve a guide who makes Jewish learning come alive.
        </p>
        <div class="hero-btns">
          <a href="#contact" class="btn-primary">Book a Free Intro Call</a>
          <a href="#services" class="btn-ghost">Explore Services</a>
        </div>
      </div>
      <div class="hero-visual">
        <div class="hebrew-deco">לִמּוּד</div>
        <div class="hero-card">
          <div class="hero-stat">
            <span class="stat-num">10+</span>
            <span class="stat-label">Years teaching across all denominations</span>
          </div>
          <div class="hero-stat">
            <span class="stat-num">100s</span>
            <span class="stat-label">Of students and educators taught</span>
          </div>
          <div class="hero-stat">
            <span class="stat-num serif" style="font-size:1.5rem;line-height:1.4;color:var(--gold-lt)">In-Person + Virtual</span>
            <span class="stat-label">Denver metro and anywhere online</span>
          </div>
        </div>
      </div>
    </div>
  </div>
</section>

<!-- ══════════ TRUST BAR ══════════ -->
<div class="trust-bar">
  <div class="container">
    <div class="trust-items">
      <span><span class="trust-icon">📺</span> Educator &amp; Host, Unpacked for Educators</span>
      <span><span class="trust-icon">🎙️</span> Public Speaker &amp; Curriculum Designer</span>
      <span><span class="trust-icon">✡️</span> 10+ Years Across All Denominations</span>
      <span><span class="trust-icon">🌐</span> In-Person (Denver) &amp; Virtual Worldwide</span>
    </div>
  </div>
</div>

<!-- ══════════ PROBLEM / HERO'S STRUGGLE ══════════ -->
<section class="section-problem" id="problem">
  <div class="container">
    <div class="problem-intro">
      <span class="section-eyebrow">You're Not Alone</span>
      <h2>Jewish learning should feel meaningful — not like a to-do list.</h2>
      <p>Most families and adults know they want more from their Jewish life. But between busy synagogue programs, generic online resources, and tutors who just drill Hebrew without context — it never quite lands.</p>
    </div>
    <div class="problem-cards">
      <div class="prob-card">
        <h3>The B'nai Mitzvah Family</h3>
        <p>Your child's big day is approaching. The synagogue program is fine — but you want your kid to actually <em>understand</em> what they're doing, connect to their portion, and walk away with a real relationship to Jewish life. Not just a performance.</p>
      </div>
      <div class="prob-card">
        <h3>The Adult Who Missed Out</h3>
        <p>You had a Bar or Bat Mitzvah, or maybe you didn't. Either way, there are gaps — in Hebrew, in texts, in history, in identity. You're ready to finally learn as an adult, on your own terms, without judgment.</p>
      </div>
      <div class="prob-card">
        <h3>The Curious Learner</h3>
        <p>Torah, Israel, Jewish history, mindfulness, dialogue across difference — there's so much you want to explore, but you've never had a guide who could go deep, engage complexity, and make it genuinely fascinating.</p>
      </div>
    </div>
  </div>
</section>

<!-- ══════════ GUIDE / ABOUT ══════════ -->
<section class="section-guide" id="about">
  <div class="container">
    <div class="guide-grid">
      <div class="guide-avatar">
        <span style="position:relative;z-index:1;font-size:4rem;color:rgba(201,150,62,.3)">י</span>
      </div>
      <div class="guide-content">
        <span class="section-eyebrow guide-eyebrow">Your Guide</span>
        <h2>Hi — I'm Yoni.<br><em>I've spent my life inside Jewish learning.</em></h2>
        <p>I grew up in a Hebrew-speaking household, attended Jewish day school, and went on to spend over a decade working in synagogues across the denominational spectrum — from Orthodox to Reform and everywhere in between.</p>
        <p>Today I'm a Senior Educator at OpenDor Media, where I work under the Unpacked for Educators and ConnectED brands. I train teachers at elite independent and private schools across North America, design curriculum that helps students and educators engage Jewish history, antisemitism, Israel, and dialogue with intellectual honesty and depth. I host and lead the Unpacked Junior video series, and I'm a national public speaker.</p>
        <p>When I'm not traveling for work, I'm here in Denver — and I take on a small number of private students. Because I believe great Jewish education changes lives. And it should be available to more people.</p>
        <div class="creds">
          <div class="cred-item">
            <span class="cred-icon">📚</span>
            <span class="cred-text"><strong>Senior Educator, OpenDor Media</strong>Curriculum design, teacher training, and student programming across North America</span>
          </div>
          <div class="cred-item">
            <span class="cred-icon">📺</span>
            <span class="cred-text"><strong>Host &amp; Education Lead, Unpacked Junior</strong>Nationally distributed Jewish educational video series for youth</span>
          </div>
          <div class="cred-item">
            <span class="cred-icon">🎙️</span>
            <span class="cred-text"><strong>Public Speaker &amp; PD Facilitator</strong>Schools, conferences, and communities — including Dialogue Across Difference programming</span>
          </div>
          <div class="cred-item">
            <span class="cred-icon">✡️</span>
            <span class="cred-text"><strong>10+ Years in Synagogues</strong>Worked across Orthodox, Conservative, Reform, and pluralistic settings; B'nai mitzvah tutoring, adult learning, and more</span>
          </div>
        </div>
      </div>
    </div>
  </div>
</section>

<!-- ══════════ PLAN / HOW IT WORKS ══════════ -->
<section class="section-plan" id="how">
  <div class="container">
    <div class="plan-intro">
      <span class="section-eyebrow">Simple. Personal. No Pressure.</span>
      <h2>Getting started is three easy steps.</h2>
      <p>No lengthy intake forms. No jargon. Just a real conversation about what you're looking for — and a path forward that fits your life.</p>
    </div>
    <div class="steps">
      <div class="step">
        <div class="step-num">1</div>
        <h3>Book a Free Intro Call</h3>
        <p>15–20 minutes on Zoom. You share what you're looking for; I share how I can help. No commitment required — just a conversation.</p>
      </div>
      <div class="step">
        <div class="step-num">2</div>
        <h3>Get a Custom Learning Plan</h3>
        <p>Whether it's B'nai mitzvah prep, Torah study, Hebrew, or Jewish identity — we'll map out a program designed around your goals, schedule, and learning style.</p>
      </div>
      <div class="step">
        <div class="step-num">3</div>
        <h3>Learn. Connect. Come Alive.</h3>
        <p>Show up for sessions that are intellectually engaging, personally meaningful, and free of judgment. Jewish learning that sticks.</p>
      </div>
    </div>
  </div>
</section>

<!-- ══════════ SERVICES ══════════ -->
<section class="section-services" id="services">
  <div class="container">
    <div class="services-intro">
      <span class="section-eyebrow">What We'll Learn Together</span>
      <h2>Every Jewish journey is different. Here's how I can guide yours.</h2>
      <p>I work with youth and adults, beginners and advanced learners, affiliated families and the entirely unaffiliated. In-person in Denver or virtually anywhere in the world.</p>
    </div>
    <div class="services-grid">
      <div class="service-card" data-heb="מִצְוָה">
        <span class="service-tag tag-youth">Youth &amp; Families</span>
        <h3>B'nai Mitzvah Preparation</h3>
        <p>Full, personalized B'nai mitzvah tutoring: Hebrew reading, trope (Torah and haftarah cantillation), leading prayers, writing a meaningful d'var Torah, and designing creative, personal rituals. I help your child understand <em>why</em> — not just memorize how.</p>
        <div class="service-rate">From $450/month</div>
      </div>
      <div class="service-card" data-heb="עִבְרִית">
        <span class="service-tag tag-all">All Ages</span>
        <h3>Hebrew Language</h3>
        <p>Biblical Hebrew reading (liturgical and Torah), modern Hebrew conversation, and advanced trope skills for experienced readers. Whether you're starting from the aleph-bet or ready to leyn a full parasha, I meet you where you are.</p>
        <div class="service-rate">$125/hour</div>
      </div>
      <div class="service-card" data-heb="תּוֹרָה">
        <span class="service-tag tag-all">All Ages</span>
        <h3>Torah &amp; Tanach Study</h3>
        <p>My personal passion. Deep textual study of the Hebrew Bible — Torah, Nevi'im, Ketuvim — with attention to literary meaning, rabbinic interpretation, and contemporary resonance. For beginners seeking a foundation or advanced learners wanting to go further.</p>
        <div class="service-rate">$125/hour</div>
      </div>
      <div class="service-card" data-heb="זֶהוּת">
        <span class="service-tag tag-adult">Adults</span>
        <h3>Jewish Identity &amp; Israel Education</h3>
        <p>Explore what it means to be Jewish today — Zionism, Israel, antisemitism, Jewish peoplehood, and how your story connects to a 3,500-year thread. Ideal for adults navigating complicated feelings or wanting a sophisticated, honest framework.</p>
        <div class="service-rate">$125/hour</div>
      </div>
      <div class="service-card" data-heb="שִׁיחָה">
        <span class="service-tag tag-all">All Ages</span>
        <h3>Dialogue Across Difference</h3>
        <p>Based on my nationally recognized curriculum, this is training in the skills of productive dialogue — how to hold complexity, engage disagreement, and find curiosity instead of certainty. For families, students, or groups navigating hard conversations.</p>
        <div class="service-rate">$125/hour · or Group Rate</div>
      </div>
      <div class="service-card" data-heb="הֲכָנָה">
        <span class="service-tag tag-youth">Youth &amp; Families</span>
        <h3>School Readiness &amp; Enrichment</h3>
        <p>Entering a Jewish day school, Hebrew school, or religious school? I can help students prepare with targeted academic support. Or, for students already enrolled, enrichment study in Torah, Jewish history, or any area where curiosity is running ahead of the classroom.</p>
        <div class="service-rate">$125/hour</div>
      </div>
      <div class="service-card" data-heb="בֵּרָכָה">
        <span class="service-tag tag-adult">Adults</span>
        <h3>Adult B'nai Mitzvah</h3>
        <p>It's never too late. Whether you're finally having the B'nai Mitzvah you never had, or renewing your connection to a milestone from long ago — I specialize in making the adult B'nai mitzvah experience personally profound and intellectually rich.</p>
        <div class="service-rate">Custom packages available</div>
      </div>
      <div class="service-card" data-heb="חַיִּים">
        <span class="service-tag tag-adult">Adults</span>
        <h3>Lifecycle &amp; Creative Ritual Design</h3>
        <p>Designing a meaningful Jewish lifecycle ceremony — wedding, brit milah, conversion, shloshim, or other passage? I help you think through the Jewish texts, rituals, and creative elements that will make it deeply personal and genuinely beautiful.</p>
        <div class="service-rate">$125/hour</div>
      </div>
      <div class="service-card" data-heb="לִמּוּד">
        <span class="service-tag tag-adult">Adults</span>
        <h3>Adult Jewish Learning &amp; Wisdom</h3>
        <p>Jewish texts, history, philosophy, mindfulness, and spiritual wisdom for adult learners. Ideal for individuals or couples who are curious, spiritually seeking, or simply want to know their tradition better — without dogma, on their own terms.</p>
        <div class="service-rate">$125/hour</div>
      </div>
    </div>
  </div>
</section>

<!-- ══════════ GROUP BANNER ══════════ -->
<div class="group-banner">
  <div class="container">
    <h2>Want to learn together? Group Learning Circles available.</h2>
    <p>Gather up to 12 adults for a single group session or a multi-week series. Topics: Torah, Jewish history, Israel, Dialogue Across Difference, Jewish wisdom, and more. One flat rate — the learning belongs to everyone in the room.</p>
    <p><strong>$500 per session · Up to 12 participants · ~2 hours</strong></p>
    <a href="#contact" class="btn-dark">Inquire About Group Learning</a>
  </div>
</div>

<!-- ══════════ PRICING ══════════ -->
<section class="section-pricing" id="pricing">
  <div class="container">
    <div class="pricing-intro">
      <span class="section-eyebrow" style="color:var(--gold)">Transparent Pricing</span>
      <h2>Flexible options for every learner.</h2>
      <p>No hidden fees. No long-term commitments required. I want learning to be accessible, so let's find what works for your situation.</p>
    </div>
    <div class="pricing-grid">
      <div class="price-card">
        <h3>Single Session</h3>
        <div class="price-amount">$125 <span>/ hour</span></div>
        <div class="price-desc">Pay as you go. In-person (Denver) or Zoom.</div>
        <ul class="price-features">
          <li>Any subject area</li>
          <li>Youth or adult</li>
          <li>In-person or virtual</li>
          <li>60-minute sessions</li>
        </ul>
        <a href="#contact" class="btn-price">Book a Session</a>
      </div>
      <div class="price-card featured">
        <div class="featured-badge">Most Popular</div>
        <h3>B'nai Mitzvah Monthly</h3>
        <div class="price-amount">$450 <span>/ month</span></div>
        <div class="price-desc">4 sessions/month — best for consistent prep.</div>
        <ul class="price-features">
          <li>4 weekly sessions (60 min each)</li>
          <li>Hebrew + trope + d'var Torah</li>
          <li>Portion-specific materials</li>
          <li>Parent update each month</li>
          <li>In-person or virtual</li>
        </ul>
        <a href="#contact" class="btn-price">Start B'nai Mitzvah Prep</a>
      </div>
      <div class="price-card">
        <h3>Group Learning Circle</h3>
        <div class="price-amount">$500 <span>/ session</span></div>
        <div class="price-desc">Up to 12 adults. ~2 hours. Any Jewish topic.</div>
        <ul class="price-features">
          <li>Torah, Tanach, Jewish history</li>
          <li>Israel &amp; Jewish identity</li>
          <li>Dialogue Across Difference</li>
          <li>Jewish wisdom &amp; mindfulness</li>
          <li>Series pricing available</li>
        </ul>
        <a href="#contact" class="btn-price">Inquire About Groups</a>
      </div>
    </div>
    <p class="pricing-note">Need something custom? Full-year B'nai Mitzvah packages, adult learning series, and lifecycle consultation packages available. Let's talk.</p>
  </div>
</section>

<!-- ══════════ TESTIMONIALS ══════════ -->
<section class="section-testimonials">
  <div class="container">
    <div class="testimonials-intro">
      <span class="section-eyebrow">What Students &amp; Families Say</span>
      <h2>Jewish learning that sticks.</h2>
    </div>
    <div class="testimonials-grid">
      <div class="testimonial">
        <div class="testimonial-stars">★★★★★</div>
        <div class="testimonial-text">"Yoni didn't just teach my daughter her Torah portion. He helped her understand <em>why</em> it matters, and why she matters. She walked onto the bima with real confidence — not just rehearsed words."</div>
        <div class="testimonial-author">B'nai Mitzvah Family</div>
        <div class="testimonial-role">Denver, CO</div>
      </div>
      <div class="testimonial">
        <div class="testimonial-stars">★★★★★</div>
        <div class="testimonial-text">"I'd wanted to do adult Jewish learning for years but felt too far behind. Yoni made it feel completely natural. His Torah teaching is unlike anything I'd experienced — I actually wanted to come back every week."</div>
        <div class="testimonial-author">Adult Learner</div>
        <div class="testimonial-role">Virtual Student</div>
      </div>
      <div class="testimonial">
        <div class="testimonial-stars">★★★★★</div>
        <div class="testimonial-text">"Our group hired Yoni for a four-session series on the Israeli-Palestinian conflict. He brought nuance, clarity, and genuine intellectual depth. Everyone left with more questions — in the best possible way."</div>
        <div class="testimonial-author">Adult Learning Group</div>
        <div class="testimonial-role">Denver, CO</div>
      </div>
    </div>
  </div>
</section>

<!-- ══════════ SUCCESS VISION ══════════ -->
<section class="section-success">
  <div class="container">
    <h2>Imagine standing at the bima — or the Shabbat table — and feeling <em>at home.</em></h2>
    <p>That's the goal. Not just knowing your parasha. Not just being able to read Hebrew. But feeling like Jewish learning belongs to you — because it does.</p>
    <a href="#contact" class="btn-primary">Begin Your Learning Journey</a>
  </div>
</section>

<!-- ══════════ FAQ ══════════ -->
<section class="section-faq" id="faq">
  <div class="container">
    <div class="faq-intro">
      <span class="section-eyebrow">Common Questions</span>
      <h2>Frequently Asked Questions</h2>
    </div>
    <div class="faq-grid">
      <div class="faq-item">
        <h4>Do you work alongside synagogue programs?</h4>
        <p>Absolutely, and I prefer it. I'm happy to supplement your synagogue's B'nai mitzvah program — providing extra prep, enrichment, or the personal depth that busy clergy often can't offer one-on-one. I am not a substitute for your synagogue community.</p>
      </div>
      <div class="faq-item">
        <h4>We're not affiliated with a synagogue. Can you still help?</h4>
        <p>Yes. I've worked with families from across the denominational spectrum and with many unaffiliated families. Whether you're planning a B'nai mitzvah outside a synagogue, or simply want Jewish learning without the institutional context, I can help you build something meaningful.</p>
      </div>
      <div class="faq-item">
        <h4>My child has no Hebrew background. Is that okay?</h4>
        <p>That's exactly where I start with many students. I teach Hebrew reading from the aleph-bet. With consistent practice, most students can reach B'nai mitzvah-level Hebrew reading in 12–18 months — and many in less.</p>
      </div>
      <div class="faq-item">
        <h4>I'm an adult who feels totally behind. Will I feel judged?</h4>
        <p>Never. Adult learners are some of my favorite students. Coming to Jewish learning as an adult — with questions, with life experience, with a critical mind — makes for the richest possible learning. No background required. Just curiosity.</p>
      </div>
      <div class="faq-item">
        <h4>How does virtual tutoring work?</h4>
        <p>All sessions are conducted via Zoom. I share materials digitally and we work through everything together on screen. Virtual is actually excellent for trope and Hebrew work — many of my students prefer it for the flexibility it offers.</p>
      </div>
      <div class="faq-item">
        <h4>What is Dialogue Across Difference?</h4>
        <p>It's a curriculum I developed for teaching the skills of productive dialogue — how to hold complexity, listen to different perspectives, and engage controversial topics with curiosity rather than defensiveness. I offer this for individuals, families, and groups. It's especially powerful for families navigating disagreement about Israel, politics, or Jewish identity.</p>
      </div>
      <div class="faq-item">
        <h4>How far in advance should we start B'nai Mitzvah prep?</h4>
        <p>For students with no Hebrew background: ideally 18–24 months before the date. For students with some Hebrew: 12 months is usually comfortable. Shorter timelines are possible — I've helped students learn Torah portions in as little as 3 months — but more time means less stress and richer learning.</p>
      </div>
      <div class="faq-item">
        <h4>Do you offer group classes for youth, or just adults?</h4>
        <p>My group Learning Circles are designed for adults (12 max). For youth, I focus on individual or family tutoring, which I find most effective for B'nai mitzvah prep and enrichment work. If you have a specific group request for youth, reach out and we'll talk through options.</p>
      </div>
    </div>
  </div>
</section>

<!-- ══════════ CONTACT ══════════ -->
<section class="section-contact" id="contact">
  <div class="container">
    <div class="contact-inner">
      <div class="contact-left">
        <span class="section-eyebrow">Let's Connect</span>
        <h2>Ready to begin?<br>Let's talk.</h2>
        <p>Start with a free 15-minute intro call. Tell me where you are in your Jewish journey — and I'll share how I might help.</p>
        <p>There's no pressure, no commitment, and no wrong place to start.</p>
        <div class="contact-meta">
          <div class="meta-item"><span class="meta-icon">📍</span> Denver, CO (in-person) &amp; Zoom (everywhere)</div>
          <div class="meta-item"><span class="meta-icon">✉️</span> yoni@learnwithyoni.com</div>
          <div class="meta-item"><span class="meta-icon">📅</span> Free intro call — 15 minutes, no commitment</div>
        </div>
      </div>
      <div class="contact-right">
        <form class="contact-form" onsubmit="handleSubmit(event)">
          <div class="form-row">
            <div>
              <label for="fname">First Name</label>
              <input type="text" id="fname" placeholder="Your first name" required />
            </div>
            <div>
              <label for="lname">Last Name</label>
              <input type="text" id="lname" placeholder="Your last name" />
            </div>
          </div>
          <div>
            <label for="email">Email Address</label>
            <input type="email" id="email" placeholder="you@example.com" required />
          </div>
          <div>
            <label for="interest">What brings you here?</label>
            <select id="interest">
              <option value="">Select a category</option>
              <option>B'nai Mitzvah prep (youth)</option>
              <option>Adult B'nai Mitzvah</option>
              <option>Hebrew language</option>
              <option>Torah &amp; Tanach study</option>
              <option>Jewish identity &amp; Israel</option>
              <option>Adult Jewish learning / enrichment</option>
              <option>Dialogue Across Difference</option>
              <option>Group Learning Circle</option>
              <option>School readiness or enrichment</option>
              <option>Lifecycle / creative ritual</option>
              <option>Something else</option>
            </select>
          </div>
          <div>
            <label for="message">Tell me a little more (optional)</label>
            <textarea id="message" placeholder="Where are you in your journey? What are you hoping to learn or accomplish? Any timeline or context that's helpful to share..."></textarea>
          </div>
          <button type="submit" class="btn-submit">Send — Let's Talk</button>
          <p class="form-note">I respond within 1–2 business days. Your information is never shared.</p>
        </form>
      </div>
    </div>
  </div>
</section>

<!-- ══════════ FOOTER ══════════ -->
<footer>
  <div class="container">
    <div class="footer-top">
      <div class="footer-logo">Learn<span>WithYoni</span></div>
      <div class="footer-links">
        <a href="#services">Services</a>
        <a href="#pricing">Pricing</a>
        <a href="#about">About</a>
        <a href="#faq">FAQ</a>
        <a href="#contact">Contact</a>
      </div>
    </div>
    <p>Jewish Education &amp; Tutoring · Denver, CO &amp; Virtual · B'nai Mitzvah · Hebrew · Torah · Jewish Identity · Adult Learning</p>
    <p style="margin-top:.5rem">© 2025 Learn With Yoni · <a href="mailto:yoni@learnwithyoni.com">yoni@learnwithyoni.com</a></p>
  </div>
</footer>

<script>
function handleSubmit(e) {
  e.preventDefault();
  const btn = e.target.querySelector('.btn-submit');
  btn.textContent = '✓ Message Sent! I\'ll be in touch soon.';
  btn.style.background = '#4a6741';
  btn.disabled = true;
}
</script>

</body>
</html>
