# CraftCSS

**CraftCSS** est un framework CSS léger pour créer des interfaces modernes, responsives et animées avec des classes simples.

> **Write less code, use simple classes, get a responsive & animated result automatically.**

## ✨ Philosophie

* Classes simples et lisibles
* Responsive automatique
* CSS d'abord
* JavaScript uniquement si nécessaire
* Animations simples
* 20 familles de couleurs
* Pas de `primary` / `secondary`
* Pas de `md:`, `lg:`, `xl:`
* Pas de classes Bootstrap
* Documentation avec exemples

### Exemple

```html
<section class="hero hero-split">
```

Le composant gère automatiquement son responsive.

---

## 🎨 Couleurs

20 familles :

```text
red orange amber yellow lime green emerald teal cyan sky
blue indigo violet purple fuchsia pink rose slate gray zinc
```

Nuances :

```text
50 100 200 300 400 500 600 700 800 900 950
```

Exemples :

```html
<div class="bg-blue"></div>
<p class="text-gray-700"></p>
<div class="border-blue-200"></div>
<button class="hover-blue"></button>
```

`bg-blue` utilise `blue-500` par défaut.

---

## ⚡ Animations

### CSS

```text
transition
smooth
hover-up
hover-scale
hover-rotate
hover-shadow
marquee
marquee-reverse
marquee-slow
marquee-fast
```

### Scroll

```text
reveal
fade
show
slide-up
slide-down
slide-left
slide-right
scale-in
zoom
blur-in
```

Les animations au scroll utilisent `IntersectionObserver`.

`prefers-reduced-motion` est respecté.

---

## 🧩 Composants

```text
navbar
hero
bento
card
footer
form
accordion
faq
testimonial
carousel
```

Exemple :

```html
<div class="card card-glass smooth hover-up">
  <h3>CraftCSS</h3>
  <p>Simple UI.</p>
</div>
```

Les composants sont responsives automatiquement.

---

## 🪶 CSS d'abord

CraftCSS évite JavaScript lorsque CSS suffit.

**Sans JS :**

```text
accordion
faq
hover
transition
smooth
marquee
```

**Avec JS lorsque nécessaire :**

```text
navbar
scroll reveal
carousel
```

L'Accordion et les FAQ utilisent `<details>` / `<summary>` et sont **100 % CSS**.

---

## 📦 Installation

```html
<link rel="stylesheet" href="dist/craftcss.css">
<script src="dist/craftcss.js"></script>
```

Le JavaScript est automatiquement initialisé.

---

## 📁 Structure

```text
craftcss/
├── dist/
├── src/
│   ├── css/
│   └── js/
├── docs/
└── README.md
```

Les documentations détaillées se trouvent dans `docs/`.

---

## 📚 Documentation

Chaque composant possède sa documentation avec :

* classes ;
* variantes ;
* responsive ;
* animations ;
* couleurs ;
* exemples HTML.

```text
docs/navbar/README.md
docs/hero/README.md
docs/card/README.md
...
```

---

## 🚀 Objectif

CraftCSS se situe entre un **framework CSS utilitaire léger** et une **bibliothèque de composants CSS**.

```text
Classes simples
      +
Responsive automatique
      +
CSS-first
      +
Animations simples
      +
JS minimal
      =
CraftCSS
```

**CraftCSS — Simple classes. Automatic responsive. Clean UI.**
