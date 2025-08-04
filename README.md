**AdVision: Advertising Campaign Success Predictor**
----> AdVision is a machine learning project designed to predict the success of advertising campaigns based on key input features such as campaign type, channel, target audience, location, cost, impressions, and engagement metrics. It enables marketing teams to make data-driven decisions before launching a campaign by estimating its likelihood of success.

💡 Project Objective
  |-->The main goal is to assist marketers in evaluating campaign performance using historical data and predictive modeling. With proper insights, companies can allocate budgets more effectively and optimize their outreach strategy.

🔍 Features
  |-->Predicts whether a campaign will be successful or not
  |-->User-friendly Gradio web interface for making predictions
  |-->Uses Random Forest model with optimized hyperparameters
  |-->Input validation and preprocessing handled within the pipeline
  |-->Interactive and easy-to-deploy solution

📊 Dataset
  |-->The dataset used was synthetic and tailored for marketing campaign analysis. It includes features such as:
      |-->Campaign_Type
      |-->Channel_Used
      |-->Target_Audience
      |-->Duration
      |-->ROI
      |-->Location
      |-->Language
      |-->Acquisition_Cost
      |-->Engagement_Score
      |-->Clicks, Impressions, Conversion_Rate, etc.

🧠 Machine Learning
 |-->The pipeline includes:
     |-->Data preprocessing (encoding categorical data, dropping irrelevant features)
     |-->Feature engineering
     |-->Model training using Random Forest and XGBoost
     |-->Hyperparameter tuning using RandomizedSearchCV
     |-->Evaluation with classification report and accuracy score
     |-->Final model saved as a .pkl file for deployment

🖥️ Gradio UI
 |-->A simple interface allows users to enter campaign details and receive predictions in real-time. Built using Gradio for lightweight deployment and easy user interaction.


🚀 How to Run
Clone this repository
Install dependencies:
pip install -r requirements.txt
Run notebook or execute app.py to launch the UI

📜 License
This project is licensed under the MIT License — see the LICENSE file for details.
