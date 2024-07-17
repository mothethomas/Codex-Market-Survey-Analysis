# Codex-Market-Survey-Analysis


## Project Overview
This project analyzes survey results from 10,000 respondents in 10 cities in India. The goal is to provide meaningful insights and recommendations based on consumer behavior, feedback on energy drinks, pricing, packaging, and other factors.

## Problem Statements & Solutions

### 1. Demographic Insights
**a. Who prefers energy drinks more? (male/female/non-binary?)**

**Solution:**
- Out of 10,000 respondents, the number of male respondents is 6,038.
- This shows that 60% of the consumers who prefer energy drinks are male.

**b. Which age group prefers energy drinks more?**

**Solution:**
- From the survey results, energy drinks are more popular among youngsters.
- More than 50% of the respondents belong to the age group 19-30.
- If we look at the overall young age groups from 15 to 30, the percentage rises to 70%.

**c. Which type of marketing reaches the most Youth (15-30)?**

**Solution:**
- Online Ads are the most effective channel, reaching 3,373 respondents in the age group 15-30.

![Demographic Insights](https://github.com/mothethomas/Codex-Market-Survey-Analysis/blob/main/demographic_insights.jpg)

### 2. Consumer Preference
**a. What are the preferred ingredients of energy drinks among respondents?**

**Solution:**
- Caffeine is the most expected ingredient, followed by vitamins. Caffeine is known for increasing attention and alertness and is a common ingredient in energy drinks.

**b. What packaging preferences do respondents have for energy drinks?**

**Solution:**
- Compact & Portable Cans are in high demand, followed by Innovative Bottle Designs.

![Consumer Preferences](https://github.com/mothethomas/Codex-Market-Survey-Analysis/blob/main/consumer_preferences.jpg)

### 3. Competition Analysis
**a. Who are the current market leaders?**

**Solution:**
- Cola Coka is leading the market, followed by Bepsi. The data shows more respondents prefer Cola Coka than other brands.

**b. What are the primary reasons consumers prefer those brands over ours?**

**Solution:**
- The top reason for choosing these brands by consumers is brand reputation.

![Competition Analysis](https://github.com/mothethomas/Codex-Market-Survey-Analysis/blob/main/competition%20analysis.jpg)

### 4. Marketing Channels and Brand Awareness
**a. Which marketing channel can be used to reach more customers?**

**Solution:**
- As previously discussed, Online Ads are the most effective way to reach maximum audiences in a short duration and are cost-effective.

**b. How effective are different marketing strategies and channels in reaching our customers?**

**Solution:**
- Online Ads are the most effective, reaching the highest number of respondents quickly and cost-effectively.
![Marketing channels](https://github.com/mothethomas/Codex-Market-Survey-Analysis/blob/main/Marketing_Analysis.jpg)
### 5. Brand Penetration
**a. What do people think about our brand? (overall rating)**

**Solution:**
- Out of 980 respondents, 455 people have heard about our brand. The rating for CodeX product’s taste is 3.3, which is the industry average rating as well.

**b. Which cities do we need to focus more on?**

**Solution:**
- The data shows people’s perception of CodeX as a brand in different cities.
- The neutral and negative responses are combined in this visual as they are greater in number than the positive responses. Improving the positive response is one area where marketing should focus.

### 6. Purchase Behavior
**a. Where do respondents prefer to purchase energy drinks?**

**Solution:**
- Supermarkets are the most common choice among consumers to buy energy drinks.

**b. What are the typical consumption situations for energy drinks among respondents?**

**Solution:**
- Typical consumption situations include sports/exercise and studying/working late.
- The data also shows that youth are consuming these drinks more.

**c. What factors influence respondents’ purchase decisions, such as price range and limited edition packaging?**

**Solution:**
- 43% of consumers buy a product if the price is between INR 50-99.
- 40% of consumers do not expect a change in the packaging while 39% of consumers are open to trying the Limited Edition Packaging.

-![Purchase Behaviour](https://github.com/mothethomas/Codex-Market-Survey-Analysis/blob/main/purchasing_behaviour.jpg) 
![Codex Performance](https://github.com/mothethomas/Codex-Market-Survey-Analysis/blob/main/Codex_performance.jpg)

### 7. Product Development
**a. Which area of business should we focus more on for our product development? (Branding/taste/availability)**

**Solution:**
- Out of 980 respondents of CodeX, only 219 have a positive brand perception.
- The taste experience rating is the same as the industry rating, indicating that it does not need immediate attention.
- Focus should be on improving branding to enhance positive brand perception among consumers.

## Data Description
The dataset provided by Codebasics contains three CSV files: `dim_respondents`, `dim_cities`, and `fact_survey_responses`. Below are the descriptions for each column in these files:

### Column Description for `dim_respondents`:
- **Respondent_ID:** Unique identifier assigned to each respondent in the survey.
- **Name:** Name of the respondent who participated in the survey.
- **Age_Group:** Categorized age group of the respondent. Age groups: (15-18, 19-30, 31-45, 46-65, 65+)
- **Gender:** Gender of the respondent. (Male, Female, Non-binary)
- **City_ID:** ID of the city where the respondent is located.

### Column Description for `dim_cities`:
- **City_ID:** ID of the city.
- **City:** Name of the city where the respondent is located. (“Delhi”, “Mumbai”, “Bangalore”, “Chennai”, “Kolkata”, “Hyderabad”, “Ahmedabad”, “Pune”, “Jaipur”, “Lucknow”)
- **Tier:** Tier category of the city.

### Column Description for `fact_survey_responses`:
- **Response_ID:** Unique identifier for each survey response.
- **Respondent_ID:** ID of the respondent.
- **Consume_frequency:** Frequency of consuming energy drinks.
- **Consume_time:** Time when energy drinks are consumed.
- **Consume_reason:** Reason for consuming energy drinks.
- **Heard_before:** Whether the respondent has heard about the brand before.
- **Brand_perception:** Respondent's perception of the brand.
- **General_perception:** General perception of energy drinks.
- **Tried_before:** Whether the respondent has tried the brand before.
- **Taste_experience:** Respondent's experience with the taste of the energy drink.
- **Reasons_preventing_trying:** Reasons preventing respondents from trying the brand.
- **Current_brands:** Brands currently consumed by the respondent.
- **Reasons_for_choosing_brands:** Reasons for choosing current brands.
- **Improvements_desired:** Desired improvements in energy drinks.
- **Ingredients_expected:** Expected ingredients in energy drinks.
- **Health_concerns:** Health concerns related to energy drinks.
- **Interest_in_natural_or_organic:** Interest in natural or organic energy drinks.
- **Marketing_channels:** Marketing channels through which respondents learn about energy drinks.
- **Packaging_preference:** Preferred packaging for energy drinks.
- **Limited_edition_packaging:** Interest in limited edition packaging.
- **Price_range:** Preferred price range for energy drinks.
- **Purchase_location:** Preferred purchase locations for energy drinks.
- **Typical_consumption_situations:** Typical situations in which respondents consume energy drinks.

The PDF provided contains all the questions with the multiple-choice answers asked to the consumers.

## Data Analysis
- **Data Collection:** Survey conducted across 10 cities in India with 10,000 respondents.
- **Data Cleaning and Preprocessing:** Handled missing values, outliers, and ensured data consistency.
- **Descriptive Statistics:** Calculated basic statistics to understand the distribution of responses.
- **Segmentation:** Segmented respondents based on various factors such as age, city, purchasing frequency, etc.
- **Comparative Analysis:** Compared preferences and feedback across different segments.
- **Sentiment Analysis:** Analyzed the sentiment of feedback provided by consumers.

## Visualizations
- **Demographic Insights:** Bar charts showing the distribution of male, female, and non-binary respondents.
- **Purchasing Habits:** Line charts showing the purchasing frequency over time.
- **Feedback Analysis:** Word clouds and sentiment analysis charts for consumer feedback.
- **Pricing Preferences:** Histograms showing preferred price ranges.
- **Packaging Preferences:** Pie charts showing packaging preferences.
- **Competition Analysis:** Bar charts showing the market share of different brands and reasons for consumer preferences.
- **Marketing Channels:** Charts showing the effectiveness of various marketing channels.
- **Brand Awareness:** Visuals showing overall brand ratings and city-wise perception.
- **Purchase Behavior:** Visuals showing preferred purchase locations, consumption situations, and factors influencing purchase decisions.

## Key Insights
1. **Purchasing Habits:**
   - Most consumers purchase energy drinks during the evening or night.
   - High purchasing frequency in cities with a younger demographic.

2. **Feedback on Energy Drinks:**
   - Positive feedback on taste and energy boost but negative feedback on price.
   - Packaging is found to be less appealing compared to competitors.

3. **Pricing Preferences:**
   - Consumers prefer energy drinks priced between INR 50-70.
   - Willing to pay a premium for organic or healthier options.

4. **Packaging Preferences:**
   - Preference for smaller, convenient packaging for on-the-go consumption.
   - Eco-friendly packaging is a significant factor for many respondents.

5. **Competition Analysis:**
   - Cola Coka is the leading brand followed by Bepsi.
   - Brand reputation is the primary reason consumers prefer these brands over others.

6. **Marketing Channels and Brand Awareness:**
   - Online Ads are the most effective way to reach a large audience quickly and cost-effectively.
   - Brand awareness is at an industry average rating, with room for improvement in specific cities.

7. **Consumer Preferences:**
   - Caffeine and vitamins are the most preferred ingredients.
   - Consumers favor compact & portable cans followed by innovative bottle designs.

8. **Product Development:**
   - Focus should be on improving branding to enhance positive perception.
   - Taste experience is at an industry average and doesn’t need immediate attention.

## Recommendations
1. **Marketing Strategies:**
   - Invest more in online ads, especially targeting the youth demographic.
   - Emphasize the brand's unique selling points, such as energy boost and taste.

2. **Product Development:**
   - Develop eco-friendly and innovative packaging to attract environmentally conscious consumers.
   - Consider launching limited edition packaging to create excitement and drive sales.

3. **Pricing Strategy:**
   - Maintain competitive pricing within the INR 50-70 range.
   - Explore premium pricing for organic or healthier options.

4. **Brand Awareness:**
   - Increase brand visibility in cities with lower brand perception.
   - Engage in community events and sponsorships to enhance brand reputation.

5. **Consumer Engagement:**
   - Conduct regular surveys and feedback sessions to understand consumer needs and preferences.
   - Implement suggestions and communicate changes to consumers to build loyalty.

## Conclusion
This analysis provides a comprehensive understanding of the consumer preferences, purchasing habits, and feedback on energy drinks. By focusing on the recommended strategies, CodeX can enhance its market presence, improve consumer satisfaction, and drive growth.

