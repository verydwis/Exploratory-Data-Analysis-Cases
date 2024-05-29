# Exploratory-Data-Analysis-Cases

This repository contains Exploratory Data Analysis of cases.<br/>
This is conducted to sharpen my EDA and business knowledges regarding the case.<br/>
The library utilized are mostly Pandas, NumPy, Matplotlib and Seaborn.<br/>
** Explanation in Jupyter Notebook is conducted in Indonesian.<br/>

## Cases
1. E-Commerce
  - Problems:
    A company reduces all the price of 7 different product categories, such as: Athletic Shoes, Casual & Dress Shoes, Eyewear, Perfumes & Fragrances, Sportswear, Wallets, Watches. By reducing the price, the company expects to increase the percentage of unit sold, yet the profit will also reduce, ceteris paribus. Does rating increase after reducing the price of the product categories? Which product categories are favored by the consumers when the price is reduced? Dataset contains more than 50% null values. Therefore, the imputation will be conducted in the EDA.
  - Aims:
    Finding 3 product categories which is favorable/more percentage of unit sold after price reduction. Additionally, the categories are the products that gain the less profit but the unit sold is increasing. Therefore, those 3 products could be evaluated, so that the company wouldn't loose more revenue and the unit sold will reach the target.
2. Goodreads
  - Problems
    Rating could be a tricky measurement as a consumer or a seller. However, a good rating isn't always be meant that the book is favorable or recommended because the total consumers who give the rating might be not that much. Additionally, the total character in review comment is not necessarily the comment is good. Therefore, there must be a new system to measure the rating as the new insight for the book recommendation.
  - Aims:
    I would like to give top 20 book title and top 20 feature recommendation based on a new system, based on total book pages, the reader who have given rating and review comment of the book. Additionally, the trusted rating book will be given based on the book which is read by many Goodreads's subscibers.
