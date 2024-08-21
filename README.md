# 📚 GoodReads Quotes PDF Generator 📝

This Google Colab script processes your GoodReads quotes, creates visualizations, and generates a formatted PDF. Perfect for book lovers and quote enthusiasts!

## 🌟 Features

- 📊 Process and clean quotes from your GoodReads export
- 🎨 Generate insightful visualizations of your quote collection
- 📄 Create a professionally formatted PDF of your quotes
- 🔧 Customizable sorting options and quote length limits

## 🚀 Getting Started

1. 📥 Download your quotes from your GoodReads profile
2. 📁 Upload the file as `goodreads_quotes_export.csv` to your Google Colab environment
3. 🏃‍♂️ Run the script and watch the magic happen!

## 📊 Visualizations

The script generates four types of visualizations:

1. 📏 Distribution of word counts in quotes
2. 📈 Top 20 authors by average quote length
3. 🏆 Top 20 authors by number of quotes
4. 📊 Box plot of word count per author for top 20 authors

## 🛠️ Customization

You can customize the following options:

- 🔄 Sorting method: random, author, title, or length
- ✂️ Maximum quote length (set to 0 for no limit)

## 📦 Requirements

- pandas
- matplotlib
- seaborn
- fpdf
