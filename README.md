⚡ Power System Fault Detection and Classification
A machine learning-based solution to detect and classify faults in electric power distribution systems using real-time electrical measurements like voltage and current phasors.

📌 Problem Statement
Electric power distribution networks often encounter faults such as:

Line-to-Ground (LG)

Line-to-Line (LL)

Three-Phase (LLL)

Quick and accurate identification of these faults is crucial to reduce outages and ensure grid stability. However, traditional protection systems struggle with real-time classification under complex system conditions.

✅ Proposed Solution
This project implements a Machine Learning-based Fault Detection System deployed on IBM Cloud to classify faults using electrical phasor data.

🔑 Key Features:
Real-time fault detection

Fault classification: Normal, LG, LL, LLL

Cloud-based model deployment (IBM Watson Studio)

⚙️ System Approach
Platform: IBM Cloud

Tools Used:

IBM Watson Studio – model development & deployment

IBM Cloud Object Storage – dataset handling

Python (Scikit-learn / TensorFlow)

Algorithm: Random Forest Classifier

🧠 ML Workflow
Data Input: Voltage, Current, and Phasor measurements

Preprocessing: Feature extraction and labeling

Training: Supervised learning with Random Forest

Deployment: IBM Watson Studio with API endpoint

Prediction: Real-time fault classification

📊 Result
The ML model shows high accuracy and faster response time compared to traditional methods. Real-time classification enables power utilities to quickly isolate faults and improve reliability.

🌐 Live Deployment
You can try the model via the IBM Cloud API (authentication required).

Note: Demo link or API endpoint can be added here if publicly available.

🔮 Future Scope
Expand model to transmission-level faults

Integrate with IoT sensor networks

Apply deep learning (e.g., LSTM) for temporal fault patterns

Add predictive maintenance and alerting

📚 References
IEEE Papers on Power System Fault Detection

IBM Cloud and Watson Studio Documentation

Scikit-learn, TensorFlow Libraries

Research on Phasor Measurement Units (PMUs)

👨‍💻 Author
Devam Vinod Suryawanshi
MIT Academy of Engineering, Department of Computer Engineering
