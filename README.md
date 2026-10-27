**Portfolio:** [panditshivam.github.io ↗](https://panditshivam.github.io/)

# Shivam Dwivedi

**Principal Data Scientist · Machine Learning Solution Architect**

[LinkedIn](https://linkedin.com/in/panditshivam) · [Medium](https://medium.com/@panditshivam) · [Email](mailto:shivampandit@icloud.com)

I design, evaluate, and deliver enterprise AI systems—from problem definition and proof of concept to production architecture. My **12+ years** span generative AI, LLMs, predictive modeling, multilingual voice AI, and explainable machine learning.

At **Code & Theory**, I lead the **India ML/AI engineering team**, combining hands-on architecture with technical direction, mentoring, delivery ownership, and production readiness. My current focus is GraphRAG, agentic decision support, grounded LLM evaluation, and multimodal AI. I’m also pursuing a **Ph.D. at IIT Patna** in explainable multimodal AI for clinically safe decision support.

## Selected work

| Focus | What I built | Selected result |
| :--- | :--- | :--- |
| **Grounded enterprise AI** | GraphRAG with source traceability and a formal retrieval/answer evaluation framework | **89% multi-hop fact recovery** versus 53% in an internal comparison across 22 questions in six categories |
| **Pricing & decision support** | Production pricing, controlled experiments, and an agentic “Explain the Price” system | Pricing coverage of **~$1.6B in trailing-12-month revenue**; experiments contributed **$13.5M+ estimated annualized margin impact** across eight tests |
| **Content intelligence** | Hybrid retrieval, recommendations, and LLM-assisted editorial workflows on GCP | A **multi-million-article corpus**, with **50%+ less manual curation** |
| **Generative vision** | Modular Python services for image-conditioned generation, segmentation, and controllable multimodal workflows | SDXL, LoRA, IP-Adapter, SAM-HQ, and GroundingDINO with stage-level tracing and regression checks |
| **Multilingual voice AI** | Real-time translation and voice-assisted digital commerce at Pulastya AI | Approximately **0.45-second end-to-end latency** and **3,000+ bilingual pilot calls** |
| **Healthcare research** | Explainable CNN models with clinicians at L. V. Prasad Eye Institute | Tomography research using **1,200+ subjects**, published in the European Journal of Ophthalmology |

## Expertise

| Area | Methods & tools |
| :--- | :--- |
| **Data science & statistics** | Predictive modeling, hypothesis testing, A/B testing, temporal validation, pricing, customer analytics |
| **Machine learning & explainability** | PyTorch, TensorFlow, scikit-learn, XGBoost, LightGBM, computer vision, counterfactual explanations |
| **GenAI, agents & evaluation** | Agentic workflows, tool use, context engineering, LLM grounding, prompt and agent evaluation, LangChain, LlamaIndex |
| **Graphs, retrieval & multimodal AI** | GraphRAG, Neo4j, hybrid search, embeddings, NLP, Stable Diffusion XL, LoRA, SAM, GroundingDINO |
| **Architecture & MLOps** | Kedro, Argo Workflows, Docker, Kubernetes, CI/CD, experiment tracking, observability, regression checks, model serving |
| **Data platforms & cloud** | Python, Java, SQL, GCP, AWS, Azure, BigQuery, Cloud Spanner, Vertex AI, Kafka, Spark, Airflow |

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

**Engineering leadership**

- Lead the India ML/AI engineering team, set technical direction, mentor engineers, and review architecture and implementation.
- Own delivery and production readiness across enterprise AI platforms, from problem formulation and PoC to evaluation, deployment, and operations.

**Commercial Pricing & ML Decision Intelligence**

- Architected a production pricing decision framework combining transaction-level feature engineering, comparable-price logic, recency and transaction weighting, conversion-rate adjustments, ML recommendations, and multi-layer commercial guardrails.
- Operationalized reusable data and model pipelines through Kedro and Argo, with lineage, regression validation, and memory/runtime optimization.
- Designed an agentic “Explain the Price” system that connects model outputs, costs, discounts, order-size adjustments, and active experiments, with follow-up questions on comparable deals and win likelihood.
- Architected a pricing engine covering **~$1.6B in trailing-12-month revenue**, built on **~$8.8B in historical transactions**; controlled experiments contributed **$13.5M+ in estimated annualized margin impact across eight tests**.

**Customer Attrition & Enterprise Churn Modeling**

- Designed a leakage-safe customer attrition model using 31 behavioral, volume, product-mix, quote, and lead-time inputs over four-quarter observation windows to predict 50%+ next-quarter volume decline.
- Converted churn probabilities into revenue and volume at risk, identifying approximately **2,430 significant-reduction customers per quarter** representing roughly **243M T12M lbs**, and translated the scores into intervention priorities and controlled validation plans.
- Built an enterprise portfolio churn framework combining financial, contractual, organizational, people, and engagement signals into entity-level predictors of relationship risk.

**Experimentation & Economic Signal Intelligence**

- Designed and evaluated controlled pricing experiments across material/form adders, large-order discounts, recommendation methods, and adoption scenarios, reconciling win-rate movement with gross-margin economics through sensitivity and break-even analysis.
- Built a signal-engineering pipeline across 52 external indicators, mapping signals to end markets, applying STL seasonal adjustment and PPO transformations, and validating relationships against end-market-specific volume.

**Quality Intelligence, GraphRAG & Applied AI**

- Lead the design of a structural-intelligence platform for large codebases, combining deterministic program analysis, graph-based reasoning, evidence-gated decisions, explainability, and large-scale evaluation.
- Architected and benchmarked an enterprise GraphRAG system combining entity-relationship graphs, semantic traversal, and vector retrieval; achieved **89% multi-hop fact recovery versus 53% for a leading enterprise benchmark** and **2.9× faster average inference** across **22 ground-truth questions in six categories**.
- Built a formal retrieval and LLM evaluation framework that separates retrieval quality from answer quality and includes adversarial and out-of-scope cases.
- Improved internal GraphRAG evaluation quality from **43.1% to 54.6%**, with **zero confirmed hallucinations in the reported evaluation** after retrieval, traversal, and grounding refinements.
- Led architecture for a production content-intelligence platform across a **multi-million-article corpus**, combining hybrid retrieval, ranking, recommendations, entity intelligence, external trends, and geospatial signals; reduced manual curation by **50%+**.
- Designed LLM-assisted tagging, drafting support, retrieval augmentation, and distribution workflows using BigQuery, Cloud Spanner, and Vertex AI, with prompt/version control, tracing, observability, and regression checks.

**Generative Vision & Multimodal AI**

- Re-engineered node-based generative workflows into modular Python services using **Stable Diffusion XL, LoRA, IP-Adapter, SAM-HQ, and GroundingDINO** for image-conditioned generation, segmentation, and controlled multimodal workflows.
- Added stage-level tracing, artifact validation, model/config versioning, deterministic controls, and regression checks to support reproducibility and production readiness.

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

- **Ph.D. — IIT Patna · Ongoing; expected completion 2028**
  Explainable multimodal AI for clinically safe decision-support systems. Advisor: **Dr. Chandranath Adak**.
- **M.Tech — Artificial Intelligence · 2017–2019**
  University of Hyderabad & IIIT Hyderabad (Research). Thesis: *Machine Learning Approaches for Understanding the Brain and Psychiatric Disorders*. Advisor: [Prof. Bapi S. Raju](https://www.iiit.ac.in/faculty/bapi-raju-s/).

### Publications

- **[ML Classifier Explanations with Diversified Prototype Counterfactuals](https://link.springer.com/book/9783031472237)** — AMRIT, Springer, 2023
- **[KEDOP: Keratoconus Early Detection of Progression Using Tomography Images](https://pubmed.ncbi.nlm.nih.gov/35343267/)** — European Journal of Ophthalmology, 2022
- **[Impact of COVID-19 Ripples on Cataract Surgical Care](https://ascrs.confex.com/ascrs/22am/meetingapp.cgi/Paper/84958)** — ASCRS, 2022
- **[Early Detection of Keratoconus Progression with Deep Learning on Tomography Images](https://journals.sagepub.com/doi/10.1177/11206721221087566)** — World Cornea Congress, 2020
- **Identifying Correlation Between Frontoparietal Networks and Other Cognitive Networks in Autism** — IEEE TENCON, 2019

## Learning & credentials

- **MongoDB:** Deploying and Evaluating GenAI Apps Learning Badge Path
- **Anthropic:** Introduction to Model Context Protocol; Introduction to Agent Skills; Claude Code in Action; Building with the Claude API
- **Hugging Face:** Fundamentals of MCP

## Recognition

- **Winner — ONDC-Bhashini Sprint 2024**, Ministry of Electronics and Information Technology, Government of India
- **Runner-up — Bhashini Velocity 2024**
- Represented the startup ecosystem at **London Tech Week** and **GITEX**

## Writing

Notes on machine learning, generative AI, and the ideas behind the systems.

<!-- BLOG-POST-LIST:START -->
- [Sixteen JAX devices on a CPU, and one gradient bug worth finding](https://panditshivam.medium.com/sixteen-jax-devices-on-a-cpu-and-one-gradient-bug-worth-finding-a7df944acfbf?source=rss-5f672468752e------2)
- [PaperPilot runs locally. Your agent still has a data boundary.](https://panditshivam.medium.com/paperpilot-runs-locally-your-agent-still-has-a-data-boundary-1eff29fe768b?source=rss-5f672468752e------2)
- [The first LLM router metric I check is the missing-row count](https://panditshivam.medium.com/the-first-llm-router-metric-i-check-is-the-missing-row-count-7a9eb72aaacb?source=rss-5f672468752e------2)
- [LitPivot makes a quiet research bug visible: the metric can outlive the idea](https://panditshivam.medium.com/litpivot-makes-a-quiet-research-bug-visible-the-metric-can-outlive-the-idea-666f1a94151d?source=rss-5f672468752e------2)
- [Claude can write the proof. You still have to choose the theorem.](https://panditshivam.medium.com/claude-can-write-the-proof-you-still-have-to-choose-the-theorem-c697de4a8298?source=rss-5f672468752e------2)
<!-- BLOG-POST-LIST:END -->
