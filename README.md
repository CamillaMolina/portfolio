# Mathematics & Data

## About me

After graduating in Mathematics (M.S.) from Universidad Nacional de Cordoba (Argentina), my life took some unexpected turns and I started moving around the world. In the past 3 years I have been living in Italy, Sweden and now in the US. In my free time I do a lot of reading and exercise is my non-negotiable.


## Tech Skills

Python (pandas, scikit-learn, matplotlib),  SQL, AWS (CloudFormation, Lambda, S3, CloudWatch, RDS), git, Grafana.


## Projects & Experience

### - Anomaly detection in claimed items prices, at ValueChecker.

Context: ValueChecker helps insurance companies valuate the cost of claimed items.
In this project I designed and implemented a filter that would run daily, detecting and filtering out abnormal prices for each claimed item subcategory. The design consisted, roughly, of the following:
- Data preprocessing. Prices included taxes and were presented in different currencies.
- A scikit-learn clustering algorithm with a custom metric, designed specifically for this business problem. I proved that the function was indeed a metric, which is a necessary condition for the algorithm to work correctly.
- Percentile filtering on the price clusters, with fine-tuning to find the best performing value.

This filter helped catch over 4000 abnormal prices only in the first few months, allowing for greater reliability and serving as a starting point for investigations.

### - Flight prices prediction with scikit-learn.
This is a Colab Notebook where I used a Kaggle dataset to do some data exploration and create different ML models to predict flight prices. I am still working on polishing the code and the final part where I evaluate the models. Several visualizations are included. Main libraries: pandas, matplotlib and scikit-learn.
Click [here](https://colab.research.google.com/drive/1HyltKJO8E6OiIl1F6biv0JRDnLGIpcYa?usp=sharing) to view project.

![Flight Prices Prediction](/images/flight_plots.jpeg)


## Learning

### Currently reading
- Ian Goodfellow, Yoshua Bengio and Aaron Courville (2016). **Deep Learning.** MIT Press.
- Peter J. Bickel, Kjell A. Doksum (2015). **Mathematical Statistics: Basic Ideas and Selected Topics, Volume I, Second Edition.** Chapman & Hall.


### "Models and simulation" course, Universidad Nacional de Cordoba (completed 2021).
This course is a subject in the Computer Science program tought at the University.
Topics covered: Generation of random numbers and variables. Monte Carlo methods for numerical integration and estimations. Statistical analysis of simulated data. Markov chains.


### Refresher courses
- DataCamp course: Supervised Learning with scikit-learn (completed September 24th 2024).
- DataCamp course: Unsupervised Learning in Python (completed September 26th 2024).
- DataCamp course: Introduction to Deep Learning with PyTorch (completed October 16th 2024).
