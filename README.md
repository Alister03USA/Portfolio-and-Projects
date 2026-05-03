# 📊 Data Science & AI Projects

> A collection of end-to-end data science, machine learning, and AI projects spanning public health analytics, NLP, computer vision, financial modeling, and geospatial intelligence.

---

## 🗂️ Table of Contents

1. [AI Financial Advisor](#1-ai-financial-advisor)
2. [Airbnb Pricing Optimization Engine](#2-airbnb-pricing-optimization-engine)
3. [Marketing Campaign Analysis & Customer Segmentation](#3-marketing-campaign-analysis--customer-segmentation)
4. [African vs. Asian Elephant Image Classifier (CNN)](#4-african-vs-asian-elephant-image-classifier-cnn)
5. [S&P 500 Stock Movement Prediction & Backtesting Engine](#5-sp-500-stock-movement-prediction--backtesting-engine)
6. [AI Chatbot for Rural Iowa Housing Data (RAG + LLM)](#6-ai-chatbot-for-rural-iowa-housing-data-rag--llm)
7. [Housing Price Prediction — Multi-Model Comparison](#7-housing-price-prediction--multi-model-comparison)
8. [ArcGIS Opioid Surveillance Dashboard — Jackson Tri-County](#8-arcgis-opioid-surveillance-dashboard--jackson-tri-county)
9. [Substance Use Monitoring Dashboards — R Shiny](#9-substance-use-monitoring-dashboards--r-shiny)

---

## 1. AI Financial Advisor

**Domain:** NLP · Generative AI · LLM Ops  
**Tools:** Python · RAG · N8N · Prompt Engineering · Document Pipelines

**Key Metrics**
| Metric | Value |
|---|---|
| User Base | 25,000+ ISU students |
| Validation Method | Human-in-the-loop |
| Workflow Orchestration | N8N |

**What I Built**
- Reduced LLM hallucination rate in a live financial aid chatbot by implementing RAG pipelines, human-in-the-loop validation, and prompt chaining to enable reliable real-time query resolution for ISU students.
- Automated resume & essay review at scale by engineering document pipelines that parse scholarship rubrics and generate instant, structured feedback, compressing manual review time from hours to seconds.
- Deployed end-to-end LLM workflow on N8N integrating heterogeneous financial documents into a coherent retrieval system, increasing information accessibility for a student body of 25,000+.

**Skills Demonstrated**  
`LLMs` `RAG` `Prompt Engineering` `N8N` `Document Pipelines` `Human-in-the-loop` `NLP` `LLM Ops`

---

## 2. Airbnb Pricing Optimization Engine

**Domain:** Machine Learning · Regression · Geospatial Analytics  
**Tools:** Python · Scikit-learn · Random Forest · Pandas · Haversine Formula

**Key Metrics**
| Metric | Value |
|---|---|
| Price Accuracy Improvement | **+28%** |
| MAE | $82.83 |
| R² | 0.48 |
| Properties Analyzed | 7,000+ |
| Model | Random Forest |

**What I Built**
- Improved listing price accuracy by 28% for 7,000+ San Francisco Airbnb properties by engineering a Random Forest pipeline (MAE: $82.83, R²: 0.48) with geospatial feature engineering via the Haversine formula.
- Surfaced primary pricing drivers (latitude and room type) through feature importance analysis, producing market insights that directly inform revenue optimization strategies for hosts.

**Skills Demonstrated**  
`Machine Learning` `Random Forest` `Geospatial Feature Engineering` `Regression Analysis` `Feature Importance` `Python` `Scikit-learn`

---

## 3. Marketing Campaign Analysis & Customer Segmentation

**Domain:** Machine Learning · Customer Analytics  
**Tools:** Python · Scikit-learn · Pandas · Matplotlib · PCA · K-Means

**Key Metrics**
| Metric | Value |
|---|---|
| Dataset Size | 2,240 customer records |
| Segmentation Method | K-Means Clustering + RFM Analysis |
| Segments Identified | 4 distinct behavioral cohorts |

**What I Built**
- Engineered customer personality features from a 2,240-record dataset, applying K-Means clustering and RFM (Recency, Frequency, Monetary) segmentation to identify 4 distinct behavioral cohorts for targeted campaign allocation.
- Built an end-to-end ML pipeline covering EDA, feature engineering, dimensionality reduction (PCA), and model evaluation — surfacing actionable segments that map directly to campaign ROI optimization.
- Produced data visualizations (heatmaps, pair plots, cluster scatterplots) to communicate segment profiles to non-technical stakeholders.

**Skills Demonstrated**  
`Machine Learning` `Customer Segmentation` `Feature Engineering` `PCA` `Data Visualization` `EDA` `Unsupervised Learning`

📎 **Dataset:** [Customer Personality Analysis — Kaggle](https://www.kaggle.com/datasets/whenamancodes/customer-personality-analysis)

---

## 4. African vs. Asian Elephant Image Classifier (CNN)

**Domain:** Deep Learning · Computer Vision  
**Tools:** Python · TensorFlow · Keras · Xception · Transfer Learning

**Key Metrics**
| Metric | Value |
|---|---|
| Test Accuracy | **87%** |
| Training Images | 940 |
| Test Images | 188 |
| Architecture | Xception (ImageNet pre-trained) |

**What I Built**
- Achieved 87% classification accuracy on a held-out test set of 188 images by fine-tuning the Xception architecture (ImageNet pre-trained weights) on a custom two-class elephant dataset.
- Applied transfer learning with layer freezing and a custom classification head, reducing training time while preserving deep feature representations learned from 1M+ ImageNet samples.
- Implemented data augmentation (horizontal flip, rotation, zoom) to combat overfitting on a limited training corpus, improving generalization by an estimated 8–12% over baseline.

**Skills Demonstrated**  
`Deep Learning` `CNNs` `Transfer Learning` `Keras` `TensorFlow` `Data Augmentation` `Computer Vision` `Model Fine-Tuning`

---

## 5. S&P 500 Stock Movement Prediction & Backtesting Engine

**Domain:** Machine Learning · Time Series · Quantitative Finance  
**Tools:** Python · Scikit-learn · Random Forest · yfinance · Pandas

**Key Metrics**
| Metric | Value |
|---|---|
| Directional Accuracy | 55% (baseline established) |
| Model | Random Forest Classifier |
| Hyperparameters | n_estimators=100, min_samples_split=100 |
| Evaluation Method | Rolling walk-forward backtesting |

**What I Built**
- Built a Random Forest classifier to predict daily S&P 500 upward price movements, engineering OHLCV features (Open, High, Low, Close, Volume) and a binary next-day target variable from historical market data.
- Designed a rolling walk-forward backtesting framework to evaluate model performance on sequential, non-overlapping time windows — ensuring zero data leakage and realistic out-of-sample assessment.
- Identified model limitations at 55% directional accuracy and documented a targeted improvement roadmap: adding momentum indicators (RSI, MACD), macro features, and ensemble stacking to close the gap toward a tradeable signal threshold (>58%).

**Next Steps / Improvement Roadmap**
- [ ] Add technical indicators: RSI, MACD, Bollinger Bands
- [ ] Incorporate macroeconomic features (VIX, bond yields)
- [ ] Explore LSTM and ensemble stacking approaches
- [ ] Target: >58% precision for directional signal viability

**Skills Demonstrated**  
`Time Series Forecasting` `Backtesting` `Random Forest` `Feature Engineering` `Quantitative Finance` `Model Evaluation` `Python`

---

## 6. AI Chatbot for Rural Iowa Housing Data (RAG + LLM)

**Domain:** NLP · Generative AI · Public Good  
**Tools:** Python · LlamaIndex · Mistral AI · Ollama · RAG · Satellite Imagery Processing

**Key Metrics**
| Metric | Value |
|---|---|
| Recognition | Presented at 2024 Iowa Technology Conference |
| LLMs Used | Mistral AI · Ollama |
| RAG Framework | LlamaIndex |
| Data Sources | Iowa housing datasets + satellite imagery |

**What I Built**
- Architected a Retrieval-Augmented Generation (RAG) pipeline using LlamaIndex to fine-tune Ollama and Mistral LLMs on curated Iowa housing datasets, enabling natural language querying of complex housing records for rural communities.
- Preprocessed and integrated satellite imagery data using Python to enrich LLM context with geospatial features, measurably improving chatbot response accuracy for location-specific housing queries.
- Delivered a fully tested prototype to stakeholders serving rural Iowa communities; project selected for presentation at the **2024 Iowa Technology Conference** out of a competitive DSPG cohort.

**Skills Demonstrated**  
`LLMs` `RAG` `LlamaIndex` `Prompt Engineering` `Geospatial Data` `ETL Pipeline` `Python` `Mistral AI` `Ollama` `NLP`

📎 **Project Blog:** [DSPG 2024 — AI Chatbot for Housing Data](https://dspg-2024.github.io/DSPG24-Main-Blog/blogs2024/Final_Blogs/dspg-final-blogs-housing-ai/Final_Team_Blog.html)

---

## 7. Housing Price Prediction — Multi-Model Comparison

**Domain:** Machine Learning · Regression · No-Code/Low-Code Analytics  
**Tools:** KNIME Analytics Platform · Linear Regression · Random Forest · Gradient Boosting

**Key Metrics**
| Metric | Value |
|---|---|
| Models Benchmarked | 3 (Linear Regression, Random Forest, Gradient Boosting) |
| Best Model | Random Forest (highest R²) |
| Evaluation Metrics | MAE · RMSE · R² |

**What I Built**
- Trained and benchmarked Linear Regression, Random Forest, and Gradient Boosting models in KNIME Analytics Platform on a housing price dataset, evaluating each against MAE, RMSE, and R² to select the highest-fidelity predictor.
- Identified Random Forest as the best-performing model based on composite error metrics, and documented feature importance rankings to interpret the key drivers of housing valuation for stakeholder reporting.
- Demonstrated proficiency in no-code/low-code ML workflows — applicable in enterprise analytics environments where rapid prototyping without engineering overhead is required.

**Skills Demonstrated**  
`Regression Analysis` `Random Forest` `Gradient Boosting` `Model Evaluation` `KNIME` `Feature Importance` `No-Code ML`

---

## 8. ArcGIS Opioid Surveillance Dashboard — Jackson Tri-County

**Domain:** Geospatial Analytics · Public Health · Policy  
**Tools:** ArcGIS Online · R · Geocoding · Spatial Analysis · Federal Health Databases

**Key Metrics**
| Metric | Value |
|---|---|
| Data Sources | Federal health databases |
| Output | Interactive ArcGIS Online dashboard |
| Impact | Findings submitted to local authorities for policy planning |

**What I Built**
- Collected and synthesized opioid-related incident data from federal health databases, performing spatial analysis and geocoding in R to pinpoint regional hotspots across Jackson Tri-County — surfacing patterns invisible in tabular reporting alone.
- Applied choropleth mapping and spatial clustering to identify statistically significant hotspot zones, enabling public health officials to prioritize resource allocation by geographic risk tier.
- Deployed an interactive ArcGIS Online dashboard visualizing opioid trends and community health metrics; findings formally submitted to local authorities to inform evidence-based policy and intervention planning.

**Skills Demonstrated**  
`ArcGIS Online` `Spatial Analysis` `Geocoding` `R` `Public Health Analytics` `Choropleth Mapping` `Data Visualization` `Policy Reporting`

📎 **Live Dashboard:** [Jackson Tri-County Dashboard](https://publicsciencecollaborative.org/jackson-rota/)

---

## 9. Substance Use Monitoring Dashboards — R Shiny

**Domain:** Business Intelligence · Public Health · Interactive Dashboards  
**Tools:** R · R Shiny · ggplot2 · shinyapps.io

**Key Metrics**
| Metric | Value |
|---|---|
| Deployments | 2 county-level dashboards (Lincoln County, NE · Lee County) |
| Hosting | Live on shinyapps.io |
| Users | County public health officials and community stakeholders |

**What I Built**
- Designed and deployed two production R Shiny dashboards to monitor county-level substance use trends — transforming raw public health data into interactive, real-time decision support tools for community stakeholders.
- Implemented dynamic filtering, trend visualizations, and KPI panels to allow non-technical public health officials to self-serve insights without requiring analyst support.
- Delivered live deployments on shinyapps.io, ensuring zero-friction access for county officials and enabling continuous data updates without re-deployment overhead.

**Skills Demonstrated**  
`R Shiny` `BI Dashboards` `ggplot2` `Public Health Analytics` `Data Pipeline` `Stakeholder Communication` `Interactive Visualization`

📎 **Live App:** [Lee County Substance Use Monitoring System](https://publicsciencecollaborative.shinyapps.io/lee_rota/)

---

## 🛠️ Tech Stack Summary

| Category | Tools & Technologies |
|---|---|
| **Languages** | Python · R · SQL |
| **ML & Stats** | Scikit-learn · XGBoost · Random Forest · Gradient Boosting · PCA · K-Means |
| **Deep Learning** | TensorFlow · Keras · PyTorch · CNNs · Transfer Learning |
| **NLP & AI** | LlamaIndex · LangChain · RAG · Mistral AI · Ollama · Prompt Engineering · N8N |
| **BI & Visualization** | Tableau · Power BI · R Shiny · ArcGIS Online · ggplot2 · Matplotlib |
| **Data Engineering** | ETL Pipelines · Pandas · NumPy · Snowflake · MongoDB · Hadoop |
| **Dev Tools** | Git/GitHub · Jupyter · VS Code · RStudio · KNIME |

---

*All projects were built as part of academic research, internship work, or independent exploration. For questions or collaboration, reach out via [LinkedIn](https://www.linkedin.com/in/alister-gan-ee-shern-00831a230/).*
