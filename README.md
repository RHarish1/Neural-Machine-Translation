**Title**: Neural Machine Translation with GloVe Embeddings

**Description**:
This repository contains Python code for a neural machine translation (NMT) model using pre-trained GloVe embeddings for English and French languages. The model is built using TensorFlow and Keras, and it translates English sentences to French.

**Features**:
- **Data Loading and Preprocessing**: Functions are provided to load a dataset containing English sentences and their corresponding French translations. The text is cleaned and tokenized for preprocessing.
- **GloVe Embeddings Integration**: The model integrates pre-trained GloVe word embeddings for English and French languages to enhance translation quality.
- **Bidirectional LSTM Architecture**: The NMT model utilizes a bidirectional LSTM architecture with attention mechanisms for sequence-to-sequence translation tasks.
- **Training and Evaluation**: The code includes functions to train the model on the training data, evaluate its performance on a separate test set, and calculate the BLEU score for translation quality assessment.
- **Main Runner Script**: A main script orchestrates the entire pipeline, from data loading to model evaluation.

**Usage**:
1. **Clone the Repository**: Clone the repository to your local machine.
2. **Install Dependencies**: Install the required dependencies using `pip install -r requirements.txt`.
3. **Set File Paths**: Set the file paths for the dataset and GloVe embeddings in the main script (`main.py`).
4. **Run the Main Script**: Execute the main script (`main.py`) to run the entire pipeline.

**Contributing**:
Contributions to improve the model's performance or add new features are welcome. Please open an issue to discuss proposed changes or submit a pull request with your modifications.

**Authors**:
- **Harish Ramaswamy**: Initial work on the project.

**Acknowledgements**:
- [Stanford NLP - GloVe Project](https://nlp.stanford.edu/projects/glove/): For providing the English GloVe embeddings used in this project. The GloVe project by Stanford NLP offers high-quality word vectors trained on large-scale text corpora.
- [Common Crawl](https://commoncrawl.org/): For providing the French GloVe embeddings sourced from the Common Crawl project. Common Crawl is an initiative that archives and makes accessible web data to support research and development in various fields.

**Note**:
This project is for educational purposes and experimentation. No license is applied, so feel free to use and modify the code as needed. However, proper attribution to the original authors is appreciated.
