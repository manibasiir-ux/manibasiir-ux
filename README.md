# Mani Basir · ML/AI Engineer

**I build machine learning for physical systems: robots, industrial machines, and the people who operate them.**

ML/AI engineer focused on perception, multimodal AI and machine learning for robotics. Before ML I worked in industrial automation (Siemens PLC, EPLAN, RoboDK), so I design models around the machine they run on and the operator who has to trust them.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-mani--basir-0A66C2)](https://www.linkedin.com/in/mani-basir) [![Email](https://img.shields.io/badge/Email-manibasiir%40gmail.com-D14836)](mailto:manibasiir@gmail.com)

## If you only have 60 seconds

| Want to see | Start here | What it shows |
|---|---|---|
| ML on industrial data | [Manine](https://github.com/manibasiir-ux/Manine) | Imbalanced classification, choosing a model by the cost of a missed failure, SHAP explanations, a working app |
| Unsupervised ML at scale | [AI_Jobs_Market_Clustering](https://github.com/manibasiir-ux/AI_Jobs_Market_Clustering) | 90,000 records, three pipelines, KMeans vs DBSCAN vs hierarchical, three cluster-validity metrics |
| Engineering discipline | [TIMBRE](https://github.com/manibasiir-ux/TIMBRE) | 520 automated tests, CI with a bundle-size gate, Lighthouse accessibility 100, Docker |
<!-- Add your deep learning / computer vision projects as the first rows -->

## Projects

### Manine: explainable failure-risk prediction for industrial machines
Predicts whether a drill, lathe or mill is at risk of failure from temperature, vibration, power and humidity, and explains each prediction with SHAP. The data is 70/30 imbalanced, so I chose a class-balanced model that actually catches failures over models with higher accuracy that mostly predicted "normal". The README documents the trade-off and its limits.

**Signal:** imbalanced learning · model selection by error cost · explainable AI · ML deployment (Streamlit)

### AI Jobs Market Clustering
Segments ~90,000 AI job records to show where hiring is hard, where pay is competitive, and which roles carry the most risk. Three business questions, three preprocessing pipelines (PCA, TruncatedSVD), and clusters validated with silhouette, Davies-Bouldin and Calinski-Harabasz scores.

**Signal:** unsupervised learning · dimensionality reduction · cluster validation · written analysis

### TIMBRE: audio-reactive web application
A WebGL sculpture driven by live audio analysis, built from a written spec to deployment. Verified with 326 unit and 194 end-to-end tests across Chromium and WebKit, plus a manual screen-reader pass that found two bugs no automated tool caught.

**Signal:** testing · CI/CD · performance budgets · accessibility · shipping end to end

## How I work

| Area | Approach |
|---|---|
| Evaluation | Compare against a baseline, pick the metric that matches the cost of being wrong, and keep weak results visible |
| Testing | Unit and end-to-end tests behind CI gates before anything ships |
| Real-world context | Think from the machine and the operator back to the model, from PLC control logic to ML predictions |

## Stack

**ML:** Python · scikit-learn · [DL FRAMEWORK] · SHAP · pandas · NumPy
**AI systems:** LLM APIs · multimodal (text + audio) pipelines · n8n · Streamlit
**Engineering:** Docker · GitHub Actions · Playwright · TypeScript · Next.js
**Industrial automation:** Siemens S7 (TIA Portal, STEP 7) · EPLAN Electric P8 · RoboDK

## What I'm looking for

Machine Learning Engineer · AI Engineer · Computer Vision Engineer · Perception Engineer · Deep Learning Engineer

Ideally on a robotics team. Open to remote work and to relocating to the US, Europe (Germany first) or Japan, with visa sponsorship.
