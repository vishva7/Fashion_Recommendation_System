# 👗 Fashion Recommendation System

A deep learning-based **Fashion Recommendation System** that suggests visually and semantically similar fashion items to users.  
This project performs a **comparative study** between **Convolutional Neural Networks (CNNs)** and **Graph Neural Networks (GNNs)** to identify the most effective approach for clothing recommendations.

---

## 🚀 Features
- Image-based recommendation of clothing items.
- Feature extraction using **ResNet50** and **VGG16**.
- Graph-based similarity learning using **GCN** and **Node2Vec**.
- Item similarity computed using **cosine similarity** and graph-based approaches.


---

## 📊 Models Used
- **CNN Models**
  - VGG16
  - ResNet50
- **GNN Models**
  - Graph Convolutional Networks (GCN)
  - Node2Vec

---

## 🗂 Dataset
- Images of clothing items.
- Metadata (from `styles.csv`):
  - `article_id`
  - `gender`
  - `masterCategory`
  - `subCategory`
  - `productType`
  - `productDisplayName`

---

## ⚙️ Tech Stack
- **Python**
- **PyTorch / TensorFlow**
- **NetworkX / PyTorch Geometric (PyG)**
- **Matplotlib / Seaborn** (for visualization)
- **scikit-learn** (for KNN & similarity search)

---

## 📦 Installation
Clone the repository:
```bash
git clone https://github.com/your-username/fashion-recommendation-system.git
cd fashion-recommendation-system
