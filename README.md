# Żabka Lublin: Google Maps Reviews Analysis

I wanted to see what people actually complain about when they visit Żabka stores in my city (Lublin). Instead of guessing, I scraped Google Maps reviews and ran a quick text analysis to find the main pain points.

## The Stack
* **Scraping:** Apify
* **Data Processing & NLP:** Python (Pandas)
* **Dataviz:** Plotly Express

## What I did
1. Extracted 3,864 raw reviews from various Żabka locations across Lublin.
2. Cleaned the dataset (dropped ratings without text), leaving 1,913 actual text reviews.
3. Built a rule-based NLP script to tag negative reviews with specific categories (Service, Food, Pricing, Cleanliness).

## The Findings
I focused heavily on the 1- and 2-star reviews (~700 in total). Here is what stood out:

* **Service is the main bottleneck:** Over 250 pure complaints were just about long queues, slow cashiers, or rude staff. It's the #1 reason people leave bad reviews.
* **The "Cold Hot Dog" effect:** There’s a strong overlap between Service and Food complaints (78 reviews). Basically, people get stuck in line, and by the time they get their hot dog or coffee, it's cold. Service issues directly ruin the product.
* **Nobody really cares about the prices:** Surprisingly, complaints about high prices or wrong labels are super rare (only 28 complaints) compared to staff issues.

### Top Complaints Chart

