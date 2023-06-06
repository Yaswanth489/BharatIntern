# Wine Quality Prediction using Linear Regression

This project aims to predict the quality of wines based on various features using linear regression. The dataset used for this project is sourced from Kaggle, a popular platform for data science competitions and datasets.

## Dataset

The dataset used for this project can be found on Kaggle under the name "Red Wine Quality". It contains a collection of red and white wine samples with their corresponding quality ratings. The dataset includes various chemical and sensory features that describe the properties of each wine sample. The dataset can be downloaded from the following link: [Kaggle Dataset](https://www.kaggle.com/datasets/uciml/red-wine-quality-cortez-et-al-2009)

### Context
The two datasets are related to red and white variants of the Portuguese "Vinho Verde" wine. For more details, consult the reference [Cortez et al., 2009]. Due to privacy and logistic issues, only physicochemical (inputs) and sensory (the output) variables are available (e.g. there is no data about grape types, wine brand, wine selling price, etc.).

These datasets can be viewed as classification or regression tasks. The classes are ordered and not balanced (e.g. there are much more normal wines than excellent or poor ones).

## Dependencies

To run this project, the following dependencies are required:

- Python 3.6 or above
- NumPy
- Pandas
- Matplotlib
- Scikit-learn

You can install the required packages using pip:

```
pip install numpy pandas matplotlib scikit-learn
```

## Usage

1. Download the dataset from the provided Kaggle link and save it in the project directory.

2. Run the `Red_Wine_Quality.ipynb` file, which contains the code for data preprocessing, model training, and evaluation.

3. The script will load the dataset, preprocess the data, split it into training and testing sets, train a linear regression model, and evaluate its performance.

4. After the model training is completed, it will predict the wine quality for the testing set and display the evaluation metrics such as mean absolute error, mean squared error, and R-squared score.

## Input variables (based on physicochemical tests):

1. fixed acidity
2. volatile acidity
3. citric acid
4. residual sugar
5. chlorides
6. free sulfur dioxide
7. total sulfur dioxide
8. density
9. pH
10. sulphates
11. alcohol

Output variable (based on sensory data): quality (score between 0 and 10)

## Coefficient Values
![alt text](https://user-images.githubusercontent.com/19779081/53143050-5d7b5b80-35bc-11e9-846b-fd0ee3e09565.PNG)

## Regression Evaluation Metrics

Here are three common evaluation metrics for regression problems:
Mean Absolute Error (MAE) is the mean of the absolute value of the errors:
![alt text](https://render.githubusercontent.com/render/math?math=%5Cfrac%201n%5Csum_%7Bi%3D1%7D%5En%7Cy_i-%5Chat%7By%7D_i%7C&mode=display)

Mean Squared Error (MSE) is the mean of the squared errors:
![alt text](https://render.githubusercontent.com/render/math?math=%5Cfrac%201n%5Csum_%7Bi%3D1%7D%5En%28y_i-%5Chat%7By%7D_i%29%5E2&mode=display)

Root Mean Squared Error (RMSE) is the square root of the mean of the squared errors:
![alt text](https://render.githubusercontent.com/render/math?math=%5Csqrt%7B%5Cfrac%201n%5Csum_%7Bi%3D1%7D%5En%28y_i-%5Chat%7By%7D_i%29%5E2%7D&mode=display)

Comparing these metrics:

- MAE is the easiest to understand because it’s the average error.
- MSE is more popular than MAE because MSE “punishes” larger errors, which tends to be useful in the real world.
- RMSE is even more popular than MSE because RMSE is interpretable in the “y” units.

## Results

The results of the wine quality prediction are displayed after the model training and evaluation. These results include the evaluation metrics and can be used to assess the accuracy and performance of the linear regression model.
![alt text](https://www.kaggleusercontent.com/kf/117393552/eyJhbGciOiJkaXIiLCJlbmMiOiJBMTI4Q0JDLUhTMjU2In0..WTI87VUpnDreQiX3KX61vg.q2c6auEBnm9ciPCZ2WxHXu8F-ohqIaRUNcqd0AQe9kj64RVUJGf3yb5bwrbTDTZ0fDNv-lA0pPUZ_8aIMzXACRtQ3-pknfqYYOTko-DdQj3FNsFEr_ZoFbeBZ8-8q2yr0GvcfTvNzf1kaMFLRUjLmLPzNf7Qxus2P8K2xQrJZyNBwysMBGGonzUXmxC37_XmJLFCbeJ7oXUC1Ht-JpmQG0yrWR7-WuZSReqSilYNn_bCueav5fNqKukqO6NUrbt5f_cSbiE5IJkSWAJNWIbXzGCD2f2IUnK3JetwNGlo0P6slwhwhdjskQcBe18InFPX3Hl8I6h7iIwUdr1zXl6mjZJLMgh8I5snSaEc2uPkytT9jG8ZXF_G_p1UJNvwQUKS7HrWfyPesy9aCLq97zIov2zZqgPOOvolhwh_jJvh1RDwx6TaR8ZGJdFd1edO1p7XHN-TudSiERFaYEMCuXRzoqi72YzVYiwCjI8VdGqiYlV7SvZYN8oyoZUuli0XQL6cDZHlH3bpAMrRYKA8jmfaiV1VifQLRKFgd_m7gIXGb80jLsKfCPHOmhNl8YiXEGZ-Lygzpw1Y23Hegx4fQXwdisf0jNBAOpNTzxSoSjmvXLtAvhzMQPzOm3jMY1Vmv289nUqRI66vAWC5aEfw678oS8MKQUmDACkjjlO4pOzGj7Y.zogwz7VOEJ0msOFdvgc2nQ/__results___files/__results___5_0.png)

## License

The dataset used in this project is subject to the licensing terms provided by Kaggle. Please refer to the dataset's license for more details.

## Contributing

Contributions to this project are welcome. If you find any issues or have suggestions for improvements, please feel free to open an issue or submit a pull request.

## Contact

For any questions or inquiries, please contact [m.arpanareddy18@gmail.com].

---
