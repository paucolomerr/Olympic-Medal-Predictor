# Olympic Medal Predictor

This project aims to predict the winners of medals in the upcoming 2024 Olympic Games based on historical data from the past 120 years of Olympic history. By analyzing patterns and trends in the data, we aim to build a machine learning model that can accurately forecast which athletes are most likely to win gold, silver, and bronze medals in their respective events.

## Project Overview

The "120 Years of Olympic History: Athletes and Results" dataset from Kaggle provides a comprehensive overview of athletes, events, and outcomes from modern Olympic Games. This project will use this historical data to train and evaluate machine learning models for predicting medal winners.

## Dataset

The dataset includes:
- Athlete information: Name, age, gender, height, weight, and nationality.
- Event information: Year, city, sport, and event.
- Results: Medal type (gold, silver, bronze, or none).

You can find the dataset [here](https://www.kaggle.com/heesoo37/120-years-of-olympic-history-athletes-and-results).

## Project Structure

- *data/*: Contains the dataset and any preprocessing scripts.
- *notebooks/*: Jupyter notebooks for data exploration, preprocessing, and model development.
- *models/*: Saved machine learning models.
- *scripts/*: Python scripts for training and evaluating models.
- *results/*: Evaluation results and analysis.
- *README.md*: Project overview and instructions.

## Getting Started

### Prerequisites

- Python 3.x
- Jupyter Notebook
- Required Python packages (listed in requirements.txt)

### Installation

1. Clone the repository:
    bash
    git clone https://github.com/yourusername/Olympic-Medal-Predictor.git
    cd Olympic-Medal-Predictor
    

2. Create a virtual environment and activate it:
    bash
    python3 -m venv venv
    source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
    

3. Install the required packages:
    bash
    pip install -r requirements.txt
    

### Usage

1. *Data Preprocessing*:
   - Explore and preprocess the data using the notebooks in the notebooks/ directory.

2. *Model Training*:
   - Train machine learning models using the scripts in the scripts/ directory.

3. *Evaluation*:
   - Evaluate the models and analyze the results stored in the results/ directory.

4. *Prediction*:
   - Use the trained models to predict the medal winners for the 2024 Olympic Games.

### Example Workflow

1. *Data Exploration*:
   - Use notebooks/01_data_exploration.ipynb to explore the dataset and understand the features.

2. *Data Preprocessing*:
   - Use notebooks/02_data_preprocessing.ipynb to clean and preprocess the data.

3. *Model Training*:
   - Train models using scripts/train_model.py.

4. *Model Evaluation*:
   - Evaluate the models using notebooks/03_model_evaluation.ipynb.

5. *Prediction*:
   - Predict the 2024 Olympic medal winners using scripts/predict_2024_winners.py.

## Contributing

We welcome contributions to improve the project. Feel free to open issues or submit pull requests with enhancements or bug fixes.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgments

- The dataset is provided by [Kaggle](https://www.kaggle.com/heesoo37/120-years-of-olympic-history-athletes-and-results).
- Thanks to the open-source community for providing valuable tools and resources.