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

---
## Itération v2.3 (04/06) — revue supervision : 3 resserrages niveau agence
- P1 — Section 07 Ton de voix réalignée sur la grille 12 col : 3 groupes labellisés (Registres / Caractère / Formulations) avec filets, splits 6/6 et table 3/6/3 (colgroup), espaces base-8. Cohérente avec 01/05/06.
- P2 — Applications en fidélité production : plaquette A4 = vrai spread éditorial (en-tête courant logo+rubrique, eyebrow, titre, corps, citation filet, stats à dividers, folio, légales ORIAS sur la cover, marges 32px base-8). Posts LinkedIn → carousel 3 slides 1080 (accroche dark → preuve « 30 » photo → CTA light), indicateurs 01/03 + « glissez → ».
- P3 — Photo cover affinée : contraste 0.9 + brightness 1.07 (high-key, moins mécanique), cadrage 34%/26% recentré sur les visages, dégradé bas pour profondeur + ancrage légende. Reste 100% N&B.
- Contraintes respectées : Satoshi, #0E0E0E/#FAF8F3, zéro accent couleur, base-8, AAA. Rien d'autre touché.
- Bug outil (pas prod) : script d'isolation masquait `.a4.cover` via sélecteur `.cover` trop large → corrigé en `.cover:not(.a4)`. Le live a toujours été correct.
- Commits incrémentaux (07, cover, applications). Push + Pages built. Live /v2/ vérifié (licar, spread, vgroup, folio, 01/03 présents). DRAFT en attente validation Mendar — tâche NON passée à Fait.
