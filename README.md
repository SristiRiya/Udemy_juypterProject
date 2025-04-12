 Project Title:
Exploratory Data Analysis of Udemy Courses Dataset

📝 Objective:
To explore, analyze, and visualize the Udemy course dataset in order to uncover insights about:

Course popularity (based on subscribers and reviews)

Subject-wise distribution

Course content (like number of lectures)

Relationships between engagement metrics

This analysis can help identify trends, popular topics, and patterns in online education offerings.

📂 Dataset Overview:
The dataset includes various features about Udemy courses, such as:

Column	Description
course_title	Title of the course
subject	Main subject category (e.g., Business, Web Development, etc.)
num_subscribers	Number of users subscribed to the course
num_reviews	Number of user reviews
num_lectures	Total number of lectures in the course
price	Price of the course
level	Target audience (e.g., Beginner, All Levels)
content_duration	Duration of the course in hours
published_timestamp	Date when the course was published
🔍 Key Analyses Performed:
1. Subject-wise Course Distribution
Used value_counts() to count how many courses exist per subject.

Created a pie chart to visualize this distribution.

2. Top Courses by Number of Subscribers
Sorted the dataset by num_subscribers.

Visualized top 10 courses using a bar chart.

3. Course Title vs Subject
Created a bar plot showing course titles with their subjects (colored).

Used hue='subject' in seaborn to add categorical dimension.

4. Histograms for Numeric Distributions
Plotted histograms for:

Number of subscribers

Number of reviews

Number of lectures

Helped understand how data is skewed (e.g., most courses have low subscriber count, few are viral).

# Potential Insights Derived:
Some subjects have significantly more courses (e.g., Business, Web Dev).

Few courses dominate in terms of subscribers and reviews (power-law distribution).

Beginner-level courses are more prevalent.

Free or low-cost courses often attract more students.

Longer courses don't always correlate with higher subscribers.
