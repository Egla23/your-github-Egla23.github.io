
# Hello, I'm Egla Mekonnen 
**Data Scientist & AI Developer**

I am a recent Data Science and Artificial Intelligence graduate specializing in building practical AI applications, multimodal systems, and business intelligence. My core technical foundation spans the entire data lifecycle—from rigorous **data exploration, SQL database querying, and statistical analysis (Python/R)** to **machine learning model training** and building interactive **Tableau dashboards**.

I am deeply passionate about data storytelling and responsible AI governance, particularly regarding the ethical adoption of generative tools in corporate environments. Below are my featured projects showcasing my ability to leverage APIs like Gemini 2.5 Flash to turn complex datasets into actionable, production-ready tools.

---

##  Featured Data Science & AI Projects

### 1. Live Financial News Sentiment Classifier & Analytics Pipeline
An automated NLP data pipeline that ingests live macro catalysts from Yahoo Finance RSS feeds, extracts structured trading signals using generative AI, and compiles a comprehensive performance dashboard.

* **Production Stack:** Python, LangChain, Pydantic, Gemini 2.5 Flash API, Feedparser, Matplotlib
* **Core Architecture:**
    * **Data Ingestion & Deduplication:** Developed an automated RSS scraper utilizing `feedparser` to pool real-time headlines from Yahoo Finance, matching entries against a local JSON storage to guarantee exact data deduplication and eliminate redundant API calls.
    * **Deterministic Structured Output:** Implemented LangChain's `.with_structured_output` built on top of a strict Pydantic schema (`TradingSignal`). This forces the Gemini 2.5 Flash model to reliably output clean, standardized JSON features—such as `market_sentiment`, `volatility_risk`, target stock tickers, trading theses, and raw granular analysis—with zero formatting drift.
    * **Edge-Case Nuance Handlers:** Configured strict system-level instructions demanding the model explicitly isolate market sarcasm and slang keywords (classifying them uniquely under "Sarcasm" or "Slang" tokens) rather than dumping them into generic market noise.
    * **Downstream Visualization:** Programmed a companion analytical script to read the historical database and render a 4-panel data visualization report (`classification_dashboard.png`) directly tracking sentiment distribution, volatility risk, ticker frequency, and output quality.
* **Quantitative/Business Value:** Turns raw text streams into machine-readable, actionable alpha signals. This pipeline lets you adjust exposure or execute portfolio hedges instantly when extreme volatility or clear sentiment shifts hit major market catalysts.

### 2. REEL Vendor Network Chatbot & Recommendation Engine
A highly adaptive, multimodal recommendation engine designed to match engaged couples with localized event vendors based on stylistic preferences, budget criteria, and complex text inquiries.

* **Production Stack:** Python, Streamlit, Gemini 2.5 Flash API
* **Core Architecture:**
    * **Multimodal Query Processing:** Leveraged the multi-sensory processing capabilities of the Gemini API to parse complex, unstructured user inputs (such as vision assets, color palettes, venue imagery, and detailed text descriptions) without needing dense preprocessing.
    * **Intelligent Recommendation Engine:** Engineered a collaborative matching pipeline that evaluates user constraints against vendor databases, ranking results natively to deliver tailored vendor recommendations.
    * **Streamlit UI Interface:** Built a lightweight, production-ready frontend using Streamlit, allowing users to interact with the model in real time, adjust filtering constraints, and review vendor matches dynamically.
* **Quantitative/Business Value:** Lowers the operational barrier to entry for local, independent small businesses by connecting them with perfectly aligned leads. It automates the initial client discovery process, replacing tedious sorting and filtering with a seamless, conversational search interface.

### 3. Tech Industry Mental Health Predictor & Classifier
A statistical machine learning project analyzing the OSMI 2016 survey to predict whether tech professionals will seek mental health treatment based on workplace environments, demographics, and personal attitudes.

* **Production Stack:** Python, Pandas, Scikit-Learn, Matplotlib
* **Core Architecture:**
    * **Feature Engineering & Preprocessing:** Cleaned a 1,259-row dataset by isolating 27 variables, imputing missing values, mapping categorical baseline references, applying one-hot encoding, and scaling numeric predictors. 
    * **Multi-Model Classification Pipeline:** Built, trained, and tested three distinct predictive algorithms to find the optimal fit for the binary target variable: Logistic Regression, Linear Discriminant Analysis (LDA), and Random Forest.
    * **Rigorous Statistical Evaluation:** Utilized bootstrap analysis to generate 95% confidence intervals for model comparison. This mathematical proof showed that the LDA model outperformed the others on this dataset, achieving 83.3% test accuracy and a 0.886 AUC.
    * **Coefficient Analysis:** Extracted and interpreted the model coefficients to identify the strongest predictors for seeking treatment, specifically flagging "Work Interference" and "Family History" as the primary drivers.
* **Quantitative/Business Value:** Provides HR departments and corporate leadership with an empirical framework to understand mental health trends in the tech sector. By isolating the exact variables that correlate with employees seeking help, organizations can proactively optimize their wellness benefits, adjust leave policies, and allocate support resources where they are most effective.

---

##Get In Touch
* **LinkedIn:** www.linkedin.com/in/egla-mekonnen-59055533a
* **GitHub:** https://github.com/Egla23?tab=repositories
* **Email:** eglamekonnen@gmial.com
* **Resume:***
