# Data Scientist
M.Tech(Computer Science) Post graduate with 5+ Years hands on experience in Data Science & SAP ABAP technologies which involved in solving complex business problems by leveraging AI & ML. Focus areas include CRM , OCR & Healthcare Technologies.

#### Technical Skills
- Python (Programming Language)
- Machine Learning
- TensorFlow
- Data Visualization
- Natural Language Processing
- Convolutional Neural Network
- SQL
- SAP ABAP

## Education

- **[PG Diploma in Artificial Intelligence & Machine Learning](https://www.edureka.co/my-certificate/9306fd037be6f530791ae57d286e0aef)**  
  NIT Warangal jointly with Edureka  
  (2022)

- **[M.Tech in Computer Science]()**  
  Malla Reddy College of Engineering  
  (2017)
  
## Work Experience

**Data Scientist @ Cognier Insights Private Limited (May 2021 - Present)**
- Developed CNN LSTM Model for converting hand-written text into machine-encoded (Digital) text.
- Developed a customer churn prediction model for a General Insurance company using ensemble ML modelling techniques.
- Developed an ML model for forecasting high-demand periods for cab bookings based on climatic conditions.

**Software Developer @ Appsian Tech Pvt Ltd (May 2019 - April 2021)**
- Analyzed requirements & developed objects based on customer use cases.
- Prepared Technical design documents & implemented code as per approval.
- Debugged SAP programs & implemented logic enhancements.
- Conducted performance grading & testing of ABAP/4 programs & reports.

# Projects

### CNN LSTM Model for Converting hand-written text into machine-encoded (Digital) text in the Optical Character Recognition (OCR) domain
[Publication](https://www.mdpi.com/1424-8220/22/8/3048)
- Developed Hand Written character Recognition model for a medical Company, Business wants to convert handwritten doctor prescriptions & retrieve the text from it. Manually also this can be possible but it takes lot of time so client wants to automate this task, Hence, we have created neural network model that took images as input, it reads the text images & Converts into digital text. To solve this we needed CNN LSTM model.

![Hand Written character Recognition](/assets/img/OCR.jpg)

### [Customer churn prediction model for a General Insurance company using ensemble Machine Learning modelling techniques in the Customer Relationship Management (CRM) domain](https://github.com/ChandraKanth-datascience/Magma-HDI-General-Insurance)
- A General Insurance Company, they want to findout the customers who are likely to churn and with this action what would be the impact on the entire business and to take the proactive retention measures to save the business by targeting the likely churn customers.

5)Model Building - Artificial Neural Network (ANN):
Built an ANN using Keras with input, hidden, and output layers.
Compiled the ANN with 'adam' optimizer and 'binary_crossentropy' loss function.
Trained the ANN for a specified number of epochs and batch size.
Made predictions on the test set and evaluated results using confusion matrix and accuracy score.

6)Model Evaluation:
Evaluated models using metrics like accuracy, precision, recall, and F1-score.
Plotted ROC curves for training and testing datasets to visualize performance.

7)Hyperparameter Tuning:
Performed hyperparameter tuning to optimize the model.
Tested different thresholds to adjust model sensitivity and specificity.
Re-evaluated model performance using accuracy and confusion matrix after adjusting thresholds.

8)Comparative Analysis with Other Models:
Trained and evaluated other models including Logistic Regression, Decision Tree, K-Neighbors Classifier, and Gaussian Naive Bayes.
Compared the performance of each model based on accuracy and ROC AUC scores to identify the best performing model.

9)Performed Data Visualization:
Visualized model performance metrics using plots and tables.
Generated confusion matrices, ROC curves, and classification reports to summarize findings.
  
![Customer Churn Prediction](/assets/img/Customer_Churn.png)

### [Forecasting cab booking demand using ensemble Machine Learning modelling techniques in the Transportation and Logistics domain](https://github.com/ChandraKanth-datascience/Lyft)
- Historical data on cab bookings, including timestamps, locations, and other relevant factors such as weather conditions, events, and holidays has been collected.
- The collected raw data has been cleaned and preprocessed, including handling missing values, and engineering relevant features such as time of day, day of the week, and seasonality.
- Initially we thought the data might be seasonal so we have gone with appropriate time series forecasting models such as Arima(autoregressive integrated moving average), SARIMA(Seasonal Auto-Regressive Integrated Moving Average)  has been selected and trained on the prepared data but we found the data is not seasonal.
- So we have started working with traditional base multiple regression ML algorithms like Decision Tree, Random Forest, XG Boost, SVM, KNN, Gradient Boost, and AdaBoost.
- Random forest Regressor really performed well for the given data.So, Tuned the Random Forest Regressor model using GridSearchCV & K-Fold Cross-Validation to increase accuracy by 2%.
- The performance of the trained models have been evaluated using appropriate metrics such as Root Mean Squared Error, R^2, and Mean_Squared_Error,Mean_Squared_Log_Error.
- Finally, the trained model has been deployed into a production environment and integrated with the cab booking system to provide real-time demand forecasts.


![Forecasting cab booking demand](/assets/img/Cab booking.png)


<!--# Talks & Lectures
- Causality: The new science of an old question - GSP Seminar, Fall 2021
- Guest Lecture: Dimensionality Reduction - Big Data and Machine Learning for Scientific Discovery (PHYS 5336), Spring 2021
- Guest Lecture: Fourier and Wavelet Transforms - Scientific Computing (PHYS 5315), Fall 2020
- A Brief Introduction to Optimization - GSP Seminar, Fall 2019
- Weeks of Welcome Poster Competition - UTD, Fall 2019
- A Brief Introduction to Networks - GSP Seminar, Spring 2019

# Data Science YouTube

# Publications
- Talebi S., Lary D.J., Wijeratne L. OH., and Lary, T. Modeling Autonomic Pupillary Responses from External Stimuli Using Machine Learning (2019). DOI: 10.26717/BJSTR.2019.20.003446
- Wijeratne, L.O.; Kiv, D.R.; Aker, A.R.; Talebi, S.; Lary, D.J. Using Machine Learning for the Calibration of Airborne Particulate Sensors. Sensors 2020, 20, 99.
- Lary, D.J.; Schaefer, D.; Waczak, J.; Aker, A.; Barbosa, A.; Wijeratne, L.O.H.; Talebi, S.; Fernando, B.; Sadler, J.; Lary, T.; Lary, M.D. Autonomous Learning of New Environments with a Robotic Team Employing Hyper-Spectral Remote Sensing, Comprehensive In-Situ Sensing and Machine Learning. Sensors 2021, 21, 2240. https://doi.org/10.3390/s21062240
- Zhang, Y.; Wijeratne, L.O.H.; Talebi, S.; Lary, D.J. Machine Learning for Light Sensor Calibration. Sensors 2021, 21, 6259. https://doi.org/10.3390/s21186259
- Talebi, S.; Waczak, J.; Fernando, B.; Sridhar, A.; Lary, D.J. Data-Driven EEG Band Discovery with Decision Trees. Preprints 2022, 2022030145 (doi: 10.20944/preprints202203.0145.v1).
- Fernando, B.A.; Sridhar, A.; Talebi, S.; Waczak, J.; Lary, D.J. Unsupervised Blink Detection Using Eye Aspect Ratio Values. Preprints 2022, 2022030200 (doi: 10.20944/preprints202203.0200.v1).
- Talebi, S. et al. Decoding Physical and Cognitive Impacts of PM Concentrations at Ultra-fine Scales, 29 March 2022, PREPRINT (Version 1) available at Research Square [https://doi.org/10.21203/rs.3.rs-1499191/v1]
- Lary, D.J. et al. (2022). Machine Learning, Big Data, and Spatial Tools: A Combination to Reveal Complex Facts That Impact Environmental Health. In: Faruque, F.S. (eds) Geospatial Technology for Human Well-Being and Health. Springer, Cham. https://doi.org/10.1007/978-3-030-71377-5_12
- Wijerante, L.O.H. et al. (2022). Advancement in Airborne Particulate Estimation Using Machine Learning. In: Faruque, F.S. (eds) Geospatial Technology for Human Well-Being and Health. Springer, Cham. https://doi.org/10.1007/978-3-030-71377-5_13

# Data Science Blog -->

