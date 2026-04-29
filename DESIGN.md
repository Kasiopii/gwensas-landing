---
brand: Gwensas
tagline: "Bitcoin Mining accessible à tous — énergie verte, transparence totale."
personality: "Innovation humaniste meets Fintech premium dark"
---

# Overview

Gwensas est une société française de Bitcoin mining hosting (Bordeaux, 2017) qui héberge des ASIC dans des fermes hydroélectriques au Parc National des Virunga, RDC. À 0,047 €/kWh, ses clients produisent leur Bitcoin au lieu de l'acheter.

**Ambiance visuelle** : Premium fintech sombre + glassmorphism aero + nature volcanique Congo. Technologie avancée au service d'un impact humain réel. Ni corporate froid, ni startup agressive — mineur Bitcoin humaniste et engagé.

**Règle absolue** : Glassmorphism sur toutes les surfaces (backdrop-filter blur + fond semi-transparent + bordure lumineuse). Boutons toujours en pill shape (border-radius 100px). Fond hero toujours sombre.

---

## Colors

```yaml
colors:
  # Brand primaire
  primary: "#009FE3"          # Gwensas Blue — liens, CTA, accents
  primary-dark: "#0077CC"     # Hover états boutons
  primary-xdark: "#005FA3"    # Dégradés profonds, fins de gradient
  
  # Accent Bitcoin
  bitcoin: "#F7931A"          # Bitcoin Orange — exclusivement pour références BTC
  
  # Fonds sombres
  hero-bg: "#06101e"          # Fond hero full-screen canvas mining
  ticker-bg: "#030d18"        # Fond ticker barre top
  navy: "#00294A"             # Sections sombres (KPI, Virunga, footer)
  navy-2: "#003D6B"           # Dégradés sections sombres
  nav-glass: "rgba(8,20,40,0.75)"  # Nav glassmorphism dark
  
  # Fonds clairs
  white: "#FFFFFF"
  off-white: "#F4F8FC"        # Fond subtil cards, pricing
  off-white-2: "#EBF4FC"      # Borders légères
  
  # Texte
  text-primary: "#0A1628"
  text-secondary: "#3D5A73"
  text-muted: "#7A9BB5"       # Labels, captions
  
  # Fonctionnel
  success: "#10B981"          # Vert énergie renouvelable, "actif"
  success-dark: "#059669"
  up: "#4ade80"               # Hausse BTC, indicateur positif
  down: "#f87171"             # Baisse BTC, alerte

  # Glassmorphism surfaces
  glass-light: "rgba(255,255,255,0.65)"     # Cards sur fond clair
  glass-light-heavy: "rgba(255,255,255,0.70)"
  glass-dark: "rgba(255,255,255,0.04)"      # Cards sur fond sombre
  glass-blue: "rgba(0,127,200,0.55)"        # Plan Pro featured
```

**Sémantique couleurs** : `primary` (#009FE3) est la seule couleur d'interaction — tous les liens, focus states, et accents actifs l'utilisent. `bitcoin` (#F7931A) est réservé exclusivement aux références Bitcoin (prix, symbole ₿, "block found"). `success` (#10B981) est réservé à l'énergie verte et aux statuts positifs opérationnels. Ne jamais mélanger `bitcoin` et `primary` sur le même élément.

---

## Typography

```yaml
typography:
  # Familles
  font-display: "'Bricolage Grotesque', sans-serif"
  font-body: "'DM Sans', sans-serif"
  
  # Google Fonts import
  google-fonts-url: "https://fonts.googleapis.com/css2?family=Bricolage+Grotesque:opsz,wght@12..96,300;12..96,400;12..96,500;12..96,600;12..96,700;12..96,800&family=DM+Sans:ital,opsz,wght@0,9..40,300;0,9..40,400;0,9..40,500;0,9..40,600;0,9..40,700;1,9..40,400&display=swap"
  
  # Échelle
  hero-h1:
    fontFamily: "Bricolage Grotesque"
    fontSize: "clamp(3rem, 6.5vw, 5.8rem)"
    fontWeight: 800
    letterSpacing: "-0.04em"
    lineHeight: 1.02
    color: "#FFFFFF"
  
  section-h2:
    fontFamily: "Bricolage Grotesque"
    fontSize: "clamp(2rem, 4vw, 3rem)"
    fontWeight: 700
    letterSpacing: "-0.03em"
    lineHeight: 1.07
    color: "#00294A"
  
  card-h3:
    fontFamily: "Bricolage Grotesque"
    fontSize: "17px"
    fontWeight: 700
    letterSpacing: "-0.01em"
    color: "#00294A"
  
  eyebrow:
    fontFamily: "DM Sans"
    fontSize: "11px"
    fontWeight: 600
    letterSpacing: "0.12em"
    textTransform: "uppercase"
    color: "#009FE3"
  
  body-large:
    fontFamily: "DM Sans"
    fontSize: "17px"
    fontWeight: 400
    lineHeight: 1.72
    color: "#3D5A73"
  
  body:
    fontFamily: "DM Sans"
    fontSize: "14px"
    fontWeight: 400
    lineHeight: 1.7
    color: "#3D5A73"
  
  caption:
    fontFamily: "DM Sans"
    fontSize: "11px"
    fontWeight: 600
    letterSpacing: "0.08em"
    textTransform: "uppercase"
    color: "#7A9BB5"
  
  stat-value:
    fontFamily: "Bricolage Grotesque"
    fontSize: "30px"
    fontWeight: 800
    letterSpacing: "-0.03em"
    color: "#009FE3"
```

**Rationale** : Bricolage Grotesque est choisi pour les titres car sa géométrie humaniste incarne le positionnement Gwensas — technologique mais accessible, innovant mais chaleureux. Éviter font-weight 900 (trop agressif). DM Sans pour le corps : propre, lisible, avec des proportions humanistes qui contrebalancent la rigueur technique du sujet.

---

## Spacing

```yaml
spacing:
  xs: "4px"
  sm: "8px"
  md: "16px"
  lg: "24px"
  xl: "32px"
  2xl: "48px"
  3xl: "72px"
  4xl: "100px"
  
  # Padding sections (desktop)
  section-padding: "100px 72px"
  section-padding-mobile: "60px 24px"
  
  # Largeur max contenu
  content-max: "1100px"
  content-narrow: "800px"
  content-form: "760px"
```

---

## Rounded (Border Radius)

```yaml
rounded:
  sm: "8px"       # Badges, pills internes
  md: "12px"      # Petites cards, inputs
  lg: "16px"      # Cards standard
  xl: "20px"      # Cards principales, glassmorphism panels
  2xl: "24px"     # Modals, grandes surfaces
  pill: "100px"   # TOUS les boutons CTA — règle absolue
  circle: "50%"   # Avatars, dots, icônes rondes
```

---

## Components

```yaml
components:
  # ── BOUTONS ──
  button-primary:
    borderRadius: "100px"        # pill — jamais carré
    padding: "15px 32px"
    background: "linear-gradient(135deg, #009FE3 0%, #005FA3 100%)"
    color: "#FFFFFF"
    fontFamily: "Bricolage Grotesque"
    fontWeight: 700
    fontSize: "15px"
    letterSpacing: "0.02em"
    boxShadow: "0 4px 18px rgba(0,159,227,0.40), inset 0 1px 0 rgba(255,255,255,0.18)"
    hover:
      transform: "translateY(-2px)"
      boxShadow: "0 10px 32px rgba(0,159,227,0.55), inset 0 1px 0 rgba(255,255,255,0.18)"
    icon: "flèche SVG droite, transition translateX(4px) au hover"

  button-ghost:
    borderRadius: "100px"
    padding: "15px 28px"
    background: "transparent"
    border: "1.5px solid rgba(255,255,255,0.18)"
    color: "rgba(255,255,255,0.8)"
    hover:
      borderColor: "#009FE3"
      background: "rgba(0,159,227,0.10)"
      color: "#FFFFFF"
      transform: "translateY(-2px)"

  button-nav:
    borderRadius: "100px"
    padding: "11px 26px"
    background: "linear-gradient(135deg, #009FE3, #005FA3)"
    boxShadow: "0 2px 14px rgba(0,159,227,0.35), inset 0 1px 0 rgba(255,255,255,0.15)"
    icon: "flèche SVG, translateX(3px) au hover"

  # ── CARDS ──
  card-project:
    borderRadius: "20px"
    padding: "28px 24px"
    background: "rgba(255,255,255,0.70)"
    backdropFilter: "blur(12px) saturate(150%)"
    border: "1px solid rgba(0,159,227,0.10)"
    boxShadow: "0 2px 16px rgba(0,41,74,0.05), inset 0 1px 0 rgba(255,255,255,0.95)"
    accentTop: "barre 3px couleur projet en haut de la card"
    cursor: "pointer"
    hover:
      transform: "translateY(-8px)"
      boxShadow: "0 24px 56px rgba(0,159,227,0.18), 0 0 0 1px rgba(0,159,227,0.12)"
      borderColor: "rgba(0,159,227,0.35)"
      accentTopHeight: "5px"

  card-value:
    borderRadius: "20px"
    padding: "28px 24px"
    background: "rgba(255,255,255,0.60)"
    backdropFilter: "blur(16px) saturate(160%)"
    border: "1px solid rgba(0,159,227,0.12)"
    boxShadow: "0 2px 20px rgba(0,41,74,0.06), inset 0 1px 0 rgba(255,255,255,0.90)"
    hover:
      transform: "translateY(-6px)"
      boxShadow: "0 16px 40px rgba(0,159,227,0.15), inset 0 1px 0 rgba(255,255,255,0.95)"

  card-stat-dark:
    background: "rgba(255,255,255,0.04)"
    backdropFilter: "blur(12px)"
    border: "1px solid rgba(255,255,255,0.07)"
    borderRadius: "16px"
    padding: "18px 16px"
    boxShadow: "inset 0 1px 0 rgba(255,255,255,0.08)"

  # ── PLANS TARIFAIRES ──
  plan-standard:
    borderRadius: "20px"
    padding: "32px 26px"
    background: "rgba(255,255,255,0.65)"
    backdropFilter: "blur(20px) saturate(160%)"
    border: "1px solid rgba(0,159,227,0.10)"
    boxShadow: "0 4px 24px rgba(0,41,74,0.06), inset 0 1px 0 rgba(255,255,255,0.90)"

  plan-featured:
    background: "rgba(0,127,200,0.55)"
    backdropFilter: "blur(20px) saturate(180%)"
    border: "1px solid rgba(0,159,227,0.50)"
    boxShadow: "0 8px 32px rgba(0,159,227,0.35), inset 0 1px 0 rgba(255,255,255,0.20)"
    badge: "pill navy 'Le plus populaire' centré en haut"

  # ── NAVIGATION ──
  navbar:
    height: "72px"
    topOffset: "40px"         # hauteur ticker
    background: "rgba(8,20,40,0.75)"
    backdropFilter: "blur(28px) saturate(180%)"
    borderBottom: "1px solid rgba(0,159,227,0.15)"
    scrollEffect: "border-top gradient bleu→orange + box-shadow renforcé"
    logo: "SVG inline Gwensas, height 54px, cliquable scroll-top, glow hover"
    links: "DM Sans 11.5px uppercase letter-spacing 0.10em, underline slide-in hover"

  # ── TICKER ──
  ticker:
    height: "40px"
    background: "#030d18"
    borderBottom: "1px solid rgba(0,159,227,0.10)"
    animation: "marquee 55s linear infinite"
    items: "liens <a> cliquables vers sources externes"
    sparklines: "area chart SVG 40x18px avec dégradé fill semi-transparent"

  # ── MODAL ──
  modal:
    overlay: "rgba(0,0,0,0.70) + backdropFilter blur(12px)"
    container:
      borderRadius: "24px"
      background: "#FFFFFF"
      maxWidth: "760px"
      padding: "36px 44px"
    animation: "scale(0.9)→scale(1) + translateY(24px)→0 + opacity 0→1"

  # ── HERO ──
  hero:
    minHeight: "100vh"
    background: "#06101e"
    canvas: "réseau 28 mineurs animés, hash particles, symboles ₿, block found flash orange"
    overlay: "radial-gradient ellipse 80% bleu centré 7% opacité"
    statsBar: "glass pill rgba(255,255,255,0.04) + blur 16px + border rgba(255,255,255,0.07)"
    scrollIndicator: "ligne animée + 'Découvrir'"

  # ── BADGES / PILLS ──
  badge-live:
    background: "rgba(16,185,129,0.15)"
    border: "1px solid rgba(16,185,129,0.25)"
    borderRadius: "100px"
    dotColor: "#10B981"
    dotAnimation: "pulse 1.5s infinite"

  badge-eyebrow:
    background: "rgba(0,159,227,0.10)"
    border: "1px solid rgba(0,159,227,0.30)"
    borderRadius: "100px"
    backdropFilter: "blur(8px)"

  # ── ICÔNES ──
  icons:
    library: "SVG inline uniquement (Lucide / Heroicons style)"
    rule: "jamais d'emoji comme icône UI"
    size-sm: "13-15px"
    size-md: "16-20px"
    size-lg: "24-28px"
    strokeWidth: "1.5-2px"
    color: "hérite du contexte (currentColor)"
```

---

## Effects & Motion

```yaml
motion:
  ease-spring: "cubic-bezier(0.22, 1, 0.36, 1)"     # Spring overshoot — tous les reveals
  ease-standard: "cubic-bezier(0.4, 0, 0.2, 1)"     # Material standard — transitions UI
  
  reveal-scroll:
    type: "fadeUp"
    from: "opacity:0, translateY:32px"
    to: "opacity:1, translateY:0"
    duration: "0.75s"
    easing: "spring"
    stagger: "0.08s entre enfants"
  
  hover-card:
    type: "spring"
    stiffness: 400
    damping: 25
    lift: "translateY(-6 to -8px)"
  
  button-hover:
    lift: "translateY(-2px)"
    icon-shift: "translateX(4px)"
    duration: "0.2s"
  
  nav-underline:
    transform: "scaleX(0→1)"
    transformOrigin: "left"
    duration: "0.3s"
    easing: "spring"
```

**Glassmorphism** : chaque surface utilise `backdrop-filter: blur(Xpx) saturate(Y%)` + fond semi-transparent + `inset 0 1px 0 rgba(255,255,255,0.N)` pour le highlight de surface. C'est la signature visuelle Gwensas.

---

## Layout Structure

```yaml
layout:
  sections-order:
    - ticker          # 40px fixe, données Bitcoin live
    - navbar          # 72px fixe, glassmorphism dark
    - hero            # 100vh, canvas animé, centré
    - trust           # Logos presse, fond glass clair
    - manifeste       # Mission + 3 valeurs glass cards
    - kpi             # Fond navy, chiffre 0,047€/kWh, grille 4 métriques
    - histoire        # Timeline + quote + paragraphes + 6 project cards
    - how-it-works    # 3 étapes glass + photo ferme
    - virunga         # Split 50/50 dark-left photo-right
    - pricing         # 3 plans glass (standard/pro/industriel)
    - transparency    # Formule calcul versement client
    - faq             # Accordion
    - cta             # Gradient dark, email + WhatsApp
    - footer          # Compact navy

  grid:
    values: "repeat(3, 1fr)"
    projects: "repeat(3, 1fr) — première card wide (span 2)"
    pricing: "repeat(3, 1fr)"
    kpi: "repeat(4, 1fr)"
    how: "repeat(3, 1fr)"
    virunga: "1fr 1fr"
  
  breakpoint-mobile: "900px"
```

---

## Content Tokens

```yaml
content:
  company: "Gwensas SAS"
  siren: "829 251 644"
  address: "14 rue Honoré Tessier, 33000 Bordeaux"
  founded: "2017"
  email: "contact@gwensas.com"
  whatsapp: "https://wa.me/33782688214"
  
  kpi-electricity: "0,047 €/kWh"
  kpi-power: "5+ MW"
  kpi-experience: "7 ans"
  kpi-clients: "100+"
  kpi-fee: "15%"
  kpi-cost-btc: "$25-30k/BTC"
  
  farms:
    - name: "Matebe / Virunga"
      location: "Nord-Kivu, RDC"
      type: "Hydroélectrique"
      containers: 26
      model: "HK3 V6 liquid cooling"
    - name: "Ivingu / Luviro"
      location: "RDC"
      type: "Air-cooled"
    - name: "Inga"
      location: "RDC"
      type: "Secondaire"
  
  pool: "Antpool"
  pool-fee: "~1%"
  efficiency-formula: "hashrate × 17.23 W/TH (moyenne ASIC)"
```

---

## Agent Prompt

Instructions permanentes pour Stitch lors de la génération d'écrans Gwensas :

1. **Glassmorphism obligatoire** sur toutes les cards, panels, nav et overlays. Toujours `backdrop-filter: blur()`.

2. **Boutons pill shape uniquement** (`border-radius: 100px`). Jamais de coins carrés sur les CTAs.

3. **Fond hero toujours sombre** (#06101e ou similaire). Textes blancs sur hero.

4. **Pas d'emoji comme icônes** — utiliser des SVG inline (stroke, pas fill, strokeWidth 1.5-2px).

5. **Bitcoin Orange (#F7931A) réservé** aux éléments explicitement Bitcoin (prix, ₿, accents BTC).

6. **Vert (#10B981) réservé** à l'énergie renouvelable et aux statuts opérationnels positifs.

7. **Bricolage Grotesque** pour TOUS les titres, jamais d'autre police pour les H1/H2/H3.

8. **Sparklines** dans le ticker : area charts SVG avec gradient fill, pas de simples lignes.

9. **Langue** : interface toujours en français. Textes marketing en français.

10. **Ton** : premium et direct. Pas de jargon crypto trop technique. Humaniste et accessible.

---

Sources :
- [Stitch Prompt Guide - Google AI Forum](https://discuss.ai.google.dev/t/stitch-prompt-guide/83844)
- [What Is DESIGN.md - MindWiredAI](https://mindwiredai.com/2026/04/23/design-md-is-now-open-source-googles-new-file-format-that-makes-ai-build-your-brand-correctly/)
- [Stitch Design System Guide - MindStudio](https://www.mindstudio.ai/blog/how-to-use-google-stitch-website-design-system)
