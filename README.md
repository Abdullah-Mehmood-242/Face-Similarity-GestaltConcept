# Face Similarity using GestaltMatcher Concept

This project demonstrates face similarity matching using facial embeddings inspired by the GestaltMatcher approach. It leverages deep learning to extract embeddings from face images and computes similarity between them.

## 📁 Project Structure

```
ai_project/
├── images/                        # Folder containing face images (extracted from images.rar)
├── requirements.txt              # Python dependencies
└── Face_Similarity_GestaltConcept.ipynb   # Jupyter Notebook with full code
```

## 🚀 How It Works

1. Loads face images and extracts embeddings using a pre-trained deep learning model.
2. Computes similarity between a reference face and other faces.
3. Visualizes top similar faces and clusters using UMAP.

## 📦 Dataset Download

Due to GitHub file size limitations, the full image dataset (~835MB) is hosted on Google Drive.

👉 [Click here to download images.rar](https://drive.google.com/uc?export=download&id=1XDRAR2CcDu1cMHRFHMPjc9_9ZDb9gQAC)

After downloading, extract `images.rar` and place the extracted `images/` folder in the project root directory like this:

```
ai_project/
├── images/
│   ├── 1_0_0_20161219140622224.jpg
│   ├── 1_0_1_20161219162142125.jpg
│   └── ...
```

## 🛠 Requirements

Install dependencies using:

```bash
pip install -r requirements.txt
```

## 📒 Run the Notebook

Make sure your environment is active and JupyterLab is launched:

```bash
conda create --name ai_project
conda activate ai_project
jupyter lab
```

Then open `Face_Similarity_GestaltConcept.ipynb` and run all cells.

## 📌 Notes

- This project uses `torchvision`, `facenet-pytorch`, `sklearn`, `umap-learn`, and `PIL`.
- Visualization is done using `matplotlib`.

## 🧠 Based On

This project is inspired by the GestaltMatcher database and face similarity research.

## 🤖 Author
This project was developed by Abdullah Mehmood as part of a Data Mining course.

---
