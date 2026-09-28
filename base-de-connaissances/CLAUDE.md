# Base de connaissances — WEHEM / Gaëtan

## Règles de gestion
- Les documents sources se trouvent dans `raw/`.
- La base organisée se trouve dans `wiki/`.
- Les réponses générées et sauvegardées se trouvent dans `outputs/`.
- Toujours citer la source de chaque information (nom du fichier dans `raw/`).
- Ne jamais inventer une information si elle n'est pas dans la base : le signaler explicitement.

## Commandes à utiliser

### Compiler la base
```
Lis tout ce qui se trouve dans le dossier raw de ma base de connaissances,
puis compile la base dans le dossier wiki en suivant les règles du CLAUDE.md de ce dossier.
Crée d'abord un fichier index.md, puis une page par sujet, et relie les sujets entre eux.
Cite la source de chaque information.
```

### Poser une question (avec sauvegarde)
```
En te basant uniquement sur ma base de connaissances, réponds à cette question :
[TA QUESTION].
Lis l'index et les pages concernées, cite tes sources, et enregistre ta réponse
dans le dossier outputs. Si une information manque, dis-le-moi au lieu de l'inventer.
```

### Mettre à jour après ajout dans raw/
```
J'ai ajouté [NOM DU FICHIER] dans raw/. Mets à jour la base wiki en intégrant
ce nouveau contenu. Relie-le aux sujets existants et mets à jour l'index.
```

## Organisation du wiki
- Un fichier par grand sujet (ex. `seo.md`, `agents-ia.md`, `upwork.md`, `clients-gabon.md`).
- Chaque fichier commence par une définition du sujet, puis les points clés, puis les sources.
- Les liens entre sujets utilisent la syntaxe `[[nom-du-sujet]]`.
- Le fichier `index.md` liste tous les sujets avec une ligne de description.

## Sujets prioritaires pour WEHEM
- SEO / référencement local (GBP, Gabon)
- Agents IA (Hermes Agent, architecture, cas d'usage)
- Marketing digital PME Afrique francophone
- Upwork / freelance IA Automation
- Prompt engineering
- Base44 (no-code)
- Stratégie de contenu
