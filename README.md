# Predicting Consumer Tastes with Big Data at Gap

This project, created as part of our Web Data Analytics course at Purdue University, explores how fashion retailers like Gap Inc. can integrate data-driven strategies to better understand consumer preferences, enhance competitiveness, and balance creativity with analytics in the fast-evolving retail landscape.

## 🧠 Objective

To evaluate the effectiveness of Gap Inc.'s transition to a data-driven design approach (Product 3.0), replacing creative directors with a big data methodology, and assess the business implications for its brands: Gap, Old Navy, and Banana Republic.

## 📈 Key Analyses

### 1. **Google Trends Analysis**
- Used PyTrends to extract regional search interest for fashion terms (e.g., “denim jacket”).
- Insights: Highlight trending apparel categories to guide design decisions.

### 2. **Web Scraping Fashion Magazines**
- Extracted emerging fashion trends from Vogue, Elle, and Harper’s Bazaar using `BeautifulSoup` and `Selenium`.
- Insights: Identified hot patterns (e.g., leopard prints) for upcoming releases.

### 3. **Sentiment Analysis on Reddit**
- Scraped fashion subreddit discussions related to Gap brands.
- NLP and sentiment scoring showed:
  - Gap: Mostly negative sentiment
  - Old Navy: Positive consumer perception
  - Banana Republic: Mixed views

### 4. **Competitor Analysis**
- Scraped Macy’s and Amazon product listings:
  - Compared discount patterns, top-selling products, ratings, and pricing strategies.
- Insights: 83% of bestsellers were discounted (typically by 30%).

### 5. **Gap Product Review Analysis**
- Conducted text analysis and sentiment mining on customer reviews.
- Identified product-specific issues and strengths to guide improvements.

## 🎨 Art vs. Science in Marketing

We propose a hybrid approach combining:
- **Science**: A/B testing, forecasting, trend detection
- **Art**: Aesthetic creativity, emotional appeal, brand identity

## 📉 Limitations

- **Trends ≠ Demand**: Google search may not reflect real purchase intent.
- **Editorial Bias**: Magazine recommendations may be delayed or skewed.
- **Sentiment Bias**: Reddit can amplify negative voices due to hive mentality.
- **Scraping Ethics**: Limitations exist with accessing competitor data.

## 📊 Tools & Technologies Used

- Python: `Selenium`, `BeautifulSoup`, `PyTrends`, `NLTK`, `Pandas`
- Web Sources: Google Trends, Reddit, Amazon, Macy’s, Vogue, Elle, Harper’s Bazaar
- NLP: Sentiment scoring on product and community feedback

## 👨‍💻 Contributors

- Abhishek Bagepalli  
- Ananth Mohan  
- Tushar Malankar

## 📜 References

- [Google Trends](https://trends.google.com/trends/)
- [Gap 10K Filing](http://c.gov/Archives/edgar/data/39911/000003991119000023/fy201810-k.htm)
- [Reddit Fashion Advice](https://www.reddit.com/r/malefashionadvice/)
- [Vogue Fall Trends 2024](https://www.vogue.com/article/fall-shopping-list-editor-picks-2024)
- [Elle Fall Trends 2024](https://www.elle.com/fashion/trend-reports/)
- [GlobalData Market Size](https://www.globaldata.com/data-insights/retail-and-wholesale/market-size-of-retail-clothing-in-us/)

---

> 📌 This project demonstrates how big data can support decision-making in consumer fashion but also highlights the need for human creativity in brand storytelling.
