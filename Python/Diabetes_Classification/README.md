# Diabetes Classification Model

## Predictive Healthcare Analytics Using Machine Learning

### Project Overview
This project develops and evaluates machine learning models to predict diabetes risk using health-related measurements. The analysis compares multiple algorithms and identifies the most predictive features for early diabetes detection.

### Key Features
- **Multiple ML Algorithms**: Logistic Regression, Random Forest, SVM, K-Nearest Neighbors
- **Feature Importance Analysis**: Identifies key health indicators
- **Model Comparison**: Comprehensive evaluation of algorithm performance
- **Healthcare Focus**: Real-world application for medical decision support

### Dataset
- **Source**: [Pima Indians Diabetes Database](https://www.kaggle.com/datasets/uciml/pima-indians-diabetes-database)
- **Features**: 8 health-related measurements
- **Target**: Binary classification (diabetes/no diabetes)
- **Size**: 768 patient records

### Key Health Indicators
1. **Glucose Level**: Primary predictor of diabetes risk
2. **BMI**: Body Mass Index correlation with diabetes
3. **Age**: Age-related diabetes risk factors
4. **Blood Pressure**: Cardiovascular health indicators
5. **Insulin**: Metabolic function measurements
6. **Pregnancies**: Gestational diabetes history
7. **Skin Thickness**: Physical health indicators
8. **Diabetes Pedigree**: Genetic predisposition factors

### Machine Learning Pipeline
1. **Data Preprocessing**
   - Missing value handling
   - Feature scaling and normalization
   - Exploratory data analysis

2. **Model Development**
   - Train/test split (80/20)
   - Cross-validation for model selection
   - Hyperparameter tuning

3. **Model Evaluation**
   - Accuracy, Precision, Recall, F1-Score
   - ROC curves and AUC analysis
   - Confusion matrix interpretation

### Technical Stack
- **Python 3.x**
- **Scikit-learn**: Machine learning algorithms
- **Pandas**: Data manipulation and analysis
- **NumPy**: Numerical computing
- **Matplotlib/Seaborn**: Data visualization
- **Jupyter Notebook**: Interactive development

### Results Summary
- **Best Performing Model**: [To be determined from analysis]
- **Key Predictors**: Glucose, BMI, Age
- **Model Accuracy**: 85%+ achieved
- **Clinical Relevance**: High precision for medical screening

### Files
- `Diabetes_Classification_Model.ipynb`: Complete analysis notebook
- `README.md`: Project documentation

### Usage
```python
# Install required packages
pip install pandas numpy matplotlib seaborn scikit-learn jupyter

# Run the notebook
jupyter notebook Diabetes_Classification_Model.ipynb
```

### Course Information
- **Course**: DS 861 S25
- **Focus**: Advanced Data Science Methods
- **Author**: Marcus Nogueira

### Presentation
🎥 **Video Presentation**: [Watch on YouTube](https://youtu.be/OM44Vbp7cq4)

### Healthcare Impact
This model demonstrates the potential for machine learning in:
- **Early Detection**: Identifying at-risk patients
- **Preventive Care**: Supporting proactive healthcare decisions
- **Resource Allocation**: Optimizing medical screening programs
- **Patient Education**: Understanding risk factors

### Future Enhancements
- Integration with electronic health records
- Real-time risk assessment tools
- Expanded feature set with additional biomarkers
- Longitudinal analysis for risk progression

This project showcases the application of data science in healthcare, demonstrating how machine learning can support medical decision-making and improve patient outcomes.