# 20 Newsgroups PCA Analysis

This project demonstrates how to:
- **Load and explore** the [20 Newsgroups dataset](https://scikit-learn.org/stable/datasets/real_world.html#newsgroups-dataset) from scikit-learn.
- **Sample and preprocess** data:
  - Take 5% of the original dataset to reduce memory usage.
  - Convert the sparse data to dense (if needed) for PCA compatibility.
  - Standardize features using `StandardScaler` (with `with_mean=False`).
- **Apply PCA**:
  - Set `n_components=0.95` to retain 95% of variance.
  - Observe the number of principal components required.
- **Visualize and interpret** results:
  - Plot *cumulative explained variance* vs. number of PCA components.
  - Determine how many components capture the desired variance (here, 468 out of 130,107 features).


