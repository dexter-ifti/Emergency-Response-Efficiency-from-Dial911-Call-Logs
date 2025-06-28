# 🚨 Emergency Response Efficiency Analysis

This project analyzes emergency service response times using real-world emergency call logs. It focuses on understanding how quickly services respond in different neighborhoods, during different times, and based on call types and priorities. The goal is to find delays, patterns, and areas needing improvement to help optimize emergency response systems.

---

## 📂 Dataset Overview

The dataset contains emergency call logs with the following key features:

* **Call Timestamps:** Various stages from call received to reaching the scene.
* **Location Data:** Neighborhoods, zip codes, and station areas.
* **Call Types:** Medical, Fire, and other incidents.
* **Priority Levels:** Original and final priority of calls.
* **Response Units:** ALS (Advanced Life Support), Private, Engine units, etc.

---

## 📊 Key Metrics Calculated

* **Dispatch Delay:** Time from call received to dispatch.
* **Travel Time:** Time from dispatch to on-scene arrival.
* **Total Response Time:** Full time from call received to on-scene arrival.

---

## 📌 Libraries Used

* **Numpy**
* **Pandas**
* **Matplotlib**
* **Seaborn**

*(No machine learning, no external APIs — purely data analysis and visualization.)*

---

## 🔍 Analysis Performed

1. **Distribution of Total Response Times**
   Visualized how emergency response times vary overall.

2. **Neighborhood-wise Average Response Time**
   Identified areas with fastest and slowest responses.

3. **Hourly Response Patterns**
   Detected peak hours with highest delays.

4. **Response Time by Emergency Type**
   Compared efficiency based on medical, fire, and alarm incidents.

5. **Response Time by Final Priority**
   Analyzed whether higher priority calls are actually getting faster responses.

6. **ALS vs. Non-ALS Unit Response Time**
   Compared advanced vs. basic emergency unit performance.

7. **Response Time by Unit Type**
   Explored which unit types (Medic, Engine, Private) respond fastest.

8. **Response Time by Zipcode**
   Provided a geo-level view of emergency response efficiency.

9. **Correlation Matrix**
   Examined the relationship between dispatch delay, travel time, and total response time.

---

## 📂 Folder Structure

```
Emergency_Response_Analysis/
│
├── dataset2_cleaned.csv           # Cleaned dataset used for analysis
├── Emergency_Response_Analysis.ipynb  # Complete Jupyter Notebook
├── README.md                      # Project documentation
```

---

## 🚀 How to Run the Project

1. Clone this repository or download the notebook.
2. Ensure the following libraries are installed:

   ```bash
   pip install numpy pandas matplotlib seaborn
   ```
3. Open the Jupyter Notebook and run all cells.
4. Upload your dataset in the same directory as the notebook.

---

## 📢 Key Insights

* Certain neighborhoods consistently have slower response times.
* Peak delays occur during specific hours of the day.
* Life-threatening incidents generally get faster responses, but some call types still face delays.
* Advanced life support (ALS) units are generally quicker in response compared to non-ALS units.

---

## ✨ Future Scope

* Integrate machine learning to predict delays based on call features.
* Analyze resource allocation to suggest better staffing during peak hours.
* Build an interactive dashboard for real-time emergency response monitoring.

---

## 👨‍💻 Author

**[dexter-ifti](https://x.com/DexterIfti)** 

---

