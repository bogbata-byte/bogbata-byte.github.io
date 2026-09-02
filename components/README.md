# Dossier composants

Les blocs ci-dessous correspondent aux sections du portfolio. Ils sont construits sans dependance JavaScript externe afin de rester faciles a reprendre.

## 1. Navigation

```html
<header class="site-header">
  <a class="brand" href="#accueil">Enzo Yangandia</a>
  <nav class="main-nav" aria-label="Navigation principale">
    <a href="#profil">Profil</a>
    <a href="#projets">Projets</a>
    <a href="#parcours">Parcours</a>
  </nav>
</header>
```

## 2. Hero

```html
<section class="hero section-wrap" aria-labelledby="hero-title">
  <div class="hero-copy">
    <p class="eyebrow">Portfolio personnel</p>
    <h1 id="hero-title">Je construis<br><em>avec intention.</em></h1>
    <a class="button button-dark" href="#projets">Decouvrir mes projets</a>
  </div>
  <div class="hero-visual">
    <div class="image-frame">
      <img src="assets/enzo.jpg" alt="Portrait d'Enzo Yangandia">
    </div>
  </div>
</section>
```

## 3. Carte projet

```html
<article class="project-card">
  <div class="card-top">
    <span class="project-index">01 / 03</span>
    <span class="project-type">Organisation</span>
  </div>
  <div class="project-visual visual-notary">
    <span class="visual-letter">N</span>
  </div>
  <div class="card-content">
    <h3>Realisation d'un notariat</h3>
    <p>Un projet organise autour de la confiance et de la clarte.</p>
    <a class="card-arrow" href="#contact" aria-label="Voir le projet">↗</a>
  </div>
</article>
```

## 4. Parcours

```html
<div class="timeline">
  <div class="timeline-item">
    <span class="timeline-date">CI → 4e</span>
    <div>
      <h3>Lycee La Renaissance</h3>
      <p>Les premieres bases et l'envie de comprendre.</p>
    </div>
  </div>
</div>
```

## 5. Contact

```html
<section class="contact-section">
  <div class="section-wrap contact-inner">
    <p class="eyebrow">03 · Contact</p>
    <h2>Une idee en tete ?<br><em>Parlons-en.</em></h2>
    <a class="contact-email" href="mailto:enzo.yangandia@example.com">
      enzo.yangandia@example.com ↗
    </a>
  </div>
</section>
```

## Conventions UI

- Les couleurs sont centralisees dans `:root` dans `style.css`.
- Les cartes utilisent une bordure fine, un espacement regulier et un etat hover visible.
- Les images possedent un texte alternatif descriptif.
- Le menu mobile se replie via `aria-expanded` et conserve les ancres de section.
- `prefers-reduced-motion` desactive les transitions pour les utilisateurs qui le demandent.
