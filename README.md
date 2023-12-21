# Classification Empirical Study with Textual Data 📊📝

## Overview 🚀
This repository contains the code and documentation for a classification empirical study on airline passenger reviews using deep learning approaches on textual data. The study involves tasks related to Natural Language Processing (NLP), including the creation of derived datasets, encoding text as input features, and evaluating models.

## Datasets 📂
The primary dataset used is the [Airline Passenger Reviews dataset](https://www.kaggle.com/datasets/malharkhatu/airline-passenger-reviews), which classifies passenger reviews into three classes (promoters, detractors, and passives). A reduced version with 10,761 samples is used.

### Derived Datasets 📑
1. **Derived-Dataset-1:** Subset of POS tags (lemmatized).
2. **Derived-Dataset-2:** Named entities + important POS tags (chosen based on exploration using spaCy).

## Tasks and Steps 📑

### 1. NLP Pipeline Tasks 🤖
- [ ] Explore NLP pipeline using spaCy.
- [ ] Create Derived-Dataset-1 with selected POS tags.
- [ ] Create Derived-Dataset-2 with named entities and chosen POS tags.

### 2. Classification Empirical Study 🧠
1. **Encode Text as Input Features:**
   - [ ] Utilize bag-of-words representation.
   - [ ] Remove stopwords and use tf-idf as the attribute value.

2. **Define Models:**
   - [ ] Logistic Regression Model (default parameters).
   - [ ] Multilayer Perceptron Model (default parameters).

3. **Train/Test/Evaluate Models:**
   - [ ] 4-fold cross-validation.
   - [ ] Evaluation with precision/recall measures (micro and macro averages).
   - [ ] Discuss class balance impact on results.

4. **Modify MLP Model Parameters:**
   - Experiment 1:
     - [ ] Change hidden layer size.
     - [ ] Modify activation function.
     - [ ] Adjust learning rate.

   - Experiment 2:
     - [ ] Change a different set of parameters.

5. **Analyze Results:**
   - [ ] Quantitatively compare 12 results.
   - [ ] Visualize results using tables.
   - [ ] Discuss differences in micro and macro averages.

### 3. Jupyter Notebook 📓
- [ ] Document the entire empirical study in a Jupyter Notebook.
- [ ] Include explanations, code, and results in separate cells.
- [ ] Follow logical cell separations for clarity.

## Technology Stack 🛠️
- **Python Packages:** scikit-learn, spaCy
- **Tools:** Jupyter Notebook, Kaggle for datasets

## Results and Discussion 📊
For detailed results and discussions, refer to the Jupyter Notebook.



