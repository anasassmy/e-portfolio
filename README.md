# Portfolio — BUT R&T Cybersécurité

Portfolio étudiant BUT Réseaux & Télécommunications, parcours Cybersécurité.

## Structure

```
portfolio/
├── index.html          ← Accueil (hero, aperçu UE, SAÉ, skills)
├── competences.html    ← Toutes les UE et CE (1A + 2A avec onglets)
├── projets.html        ← Toutes les SAÉ détaillées (1A + 2A)
├── apropos.html        ← Présentation, timeline, centres d'intérêt
├── contact.html        ← Formulaire de contact + liens
└── style.css           ← CSS UNIQUE pour toutes les pages
```

## Déploiement GitHub Pages

1. Créer un repo GitHub `portfolio` (ou `votre-username.github.io`)
2. Uploader tous les fichiers à la racine du repo
3. Aller dans **Settings → Pages**
4. Source : `Deploy from a branch` → `main` → `/ (root)`
5. Ton portfolio sera disponible à : `https://votre-username.github.io/portfolio`

## Personnalisation rapide

Remplace dans tous les fichiers :
- `[Votre ville]` → ta ville
- `[Votre IUT]` → le nom de ton IUT
- `votre.email@example.com` → ton email
- `votre-profil` / `votre-github` → tes vrais liens

## Design

Inspiré du style de [Sun Metalon](https://sunmetalon.com) :
- Fond brun-noir industriel (`#0f0e0b`)
- Accents orange cuivré (`#d96833`)  
- Typographie : Syne (titres) + Space Grotesk (corps) + JetBrains Mono (code)
- Animations CSS au scroll, grille vectorielle, texture noise
