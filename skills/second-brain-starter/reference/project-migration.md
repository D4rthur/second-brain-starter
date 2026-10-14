# Rapatrier tes anciens projets dans ton cerveau

Tu as des projets dans Claude, Cowork ou ChatGPT ? Chacun garde ses instructions et ses fichiers dans son coin. Ici, on les rapatrie dans ton cerveau, un à la fois. Ensuite, plus besoin de choisir un projet avant de poser une question : ton assistant sait où chercher.

Compte environ 5 minutes par projet. Rien n'est supprimé de l'ancien projet.

## 1. Dans l'ancien projet

Ouvre une **nouvelle conversation à l'intérieur du projet** et colle :

```text
Je migre ce projet vers mon second cerveau (un dossier de notes). Produis une FICHE D'EXPORT en Markdown, dans un seul bloc que je pourrai copier.
- Recopie MOT POUR MOT les instructions du projet. Si tu n'y as pas accès, écris « INSTRUCTIONS NON ACCESSIBLES ».
- Liste les fichiers du projet (nom — sujet en une ligne).
- N'invente rien : ce que tu ne sais pas s'écrit « inconnu ».
- Aucun mot de passe, clé ou jeton : écris seulement « secret présent — à retirer ».

# FICHE D'EXPORT — [nom du projet]
## Instructions du projet (copie intégrale)
## Objectif du projet (3 lignes)
## Règles de travail et style
## Fichiers du projet
## Personnes et organisations mentionnées
## Décisions déjà prises
## Travail en cours et prochaines étapes
## Faits à retenir
## À confirmer
```

Copie la fiche. Vérifie dans les **paramètres du projet** que les instructions recopiées sont bien les vraies; sinon, copie-les toi-même.

## 2. Dans ton cerveau

Ouvre ton assistant **dans ton dossier de cerveau** et colle :

```text
Range cette fiche d'export dans mon cerveau, sans écraser aucune note existante.
- Projet actif → une note dans 01-Projects/ (modèle _templates/project.md).
- Projet terminé ou de référence → 04-Archive/.
- Règles utiles partout → propose-les-moi pour ai-assistant-instructions.md; n'ajoute rien sans mon accord.
- Décisions → Decisions/decision-log.md, avec « repris de l'ancien projet [nom] ».
- Ce qui est « à confirmer » le reste.
Mets à jour index.md, puis dis-moi quels fichiers tu as créés ou modifiés.

[colle ici la fiche]
```

## 3. Vérifier

Nouvelle conversation dans ton cerveau, sans redonner le contexte : « Que sais-tu du projet [nom] ? » S'il répond juste, la migration est réussie. Tu peux arrêter d'utiliser l'ancien projet — garde-le quelques semaines avant de le supprimer.

---

> Envie qu'on le fasse avec toi, pour tous tes projets d'un coup, avec une mémoire qui se tient à jour toute seule ? C'est ce que fait l'accompagnement Arkytechs : [arkytechs.com](https://arkytechs.com).
