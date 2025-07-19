from docx import Document
from docx.shared import Inches

# Create a new Word document
doc = Document()
doc.add_heading('Common Data Preprocessing Techniques in Machine Learning and Data Science', 0)

doc.add_heading('1. Data Cleaning', level=1)
doc.add_paragraph("""
- Handling Missing Values:
  - Imputation (mean, median, mode)
  - Deletion (row-wise or column-wise)
  - Predictive imputation (KNN, regression)
- Removing Duplicates
- Correcting Data Types
- Handling Outliers (Z-score, IQR method, Clipping)
""")

doc.add_heading('2. Data Transformation', level=1)
doc.add_paragraph("""
- Scaling:
  - MinMaxScaler (0 to 1)
  - StandardScaler (mean=0, std=1)
  - RobustScaler (resistant to outliers)
  - MaxAbsScaler
- Normalization (L1/L2 normalization)
- Log / Power Transformations (Log, Box-Cox, Yeo-Johnson)
""")

doc.add_heading('3. Encoding Categorical Variables', level=1)
doc.add_paragraph("""
- Label Encoding
- One-Hot Encoding
- Ordinal Encoding
- Binary Encoding / Hashing / Target Encoding
""")

doc.add_heading('4. Feature Engineering', level=1)
doc.add_paragraph("""
- Feature Extraction:
  - PCA (Principal Component Analysis)
  - LDA (Linear Discriminant Analysis)
  - Kernel PCA, Autoencoders
- Feature Selection:
  - Filter Methods (Chi-Square, ANOVA, correlation)
  - Wrapper Methods (RFE, Forward/Backward Selection)
  - Embedded Methods (Lasso, Tree importance)
- Polynomial Features / Interaction Terms
""")

doc.add_heading('5. Text & NLP Preprocessing', level=1)
doc.add_paragraph("""
- Lowercasing
- Removing punctuation/stopwords
- Tokenization
- Stemming/Lemmatization
- TF-IDF / Bag of Words / Word Embeddings
""")

doc.add_heading('6. Image/Audio Preprocessing', level=1)
doc.add_paragraph("""
- Resizing / Rescaling
- Normalization (pixel values)
- Noise reduction
- Spectrogram conversion (for audio)
""")

doc.add_heading('7. Data Splitting (Bonus)', level=1)
doc.add_paragraph("""
- Train-Test Split
- Cross-Validation
- Stratified Splits
""")

# Save the document
output_path = "/mnt/data/Data_Preprocessing_Techniques.docx"
doc.save(output_path)

output_path
