# SPAM-SMS-DETECTION

This project focuses on the detection of spam messages in SMS communication. The aim is to develop a machine learning model capable of accurately distinguishing between legitimate (ham) and spam messages.

Interpretation of Metrics
Naive Bayes (NB)
Achieves high precision for both ham (97.90%) and spam (92.80%), demonstrating accurate classification. Balanced recall and F-score (92.90%, 97.90%, and 95.30%) indicate effective identification of instances in both classes.

K-Nearest Neighbors (KNN)

Shows moderate precision for ham (83.20%) and spam (82.60%), with balanced recall and F-score (83.80%, 82.10%, and 82.40%) reflecting a fair trade-off between precision and recall.

Logistic Regression (LR)

Exhibits high precision for both ham (97.50%) and spam (99.30%), along with balanced recall and F-score (99.40%, 97.20%, and 98.30%), showcasing accurate and well-rounded classification.

Random Forest Classifier (RFC)

Achieves high precision for ham (90.10%) and perfect precision for spam (100.00%), indicating low false positive rates. High recall for ham (100.00%) and moderate recall for spam (88.30%) result in balanced F-scores (94.80% and 93.80%), showcasing robust performance in both classes.

Suggestion for Final Model:

Considering the high precision and well-balanced performance, Logistic Regression (LR) emerges as a strong candidate for the final model, demonstrating accurate classification across both ham and spam instances.


<img width="561" alt="Screenshot 2024-02-14 at 5 35 34 PM" src="https://github.com/hannu-shaik/SPAM-SMS-DETECTION/assets/140539636/238d0e83-a35c-4201-8a8a-911642a0bd62"> 







<img width="291" alt="Screenshot 2024-02-14 at 5 35 19 PM" src="https://github.com/hannu-shaik/SPAM-SMS-DETECTION/assets/140539636/d45fb03a-a695-422b-9038-73b884b18224">




Conclusion
Through rigorous analysis and evaluation, the Logistic Regression model emerged as the most suitable for spam detection, demonstrating high accuracy, precision, and balanced performance across both ham and spam instances.

Acknowledgment
This project is created as a part of learning and exploration in machine learning and natural language processing techniques. The dataset used is publicly available and credited to its original sources.








