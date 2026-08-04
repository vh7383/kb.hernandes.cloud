# kb.hernandes.cloud

Base de connaissances publique du laboratoire **LabIA** — vue en ligne sur
[kb.hernandes.cloud](https://kb.hernandes.cloud).

## Ce que c'est

Un sous-ensemble dérivé du [vault privé LabIA](https://github.com/vh7383/LabIA)
(Obsidian), publié ici de façon **irréversible dans un sens, réversible dans
l'autre** : seules les notes marquées `visibility: public` sont exportées ;
repasser une note en `private` la fait disparaître au prochain build.

## Comment ça arrive ici

1. **Export** (`labia-kb-pipeline/export-public`) — transforme les notes
   publiées du vault en contenu Quartz, neutralise les liens vers le privé.
2. **Push** sur ce dépôt (`content/`).
3. **CI** (`.github/workflows/build-and-deploy-kb.yaml`) — build Quartz,
   déploie sur le Pi via rsync restreint (rrsync).
4. **Réindexation** (`labia-kb-pipeline/reindex`) — un timer local reconstruit
   l'index de recherche (Raphaël) à partir de ce contenu publié, pour que
   Gabrielle (l'accueil du site principal) puisse y répondre avec sources.

Détail complet du pipeline → [`guide-publier-la-kb.md`](https://github.com/vh7383/LabIA/blob/main/guides/guide-publier-la-kb.md)
(vault privé).

## Propulsé par Quartz

> "[One] who works with the door open gets all kinds of interruptions, but [they] also occasionally gets clues as to what the world is and what might be important." — Richard Hamming

Quartz is a set of tools that helps you publish your [digital garden](https://jzhao.xyz/posts/networked-thought) and notes as a website for free.

🔗 Read the documentation and get started: https://quartz.jzhao.xyz/

[Join the Discord Community](https://discord.gg/cRFFHYye7t)

### Sponsors

<p align="center">
  <a href="https://github.com/sponsors/jackyzha0">
    <img src="https://cdn.jsdelivr.net/gh/jackyzha0/jackyzha0/sponsorkit/sponsors.svg" />
  </a>
</p>
