🎬 Rental Movie Analysis | From Database to Charts 📊

Time for a cinema-themed data project! 🍿

I explored a rental movie database (Sakila) to analyze:
✔️ The most rented movies
✔️ Rental pricing trends
✔️ Movie ratings and more!


🔍 Step 1: Database Preparation

First, I connected to the SQLite database and imported the films table. However, there were many unnecessary columns, so I removed the following:

❌ film_id – Not needed
❌ description – Irrelevant text
❌ release_year – Not required for this analysis
❌ language_id, original_language_id – Language wasn’t a focus
❌ special_features, last_update – Unnecessary details

Then, I cleaned the dataset by removing duplicate records and missing values. ✨


📊 Step 2: Data Analysis & Visualization

Now, let's extract insights from the data! 👀

1️⃣ Most Popular Movies 🍿

I identified the top 10 most rented movies and visualized them using a bar chart.

2️⃣ Movie Rating Distribution ⭐

A pie chart displayed the distribution of movie ratings.

3️⃣ Rental Cost vs. Number of Rentals 💰

I used a scatter plot to check if rental price impacts the number of times a movie is rented.

4️⃣ Movie Duration Distribution ⏳

A histogram revealed the typical runtime of movies.

5️⃣ Rental Cost vs. Movie Ratings 📦

A box plot examined whether higher-rated movies have higher rental prices.

6️⃣ Most Expensive Rentals 💸

A bar chart highlighted the highest rental cost movies.


🔥 Key Findings

📌 Popular movies are rented frequently, even at high prices.
📌 Price alone doesn’t discourage people from renting a movie.
📌 Movie ratings don’t always determine rental frequency, but famous movies remain in demand.

🎥 Combining cinema and data analysis reveals fascinating insights! 🚀
