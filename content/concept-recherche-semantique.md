---
title: "Recherche sémantique"
date: 2026-07-13
tags: [concept, rag]
source: labia
---
# Recherche sémantique

**En une phrase :** retrouver de l'information par **proximité de sens** (via [concept-embeddings](/concept-embeddings)) plutôt que par correspondance de mots-clés.

La recherche lexicale classique (ex. BM25) matche les mots exacts ; elle rate les reformulations et les synonymes. La recherche sémantique compare les vecteurs de la requête et des passages : « voiture » et « automobile » deviennent proches. En pratique on combine souvent les deux (**recherche hybride**) pour capter à la fois le sens et les termes exacts.

## Voir aussi
- [concept-base-vectorielle](/concept-base-vectorielle) · [concept-rag](/concept-rag) · [concept-eval-retrieval](/concept-eval-retrieval)

## Source
- Reimers & Gurevych (2019), *Sentence-BERT: Sentence Embeddings using Siamese BERT-Networks*, EMNLP.
