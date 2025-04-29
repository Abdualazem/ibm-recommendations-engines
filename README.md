# IBM Recommendations Project

This project implements several recommendation system techniques using real user interaction data from the IBM Watson Studio platform. The notebook explores rank-based, collaborative filtering, content-based, and matrix factorization (SVD) approaches to recommending articles to users.

## Project Structure

```
Recommendations_with_IBM.ipynb
project_tests.py
data/
    articles_community.csv
    user-item-interactions.csv
user_item_matrix.p
top_5.p
top_10.p
top_20.p
```

## Features

- **Exploratory Data Analysis:** Understand user and article interaction patterns.
- **Rank-Based Recommendations:** Recommend the most popular articles.
- **User-User Collaborative Filtering:** Recommend articles based on similar users' interactions.
- **Content-Based Recommendations:** Recommend articles using metadata and keyword matching.
- **Matrix Factorization (SVD):** Use latent features to predict user-article interactions and make recommendations.
- **Evaluation:** Analyze cold start problems and model accuracy.

## Getting Started

1. **Clone the repository:**
    ```sh
    git clone https://github.com/Abdualazem/ibm-recommendations-engines
    cd ibm-recommendations-engines
    ```

2. **Install dependencies:**
    - Python 3.x
    - pandas, numpy, matplotlib, pickle

    You can install dependencies with:
    ```sh
    pip install pandas numpy matplotlib
    ```

3. **Data:**
    - Place `articles_community.csv` and `user-item-interactions.csv` in the `data/` directory.

4. **Run the notebook:**
    - Open `Recommendations_with_IBM.ipynb` in Jupyter Notebook or VS Code and run the cells sequentially.

## Usage

- Modify and run the notebook to explore different recommendation strategies.
- Use the provided functions to generate recommendations for new or existing users.
- Evaluate the performance of each approach using the included tests and visualizations.

## Project Files

- `Recommendations_with_IBM.ipynb`: Main notebook with all code and analysis.
- `project_tests.py`: Helper functions for validating your implementation.
- `data/`: Contains the datasets used for analysis.
- `user_item_matrix.p`, `top_5.p`, `top_10.p`, `top_20.p`: Precomputed data for efficiency.

## License

This project is for educational purposes.

---

**Author:** Abdualazem Ebrahim  
**Contact:** Abdualazem.Fadol@gmail.com