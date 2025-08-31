Project Overview
In today’s fast-paced digital media landscape, understanding how and when content performs best is critical to audience engagement. Media platforms often experiment with publishing strategies to optimize reach, clicks, and reader interaction.  
This project simulates an A/B test using real-world news article data retrieved from the Guardian Open Platform API. The primary focus is to investigate whether the time of publication, specifically morning (6 AM – 12 PM) vs. evening (6 PM – 12 AM) affects the length of articles (used here as a proxy for editorial depth or writer effort).

Objectives
Collect and clean article metadata using Python, requests, and pandas
Simulate experimental groups:
Group A → Morning articles (6 AM – 12 PM)  
Group B → Evening articles (6 PM – 12 AM)
- Explore statistical differences using aggregation and a two-sample t-test.
- Visualize results to uncover patterns in publishing behavior.
While word count is not a direct measure of article success, this analysis lays the foundation for designing more complex A/B tests using engagement metrics (clicks, shares, read-time) in the future.
