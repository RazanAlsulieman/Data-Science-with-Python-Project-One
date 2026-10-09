# MovieLens Exploratory Analysis and Rating Models

A 2019 learning project in a fork of [Simplilearn-Edu/Data-Science-with-Python-Project-One](https://github.com/Simplilearn-Edu/Data-Science-with-Python-Project-One).

**Razan Alsulieman's contribution:** the [MovieLens case-study notebook](DSProjectOne_MovielensCaseStudy.ipynb) and expanded README. Simplilearn supplied the educational project and dataset archive; GroupLens supplied the MovieLens data.

## Workflow

The notebook joins movie, rating, and user tables; explores age groups, movie-rating distributions, and viewership counts; one-hot encodes genres; and fits random-forest models using age, occupation, and genre features.

The exploratory workflows include a `RandomForestRegressor` and a later feature-selection branch using `RandomForestClassifier`. Their outputs measure different tasks: regression R² and classification accuracy. Full steps, figures, and results remain in the original notebook.

## Files and data

| File | Purpose |
| --- | --- |
| [DSProjectOne_MovielensCaseStudy.ipynb](DSProjectOne_MovielensCaseStudy.ipynb) | Notebook added by Razan Alsulieman in June 2019 |
| `Data science with Python 1.zip` | Archive inherited from Simplilearn; contains `movies.dat`, `ratings.dat`, and `users.dat` |

The data correspond to [MovieLens 1M](https://grouplens.org/datasets/movielens/1m/): 1,000,209 ratings from 6,040 users, with anonymous IDs and demographic categories.

## Open the notebook

With Jupyter installed:

```bash
git clone https://github.com/RazanAlsulieman/Data-Science-with-Python-Project-One.git
cd Data-Science-with-Python-Project-One
jupyter notebook DSProjectOne_MovielensCaseStudy.ipynb
```

For execution in a working copy, replace the three author-specific input paths with your authorized local MovieLens paths and match the filename `users.dat`.

**Dependencies:** NumPy, pandas, Matplotlib, Seaborn, scikit-learn, and Jupyter. The notebook records Python 3.7.1 and uses legacy APIs, including pandas `join_axes` and NumPy `np.bool`; package versions are not pinned.

## Attribution and data use

Use the official [MovieLens 1M documentation and terms](https://files.grouplens.org/datasets/movielens/ml-1m-README.txt). They require acknowledgment, separate permission for redistribution and commercial use, and prohibit implying GroupLens endorsement. Redistribution permission for the inherited archive is not documented here; no repository code license is included.

Dataset citation: F. Maxwell Harper and Joseph A. Konstan, *The MovieLens Datasets: History and Context* (2015), [DOI: 10.1145/2827872](https://doi.org/10.1145/2827872).
