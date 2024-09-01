# Tackling COVID-19 Misinformation: Sentiment Analysis and False Claims Detection on Twitter

## Project Overview
This project focuses on analyzing COVID-19-related tweets to identify sentiment patterns and detect misinformation on Twitter. We use sentiment analysis to understand public opinion and a false claims detection model to spot misinformation. The analysis helps in identifying sentiment clusters, understanding the influence of users, and exploring the relationship between sentiment and misinformation spread.

## Dataset
The project utilizes the LIAR dataset, which is designed for false claims detection. This dataset is used to train our model to evaluate the factual accuracy of tweets related to COVID-19.

## Approach
Our approach involves several key analyses aimed at understanding sentiment dynamics and misinformation spread on Twitter during the COVID-19 pandemic. These analyses include:

1. **Sentiment Analysis**: We analyze COVID-19-related tweets to gauge public sentiment and identify sentiment patterns.
2. **False Claims Detection**: We classify and detect instances of misinformation using a BERT model trained on the LIAR dataset to compute factual scores and evaluate the accuracy of claims made in tweets.
3. **Community Detection**: We use community detection algorithms to identify user groups with similar sentiment patterns.
4. **User Influence Analysis**: We investigate how influential users impact sentiment propagation within the network using centrality measures like degree centrality.
5. **Correlation Analysis**: We examine correlations between sentiment scores and network structure measurements to uncover patterns and insights.

## How to Use
1. **Clone the Repository**:
   ```bash
   git clone https://github.com/your-username/Tackling-COVID-19-Misinformation.git

2. **Run the Jupyter Book: Open the Jupyter Book to explore the analysis and visualizations:**:
   ```bash
   jupyter-book build .
   jupyter-book serve .

## Contributions
Contributions to this project are welcome! If you have any suggestions, improvements, or additional analyses, please feel free to submit a pull request or open an issue.

## License
This project is licensed under the Apache License - see the [LICENSE](http://www.apache.org/licenses/) file for details.

## Acknowledgments
We acknowledge the contributions of the research community in providing datasets and tools that made this project possible. Special thanks to William Yang Wang for his work on the LIAR dataset and his contributions to the field of misinformation detection.
