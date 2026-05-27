**Bellabeat Smart Device Usage Analysis Introduction** 

This project is a data analytics case study completed as part of my professional portfolio. It simulates a real-world business scenario in which I act as a **junior data analyst on the Bellabeat marketing analytics team**. The objective of the analysis is to examine smart device usage data to uncover behavioral trends and translate those insights into **actionable marketing recommendations** for Bellabeat. 

Bellabeat is a high-tech wellness company that develops smart, health-focused products designed primarily for women. By analyzing non-Bellabeat smart device data, the company aims to better understand how consumers engage with wellness technology and identify opportunities to improve product positioning, customer engagement, and marketing strategy. 

The insights generated in this analysis are intended to support Bellabeat’s executive leadership in making data-informed strategic decisions. 

**Methodology** 

**Business Objective** 

To understand how consumers use smart wellness devices and identify behavioral patterns that can inform Bellabeat’s marketing strategy and product messaging. 

**Guiding Questions** 

● What are the key trends in smart device usage? 

● How do users engage with activity, sleep, and wellness tracking? 

● How can these trends be applied to Bellabeat customers? 

● How can Bellabeat leverage these insights to drive growth? 

**Data Sources** 

● **Dataset:** FitBit Fitness Tracker Data (Public Domain, CC0) 

● **Source:** Kaggle (provided by Mobius)  
● **Sample Size:** 30 users 

● **Time Period:** 2016 

The dataset includes daily and minute-level data on: 

● Steps and activity intensity 

● Calories burned 

● Heart rate 

● Sleep duration and sleep stages 

**Data Preparation** 

● Removed duplicate records 

● Standardized date and time formats 

● Converted string-based timestamps into DATE and DATETIME data types ● Validated numeric ranges for steps, sleep minutes, and heart rate 

● Engineered derived fields such as weekday, hour of day, and sleep efficiency 

● Maintained a two-tier architecture (Raw vs. Cleaned datasets) to preserve data integrity 

**Tools Used** 

● **SQL:** Data cleaning, aggregation, joins, correlation analysis 

● **Google Sheets:** Pivot tables, dashboards, and visualizations 

**Results** 

**1\. Activity Levels (Overall Engagement)** 

Users were generally **less active than recommended health guidelines**. **Key Metrics**  
● **Average daily steps:** 6,547 

● **Median daily steps:** 5,893 

● **Minimum steps:** 0 

● **Maximum steps:** 28,497 

● **Days meeting 10,000-step goal:** 27.79% 

**Activity Distribution** 

● Sedentary (\<5,000 steps): 197 days 

● Lightly active (5,000–7,500): 83 days 

● Fairly active (7,500–10,000): 50 days 

● Highly active (10,000+): 127 days 

**Insight:** 

Most users fall below optimal activity levels, indicating a large opportunity for behavior-change messaging and motivation-focused features. 

**2\. Usage Consistency (Device Engagement)** 

User engagement varied significantly. 

● A small group of users wore their devices consistently (30+ active days). 

● The majority showed **partial or declining usage**, with many active for only 8–15 days. 

**Insight:** 

Drop-off behavior suggests that maintaining long-term engagement is a major challenge and a critical area for Bellabeat to address through habit-building features and retention campaigns. 

**3\. Time-of-Day & Weekly Activity Patterns** 

**Hourly Trends**  
● Peak activity occurs between **12 PM and 7 PM** 

● Highest average steps recorded at **7 PM** 

● Very low activity during early morning and late-night hours 

**Day-of-Week Trends** 

● Most active day: **Wednesday** 

● Least active day: **Tuesday** 

● Activity dips on **Sundays**, with higher sedentary minutes 

**Insight:** 

Users follow predictable routines, making **time-based nudges and scheduled notifications** an effective marketing and engagement strategy. 

**4\. Sleep Behavior & Recovery** 

A sleep summary table was engineered from minute-level sleep data to enable deeper analysis. 

**Average Sleep Metrics** 

● **Average sleep duration:** 3.72 hours 

● **Average time in bed:** 4.03 hours 

● **Average sleep efficiency:** 91.24% 

**Insight:** 

Although sleep efficiency is high, total sleep duration is **well below the recommended 7–9 hours**, indicating widespread sleep deprivation among users. 

**5\. Relationship Between Activity and Sleep** 

Pearson correlation analysis revealed **weak relationships**: 

● Steps vs. Sleep Duration: **\-0.11**  
● Active Minutes vs. Sleep Efficiency: **0.06** 

● Sedentary Minutes vs. Sleep Duration: **\-0.19** 

**Interpretation** 

● More steps did not lead to more sleep 

● High-intensity activity had little effect on sleep efficiency 

● Increased sedentary behavior showed the strongest (negative) relationship with sleep 

**Insight:** 

Sleep quality appears more influenced by **sedentary behavior and lifestyle habits** than by activity volume alone. 

**6\. User Segmentation** 

Users were grouped into three behavioral segments: 

● Low Activity: 197 days 

● Moderate Activity: 133 days 

● High Activity: 127 days 

**Insight:** 

Distinct user types exist, supporting the need for **personalized messaging and segmented marketing campaigns**. 

**Recommendations** 

1\. **Promote Consistency Over Intensity** 

Shift messaging from “more steps” to “daily movement consistency,” emphasizing sustainable habits. 

2\. **Leverage Inactivity Alerts** 

Highlight Leaf and Time’s inactivity reminders as tools to reduce sedentary behavior and improve sleep readiness. 

3\. **Introduce Time-Based Engagement Nudges** 

Schedule notifications during peak activity hours and low-activity days (e.g., “Sunday  
Reset” prompts). 

4\. **Position Bellabeat as a Sleep & Recovery Brand** 

Educate users that sleep quality depends on movement timing, mindfulness, and reduced sedentary time. 

5\. **Personalize Marketing by User Segment** 

○ Low-activity users: Gentle motivation and beginner goals 

○ Moderate users: Habit reinforcement and streaks 

○ High-activity users: Performance insights and recovery tools 

6\. **Promote Membership Content Strategically** 

Market mindfulness and meditation features to highly sedentary, office-based users to improve sleep efficiency. 

**Conclusions** 

This analysis reveals that most smart device users are **not meeting recommended activity or sleep guidelines** and struggle with long-term engagement. While physical activity alone does not strongly predict better sleep, sedentary behavior shows a meaningful negative relationship with sleep duration. 

For Bellabeat, these insights highlight a strategic opportunity to: 

● Focus on **behavioral consistency** 

● Reduce sedentary lifestyles 

● Deliver **personalized, time-aware wellness messaging** 

● Position products as holistic wellness tools rather than step counters 

By aligning marketing strategy with real user behavior, Bellabeat can strengthen customer engagement, improve retention, and reinforce its identity as a data-driven wellness brand.
