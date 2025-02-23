# Logic Depth Prediction Using Machine Learning

## **Project Overview**  
This project predicts the combinational logic depth of digital circuits using an **Random Forest Regressor model**. It processes input circuit parameters such as **Fan-In, Fan-Out, and Gate-Type**, applies one-hot encoding for categorical variables, and trains the model using supervised learning.

## **Dependencies**
*Python 3.7+
*Pandas
*NumPy
*Scikit-Learn
*Random Forest Regressor Model
*System Verilog  (for logic simulation)
*EDA Tool (ModelSim, Quartus, Vivado, etc.)

## **Setup Instructions**  

1. Clone the Repository   
Navigate to the directory where you want to clone the project and run:  
```bash
git clone <your-repository-link>
cd Logic-Depth-Prediction-Using-Machine-Learning

2. Install Dependencies
Run the following command to install all required Python libraries

3. Download and Place the Dataset
/*from google.colab import drive
drive.mount('/content/drive')*/

Then, load the dataset:
/*import pandas as pd
dataset = pd.read_csv("/content/drive/MyDrive/Logic-Depth-Prediction-Using-Machine-Learning/log*/

/*Example Output
When the model runs successfully, it prints:
Mean Absolute Error: 0.312*/




#  **Project Structure**
Logic-Depth-Prediction-Using-Machine-Learning
│── data
│   ├── logic_depth_data.csv
│── models
│   ├── trained_model.pkl
│── src
│   ├── train.py
│   ├── test.py
│── System verilog
│   ├── logic_depth_lut.v
│   ├── testbench.v
│── requirements.txt
│── README.md



