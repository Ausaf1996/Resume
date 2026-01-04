<style>
  /* Global Layout */
  body { 
    font-family: "Inter", "Helvetica", "Arial", sans-serif; 
    line-height: 1.4; 
    color: #000 !important; 
    background-color: #fff !important;
    max-width: 850px; 
    margin: 0 auto; 
    font-size: 10.5pt; 
  }
  
  /* Vertical Line Separator */
  .pipe { color: #666; margin: 0 10px; font-weight: 300; }
  
  /* Header Styling */
  h1 { text-align: center; margin-bottom: 4px; font-size: 24pt; letter-spacing: -1px; border: none; }
  .contact-bar { text-align: center; font-size: 9.5pt; color: #333; margin-bottom: 15px; }
  
  /* Section Headings */
  h2 { 
    border-bottom: 1px solid #000; 
    margin-top: 20px; 
    margin-bottom: 10px; 
    font-size: 12pt; 
    text-transform: uppercase; 
    letter-spacing: 1.5px;
    padding-bottom: 2px;
  }
  
  /* Experience & Education Headers */
  .exp-header { 
    margin-top: 12px; 
    margin-bottom: 0px; 
    font-size: 11pt; 
    display: flex; 
    justify-content: space-between; 
    align-items: baseline; 
  }
  .company { font-weight: bold; }
  .edu-header-plain { font-weight: normal; font-size: 11pt; } /* Removed all bolding */
  .date { font-weight: normal; font-size: 10pt; color: #333; }
  
  /* Context Styling */
  .context { 
    font-style: italic; 
    color: #555; 
    font-size: 9.5pt; 
    display: block; 
    margin-top: 0px; 
    margin-bottom: 8px; 
  }

  /* Page Break for Magnit */
  .magnit-section { 
    page-break-before: always; 
  }
  
  /* Skills Styling */
  .skill-item { margin-bottom: 5px; display: block; font-weight: normal; text-align: justify;}
  .category { font-weight: bold; }

  /* Sub-headings */
  .sub-sect { font-weight: bold; font-size: 10pt; margin-top: 8px; margin-bottom: 4px; display: block; text-decoration: underline; }
  
  ul { margin-top: 0; padding-left: 20px; }

  /* Bullet Point Styling */
  li { 
    margin-bottom: 4px; 
    text-align: justify;
    hyphens: none; 
    word-break: keep-all;
    -webkit-hyphens: none;
    -ms-hyphens: none;
  }

  /* Summary Styling */
  .summary-text {
    text-align: justify;
    hyphens: none;
    word-break: keep-all;
    -webkit-hyphens: none;
    -ms-hyphens: none;
  }
</style>

# AUSAF QS
<div class="contact-bar">
  Macquarie Park, NSW 2113 <span class="pipe">|</span> +61 403 138 910 <span class="pipe">|</span> ausaf1996@gmail.com
</div>

## Summary
<div class="summary-text">
Principal AI Engineer with 5 years of experience (3 years in Australia) specializing in the full-lifecycle delivery of Agentic AI systems and cloud-native data products. Expertise in <b>Product Strategy, Agentic Architecture, and AI Governance</b> with a proven track record of <b>integrating AI into complex business processes</b> to drive measurable revenue growth.
</div>

## Experience

<div class="exp-header">
  <span class="company">Principal AI Engineer <span class="pipe">|</span> VentureCrowd <span class="pipe">|</span> Australia</span> 
  <span class="date">Jan 2023 – Present</span>
</div>
<span class="context">Leading AI strategy and deployment for Australia’s leading digital equity crowdfunding platform.</span>

<span class="sub-sect">Product Strategy & Revenue Growth</span>
- **Spearheaded** the conceptualization and launch of a new **Venture Benchmarking Data Product** which measures 30+ growth metrics from previously successful ventures to provide benchmarks for new startups to raise capital; revenue stream projected at **$500k ARR**.
- **Engineered** a proprietary **Investor Likelihood Engine** to calculate likelihood to investment scores using regression analysis based on existing and enriched data for identifying "hidden" wholesale-qualified investors; contributed to **>$2M in investments**.
- **Optimized** the Founder onboarding funnel by architecting an **Agentic Data Enrichment layer**; leveraged autonomous web-scraping to pre-populate venture profiles, reducing registration friction and slashing profile completion time from 4 hours to <60 minutes, **improving conversion by 20%**.

<span class="sub-sect">Technical Architecture & Agentic Systems</span>
- **Designed** and deployed a **closed-loop Agentic Email marketing tool** in collaboration with the marketing team using **CrewAI**; automated the end-to-end drafting and A/B testing of new self generated variations, resulting in a **15% increase in CTR** (continuous self-improving) and 90+ hours saved weekly.
- **Developed** and scaled a company-wide **Low-Code AI Framework** through custom tool-building and integrations; **upskilled cross-functional teams** to build and maintain bespoke agents, achieving an exponential increase in organizational automation velocity.
- **Optimized** internal data accessibility by deploying custom **Data Analysis Chatbots** (leveraging Agentforce and AWS Bedrock); implemented **DeepEval** frameworks and deterministic prompting strategies to **minimize hallucinations and query misinterpretation**, reducing cross-team reporting requests by 70%.

<span class="sub-sect">Governance, LLMOps & ROI Measurement</span>
- **Implemented** a robust security middleware layer using **LlamaGuard**; enforced real-time safety guardrails to ensure 100% of LLM outputs met **Australian financial regulatory standards**.
- **Integrated** **MLflow** into Agentic workflows to monitor internal reasoning chains using **Postgres and AWS S3**; established full observability into LLM "thought processes" to ensure transparency and auditability.
- **Designed** and launched **Executive ROI Dashboards in Tableau**; visualized real-time KPIs including increase in wholesale conversion rates, AI-attributed revenue, sale of new products, and **"Time-Saved-to-Dollar"** efficiency metrics for the board.

<div class="magnit-section">
<div class="exp-header">
  <span class="company">Data Scientist <span class="pipe">|</span> Magnit Global <span class="pipe">|</span> India</span> 
  <span class="date">Jan 2021 – Jan 2023</span>
</div>
<span class="context">Executed end-to-end data science initiatives for a recruitment technology startup (acquired by Magnit Global).</span>

- **Built** an autonomous chatbot to directly engage users and encourage resume submissions; **increased candidate applications by 15%** through automated top-of-funnel engagement.
- **Developed** custom **Named Entity Recognition (NER)** models to extract specialized skills from unstructured data; achieved **90% precision** in professional experience mapping for the core engine.
- **Engineered** a multi-directional matching system (Resume-to-Job, Job-to-Job, Resume-to-Resume) utilizing **Sentence-Transformers (SBERT)** and custom vector embeddings; **increased candidate discovery accuracy and relevance by 30%** compared to traditional keyword matching.
- **Architected** and deployed matching algorithms as production-ready **REST APIs using Swagger**; managed the full containerization and deployment lifecycle on **AWS**.
- **Led** the competitive analysis and performance benchmarking of 3rd-party AI models; delivered **"build-vs-buy" reports** to executive leadership that guided the long-term AI product roadmap.
- **Designed** and implemented **ETL pipelines in PostgreSQL** using scheduled materialized views; drastically reduced dashboard load times for monitoring **conversion funnels, Time-to-Hire, and source tracking**.
</div>

## Technical Skills

<div class="skill-item">
  <span class="category">AI & Systems Architecture:–</span> Agentic Frameworks (LangGraph, CrewAI), Evaluation (RAGAS, DeepEval), Guardrails (LlamaGuard), RAG, LLMOps, NLP, Deep Learning, Machine Learning
</div>
<div class="skill-item">
  <span class="category">Cloud & Infrastructure:–</span> AWS (Bedrock, Fargate, Lambda, S3, API Gateway, ECS), Infrastructure as Code (IaC), CI/CD, Docker, GitOps, ETL Pipelines
</div>
<div class="skill-item">
  <span class="category">Data Engineering & Visualization:–</span> Python, SQL, PostgreSQL, Embedding Models, Custom API Integration, Data Sync Automation, Tableau, Metabase
</div>

## Education

<div class="exp-header">
  <span class="edu-header-plain">Master of Data Science <span class="pipe">|</span> Deakin University <span class="pipe">|</span> Melbourne</span> 
  <span class="date">July 2019 – July 2021</span>
</div>

<div class="exp-header">
  <span class="edu-header-plain">Bachelor of Mechanical Engineering <span class="pipe">|</span> Osmania University <span class="pipe">|</span> India</span> 
  <span class="date">June 2014 – June 2018</span>
</div>