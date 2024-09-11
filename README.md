Project Overview:

This project focuses on visualizing the distribution of app ratings across different categories by leveraging a violin plot. The analysis aims to filter out irrelevant apps to provide insights into how specific app categories perform in terms of user ratings. Several filters are applied to the dataset to ensure the inclusion of meaningful data. The final visualization will allow stakeholders to compare app ratings across categories, but with a particular emphasis on apps that meet stringent filtering criteria.

Additionally, the visualization will only be displayed during certain times of the day, ensuring the plot is generated outside the hours of 6 PM to 11 PM.
Key Filters Applied:

    Category Filter: Only include categories with more than 50 apps to ensure that the analysis is robust and represents categories with significant data.

    App Name Filter: Include only apps whose names contain the letter "C" (case-insensitive).

    Review Filter: Exclude apps that have received fewer than 10 reviews, ensuring that only apps with a reasonable amount of user feedback are considered.

    Rating Filter: Only include apps with ratings lower than 4.0 to focus on apps that may have lower user satisfaction.

    Time Restriction: The plot will not be generated or displayed between 6 PM and 11 PM, ensuring the process is restricted to specific timeframes.

Deliverables:

A violin plot that:

    Visualizes the distribution of ratings for each app category that meets the above filtering criteria.
    Only includes app categories with more than 50 apps, app names containing the letter "C", apps with at least 10 reviews, and a rating below 4.0.
    Is restricted from running between 6 PM and 11 PM.
