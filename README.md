A work in progress inspired by my passion for motorcycles. This project will use data from Bikez.com to scrape, clean, and organize information in a database. I aim to explore the data, create visualizations, and develop tools to help users find their ideal motorcycle. Updates will follow as I progress.

Finished work:
Stage 1 - Web scraping.

Challenges and Solutions:

Combining libraries for scraping: Learned to integrate Beautiful Soup with libraries (started with Selenium, finally transitioned to Asyncio for headless browser automation) capable of waiting for dynamic content to load, overcoming issues where fields displayed “Loading…” instead of data.

Dealing with inconsistencies: The website’s inconsistent column naming required custom handling to harmonize the data and ensure usability in subsequent stages.

Handling stalled processes: Browser processes occasionally failed to close, causing the computer to freeze due to massive usage on RAM memory. Implementing proper process management was essential to ensure smooth execution.

Managing Data Saves: To avoid re-scraping pages during interruptions, I developed a strategy to save the names of scraped motorcycles and skip them in future script runs.

These challenges helped me enhance my skills and build a more resilient scraping pipeline. This phase lays the groundwork for the next steps in the project.

Stage 2 - Data cleaning.

Challenges and Solutions:

Brand/model separation: Extracted motorcycle brand listings from Bikez.com to split combined "Brand+Model" field into two distinct columns for proper categorization.

Regex-based normalization: Implemented regex dictionaries to handle minor data inconsistencies and standardize values across the dataset.

Numeric field preparation: Cleansed numerical columns by removing extraneous characters and non-numeric information to ensure readiness for analysis.

Dataset reorganization: Maintained structural integrity by systematically adding/modifying, new columns and removing old ones while preserving the original dataset's logical organization.

Output optimization: Exported the refined dataset to a clean CSV, ready to be used in next stages.

These challenges helped me develop stronger data processing skills and transform raw scraped data into a clean, structured format.

Incoming work:
Stage 3 - Creating and populating a database.
Stage 4 - Creating a Machine Learning model.
