# 🏛️ Copywriting Council

Un conseil de 7 experts légendaires du copywriting qui débattent avant de produire du contenu.

## Concept

Avant de générer un email, une page de vente ou un post, le contenu passe devant le **Conseil des Experts**. Chaque expert apporte sa perspective unique, ils débattent, et un consensus émerge.

## Les Experts

| Emoji | Expert | Spécialité |
|-------|--------|------------|
| 🎩 | **David Ogilvy** | Brand, research, élégance |
| 🔥 | **Gary Halbert** | Direct response, urgence, émotion |
| 📖 | **Joe Sugarman** | Storytelling, triggers, slippery slide |
| 🧠 | **Robert Cialdini** | 7 principes de persuasion |
| 📊 | **Eugene Schwartz** | Awareness levels, headlines |
| 🇫🇷 | **Sélim Niederhoffer** | Pages de vente FR, Super Structure |
| 💼 | **Thibault Louis** | LinkedIn, templates, data-driven |

## Usage

```bash
# Dans Claude Code ou votre agent
/council [brief]        # Débat complet
/council-quick [brief]  # Tour de table rapide
```

## Process

```
┌─────────────────────────────────────────────────┐
│  1. BRIEF                                       │
│     Objectif, audience, contraintes             │
├─────────────────────────────────────────────────┤
│  2. TOUR DE TABLE                               │
│     Chaque expert donne son angle (30 sec)      │
├─────────────────────────────────────────────────┤
│  3. DÉBAT                                       │
│     Confrontation des approches                 │
│     Points de désaccord → Résolution            │
├─────────────────────────────────────────────────┤
│  4. CONSENSUS                                   │
│     Synthèse ou vote majoritaire                │
├─────────────────────────────────────────────────┤
│  5. OUTPUT                                      │
│     Contenu final + justification               │
└─────────────────────────────────────────────────┘
```

## Exemple de Débat

```
## Sujet: Email de lancement formation VibeCoding

### 📊 Schwartz
"Audience = Problem Aware. Ils savent qu'ils ne savent pas coder.
Headline: Agiter le problème, pas vendre direct."

### 🎩 Ogilvy
"Research: 80% de la cible a déjà essayé d'apprendre. 
Big Idea: 'Le code est mort' = pattern interrupt fort."

### 🔥 Halbert
"URGENCE! Places limitées, deadline réelle.
Hook: 'Ce matin j'ai fait 1343$ sans écrire une ligne de code.'"

### 📖 Sugarman
"Slippery slide: L'email doit couler. Pas de friction.
Chaque phrase pousse à la suivante."

### 🧠 Cialdini
"Preuve sociale dès le début. Rareté à la fin.
'Rejoins les 500+ VibeCodrs' + '37 places restantes'"

### 🇫🇷 Selim
"Confession: 'J'ai galéré 2 ans à apprendre Python. Puis j'ai découvert...'
Chiffres précis: 1343€, pas '1000€+'"

### 💼 Thibault
"Format email OK mais penser au relai LinkedIn.
CTA unique, pas 3 liens différents."

### ✅ CONSENSUS
- Hook: Résultat chiffré (Halbert) + Pattern interrupt (Ogilvy)
- Body: Slippery slide (Sugarman) + Confession (Selim)
- Preuves: Social proof early (Cialdini)
- Close: Urgence authentique (Halbert) + CTA unique (Thibault)
```

## Structure

```
copywriting-council/
├── README.md
├── AGENTS.md
├── council/
│   ├── COUNCIL.md           # Process détaillé
│   └── experts/
│       ├── ogilvy.md
│       ├── halbert.md
│       ├── sugarman.md
│       ├── cialdini.md
│       ├── schwartz.md
│       ├── selim.md
│       └── thibault.md
├── debates/                  # Logs des débats
└── output/                   # Contenus produits
```

## Installation

```bash
# Clone dans ton workspace
git clone https://github.com/NassBarbossa/copywriting-council.git

# Ou copie le dossier
cp -r copywriting-council ~/.claude/skills/
```

## Auteur

Créé par **Nass Riviera** (@NassRiviera)
