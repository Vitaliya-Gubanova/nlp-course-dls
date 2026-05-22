# 🗣 NLP Course — Deep Learning School, ФПМИ МФТИ

Домашние задания второго семестра **Deep Learning School** (МФТИ).  
Тема семестра: **языковые модели и NLP**.

---

## 📋 Содержание

| № | Тема | Ноутбук | Ключевые концепции |
|---|------|---------|--------------------|
| 1 | Word Embeddings | [`hw_simple_embeddings.ipynb`](hw_simple_embeddings.ipynb) | Word2Vec, семантические пространства, косинусное сходство |
| 2 | Text Classification | [`hw_text_classification.ipynb`](hw_text_classification.ipynb) | Нейросетевая классификация, AG News (4 класса), токенизация, DataLoader |
| 3 | Language Modelling (LSTM) | [`hw_language_modelling.ipynb`](hw_language_modelling.ipynb) | LSTM, языковая модель на уровне слов, датасет IMDB |
| 4 | Attention & Transformers | [`hw_attention_transformers.ipynb`](hw_attention_transformers.ipynb) | Self-attention, Transformer, классификация математических задач |
| 5 | RAG | [`hw_rag.ipynb`](hw_rag.ipynb) | Retrieval-Augmented Generation, FAISS, LangChain, HuggingFace, sentence-transformers |
| 6 | Bot Detection | [`hw_bot_detection.ipynb`](hw_bot_detection.ipynb) | Feature engineering, TF-IDF, CatBoost + LightGBM + ruBERT, стекинг ансамбль |

---

## 🔍 Краткое описание задач

### 1 · Word Embeddings
Изучение семантических представлений слов: векторные пространства, аналогии, визуализация через t-SNE.

### 2 · Text Classification
Классификация новостей **AG News** на 4 категории (World / Sports / Business / Sci-Tech) с помощью нейронной сети, построенной с нуля на PyTorch. Задача — добиться максимального качества на тестовой выборке.

### 3 · Language Modelling (LSTM)
Обучение **языковой модели на уровне слов** с помощью LSTM на корпусе отзывов IMDB. Генерация текста с заданной начальной фразой.

### 4 · Attention & Transformers
Реализация механизма **self-attention** и классификация математических задач по темам (многоклассовая классификация) с помощью Transformer. Датасет — математические задачи из разных областей.

### 5 · RAG (Retrieval-Augmented Generation)
Построение туристического RAG-чат-бота. Данные — достопримечательности с описаниями из WikiData. Векторное хранилище на **FAISS**, ретривер на **sentence-transformers**, генерация через **HuggingFace** модели. EDA + визуализация с помощью UMAP.

### 6 · Bot Detection
Детектор ботов в диалогах. **Часть 1:** признаковая инженерия (длина сообщений, энтропия, jailbreak-маркеры, TF-IDF на n-граммах), стекинг из CatBoost и LightGBM. **Часть 2:** fine-tuning **DeepPavlov/rubert-base-cased**. Финальный ансамбль с взвешенным голосованием.

---

## 🛠 Технологии

`Python` · `PyTorch` · `HuggingFace Transformers` · `FAISS` · `LangChain` · `sentence-transformers` · `CatBoost` · `LightGBM` · `scikit-learn` · `NLTK` · `Pandas` · `NumPy` · `Matplotlib` · `UMAP`

---

## 📁 Структура репозитория

```
nlp-course-dls/
├── hw_simple_embeddings.ipynb
├── hw_text_classification.ipynb
├── hw_language_modelling.ipynb
├── hw_attention_transformers.ipynb
├── hw_rag.ipynb
├── hw_bot_detection.ipynb
└── README.md
```

---

*Курс проводится ФПМИ МФТИ в рамках программы Deep Learning School.*
