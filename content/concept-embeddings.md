---
title: "Embeddings — représentations vectorielles"
date: 2026-07-13
tags: [concept, rag, llm]
source: labia
---
# Embeddings — représentations vectorielles

**En une phrase :** représentation d'un texte sous forme de vecteur numérique capturant son sens, de sorte que deux textes proches par le sens ont des vecteurs proches.

C'est ce qui permet de comparer des textes par leur **sens** et non par leurs mots exacts. Un modèle d'embedding (ex. `nomic-embed-text`) transforme chaque passage en vecteur ; la proximité entre vecteurs (souvent cosinus) mesure la proximité de sens. Base de la [concept-recherche-semantique](/concept-recherche-semantique) et du [concept-rag](/concept-rag).

À retenir : un embedding a une **dimension fixe** propre au modèle ; changer de modèle impose de tout recalculer.

## Voir aussi
- [concept-base-vectorielle](/concept-base-vectorielle) · [concept-recherche-semantique](/concept-recherche-semantique)

## Source
- Mikolov et al. (2013), *Efficient Estimation of Word Representations in Vector Space* (word2vec). Pour la phrase : Reimers & Gurevych (2019), *Sentence-BERT*.
