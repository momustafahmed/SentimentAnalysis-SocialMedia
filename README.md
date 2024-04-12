The "SentimentAnalysis-SocialMedia" repository is a robust project aimed at leveraging machine learning for sentiment analysis on social media platforms, focusing specifically on YouTube comments related to a high-profile criminal case in Mogadishu. The project analyzes user comments to understand public sentiments—positive, negative, and neutral—towards the kidnapping and murder of a young businessman named Kaabax, which garnered significant attention on social media.

1. **Data Collection**: Utilizing YouTube's API, the project team collected data from comments on videos discussing the case, storing the data in CSV files for further processing.

2. **Data Processing**: The data was cleaned to ensure quality, including removing duplicates and handling outliers. The integrity of the data was preserved to maintain meaningful insights, especially from comments with a high number of likes or replies, which indicate higher engagement.

3. **Analysis**:

   - **Sentiment Analysis**: Machine learning techniques were used to classify the sentiments of the comments into positive, negative, and neutral categories. This classification provided a granular view of public opinion.
   - **Visualization**: Various distributions, such as comment length and engagement metrics (likes and replies), were visualized to illustrate patterns in the data.

4. **Community Insights**:
   
   - **Word Cloud**: A Word Cloud was generated to identify and display the most frequently used words in the comments, highlighting key themes and sentiments related to the case.
   - **Engagement Analysis**: The project identified the most engaging comments and analyzed common themes within these comments, such as calls for justice and expressions of grief.

6. **Model Training and Application**:

   - **Sentiment Model**: A machine learning model was trained to understand and categorize sentiments expressed in the comments. This model helped quantify the community's emotional responses to the incident.
   - **Keyword Analysis**: Using TF-IDF vectorization, the project extracted keywords associated with positive and negative sentiments, offering insights into the specific language that resonates with the community.

7. **Challenges and Implications**:

   - The complexity of the Somali language, including dialects and slang, posed challenges in accurately capturing sentiments, which the project acknowledged.
   - The findings underscore the importance of understanding societal reactions in real-time and offer insights into how the community views justice and morality in light of tragic events.

The project showcases the potential of social media analytics to capture and analyze public sentiment, providing valuable insights into societal values and norms. It also highlights the role of advanced data analytics in understanding complex social dynamics and informs strategies for engaging with the community in meaningful ways. The methods and results from this project can serve as a reference for future research in social media analytics, particularly in contexts involving sensitive or impactful societal events.
