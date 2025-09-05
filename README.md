# Hi there, I'm Seong Jun Chang 👋

🎓 I graduated with a Bachelor's degree in Applied Statistics from Dankook University.
📊 I'm passionate about statistics and data science, and I'm aiming to become a data scientist.

## 🛠️ Tech Stack

- 💻 **Languages**: 
  - ![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
  - ![R](https://img.shields.io/badge/R-276DC3?style=flat&logo=r&logoColor=white)
- 🌐 **Web Development**: 
  - ![HTML](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
  - ![CSS](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)
- 📊 **Data Analysis**: 
  - ![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat&logo=pandas&logoColor=white)
  - ![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat&logo=numpy&logoColor=white)
- 📚 **Machine Learning**: 
  - ![scikit-learn](https://img.shields.io/badge/scikit--learn-F7931E?style=flat&logo=scikit-learn&logoColor=white)
  - ![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat&logo=tensorflow&logoColor=white)
  - ![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white)
- 🛢️ **Databases**: 
  - ![SQL](https://img.shields.io/badge/SQL-336791?style=flat&logo=sql&logoColor=white)
  - ![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat&logo=mysql&logoColor=white)

## 💼 Projects

### [MBTI-based Personalized Media Content Recommendation Service](https://github.com/MVTI-MovieAndVideo-Recommender-Platform)
This project leverages MBTI characteristics to provide personalized media content recommendations. I was responsible for data analysis and implementing the recommendation system.

**Project Highlights**:
- **Data Collection and Preprocessing**: Collected VOD content data from WatchaPedia and MBTI data from various sources, then preprocessed the data for analysis.
- **Exploratory Data Analysis (EDA)**: Visualized genre distribution, rating distribution, production countries, and OTT platform distribution to understand the data better.
- **Text Embedding**: Used LaBSE to embed both Korean content descriptions and English MBTI posts into the same vector space.
- **Clustering**: Applied K-means clustering to group similar content based on descriptions, determining the optimal number of clusters using the Elbow method and Silhouette score.
- **Cosine Similarity Matching**: Calculated cosine similarity between content embeddings and MBTI embeddings to find the most relevant content for each MBTI type.
- **Visualization**: Visualized the embeddings and clustering results using UMAP to illustrate the relationship between MBTI types and content.
- **Recommendation System**: Developed a hybrid recommendation system combining MBTI-based embeddings, content similarity, and Gradient Boosting Machine (GBM) predictions to provide personalized recommendations.
- **Evaluation**: Evaluated the recommendation system using NDCG@k, achieving a mean NDCG@20 score of 0.6206.

### [Multi-Strategy Stock Trading Analysis](https://github.com/SEON97UN/multi-strategy_stock_trading_analysis)
This project implements and compares multiple systematic trading strategies using financial time series data. It integrates factor models, momentum/mean reversion, statistical arbitrage, and machine learning/deep learning models within a unified backtesting and evaluation framework.

**Project Highlights**:
- **Five Quantitative Strategies**:
  - Factor Model (PCA-based factor extraction)
  - Momentum & Mean Reversion (technical indicator signals)
  - Statistical Arbitrage (pair trading with spread reversion)
  - Machine Learning (Random Forest, XGBoost classification)
  - Deep Learning (LSTM with Attention Mechanism)
- **Backtesting and Walk-forward Validation**: Evaluates strategy performance using cumulative return, Sharpe ratio, maximum drawdown, and other key metrics.
- **Interactive Streamlit Dashboard**: Provides user-friendly strategy testing, visualization, and model diagnostics.
- **Model Diagnostics**: Includes feature importance, confusion matrix, classification report, and attention-based interpretability for deep learning models.
- **Portfolio Risk Management**: Supports position sizing, signal thresholding, and parameter optimization.

> This project demonstrates my ability to apply data science techniques to financial market analysis, combining quantitative modeling, machine learning, and deep learning approaches for systematic trading strategy development.


## 🏆 GitHub Stats

![Seongjun Chang's GitHub stats](https://github-readme-stats.vercel.app/api?username=SEON97UN&show_icons=true&theme=radical)
![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=SEON97UN&layout=compact&theme=radical)


## 🌐 Connect with me
- [Email](mailto:sjchang.stats@gmail.com)

<!---
SEON97UN/SEON97UN is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
