\# 🩸 Blood Donor Matching System using Machine Learning and Hybrid AI



\## 📌 Project Overview



The \*\*Blood Donor Matching System\*\* is an AI and Machine Learning-based project designed to identify and rank suitable blood donors for patients based on blood group compatibility, donor eligibility, availability, geographical distance, estimated travel time, and response history.



The project combines traditional Machine Learning algorithms with a Hybrid AI architecture to generate intelligent donor matching scores and recommend the Top 3 suitable donors for each blood request.



\## 🎯 Project Objectives



\- Identify compatible blood donors based on blood group requirements.

\- Evaluate donor eligibility and availability.

\- Calculate geographical distance between donors and hospitals.

\- Estimate donor travel time.

\- Predict donor matching outcomes using Machine Learning.

\- Develop an AI-based donor matching and ranking mechanism.

\- Recommend the Top 3 suitable donors for each blood request.



\## 🛠️ Technologies Used



| Category | Technologies |

|---|---|

| Programming Language | Python |

| Development Environment | Jupyter Notebook |

| Data Processing | Pandas, NumPy |

| Data Visualization | Matplotlib, Seaborn |

| Machine Learning | Scikit-learn, XGBoost |

| Deep Learning | PyTorch |

| AI Architecture | Transformer, GraphSAGE-based Hybrid Model |

| Mathematical Calculation | Haversine Formula |



\## ⚙️ Project Workflow



1\. Dataset Loading and Inspection

2\. Data Cleaning and Preprocessing

3\. Exploratory Data Analysis (EDA)

4\. Blood Group Compatibility Calculation

5\. Donor Eligibility and Availability Analysis

6\. Geographical Distance Calculation

7\. Travel Time Estimation

8\. Feature Engineering

9\. Machine Learning Model Training

10\. Hybrid AI Model Development

11\. Model Evaluation and Comparison

12\. AI-Based Donor Ranking

13\. Final Top-3 Donor Recommendation



\## 🤖 Machine Learning Algorithms



The project implements and compares the following classification algorithms:



\- Logistic Regression

\- Decision Tree

\- Random Forest

\- XGBoost

\- K-Nearest Neighbors (KNN)



Regression algorithms:



\- Linear Regression

\- Decision Tree Regressor

\- Random Forest Regressor

\- XGBoost Regressor

\- K-Nearest Neighbors Regressor



\## 🧠 Hybrid AI Architecture



The project also implements a Hybrid AI model using Transformer and GraphSAGE-based components.



The Hybrid AI model is designed to learn relationships between donor-related features and blood request-related features.



Key components:

\- Transformer-based feature representation

\- Donor feature representation

\- Request feature representation

\- Hybrid feature aggregation

\- AI-based matching probability

\- AI-enhanced matching score

\- Donor ranking and recommendation



\## 📊 Hybrid AI Model Performance



The following results were obtained on the notebook's test set:



| Evaluation Metric | Result |

|---|---:|

| Accuracy | 96.93% |

| Precision | 84.92% |

| Recall | 100.00% |

| F1-Score | 91.84% |

| ROC-AUC | 98.96% |



\*\*Note:\*\* These are experimental results from the notebook's test split, not clinical validation. The traditional Logistic Regression model achieved a higher F1-score of 93.97% in the model comparison.



\## 🏆 Final Donor Recommendation



The system generates an AI-enhanced matching score using:



\- Blood group compatibility

\- Donor availability

\- Geographical distance score

\- Estimated travel-time score

\- Donor response history

\- Hybrid AI matching probability



The final recommendation process filters eligible, available and compatible donors and ranks them according to their AI-enhanced matching scores.



The system recommends the \*\*Top 3 donors for each blood request\*\*.



\## 📂 Project Structure



```text

Blood-Donor-Matching-System/

│

├── blood donor matching system\_2.ipynb

├── blood\_data.csv

├── README.md

└── requirements.txt

```



\## 🚀 Installation and Execution



\### 1. Clone the repository



```bash

git clone https://github.com/amareshprogramer123/Blood-Donor-Matching-System.git

```



\### 2. Navigate to the project directory



```bash

cd Blood-Donor-Matching-System

```



\### 3. Install required libraries



```bash

pip install pandas numpy matplotlib seaborn scikit-learn xgboost torch torchvision torchaudio jupyter

```



\### 4. Add the dataset



Place the required dataset file named `blood\_data.csv` in the project directory.



\### 5. Launch Jupyter Notebook



```bash

jupyter notebook

```



Open `blood donor matching system\_2.ipynb` and execute the notebook cells in order.



\## 🔮 Future Enhancements



\- Real-time blood donor registration and matching.

\- Integration with hospital databases.

\- Live donor location tracking.

\- SMS and notification-based donor alerts.

\- Web-based application development.

\- Real-world dataset validation and clinical expert review.



\## ⚠️ Disclaimer



This project is developed for academic and research purposes. Its predictions and recommendations should not be used as a substitute for professional medical judgment or verified blood-bank compatibility testing.



\## 👨‍💻 Author



\*\*Amaresh Mohapatra\*\*



B.Tech – Computer Science and Engineering



Areas of Interest: Artificial Intelligence, Machine Learning, Data Science and Data Analytics.



\*\*GitHub:\*\* https://github.com/amareshprogramer123



\---



⭐ If you find this project interesting, feel free to explore the repository!



