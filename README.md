# E-commerce-Customer-Churn-Prediction

## 1. Business Problem

The primary challenge facing our company is the high churn rate among our customer base. Out of a total of 5,630 active customers, 948 customers (16.83%) have chosen to discontinue their engagement with our platform. This elevated churn rate significantly impacts our operations in two critical ways:

1. Financial Implications: The departure of nearly 17% of active customers directly affects our revenue stream.Each customer holds considerable financial value for the company, making this loss a significant concern.

2. Brand Image and Perception: Beyond financial concerns, high churn rates can tarnish our brand's image. The sustainability of our business isn't solely tied to revenue but also hinges on how customers and the public perceive our brand. Elevated churn rates may raise doubts about our product quality and services, potentially impacting our reputation.

Addressing this churn issue is crucial for our business to retain our existing customer base and fortify our brand's standing in the market.

## 2. Solution Strategy

My approach to tackle this issue involves crafting a data-driven solution—an E-commerce customer churn prediction system. This project will feature a sophisticated machine learning model designed to forecast whether a customer is likely to churn or remain engaged with the platform.

1. EDA, Insights & Visualization:  Exploratory Data Analysis (EDA) encompasses descriptive statistics, univariate, and multivariate analysis techniques. It aims to comprehend the dataset by exploring its characteristics. Through analysis and visualization, EDA aims to uncover valuable business insights within the data.
2. Data Pre-Processing: Data preprocessing is a critical step in preparing raw data for machine learning models. It involves several tasks aimed at cleaning, transforming, and organizing the data to make it suitable for analysis or modeling.
3. Machine Learning Modelling & Evaluation: The process begins with splitting the dataset into training and testing sets. The training set is used to teach the model patterns and relationships within the data. Algorithms are then implemented to train the model based on this data, utilizing various methods taught or relevant to the problem at hand.
4. Business Insight and Recommendation: Business insights involve understanding and interpreting data to gain valuable knowledge about various aspects of a business. This understanding can be used to make informed decisions, identify opportunities, and address challenges.

## 3. Top 3 Insights

![download](https://github.com/muhfahmiamiq/E-commerce-Customer-Churn-Prediction/assets/148199919/c2906159-2886-4d1b-8026-2d3ee6429b3d)
Customer dengan Tenure rendah (kurang dari 2 bulan) memiliki potensi churn jauh lebih tinggi daripada tenure menengah keatas. Terlihat dalam grafik tenure 0-1 bulan memiliki persentase churn yang paling tinggi sebesar 53,5%.Tenure 1-2 bulan memiliki persentase churn yang tinggi juga sebesar 50,6%. Sedangkan Tenure yang lebih dari 2 bulan memiliki sampai 21 bulan memiliki rata-rata sekitar 7,6%.

![Screenshot 2023-12-04 170254](https://github.com/muhfahmiamiq/E-commerce-Customer-Churn-Prediction/assets/148199919/96c39bc5-f37a-482d-9607-f95c587f0448)
Persentase churn akibat customer complain (31.67%) hampir 3 kali lebih besar dari persentase churn dari total customer yang tidak complain (10.93%)

![Screenshot 2023-12-04 170327](https://github.com/muhfahmiamiq/E-commerce-Customer-Churn-Prediction/assets/148199919/6cc8ad8b-701b-4be6-9ea2-5218d807b463)
Customer yang mengorder kategori Mobile Phone dan Phone cenderung untuk churn dibandingkan dengan customer yang mengorder kategori lainnya.

## 4. Machine Learning Modelling & Evaluation

![Screenshot 2023-12-04 230720](https://github.com/muhfahmiamiq/E-commerce-Customer-Churn-Prediction/assets/148199919/128d63c8-8629-4a19-bede-d373de2f98de)
XGBOOST is the selected model because The XGBoost model is the most superior. XGBClassifier shows consistency high performance in both metrics evaluation used.

## 5. Business Insight and Recommendation

![Screenshot 2023-12-04 231931](https://github.com/muhfahmiamiq/E-commerce-Customer-Churn-Prediction/assets/148199919/0d322e56-9d58-48f7-a386-06e71d3c858c)
Recommendation:
1. Tenure: Providing promotional vouchers for new customers (For the first 2 months).
2. Marital Status_Single: Create marketing campaigns that focus more on freedom, flexibility, and individual experiences.
3. Complain: Pay attention to complaint trends and provide quick solutions, Feedback system
4. Preferred Order Category: Special offers for specific laptop & accessory categories, increased provision of products or services in these categories.
