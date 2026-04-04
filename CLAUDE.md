# CLAUDE.md

## Instruction obligatoire

Ce projet est le **Conseil des Experts Copywriting** — un système de débat entre 6 experts légendaires du copywriting qui confrontent leurs approches avant de produire du contenu pour la marque **Nass Riviera**.

Le skill principal est `/council` — il lance le débat complet des 6 experts.

## Les 6 Experts

| Expert | Spécialité | Fiche |
|--------|------------|-------|
| 📊 Schwartz | Awareness levels, headlines, sophistication marché | `council/experts/schwartz.md` |
| 🎩 Ogilvy | Research, Big Idea, brand image, classiques pub | `council/experts/ogilvy.md` |
| 🔥 Halbert | Direct response, hooks, urgence, AIDA, 29 triggers | `council/experts/halbert.md` |
| 📖 Sugarman | Slippery slide, 31 triggers psychologiques, flow | `council/experts/sugarman.md` |
| 🧠 Cialdini | 7 principes persuasion, SUCCES, psychologie client | `council/experts/cialdini.md` |
| 🇫🇷 Selim | Adaptation FR, pages de vente, email marketing | `council/experts/selim.md` |

> **Note :** Thibault a été supprimé. Ne pas le référencer.

## Fichiers à lire au démarrage

1. `config/brand.md` — Identité, audience, ton, voix de Nass
2. `council/COUNCIL.md` — Process détaillé du débat (8 phases)
3. Les fiches experts dans `council/experts/` (6 fichiers)

## Feedback Loop (CRITIQUE)

Avant chaque session `/council`, lire le fichier feedback :
`/Users/punk6995/.claude/projects/-Users-punk6995/memory/feedback_council_session.md`

Ce fichier contient les **erreurs passées et leçons apprises**. Les règles clés :

- **"Change juste X" = change JUSTE X.** Ne pas reconstruire tout le post. Respecter la structure gagnante.
- **WebSearch d'abord, écrire ensuite.** Ne JAMAIS inventer un fait, un nom, une entreprise. Vérifier avant.
- **Structure gagnante = sacrosaint.** Les ajouts doivent s'y intégrer sans la casser.
- **L'utilisateur connaît mieux son produit que toi.** Son instinct prime sur tes "améliorations".

## Règles

- Toujours charger `config/brand.md` avant de produire du contenu
- Respecter les mots interdits et le ton de la brand (casual, pote au café)
- Pas de hashtags, jamais
- Max 2 tours d'itération en review
- Chaque fait/nom/événement cité doit être vérifié par WebSearch
- Log obligatoire de chaque débat dans `debates/`
