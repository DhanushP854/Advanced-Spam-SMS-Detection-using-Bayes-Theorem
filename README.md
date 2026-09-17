Advanced Spam SMS Detection using Bayes' Theorem

(Advanced Mathematics Course Project | Explainable AI | Natural Language Processing | Machine Learning)

- An advanced Spam SMS Detection system developed by extending my B.Tech minor project into a more mathematically explainable Machine Learning application. The project combines Bayes' Theorem, Multinomial Naive Bayes, TF-IDF vectorization, and Explainable AI techniques to classify SMS messages as Spam or Ham while providing interpretable confidence metrics and visual analytics.

**Project Overview**

- Unlike a basic spam classifier, this project focuses on the mathematical reasoning behind predictions. Instead of only displaying whether a message is spam, it explains why the prediction was made using Bayesian probabilities, entropy, influential-word analysis, and confidence visualizations.
- Model Accuracy: 98.56%
- The project is named as An advanced Spam SMS Detection system. But it would also works for Emails (replacing the dataset with an email corpus), Social Media Message Filtering, Enterprise Communication Filtering, etc.

**Features:**

- SMS Spam/Ham classification using Multinomial Naive Bayes
- TF-IDF feature extraction for text representation
- Bayesian posterior probability calculation
- Prior and posterior probability analysis
- Entropy-based prediction confidence
- Log-likelihood computation
- Explainable AI through influential-word analysis
- Four analytical visualizations for every prediction

**Mathematical Foundation:**

This project is built around several core mathematical concepts.

1. Bayes' Theorem: The classifier predicts the probability of a message belonging to either Spam or Ham.
Where:
C = Spam or Ham
X = Input SMS message
P(C) = Prior probability
P(C∣X) = Posterior probability

2. Prior Probability: The prior probabilities are calculated directly from the dataset.
	​
3. TF-IDF Vectorization: Text messages are converted into numerical vectors using TF-IDF. This gives higher importance to informative words while reducing the impact of frequently occurring words.

4. Multinomial Naive Bayes: The classifier assumes that words contribute independently to the final probability.

5. Laplace Smoothing: To prevent zero probabilities for unseen words.
	​
6. Log-Likelihood: The model performs calculations in logarithmic space.

7. Information Entropy: Prediction uncertainty is measured using entropy. Lower entropy indicates higher confidence.

**System Workflow**

*Technologies Used*

Category: Advanced Mathematics and ML
Tool: Used Python IDLE and also tested in Google Collab.
Language: Python
Data Processing: Pandas, Numerical Computing, NumPy, Machine Learning, Scikit-learn, NLP, TF-IDF

Classifiers: Multinomial Naive Bayes
Visualization: Matplotlib

**Project Output:** For every SMS entered, the system displays:
- Spam or Ham prediction
- Posterior probabilities
- Prior probabilities
- Confidence score
- Entropy value
- Log-posterior scores

**Four analytical visualizations:**
- Visualization Dashboard

  - Bayesian Posterior Probability: Shows the final probability assigned to Ham and Spam.
  - Bayesian Confidence Gauge: Displays prediction confidence on a 0–100% scale.
  - Top Influential Words: Highlights the words that contributed most to the decision.
  - Bayesian Decision Metrics: Combines confidence, priors, posterior strength, and certainty.

**Sample Prediction:**

Example: Message: You won an iPhone
Prediction: Spam
Spam Probability: 51.55%
Ham Probability: 48.45%

- The system also explains the prediction mathematically using posterior probabilities, entropy, and influential-word contributions.

Project Structure
Advanced-Spam-SMS-Detection/
│── ADVANCED_SPAM_SMS_DETECTION_USING_BAYES_THEOREM.ipynb
│── advanced_spam_sms_detection_using_bayes_theorem.py
│── CODE.txt
│── README.md
│── images/
│    ├── Bayesian Posterior Probability.png
│    ├── Bayesian Decision Confidence Gauge.png
│    ├── Influential Words used in prediction.png
│    ├── Bayesian Decision Metrics.png
│    └── Sample Output.png

**Future Improvements:**
- Web deployment using Flask or Streamlit
- Multilingual spam detection
- Comparison with SVM, Random Forest, and Transformer models
- SHAP and LIME for advanced explainability

Author
- Dhanush P
- MTECH (1ST YEAR)

Electronics and Communication Engineering | Machine Learning | Data Science | NLP
