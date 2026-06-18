# Blueprint du vault — pourquoi cette structure

La structure scaffoldée combine deux approches éprouvées. Comprendre le « pourquoi » aide à la garder vivante.

## PARA — la colonne vertébrale (organiser par actionnabilité)

Tout ce que tu sais tient dans quatre tiroirs, classés par à quel point c'est actionnable maintenant :

| Dossier | Contient | Test |
|---|---|---|
| **01-Projects** | Efforts actifs avec une fin | « Est-ce que ça se termine ? » |
| **02-Areas** | Responsabilités continues sans fin | « Dois-je maintenir un standard là-dessus ? » |
| **03-Resources** | Sujets d'intérêt, références | « Est-ce utile un jour, sans être actif ? » |
| **04-Archive** | Tout ce qui est devenu inactif | « C'est fini ou en pause ? » |

Règle d'or : une note vit là où elle est **actionnable**, pas là où elle « appartient » par thème. Un document sur un client passe de Resources à Projects quand un deal démarre, puis à Archive quand il se ferme.

## LYT — la couche de navigation (cartes de contenu)

Le dossier **MOCs/** (Maps of Content) tient des notes-index qui pointent vers tes autres notes. Au lieu de chercher, tu navigues. Un MOC « Clients » liste et relie toutes tes notes clients, peu importe leur dossier PARA.

Tu crées un MOC quand un sujet accumule 5+ notes reliées. Pas avant. C'est une couche qui émerge, pas une obligation de départ.

## Les pièces fixes

- **index.md** — la porte d'entrée. La carte de tout le vault. Ton assistant le lit en premier.
- **00-About-Me/about-me.md** — qui tu es, comment tu décides. Ça rend l'assistant pertinent.
- **Daily-Notes/** — une note par jour. Capture rapide, journal de bord, contexte du moment.
- **Decisions/decision-log.md** — chaque décision importante, datée, avec le pourquoi. Ta mémoire décisionnelle.
- **_templates/** — modèles vides à dupliquer pour rester cohérent sans effort.
- **ai-assistant-instructions.md** — le mode d'emploi de ton assistant IA : son rôle, son ton, ce qu'il lit en démarrant.

## Les 3 pièges à éviter

1. **Sur-organiser.** Le perfectionnisme structurel tue plus de seconds cerveaux que le désordre. La structure de base suffit.
2. **Capturer sans distiller.** Vise 3 captures pour 1 mise au propre. Un dépotoir n'est pas un cerveau.
3. **Tout taguer.** Les liens et les MOCs valent mieux que les tags. Garde les tags rares.
