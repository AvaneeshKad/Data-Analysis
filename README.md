# YouTube Data Analysis Project

This repository contains a comprehensive data analysis of YouTube video trends and metrics. The project utilizes Python and Jupyter Notebooks to clean, process, and visualize data to uncover insights into viewer engagement, content performance, and category trends.

## 📊 Project Overview

The primary goal of this analysis is to explore YouTube datasets to understand the underlying mechanics of viral content and audience behavior. By leveraging statistical methods and visual storytelling, this project identifies patterns that differentiate high-performing videos from the rest.

### 🔍 Deep Dive into the Analysis

The analysis goes beyond surface-level metrics to investigate several complex dimensions of the data:

* **Engagement Dynamics:** A detailed look at the correlation between views, likes, and comment counts. We explore whether high engagement strictly follows high view counts or if certain "niche" categories boast higher loyalty and interaction rates despite lower reach.
* **Temporal Trending:** Analyzing "Trending" durations. How long does a video stay relevant on the trending page? We map the velocity of views from the moment of upload to peak performance to identify the "half-life" of viral content.
* **Tag & Metadata Impact:** Examining the influence of tags and title length on discoverability. The project looks at high-frequency terms in top-performing categories to see how metadata optimization affects a video's likelihood of trending.
* **Category Distribution:** A cross-sectional analysis of which genres (e.g., Entertainment vs. Education vs. Gaming) dominate the charts and how the distribution of these categories varies by region.
* **Sentiment Analysis (Proxy):** Assessing the ratio of likes to dislikes as a proxy for audience sentiment and how this feedback loop influences the YouTube algorithm's recommendation engine.

## 🛠️ Requirements

To run the analysis locally, you will need the following Python libraries installed:

```bash
pip install pandas numpy matplotlib seaborn scipy

```
## 📈 Key Visualizations

The notebook includes several key plots to aid interpretation:

Correlation Heatmaps: To visualize the strength of relationships between numerical variables.

Category-wise Bar Charts: Identifying which genres dominate the trending charts.

Time-Series Graphs: Plotting view growth trends over the duration of the dataset.
