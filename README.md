# Cinema Analytics and Prediction System  
### AAI-590 Capstone Project | Team 5  
**Authors**: Arup Chakraborty, Seema Mittal, Rene Ortiz  

---

## Overview

This project leverages machine learning (ML) and deep learning (DL) to analyze metadata from over 4,800 Hollywood films and provide predictive insights across multiple dimensions, including:

-  Box Office Revenue Prediction  
-  Success Classification  
-  Genre Prediction using NLP  
-  Content-Based Movie Recommendation  

Built as part of the AAI-590 capstone, this solution aims to demonstrate how AI can support decision-making in the creative industry using structured and unstructured movie data.

---

## Problem Statement

We aim to answer key questions using AI:
- How much revenue will a movie likely earn?
- Will the movie be commercially successful?
- What genres best represent the plot?
- What similar movies can be recommended?
- *(Bonus)* What poster would best represent the movie?

---

## Features

| Module | Description |
|--------|-------------|
| Revenue Prediction | Regression models (XGBoost, MLP) for box office forecasting |
| Success Classification | ML classifier using KPIs like vote average and revenue |
| Genre Classification | BERT-based multi-label classifier from movie plots |
| Movie Recommendation | Embedding-based content similarity using FAISS |
| Dashboard UI | User interface built with Streamlit or Gradio |

---

##  End Users

This system is built for:
-  **Film Studios & Producers** – for forecasting and risk analysis  
-  **Streaming Platforms** – for content recommendation engines  
-  **Market Analysts** – for trend analysis and KPIs  
-  **Consumers** – for intelligent viewing recommendations  

---

## Dataset

We use the **Hollywood Movies Dataset** from Kaggle, which contains:
- Movie metadata (budget, revenue, cast, release date, etc.)
- Plot overviews (for NLP analysis)
- Genre and production info

 In a live product, this data would be fetched dynamically from:
- [IMDb API](https://developer.imdb.com/)
- [TMDb API](https://developers.themoviedb.org/3)

---

## Hypothesis & Final Goal

> **Hypothesis**:  
> Movie performance and genre affinity can be accurately predicted using a combination of structured metadata and unstructured plot summaries processed by ML/DL models.

 **Final Deliverable**:  
A live, web-based platform hosted via Hugging Face or Vercel that enables users to:
- Upload/select a movie
- View predicted revenue & success likelihood
- Analyze genre classification
- Receive AI-powered similar movie suggestions

---

## References

1. Muttalib, M. (2023). *Hollywood Movies Dataset*. Kaggle. https://www.kaggle.com/datasets/mohdmuttalib/hollywood-movies-dataset  
2. IMDb. (n.d.). *IMDb API Documentation*. https://developer.imdb.com/  
3. The Movie Database (TMDb). (n.d.). *TMDb API Overview*. https://developers.themoviedb.org/3/getting-started/introduction  
4. AI in Screen Trade. (2024, July 17). *The role of AI in predicting box office success and audience preferences*. https://aiinscreentrade.com/2024/07/17/the-role-of-ai-in-predicting-box-office-success-and-audience-preferences/

---

## Contributors

- Arup Chakraborty  
- Seema Mittal  
- Rene Ortiz  

---

## License

This project is released under the [MIT License](LICENSE).

