# Project Description
Vehicle crashes involve complex interactions between road users, split-second decisions, and challenging environmental conditions. Among these, two-vehicle crashes are the most prevalent. Accounting for approximately 70% of roadway crashes, they present a significant challenge to traffic safety. Identifying Driver Hazardous Action (DHA) is essential for understanding crash causation, yet the reliability of DHA data in large-scale databases is limited by inconsistent and labor-intensive manual coding practices. Here, we present an innovative framework that leverages a fine-tuned large language model (LLM) to automatically infer DHAs from textual crash narratives, thereby improving the validity and interpretability of DHA classifications.
# Core Files
"MTCF_NARRATIVE.ipynb" gives the main process of how we reformulate original tabulated crash data in MTCF to structured crash narratives;
"LLAMA_FINETUNING.ipynb" provides the main process of how we set up the fine-tuning flows using A 1B LLM (LLama 3.2 1B);
"LLAMA_PROBABILITY.ipynb" illustrates the main process of an explainable approach regarding the quantified probability-based LLM outputs in the context of simulating couterfactual risky crash scenarios.
# Data Access
Full data access is open to public, a link is provided below:
https://www.michigantrafficcrashfacts.org, access the data may require permissions from the provider.
