---
validated: true
level: 1
---

## Favoriser les pages statiques

La génération des sites de façon dynamique (via CMS, en PHP…) consomme plus de ressource qu’une simple page statique.

Il est nécessaire de favoriser les pages statiques dans la mesure du possible. Par exemple dans le cas d’une page dont le contenu ne change pas (présentation d’une société par exemple), on pourra utiliser une page statique.

Si l’on souhaite conserver un CMS, on peut utiliser des plugins qui générent le contenu de façon statique.

Pour les sites à fort traffic et à contenu dynamique, on favorise l’utilisation de proxy web, qui génèrent des pages statiques.

Solutions techniques utilisables :

1. systèmes de cache (plugins qui génèrent le contenu de façon statique) :
- Boost pour Drupal
- W3 Total Cache pour WordPress
- ...

2. systèmes de reverse proxy :
- Varnish
- ...

Il faut adapter les constats au niveau de mise à jour des contenus et à la fréquentation du site.
