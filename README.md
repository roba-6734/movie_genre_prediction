
# Movie Genre Prediction

This project is designed to predict the genre of a movie based on its plot summary or other textual information. The machine learning model used in this project analyzes input data and predicts the most likely genre of the movie. 

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Model](#model)
- [Data](#data)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Installation

1. Clone the repository:

```bash
git clone https://github.com/roba-6734/movie_genre_prediction.git
```

2. Navigate to the project directory:

```bash
cd movie_genre_prediction
```

3. Install the necessary dependencies:

```bash
pip install -r requirements.txt
```

## Usage

To run the model and make predictions:

1. Place your dataset in the `data/` folder (ensure it's in the appropriate format).
2. Run the script to train the model:

```bash
python train_model.py
```

3. Once the model is trained, use the following command to predict the genre of a movie based on its plot summary:

```bash
python predict.py "Enter your movie plot summary here"
```

## Model

This project uses natural language processing (NLP) techniques to analyze the plot summary of movies and predict their genre. The machine learning model includes:

- **Text Preprocessing:** Tokenization, stop-word removal, and lemmatization to prepare the data for training.
- **Feature Extraction:** TF-IDF (Term Frequency-Inverse Document Frequency) is used to convert text data into numerical vectors.
- **Model Selection:** A suitable classification algorithm (e.g., Logistic Regression, Random Forest) is used for genre prediction.

## Data

This project uses a dataset of movies with their plot summaries and associated genres. You can use any suitable dataset of your choice in the `data/` folder, ensuring that it follows the same structure (e.g., a CSV file with `plot` and `genre` columns).

## Results

After training the model, you can view the classification accuracy and other evaluation metrics (e.g., confusion matrix, F1-score). 

## Contributing

Contributions are welcome! If you have suggestions for improvements or find any bugs, feel free to open an issue or submit a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
