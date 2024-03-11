# html-scrape-challenge
- Background

You’re now ready to take on a full web-scraping and data analysis project. You’ve learned to identify HTML elements on a page, identify their id and class attributes, and use this knowledge to extract information via both automated browsing with Splinter and HTML parsing with Beautiful Soup. You’ve also learned to scrape various types of information. These include HTML tables and recurring elements, like multiple news articles on a webpage.
As you work on this Challenge, remember that you’re strengthening the same core skills that you’ve been developing until now: collecting data, organising and storing data, analysing data, and then visually communicating your insights.
What You're Creating

This new assignment consists of two technical products. You will submit the following deliverables:
Deliverable 1: Scrape titles and preview text from Mars news articles.
Deliverable 2: Scrape and analyse Mars weather data, which exists in a table.

## Part 1: Scrape Titles and Preview Text from Mars News

## Part 2: Scrape and Analyse Mars Weather Data

## References
- Count the occurrences of each unique value in the 'month' column
month_counts = Mars_df['month'].value_counts()

- Sort the result by the index (month numbers)
month_counts_sorted = month_counts.sort_index()

print(month_counts_sorted)

- chatgpt "https://chat.openai.com/c/99f4c781-d961-48c8-9f98-fceaf7b67351"