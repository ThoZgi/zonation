# Transect

Outil de terrain pour l'identification des habitats des marais salés de la
**Petite Mer de Gâvres** (BTS GPN — Kerplouz), à partir du référentiel
phytosociologique COLASSE V., 2019 (CBN de Brest).

Un·e élève réalise un relevé floristique à chaque point d'un transect
(abondance-dominance Braun-Blanquet), et l'application propose l'habitat le
plus probable en comparant le relevé au référentiel des 16 groupements
végétaux trouvables sur le site.

## État actuel

- **Front seul, vanilla (sans build)** : `index.html` + `data.js` + `fonts/`.
- **Données en `localStorage`** (hors-ligne, un appareil = ses propres
  transects).
- Export CSV et export JSON compatible avec l'import de
  [Phytoscope](https://github.com/btsgpn-kerplouz/portail/tree/main/apps/phytoscope).

## Développement local

Aucune étape de build : ouvrir `index.html` directement, ou servir le dossier
avec n'importe quel serveur statique.

## Déploiement

En ligne sur **https://zonation.kerplouz.workers.dev**, et intégré au
[portail pédagogique BTS GPN](https://portail-gpn.kerplouz.workers.dev/)
(dans `apps/transect/` du monorepo
[btsgpn-kerplouz/portail](https://github.com/btsgpn-kerplouz/portail)).
Ce dépôt-ci est la copie de travail personnelle ; les changements sont
resynchronisés vers le monorepo par Pull Request au moment de publier.
