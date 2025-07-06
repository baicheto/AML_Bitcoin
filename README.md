# AML Detection in Bitcoin Transactions using Graph Embedding Models

This project applies multiple **graph representation learning techniques**—including **DeepWalk**, **Node2Vec**, **GraphSAGE**, and **Graph Isomorphism Networks (GIN)**—to detect **illicit transactions in the Bitcoin network** using the Elliptic dataset.

---

## 📌 Overview

We explore and compare several **graph-based machine learning models** for anti-money laundering (AML) detection:

- **DeepWalk**: Unsupervised learning of node embeddings using random walks + Word2Vec.
- **Node2Vec**: Biased random walk strategy to capture homophily and structural equivalence.
- **GraphSAGE**: Inductive learning framework aggregating neighbor features.
- **GIN**: State-of-the-art message-passing GNN with strong discriminative power.

We use these embeddings or node representations to train **supervised classifiers** that predict whether a transaction is **licit**, **illicit**, or **unknown**.

---

## 🗂️ Dataset

We use the **Elliptic Bitcoin dataset**, which contains:
- A directed transaction graph with temporal structure.
- Node-level class labels: **licit**, **illicit**, or **unknown**.
- **Nodes and edges**
The graph is made of 203,769 nodes and 234,355 edges. Two percent (4,545) of the nodes are labelled class1 (illicit). Twenty-one percent (42,019) are labelled class2 (licit). The remaining transactions are not labelled with regard to licit versus illicit.




