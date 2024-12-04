# Twitter Data Analytics Dashboard

This project is a **Twitter Data Analytics Dashboard** designed to visualize and analyze various aspects of tweet performance. The dashboard incorporates multiple visualizations to help users gain insights into tweet engagements, media interactions, and user behaviors. Below is an overview of the project and the tasks accomplished.

---

## Features and Tasks

### **1. Pie Chart for Click Proportions**
- **Description:** Displays the proportion of total clicks (URL clicks, user profile clicks, and hashtag clicks) for tweets with more than 500 impressions. 
- **Drill-Down:** Allows users to view specific types of clicks for each tweet.
- **Filters:** Includes tweets with more than 500 impressions.

---

### **2. Clustered Bar Chart for Clicks by Tweet Category**
- **Description:** Breaks down the sum of URL clicks, user profile clicks, and hashtag clicks by tweet category (e.g., tweets with media, links, or hashtags).
- **Constraints:**  
  - Only shows tweets with at least one interaction type.  
  - **Available Time:** 3 PM to 5 PM IST.  
  - **Additional Filters:**  
    - Tweet date must be even.  
    - Tweet word count must be above 40.

---

### **3. Scatter Chart for Media Engagements vs. Media Views**
- **Description:** Analyzes the relationship between media engagements and media views for tweets with more than 10 replies. Tweets with an engagement rate above 5% are highlighted.
- **Constraints:**  
  - **Available Time:** 6 PM to 11 PM IST.  
  - **Additional Filters:**  
    - Tweet date must be odd.  
    - Tweet word count must be above 50.

---

### **4. Top 10 Tweets by Retweets and Likes**
- **Description:** Displays the top 10 tweets ranked by the sum of retweets and likes. Shows the user profile that posted each tweet.  
- **Constraints:**  
  - Excludes tweets posted on weekends.  
  - **Available Time:** 3 PM to 5 PM IST.  
  - **Additional Filters:**  
    - Tweet impression count must be even.  
    - Tweet date must be odd.  
    - Tweet word count must be below 30.

---

### **5. Line Chart for Average Engagement Rate Trends**
- **Description:** Shows the trend of the average engagement rate over each month of the year, separating tweets with media content from those without.  
- **Constraints:**  
  - **Available Time:** 3 PM to 5 PM IST and 7 AM to 11 AM IST.  
  - **Additional Filters:**  
    - Engagement rate must be even.  
    - Tweet date must be odd.  
    - Tweet character count must be below 20.  
    - Excludes tweets containing words with the letter 'C'.

---

### **6. Dual-Axis Chart for Media Views and Engagements**
- **Description:** Compares the number of media views and media engagements by the day of the week for the last quarter. Highlights days with significant spikes in media interactions.  
- **Constraints:**  
  - **Available Time:** 3 PM to 5 PM IST and 7 AM to 11 AM IST.  
  - **Additional Filters:**  
    - Impression count must be even.  
    - Tweet date must be odd.  
    - Tweet character count must be below 30.  
    - Excludes tweets containing words with the letter 'H'.

---

### **7. Replies, Retweets, and Likes Comparison**
- **Description:** Visualizes the comparison of replies, retweets, and likes for tweets with media engagements greater than the median value.  
- **Constraints:**  
  - Includes only tweets posted between June and August 2020.  
  - **Available Time:** 3 PM to 5 PM IST and 7 AM to 11 AM IST.  
  - **Additional Filters:**  
    - Tweet date must be odd.  
    - Media views must be even.  
    - Tweet character count must be below 20.  
    - Excludes tweets containing words with the letter 'S'.

