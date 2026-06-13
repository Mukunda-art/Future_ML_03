# Resume / Candidate Screening System

## Project Overview

This project is a Machine Learning-based Resume Screening and Candidate Ranking System that automatically screens resumes and ranks candidates based on their match with a given job description.

The system uses Natural Language Processing (NLP) and TF-IDF similarity techniques to identify suitable candidates, extract skills, and detect missing skills.

---

## Features

* Resume text cleaning and preprocessing
* Skill extraction from resumes
* Job description matching
* Candidate ranking based on match score
* Missing skill identification
* Candidate score visualization
* Export ranked results to CSV

---

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Matplotlib

---

## Project Structure

```text
Resume-Screening-System/
│
├── resume_screening.py
├── candidate_ranking.csv
├── requirements.txt
├── README.md
└── output_graph.png
```

---

## Installation

Clone the repository:

```bash
git clone <repository_link>
cd Resume-Screening-System
```

Install dependencies:

```bash
pip install -r requirements.txt
```

---

## Run the Project

Execute:

```bash
python resume_screening.py
```

---

## Workflow

1. Load resumes and job description
2. Clean and preprocess resume text
3. Extract important skills
4. Convert text using TF-IDF
5. Calculate similarity scores
6. Rank candidates
7. Identify missing skills
8. Generate visualization

---

## Output

The project generates:

* Candidate ranking table
* Match score percentage
* Missing skills report
* Candidate ranking graph
* CSV export file

Example:

| Resume ID | Match Score (%) |
| --------- | --------------- |
| 1219      | 19.3            |
| 1763      | 18.5            |
| 1143      | 16.7            |

---

## Model Used

TF-IDF Vectorization + Cosine Similarity

---

## Future Enhancements

* Resume upload support (PDF/DOCX)
* Deep Learning-based ranking
* Web application using Flask
* Real-time resume screening
* Advanced NLP using spaCy

---

## Author

Mukunda

