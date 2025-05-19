# ML Exercise 0001 — Sensor Status Classification

This notebook demonstrates a **complete machine learning pipeline** using the K-Nearest Neighbors (KNN) classifier to predict sensor status based on IoT telemetry data.

## 📌 Goal

Classify sensor status (`normal`, `warning`, `critical`) using:
- Temperature
- Humidity
- Vibration

## ⚙️ Workflow

1. **Data Preparation** – Load and explore sensor data
2. **Label Encoding** – Convert categorical labels to numbers using `LabelEncoder`
3. **Model Training** – Split data into training/testing sets and fit a `KNeighborsClassifier`
4. **Evaluation** – Predict, measure accuracy, and show confusion matrix

## 🗂️ Dataset

Synthetic dataset with:
- 1000 rows
- 3 numerical features + 1 categorical label (`status`)

Note: This is a **generated dataset** for practice and learning.

## 🔍 Why this matters

This project builds foundational ML intuition:
- Scikit-learn syntax and structure
- Working with real-world-like data
- Tracking performance and errors

## ✍️ Author Notes

This notebook contains intentionally long inline comments to help me reflect, understand, and solidify key concepts.
I’m building a personal collection of real, hands-on machine learning mini-projects — not just to showcase code, but to demonstrate actual learning and growth. This project may be simple, but it’s a meaningful step forward as one of my first real experiences in the field.
