# 📊 YouTube Trending Videos Analysis Using Python 🎬

## 📊 Project overview and data analysis
This project explores a YouTube trending-video dataset using Python. The notebook performs initial data inspection and exploratory data analysis (EDA) to understand video categories, channels, views, likes, comments, and engagement-related metrics.

## 🎯 Objectives
- Inspect the dataset structure and column types.
- Check for missing values and duplicate rows.
- Generate descriptive statistics for numeric and categorical columns.
- Explore distributions of video categories, channels, views, likes, comments, and like rate.
- Examine outliers in selected performance and engagement metrics.
- Inspect category and channel values and sample Music-category records.

## 🛠️ Tools and Libraries
- **Python**
- **Pandas** — data loading and manipulation
- **NumPy** — numerical operations
- **Matplotlib** — plotting
- **Seaborn** — statistical visualizations
- **Jupyter Notebook** — interactive analysis environment

## The notebook references these columns:
- channel_title
- category
- views
- likes
- comments
- trending_duration
- engagement_rate
- like_rate
- comment_rate


## Analysis Performed
1. **Data loading and preview**
   - Load the CSV into a Pandas DataFrame.
   - View the first and last rows.

2. **Data quality and structure**
   - Count unique values in columns.
   - Check missing values.
   - Review data types and non-null counts.
   - Generate descriptive statistics.
   - Count duplicate rows.

3. **Exploratory data analysis**
   - Plot the distribution of video categories and channel titles.
   - Plot distributions for views, likes, comments, and like rate.
   - Review unique categories and channel titles.
   - Count records by category.
   - Preview the first ten records in the Music category.

# 🔮 Future Improvements
- Handle missing values and duplicates where appropriate.
- Add clear, concise interpretations below each visualization.
- Compare engagement metrics across categories and channels.
- Add correlation analysis for views, likes, comments, and engagement metrics.
- Summarize key findings and recommendations in a final conclusion.
