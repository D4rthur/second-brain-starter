# Guide d'installation — pas à pas

> Pour tout le monde, même si tu n'as jamais touché à du code. Compte **30 à 45 minutes**, installation et première session incluses.
> Fonctionne sur **Mac** et **Windows**, avec **Claude** ou avec **ChatGPT**.

## Ce que tu vas installer (et pourquoi)

| Outil | À quoi il sert | Prix |
|---|---|---|
| **Obsidian** | L'app qui affiche ton cerveau : tes notes, reliées entre elles, comme un classeur intelligent. | Gratuit |
| **Ton assistant IA** — Claude *ou* ChatGPT, au choix | C'est lui qui construit ton cerveau et qui t'aide ensuite à le remplir. | Voir le tableau ci-dessous |
| **Second Brain Starter** | Le module qui apprend à ton assistant comment monter ton cerveau. | Gratuit |

### Claude ou ChatGPT ?

Prends celui que tu utilises déjà. Les deux donnent le même cerveau, et tu pourras changer d'assistant plus tard sans rien refaire.

| | **Claude** | **ChatGPT** |
|---|---|---|
| App à installer | App **Claude** (onglet **Code**) | App **ChatGPT** de bureau (anciennement « Codex ») |
| Abonnement | **Pro** minimum (environ 20 $/mois) — le plan gratuit ne suffit pas | Fonctionne dès le plan gratuit, mais avec des limites d'usage vite atteintes · **Plus** recommandé |
| Suis | [Parcours A](#parcours-a--avec-claude) | [Parcours B](#parcours-b--avec-chatgpt) |

> **Important :** il faut l'**app de bureau** installée sur ton ordinateur. Le site web (claude.ai ou chatgpt.com dans le navigateur) ne peut pas créer de fichiers sur ton ordinateur.

**Où vivent tes notes ?** Dans un simple dossier sur ton ordinateur. Pas de compte Obsidian, pas de cloud. Quand tu poses une question à ton assistant, il lit les notes nécessaires pour te répondre — comme n'importe quel échange avec lui.

---

## Étapes communes

### Étape 1 — Installer Obsidian (5 min)

1. Va sur **https://obsidian.md** → bouton **Download**.
2. Installe-le comme n'importe quelle app, puis ouvre-le une fois pour vérifier qu'il démarre.
3. Pas besoin de créer de compte. Tu peux le refermer.

### Étape 2 — Créer le dossier de ton cerveau (1 min)

Crée un dossier vide, là où tu ranges tes documents. Par exemple :

- Mac : `Documents/Mon-Cerveau`
- Windows : `Documents\Mon-Cerveau`

C'est **ce dossier** qui va contenir ton cerveau. Retiens où il est.

Ensuite, suis **un seul** des deux parcours.

---

## Parcours A — avec Claude

### A1. Prendre l'abonnement Claude Pro (5 min)

1. Va sur **https://claude.ai** et crée un compte (ou connecte-toi).
2. Passe au plan **Pro** (menu de ton profil → *Upgrade* / *Mettre à niveau*).

> Déjà abonné Pro, Max ou Team ? Passe directement à A2.

### A2. Installer l'app Claude (5 min)

1. Va sur **https://claude.ai/download** et télécharge la version **Mac** ou **Windows**.
2. Installe-la, ouvre-la, connecte-toi.

### A3. Ouvrir Claude dans ton dossier (2 min)

1. Dans l'app Claude, clique sur l'onglet **Code** (en haut).
2. Choisis ton dossier `Mon-Cerveau` comme dossier de travail.

> Pourquoi l'onglet **Code** ? C'est le mode où Claude a le droit de créer des fichiers dans ton dossier. Aucun code à écrire — tu lui parles en français, normalement.

### A4. Installer le Second Brain Starter (2 min)

Dans la zone de texte, copie-colle cette ligne puis appuie sur **Entrée** :

```
/plugin marketplace add D4rthur/second-brain-starter
```

Puis celle-ci, et **Entrée** :

```
/plugin install second-brain-starter@arkytechs
```

Si Claude demande une confirmation, accepte. S'il propose de redémarrer la session, fais-le.

### A5. Monter ton cerveau (15-20 min)

Écris simplement : **« Monte mon second cerveau »**

→ Passe ensuite à l'[étape finale](#étape-finale--ouvrir-ton-cerveau-dans-obsidian-5-min).

---

## Parcours B — avec ChatGPT

### B1. Installer l'app ChatGPT de bureau (5 min)

1. Va sur **https://learn.chatgpt.com/docs/app** et télécharge l'app pour **Mac** ou **Windows**.
2. Installe-la, ouvre-la, connecte-toi avec ton compte ChatGPT.

> C'est l'app qui s'appelait avant « Codex ». Sur Mac, le fichier téléchargé peut encore s'appeler `Codex.dmg` — c'est normal.

### B2. Télécharger le Second Brain Starter (2 min)

1. Va sur **https://github.com/D4rthur/second-brain-starter**.
2. Clique le bouton vert **Code** → **Download ZIP**.
3. Décompresse le fichier (double-clic sur Mac · clic droit → *Extraire tout* sur Windows).
4. Tu obtiens un dossier `second-brain-starter-main`. Laisse-le dans *Téléchargements*, ou range-le où tu veux — **mais pas dans `Mon-Cerveau`**.

### B3. Ouvrir ChatGPT dans ce dossier (2 min)

1. Dans l'app ChatGPT, choisis **Ouvrir un dossier** (*Open folder*).
2. Sélectionne le dossier `second-brain-starter-main` que tu viens de décompresser.

> Pourquoi ce dossier-là ? Il contient le mode d'emploi (le fichier `AGENTS.md`) que ChatGPT lit tout seul pour savoir comment monter ton cerveau.

### B4. Monter ton cerveau (15-20 min)

Écris : **« Monte mon second cerveau dans Documents/Mon-Cerveau »** (adapte le chemin si ton dossier est ailleurs).

ChatGPT va te demander la permission d'écrire dans `Mon-Cerveau`, puisque ce dossier est en dehors de celui que tu as ouvert : **accepte**. C'est la seule autorisation spéciale dont il a besoin.

> **Sécurité :** garde le mode **« Demander l'approbation »** (*Ask for approval*), celui par défaut. N'active jamais « Accès complet » (*Full access*). Accepte seulement les demandes que tu comprends.

→ Passe ensuite à l'étape finale.

---

## Pendant la construction (les deux parcours)

Ton assistant va te poser **9 questions**, une à la fois : ton nom, ton métier, tes domaines, tes projets… Réponds naturellement, comme à quelqu'un qui t'aide. Il construit ensuite ton cerveau dans `Mon-Cerveau`, puis te pose quelques questions de plus pour le remplir.

Il te demandera parfois la permission de créer des fichiers : accepte, c'est ton cerveau qui se construit.

## Étape finale — Ouvrir ton cerveau dans Obsidian (5 min)

1. Ouvre Obsidian → **Ouvrir un dossier comme coffre** (*Open folder as vault*) → choisis `Mon-Cerveau`.
2. Tu vois tes dossiers à gauche : Projects, Areas, Resources, etc.
3. Active les modèles (une seule fois) :
   - **Paramètres** (roue dentée en bas à gauche) → **Modules principaux** (*Core plugins*).
   - Active **Modèles** (*Templates*) → dossier des modèles : `_templates`.
   - Active **Notes quotidiennes** (*Daily notes*) → dossier : `Daily-Notes` · modèle : `_templates/daily`.

## Vérifier que tout est branché (1 min)

1. Ferme ton assistant, rouvre-le **directement dans le dossier `Mon-Cerveau`** :
   - Claude : onglet **Code** → dossier `Mon-Cerveau`.
   - ChatGPT : **Ouvrir un dossier** → `Mon-Cerveau` (plus le dossier du starter).
2. Demande : **« Résume ce que tu sais sur moi et mon cerveau. »**
3. S'il te parle de ton rôle, de tes domaines et de tes projets → **c'est gagné.**

Le dossier `second-brain-starter-main` (parcours B) ne sert plus : tu peux le supprimer.

---

## Au quotidien

- **Capturer** : dis à ton assistant « note que… » ou « ajoute à ma note du jour… ». Il range au bon endroit.
- **Retrouver** : « Qu'est-ce que j'avais décidé pour… ? » — il cherche dans ton cerveau.
- **Relire, réfléchir** : ouvre Obsidian, navigue dans tes notes.

**Règle d'or** : ouvre toujours ton assistant **dans le dossier `Mon-Cerveau`**. Deux petits fichiers à la racine, `CLAUDE.md` (pour Claude) et `AGENTS.md` (pour ChatGPT), lui rappellent qui tu es à chaque session. Ne les supprime pas.

## Mettre à jour le module

- **Claude** : dans l'onglet Code, tape `/plugin` → **Installed** → *second-brain-starter* → **Update now**.
- **ChatGPT** : rien à faire pour ton cerveau existant. Pour un nouveau cerveau, retélécharge le ZIP (étape B2).

---

## Problème ?

| Ce que tu vois | Quoi faire |
|---|---|
| **Claude** : pas d'onglet **Code** | Vérifie ton abonnement **Pro** (ou plus) et que l'app est à jour. |
| **Claude** : `/plugin` ne répond pas | Tu es dans l'onglet **Chat** au lieu de **Code**. Change d'onglet. |
| **Claude** : « Monte mon second cerveau » ne déclenche rien | Tape plutôt `/second-brain-starter:second-brain-starter`. |
| **ChatGPT** : il ne sait pas quoi faire | Vérifie que tu as ouvert le dossier `second-brain-starter-main` (celui qui contient `AGENTS.md` et `README.md`), pas un sous-dossier. Puis écris : « Lis AGENTS.md et suis ses instructions. » |
| **ChatGPT** : il refuse d'écrire dans `Mon-Cerveau` | Il attend ton approbation : regarde s'il y a une demande en attente et accepte-la. |
| **ChatGPT** : message de limite d'usage | Le plan gratuit est vite limité. Attends la réinitialisation, ou passe à **Plus**. |
| Il a créé ton cerveau dans le dossier du starter | Déplace tout son contenu dans `Mon-Cerveau`, ou demande-lui : « Déplace mon cerveau dans Documents/Mon-Cerveau ». |
| L'assistant ne se souvient plus de toi | Tu ne l'as pas ouvert dans `Mon-Cerveau`. Vérifie aussi que `CLAUDE.md` et `AGENTS.md` sont à la racine du dossier. |
| Les notes du jour affichent `{{date}}` | Les modèles ne sont pas activés dans Obsidian → refais l'étape finale, point 3. |
| Tu es bloqué | Écris-nous sur [arkytechs.com](https://arkytechs.com). |

---

## Pour les initiés — terminal

**Claude Code**

- Installer — Mac / Linux : `curl -fsSL https://claude.ai/install.sh | bash` · Windows (PowerShell) : `irm https://claude.ai/install.ps1 | iex`
- Dans ton dossier de vault : `claude`, puis les deux commandes `/plugin` de l'étape A4.
- Mise à jour : `/plugin marketplace update arkytechs`
- Doc : https://code.claude.com/docs/en/installation

**Codex CLI**

- Installer — Mac / Linux : `curl -fsSL https://chatgpt.com/codex/install.sh | sh` · Partout : `npm install -g @openai/codex`
- Le repo est aussi une marketplace compatible Codex : `codex plugin marketplace add D4rthur/second-brain-starter`, puis installe le plugin et redémarre Codex.
- Ou clone le repo, lance `codex` à sa racine et dis « monte mon second cerveau » : `AGENTS.md` fait le reste.
- Doc : https://learn.chatgpt.com/docs/codex/cli

---

*Second Brain Starter — offert par [Arkytechs](https://arkytechs.com).*
