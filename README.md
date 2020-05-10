# Kaggle competititon: Diamonds
## `Supervised Machine Learning`

This project is a [Kaggle competition](https://www.kaggle.com/c/diamonds-datamad0320/overview) whose goal is to predict the price of diamonds based on their characteristics. For this purpose, three datasets are given:

- **Dataset for model training:** This dataset contains **40345 records**, **9 features** containing the predictive values and a last column with the `price` of each record. The 9 predictive features are:
  - Numeric features: proportions and weight of diamonds
  
        - carat: weight of the diamond
        
        - x: length in mm
        
        - y: width in mm
        
        - z: depth in mm
        
        - depth: total depth percentage = z / mean(x, y) = 2 * z / (x + y) (43--79)
        
        - table: width of top of diamond relative to widest point in percentage (43--95)
        
  - Categorical features: mesuares of shape, color and imperfections in diamonds
  
        - cut: quality of the cut (Fair, Good, Very Good, Premium, Ideal)
        
        - color: diamond colour, from J (worst) to D (best)
        
        - clarity: a measure of how clear the diamond is (I1(worst), SI2, SI1, VS2, VS1, VVS2, VVS1, IF(best))
        
        
- **Dataset for model test:** This dataset contains the same information about new records (new diamonds), except the price which will be predicted by the trained model with the training dataset.

- **Sample of dataset for submission:** The dataset for submission must contain only two columns: id (th same ID number for the records in the test dataset) and price (predicted prices for records in test dataset by trained model).
        
  
