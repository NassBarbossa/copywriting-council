# Copywriting Council

Un conseil d'experts légendaires du copywriting qui débattent avant de produire du contenu.

## Concept

Avant de générer un email, une page de vente ou un post, le contenu passe devant le **Conseil des Experts**. Chaque expert apporte sa perspective, ils débattent, puis un consensus émerge.

## Les Experts

| Expert | Spécialité | Style |
|--------|------------|-------|
| 🎩 Ogilvy | Brand, research, élégance | Classique, factuel |
| 🔥 Halbert | Direct response, urgence | Agressif, émotionnel |
| 📖 Sugarman | Storytelling, triggers | Méthodique, slippery slide |
| 🧠 Cialdini | Psychologie, persuasion | Scientifique, principes |
| 📊 Schwartz | Awareness levels, headlines | Stratégique, segmenté |
| 🇫🇷 Selim | Pages de vente FR | Concret, pratique |
| 💼 Thibault | LinkedIn, templates | Data-driven, scalable |

## Usage

```
/council [brief]        → Lance un débat complet
/council-quick [brief]  → Tour de table rapide (pas de débat)
/council-vote [options] → Fait voter les experts
```

## Process

```
0. BRAND     → Charger config/brand.md (automatique)
1. INPUT     → Brief reçu
2. TOUR      → Chaque expert donne son angle (30 sec)
3. DÉBAT     → Confrontation des approches
4. CONSENSUS → Vote ou synthèse
5. OUTPUT    → Contenu produit
6. REVIEW    → Chaque expert : ✅ OK ou ⚠️ FLAG (1 ligne)
7. ITÉRATION → Mini-débat sur les flags uniquement (max 2 tours)
8. VALIDATION → Check final brand + livraison
```

**Règles :**
- Chaque expert DOIT adapter ses recommandations à la brand de Nass (ton, audience, mots interdits)
- Utiliser **model: sonnet** pour tout le process
- Max **2 tours** de review — après, le Modérateur tranche

## Fichiers

```
copywriting-council/
├── AGENTS.md                    # Ce fichier
├── config/
│   └── brand.md                 # Identité, audience, ton, voix, offres
├── council/
│   ├── COUNCIL.md               # Rules et process détaillé
│   ├── experts/                 # Fiches des 7 experts
│   │   ├── ogilvy.md
│   │   ├── halbert.md
│   │   ├── sugarman.md
│   │   ├── cialdini.md
│   │   ├── schwartz.md
│   │   ├── selim.md
│   │   └── thibault.md
│   └── debates/                 # Logs des débats passés
└── output/                      # Contenus produits
```
