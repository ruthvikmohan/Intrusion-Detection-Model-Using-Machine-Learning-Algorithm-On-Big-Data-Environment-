# Intrusion-Detection-Model-Using-Machine-Learning-Algorithm-On-Big-Data-Environment-
🛡️ Real-time Intrusion Detection Model (IDM) using a Spark Chi-SVM classifier on Apache Spark. Processes massive network logs, optimizes features via Chi-Square selection, and outperforms Chi-Logistic Regression in speed and accuracy. Benchmarked on 494k+ KDD99 dataset records for high-scale cybersecurity monitoring.
## 🚀 Key Features

* Real-Time Detection: Utilizes Machine Learning to identify patterns and network anomalies instantaneously.
* Big Data Architecture: Powered by Apache Spark to leverage fast, distributed data processing over traditional MapReduce/Hadoop systems.
* Feature Optimization: Implements Chi-Square feature selection to filter out noise and improve classifier efficiency.
* High Performance: Outperforms traditional methods like Chi-Logistic Regression in execution speed and scale.

## 🛠️ Proposed Workflow

   1. Data Ingestion: Loads massive datasets and converts them into Resilient Distributed Datasets (RDD) and DataFrames in Apache Spark.
   2. Data Preprocessing: Cleans and formats the raw network traffic data for analysis.
   3. Feature Selection: Applies statistical methods to identify the most relevant attributes for intrusion detection.
   4. Model Training: Trains the parallelized Spark Chi SVM model.
   5. Evaluation: Tests model performance using standard cybersecurity benchmarks.

## 📊 Dataset Information

* Dataset Used: KDD99 Cup Dataset
* Total Instances: 494,021 network records
* Attributes: 41 features per record
* Target Class: Binary classification (Normal vs. Attack)

## 💻 Tech Stack

* Framework: Apache Spark (PySpark / Scala)
* Storage & Processing: Resilient Distributed Datasets (RDD), DataFrames
* Machine Learning: Spark MLlib (SVM, Chi-Square Selector)
* Language: Python / Scala


