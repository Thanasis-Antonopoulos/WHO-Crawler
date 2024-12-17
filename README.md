# WHO Coronavirus Data Crawler

This project crawls the official World Health Organization (WHO) website for information related to COVID-19. It extracts text data from relevant pages, preprocesses the data by tokenizing and filtering out stopwords, and then vectorizes the text using TF-IDF to analyze the most frequent and relevant terms.

## Dependencies

Before running the code, ensure you have the following libraries installed:

- `requests`
- `beautifulsoup4`
- `nltk`
- `scikit-learn`
- `lxml`

You can install these dependencies using pip:

```bash
pip install requests beautifulsoup4 nltk scikit-learn lxml
