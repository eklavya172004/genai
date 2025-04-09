# 🧠 Gen AI Learning Hub

![Banner Image](https://img.shields.io/badge/GenAI-Learning%20Repository-brightgreen?style=for-the-badge&logo=openai)

A curated collection of Natural Language Processing and Generative AI resources, notebooks, and projects to facilitate learning and experimentation in the field of AI.

## 📚 Repository Contents

This repository contains Jupyter notebooks covering essential concepts in NLP and Generative AI:

- **Tokenization** - Breaking text into meaningful units
- **Parts of Speech Tagging** - Identifying grammatical components of sentences
- **Stopwords** - Managing common words that typically don't contribute to meaning
- **Stemming and Lemmatization** - Reducing words to their root forms
- **Named Entity Recognition** - Identifying and classifying named entities in text
- **Machine Learning Applications** - Using ML techniques with NLP

## 🔍 Notebooks Overview

| Notebook | Description |
|----------|-------------|
| `tokenization.ipynb` | Text tokenization techniques and implementations |
| `partofspeech.ipynb` | Implementation of POS tagging using NLTK |
| `stopwords.ipynb` | Working with stopwords in NLP pipelines |
| `stemming.ipynb` | Word stemming and lemmatization techniques |
| `namedPostag.ipynb` | Named entity recognition and advanced POS analysis |

## 🛠️ Technologies Used

- **Python** - Primary programming language
- **NLTK** - Natural Language Toolkit for text processing
- **Jupyter** - Interactive computing and documentation

## 🚀 Getting Started

### Prerequisites

- Python 3.7+
- Pip package manager

### Installation

```bash
# Clone the repository
git clone https://github.com/eklavya172004/genai.git

# Navigate to the project directory
cd genai

# Create a virtual environment (optional)
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt

# Download NLTK data
python -c "import nltk; nltk.download('punkt'); nltk.download('stopwords'); nltk.download('averaged_perceptron_tagger'); nltk.download('maxent_ne_chunker'); nltk.download('words')"
```

## 📝 Usage

Simply open the Jupyter notebooks in your preferred environment:

```bash
jupyter notebook
```

Each notebook is self-contained with explanations, code examples, and outputs to help you understand the concepts.

## 📊 Examples

The notebooks include practical examples such as:

- Building a basic tokenizer
- Identifying parts of speech in text
- Extracting named entities from documents
- Creating pipelines for text processing

## 🔗 Resources

For additional learning resources on NLP and Generative AI:

- [NLTK Documentation](https://www.nltk.org/)
- [Stanford NLP Group](https://nlp.stanford.edu/)
- [Hugging Face](https://huggingface.co/)
- [Papers with Code - NLP](https://paperswithcode.com/area/nlp)

## 🤝 Contributing

Contributions are welcome! If you have improvements or additional notebooks to contribute:

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-notebook`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-notebook`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 👨‍💻 Author

- **Your Name** - [GitHub Profile](https://github.com/eklavya172004)

---

⭐ Star this repository if you find it helpful!

*Last Updated: April 2025*
