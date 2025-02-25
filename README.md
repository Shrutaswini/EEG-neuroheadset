# 🧠 EEG Neuroheadset Eye State Prediction

## 🔍 Project Overview  
This project develops a **machine learning model** to predict whether a person’s **eyes are open or closed** based on **EEG (electroencephalography) signals** recorded from 14 different brain regions.  

## 🎯 Objectives  
- Process **EEG data** to extract meaningful insights.  
- Compare multiple **machine learning models** to determine the best classifier.  
- Evaluate performance using accuracy and other relevant metrics.  

📌 *Dataset:* Includes **14 EEG features** with a manually labeled eye state ('0' for open, '1' for closed).  

## 🧹 Data Preprocessing  
- **Standardization**: Used `StandardScaler` to normalize EEG signals for better model performance.  
- **Train-Test Split**: Split dataset into **80% training** and **20% testing** for fair model evaluation.  
- **Class Balance Check**: Verified that the dataset was relatively balanced (~55% closed, ~45% open).  

## 🔬 Model Comparisons & Performance  
### ✅ **Logistic Regression**  
- **Insights**: Struggled to capture complex EEG patterns due to its linear nature.  
- **Performance**: Limited effectiveness in distinguishing between eye states.  

### 🌳 **Random Forest Classifier**  
- **Insights**: Demonstrated **strong predictive accuracy** with EEG data.  
- **Performance Metrics**:  
  - **Accuracy:** High classification accuracy.  
  - **Feature Importance:** Certain EEG channels were more influential in predicting eye state.  

### 🤖 **Neural Networks (Future Work)**  
- Potential improvement using **deep learning** models such as LSTMs or CNNs for EEG signal classification.  

## 📊 Tech Stack  
- **Python**  
- **Pandas & NumPy** (Data manipulation & preprocessing)  
- **Scikit-learn** (Machine learning models)  
- **Matplotlib & Seaborn** (Data visualization)  

## 📌 How to Use  
1. Clone this repository:  
   ```bash
   git clone https://github.com/YOUR_USERNAME/eeg-neuroheadset.git
2. Install dependencies:
bash -
pip install pandas numpy scikit-learn matplotlib seaborn
3. Open and run the Jupyter Notebook to explore the analysis.

## 📜 License
This project is open-source and available under the MIT License.

