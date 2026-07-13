---
title: "Évaluation de la récupération"
date: 2026-07-13
tags: [concept, rag]
source: labia
---
# Évaluation de la récupération

**En une phrase :** mesurer si la récupération renvoie **le bon passage**, et s'il est **bien classé**, avant de juger la réponse finale du LLM.

Sans mesure, impossible de savoir si un changement (de [concept-chunking](/concept-chunking), de modèle d'[concept-embeddings](/concept-embeddings), de moteur) améliore ou dégrade. Métriques standards issues de la recherche d'information : **recall@k** (le bon passage est-il dans le top k ?), **precision@k**, **MRR** (à quel rang arrive-t-il ?). On maintient un petit jeu de questions de référence pour comparer les versions.

## Voir aussi
- [concept-recherche-semantique](/concept-recherche-semantique) · [concept-rag](/concept-rag)

## Source
- Manning, Raghavan & Schütze (2008), *Introduction to Information Retrieval*, Cambridge University Press.
