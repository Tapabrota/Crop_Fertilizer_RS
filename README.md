# Crop and Fertilizer Recommendation System using Machine Learning

## Project Overview
This project aims to **recommend the most suitable crop and fertilizer** based on soil and environmental conditions. Using **machine learning models**, we analyze key agricultural parameters to provide data-driven recommendations that optimize crop yield and resource utilization.

## Learning Objectives
- Understand the **importance of soil nutrients and weather conditions** in agriculture.
- Apply **machine learning algorithms** for crop and fertilizer recommendations.
- Work with real-world agricultural datasets.
- Implement a predictive model and evaluate its performance.
- Gain hands-on experience with **Python, Pandas, Scikit-learn, and Flask**.

## Problem Statement
Farmers often struggle with selecting the best crops and fertilizers for their land due to **insufficient soil analysis and unpredictable climate changes**. This project addresses this challenge by using **machine learning models** to predict suitable crops and fertilizers based on soil and weather conditions.

## Tools and Technologies Used
- **Programming Language:** Python
- **Libraries:** Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn
- **Modeling:** Decision Tree, Random Forest, Logistic Regression
- **Dataset:** `crop_recommendation.csv`, `fertilizer_recommendation.csv`
- **Framework:** Flask (for web application)
- **Deployment:** Streamlit / Flask Web App (optional)

## Dataset Description
### 1. Crop Recommendation Dataset
Contains **soil and weather parameters** with a labeled column indicating the best crop.
- **Features:** N, P, K, temperature, humidity, pH, rainfall
- **Target Label:** Crop name (e.g., rice, wheat, maize, etc.)

### 2. Fertilizer Recommendation Dataset
Contains **nutrient levels, soil type, and crop type** with corresponding fertilizer recommendations.
- **Features:** N, P, K, temperature, humidity, moisture, soil type, crop type
- **Target Label:** Fertilizer name

## Methodology
1. **Data Preprocessing**
   - Load datasets and handle missing values (if any).
   - Normalize numerical values for better model performance.
2. **Exploratory Data Analysis (EDA)**
   - Visualize relationships between **nutrients and crop yield**.
   - Identify patterns using **histograms, scatter plots, and heatmaps**.
3. **Model Selection & Training**
   - Train **classification models** like Decision Tree, Random Forest, and Logistic Regression.
   - Use **accuracy and confusion matrix** to evaluate models.
4. **Prediction System**
   - Take input values (N, P, K, temperature, etc.) and predict the best crop/fertilizer.
   - Provide insights and recommendations.
5. **Web Application (Optional Deployment)**
   - Create a simple UI using Flask/Streamlit for user interaction.

## Screenshot of Solution
_(Add relevant screenshots of your code, EDA, model accuracy, and web interface here)_

## Output
- The system predicts the most suitable crop and fertilizer based on given inputs.
- Example Output:
  ```
  Recommended Crop: Rice
  Suggested Fertilizer: Urea
  ```

## Conclusion
- **Improves decision-making** for farmers using AI-driven recommendations.
- **Enhances crop productivity** by considering soil nutrients and weather conditions.
- **Can be expanded** to include real-time weather updates and IoT sensor data for **real-world deployment**.

## Future Scope
- Integrate **IoT sensors** for real-time soil data collection.
- Deploy as a **mobile-friendly web app** for farmer accessibility.
- Improve model accuracy with **advanced deep learning techniques**.

## How to Run the Project
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/crop-fertilizer-recommendation.git
   cd crop-fertilizer-recommendation
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the script:
   ```bash
   python main.py
   ```
4. (Optional) Run the web app:
   ```bash
   streamlit run app.py
   ```

## Contributors
- **TAPABROTA CHANGDER** - AI/ML Developer

## Contributing 
Contributions are welcome! Please fork the repository and submit a pull request with your changes.

## License
This project is licensed under the **MIT License**.
