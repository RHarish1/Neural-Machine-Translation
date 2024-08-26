# Neural Machine Translation with GloVe Embeddings

## Description
This repository contains Python code for a neural machine translation (NMT) model that translates English sentences into French. The model leverages pre-trained GloVe embeddings for both English and French languages and is built using TensorFlow and Keras. Additionally, this repository includes a Flask web application that serves the translation model, allowing users to input English sentences through a web interface and receive French translations.

## Features
- **Data Loading and Preprocessing**: Functions are provided to load a dataset containing English sentences and their corresponding French translations. The text is cleaned and tokenized for preprocessing.
- **GloVe Embeddings Integration**: The model integrates pre-trained GloVe word embeddings for English and French languages to enhance translation quality.
- **Bidirectional LSTM Architecture**: The NMT model utilizes a bidirectional LSTM architecture with attention mechanisms for sequence-to-sequence translation tasks.
- **Training and Evaluation**: The code includes functions to train the model on the training data, evaluate its performance on a separate test set, and calculate the BLEU score for translation quality assessment.
- **Flask Web Application**: A Flask web application is included to serve the translation model. Users can input sentences through a web interface and receive translated outputs.
- **Main Runner Script**: A main script orchestrates the entire pipeline, from data loading to model evaluation.

## Usage
### 1. Clone the Repository
Clone the repository to your local machine:
```bash
git clone https://github.com/your-username/nmt-glove-translation.git
cd nmt-glove-translation
```

### 2. Install Dependencies
Install the required dependencies using pip:
```bash
pip install -r requirements.txt
```

### 3. Set File Paths
Set the file paths for the dataset and GloVe embeddings in the main script (`main.py`). The paths should point to the relevant dataset files and GloVe vectors.

### 4. Train the Model (Optional)
If you wish to retrain the model, execute the main script (`main.py`) to run the entire training pipeline:
```bash
python main.py
```

### 5. Run the Flask Web Application
To use the web interface for translation, run the Flask application:
```bash
python app.py
```
This will start a local web server. You can access the application in your browser at `http://127.0.0.1:5000/`.

### 6. Customize the Front-End
The repository includes a basic Flask web application (`app.py`) that serves the translation model. Users are encouraged to create their own front-end to interact with this backend. As long as your front-end sends a POST request with the sentence to be translated, it will be compatible with the Flask application provided.

## Contributing
Contributions to improve the model's performance, add new features, or enhance the web interface are welcome. Please open an issue to discuss proposed changes or submit a pull request with your modifications.

## Authors
- **Harish Ramaswamy**: Initial work on the project.

## Acknowledgements
- [Stanford NLP - GloVe Project](https://nlp.stanford.edu/projects/glove/): For providing the English GloVe embeddings used in this project. The GloVe project by Stanford NLP offers high-quality word vectors trained on large-scale text corpora.
- [Common Crawl](https://commoncrawl.org/): For providing the French GloVe embeddings sourced from the Common Crawl project. Common Crawl is an initiative that archives and makes accessible web data to support research and development in various fields.

## Note
This project is for educational purposes and experimentation. No license is applied, so feel free to use and modify the code as needed. However, proper attribution to the original authors is appreciated.
