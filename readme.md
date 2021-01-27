pip install requests[security] bs4 pandas numpy nltk matplotlib seaborn spacy networkx gensim pyLDAvis sklearn
python -m spacy download en_core_web_sm
python -m spacy download en
import nltk
nltk.download('averaged_perceptron_tagger')
nltk.download('stopwords')