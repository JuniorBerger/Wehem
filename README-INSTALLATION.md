# Installation — Package Claude Code pour Gaëtan

## Ce que contient ce package

```
.claude/
  CLAUDE.md                    ← ton fichier de contexte personnel (Claude Code)
base-de-connaissances/
  CLAUDE.md                    ← règles et commandes pour la base de connaissances
  raw/                         ← dépose ici tes documents bruts (PDF, notes, .md)
  wiki/                        ← Claude organise ici la base (ne pas modifier manuellement)
  outputs/                     ← réponses générées et sauvegardées
```

---

## Étape 1 — Installer le CLAUDE.md personnel

```bash
# Sur ton ordinateur (Linux / Mac)
cp .claude/CLAUDE.md ~/.claude/CLAUDE.md

# Sur Windows
copy .claude\CLAUDE.md %USERPROFILE%\.claude\CLAUDE.md
```

> Ce fichier est chargé automatiquement par Claude Code à chaque session.

---

## Étape 2 — Placer la base de connaissances

```bash
# Déplace le dossier base-de-connaissances dans ton home
mv base-de-connaissances ~/base-de-connaissances
```

---

## Étape 3 — Vérifier l'installation

Lance Claude Code et tape :
```
/context
```
Tu dois voir ton CLAUDE.md chargé dans le contexte.

---

## Comment utiliser la base de connaissances

### Ajouter un document
Dépose n'importe quel fichier (PDF, .md, .txt) dans `~/base-de-connaissances/raw/`.

### Compiler la base
Dans Claude Code, colle cette commande :
```
Lis tout ce qui se trouve dans le dossier raw de ma base de connaissances,
puis compile la base dans le dossier wiki en suivant les règles du CLAUDE.md de ce dossier.
Crée d'abord un fichier index.md, puis une page par sujet, et relie les sujets entre eux.
Cite la source de chaque information.
```

### Poser une question
```
En te basant uniquement sur ma base de connaissances, réponds à cette question :
[TA QUESTION].
Lis l'index et les pages concernées, cite tes sources, et enregistre ta réponse
dans le dossier outputs. Si une information manque, dis-le-moi au lieu de l'inventer.
```

---

## Mise à jour du CLAUDE.md

Pour modifier ton identité, stack ou conventions, édite directement :
```
~/.claude/CLAUDE.md
```
Les changements s'appliquent à la prochaine session Claude Code.

