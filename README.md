# Text_Generation_Topsis_Best_Models_102217106_DeepanshPatni

# Text Generation Model Evaluation

## Overview
This project evaluates different text generation models using multiple performance metrics and ranks them using the *TOPSIS* method. The analysis includes *GPT-4, Gemini 1.5 Pro, Claude 2.1, LLaMA 2, and MPT-30B, comparing their **Perplexity (PPL), BLEU Score, ROUGE Score, Diversity Metrics, Latency, and Memory Usage*.

## Methodology
### Metrics Used
- *Perplexity (PPL):* Measures how well a model predicts a dataset (lower is better).
- *BLEU Score:* Evaluates text quality compared to a reference (higher is better).
- *ROUGE Score:* Measures similarity to a reference text (higher is better).
- *Diversity Metrics:* Assesses variability in generated text (higher is better).
- *Latency:* Measures response time (lower is better).
- *Memory Usage:* Evaluates computational cost (lower is better).

### TOPSIS Ranking
TOPSIS (Technique for Order of Preference by Similarity to Ideal Solution) ranks models based on their proximity to an ideal performance.

## How to Run the Notebook
1. Clone this repository:
   ```sh
   git clone https://github.com/your-repo/Text-Generation-Evaluation.git
   cd Text-Generation-Evaluation

This evaluation provides insights into different text generation models and ranks them objectively. Depending on your use case (accuracy, creativity, efficiency), you can select the best model accordingly.

# Analysis of Model Performance and Results

## Decision Matrix Analysis
The decision matrix shows how each model performs across different evaluation metrics.

### Key Observations:
- *GPT-4* performs well in most areas but has *higher latency and memory usage*.
- *Gemini 1.5 Pro* scores the highest in *BLEU and diversity, making it a **strong candidate for creative tasks*.
- *Claude 2.1* excels in *ROUGE, meaning it is **well-suited for summarization tasks*.
- *LLaMA 2 and MPT-30B* provide open-source alternatives but are slightly weaker in performance compared to proprietary models.

## TOPSIS Ranking Insights
A bar chart visualizes the *TOPSIS ranking*, which balances all metrics to determine the most optimal model.

### Rank Summary:
1. *GPT-4* – Best all-rounder but resource-intensive.
2. *Gemini 1.5 Pro* – Excels in BLEU and diversity.
3. *Claude 2.1* – Strong in ROUGE but lower in diversity.
4. *LLaMA 2* – Decent but weaker in latency and memory.
5. *MPT-30B* – Competitive but falls short in overall efficiency.

## Graph Interpretations
### Decision Matrix Heatmap:
- Darker colors indicate *stronger performance in each category*.
- *GPT-4 and Gemini 1.5 Pro* dominate across multiple metrics.

### TOPSIS Bar Chart:
- Models are ranked based on their overall score.
- *GPT-4 and Gemini 1.5 Pro* are at the top, with *Claude 2.1* closely following.

## Conclusion
- If *efficiency and creativity* are important, *Gemini 1.5 Pro* is a strong choice.
- If you need *accuracy and robustness, **GPT-4* is ideal.
- *Claude 2.1* is great for summarization-based tasks.
- Open-source models like *LLaMA 2 and MPT-30B* are viable but trade off some performance.

Each model has *strengths and trade-offs*, so choosing the right one depends on your use case
