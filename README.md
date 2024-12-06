# Film review classification
### Solving the problem of classifying movie ratings into positive and negative using different algorithms.

### 1. The task:

The task is to perform sentiment analysis of movie reviews from the Internet Movie Database (IMDb).

### 2. Used frameworks and libraries:
- Google Colab
- Pandas
- Numpy
- NLTK
- Pytorch
- Transformers

### 3. Used models:
- Random Forest classifier
- Support Vector classifier
- DistilBERT for text classification

### 4. Workflow:
- Loading dataset (40,000 lines)
- Tokenization
- Deleting stopwords and punctuation
- Stemming
- Splitting into train and validation
-- BERT classification
- TF-IDF vectorization
-- Random Forest classification
-- Support Vector classification

### 5. Results:
- AUROC of Random Forest on validation: 0.825840
- Max AUROC of DistilBERT on validation: 0.937440
- AUROC of SVC on validation: 0.950542
