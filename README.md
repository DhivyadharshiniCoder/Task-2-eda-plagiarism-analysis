# 📘 Task 2 – Exploratory Data Analysis on Plagiarism Detection Results

This repository contains my submission for **Task 2** of the **AI & ML Internship (June 2025)**.

---

## 🎯 Objective

To perform **Exploratory Data Analysis (EDA)** on the results obtained from the semantic plagiarism checker built in Task 1. The analysis focuses on understanding sentence similarity scores and identifying patterns of plagiarism.

---

## 📊 Dataset Used

- **Input File**: `similarity_output.csv`  
  (Generated in Task 1 using Sentence-BERT model)

### 📁 Columns:
- `Sentence_File1`: Sentence from the first document
- `Sentence_File2`: Most similar sentence from the second document
- `Similarity_Score`: Cosine similarity between the two sentences

---

## 📈 EDA Highlights

1. **Distribution of Similarity Scores**
   - Visualized using histograms
   - Identifies range and density of sentence similarities

2. **Threshold Analysis**
   - Compared plagiarism detection at 0.75 vs 0.6 thresholds
   - Showed how more paraphrased content is flagged at lower thresholds

3. **Plagiarism Count**
   - Count of sentence pairs exceeding threshold
   - Calculated percentage of plagiarised matches

---

## 🔧 Technologies Used

- Python
- Pandas
- Matplotlib
- Seaborn
- Google Colab

---

## 📁 Files Included

| File Name                | Description                              |
|-------------------------|------------------------------------------|
| `similarity_output.csv` | Input file generated from Task 1         |
| `eda_plagiarism.ipynb`  | Jupyter Notebook with full EDA process   |
| `README.md`             | This file                                |

---

## ✅ Task Status

✅ **Task 2 completed successfully**  
📊 Ready for model tuning, deployment or further analytics in Task 3
