# Kaggle exercises

My homework folder from the free Kaggle Learn courses. Nothing here is original research: these are the course exercises, filled in and (mostly) passing the built-in checker.

## Why it exists

To keep a record of what I practiced while learning data analysis and machine learning, and so I can find that one `GROUP BY ... HAVING` trick again later.

## What is in here

| Notebook | Course | Topic |
| --- | --- | --- |
| `exercise-group-by-having-count.ipynb` | Intro to SQL | `GROUP BY`, `HAVING`, `COUNT` on the Hacker News BigQuery dataset |
| `exercise-introduction.ipynb` | Intermediate Machine Learning | Comparing five random forest models on the Housing Prices competition data |
| `exercise-missing-values.ipynb` | Intermediate Machine Learning | Finding and handling missing values |
| `exercise-parsing-dates.ipynb` | Data Cleaning | Turning messy date columns into real datetimes (earthquakes dataset) |
| `exercise-random-forests.ipynb` | Intro to Machine Learning | Random forests for home prices |

## How to run it

These notebooks are built for the **Kaggle notebook environment**. They import Kaggle's `learntools` checker and read data from `/kaggle/input/...`, so they will not run as-is on a plain laptop. The easy way: open the matching course exercise on Kaggle, or upload a notebook there and attach the dataset named in its first cells. I did not add a `requirements.txt` on purpose, since `learntools` only exists inside Kaggle.

## Small result

In the model comparison exercise, the validation MAE ranges from about 23,500 to 24,000 across the five models, and model 3 wins (MAE 23,528).

## What I learned

Missing values and date formats are where most of the real work hides, and the course checkers are very good at telling you when you were almost right.

## Heads-up

- The exercises come from Kaggle Learn, so the exercise text belongs to Kaggle. I only added my own answers.
- No license file yet, so by default all rights are reserved for my own parts.
- I have not re-run the notebooks.
