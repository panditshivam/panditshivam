**Portfolio:** [panditshivam.github.io ↗](https://panditshivam.github.io/)

# Shivam Dwivedi

**Principal Data Scientist · Machine Learning Solution Architect**

[LinkedIn](https://linkedin.com/in/panditshivam) · [Medium](https://medium.com/@panditshivam) · [Email](mailto:shivampandit@icloud.com)

I build AI systems that connect research, engineering, and business decisions. Over 10+ years, my work has spanned predictive modeling, enterprise retrieval, multilingual AI, healthcare research, and production ML architecture.

Currently, I’m a **Solution Architect, Machine Learning at Code & Theory**, focused on decision intelligence, GraphRAG, and explainable quality systems. Alongside industry work, I’m pursuing a **Ph.D. in explainable multimodal AI** for clinically safe decision support.

## Selected work

| Focus | What I built | Selected result |
| :--- | :--- | :--- |
| **Knowledge & retrieval** | Enterprise GraphRAG combining entity relationships, semantic traversal, and vector retrieval | **89% multi-hop fact recovery** versus 53% in an internal comparison across 22 questions in six categories |
| **Decision intelligence** | Production pricing, customer attrition, controlled experimentation, and economic signal pipelines | Connected **52 external indicators** to end-market analysis and commercial decisions |
| **Multilingual AI** | Real-time voice translation and voice-assisted digital commerce at Pulastya AI | Approximately **0.45-second latency** across **3,000+ bilingual pilot calls** |
| **Healthcare research** | CNN-based keratoconus progression modeling with clinicians at L. V. Prasad Eye Institute | Research using tomography data from **1,200+ subjects** |

## Expertise

| Area | Methods & tools |
| :--- | :--- |
| **Data science & statistics** | Predictive modeling, hypothesis testing, A/B testing, temporal validation, pricing, customer analytics |
| **Machine learning & explainability** | PyTorch, TensorFlow, scikit-learn, XGBoost, LightGBM, computer vision, counterfactual explanations |
| **Graphs, retrieval & GenAI** | GraphRAG, Neo4j, knowledge graphs, hybrid retrieval, embeddings, NLP, LangChain, LlamaIndex |
| **Architecture & MLOps** | Kedro, Argo Workflows, Docker, Kubernetes, CI/CD, observability, batch and API serving |
| **Data platforms & cloud** | Python, SQL, GCP, AWS, BigQuery, Vertex AI, Kafka, Spark, Airflow |

## Experience

| Organization | Role | Period |
| :--- | :--- | :--- |
| **Code & Theory** | Solution Architect, Machine Learning | Mar 2025 – Present |
| **Pulastya AI** | Co-Founder & CTO | Jun 2022 – Feb 2025 |
| **Concentrix Innovation Labs** | Senior Machine Learning Engineer | Aug 2021 – May 2022 |
| **Techsophy** | Machine Learning Engineer | Jan 2019 – Aug 2021 |
| **SDLC Corp** | AI Consultant; previously Software Engineer | Jun 2015 – Jan 2019 |
| **Cognizant** | Programmer Analyst | Aug 2014 – Jun 2015 |

<details>
<summary><strong>Explore contributions, systems, and outcomes</strong></summary>

### Code & Theory — Solution Architect, Machine Learning
**March 2025 – Present · India**

**Commercial Pricing & ML Decision Intelligence**

- Architected a production pricing decision framework combining transaction-level feature engineering, comparable-price logic, recency and transaction weighting, conversion-rate adjustments, ML recommendations, and multi-layer commercial guardrails.
- Operationalized reusable data and model pipelines through Kedro and Argo, with lineage, regression validation, and memory/runtime optimization.
- Designed an agentic “Explain the Price” decision-support layer that surfaces the factors behind recommendations across region, product/form, order size, and customer and market signals.

**Customer Attrition & Enterprise Churn Modeling**

- Designed a leakage-safe customer attrition model using 31 behavioral, volume, product-mix, quote, and lead-time inputs over four-quarter observation windows to predict 50%+ next-quarter volume decline.
- Converted churn probabilities into revenue and volume at risk, identifying approximately **2,430 significant-reduction customers per quarter** representing roughly **243M T12M lbs**, and translated the scores into intervention priorities and controlled validation plans.
- Built an enterprise portfolio churn framework combining financial, contractual, organizational, people, and engagement signals into entity-level predictors of relationship risk.

**Experimentation & Economic Signal Intelligence**

- Designed and evaluated controlled pricing experiments across material/form adders, large-order discounts, recommendation methods, and adoption scenarios, reconciling win-rate movement with gross-margin economics through sensitivity and break-even analysis.
- Built a signal-engineering pipeline across 52 external indicators, mapping signals to end markets, applying STL seasonal adjustment and PPO transformations, and validating relationships against end-market-specific volume.

**Quality Intelligence, GraphRAG & Applied AI**

- Architected an organization-wide Quality Intelligence platform that converts multi-tool SARIF evidence into deterministic, explainable repository-, module-, and function-level quality scores and trends.
- Designed graph-based extensions for semantic redundancy, localized call-graph structure, AI-generated-code assessment, and completeness-aware scoring that prevents failed analyzers from inflating quality.
- Architected and benchmarked an enterprise GraphRAG system combining entity-relationship graphs, semantic traversal, and vector retrieval; achieved **89% multi-hop fact recovery versus 53% for a leading enterprise benchmark** and **2.9× faster average inference** across **22 ground-truth questions in six categories**.
- Improved internal GraphRAG evaluation quality from **43.1% to 54.6%** while reducing confirmed hallucinations to **zero** through retrieval, traversal, and grounding refinements.
- Led architecture for a production content-intelligence platform on GCP, combining external trends, entity intelligence, hybrid retrieval, recommendations, and geospatial analytics across a **multi-million-article corpus**, reducing manual editorial curation by **50%+**.

### Pulastya AI — Co-Founder & CTO
**June 2022 – February 2025 · India / UK**

**Voice AI, Language Technology & Digital Commerce**

- Co-founded and engineered a mobile-to-mobile, real-time voice translation platform with approximately 0.45-second latency, supporting 3,000+ bilingual calls during pilot programs.
- Built multilingual translation systems that achieved 20% higher fluency across Hindi, Tamil, Bengali, and Gujarati against baseline benchmarks.
- Led ONDC and Bhashini integrations and voice-assisted merchant onboarding workflows, reducing listing time by 40% and supporting 500+ sellers.
- Deployed multilingual AI for Parliamentary Archives covering **1M+ records** and enterprise voice workflows processing **50K+ minutes per month**, contributing approximately **$1.5M in annual savings**.

**BFSI Decision Intelligence for a Confidential Client**

- Led the architecture of an AI-powered credit-underwriting platform processing **7M+ loan applications annually**, shortening approval cycles by **45%** and reducing processing errors by **20%**.
- Developed ensemble risk models using **10+ years of loan history**, macroeconomic indicators, and behavioral signals, improving risk-prediction accuracy by **30%**.
- Designed a GenAI-assisted counterfactual decisioning approach that helped eligible rejected applicants move toward approvable profiles, increasing approval rates by **18%** and unlocking **$20M+ in estimated annual revenue**.
- Reduced default rates by **2.5 percentage points** and underwriting costs by **10%**, generating approximately **$3.5M in annual savings**, while unstructured-data analysis improved fraud-detection accuracy by **35%**.
- Built an LLM- and speech-analysis-driven customer reactivation framework that increased conversion from approximately **3% to 19.8%** and delivered **$15M+ in annual savings**.
- Enabled Kafka-based recovery and lead-generation analytics that improved recovery efficiency by **25%**, lead-to-conversion rates by **40%**, and customer engagement by **30%**.
- Delivered a multilingual customer and representative assistant handling **1.5M+ daily interactions**, with OCR-based document extraction at **98% accuracy**; reduced query-resolution time by **40%**, improved customer satisfaction by **25%**, and increased cross-channel adoption by **50%**.
- Added computer-vision document checks that reduced onboarding fraud cases by **20%** and deployed Docker-, Kafka-, and AWS-based infrastructure capable of handling **25× peak traffic**, maintaining **99.99% uptime** while lowering infrastructure cost by **35%**.

**Healthcare, Enterprise AI & Applied Research**

- Delivered a voice-enabled health agent for elderly care, supporting **2,000+ seniors** and reducing manual caregiver workload by **30%**.
- Developed predictive flu-outbreak models with The Weather Company by combining climate and health signals, achieving approximately **80% accuracy** with up to a **two-week lead time**.
- Led enterprise voice-bot and agent deployments that reduced inbound query-handling costs by **35%**, and explored multimodal integrations with expressive 3D avatars.

### Concentrix Innovation Labs — Senior Machine Learning Engineer
**August 2021 – May 2022 · China / India**

- Developed and scaled multilingual conversational AI for English, Spanish, and Portuguese, handling 1M+ monthly interactions with 99.9% uptime.
- Integrated real-time computer vision for automated document verification, achieving 95% accuracy and reducing manual review by 30%.
- Connected NLP and vision services with CRM workflows, reducing query-resolution time by 25%.

### Techsophy — Machine Learning Engineer
**January 2019 – August 2021 · Hyderabad, India**

**Research collaboration with L. V. Prasad Eye Institute**

- Collaborated with clinicians to develop CNN-based keratoconus progression models using tomography data from 1,200+ subjects.
- Supported progression prediction up to approximately 500 days in advance through medical-image modeling, longitudinal validation, demographic analysis, and explainable ML.

**Conversational AI & Recommendation**

- Designed an ensemble intent-classification system achieving 93.5% accuracy with sub-0.65-second latency.
- Developed a hybrid content-based and collaborative recommendation system with automated retraining and multi-channel support.

### Earlier career

- **AI Consultant, SDLC Corp** — May 2017 – January 2019
- **Software Engineer, SDLC Corp** — June 2015 – April 2017
- **Programmer Analyst, Cognizant** — August 2014 – June 2015

</details>

## Research & education

- **Ph.D. — IIT / Lincoln University · Ongoing**
  Explainable multimodal AI and interpretable systems for clinically safe decision support.
- **M.Tech — Artificial Intelligence · 2017–2019**
  University of Hyderabad & IIIT Hyderabad (Research). Thesis: *Machine Learning Approaches for Understanding the Brain and Psychiatric Disorders*. Advisor: [Prof. Bapi S. Raju](https://www.iiit.ac.in/faculty/bapi-raju-s/).

### Publications

- **[ML Classifier Explanations with Diversified Prototype Counterfactuals](https://link.springer.com/book/9783031472237)** — AMRIT, Springer, 2023
- **[KEDOP: Keratoconus Early Detection of Progression Using Tomography Images](https://pubmed.ncbi.nlm.nih.gov/35343267/)** — European Journal of Ophthalmology, 2022
- **[Impact of COVID-19 Ripples on Cataract Surgical Care](https://ascrs.confex.com/ascrs/22am/meetingapp.cgi/Paper/84958)** — ASCRS, 2022
- **[Early Detection of Keratoconus Progression with Deep Learning on Tomography Images](https://journals.sagepub.com/doi/10.1177/11206721221087566)** — World Cornea Congress, 2020
- **Identifying Correlation Between Frontoparietal Networks and Other Cognitive Networks in Autism** — IEEE TENCON, 2019

## Recognition

- **Winner — ONDC-Bhashini Sprint 2024**, Ministry of Electronics and Information Technology, Government of India
- **Runner-up — Bhashini Velocity 2024**
- Represented the startup ecosystem at **London Tech Week** and **GITEX**

## Writing

Notes on machine learning, generative AI, and the ideas behind the systems.

<!-- BLOG-POST-LIST:START -->
- [Navigating the Abundance of LLM Content: A Comprehensive Guide](https://medium.com/kritrimlabs-ai/navigating-the-abundance-of-llm-content-a-comprehensive-guide-af41c1224531?source=rss-5f672468752e------2)
- [AnimateDiff: Revolutionize Text-to-Image Generation and Animation](https://panditshivam.medium.com/animatediff-revolutionize-text-to-image-generation-and-animation-33d74920cc11?source=rss-5f672468752e------2)
- [Why is everyone talking about large language models &lpar;LLMs&rpar;?](https://medium.com/kritrimlabs-ai/why-is-everyone-talking-about-large-language-models-llms-422d140fafa6?source=rss-5f672468752e------2)
- [Introduction to Neural Networks Part-2 &lpar;AND, OR and XOR Gate&rpar;](https://medium.com/kritrimlabs-ai/introduction-to-neural-networks-part-2-879d9660b929?source=rss-5f672468752e------2)
- [Introduction to Neural Networks Part-1](https://medium.com/kritrimlabs-ai/introduction-to-neural-networks-part-1-56324f7aa15d?source=rss-5f672468752e------2)
<!-- BLOG-POST-LIST:END -->
