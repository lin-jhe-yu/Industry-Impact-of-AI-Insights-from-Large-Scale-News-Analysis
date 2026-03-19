<img width="1000" height="450" alt="Image" src="https://github.com/user-attachments/assets/e02e094c-0198-45a2-942e-c5f1a95944a4" />

# Industry Impact of AI: Insights from Large-Scale News Analysis
## Executive Summary

AI is rapidly transforming industries worldwide. But which sectors and companies are being impacted the most — and is the overall sentiment positive, negative, or uncertain?

Through large-scale analysis of **200,000+ news articles**, this project identifies the industries and companies most affected by AI, uncovers the key drivers of impact, and reveals adoption patterns across sectors.

**Key Findings:**
- AI is having the strongest positive impact on **Healthcare & Biotech**, **Semiconductors**, **Finance/FinTech**, **Technology**, and **Automotive**.
- Leading players include **OpenAI, Google, Microsoft, Amazon, Nvidia, Samsung**, and major pharmaceutical companies.
- **Cloud AI, Edge AI, and Data Infrastructure** are the primary drivers of confidence and successful adoption.
- **Retail & E-commerce** shows mixed sentiment due to workforce displacement and privacy concerns.
- Overall, AI drives **automation, augmentation, workflow redesign, and cost optimization**, while introducing regulatory, ethical, and talent-related risks.

The analysis provides a clear strategic view of where AI creates value and where challenges remain.

### Business & Strategic Impact
This project delivers actionable intelligence for:
- **Executives and strategists** evaluating AI investment and competitive positioning
- **Investors** seeking to understand AI-driven industry disruption
- **Policymakers and analysts** monitoring technology adoption trends
- **Technology leaders** aiming to benchmark their AI initiatives against industry peers

By combining topic modeling, entity recognition, and fine-tuned sentiment analysis, the solution transforms unstructured news data into clear, strategic insights.

### Solution Overview
We built an end-to-end NLP pipeline that:
- Processes and cleans large-scale news data
- Discovers 100+ latent topics using **BERTopic**
- Extracts key entities (companies, technologies, locations) with **spaCy Transformer NER**
- Performs domain-adapted sentiment analysis using fine-tuned **DistilBERT**
- Generates temporal trends and multi-level impact scoring
- Produces executive-level insights and visualizations

---

## Business Problem
News media contains rich, real-time information about AI adoption, breakthroughs, and challenges, yet this data is largely unstructured and overwhelming in volume.

We address three core questions:
1. **Which industries and companies are most impacted by AI?**
2. **Is the impact predominantly positive, negative, or uncertain across sectors?**
3. **What technologies, infrastructure, and success factors drive effective AI adoption?**

---

## Data Overview
- **Scale**: 200,000+ news articles
- **Time Period**: Focused on recent years with emphasis on 2022–2026 trends
- **Content**: Global news coverage spanning technology, business, healthcare, finance, automotive, and more

**Why this scale matters**: Only large-scale, real-world text data can reveal meaningful industry-wide patterns and temporal shifts in AI sentiment and adoption.

---

## Methodology

<img width="1119" height="579" alt="Image" src="https://github.com/user-attachments/assets/5e345619-63c4-4d43-891f-9cd70085e676" />

**Core Technologies**: PySpark, BERTopic, spaCy, DistilBERT (Hugging Face), LLM APIs, Pandas, Tableau/PowerPoint

---

## Full Presentation

Please find the **complete insight dashboard** with all visualizations, temporal trends, topic deep-dives, and strategic recommendations here:

**[Full Executive Dashboard: Industry Impact of AI](https://github.com/lin-jhe-yu/Industry-Impact-of-AI-Insights-from-Large-Scale-News-Analysis/blob/main/NLP%20Final%20Project.pdf)**
