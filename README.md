# GenSize - Personalized Size Recommendation System

GenSize is an AI-powered size recommendation system that enhances online shopping by predicting the best fit for users based on body measurements and purchase history. This project aims to improve user satisfaction and reduce returns by providing accurate size recommendations.

- [PPT Link](https://drive.google.com/file/d/1JckQim3auUT8_nkg9yZgqGIdzh3TelRb/view?usp=sharing)

## Features

### 1. Data Collection & Clustering
- **Data Gathering**: Collects body measurements (height, weight, chest, waist, hip) and purchase history.
- **K-means Clustering**: Segments users into groups based on body type and fit preferences.
- **Standardization**: Ensures consistent sizing by standardizing measurements across brands.

### 2. Model Training & Prediction
- **Random Forest Models**: Trains predictive models for each cluster using historical data to suggest the most suitable size.
- **Confidence Scoring**: Uses Bayesian Inference to generate a confidence score, helping users make informed decisions on fit likelihood.

### 3. Continuous Improvement
- **Real-Time Feedback**: Adjusts size predictions dynamically based on user feedback.
- **Feedback Loop**: Analyzes returns and exchanges to refine model accuracy and improve recommendations.

## Performance Metrics
- **Training Accuracy**: 99.78% accuracy in initial model tests.
- **K-means & Bayesian Testing**: Achieved scores of 96% (K-means) and 82% (Bayesian).

## Deployment
Currently deployed locally using Ngrok and Vercel. CI/CD pipeline includes Docker and GitHub Actions, with plans for AWS deployment for scalability and improved performance.

## Repositories
- [Frontend Repository](https://github.com/raaahul1102/GenSize-frontend)
- [Backend Repository](https://github.com/raaahul1102/GenSize)


