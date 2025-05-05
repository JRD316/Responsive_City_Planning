# NLP-Driven Social Media Monitoring & Evaluation Framework

A reusable end-to-end pipeline combining state-of-the-art NLP with publication-quality visualizations to track public discourse, sentiment, and emerging themes on any topic. This repository demonstrates the approach through a case study of Bogotá’s TransMiCable project—but the same methods apply to transit systems, public policy, brand tracking, or community engagement.

---

## 🚀 Key Capabilities

1. **Modular Data Pipeline**  
   - Ingests raw social-media exports (CSV/Excel)  
   - Cleans, standardizes, and timestamps posts into uniform quarters/weeks  

2. **NLP Labeling & Validation**  
   - Applies sentiment analysis, multi-class emotion detection, and zero-shot classification  
   - Extracts dynamic topics with BERTopic and aspect keywords with KeyBERT  
   - Validates social-media–derived indices against independent survey benchmarks  

3. **Rich Visual Storytelling**  
   - **Treemaps** for content share by topic, origin, sentiment, and emotion  
   - **Stacked-area timelines** with smooth interpolation to reveal quarterly trends  
   - **Sankey diagrams** illustrating flows between sentiment → topic → emotion  
   - **Heatmaps**, **bubble charts**, and **word clouds** for deeper aspect-level insights  

4. **Alerting & Rumor Flagging**  
   - Zero-shot classification to spot emergent “scare” narratives  
   - Rule-based triggers (e.g., weekly rumour-post thresholds) for real-time dashboards  

5. **Reproducible & Extensible**  
   - All notebooks runnable in Google Colab or locally via Jupyter  
   - Clear directory structure, requirements.txt, and exported figures/HTML  
   - Easily swap in new data sources, models, or custom lexicons  

---

## 📂 Repo Layout

