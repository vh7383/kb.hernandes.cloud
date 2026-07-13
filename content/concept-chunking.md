---
title: "Chunking — découpage en passages"
date: 2026-07-13
tags: [concept, rag]
source: labia
---
# Chunking — découpage en passages

**En une phrase :** découper un document en morceaux (*chunks*) avant de les vectoriser, pour que la recherche renvoie des passages ciblés plutôt que des documents entiers.

C'est souvent le réglage qui pèse le plus sur la qualité d'un [concept-rag](/concept-rag). Un chunk trop gros noie l'information utile ; trop petit, il perd le contexte. Bonnes pratiques : découper sur des **frontières sémantiques** (titres, sections), viser une taille cohérente, et prévoir un léger **chevauchement** pour ne pas couper une idée en deux.

## Voir aussi
- [concept-embeddings](/concept-embeddings) · [concept-eval-retrieval](/concept-eval-retrieval)

## Source
- Gao et al. (2023), *Retrieval-Augmented Generation for Large Language Models: A Survey*, arXiv.
