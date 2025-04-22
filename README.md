# Plant_based_water_needs_202401100300205
# 🌿 Plant Water Needs Classification

This project predicts the water requirement of plants based on their environmental preferences using a Naive Bayes classifier.

---

## 📁 Dataset

The dataset used (`plants.csv`) contains the following features:

- `sunlight_hours`: Number of hours of sunlight the plant receives
- `watering_freq_per_week`: How often the plant is watered per week
- `soil_type`: Type of soil
- `water_need`: Target variable (Low, Medium, High)

---

## 🧠 Model Used

- **Naive Bayes Classifier** (GaussianNB)

This model is suitable for categorical and continuous features and performs well with smaller datasets.

---

## 🛠️ Steps Involved

1. Load the dataset using `pandas`
2. Encode categorical features with `LabelEncoder`
3. Split the data into training and test sets (80/20)
4. Train the Naive Bayes classifier
5. Predict and evaluate performance
6. Visualize results:
   - Confusion matrix
   - Class distribution

---

## 📊 Output

### Classification Report

Shows precision, recall, F1-score, and support for each water need class.

### Graphs

- **Confusion Matrix**: Visualizes prediction accuracy across classes
- **Class Distribution**: Shows how balanced the dataset is

---

## 🚀 How to Run

1. Clone or download this repository
2. Ensure the dataset file is named `plants.csv`
3. Run the Python script:

```bash
python classify_plants.py
