

This project uses sentiment analysis and topic modeling to assess consumer reactions to Treehut's social media posts. We discovered that certain products (e.g., body scrubs and seasonal scents) drove highly positive engagement, while packaging concerns emerged in lower-sentiment clusters.

Key visualizations highlight the relationship between sentiment and engagement, time-based emotional patterns, and frequently mentioned topics. The bubble plot was particularly useful in surfacing high-engagement, low-sentiment posts that may require brand attention.

---

## Project Structure

```
treehut-insights/
├── engagements.csv
├── comment_analysis.ipynb
└── README.md
```

---

## Key Visualizations + Insights

<img width="1324" height="769" alt="Screenshot 2025-07-14 at 2 31 04 PM" src="https://github.com/user-attachments/assets/2b2b5143-841e-4c69-b0b4-8ee68eb0f92e" />

- Sentiment vs. Engagement Bubble Plot**  
  Larger bubbles represent posts with more comments. Posts with high engagement but negative sentiment may indicate product issues or controversial topics.

---

## How to Run

1. Open repository in jupyter notebook, google colab or similar environment
2. Ensure project structre is maintained
3. Run all code cells
---

## Extension Proposal

If given additional time, I would expand the project by:

1. **Deploying a real-time dashboard** using Streamlit to monitor live comments and alerts.
2. **GPT-based topic labeling** to group sentiment by product or theme using natural clusters.
3. **Multi-modal engagement scoring** by combining likes, shares, and comments.
4. **Tagging user-generated content** mentions to help the brand find UGC for reuse.
5. **Benchmarking performance** by comparing March data to previous months.

---

## AI & Tool Usage Disclosure

This project used the following AI and software tools:

- **GPT-4 (ChatGPT)**: Code Library research, Debugging, Boilerplate template generate
- **Python Libraries**:  
  - `pandas`, `matplotlib`, `seaborn`: Data manipulation & visualization  
  - `nltk`, `vaderSentiment`: NLP & sentiment analysis  
  - `scikit-learn`: TF-IDF topic modeling  
  - `ipywidgets`: Interactive sliders in Jupyter  
- **Bubble plots, bar charts, line graphs**: Generated via `seaborn` and `matplotlib`


