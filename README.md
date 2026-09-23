# Hospital OPD Bottleneck Analysis

A comprehensive data-driven analysis of operational bottlenecks in a hospital Outpatient Department (OPD).  
This project identifies delays, congestion points, and workflow inefficiencies across patient activities such as doctor consultation, lab, imaging, and transitions.  
Using a dataset of **10,000 records** and **46 features**, the analysis highlights where bottlenecks occur and why.

---

##  Dataset Overview

This dataset was obtained from a healthcare operational workflow simulation containing **10,000 labeled OPD events**.  
It includes timestamps, activity transitions, workload indicators, and bottleneck labels generated from process mining outputs.

### Dataset Includes:
- 10,000 OPD event records  
- 46 columns covering:
  - Waiting time  
  - Processing duration  
  - Transition delays  
  - Doctor workload  
  - Resource load  
  - Activity frequency  
  - Bottleneck labels  

---

## Analysis Objectives

- Identify activities causing the highest bottlenecks  
- Measure average waiting time per activity  
- Evaluate processing duration  
- Detect transition delays  
- Assess resource load and doctor workload  
- Generate visual insights for workflow optimization  


---

##   Project Visual Highlights   

<div style="display: flex; overflow-x: auto; gap: 10px;">

  <img src="Hospital_OPD_BottleneckAnalysis .ipynb - Colab-page-00005.jpg" width="350">
  <img src="Hospital_OPD_BottleneckAnalysis .ipynb - Colab-page-00006.jpg" width="350">
  <img src="Hospital_OPD_BottleneckAnalysis .ipynb - Colab-page-00008.jpg" width="350">
  <img src="Hospital_OPD_BottleneckAnalysis .ipynb - Colab-page-00009.jpg" width="350">

</div>

---
---

##  Code Summary

### **Bottleneck Percentage**
Calculates the percentage of bottleneck events per activity using `bottleneck_label` and ranks activities from highest to lowest.

### **Waiting Time Analysis**
Computes average waiting time for each activity using `waiting_time_minutes` to identify where patient queues build up.

### **Processing Duration**
Measures average service duration per activity using `processing_duration_minutes` to detect slow operational steps.

### **Transition Delay**
Evaluates delays between activities using `transition_delay_minutes` to uncover coordination issues between departments.

### **Resource Load**
Assesses operational pressure using `activity_resource_load` to highlight understaffed or overloaded activities.

### **Summary Table**
Combines all metrics (waiting, processing, delay, load, bottleneck %) into one consolidated table for top activities.
##  Tools Used

- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Google Colab  
- Jupyter Notebook  
- Healthcare workflow analytics  
- Process Mining concepts  

---

## By  
**Raghad Aldaghreer** — Data Analyst focused on healthcare workflow optimization and operational analytics.

