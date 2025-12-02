# LalehAE.github.io

# Welcome to Laleh's Data Science Portfolio

## About Me
<div style="text-align: justify;">

I care about responsible, transparent AI: systems that show how they arrived at an answer, respect data boundaries, and keep domain experts in control of decisions. I am Laleh, a Lead Data Scientist who designs AI solutions around complex data where accuracy and trust really matter.

Most recently, as Lead Data Scientist at TREK Engineering in Winnipeg, I led the company’s AI and data modernization roadmap. Instead of putting a chatbot on top of messy legacy files, I designed and implemented a new data foundation: using language models to help clean and consolidate thousands of historical geotechnical files into a structured Postgres/PostGIS database, surfaced through a Google Earth view with location-accuracy flags and a feedback loop so engineers could review and correct critical records.

On top of that foundation I built a secure conversational layer over the enterprise database so geotechnical engineers and researchers can ask multi-step questions in natural language, see results on a map, download KMZ and CSV outputs, and understand which data, filters and reasoning were used in each answer, while raw data stays safely inside company systems.

My best work happens between domain experts, product and engineering: listening to how people really work, clarifying the problem, shaping the data and AI approach, and guiding it into something teams trust and actually use.
</div>
<br>

- **Email**: [la.asadzadeh@gmail.com](mailto:la.asadzadeh@gmail.com)
- **LinkedIn**: [linkedin.com/lalehas](https://www.linkedin.com/in/lalehas/)
- **Github**: [github.com/LalehAE](https://github.com/LalehAE)

## Projects


<div style="text-align: justify;">
Below is a curated selection of projects that show how I approach real-world AI and data problems: from LLM based assistants and agents, to recommender systems, computer vision, and analytics for decision making.
</div>
<br>
<br>

<img align="left" width="150" height="150" src="images/TREK_AI_Assistant.png"> **Geotechnical AI Assistant over Enterprise Data and Reports**
<div style="text-align: justify;">
At TREK Geotechnical I designed and built an AI assistant for geotechnical engineers that can answer complex questions over both structured data and technical reports, while keeping sensitive data inside company systems. The assistant uses an agentic LLM workflow to translate multi-step, domain-specific questions into SQL without exposing raw data, and returns results on a map with downloadable KMZ (Google Earth) and CSV outputs. It also explains which data, filters and reasoning were used for each answer, and can summarise PDF-based technical reports through a chat-style interface so complex documentation becomes easier to use for both technical and non-technical stakeholders.
</div>
<br>
<br>

<img align="left" width="150" height="150" src="images/TREK_Data_Platform.png"> **Geotechnical Data Platform and Google Earth Feedback Loop**
<div style="text-align: justify;">
I led the redesign of TREK’s geotechnical data foundation by consolidating thousands of legacy files into a structured relational geospatial database using automated ETL pipelines and LLM/NLP-based extraction and cleaning. On top of this, I built a Google Earth view that combines internal borehole data with external sources such as LiDAR so engineers can explore all available information for a location in one place. I also designed a validation workflow and feedback loop so field and design teams can flag low-accuracy records, correct them and feed updates back into the central database, steadily improving data reliability and on-the-ground decision making.
</div>
<br>
<br>

<img align="left" width="150" height="150" src="images/GenAI.png"> **[Autonomous ETL & Data Analytics](https://LalehAE.github.io/pages/GenAI.html)**
<div style="text-align: justify;">
Empowering business users to work with complex databases without deep technical knowledge. This project uses AI agents built with OpenAI and LangChain to interpret natural language questions, identify relevant data (for example from SAP), and generate Python scripts for analysis. It also suggests visualisations and business insights, helping teams move more easily from raw data to decisions.
</div>
<br>
<br>

<img align="left" width="150" height="150" src="images/Aircraft.png"> **[Aircraft Turnaround](https://LalehAE.github.io/pages/Aircraft.html)**
<div style="text-align: justify;">
This application supports airline and airport operations by monitoring aircraft turnaround in real time. It uses computer vision with a YOLO model to analyse CCTV footage, detect key events, and feed live dashboards on Azure, helping reduce delays and improve efficiency on the apron. 
</div>
<br>
<br>

<img align="left" width="150" height="150" src="images/Items.png"> **[Procurement Invoice Classification](https://LalehAE.github.io/pages/Items.html)**
<div style="text-align: justify;">
 
I developed a CatBoost model to classify procurement invoices into more than 30 categories, reaching a macro-average accuracy of 86%. This improved direct spend analysis, made hidden costs more visible, and supported cost saving strategies. I also optimised the post-processing pipeline, reducing its runtime by about 30 percent.
</div>
<br>
<br>

<img align="left" width="150" height="150" src="images/Content.png"> **[Content Recommender Engine](https://LalehAE.github.io/pages/Content.html)**
<div style="text-align: justify;">
 
A multilingual content recommender built with TensorFlow Recommenders, running on Kubeflow and orchestrated with Apache Airflow on GCP. I extended the system to support more than one hundred languages and improved its filtering so users receive current, relevant content. Planned next steps included A/B tests to measure engagement and refine the model.
</div>
<br>

<img align="left" width="150" height="150" src="images/Social.png"> **[Social Media Recommender Engine](https://LalehAE.github.io/pages/Social.html)**
<div style="text-align: justify;">
 
A proof of concept for social matching that uses deep learning to analyse user data and connect people with similar interests and goals. The system uses LaBSE embeddings and cosine similarity, providing better matches than traditional clustering and preparing the solution for use at larger scale.
</div>
<br>
<br>


 <img align="left" width="150" height="150" src="images/Cohort.png"> **[Cohort Churn Analysis](https://LalehAE.github.io/pages/Cohort.html)**
<div style="text-align: justify;">
 
An analysis of user retention across different membership types. I worked with stakeholders to define churn, secure the required data and build live churn tables and dashboards. The insights informed strategic decisions about which memberships to focus on and how to improve long term retention.
</div>
<br>
<br>

## Core Competencies

- **Programming:** Python, SQL, R  
- **Machine Learning:** tree-based models (XGBoost, CatBoost, Random Forest, LightGBM), linear and logistic regression, regularisation (Ridge, Lasso, Elastic Net), SVM, KNN, clustering (K-Means, Hierarchical, DBSCAN), dimensionality reduction (PCA, t-SNE), NLP (BERT, LaBSE)  
- **Statistical Analysis:** descriptive and inferential statistics, regression modelling and evaluation, time series forecasting  
- **AI & Data Platforms:** Large Language Models (LLM), vector databases, Microsoft Azure, Databricks, Google Cloud Platform, Airflow, Kubeflow  
- **BI & Visualisation:** Tableau, Google Data Studio, Google Earth, dashboards for decision support  
- **Industries:** Data infrastructure and analytics, e-learning, manufacturing, geotechnical engineering  
- **Soft Skills:** problem solving, communication, leadership, critical thinking, attention to detail, cultural competence

## Education

- **MSc, Southern Illinois University**, Computer Science, United States

- **MBA, Industrial Management Institute**, Executive Management, Iran

- **MSc, Sharif University of Technology**, Mathematics, Iran

- **BSc, Isfahan University of Technology**, Mathematics, Iran

## Conference Publications & Presentations
-	**Laleh, A.** (2019, March). Data Science: Demystifying Technical Terms, Data for Her, Shell Malaysia

-	**Laleh, A.** (2018, June). Data Science Industry, Presentation, British Council Malaysia, [Watch My Talk](https://www.youtube.com/watch?v=Tuuv-X8c5ts)

-	**Laleh, A.**, & Shahram, R. (2017, December). Analyzing Facebook Activities for Personality Recognition. In *Machine Learning and Applications (ICMLA), 2017 16th IEEE International Conference* on (pp. 960-964). IEEE.

## Professional Endorsements

> "Laleh has been a valuable member of the CADS data science team, with deep understanding of statistics, time-series analysis and machine learning, eager to work and find innovative ways to solve any project/puzzle she would face. All the best in your next endeavors!"
> [**- Stamatis Kourtis, Chief Data Officer at The Center of Applied Data Science**](https://www.linkedin.com/in/stamatis-kourtis-3624121/)

> "I always enjoy working with Laleh. She's forthright, persistent, and capable of changing her mind based on data. The last trait is my favorite. You can always count on her to stat the facts and then her thoughts on the facts in context to the situation/problem. Oh, and she's amazing at the more technical elements of Machine Learning, Inferential Stats, Times Series forecasting, and on and on. Laleh is a great asset to my or any team."
> [**- Zachary Johnson, Chief Product Officer  at The Center of Applied Data Science**](https://www.linkedin.com/in/zjamesjohnson/)

> "I had the chance of teaching Management Of Technology and Innovation to L.A. (not "Los Angeles"! I mean Ms. Laleh Asadzadeh) and her nice classmates at IMI in Spetember 2012. I found her very talented, enthusiastic, involved and serious at studies. I really enjoyed speaking at their class, especially with a number of outstanding students like Ms. Asadzadeh."
> [**- Fariborz Davarpanah, Lecturer at Industrial Management Institute**](https://www.linkedin.com/in/fariborz-davarpanah-4a9ba536/) 
