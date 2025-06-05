# 📊 Exploring Ball Recovery Times in Professional Football

This repository contains the code and visualizations for the bachelor thesis **"Exploring Ball Recovery Times in Professional Football: Insights and Patterns"** by Mahbod Tajdini and supervised by Dr. Mauricio Verano Merino, submitted to the Vrije Universiteit Amsterdam in 2025.

## 🎯 Objective
To analyze how key match events (goals, substitutions, injuries, cards, etc.) affect the time it takes for elite football teams to recover ball possession. The research focuses on Argentina and France during the 2022 FIFA World Cup, using open-access StatsBomb data.

## 🔍 Features
- **Rule-based ball recovery classification** based on detailed event taxonomy.
- **Statistical testing**:
  - Shapiro-Wilk Test for normality
  - Mann-Whitney U Test for group difference
  - Cliff’s Delta for effect size and direction
- **Interactive visualizations** using Plotly:
  - Normality plots (QQ + KDE)
  - Game-timeline plots with key match events and recovery durations
  - Statistical summary tables with effect interpretations
- **Custom dashboard** to assist coaching staff and analysts in tactical evaluation.

> ⚠️ **Note:** No multiplicity adjustment has been done. Interpret p-values accordingly.

## 📦 Tech Stack
- Python
- Pandas
- Scipy
- Plotly
- StatsBombPy

## 📜 License
- This project is for academic and research purposes only.
