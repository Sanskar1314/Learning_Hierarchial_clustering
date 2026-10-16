# Learning Hierarchical Clustering

A notebook demonstrating agglomerative clustering and dendrograms using the Iris dataset.

## Contents

- `hierarchial.ipynb`: loads Iris into a pandas DataFrame and standardizes its features.
- Reduces the features to two principal components using PCA.
- Builds a Ward-linkage dendrogram with SciPy and visualizes a two-cluster agglomerative solution.

## Run locally

Use Python 3 and run Jupyter from the repository directory.

```bash
git clone https://github.com/Sanskar1314/Learning_Hierarchial_clustering.git
cd Learning_Hierarchial_clustering
python -m venv .venv
source .venv/bin/activate
python -m pip install jupyterlab numpy pandas matplotlib scipy scikit-learn
jupyter lab
```

On Windows, activate the environment with `.venv\Scripts\activate`. Open the notebook listed above and run its cells in order. Results and visualizations appear in the notebook.

## Reproduction notes

Iris is included with scikit-learn. The initial scatter plot is colored using known species labels for comparison; clustering itself is unsupervised. The notebook chooses two clusters, while Iris has three species.
