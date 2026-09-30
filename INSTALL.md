# Guide d'installation — pas à pas

> Pour tout le monde, même si tu n'as jamais touché à du code. Compte **30 à 45 minutes**, installation et première session incluses.
> Fonctionne sur **Mac** et **Windows**.

## Ce que tu vas installer (et pourquoi)

| Outil | À quoi il sert | Prix |
|---|---|---|
| **Obsidian** | L'app qui affiche ton cerveau : tes notes, reliées entre elles, comme un classeur intelligent. | Gratuit |
| **Claude** (l'app de bureau) | Ton assistant IA. C'est lui qui construit ton cerveau et qui t'aide ensuite à le remplir. | Abonnement **Pro** (environ 20 $/mois) — le plan gratuit ne suffit pas |
| **Second Brain Starter** | Le module qui apprend à Claude comment monter ton cerveau. | Gratuit |

**Où vivent tes notes ?** Dans un simple dossier sur ton ordinateur. Pas de compte Obsidian, pas de cloud. Quand tu demandes quelque chose à Claude, il lit les notes nécessaires pour te répondre — comme n'importe quel échange avec Claude.

---

## Étape 1 — Installer Obsidian (5 min)

1. Va sur **https://obsidian.md** → bouton **Download**.
2. Installe-le comme n'importe quelle app, puis ouvre-le une fois pour vérifier qu'il démarre.
3. Pas besoin de créer de compte. Tu peux le refermer.

## Étape 2 — Prendre l'abonnement Claude Pro (5 min)

1. Va sur **https://claude.ai** et crée un compte (ou connecte-toi).
2. Passe au plan **Pro** (menu de ton profil → *Upgrade* / *Mettre à niveau*).

> Déjà abonné Pro, Max ou Team ? Passe directement à l'étape 3.

## Étape 3 — Installer l'app Claude sur ton ordinateur (5 min)

1. Va sur **https://claude.ai/download** et télécharge la version **Mac** ou **Windows**.
2. Installe-la, ouvre-la, connecte-toi avec ton compte de l'étape 2.

## Étape 4 — Créer le dossier de ton cerveau (1 min)

Crée un dossier vide, là où tu ranges tes documents. Par exemple :

- Mac : `Documents/Mon-Cerveau`
- Windows : `Documents\Mon-Cerveau`

C'est **ce dossier** qui va contenir ton cerveau. Retiens où il est.

## Étape 5 — Ouvrir Claude dans ce dossier (2 min)

1. Dans l'app Claude, clique sur l'onglet **Code** (en haut).
2. Choisis ton dossier `Mon-Cerveau` comme dossier de travail (bouton de sélection de dossier).
3. Tu arrives devant une zone où écrire à Claude.

> Pourquoi l'onglet **Code** ? C'est le mode où Claude a le droit de créer des fichiers dans ton dossier. Aucun code à écrire — tu lui parles en français, normalement.

## Étape 6 — Installer le Second Brain Starter (2 min)

Dans cette zone de texte, copie-colle cette ligne puis appuie sur **Entrée** :

```
/plugin marketplace add D4rthur/second-brain-starter
```

Puis celle-ci, et **Entrée** :

```
/plugin install second-brain-starter@arkytechs
```

Si Claude te demande une confirmation, accepte. Si on te propose de redémarrer la session, fais-le.

## Étape 7 — Monter ton cerveau (15-20 min)

Écris simplement :

> **Monte mon second cerveau**

Claude va te poser **9 questions**, une à la fois (ton nom, ton métier, tes domaines, tes projets…). Réponds naturellement, comme à quelqu'un qui t'aide. Il construit ensuite ton cerveau dans le dossier, puis te pose quelques questions de plus pour le remplir.

> Claude te demandera parfois la permission de créer des fichiers : accepte, c'est normal — c'est ton cerveau qui se construit.

## Étape 8 — Ouvrir ton cerveau dans Obsidian (5 min)

1. Ouvre Obsidian → **Ouvrir un dossier comme coffre** (*Open folder as vault*) → choisis `Mon-Cerveau`.
2. Tu vois tes dossiers à gauche : Projects, Areas, Resources, etc.
3. Active les modèles (une seule fois) :
   - **Paramètres** (roue dentée en bas à gauche) → **Modules principaux** (*Core plugins*).
   - Active **Modèles** (*Templates*) → dossier des modèles : `_templates`.
   - Active **Notes quotidiennes** (*Daily notes*) → dossier : `Daily-Notes` · modèle : `_templates/daily`.

## Étape 9 — Vérifier que tout est branché (1 min)

1. Ferme l'app Claude, rouvre-la, onglet **Code**, dossier `Mon-Cerveau`.
2. Demande : **« Résume ce que tu sais sur moi et mon cerveau. »**
3. S'il te parle de ton rôle, de tes domaines et de tes projets → **c'est gagné.**

---

## Au quotidien

- **Capturer** : dis à Claude « note que… » ou « ajoute à ma note du jour… ». Il range au bon endroit.
- **Retrouver** : « Qu'est-ce que j'avais décidé pour… ? » — il cherche dans ton cerveau.
- **Relire, réfléchir** : ouvre Obsidian, navigue dans tes notes.

**Règle d'or** : ouvre toujours Claude **dans le dossier de ton cerveau** (onglet Code → `Mon-Cerveau`). C'est comme ça qu'il se souvient de toi.

## Mettre à jour le module

Dans l'onglet Code, tape `/plugin`, va dans **Installed**, choisis *second-brain-starter* → **Update now**.

---

## Problème ?

| Ce que tu vois | Quoi faire |
|---|---|
| Pas d'onglet **Code** dans l'app Claude | Vérifie que tu es bien sur un abonnement **Pro** (ou plus) et que l'app est à jour. |
| `/plugin` ne répond pas / commande inconnue | Tu es dans l'onglet **Chat** au lieu de **Code**. Change d'onglet. |
| « Monte mon second cerveau » ne déclenche rien | Tape plutôt `/second-brain-starter:second-brain-starter`. |
| Claude ne se souvient plus de toi le lendemain | Tu n'as pas ouvert Claude dans le bon dossier. Onglet Code → choisis `Mon-Cerveau`. Vérifie aussi que le fichier `CLAUDE.md` est à la racine du dossier. |
| Les notes du jour affichent `{{date}}` | Les modèles ne sont pas activés dans Obsidian → refais l'étape 8, point 3. |
| Tu es bloqué | Écris-nous sur [arkytechs.com](https://arkytechs.com). |

---

## Pour les initiés — terminal

Tu préfères la ligne de commande ? Installe Claude Code directement :

- **Mac / Linux** : `curl -fsSL https://claude.ai/install.sh | bash`
- **Windows (PowerShell)** : `irm https://claude.ai/install.ps1 | iex`

Puis, dans ton dossier de vault : `claude`, et les deux commandes `/plugin` de l'étape 6. Mise à jour : `/plugin marketplace update arkytechs`. Documentation officielle : https://code.claude.com/docs/en/installation

---

*Second Brain Starter — offert par [Arkytechs](https://arkytechs.com).*
