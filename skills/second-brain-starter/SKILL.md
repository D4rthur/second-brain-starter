---
name: second-brain-starter
description: Monte un second cerveau personnel dans un vault Obsidian local. Utilise ce skill quand l'utilisateur veut créer, démarrer ou structurer un second cerveau, une base de connaissances personnelle, un système de notes, un vault Obsidian, ou organiser ses idées et décisions. Lance un intake, scaffold la structure du vault, et guide l'installation d'Obsidian.
---

# Second Brain Starter

Monte un second cerveau personnel : un vault Obsidian local qui externalise la charge mentale, relie les idées, et fait remonter la bonne information au bon moment.

Ce skill fait 4 choses, dans l'ordre :
1. **Intake** — comprendre qui est la personne et comment elle travaille.
2. **Scaffold** — créer le squelette du vault (dossiers + templates + fichier assistant).
3. **Checklist** — donner les étapes manuelles à faire en parallèle (Obsidian, dossier, documents).
4. **Complétion** — enrichir le second cerveau avec quelques questions ciblées.

## Principe à garder en tête

Un second cerveau ne sert pas à stocker. Il sert à **mieux penser**. Trois fonctions :
- Externaliser la charge cognitive — l'esprit sert à avoir des idées, pas à les retenir.
- Créer des connexions que le cerveau seul ne verrait pas.
- Faire remonter la bonne info au bon moment, sans forcer la recherche.

La structure de base suffit. Ne pas sur-organiser — c'est le piège numéro un.

---

## Étape 1 — Intake

Pose les questions de `reference/intake-questions.md`, **une à la fois**. Attends la réponse avant de passer à la suivante. Garde le ton direct et chaleureux, zéro jargon.

Quand tu as les réponses, résume en 3-4 lignes ce que tu as compris avant de scaffolder. Si une réponse manque ou est floue, demande — ne suppose jamais.

## Étape 2 — Scaffold du vault

Demande à la personne **où** créer le vault (chemin d'un dossier sur sa machine, ex. `~/Documents/Mon-Cerveau`). Si elle n'a pas encore créé le dossier, dis-lui de le faire (ou crée-le si tu as accès au système de fichiers).

Crée ensuite cette structure dans le dossier choisi. La structure suit **PARA** (organisation par actionnabilité) et **LYT** (navigation par cartes de contenu) :

```
{NomVault}/
├── index.md                       ← la carte du vault
├── ai-assistant-instructions.md   ← instructions pour ton assistant IA
├── 00-About-Me/
│   └── about-me.md
├── 01-Projects/                   ← efforts actifs avec une fin (PARA — Projects)
│   └── _exemple-projet.md
├── 02-Areas/                      ← responsabilités continues (PARA — Areas)
│   └── _exemple-domaine.md
├── 03-Resources/                  ← références par sujet (PARA — Resources)
├── 04-Archive/                    ← inactif (PARA — Archive)
├── Daily-Notes/
├── MOCs/                          ← Maps of Content : tes hubs de navigation
│   └── _exemple-moc.md
├── Decisions/
│   └── decision-log.md
└── _templates/
    ├── project.md
    ├── area.md
    ├── moc.md
    └── daily.md
```

Remplis chaque fichier à partir des modèles dans `templates/` de ce skill, en injectant les réponses de l'intake :
- `index.md` ← `templates/index.md` (carte personnalisée du vault)
- `ai-assistant-instructions.md` ← `templates/ai-assistant-instructions.md` (rôle, ton, séquence de démarrage de l'assistant — calibrés sur la personne)
- `00-About-Me/about-me.md` ← `templates/about-me.md` (qui elle est, comment elle décide)
- `01-Projects/_exemple-projet.md` ← `templates/project.md`
- `02-Areas/_exemple-domaine.md` ← `templates/area.md` (un par grand domaine cité à l'intake)
- `MOCs/_exemple-moc.md` ← `templates/moc.md`
- `Decisions/decision-log.md` ← `templates/decision-log.md`
- `Daily-Notes/` ← laisser vide (la première note se crée au premier usage)
- `_templates/*` ← copier les modèles bruts `project.md`, `area.md`, `moc.md`, `daily.md`

Remplace `{NomVault}`, `{Nom}`, `{Rôle}`, `{Secteur}`, `{Langue}` et les autres champs par les vraies valeurs de l'intake. Les fichiers `_exemple-*` servent de démonstration vivante — pré-remplis-les avec le contexte réel de la personne quand c'est possible.

Si tu n'as **pas** accès au système de fichiers (ex. Claude.ai web), génère chaque fichier en bloc de code et dis à la personne de les créer manuellement dans Obsidian. Mais le chemin recommandé reste Claude Code ou Claude Desktop avec accès au dossier.

## Étape 3 — Checklist client (en parallèle)

Affiche la checklist de `reference/client-checklist.md`. Ce sont les gestes manuels que la personne fait de son côté pendant/après le scaffold : installer Obsidian, ouvrir le dossier comme vault, classer ses documents existants, connecter son assistant IA au dossier.

## Étape 4 — Complétion

Une fois le squelette en place, pose les questions de `reference/completion-questions.md` pour densifier le cerveau : premiers projets, premières décisions à logger, premières ressources à classer. Crée les notes correspondantes au fil des réponses.

Termine en montrant à la personne **comment utiliser son cerveau au quotidien** : ouvrir une daily note, capturer une idée en un geste, demander à son assistant IA de relier ou retrouver quelque chose.

---

## Règles

- Langue : suis la langue de travail donnée à l'intake. Par défaut, français.
- Voix : directe, concrète, langage simple, orientée bénéfice. Pas de remplissage, pas de jargon.
- Ne suppose jamais une information. Si elle manque, demande.
- Reste simple. Un second cerveau qui démarre petit et vivant bat un système parfait jamais utilisé.
