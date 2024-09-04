Project Overview
- This project conducts basic analysis of user engagement on Hacker News by comparing two types of posts—Ask HN and Show HN. The goal is to determine which type of post gets more comments and whether the time of posting affects engagement.

Dataset
- We use a reduced dataset of around 20,000 posts, filtered to include only those with comments. Key columns include:

id: Unique post identifier
title: Post title
num_points: Upvotes minus downvotes
num_comments: Number of comments
created_at: Post submission time

Objectives
- Do Ask HN or Show HN posts get more comments on average?
- Does posting time affect the number of comments?

Key Findings
- Ask HN posts receive more comments on average, especially between 3:00 PM and 4:00 PM (EST).
- Show HN posts tend to earn more points, particularly when posted late at night.

How to Run
- Download the project files and place the hacker_news.csv in the same directory as the notebook.
- Run the Jupyter Notebook (Exploring Engagement on Hacker News.ipynb).
- Follow the step-by-step analysis in the notebook.
