# Crop Yield Prediction Using Machine Learning

## Project Overview
With climate variability and increasing demand for food, predicting crop yields has become critical for ensuring food security and optimizing agricultural planning.  
This project uses machine learning techniques to predict crop yield based on key environmental and soil parameters, enabling farmers and agricultural planners to make smarter, data-driven decisions.

Through comprehensive feature selection, statistical testing, and model evaluation, LightGBM was selected as the best-performing model with an R² score of 0.9561.  
The final model was deployed using Gradio, providing a simple, interactive platform for real-time yield predictions based on user-inputted farming conditions.

## Project Structure
- `/report/Final_Project_Report.docx` – Full detailed project report.
- `/data/raw_dataset.csv` – Raw agricultural dataset used for analysis and modeling.
- `/code/model_training.ipynb` – Python notebook containing data preprocessing, feature engineering, model training, evaluation, and Gradio deployment.

## Technologies and Libraries
- Python (Pandas, NumPy, Matplotlib, Seaborn)
- PyCaret (for automated model training and comparison)
- Scikit-learn (for feature selection and statistical testing)
- Gradio (for simple, interactive model deployment)

## Deployment
The trained LightGBM model is deployed using Gradio. Users can input environmental variables (such as crop type, temperature, humidity, and soil nutrients) and receive real-time yield predictions instantly through the web interface.

## Team Members
- Melbin Roy
- Arvin Jay Tambalong
- Steeve John Thomson
- Vishnu Mohan
- Santosh Kumar
- Ajay Kurmaiahgari

## Installation
To install all required libraries, run:

pip install -r requirements.txt
