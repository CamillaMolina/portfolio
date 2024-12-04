# Mathematics & Data

## About me

After graduating in Mathematics from Universidad Nacional de Cordoba (Argentina), my life took some unexpected turns and I started moving around the world a lot. In the past 3 years I have been living in Italy, Sweden and now in the US. In my free time I do a lot of reading and exercise is my non-negotiable.

## Technical Skills

Python(pandas, scikit-learn, matplotlib), SQL, AWS (CloudFormation, Lambda, S3, CloudWatch, RDS), git.

## Projects & Experience

### Flight prices prediction with scikit-learn.
This is a Colab Notebook where I used a Kaggle dataset to do some data exploration and create different ML models to predict flight prices. I am still working on polishing the code and the final part where I evaluate the models. Several visualizations are included. Main libraries: pandas, matplotlib and scikit-learn.

Click [here](https://colab.research.google.com/drive/1HyltKJO8E6OiIl1F6biv0JRDnLGIpcYa?usp=sharing) to view project.

### Anomaly detection for price of claimed items (at ValueChecker).
Context: ValueChecker helps insurance companies valuate the cost of claimed items.
In this project I designed and implemented a filter that would run daily, detecting and filtering out abnormal prices for each claimed item subcategory. The design consisted, roughly, of the following:
- Data normalization.
- A scikit-learn clustering algorithm with a custom metric, designed specifically for this business problem. I proved that the function was indeed a metric, which is a necessary for the algorithm to work correctly.
- Percentile filtering on the price clusters.
This filter helped catch over 4000 abnormal prices only in the first few months, allowing for greater realiability and serving as a starting point for investigations.

## Learning

### Currently reading
- Ian Goodfellow, Yoshua Bengio and Aaron Courville (2016). **Deep Learning.** MIT Press.
- Peter J. Bickel, Kjell A. Doksum (2015). **Mathematical Statistics: Basic Ideas and Selected Topics, Volume I, Second Edition.** Chapman & Hall.

### Refresher courses (easy, completed in few hours)
- DataCamp course: Supervised Learning with scikit-learn (completed September 24th 2024).
- DataCamp course: Unsupervised Learning in Python (completed September 26th 2024).
- DataCamp course: Introduction to Deep Learning with PyTorch (completed October 16th 2024).
