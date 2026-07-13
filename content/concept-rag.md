---
title: "RAG — Génération augmentée par récupération"
date: 2026-07-13
tags: [concept, rag]
source: labia
---
# RAG — Génération augmentée par récupération

**En une phrase :** technique qui, au moment de la question, récupère des passages pertinents d'un corpus externe et les injecte dans le prompt du LLM pour qu'il réponde en s'appuyant dessus.

Un LLM ne connaît que ce qu'il a vu à l'entraînement. Le RAG lui ajoute une **mémoire externe** : à jour, spécifique, et vérifiable. Le flux type : indexer le corpus ([concept-chunking](/concept-chunking) puis [concept-embeddings](/concept-embeddings) dans une [concept-base-vectorielle](/concept-base-vectorielle)), puis à chaque question faire une [concept-recherche-semantique](/concept-recherche-semantique) et fournir les meilleurs passages au modèle.

Intérêt clé : le RAG sert surtout pour ce que le modèle **ne sait pas déjà** (données locales, récentes, privées) — pas pour du savoir général.

## Voir aussi
- [carte-rag](/carte-rag) · [concept-recherche-semantique](/concept-recherche-semantique) · [concept-eval-retrieval](/concept-eval-retrieval)

## Source
- Lewis et al. (2020), *Retrieval-Augmented Generation for Knowledge-Intensive NLP Tasks*, NeurIPS.
