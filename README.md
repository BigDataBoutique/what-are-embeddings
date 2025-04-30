This repository explores what embeddings are and how we can better understand them through visualization and clustering.

## 🔧 Getting Started

Install dependencies with Poetry:

```poetry install```

Open and run the notebooks in order.

## 📓 Included Notebooks
 1. Prepare
    Generates embeddings for the dataset in the data/ folder using Cohere’s embedding model, and ingests them into OpenSearch.

 2. PCA
    Analyzes the raw embedding vectors:
    * Checks for normalization
    * Uses unit vectors to explore if certain dimensions capture specific semantic features

 3. KMeans
    Applies KMeans clustering to identify groups of semantically similar items.

 4. UMAP
    Reduces the embedding space to 2D and 3D for visualization.
    Also demonstrates how even a small change in context can shift the meaning — and embedding — of a term.

