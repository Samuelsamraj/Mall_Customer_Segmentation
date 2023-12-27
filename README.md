# Mall_Customer_Segmentation

# Customer Segmentation

This project implements customer segmentation based on annual income and spending score using KMeans clustering. The model is trained on a dataset, and a GUI is provided for user input and prediction.

## Data Preprocessing

- The project begins with loading and exploring the dataset ('Mall_Customers.csv').
- Null values are checked and basic statistics are obtained.

## Model Building

- KMeans clustering is applied on the 'Annual Income' and 'Spending Score' features.
- The Elbow Method is used to determine the optimal number of clusters (k=5).

## Model Training and Visualization

- The model is trained with k=5 clusters, and predictions are visualized using a scatter plot.
- Cluster centers are marked in magenta.

## GUI

- A simple GUI is implemented using Tkinter for user input.
- The trained model is loaded, and predictions are displayed based on user input.

## Usage

1. Run the notebook `MALL_Customer Segmentation.ipynb` to train and save the model.
2. Execute the GUI by running the script and input annual income and spending score to predict the customer segment.

## Dependencies

- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- joblib
- Tkinter (for GUI)

