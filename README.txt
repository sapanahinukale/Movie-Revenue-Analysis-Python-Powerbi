🎬 Movie Revenue Analysis & Visualization (Python & Power BI)

📌 Problem Statement

The movie industry is a multi-billion dollar sector, but predicting financial success remains a challenge. Several factors, such as budget, genre, and audience reception, play a crucial role in determining a movie’s profitability. This analysis aims to:

✅ Examine the relationship between budget and revenue.
✅ Identify top-grossing genres and their contribution to total revenue.
✅ Highlight high-revenue movies and key factors behind their success.
✅ Analyze trends over time to aid future production and marketing decisions.
🛠 Data Cleaning & Preprocessing (Python)

Before visualization, the dataset was cleaned and preprocessed using Python:

🧹 Missing Values: Handled via imputation or removal.
🔍 Outliers: Detected using statistical methods and treated to prevent distortions.
📅 Date Formatting: Standardized release dates to ensure accuracy in trend analysis.
📊 Power BI Measures Created

To enable interactive analysis, several DAX measures were created in Power BI:

📌 Total Revenue
Total Revenue = SUM(tmdb_5000_movies_cleaned[revenue])
💰 Calculates the sum of all movie revenues.

📌 Total Budget
Total Budget = SUM(tmdb_5000_movies_cleaned[budget])
💵 Computes the total budget spent across all movies.

📌 Total Profit
Total Profit = [Total Revenue] - [Total Budget]
💵 Derives total profit by subtracting total budget from total revenue.

📌 Average Revenue per Movie
Average Revenue = AVERAGE(tmdb_5000_movies_cleaned[revenue])
🎥 Computes the average revenue per movie.

📌 Average Budget per Movie
Average Budget = AVERAGE(tmdb_5000_movies_cleaned[budget])
💲 Determines the average budget allocated per movie.
🔍 Data Analysis & Key Insights (Power BI)

📌 1. Total Revenue & Profitability

💰 Total revenue generated: 290 billion
🎬 Total budget spent: 100 billion
💵 Total profit: 190 billion
📌 2. Genre-Based Revenue Trends

🎭 Top revenue-generating genres:

🎬 Drama
🔥 Action
🌍 Adventure
🤣 Comedy
🎬 Highest-budgeted genres:

🎭 Drama
😂 Comedy
🎬 Action
🌍 Adventure
🚀 Science Fiction
Observation: Drama leads in both revenue and budget allocation, indicating its strong industry presence.

📌 3. Top-Grossing Movies

🏆 Highest revenue-generating movies:
Avatar ($2.8B) 🌍
Titanic ($1.8B) 🚢
The Avengers ($1.5B) 🦸‍♂️
Jurassic World ($1.5B) 🦖
Furious 7 ($1.5B) 🚗💨

📌 4. Budget vs. Revenue Trends
Higher budgets generally correlate with higher revenues, particularly for blockbusters and high-rated films.
Some movies with lower budgets achieved high revenue, showcasing the impact of storytelling, marketing, and audience engagement.

📌 5. Revenue & Budget Trends Over Time
Average revenue per movie has grown in recent years, reflecting inflation and global box office expansion.
Budget allocation has increased, signaling rising production costs and investments in high-quality content.

✅ Conclusion

This analysis provides valuable insights into movie revenue trends. Key takeaways:

🎬 High-budget productions tend to yield higher profits, but success is not solely dependent on budget.
🔥 Drama, Action, and Adventure genres dominate revenue generation.
🏆 Blockbuster franchises with strong brand value and audience engagement tend to dominate the market.
💡 These insights can help producers, investors, and marketers make data-driven decisions for future films.
