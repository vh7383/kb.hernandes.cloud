---
title: "Base vectorielle"
date: 2026-07-13
tags: [concept, rag]
source: labia
---
# Base vectorielle

**En une phrase :** base de données qui stocke des [concept-embeddings](/concept-embeddings) et retrouve rapidement les vecteurs les plus proches d'un vecteur requête (recherche des plus proches voisins).

Comme comparer un vecteur à des millions d'autres est coûteux, on utilise une recherche approximative (ANN, *approximate nearest neighbors*), par exemple l'index **HNSW**, qui échange un peu d'exactitude contre beaucoup de vitesse. Exemples : pgvector, Qdrant, FAISS.

## Voir aussi
- [concept-recherche-semantique](/concept-recherche-semantique) · [concept-rag](/concept-rag)

## Source
- Malkov & Yashunin (2018), *Efficient and robust approximate nearest neighbor search using HNSW graphs*, IEEE TPAMI.
