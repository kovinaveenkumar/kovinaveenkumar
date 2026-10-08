<h1 align="center">Hi, I'm Naveen Kumar Kovi 👋</h1>

<p align="center">
  <a href="https://github.com/kovinaveenkumar"><img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=22&duration=3000&pause=800&center=true&vCenter=true&width=760&lines=Software+Engineer+%7C+Backend%2C+Data+%26+Cloud+Systems;Python+%E2%80%A2+Java+%E2%80%A2+SQL+%E2%80%A2+AWS+%E2%80%A2+Azure+%E2%80%A2+Oracle+Cloud;Well-tested+code%2C+CI%2FCD%2C+and+AI+I+can+verify;IEEE-published+%E2%80%A2+M.S.+Computer+Science+%40+NJIT" alt="Typing SVG"/></a>
</p>

<p align="center">
  <a href="https://www.linkedin.com/in/kovinaveenkumar/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white"/></a>
  <a href="https://public.tableau.com/app/profile/naveen.k7476/viz/DCCapacityDashboard/DCCapacityDashboard"><img src="https://img.shields.io/badge/Tableau%20Public-1F77B4?style=flat&logo=tableau&logoColor=white"/></a>
  <a href="https://kovinaveenkumar.github.io"><img src="https://img.shields.io/badge/Portfolio-2dd4bf?style=flat&logo=githubpages&logoColor=black"/></a>
  <a href="https://leetcode.com/u/naveenkumarkovi/"><img src="https://img.shields.io/badge/LeetCode-FFA116?style=flat&logo=leetcode&logoColor=black"/></a>
  <a href="https://www.hackerrank.com/profile/U4CSE20238"><img src="https://img.shields.io/badge/HackerRank-00EA64?style=flat&logo=hackerrank&logoColor=black"/></a>
  <a href="mailto:naveenchowdary1106@gmail.com"><img src="https://img.shields.io/badge/Email-D14836?style=flat&logo=gmail&logoColor=white"/></a>
</p>

---

### ⚡ About

I'm a **software engineer with 3+ years of experience** designing, building, testing and supporting software, from backend services and data platforms to machine-learning and AI applications.

Today I build and maintain backend and data-processing services for an enterprise healthcare platform at **Insight Global**, working in Python, SQL and PySpark on Databricks, Snowflake and AWS. Most of my work is writing reusable, well-tested components, tracing issues across distributed systems to the root cause, tuning performance, and shipping changes through code review and CI/CD.

- 🧰 **Daily tools:** Python · Java · SQL · PySpark · Databricks · Snowflake · AWS · Docker · Git
- 🤖 **Lately:** clinical reporting on EHR data models (SQL, Oracle, CCL), AI agents with guardrails and evaluation (Claude API, MCP), and forecasting and optimization
- 📄 **IEEE-published** co-author (NLP, 93.82% accuracy)
- 🎓 **M.S. Computer Science, NJIT** · B.Tech Computer Science and Engineering, Amrita Vishwa Vidyapeetham
- 🔎 **Open to** software engineer, backend and full-stack roles

---

### 🚀 Featured projects

| Project | What it does | Tech |
|---|---|---|
| 📦 [**Distribution Center Demand Forecast & Capacity Optimization**](https://github.com/kovinaveenkumar/distribution-center-optimization) · [dashboard](https://public.tableau.com/app/profile/naveen.k7476/viz/DCCapacityDashboard/DCCapacityDashboard) | Forecasts 12 weeks of regional demand (about 5.8% error vs 9.7% for a seasonal baseline), then a linear program assigns volume across 4 distribution centers within capacity at minimum cost. Compares capacity-expansion scenarios. Network inputs are documented assumptions. | Python · Prophet · ARIMA · PuLP · SQL · Tableau |
| 🏥 [**Clinical Operations Reporting (Cerner Millennium-style)**](https://github.com/kovinaveenkumar/millennium-clinical-reporting) · [case study](https://github.com/kovinaveenkumar/millennium-clinical-reporting/blob/main/docs/case_study.pdf) | 7 KPI and operational reports (ED boarding, lab turnaround, critical-result calls, readmissions, census) on a 13-table Millennium-style data model, in SQL and CCL with HTML/MPage output. 21 pre-publish checks, 19 tests, Oracle port reconciled 238/238 values, and a Discern rule tested in silent mode (60-min window: 71 false alerts vs 993). | SQL · Oracle · CCL · Python · HTML |
| 🤖 [**AI Data Analyst Agent**](https://github.com/kovinaveenkumar/ai-data-analyst-agent) | Claude agents turn plain-English questions into validated SQL, charts and reports through a read-only MCP server. CI, tests and a 30-question evaluation (28/30 correct). | Python · Claude API · MCP · PostgreSQL · Streamlit |
| 📞 [**Call Center KPI Analytics**](https://github.com/kovinaveenkumar/call-center-kpi-analytics) · [dashboard](https://public.tableau.com/app/profile/naveen.k7476/viz/CallCenterKPIDashboard_17913996371520/Dashboard1) | Workforce-management KPIs (AHT, service level, abandonment, occupancy, shrinkage) at 30-minute intervals for 3 queues, with Erlang C staffing. Found a late-morning service-level dip with flat staffing, pointing to schedule shifts rather than more headcount. | SQL · Python · Tableau |
| 🐝 [**HiveQL Supply-Chain Analytics**](https://github.com/kovinaveenkumar/hive-supply-chain-analytics) | Retail demand and forecast backtests in HiveQL on Apache Hive 4: ORC tables partitioned by region and year, a bucketed table, window functions and CTAS. Results match the original Python pipeline. | HiveQL · Apache Hive · Docker |
| 🛡️ [**Credit-Card Fraud Detection**](https://github.com/kovinaveenkumar/fraud-detection-ml) | Benchmarks Logistic Regression, Random Forest and Gradient Boosting on imbalanced data; best model served by a FastAPI scoring service. | Python · scikit-learn · FastAPI |
| 📚 [**RAG Document Assistant**](https://github.com/kovinaveenkumar/rag-document-assistant) | Retrieval-augmented assistant with embeddings, cosine-similarity retrieval and grounded answers with citations. | Python · Embeddings · FastAPI |
| 📝 [**SecureComment (IEEE)**](https://github.com/kovinaveenkumar/securecomment-nlp-toxic-comment) | TF-IDF with voting and stacking ensembles for toxic-comment classification. Basis of a co-authored IEEE paper. | Python · NLP · scikit-learn |
| ☁️ [**AWS Image Recognition Pipeline**](https://github.com/kovinaveenkumar/aws-image-recognition-pipeline) | Event-driven pipeline: SQS decouples parallel workers running Rekognition object detection and writing results to S3. | AWS · boto3 · SQS |
| 🗄️ [**Hadoop MapReduce**](https://github.com/kovinaveenkumar/big-data-hadoop-mapreduce) | Distributed batch processing on Hadoop/HDFS with a combiner for local pre-aggregation; deployable on AWS EMR. | Java · Hadoop · AWS |
| 📈 [**Data Mining & Predictive Analytics**](https://github.com/kovinaveenkumar/data-mining-predictive-analytics) | Benchmarks Random Forest, SVM, Gradient Boosting and a neural net with cross-validation and automatic best-model selection. | Python · scikit-learn |
| 🚗 [**Rent-A-Car Database System**](https://github.com/kovinaveenkumar/rent-a-car-database-system) | 3NF schema, analytical SQL and a Streamlit reporting dashboard. | SQL · Python · Streamlit |
| 📊 [**Web Scraping & Analytics in R**](https://github.com/kovinaveenkumar/data-analytics-web-scraping-r) | Paginated scraping with rvest, tidy cleaning and ggplot2 visualizations. | R · rvest · ggplot2 |

---

### 💼 Experience

- **Software Engineer**, Insight Global (May 2025 to present): backend and data-processing services for an enterprise healthcare platform (Python, SQL, PySpark, Databricks, Snowflake, AWS)
- **Software Engineer Intern**, Genpact (2024): Python data-processing and ML components, model comparison and testing
- **Software Engineer, Research Assistant**, Amrita Vishwa Vidyapeetham (2023 to 2024): built the NLP pipeline behind the IEEE-published SecureComment system
- **Software Engineering Specialist**, Chegg (2023): reviewed and debugged 300+ Python, Java and SQL solutions
- **Software Engineer Intern**, Genpact (2022): Python and SQL components and scheduled Azure Data Factory pipelines

---

### 🛠️ Tech stack

**Languages:** `Python` · `Java` · `SQL` · `Oracle SQL` · `HiveQL` · `CCL (Cerner)` · `JavaScript` · `R` · `C++`

**Backend & engineering practices:** `REST APIs` · `Microservices` · `OAuth 2.0 / JWT` · `RBAC` · `Docker` · `Git` · `Code review` · `Unit & integration testing` · `CI/CD (GitHub Actions)` · `Agile`

**Cloud & data:** `AWS` · `Azure` · `Oracle Cloud (OCI)` · `Oracle Database` · `Databricks` · `Snowflake` · `PySpark` · `Apache Spark` · `Hadoop` · `Apache Hive` · `PostgreSQL` · `MySQL` · `SQLite`

**AI & ML:** `scikit-learn` · `NLP` · `LLMs` · `Claude API` · `AI agents` · `MCP` · `RAG` · `Time-series forecasting` · `Linear programming`

**Analytics & BI:** `Tableau` · `Power BI` · `Pandas` · `Matplotlib` · `ggplot2` · `KPI & operational reporting` · `Data validation`

**Healthcare data:** `Cerner Millennium data model` · `Discern Rules` · `MPages` · `Clinical KPIs`

---

### 📜 Certifications & learning

- **Oracle:** 7 certifications across OCI, AI, data platform, ERP and AI Database
- **Databricks:** Advanced Machine Learning Operations · Fundamentals · Fine-tuning Embeddings and Advanced Retrieval
- **Google Cloud:** Generative AI · Large Language Models · Prompt Design in Vertex AI
- **Microsoft Learn:** 31 learning paths and 109+ badges across Azure, security, data and AI
- **Anthropic:** 14 Claude courses (AI Fluency, Claude API, MCP, agents, Claude Code)
- **[HackerRank](https://www.hackerrank.com/profile/U4CSE20238):** SQL (Advanced) · Software Engineer · Software Engineer Intern · Frontend Developer (React)
- **[LeetCode](https://leetcode.com/u/naveenkumarkovi/):** 100 Days Badge 2026
- **Salesforce Trailhead** and **Forage** job simulations (BCG, Deloitte, Quantium and others)

---

### 📄 Publication

📰 [**SecureComment: Safeguarding Online Discussions with Intelligent Toxic Comment Filtering**](https://ieeexplore.ieee.org/document/10503420), *IEEE IATMSI 2024* (co-author)

---

<p align="center">
  <a href="https://www.linkedin.com/in/kovinaveenkumar/"><img src="https://img.shields.io/badge/LinkedIn-Connect-0077B5?style=for-the-badge&logo=linkedin"/></a>
  <a href="https://public.tableau.com/app/profile/naveen.k7476/viz/DCCapacityDashboard/DCCapacityDashboard"><img src="https://img.shields.io/badge/Dashboard-Tableau%20Public-1F77B4?style=for-the-badge&logo=tableau&logoColor=white"/></a>
  <a href="https://kovinaveenkumar.github.io"><img src="https://img.shields.io/badge/Portfolio-Visit-2dd4bf?style=for-the-badge&logo=githubpages&logoColor=black"/></a>
  <a href="mailto:naveenchowdary1106@gmail.com"><img src="https://img.shields.io/badge/Email-Reach%20Me-D14836?style=for-the-badge&logo=gmail&logoColor=white"/></a>
</p>
