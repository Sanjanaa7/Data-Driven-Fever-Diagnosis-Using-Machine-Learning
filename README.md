__Data-Driven Fever Diagnosis: Using Machine Learning__

A machine learning-based diagnostic tool to predict whether a patient has **Dengue** or **Malaria** based on symptoms. Built using Python and trained on a real-world dataset, this project features an interactive UI powered by Gradio.

__Features__

- Predicts **Dengue** or **Malaria** from symptoms
- Trained using **Random Forest Classifier**
- Uses over 60 binary symptom inputs
- Built with an interactive UI using **Gradio**
- Displays prediction **confidence level**
- Accepts multiple symptom inputs at once

__Dataset__
  
- Training dataset: `trainn.csv`
- Each row represents a patient with binary symptoms (0 = No, 1 = Yes)
- Target column: `prognosis` (either "Dengue" or "Malaria")
- Total features: ~63 symptoms
- **Note:** The dataset used in this project was obtained from publicly available online sources and is **not my original work**. It is used here strictly for **educational and demonstrative purposes**.

 __Technologies Used__
  
- Python
 - Pandas, NumPy
- Scikit-learn
 - Gradio
- Jupyter Notebook

__How It Works__

- The user selects symptoms from a checklist.
- The trained model predicts the likely disease.
- The interface displays the result and confidence level.

__Installation__

```
1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/data-driven-fever-diagnosis.git
   cd data-driven-fever-diagnosis

2.Create a virtual environment (optional but recommended):

 python -m venv venv
 source venv/bin/activate  # For Linux/macOS
 venv\Scripts\activate     # For Windows

3.Install dependencies:

pip install -r requirements.txt

4.Run the notebook or Python script:

Use Jupyter Notebook to interactively run .ipynb

Or use python fever_diagnosis.py to launch the Gradio UI

```
__Usage__

This project is intended for educational and research purposes only. It is not a replacement for professional medical diagnosis. The data and model serve as a demonstration of applying ML in healthcare contexts.

__Acknowledgements__

Dataset: Publicly available online dataset on Dengue and Malaria symptoms

__Made With__

- Python
- Jupyter Notebook

__About Me__

Name: Sanjanaa S

Course: B.Tech Artificial Intelligence and Data Science

College: Rajalakshmi Institute of Technology

Year: 3rd Year

Email: sanjanaasrinivasan7@gmail.com

LinkedIn: www.linkedin.com/in/sanjanaa-srinivasan-802ba5290

GitHub: https://github.com/Sanjanaa7
```
