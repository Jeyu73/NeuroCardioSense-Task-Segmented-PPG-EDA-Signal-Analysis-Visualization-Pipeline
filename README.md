# NeuroCardioSense-Task-Segmented-PPG-EDA-Signal-Analysis-Visualization-Pipeline
Performs heart rate, HRV, RMSSD, and IBI analysis from raw PPG/EDA signals. Segments data based on Cognitive Tasks. Applies EDA, filtering, sampling rate correction, and box plots through heartpy and sklearn
# NeuroCardioSense

> **Task-Segmented PPG-EDA Signal Analysis & Visualization Pipeline**  
> Extract cognitive and physiological insights using heart rate (HR), RMSSD, IBI, and EDA metrics from time-synchronized bio-signals during stress and relaxation tasks.

---

## 🧠 Project Overview

**NeuroCardioSense** is a Python-based bio-signal analysis pipeline designed to:

- Analyze **PPG and EDA** data across task-labeled time intervals
- Compute key cardiovascular and autonomic metrics: **Heart Rate (HR), RMSSD, and IBI**
- Visualize signal behavior with overlaid event segmentation
- Compare stress-induced vs. relaxed physiological states using advanced plots and statistical tools

---

## 📊 Features

- 🔹 Multi-signal processing: PPG and EDA
- 🔹 Time-aligned labeling of tasks (Relaxation, Stroop, Math)
- 🔹 Computation of HRV metrics using [`heartpy`](https://github.com/paulvangentcom/heartrate_analysis_python)
- 🔹 High-resolution visualizations with shaded task regions
- 🔹 Outlier-resilient box plots grouped by experimental condition
- 🔹 Signal preprocessing (bandpass filtering, normalization)

---

## 📁 File Structure

```text
.
├── dac_adc_recording_1st.csv.csv       # PPG + EDA data with timestamps
├── dac_adc_recording_2nd.csv.csv       # Additional segment for PPG
├── main.py                             # Main analysis script
├── plot1.jpg to plot7.jpg              # Output visualizations
└── README.md
