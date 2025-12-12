# 12-Week Machine Learning Reboot Plan
**Focus:** Time-Series Modeling on Noisy, Real-World Data  
**Target Roles:** Applied ML, Data Scientist, Research-Adjacent  
**Time Commitment:** ~10–12 hours/week

---

# Weeks 1–2: Foundations & Rust Removal

## Objectives
- Refresh Python and ML fundamentals
- Rebuild intuition around data, noise, and evaluation
- Avoid tutorial-driven learning

## Topics
- NumPy, Pandas
- Matplotlib, Seaborn
- scikit-learn
- Train/test split vs cross-validation
- Bias–variance tradeoff
- Regression metrics (MAE, RMSE)

## Tasks
- Load a long-horizon time-series dataset
- Handle missing data and outliers
- Visualize:
  - raw series
  - rolling averages
  - seasonal trends
- Document assumptions and surprises

## Deliverable
- Time-series exploratory data analysis notebook
- README describing data characteristics and limitations

---

# Weeks 3–4: Classical Time-Series Models

## Objectives
- Build interpretable baseline models
- Demonstrate understanding of dynamics and stationarity

## Topics
- Stationarity
- Autocorrelation (ACF) and partial autocorrelation (PACF)
- Moving averages
- ARIMA / SARIMA
- Forecast evaluation

## Tasks
- Implement naive baseline forecasts
- Fit ARIMA/SARIMA models
- Compare model predictions against held-out data
- Analyze model breakdowns

## Deliverable
- Statistical forecasting notebook
- README discussing assumptions and failure modes

---

# Weeks 5–6: Machine Learning for Time-Series

## Objectives
- Apply supervised ML to time-series data
- Demonstrate feature engineering skills

## Topics
- Lag features
- Rolling statistics
- Trend and seasonality features
- Time-series cross-validation
- Random Forest
- Gradient Boosting (XGBoost / LightGBM)

## Tasks
- Engineer features from raw time-series
- Train ML models using time-aware splits
- Compare ML models to classical baselines
- Evaluate accuracy vs interpretability tradeoffs

## Deliverable
- ML time-series modeling notebook
- README justifying feature and model choices

---

# Weeks 7–8: Neural Networks for Time-Series

## Objectives
- Demonstrate neural modeling competence
- Evaluate whether complexity is justified

## Topics
- Feedforward neural networks
- LSTM or GRU
- Overfitting diagnostics
- Early stopping

## Tools
- PyTorch or Keras

## Tasks
- Train a neural network on the same dataset
- Compare performance to ML and statistical models
- Analyze overfitting and data limitations

## Deliverable
- Neural time-series modeling notebook
- README discussing when neural models help or hurt

---

# Weeks 9–10: Capstone Integration

## Objectives
- Create a cohesive, end-to-end modeling project
- Emphasize reasoning and evaluation

## Capstone Structure
- Problem statement
- Data cleaning and preprocessing
- Baseline models
- Machine learning models
- Neural network models
- Evaluation methodology
- Limitations
- Future work

## Optional Enhancements
- Uncertainty estimation
- Anomaly detection
- Regime-shift detection
- Concept drift discussion

## Deliverable
- Polished capstone repository
- Reproducible results and clear narrative

---

# Weeks 11–12: Portfolio & Job Preparation

## Objectives
- Translate technical work into employable artifacts
- Begin job applications

## Tasks
- Polish READMEs and documentation
- Add MIT License
- Write a one-page project summary
- Update resume with modeling decisions and evaluation strategies
- Pin capstone repository on GitHub
- Start applying to roles

## Optional Bonus
- Streamlit or Flask demo app
- Short technical blog post

---

# Guiding Principle

> Simple models first.  
> Complex models only when justified.  
> Understanding failure modes beats chasing accuracy.
