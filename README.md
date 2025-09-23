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

## Data Structure: 

**Student Information I Analyzed**
**Personal Details:**
- Age, gender, and marital status
- Nationality and international student status
- Family background and parents' education

**Academic History:**
- Previous education grades and qualifications
- Admission exam scores
- Chosen university course and application method

**University Performance:**
- Number of courses taken each semester
- Grades achieved in first and second semesters
- Courses passed vs courses failed
- Attendance patterns

**Financial Situation:**
- Scholarship status
- Tuition fee payment status
- Whether the student has unpaid debts

**External Factors:**
- Local unemployment rates
- Economic conditions and inflation
- Whether student comes from rural area

## How the System Works

**Data Processing:**
- Combines all student information
- Identifies important patterns
- Creates new helpful indicators like academic efficiency

**Prediction Engine:**
- Uses smart algorithms to analyze risk
- Compares new students to historical patterns
- Calculates dropout probability

**Results Provided:**
- Low risk (likely to graduate)
- Medium risk (may need support) 
- High risk (likely to drop out)
- Specific reasons for the risk level
- Recommended support actions

## Key Findings

**Most Important Warning Signs:**
1. Poor grades in second semester courses
2. Low academic efficiency
3. Late tuition payments
4. Low course completion rates
5. No scholarship support

**System Performance:**
- Correctly identifies 93 out of 100 at-risk students
- Very few false alarms
- Works equally well for different student groups
- Provides 6-12 months early warning

This structure allows universities to help students before it's too late, using actual academic data to guide support efforts.

![Image Alt](https://github.com/larissa-cb/MLPredUni/blob/main/pred-de-uni.streamlit.app.jpeg)

## Executive Summary

## **The Problem**
- Nearly 1 in 3 students leaves university before completing their degree
- Traditional methods detect problems too late for effective help
- Universities lose valuable students and resources

## **Solution**
- **Early warning system** that identifies at-risk students 6-12 months in advance
- Uses **existing student data** (grades, attendance, financial status)
- **93% accurate** - correctly identifies 93 out of 100 students who will struggle

## **Key Findings**

### **What Predicts Student Success:**
- **Second semester performance** is the strongest indicator
- **Tuition payment status** significantly impacts retention  
- **Academic efficiency** (courses passed vs attempted) matters most
- **Scholarship support** greatly improves completion rates

### **Student Risk Categories:**
- **High risk** (32% of students): Need immediate intervention
- **Medium risk** (18%): Benefit from ongoing support
- **Low risk** (50%): Likely to graduate successfully

## **Practical Benefits**

### **For Students:**
- **Personalized support** before problems become critical
- **Higher graduation rates** and better career outcomes
- **Timely financial and academic assistance**

### **For Universities:**
- **Save 300-350 students annually** from dropping out
- **€2 million - 3 million yearly savings** in recovered tuition and resources
- **14.94:1 return on investment** - every €1 spent returns €14.94 in benefits
- **Better resource allocation** for student support services

## **Implementation Ready**
- **Web-based platform** easy for staff to use
- **Instant risk assessment** with clear action plans
- **Proven effectiveness** with real student data
- **Scalable solution** for universities of all sizes

## **Bottom Line**
This system transforms how universities support students—moving from reactive crisis management to proactive success planning, creating better outcomes for students and stronger institutions for our communities.
