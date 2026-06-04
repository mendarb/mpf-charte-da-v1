# PROGRESS

- 2026-06-04 — Planning créé. Démarrage passe qualité.
- P1 recherche : en cours.

- 2026-06-04 — Passe qualité terminée : micro-typo FR (apostrophes ’, fines insécables, guillemets, milliers), réf concurrent retirée, palette unifiée (#FAF8F3 + rampe chaude sur 3 docs). Re-render + vérif visuelle OK. Deploy + uploads faits.

---
## Itération v2.1 (04/06) — désornementation + photos humaines + fixes exécution
- Démarrage : inspection assets photo + audit forensique rendu v2.
- v2.1 livrée : grain/flag/filets/captions-blend retirés ; cover 100px Bold (au lieu 150 Black) ; H2 56 Bold ; lead en flux ; construction sans grille de fond ; cover photo = mpf-team-portrait (humain) flaggée placeholder. Re-render + vérif OK. Deploy /v2/ + upload faits.

---
## Itération v2.2 (04/06) — brandbook COMPLET (8 sections)
- Ajout sections 05 Grille (12 col, base 8), 06 Photographie & matière (N&B doux, pierre de Jaumont), 07 Ton de voix (voice chart, on dit/on ne dit pas), 08 Applications (plaquette/LinkedIn/carte/signature).
- Fix : débordement grille 12 col (min-width:0 + overflow:hidden + box-sizing).
- Méthode rendu : capture section-par-section isolée (CSS pur) — la capture pleine page >16384px ne peint pas (limite texture Chrome).
- Vérif visuelle des 8 blocs : OK, niveau premium.
- Déploiement : remote origin re-câblé (github.com/mendarb/mpf-charte-da-v1, historiques sans ancêtre commun → travail par-dessus origin/main pour préserver l'état déployé + .nojekyll). Push OK, Pages built. Live /v2/ sert bien 8 sections.
- Brief shooting photo livré (placeholders N&B à remplacer par vrai shoot).
- Uploads HQ : cover, logo, sections 05-08, brief. Commentaire posté. En attente validation Mendar. Tâche NON passée à Fait.
