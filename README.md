# Amazon-Fashion-Recommendation

## Problem
Given a cloth from the amazon clothes data having many features like title, brand, price, image etc, we will recommend some clothes to the user which he/she might be interesting in buying.

## Input


![Input](https://user-images.githubusercontent.com/45073252/133004065-fdf781f7-ba96-421c-b627-f54d2625c6b8.png)

## Outputs




![Output1](https://user-images.githubusercontent.com/45073252/133004105-5c8a3fe4-5696-4cbb-a3db-19f86e7030b2.png)

![Output2](https://github.com/Deep1129/Amazon-Fashion-Recommendation/blob/0f55305a109ce1146bca4fedf34df6cd2c07ab7e/Output2.png)

![Output3](https://github.com/Deep1129/Amazon-Fashion-Recommendation/blob/0f55305a109ce1146bca4fedf34df6cd2c07ab7e/Output3.png)



## Data
The dataset consists of 183138 samples of cloth data, each data row having following 7 features:
1. asin                  - unique id given to every cloth
2. brand                 - brand of the cloth
3. color                 - color of the cloth
4. medium-image-url      - link to the image of the cloth
5. product_type_name     - type of the product (like shirt, tshirt etc)
6. title                 - title given to the cloth on the website
7. formatted price       - price of the product in dollars


# Ml methodologies used

* Standard data preprocessing has been done on title feature.
* Every data point was represented as a vector using various combination of the given features.
* Vector representation was done using idf, tf-idf, BoW, CNN, etc.
* Products close to the vector representation of the input data point was recommended.

**Reference**
Applied AI course


