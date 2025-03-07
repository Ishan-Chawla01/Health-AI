# HealthAssistant

HealthAssistant is an AI-powered tool for monitoring both physical and mental well-being.

## Features

1. **Hospitalization Prediction**:
    - Utilizes a prediction model with a Random Forest Regressor to determine if hospitalization is needed for respiratory problems.
    - Considers factors such as chronic disease history, presence of breathing issues, body temperature range (normal, high, low), blood oxygen saturation level (%), and age.
    - A Random Forest Classifier is also used for the same prediction.

2. **Sentiment Analysis**:
    - Analyzes journal entries to monitor daily thoughts.
    - Classifies sentiments as fearful, suicidal, anxious, normal, bipolar, etc.
    - Uses data from social media sentiment analysis.

## Data Sources

1. **Hospitalization Prediction**:
    - Data was sourced from a course on Unstop and from Kaggle.
    - The dataset is saved as `Covid_Data.csv`.

2. **Sentiment Analysis**:
    - Data was sourced from Kaggle.
    - The dataset is saved as `Combined_Data.csv`.

## How to Use

1. **Clone the repository**:
    ```sh
    git clone https://github.com/yourusername/HealthAssistant.git
    ```

2. **Navigate to the project directory**:
    ```sh
    cd HealthAssistant
    ```

3. **Install required dependencies**:
    1. Download the dataset (file could not be uploaded due to size being larger than 25 MB) from [this Kaggle link](https://www.kaggle.com/datasets/suchintikasarkar/sentiment-analysis-for-mental-health).
    2. Install libraries such as pandas, numpy, and scikit-learn:
    ```sh
    pip install pandas numpy scikit-learn
    ```

4. **Run the cells**:
    - For sentiment analysis, run the cell with the comment heading `# Function to predict the state based on user input` and the cell above it.
    - For hospitalization prediction, run the cell with the comment heading `# Hospitalization prediction program` and the cell below it.
    - Other cells are for data pre-processing if the need persists upon execution of the aforementioned cells.

## Basic UI Design
You can view the basic UI design in the [HealthAssistant.pdf](./HealthAssistant.pdf) file.

## Poster
You can view the project poster in the [HealthAssistant_Poster.pdf](./HealthAssistantPoster.pdf) file.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.
