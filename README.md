# Walmart Melatonin Product Review Analysis

## Project Overview:
This project analyzes customer reviews for melatonin products sold on Walmart's website. The dataset contains over 22,000 reviews across various melatonin products, including different brands, dosages, and formulations.

## Dataset Description:
The dataset includes the following key information:

1. **Product Details**:
   - Product ID
   - Product Name
   - Product URL

2. **Review Content**:
   - Review Text
   - Review Title
   - Rating (out of 5)

3. **Customer Feedback**:
   - Positive Feedback Count
   - Negative Feedback Count

4. **Temporal Information**:
   - Submission Time (Date/Time when the review was posted)

## Key Features:
1. **Data Cleaning and Preprocessing**: 
   - Cleaning text data, handling missing values, and extracting dosage information.

2. **Sentiment Analysis**:
   - Analyzing the sentiment of review texts to understand customer satisfaction.

3. **Rating Distribution Analysis**:
   - Examining the distribution of ratings across products.

4. **Dosage Preference Analysis**:
   - Investigating the popularity and effectiveness of different melatonin dosages.

5. **Temporal Trends**:
   - Analyzing how reviews and ratings change over time.

## Technologies Used:
1. **Python 3.x**: Programming language used for analysis.
2. **Pandas**: For data manipulation and analysis.
3. **NumPy**: For numerical operations and array handling.
4. **Matplotlib** and **Seaborn**: For data visualization.
5. **NLTK**: For natural language processing (sentiment analysis).

## Setup and Installation:
To set up and run this project, follow the steps below:

1. **Clone the repository**:
   ```bash
   git clone https://github.com/RitikGupta2203/walmart-melatonin-analysis.git

2. **Install the requried libraries:
   ```bash
   pip install -r requirements.txt

3. **Run the Jupyter notebook:
   ```
   jupyter notebook FinalDataScience.ipynb


## Analysis Highlights:

### 1. **Data Preprocessing**:
   - Cleaning and normalizing review texts.
   - Handling missing values, especially in the review content and ratings.
   - Extracting dosage information from product titles and descriptions.

### 2. **Exploratory Data Analysis (EDA)**:
   - **Distribution of Ratings**: Examined the distribution of ratings across different products to understand customer satisfaction trends.
   - **Most Common Words in Reviews**: Analyzed the most frequently mentioned terms in customer reviews to identify key themes (e.g., "effective", "helpful", "sleep").
   - **Correlation Between Dosage and Rating**: Investigated if there is any relationship between the dosage of melatonin and the rating provided by customers.

### 3. **Sentiment Analysis**:
   - Applied sentiment analysis to classify review texts as positive, negative, or neutral to assess overall customer satisfaction.

### 4. **Dosage Analysis**:
   - Examined the popularity and effectiveness of different melatonin dosages (e.g., 3mg, 5mg, 10mg).
   - Investigated which dosages received the highest ratings and positive reviews.

### 5. **Temporal Trends**:
   - Analyzed how the volume of reviews and product ratings change over time, uncovering any seasonal trends or shifts in customer sentiment.

   
