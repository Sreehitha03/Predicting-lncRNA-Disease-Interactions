## 🧬 Predicting lncRNA–Disease Interactions Using Graph Neural Networks

This project aims to predict novel interactions between **long non-coding RNAs (lncRNAs)** and **diseases** using advanced **Graph Neural Networks (GNNs)**. Two distinct pipelines were developed and compared:

- **Method 1:** Graph Convolutional Network (GCN) using random node features
- **Method 2:** MetaPath2Vec embeddings combined with GCN for enhanced semantic understanding

> ✅ Built entirely in **Google Colab** for accessibility and reproducibility.

---

### 📁 Files

| File Name | Description |
|-----------|-------------|
| `method1.ipynb` | GCN-based prediction pipeline using random features |
| `method2.ipynb` | Enhanced pipeline using MetaPath2Vec + GCN |

---
### 📂 Dataset

This project utilizes a curated biological interaction dataset for training and evaluation. The dataset includes:

- Known **lncRNA–disease** interaction pairs
- Associated biological entities and relationships used to construct a **Heterogeneous Information Network (HIN)**

- ---

### 📊 Outputs

- 🧠 **Graph Visualizations:** Show both existing and newly predicted interactions within the heterogeneous network  
- 🔍 **t-SNE Plots:** Visualize the clustering of node embeddings, illustrating how lncRNAs and diseases are grouped based on learned representations  

---

### ✅ Conclusion

Our experimental results clearly demonstrate that the **MetaPath2Vec + GCN** approach significantly outperforms the basic GCN pipeline.

> 🔍 By integrating semantic node embeddings learned from metapath-based walks, the model captures rich contextual relationships within the network — resulting in **higher accuracy, precision, and interpretability**.

This study validates the potential of **graph-based deep learning** for uncovering **novel lncRNA–disease associations**, with promising applications in **biomedical research** and **drug discovery**.

---
Developed as part of the Mini-project.
