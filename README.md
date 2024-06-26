
# Top 1000 YouTube Channels Analysis

This project provides an advanced analysis of the top 1000 YouTube channels globally. It includes various visualizations, model training for predicting subscriber count, and insightful conclusions.

## Project Overview

YouTube is the world's largest video-sharing platform, launched in 2005. With over 2 billion logged-in users monthly, it has become an essential platform for digital content and marketing. This dataset captures detailed information about the top-performing YouTube channels globally, including their rank, name, subscribers, video views, video count, category, and the year they started.

## Files Included

- `Top_Youtubers_Analysis.ipynb`: Jupyter notebook containing the complete analysis, visualizations, and model training.
- `Top Youtubers Dataset.csv`: The dataset used for the analysis (if you plan to include it).

## About Dataset

The Top 1000 YouTube Channels Dataset captures detailed information about the top-performing YouTube channels globally. This dataset includes the following columns:

- **Rank** : The ranking of the YouTube channel based on its overall popularity and performance.
- **Youtuber** : The name of the YouTuber or the title of the YouTube channel.
- **Subscribers** : The total number of subscribers to the channel, indicating its reach and popularity.
- **Video** **Views** : The total number of video views the channel has accumulated, reflecting its engagement and audience interaction.
- **Video Count** : The total number of videos uploaded by the channel, showing the content volume produced.
- **Category** : The genre or category the channel belongs to, such as music, education, entertainment, etc.
- **Started** : The year the channel was created, providing insight into its longevity and growth over time.

This dataset is invaluable for analyzing trends, understanding content strategies, and benchmarking channel performances within the YouTube ecosystem.

The dataset can be found in **Kaggle** : [Top 1000 YouTube Channels in the World 🌐📊🎥](https://www.kaggle.com/datasets/mayankanand2701/top-1000-youtube-channels-in-the-world)

## Analysis Summary

The analysis of the Top 1000 YouTube Channels dataset reveals several key insights:

1. **Popular Categories**: The most popular categories are Entertainment, Music, and Shows, with Entertainment having the highest number of channels.
2. **Correlation Analysis**: There is a strong correlation between the number of subscribers and video views, indicating that channels with more subscribers tend to have more video views.
3. **Growth Over Time**: The number of channels created each year has generally increased over time, with a noticeable spike in recent years.
4. **Top Channels**: MrBeast, T-Series, and YouTube Movies are the top 3 channels by subscribers, with MrBeast leading by a significant margin.
5. **Content Volume**: The distribution of video counts shows that most channels have uploaded a moderate number of videos, with few channels having an extremely high video count.
6. **Category Averages**: Categories like Music and Shows have the highest average subscribers and video views, indicating their strong appeal to audiences.
7. **Additional Analysis**: 
   - The correlation heatmap highlights significant relationships between key metrics.
   - The word cloud of categories visually emphasizes the prominence of popular categories.
   - The log scale distribution of subscribers provides a clearer view of the wide range of subscriber counts.
   - The ratio of subscribers to video views varies significantly across categories.
   - Subscriber growth over time analysis shows the rate at which channels gain subscribers relative to their years active.

## Model Training

A regression model is trained to predict subscriber count using features such as video views, video count, and category. The model achieved a respectable R-squared value, indicating its effectiveness in capturing the relationship between these features and subscriber count.

### Evaluation Metrics

- **Mean Absolute Error (MAE)**
- **R-squared (R2)**
  
### Predictive Model Insights

The predictive model for subscriber count demonstrates the potential for using machine learning to forecast channel growth. Future work could involve exploring more complex models and additional features to further improve predictive performance.

## Getting Started

To run the notebook locally:

1. Clone this repository:
   ```sh
   git clone https://github.com/debjit-mandal/top-youtubers-analysis.git
   cd top-youtubers-analysis
   ```
2. Ensure you have Jupyter Notebook installed. You can install Jupyter using Anaconda or pip:
   ```sh
   pip install jupyter
   ```
3. Open the Jupyter Notebook:
   ```sh
   jupyter notebook
   ```
4. In the Jupyter interface, navigate to `Top_Youtubers_Analysis.ipynb` and open it.

## Requirements

- Python 3.x
- pandas
- matplotlib
- seaborn
- scikit-learn
- wordcloud

You can install the required packages using pip:
```sh
pip install pandas matplotlib seaborn scikit-learn wordcloud
```

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any changes.