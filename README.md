In Machine Learning and Data Science, **data preprocessing** is a crucial step that helps make your models more accurate and reliable. There are **many preprocessing techniques**, but they generally fall into **six major categories**:

---

## 🧠 1. **Data Cleaning**

Deals with inaccurate, incomplete, or inconsistent data.

* **Handling Missing Values**

  * Imputation (mean, median, mode)
  * Deletion (row-wise or column-wise)
  * Predictive imputation (KNN, regression)

* **Removing Duplicates**

* **Correcting Data Types**

* **Handling Outliers**

  * Z-score
  * IQR method
  * Clipping/winsorization

---

## 🧪 2. **Data Transformation**

Converts data into a suitable format or scale.

* **Scaling**

  * MinMaxScaler (0 to 1)
  * StandardScaler (mean=0, std=1)
  * RobustScaler (resistant to outliers)
  * MaxAbsScaler

* **Normalization**

  * L1/L2 normalization (for distance-based models like KNN/SVM)

* **Log / Power Transformations**

  * Log, Box-Cox, Yeo-Johnson (to make data more Gaussian)

---

## 🔤 3. **Encoding Categorical Variables**

Converts categories into numerical format.

* **Label Encoding**
* **One-Hot Encoding**
* **Ordinal Encoding**
* **Binary Encoding / Hashing / Target Encoding**

---

## 🧬 4. **Feature Engineering**

Creating or modifying features to improve model performance.

* **Feature Extraction**

  * PCA (Principal Component Analysis)
  * LDA (Linear Discriminant Analysis)
  * Kernel PCA
  * Autoencoders

* **Feature Selection**

  * Filter Methods (Chi-Square, ANOVA, correlation)
  * Wrapper Methods (RFE, Forward/Backward Selection)
  * Embedded Methods (Lasso, Tree importance)

* **Polynomial Features / Interaction Terms**

---

## 🔍 5. **Text & NLP Preprocessing**

Used for unstructured text data.

* Lowercasing
* Removing punctuation/stopwords
* Tokenization
* Stemming/Lemmatization
* TF-IDF / Bag of Words / Word Embeddings

---

## 🖼️ 6. **Image/Audio Preprocessing**

Used for computer vision and audio ML.

* Resizing / Rescaling
* Normalization (pixel values)
* Noise reduction
* Spectrogram conversion (for audio)

---

## ✅ BONUS: Data Splitting

Technically not a preprocessing step, but part of prep for ML.

* Train-Test Split
* Cross-Validation
* Stratified Splits

---

### 🧾 Summary Table

| Category                  | Techniques                                                   |
| ------------------------- | ------------------------------------------------------------ |
| Data Cleaning             | Missing values, outliers, data types, duplicates             |
| Data Transformation       | Scaling, normalization, log/power transforms                 |
| Encoding                  | Label, One-hot, Ordinal, Binary, Target encoding             |
| Feature Engineering       | PCA, LDA, Kernel PCA, Feature selection, Polynomial features |
| Text Preprocessing        | Tokenization, stemming, TF-IDF, embeddings                   |
| Image/Audio Preprocessing | Resizing, normalization, noise reduction                     |
| Splitting Data            | Train-test split, cross-validation                           |

---

