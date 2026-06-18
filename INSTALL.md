# Installation — Second Brain Starter

## Prérequis

- [Claude Code](https://docs.claude.com/en/docs/claude-code) (recommandé, install en 2 commandes) ou Claude Desktop.
- [Obsidian](https://obsidian.md) — gratuit (pour visualiser ton cerveau une fois monté).

## Option A — Claude Code (par lien, automatique)

Dans Claude Code, ajoute la marketplace puis installe le skill :

```
/plugin marketplace add D4rthur/second-brain-starter
/plugin install second-brain-starter@arkytechs
```

Puis invoque-le :

```
/second-brain-starter:second-brain-starter
```

ou écris simplement « monte mon second cerveau ». Les mises à jour passent ensuite toutes seules via la marketplace.

## Option B — Claude Desktop (manuel)

Claude Desktop ne supporte pas l'install par lien. Dépose le skill à la main :

1. Télécharge le repo (bouton « Code → Download ZIP » sur GitHub).
2. Copie le dossier `skills/second-brain-starter/` dans tes skills :
   ```
   ~/.claude/skills/second-brain-starter/
   ```
3. Redémarre Claude Desktop, puis demande « monte mon second cerveau ».

## Vérifier que c'est connecté

Une fois le vault monté et ton assistant pointé dessus, demande-lui :
> « Résume ce que tu sais sur moi et mon cerveau. »

S'il répond avec ton contexte (rôle, domaines, projets), tu es en route.

## Problème ?

- `/plugin` introuvable → tu es sur Desktop/web, utilise l'Option B.
- Le skill n'apparaît pas après install manuelle → vérifie le chemin `~/.claude/skills/second-brain-starter/` et redémarre.
- L'assistant ne lit pas le vault → vérifie qu'il a accès au dossier du vault et que `ai-assistant-instructions.md` est chargé.

---

*Second Brain Starter — offert par [Arkytechs](https://arkytechs.com).*
