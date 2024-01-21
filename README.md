README: Adidas Fashion Retail Products Price Prediction Model
Overview
This project aims to create a sophisticated, data-driven price prediction model for the used fashion industry, focusing specifically on Adidas products. The model will leverage a comprehensive dataset of over 9300 Adidas products to predict optimal resale prices, enhancing profitability and market efficiency.

Dataset Description
The Adidas Fashion Retail Products Dataset contains detailed information on over 9300 Adidas fashion items. Key features include:

Name: Product name.
SKU: Unique identifier.
Original Price: Price in USD/Euros.
Currency: Type of currency.
Availability: Product availability status.
Color: Product color.
Category: Product category (Apparel/Footwear, etc.).
Source Website: Data source.
Breadcrumbs: Path to the product page.
Description: Product description by Adidas.
Brand: Adidas.
Images: Product images.
Country: Country of origin/destination.
Language: Language of the product page.
Average Rating: Customer rating out of 5.
Reviews Count: Number of customer reviews.
Crawled At: Data collection date.
The target variable for the model is Selling Price (in USD/Euros).

Problem Statement
The challenge is to accurately predict the selling price of used Adidas fashion items. The price prediction must balance profitability for sellers and attractiveness for buyers, considering various product attributes.

Methodology
This project will approach the problem as a regression task. Key steps include:

Data Preprocessing: Cleaning and transforming data for model compatibility.
Feature Engineering: Creating new features that may aid in better price prediction.
Model Selection: Experimenting with various regression models.
Model Training and Validation: Training models on a subset of data and validating their performance.
Evaluation Metric: Using Root Mean Square Error (RMSE) as the primary evaluation metric to emphasize the penalty on larger pricing errors.
RMSE Calculation
RMSE is calculated using the formula:

$$
RMSE = \sqrt{\frac{1}{n}\sum_{i=1}^{n}(y_i - \hat{y}_i)^2}
$$

where:
- $n$ is the total number of observations,
- $y_i$ is the actual value of the i-th observation,
- $\hat{y}_i$ is the predicted value of the i-th observation.