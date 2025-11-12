---
title: "Pourquoi j’ai choisi Astro pour mon site"
description: "Retour sur les raisons techniques et personnelles derrière le choix d’Astro comme moteur de mon portfolio"
pubDate: "Sep 14 2025"
heroImage: "/astroThumbnail.webp"
tags: ['astro', 'web', 'framework', 'site perso']
auteur: "Nathan DEJEAN"
---

Lorsqu’il a fallu choisir un framework pour construire mon portfolio, plusieurs options s’offraient à moi : React, Vue, Next.js, Nuxt… J’ai finalement opté pour [Astro](https://astro.build/) — un choix qui s’est imposé assez naturellement après quelques tests.

### Un framework pensé pour les sites de contenu

Astro se distingue par sa **philosophie orientée performance** et “content-first” :

- Le HTML est généré statiquement par défaut
- Aucun JavaScript n’est chargé côté client si ce n’est pas nécessaire
- La structure de contenu en fichiers `.md` s’intègre naturellement à un portfolio ou un blog

> Idéal pour un site vitrine ou personnel, sans dépendances lourdes.

### Une syntaxe simple et claire

Le format `.astro` permet de mélanger HTML, composants et logique de manière très lisible. Il est aussi compatible avec React, Vue, Svelte, etc., si besoin.

#### Exemple :
```astro
---
import Header from '../components/Header.astro';
---

<Header />
<main>
  <h1>Bienvenue sur mon site</h1>
</main>
```

### Un bon compromis entre statique et dynamique

Astro permet de :
- Générer des pages statiques ultra-rapides
- Ajouter des comportements interactifs **au cas par cas**
- Utiliser des composants front (React, etc.) uniquement là où c’est utile

Cette approche modulaire est très adaptée à un site personnel où l’on veut **rester léger**, sans sacrifier les possibilités.

### Une vraie logique de composants

Créer des layouts, des cartes de projet ou des blocs réutilisables est simple et bien structuré. Le système de **layouts + slots** est très clair.

### Environnement moderne

- Intégration facile avec Tailwind CSS
- Support TypeScript natif
- Hot reload ultra rapide

Astro est aussi bien documenté et évolue rapidement.

### Conclusion

J’ai choisi Astro car il combine **performance, simplicité et flexibilité**, tout en me laissant la main sur le design et l’organisation du contenu. C’est un outil adapté à la réalité d’un site de créatif ou d’étudiant — sans surcharger inutilement le code ou l’expérience utilisateur.