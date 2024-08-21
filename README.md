# Python Feature Engineering Cookbook

<a href="https://www.packtpub.com/en-us/product/python-feature-engineering-cookbook-9781835883587"><img src="https://content.packt.com/_/image/xxlarge/B22396/cover_image_large.jpg" alt="Python Feature Engineering Cookbook" height="256px" align="right"></a>

This is the code repository for [Python Feature Engineering Cookbook](https://www.packtpub.com/en-us/product/python-feature-engineering-cookbook-9781835883587), published by Packt.

**A complete guide to crafting powerful features for your machine learning models**

## What is this book about?
Python Feature Engineering Cookbook, Third Edition, walks you through tools and methods to craft powerful features from tabular, transactional, and time-series data for robust machine learning models.

This book covers the following exciting features: 
* Discover multiple methods to impute missing data effectively
* Encode categorical variables while tackling high cardinality
* Find out how to properly transform, discretize, and scale your variables
* Automate feature extraction from date and time data
* Combine variables strategically to create new and powerful features
* Extract features from transactional data and time series
* Learn methods to extract meaningful features from text data

If you feel this book is for you, get your [copy](https://www.amazon.com/dp/1835883591) today!

<a href="https://www.packtpub.com/?utm_source=github&utm_medium=banner&utm_campaign=GitHubBanner"><img src="https://raw.githubusercontent.com/PacktPublishing/GitHub/master/GitHub.png" alt="https://www.packtpub.com/" border="5" /></a>

## Instructions and Navigations
All of the code is organized into folders.

The code will look like the following:
```
date = "2024-05-17"
rng_hr = pd.date_range(date, periods=20, freq="h")
rng_month = pd.date_range(date, periods=20, freq="ME")
df = pd.DataFrame({"date1": rng_hr, "date2": rng_month})
```

**Following is what you need for this book:**
If you're a machine learning or data science enthusiast who wants to learn more about feature engineering, data preprocessing, and how to optimize these tasks, this book is for you. If you already know the basics of feature engineering and are looking to learn more advanced methods to craft powerful features, this book will help you. You should have basic knowledge of Python programming and machine learning to get started.

With the following software and hardware list you can run all code files present in the book (Chapter 1-11).

### Software and Hardware List

| Chapter  | Software required                                                                    | OS required                        |
| -------- | -------------------------------------------------------------------------------------| -----------------------------------|
|  		1-11   |   	Python 3.9 or greater Windows, macOS, or Linux						                                            			  | Windows, Mac OS X, and Linux (Any) |

### Related products <Other books you may enjoy>
* Mastering Transformers [[Packt]](https://www.packtpub.com/en-in/product/mastering-transformers-9781837633784?srsltid=AfmBOoq-sTm1lTo5AtdPERjFUb13Y4fJUATvjYuME3YRE08Aw-giNCaq) [[Amazon]](https://www.amazon.com/Mastering-Transformers-state-art-multi-modal/dp/1837633789)

* Causal inference and discovery in python [[Packt]](https://www.packtpub.com/en-in/product/causal-inference-and-discovery-in-python-9781804612989?srsltid=AfmBOopYHUuyXt2HhIq6Bp32dg1bDZH8ABHOzutz_BqQZbJf9F4pKjPZ) [[Amazon]](https://www.amazon.in/Causal-Inference-Discovery-Python-learning/dp/1804612987)

## Get to Know the Author
**Soledad Galli** is a bestselling data science instructor, author, and open-source Python developer. As the leading instructor at Train in Data, she teaches intermediate and advanced courses in machine learning that have enrolled over 64,000 students worldwide and continue to receive positive reviews. Sole is also the developer and maintainer of the Python open-source library Feature-engine, which provides an extensive array of methods for feature engineering and selection.
With extensive experience as a data scientist in finance and insurance sectors, Sole has developed and deployed machine learning models for assessing insurance claims, evaluating credit risk, and preventing fraud. She is a frequent speaker at podcasts, meetups, and webinars, sharing her expertise with the broader data science community.
