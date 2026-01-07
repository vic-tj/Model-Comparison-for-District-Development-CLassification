Regional Development Priority Classification

🎯 Brief Summary

Built ANN & SVC classifiers that flag Indonesian regions as “Needs Development” or “Doesn’t Need Development” using 2022-2023 BPS socio-economic indicators.

📊 Features

HLS, AHHP, AHHL, PPM, IPM (education, health, poverty, human-development index)

🧪 Methodology

Language: Python

Libraries: pandas, scikit-learn, imbalanced-learn (SMOTE), StandardScaler

Models: Artificial Neural Network (MLP), Support Vector Classifier (RBF kernel)

📈 Dataset

Official BPS 2022-2023 provincial/district data (~4 k regions); synthetic gap-fill generated with ChatGPT where 2024 figures are missing.

📋 Results (90:10 split, best run)

- ANN – 99 % accuracy, Log-Loss 0.0286 (chosen model)
- SVC – 97 % accuracy, Log-Loss 0.0424
