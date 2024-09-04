# News-Driven-stock-Market-Analysis

Exploratory Data Analysis (EDA) on the impact of news sentiment on stock market trends, including stock price movements and volatility. This project investigates how news headlines and sentiment influence stock market dynamics, using various data visualization and analysis techniques.

## Below are the instructions and commands you'll need to set up and work with this project:

### Clone the Repository

#### Run the following command to clone the repository to your local machine and navigate into the project directory:

git clone YOUR_REPOSITORY_URL<br>
cd your-repository

### Set Up a Virtual Environment

#### Create and activate a virtual environment using the commands below:

On Windows:<br>
python -m venv venv<br>
venv\Scripts\activate

On macOS/Linux:<br>
python3 -m venv venv<br>
source venv/bin/activate

### Install Dependencies
#### Install the required dependencies from the requirements.txt file:
pip install -r requirements.txt

## Exploratory Data Analysis (EDA) Steps

### Descriptive Statistics
- **Textual Lengths**: Analyze basic statistics for headline lengths in the Financial News dataset to understand the distribution of text lengths.
- **Article Counts**: Count the number of articles per publisher to identify the most active publishers.
- **Publication Trends**: Examine publication dates to identify trends and patterns in news frequency over time.

### Text Analysis
- **Sentiment Analysis**: Perform sentiment analysis on headlines to classify sentiments as positive, negative, or neutral, helping to understand the influence of news sentiment on stock market trends.
- **Keyword Extraction**: Use natural language processing to extract common keywords, phrases, and significant events from headlines to identify relevant news topics and their potential impact on stock prices.

### Time Series Analysis
- **Publication Frequency**: Investigate how the frequency of article publications varies over time and identify any spikes related to significant market events.
- **Publishing Times**: Analyze if there are specific times when most news is published, providing insights into trading patterns and market reactions.

### Publisher Analysis
- **Publisher Contributions**: Identify which publishers contribute the most news and analyze differences in the types of news reported to assess the influence of various sources on market trends.
- **Domain Analysis**: For datasets with email addresses as publisher names, extract unique domains to determine which organizations contribute more frequently and may have greater influence.

### Technical Indicators
- **TA-Lib**: Calculate technical indicators such as moving averages, RSI (Relative Strength Index), and MACD (Moving Average Convergence Divergence) using the Stock Price Integration Dataset to analyze stock price movements and volatility.

## Correlation Analysis
- **Pearson Correlation:** Initially assessed the linear relationship between sentiment and daily stock prices. Results showed an almost negligible linear relationship.
- **Spearman's Rank Correlation:** Applied to capture potential monotonic relationships. Similar results to Pearson’s correlation indicated that sentiment alone may not have a significant impact.
- **Lagged Correlation:** Investigated if sentiment has a delayed effect on stock prices. Results suggested that news sentiment alone might not significantly affect stock prices, and its impact could be more pronounced when integrated with other factors.


### Data Visualization
- **Visualizations**: Create charts and graphs to illustrate data insights, the impact of news sentiment on stock prices, and the relationships between different indicators. This helps visualize the correlation between news sentiment and stock market trends.
