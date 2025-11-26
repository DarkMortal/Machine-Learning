## Difference Between LDA & PCA

| **Aspect** | **LDA (Linear Discriminant Analysis)** | **PCA (Principal Component Analysis)** |
|-----------|-----------------------------------------|----------------------------------------|
| **Type** | Supervised dimensionality reduction | Unsupervised dimensionality reduction |
| **Relationship analyzed** | Uses relationship between **dependent (class labels)** and **independent variables** | Uses relationship among **independent variables only** |
| **Goal** | Maximize **class separability** | Maximize **variance** in the data |
| **What it optimizes** | Ratio of **between-class variance** to **within-class variance** | Directions with **maximum total variance** |
| **Usage** | Dimensionality reduction **with class information** | Dimensionality reduction **without class information** |
| **Data requirement** | Requires labeled data | Works with labeled or unlabeled data |
| **Works best when** | Classes are well separated with similar covariance | Features are highly correlated (collinearity) |
| **Assumptions** | Assumes Gaussian classes with shared covariance matrix | No distributional assumptions |

