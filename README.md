**Taxi Fare Prediction using Regeression Random Forest**

This repository contains the code for a machine learning project aimed at predicting taxi fares using the Random Forest algorithm. The project utilizes a dataset containing information about taxi rides, such as pickup/dropoff locations, timestamps, and the number of passengers, to train a regression model that can accurately estimate the fare amount for a given ride.

### Project Structure

- **Dataset**: Contains the dataset file `TaxiFare.csv` used for training and testing the machine learning model.
- **Code**: Contains the Python script `Abhijeet_2010991223(Project).py` that implements the Random Forest regression model and performs fare prediction.
- **README.md**: Provides an overview of the project, instructions for running the code, and additional information.

### Requirements

- Python
- pandas
- scikit-learn
- matplotlib

### How to Use

1. Clone this repository to your local machine using the following command:
   ```
   git clone https://github.com/Abhijeet-droid-AI/taxi-fare-prediction.git
   ```

2. Navigate to the project directory:
   ```
   cd Taxi-Fare-Prediction
   ```

3. Install the required Python libraries:
   ```
   pip install -r requirements.txt
   ```

4. Run the Python script to train the Random Forest model and make fare predictions:
   ```
   python Abhijeet_2010991223(Project).py
   ```

### Dataset

The dataset (`TaxiFare.csv`) contains the following columns:
- `unique_id`: Unique identifier for each record
- `date_time_of_pickup`: Timestamp of the ride pickup
- `longitude_of_pickup`: Longitude of the pickup location
- `latitude_of_pickup`: Latitude of the pickup location
- `longitude_of_dropoff`: Longitude of the dropoff location
- `latitude_of_dropoff`: Latitude of the dropoff location
- `no_of_passenger`: Number of passengers during the ride
- `amount`: Fare amount (target variable)

### Model Training and Evaluation

The Random Forest model is trained using the training data and evaluated using the testing data. Model performance is assessed using the coefficient of determination (R^2) metric, which measures the proportion of the variance in the fare amount that is predictable from the input features.

### License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

### Contributors

- [Abhijeet Dass](https://github.com/Abhijeet-droid-AI)

### Questions or Concerns

If you have any questions or concerns about the project, please feel free to [open an issue](https://github.com/Abhijeet-droid-AI/taxi-fare-prediction/issues) or contact [work@abhijeetdas2002@gmail.com].

---
Feel free to customize the README page further to include any additional information or details specific to your project.
