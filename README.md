<h1 align="center">Fabian Figueroa</h1>

<p align="center">
  Computer Science student at UTSA · Break Through Tech AI Alumnus
</p>
<p align="center">
  <a href="https://fabianfigueroa.com">fabianfigueroa.com</a>
</p>
<hr style="border:0.5px solid #e0e0e0; width:100%;">

## About

I am a computer science student at the University of Texas at San Antonio, concentrating in Software Engineering and Data Science. I completed the Break Through Tech AI fellowship and have a background in machine learning, NLP, and full-stack development, with a focus on conflict data, MENA-region research, and the systems that sit underneath both.

---

## Selected Projects

**US Military Strikes & Civilian Casualty Prediction**  
[Portfolio Page](https://fabianfigueroa.com/portfolio/us-military-strikes)

A data science investigation into the correlation between US military interventions and civilian casualties across Iraq, Syria, Afghanistan, and Yemen (2001-2024), completed under the supervision of Dr Maryam Tabar. The project integrates four conflict databases--UCDP-GED, ACLED, Airwars, and IBC--via heuristic spatial joins, and frames civilian casualty prediction as a tool for humanitarian pre-positioning and independent accountability against official underreporting.

Five models were evaluated via 5-fold cross-validation. A tuned Random Forest achieved CV RMSE of 6.68 and R² of 0.58, rising to R² of 0.8576 on a Yemen 2024 temporal holdout. A feature-level ablation study identified the Conflict Context group (tactical type, scale, documentation quality) as responsible for the majority of predictive power--removing it alone increased RMSE by 51%. An IBC validation cross-check quantified a systematic "fatality gap" between official records and independent monitors, making the model's predictions a principled lower bound on actual civilian harm.

Technologies: Python, scikit-learn, XGBoost, Pandas, Seaborn, Matplotlib, SQLite, spatial joins

---

**GitHub Actions DSL Compiler**  
[Portfolio Page](https://fabianfigueroa.com/portfolio/github-actions-compiler)

A two-phase compiler for a custom domain-specific language targeting GitHub Actions workflow YAML, built with ANTLR4 and Java under faculty supervision. Phase I covers lexing and parsing; Phase II implements semantic analysis including undefined `needs` reference detection, duplicate job name checking, invalid trigger validation, cycle detection across job dependency graphs, and dangerous command flagging.

Technologies: Java, ANTLR4, compiler design, semantic analysis

---

**WiDS Wildfire Survival Analysis - Break Through Tech AI Studio**

A machine learning project completed through the Break Through Tech AI fellowship in collaboration with the Women in Data Science Datathon. The project involved predicting wildfire survival outcomes using a Random Survival Forest model with custom-engineered features and 5-fold cross-validation, achieving a competition score of 0.91985.

Technologies: Python, scikit-learn, survival analysis, feature engineering

---

**Roo Response Categorisation - Planned Parenthood @ Break Through Tech AI Studio**  
[GitHub Repository](https://fabianfigueroa.com/portfolio/ppfa-roo)

A machine learning challenge conducted with Planned Parenthood through the Break Through Tech AI Studio programme, focused on classifying chatbot responses to improve escalation accuracy and reduce misinformation in sexual and reproductive health conversations.

I contributed to data preprocessing, feature engineering, and model development using TF-IDF representations alongside structural and sentiment-based features. A linear SVM achieved the strongest results (76% accuracy, weighted F1-score of 0.76), exceeding the project baseline.

Technologies: Python, Pandas, scikit-learn, Docker, Jupyter, NLP pipelines

---

**ALERGZ - Allergy-Safe Food Recommendation App**  
[GitHub Repository](https://github.com/SawyerAlston/ALERGZ)

A mobile application developed during RowdyHacks 2025 (24-hour hackathon), awarded *Best Beginner Project*. The app allows users to scan food products and determine allergen safety, with AI-generated alternatives suggested when products are unsuitable.

Technologies: FastAPI, React Native (Expo), SQLite, SQLAlchemy, OpenRouter, asynchronous processing

---

**Chrono - Productivity Timer & Task Tracker**  
[GitHub Repository](https://github.com/UTSA-CS-3443/Chrono)

A JavaFX desktop application for task management, countdown timers, and theme customisation. I contributed to UI design, prototyping, implementation, and testing. The project includes JUnit 5 unit tests and supports persistent task storage.

Prototype & design assets: [Figma File](https://www.figma.com/design/5vsupr5xMDlI5zN123XdFc/Chrono?node-id=0-1&t=6UpPxw3BZN2QKJ0g-1)

Technologies: Java, JavaFX, SceneBuilder, Maven, JUnit 5, FXML

---

## Technical Skills

**Languages:** Python, Java, JavaScript, C/C++, SQL  
**Machine Learning & Data:** Pandas, NumPy, scikit-learn, XGBoost, survival analysis, NLP pipelines  
**Web & Mobile:** FastAPI, React, React Native (Expo), Vue.js  
**Systems & Tools:** Git, Docker, AWS EC2, ANTLR4, LaTeX

---

## Interests

Outside of work, I read widely--technology, culture, sociology, and world affairs. I run and cycle regularly and have a strong interest in Arabic language and the broader Arab world.

---

## Contact

- LinkedIn: [https://www.linkedin.com/in/fabianfigueroajr/](https://www.linkedin.com/in/fabianfigueroajr/)
- Email: fabianfig.ff@gmail.com
