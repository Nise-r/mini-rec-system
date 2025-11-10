## mini-rec-system
This project implements a mini recommendation system for fashion products, designed to match user vibe queries (e.g., "energetic urban chic") to relevant items. It demonstrates how AI embeddings can be used to capture semantic similarity between product descriptions and user intent.

## Why AI at Nexora?
Leveraging AI enables Nexora to provide personalized shopping experiences, quickly surface relevant products, and enhance user engagement. Even a small-scale prototype like this illustrates the potential of semantic search for fashion curation.

## Features

- Small mock product catalog with descriptions.
- Uses all-MiniLM-L6-V2 embeddings to encode product descriptions.
- Cosine similarity-based vector search to find top-3 products matching a vibe query.
- Handles edge cases (no strong match → fallback recommendation).
