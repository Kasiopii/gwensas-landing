# Gwensas — Site Web

Projet : landing page gwensas.com — Bitcoin Mining as a Service  
Stack : HTML/CSS/JS vanilla (fichier unique `index.html`)  
Design system : voir `DESIGN.md`

## Contexte

Site vitrine premium pour Gwensas, société de Bitcoin mining hosting.  
Fermes hydroélectriques au Parc des Virunga, RDC. 0,047 €/kWh. 7 ans d'expérience.

## Règles design ABSOLUES

- **Police** : Inter uniquement (headings + body) — même esthétique que X.com
- **Boutons** : toujours pill shape (`border-radius: 100px`) — jamais carré
- **Glassmorphism** : toutes les cards ont `backdrop-filter: blur()` + `-webkit-backdrop-filter`
- **Fond hero** : toujours sombre (`#06101e`) — textes blancs sur hero
- **Icônes** : SVG inline uniquement — jamais d'emoji
- **Bitcoin orange** (`#F7931A`) : réservé aux éléments BTC uniquement
- **Vert** (`#10B981`) : réservé énergie renouvelable et statuts positifs

## Structure du fichier

`index.html` contient tout : CSS, HTML, JavaScript.  
Sections dans l'ordre : Ticker → Nav → Hero (canvas animé) → Trust → Manifeste → KPI → Histoire → Projects → How → Virunga → Pricing → Transparence → FAQ → CTA → Footer

## Déploiement

```bash
# Dev local
npm run dev  # http://localhost:3000

# Deploy Vercel
vercel --prod
```

## Points d'attention

- Le canvas hero est une animation mining network (28 nœuds, hash particles, ₿ symbols)
- Le ticker est cliquable — chaque item a un lien vers sa source de données
- Nav change de couleur au scroll : dark glass → blanc (`.nav-mid a` devient `var(--mid)`)
- `prefers-reduced-motion` : canvas masqué, animations désactivées
- Tout modifier dans `index.html` — pas de build step

## Skill routing

- Design review → `/design-review`
- Design system → `/design-consultation`
- Déploiement → `/deploy` ou `vercel --prod`
- QA → `/qa`
