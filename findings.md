# FINDINGS — audit forensique charte MP Finance

## P1 · Recherche (à compléter)
_(règles micro-typo FR + best practices brand guidelines + Satoshi)_

## P1 · Recherche (synthèse)
Règles micro-typo FR (sources OQLF, blogdumoderateur, correctissima) :
- Apostrophe typographique courbe ’ (U+2019), jamais droite '.
- Espace fine insécable (U+202F) avant ; ! ? et à l'intérieur des guillemets « … ».
- Deux-points : espace insécable (PAO moderne = fine insécable acceptée).
- Séparateur de milliers = espace insécable (15 004 729 ; 2 480).

## P2 · Coquilles détectées + statut

### A. Micro-typographie FR
- [x] Apostrophes DROITES partout (hero « L'épure », corps, etc.) → converties en ’ (U+2019).
- [x] Guillemets « » sans espace fine intérieure → fine insécable ajoutée.
- [x] Aucune espace avant : ; ! ? → fine insécable ajoutée.
- [x] Séparateurs de milliers (ORIAS 15 004 729 ; 2 480 abonnés) → fines insécables.

### B. Contenu / cohérence (graves pour une charte)
- [x] Référence concurrent « milimalis.com » citée dans le meta strip de la charte client → remplacée par « Posture / Minimalisme ».
- [x] PALETTE INCOHÉRENTE entre livrables : brand-board affichait papier #F7F5EF, specs documente #FAF8F3 (valeur mandatée). Rampes de gris différentes (brand-board chaud 2A2A28… vs specs/app neutre 262626/CFCFCF…). → Unification sur rampe chaude canonique + papier #FAF8F3 sur les 3 docs.

### C. Design / composition
- [x] Hiérarchie Satoshi calibrée (Black 900 display, tracking −5%).
- [ ] Vérif finale visuelle post-rerender (alignements, veuves).

---
## P2 · Audit v2.1 (retour Mendar : fioritures / photos stock / coquilles / taste)

### Photos (assets)
- STOCK à bannir : mpf-seminar (groupe de dos = cliché), photo-facade, photo-interior-light, photo-metz-arch, photo-stairwell.
- HUMAIN OK : mpf-team-portrait (2 conseillères), mpf-desk (mains/signature), mpf-interior, mpf-team.
- Action : cover = humain rapproché (portrait), traitement N&B doux homogène. Flag : shoot réel MP Finance à prévoir pour le définitif.

### Fioritures à retirer (taste: désornementer)
- [ ] Grain global (body::after).
- [ ] Draft-flag fixe coin haut-gauche.
- [ ] Filets décoratifs d'eyebrow (.ln) répétés partout.
- [ ] Captions en mix-blend-difference (illisibles) cover/photo.
- [ ] Grille dense en fond du panneau construction (surcharge).

### Coquilles d'exécution
- [ ] Cover .lead en position:absolute → risque de chevauchement / sort de la grille.
- [ ] Typo qui « crie » : cover 150px Black, H2 84px Black → calmer (Bold, ~104 / ~54px) per high-end « no oversized H1 ».
- [ ] Paddings à réaligner sur base-8 cohérente.
