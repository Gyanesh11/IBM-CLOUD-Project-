# IBM SkillsBuild 4-Week Internship on AI & Cloud Technologies

This repository documents the capstone project completed during the **IBM SkillsBuild 4-Weeks Internship on AI & Cloud Technologies**. This program is a collaborative initiative by the **Edunet Foundation**, **AICTE**, and **IBM SkillsBuild**.

The internship's primary goal is to provide hands-on experience in emerging technologies, enhancing employability and confidence by solving real-world challenges using the IBM SkillsBuild and IBM Cloud platforms.

## 📝 Table of Contents
- [Intern Details](#intern-details)
- [About the Internship](#about-the-internship)
- [Project: Intelligent Classification of PMGSY Schemes](#project-intelligent-classification-of-pmgsy-schemes)
  - [Problem Statement](#problem-statement)
  - [Solution Overview](#solution-overview)
- [⚙️ Technology Stack](#️-technology-stack)
- [🚀 Project Workflow](#-project-workflow)
- [📊 Results](#-results)
- [📁 Repository Contents](#-repository-contents)


## 👨‍💻 Intern Details
-   **NAME:** GYANESH VERMA 
-   **INSTITUTE:** GOVERNMENT POLYTECHNIC LUCKNOW 
-   **DURATION:** 4 Weeks (15th July 2025 to 7th August 2025)

## 📖 About the Internship
This 4-week program focused on providing practical skills in AI and Cloud Computing. The internship was structured with weekly virtual sessions, mentor guidance, and hands-on labs. The curriculum included:
-   **Week 1:** Internship Orientation, IBM Cloud Registration, Artificial Intelligence.
-   **Week 2:** Data Analytics concepts, Hands-On Labs, and Cloud EDA.
-   **Week 3 & 4:** Building a Chat Bot, AI/ML experiments on the cloud, and a deep dive into AutoAI experiments on IBM Cloud.

Successful completion required active participation, completion of at least two courses on IBM SkillsBuild, and the submission of a final project presentation. This internship was offered with no stipend.

## 💡 Project: Intelligent Classification of PMGSY Schemes

### Problem Statement
The Pradhan Mantri Gram Sadak Yojana (PMGSY) is a major rural development program with various schemes like PMGSY-I, PMGSY-II, etc. Manually classifying thousands of projects under these schemes is slow, error-prone, and unscalable. This inefficiency hinders effective monitoring, budget allocation, and impact assessment.

### Solution Overview
An end-to-end machine learning solution was developed to automate the classification of PMGSY projects. The system uses a project's physical and financial data to predict which PMGSY scheme it belongs to. The final, trained model was deployed as a real-time web service on the IBM Cloud platform.

## ⚙️ Technology Stack
-   **Cloud Platform:** IBM Cloud 
-   **AI/ML Service:** IBM watsonx.ai Studio
-   **Automated ML Tool:** IBM AutoAI
-   **Core Language & Libraries:**
    -   Python
    -   `scikit-learn`
    -   `pandas`
    -   `XGBoost`
    -   `ibm-watsonx-ai`

## 🚀 Project Workflow
1.  **Data Ingestion:** The PMGSY dataset from the AI Kosh portal was uploaded to an IBM Cloud project.
2.  **Automated Model Building:** An AutoAI experiment was configured in watsonx.ai. This powerful tool automated the entire machine learning pipeline, including data preprocessing, feature engineering, model selection, and hyperparameter optimization.
3.  **Model Selection:** AutoAI trained and ranked multiple classification algorithms. The **XGBoost Classifier** was identified as the best-performing model based on accuracy.
4.  **Deployment:** The top-performing pipeline was saved as a model asset and deployed as an **Online Web Service** within a Deployment Space on IBM Watsonx.ai, which provides a REST API for real-time predictions.
5.  **Testing:** The deployed API endpoint was successfully tested with sample data to validate its real-time classification capabilities.

## 📊 Results
The deployed model demonstrated high accuracy in classifying infrastructure projects, proving the effectiveness of using automated AI tools for rapid development and deployment. The project successfully met all requirements for the final evaluation and submission.

<img width="1920" height="1080" alt="Screenshot (1)" src="https://github.com/Gyanesh11/IBM-CLOUD-Project-/blob/c5ca58a5990813d07a064664b3b8a21032cea444/Screenshot%202025-07-27%20143930.png" />
<img width="1920" height="1080" alt="Screenshot (2)" src="https://github.com/Gyanesh11/IBM-CLOUD-Project-/blob/34ca2bca050fda54aedc815b724236dc8d6cc9b1/Screenshot%202025-07-27%20143958.png" />
<img width="1920" height="1080" alt="Screenshot (3)" src="https://github.com/Gyanesh11/IBM-CLOUD-Project-/blob/785d4abcfc1e129ca78da40ae7ef639d4f1a3428/Screenshot%202025-07-27%20171102.png" />
<img width="1920" height="1080" alt="Screenshot (4)" src="https://github.com/Gyanesh11/IBM-CLOUD-Project-/blob/4876df662aa8439fc93765adcef70d8eda05d8cd/Screenshot%202025-07-27%20171139.png" />
<img width="1920" height="1080" alt="Screenshot (5)" src="https://github.com/Gyanesh11/IBM-CLOUD-Project-/blob/e39debfe1353fe7b65c370d703e2f7ad41da9c07/Screenshot%202025-07-27%20171250.png" />


## 📁 Repository Contents
-   `Pradhan Mantri Gram Sadak Yojana SCHEME Detector.ipynb`: The Jupyter Notebook automatically generated by IBM AutoAI, detailing the best pipeline's architecture and code.
-   `GYANESH VERMA PROJECT REPORT.pdf`: The final project presentation pdf submitted for evaluation.
-   `README.md`: This file.
