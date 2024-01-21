### Adidas Fashion Retail Products Price Prediction Model
#### Overview
This project aims to create a sophisticated, data-driven price prediction model for the used fashion industry, focusing specifically on Adidas products. The model will leverage a comprehensive dataset of over 9300 Adidas products to predict optimal resale prices, enhancing profitability and market efficiency.

#### Dataset Description
The Adidas Fashion Retail Products Dataset contains detailed information on over 9300 Adidas fashion items. 
https://www.kaggle.com/datasets/thedevastator/adidas-fashion-retail-products-dataset-9300-prod

__Key features include:__

| Column name | Description |
| --- | --- |
| **name** | The name of the product. (String) |
| **sku** | The SKU or unique identifier for the product. (String) |
| **original_price** | The original price of the product in USD or Euros. (Float) |
| **currency** | The currency type for the selling price and original price. (String) |
| **availability** | The availability of the product. (String) |
| **color** | The color of the product. (String) |
| **category** | The category of the product. (String) |
| **source_website** | The source website from where the data was collected. (String) |
| **breadcrumbs** | The breadcrumbs or path to the product page on the source website. (String) |
| **description** | A brief description of the product provided by Adidas. (String) |
| **brand** | The brand of the product. (String) |
| **images** | Multiple product images provided by Adidas. (String) |
| **country** | The country of origin/destination for the product. (String) |
| **language** | The language in which the product page was displayed on the source website. (String) |
| **average_rating** | The average customer rating out of 5 stars. (Float) |
| **reviews_count** | The number of customer reviews for the product. (Integer) |
| **crawled_at** | The date and time when the data was collected. (String) |
| **selling_price** | The selling price of the product in USD or Euros. (Float) |

#### Problem Statement
The challenge is to accurately predict the selling price of used Adidas fashion items. The price prediction must balance profitability for sellers and attractiveness for buyers, considering various product attributes.

#### Methodology
This project will approach the problem as a regression task. Key steps include:

* Data Preprocessing: Cleaning and transforming data for model compatibility.
* Feature Engineering: Creating new features that may aid in better price prediction.
* Model Selection: Experimenting with various regression models.
* Model Training and Validation: Training models on a subset of data and validating their performance.
* Evaluation Metric: Using Root Mean Square Error (RMSE) as the primary evaluation metric to emphasize the penalty on larger pricing errors.

#### RMSE Calculation
RMSE is calculated using the formula:

$$
RMSE = \sqrt{\frac{1}{n}\sum_{i=1}^{n}(y_i - \hat{y}_i)^2}
$$

where:

- $n$ is the total number of observations,
- $y_i$ is the actual value of the i-th observation,
- $\hat{y}_i$ is the predicted value of the i-th observation.
