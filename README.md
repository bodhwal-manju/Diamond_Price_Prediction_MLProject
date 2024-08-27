# Diamond Price Prediction
## OverView
Diamonds are precious gemstones with various characteristics influencing their value. This project leverages machine learning techniques to predict the price of diamonds, taking into account factors such as carat weight, cut, color, clarity, and depth percentage.

<h2>Features</h2>
    <ul>
        <li><strong>Carat:</strong>Weight of the diamond.</li>
        <li><strong>Cut:</strong>Quality of the cut (Fair, Good, Very Good, Premium, Ideal).</li>
        <li><strong>Color:</strong>Color grade of the diamond (from D, colorless, to Z, light yellow or brown).</li>
        <li><strong>Clarity:</strong>Clarity grade indicating the presence of inclusions or blemishes.</li>
         <li><strong>Depth:</strong> Depth percentage of the diamond.</li>
    </ul>


### Dataset
The dataset used for training and testing the model is available in the data directory. The dataset contains a comprehensive set of diamonds with corresponding features and prices.


<h2>🛠️ Installation Steps:</h2>

<p>1. Clone this repository</p>

```
git clone https://github.com/bodhwal-manju/Diamond_Price_Prediction_MLProject.git
```

<p>2. Navigate to the project directory:</p>

```
cd Diamond_Price_Prediction_MLProject
```

<p>3. Create Virtual Environment(Using venv (Python 3 built-in module))</p>

```
python -m venv venv
```

<p>4. Activate the virtual environment(On Windows):</p>

```
venv\Scripts\activate
```

<p>5. Install Requirements</p>

```
pip install -r requirements.txt
```
<h2>Usage</h2>
To use the diamond price prediction model, follow these steps:

<li><strong>Prepare Data:</strong> Ensure your input data has the required features (carat, cut, color, clarity, depth).</li>

<li><strong>2. Load Model</strong>:Use the provided script to load the pre-trained model</li>
```
python load_model.py
```

<li><strong>Make Predictions:</strong> Utilize the model to make predictions on your diamond data</li>
python predict_price.py --carat 1.5 --cut Very Good --color F --clarity VS1 --depth 61.5
<li>Adjust the input values accordingly.</li>

### Model Training
If you want to retrain the model or experiment with different algorithms, refer to the training_pipeline.ipynb Jupyter notebook for detailed steps.

### Evaluation
The model's performance can be evaluated using metrics such as Mean Absolute Error (MAE) ,RMSE And  R-squared.

### Results
Lasso
Best Model Training Performance
<li><strong>RMSE:</strong> 1013.8784226767013</li>
<li><strong>MAE:</strong> 675.071692336216</li>
<li><strong>R2 score:</strong> 93.68940971841704</li>

### Contributing
Contributions are welcome! Feel free to submit issues, pull requests, or suggestions to improve the project.







