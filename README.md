# Text Summarizer App

## Installation

### Pour le développement local :
```bash
pip install -r requirements_local.txt
python -m spacy download fr_core_news_sm
python -m spacy download en_core_web_sm
python -m spacy download de_core_news_sm
python -m spacy download es_core_news_sm
```

### Pour le déploiement :
Le fichier `requirements.txt` est configuré spécifiquement pour Streamlit Cloud.

## Lancement local
```bash
streamlit run app.py
```
