## 👋 Hey, I'm Rome!

A Physics graduate with hands-on experience in data analysis, experimental design, and equipment management. As a former science laboratory technician, I am experienced in preparing and calibrating scientific instruments, analyzing complex data sets, and supporting research projects. Possesses solid foundational skills in statistical analysis, computational methods, and data handling.

I also love frozen yoghurt.

---

### 🚀 Skills & Technologies:

**Programming**: Python, SQL

**AI/ML Frameworks & Libraries**: TensorFlow, PyTorch, scikit-learn, NLTK, spaCy, TextBlob

**Data Analysis**: Pandas, NumPy, Matplotlib, Seaborn

**Databases**: Oracle SQL Developer, MongoDB

**MLOps**: GitHub

**Development Environments**: Jupyter Notebooks, Google Colab

---

### 📖 Education & Certifications: 
- **MSc Data Science & Artificial Intelligence** (current)

- **BSc (Honours) Physics** (First-class)

- **NCFE Level 2 Certificate in Principles of Business Administration**
o	Professional communication, workplace etiquette, teamwork, and organisational awareness

- **IBM Data Science Professional Certificate**
o	Used Python, R, SQL and Git for data analysis, machine learning, and version control. 
o	Applied CRISP-DM methodology for end-to-end data science projects, including EDA, data wrangling, model building, and visualisation using Jupyter Notebooks.

---
### 📌 Projects:
Here are some of my favourite projects:

### 1. [Identification of Fake Product Reviews](https://github.com/rdelmo/Identification-of-Fake-Product-Reviews)
- **Problem:** It is difficult for us humans to distinguish fake reviews from genuine reviews hence the need for assistance using artificial intelligence; this project aims to deploy intelligent systems to accurately identify fake reviews.
- **Approach:** NLP techniques extracted linguistic, behavioural, and sentiment features from reviews. Using 44,000 labelled reviews, traditional supervised machine learning approach was adopted (LR, NB, DT, SVM, RF, AdaBoost, KNN, and Stacking).
- **Impact:** AdaBoost was identified as the optimal model; when hyperparameter-tuned, it achieved 82% accuracy and 91% ROC AUC on the test set. This means the model effectively distinguished between real and fake reviews.
- **Skills:** `NLP (Text Preprocessing, Tokenization, Sentiment Analysis, Feature Extraction)`, `Machine Learning (Ensemble Modeling, Hyperparameter Tuning, Model Evaluation)`, `Python`, `EDA`

### 2. [Automatic Number Plate Recognition under Foggy Conditions](https://github.com/rdelmo/Automatic-Number-Plate-Recognition-under-Foggy-Conditions)
- **Problem:** A limitation of ANPR is due to the environmental factor of poor weather conditions; this project uses computer vision techniques to improve number plate detection in fog
- **Approach:** Plate Detection: locating the rectangular region containing the license plate within the image; used a pre-trained Haar Cascade Classifier; performed Transfer Learning with ResNet50, improved via freezing and hyperparameter-tuning, evaluated model accuracy using average IoU (Intersection over Union)
- **Impact:** Average IoU for clear images was 0.69, whereas 0.71 for foggy images. Areas for improvement are outlined in the notebook.
* **Skills:** `Image Processing`, `Data Augmentation`, `Object Detection`, `PyTorch`, `OpenCV`
