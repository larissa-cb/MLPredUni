# Predictive System for University Dropouts Using Machine Learning: Impact Analysis and Early Intervention Tools

![Image Alt](https://github.com/larissa-cb/MLPredUni/blob/main/Banner%20(1).png?raw=true)

## Background

University student dropout represents a significant challenge for higher education institutions worldwide, leading to substantial financial losses, wasted resources, and negative impacts on students' professional futures. Traditional approaches to identifying at-risk students often rely on manual monitoring and reactive interventions, which frequently occur too late to be effective.

This work addresses the critical need for proactive, data-driven solutions by developing a predictive system that can identify students at risk of dropout with sufficient advance notice to enable meaningful interventions. The research utilizes a real-world dataset from a Portuguese higher education institution containing comprehensive academic, demographic, and socioeconomic information for 4,424 students across various undergraduate programs.

## Overview

The system employs advanced machine learning techniques, including XGBoost, LightGBM, and Random Forest classifiers, to predict student outcomes categorized into three classes: dropout, enrolled, and graduate. The dataset exhibits a natural class distribution with 49.9% graduates, 32.1% dropouts, and 18.0% currently enrolled students.

Key technical achievements include:
- Achieving 93.5% accuracy with the XGBoost model
- Maintaining balanced performance across all classes (precision: 94%, recall: 93%, F1-score: 93.1%)
- Successfully handling class imbalance through SMOTE-ENN techniques
- Identifying the most influential predictive features, particularly second-semester academic performance indicators

The practical implementation includes an interactive web application built with Streamlit that enables academic advisors to input student data and receive instant risk assessments with personalized intervention recommendations. The system's impact analysis projects potential benefits of preventing 300-350 dropouts annually with an estimated return on investment of 14.94:1.

This work demonstrates the significant potential of machine learning approaches to enhance student retention strategies while providing institutions with actionable tools for early intervention and resource optimization.
