# LalehAE.github.io

# Laleh's AI & Data Science Portfolio

## About Me
<div style="text-align: justify;">

I am Laleh, a Lead Data Scientist who designs AI systems around complex, messy data where accuracy and trust really matter. I care about responsible, transparent AI: systems that show how they got to an answer, respect data boundaries, and keep domain experts in control of decisions.

Most recently, as Lead Data Scientist at TREK Engineering in Winnipeg, I led the company’s AI and data modernization roadmap. Instead of putting a chatbot on top of messy legacy files, I designed and implemented a new data foundation. I used language models to help clean and consolidate thousands of historical geotechnical files into a structured Postgres/PostGIS database, surfaced in Google Earth with location accuracy flags and a feedback loop so engineers could review and correct critical records.

On top of that foundation I built a secure conversational layer over the enterprise databases so geotechnical engineers and researchers can ask multi-step questions in natural language, see results on a map, download KMZ and CSV outputs, and understand which data, filters, and reasoning were used in each answer, while raw data stays safely inside company systems.

My best work happens between domain experts, product, and engineering: listening to how people really work, clarifying the problem, shaping the data and AI approach, and guiding it into something teams trust and actually use.
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

### AI Lab – LLM & AI Systems
<br>

<img align="left" width="170" height="170" src="images/TREK_AI_Assistant.png"> **Geotechnical AI Assistant over Enterprise Data and Reports**
<div style="text-align: justify;">
At TREK Engineering I designed an AI assistant that answers complex geotechnical questions over both structured data and technical reports, while keeping sensitive data inside company systems. It uses an agentic LLM workflow to turn multi-step, domain questions into SQL and geospatial queries, and returns results on a map with downloadable KMZ (Google Earth) and CSV files. The assistant also explains which data and filters were used and can summarise PDF reports through a chat-style interface for technical and non-technical users. 

 **[Read more](https://LalehAE.github.io/pages/TREK_AI_Assistant.html)**

  
</div>
<br>

<img align="left" width="170" height="170" src="images/TREK_Data_Platform.png"> **Geotechnical Data Platform and Google Earth Feedback Loop**
<div style="text-align: justify;">
I redesigned TREK’s geotechnical data foundation by consolidating thousands of legacy files into a structured Postgres/PostGIS database using automated ETL with LLM/NLP-assisted data extraction and cleaning. On top of this, I built a Google Earth view that merges borehole data with LiDAR-enhanced geospatial layers and added a validation and feedback loop so engineers can flag and fix low-accuracy records. This made it much easier to reuse historical investigations and steadily improved data quality for planning and design.

  **[Read more](https://LalehAE.github.io/pages/TREK_Data_Platform.html)**
  
</div>
<br>

<img align="left" width="170" height="170" src="images/GenAI.png"> **Autonomous ETL & Data Analytics**
<div style="text-align: justify;">
I built an AI agent framework to help business users work with complex databases without deep technical knowledge. The system uses OpenAI and LangChain to interpret natural language questions, identify relevant data (for example from SAP), and generate Python scripts for analysis. It also suggests visualisations and business insights, helping teams move more easily from raw data to practical decisions.

  **[Read more](https://LalehAE.github.io/pages/GenAI.html)**
  
</div>
<br>
<br>

### Other Projects


<img align="left" width="170" height="170" src="images/Aircraft.png"> **Aircraft Turnaround**
<div style="text-align: justify;">
I developed a computer vision solution to monitor aircraft turnaround in real time and support airline and airport operations. Using a YOLO model, the system analyses CCTV footage, detects key events on the apron and streams structured outputs to live dashboards on Azure. This allows operations teams to spot delays earlier, optimise resources and improve turnaround efficiency.

**[Read more](https://LalehAE.github.io/pages/Aircraft.html)**
</div>
<br>

<img align="left" width="170" height="170" src="images/Items.png"> **Procurement Invoice Classification**
<div style="text-align: justify;">
I developed a CatBoost model to classify procurement invoices into more than 30 categories, reaching a macro-average accuracy of 86%. This improved direct spend analysis, made hidden costs more visible and supported cost saving strategies for the business. I also optimised the post-processing pipeline, reducing its runtime by about 30 percent.

**[Read more](https://LalehAE.github.io/pages/Items.html)**
</div>
<br>

<img align="left" width="170" height="170" src="images/Content.png"> **Content Recommender Engine**
<div style="text-align: justify;">
I built a multilingual content recommender using TensorFlow Recommenders, running on Kubeflow and orchestrated with Apache Airflow on GCP. I extended the system to support more than one hundred languages and improved the filtering logic so users receive current, relevant content rather than outdated items. Planned next steps included A/B tests to measure engagement and refine the model.

**[Read more](https://LalehAE.github.io/pages/Content.html)**
</div>
<br>

<img align="left" width="170" height="170" src="images/Social.png"> **Social Media Recommender Engine**
<div style="text-align: justify;">
I created a proof of concept for social matching that uses deep learning to analyse user data and connect people with similar interests and goals. The system uses LaBSE embeddings and cosine similarity, providing better matches than traditional clustering and preparing the solution for use at larger scale in community or networking platforms.

**[Read more](https://LalehAE.github.io/pages/Social.html)**
</div>
<br>

<img align="left" width="170" height="170" src="images/Cohort.png"> **Cohort Churn Analysis**
<div style="text-align: justify;">
I carried out a cohort-based churn analysis across different membership types to understand retention patterns over time. Working with stakeholders, I helped define churn, secure the required data and build live churn tables and dashboards. The insights informed strategic decisions about which memberships to focus on and how to improve long-term retention.

**[Read more](https://LalehAE.github.io/pages/Cohort.html)**
</div>
<br>

## Core Competencies

<div style="text-align: justify;">
  
- **Programming & Data:** Python, SQL, R  
- **AI & Data Platforms:** Large Language Models (LLMs), vector databases, Microsoft Azure, Databricks, Google Cloud Platform, Airflow, Kubeflow  
- **Machine Learning:** Tree-based models (XGBoost, LightGBM, CatBoost, Random Forest), linear and logistic regression, regularised models (Ridge, Lasso, Elastic Net), SVM, KNN, clustering (K-Means, Hierarchical, DBSCAN), dimensionality reduction (PCA, t-SNE), NLP (BERT, LaBSE)  
- **Statistical Analysis:** Descriptive and inferential statistics, regression modelling and evaluation, time series forecasting  
- **BI & Visualisation:** Tableau, Google Data Studio, Google Earth, dashboards for decision support  
- **Domains / Industries:** Data infrastructure and analytics, e-learning, manufacturing, geotechnical engineering  
- **Soft Skills:** Problem solving, clear communication with non-technical stakeholders, leadership, critical thinking, attention to detail, cultural competence
</div>

## Education

<div style="text-align: justify;">

- **MSc, Southern Illinois University**, Computer Science, United States

- **MBA, Industrial Management Institute**, Executive Management, Iran

- **MSc, Sharif University of Technology**, Mathematics, Iran

- **BSc, Isfahan University of Technology**, Mathematics, Iran
</div>

## Conference Publications & Presentations
<div style="text-align: justify;">
  
-	**Laleh, A.** (2019, March). Data Science: Demystifying Technical Terms, Data for Her, Shell Malaysia

-	**Laleh, A.** (2018, June). Data Science Industry, Presentation, British Council Malaysia, [Watch My Talk](https://www.youtube.com/watch?v=Tuuv-X8c5ts)

-	**Laleh, A.**, & Shahram, R. (2017, December). Analyzing Facebook Activities for Personality Recognition. In *Machine Learning and Applications (ICMLA), 2017 16th IEEE International Conference* on (pp. 960-964). IEEE.
</div>

## Professional Endorsements

> "Laleh has been a valuable member of the CADS data science team, with deep understanding of statistics, time-series analysis and machine learning, eager to work and find innovative ways to solve any project/puzzle she would face. All the best in your next endeavors!"
> [**- Stamatis Kourtis, Chief Data Officer at The Center of Applied Data Science**](https://www.linkedin.com/in/stamatis-kourtis-3624121/)

> "I always enjoy working with Laleh. She's forthright, persistent, and capable of changing her mind based on data. The last trait is my favorite. You can always count on her to stat the facts and then her thoughts on the facts in context to the situation/problem. Oh, and she's amazing at the more technical elements of Machine Learning, Inferential Stats, Times Series forecasting, and on and on. Laleh is a great asset to my or any team."
> [**- Zachary Johnson, Chief Product Officer  at The Center of Applied Data Science**](https://www.linkedin.com/in/zjamesjohnson/)

> "I had the chance of teaching Management Of Technology and Innovation to L.A. (not "Los Angeles"! I mean Ms. Laleh Asadzadeh) and her nice classmates at IMI in Spetember 2012. I found her very talented, enthusiastic, involved and serious at studies. I really enjoyed speaking at their class, especially with a number of outstanding students like Ms. Asadzadeh."
> [**- Fariborz Davarpanah, Lecturer at Industrial Management Institute**](https://www.linkedin.com/in/fariborz-davarpanah-4a9ba536/) 
