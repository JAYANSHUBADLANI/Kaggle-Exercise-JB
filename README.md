# Kaggle exercises and university projects

This repository is an archive, not a portfolio project. It holds two different kinds of thing and
I would rather label them plainly than let them sit together unmarked.

## University projects

These are my own work, written for the MSc at Delhi University. They are the only files here I
would point at as representative.

| Notebook | What it does |
| --- | --- |
| [`jayanshu-badlani-du-ms-project-1.ipynb`](jayanshu-badlani-du-ms-project-1.ipynb) | Health insurance premium analysis. Distribution and smoking-impact statistics, one way ANOVA across region, sex and smoker status, then multiple linear regression with encoded categoricals and an interaction term. |
| [`jayanshu-badlani-du-ms-project-2.ipynb`](jayanshu-badlani-du-ms-project-2.ipynb) | Credit risk and loan default. Cleaning implausible ages, defaulter versus non-defaulter comparisons, debt to income ratio as the primary signal, and a logistic regression classifier. |

Two corrections I made to these later, after re-reading them:

- Project 2's logistic regression was fitted on unscaled features and did not reliably converge.
  Features are now scaled before the fit.
- Project 2 also had a summary line that contradicted its own output, and it labelled unscaled
  logistic coefficients as feature importance, which they are not. Both are fixed.

## Kaggle course exercises

The remaining sixteen notebooks are completed exercises from Kaggle's free micro courses (Python,
Intro to Machine Learning, Intermediate Machine Learning, Data Visualisation, SQL, Geospatial
Analysis). They are course completion work: the problem statements, scaffolding and prose are
Kaggle's, and only the filled-in answers are mine.

I keep them because they are a genuine record of when I learned each topic, and the commit dates
reflect that. They are not original analysis and should not be read as such.

## Licence

Deliberately unlicensed. The university projects are mine, but most of the exercise notebooks are
substantially Kaggle's own material, so putting an MIT licence across the whole repository would be
claiming something I am not in a position to grant.

## The actual portfolio

The projects I would want judged live in their own repositories, not here. A few of them:

- [credit-scorecard-service](https://github.com/JAYANSHUBADLANI/credit-scorecard-service), a scoring
  API with drift monitoring, deployed and running on Google Cloud Run
- [application-credit-scorecard](https://github.com/JAYANSHUBADLANI/application-credit-scorecard),
  weight of evidence binning, PDO scaling and reject inference
- [nyc-taxi-spark-pipeline](https://github.com/JAYANSHUBADLANI/nyc-taxi-spark-pipeline), a
  bronze/silver/gold PySpark pipeline
- [pricing-promotion-optimization](https://github.com/JAYANSHUBADLANI/pricing-promotion-optimization),
  Bayesian price elasticity with cannibalisation effects

The full list is at [github.com/JAYANSHUBADLANI](https://github.com/JAYANSHUBADLANI?tab=repositories).
