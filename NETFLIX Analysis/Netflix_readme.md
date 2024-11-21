
# Netflix Analysis Dashboard: Understanding Viewer Ratings and Preferences

## Overview
This Power BI dashboard provides insights into Netflix's content library by analyzing ratings and viewer votes across various genres, countries, and types of content. The dashboard aims to offer a deeper understanding of viewer preferences, popular content types, and rating trends on the platform.

### Dashboard Link: [Power BI Dashboard](https://app.powerbi.com/links/W-rqhj9QQ0?ctid=0c2c5eb2-7477-4593-ac08-f1de3be027d2&pbi_source=linkShare)

## Problem Statement
With a vast library of content, it’s crucial for streaming platforms like Netflix to understand viewer preferences and engagement levels. This analysis helps identify popular genres, high-rated content, and patterns in viewer voting, providing insights into which types of content receive the highest viewer approval.

## Dataset
- **Source**: `netflix_list.csv`
- **Contents**: The dataset includes information about Netflix titles, such as genres, ratings, votes, and content types (movies, series, etc.).

## Features
This dashboard includes the following key features:
- Interactive charts and slicers for filtering data by genre, rating group, country, and content type.
- Key metrics showing average ratings, total votes, and title counts by genre and country.
- Detailed visuals that highlight viewer preferences and high-rated content categories.

## Visualizations
1. **Average Ratings by Genre**: A bar chart displaying the distribution of ratings across different genres.
2. **Title Count by Rating Group**: Visual representation of the number of titles in each rating category.
3. **Country-wise Ratings and Votes**: Analysis of average ratings and votes across different countries.
4. **Content Type Comparison**: Visual comparison of movies, TV shows, and other content types by rating and votes.
5. **Genre Analysis**: A scatter plot showing correlations between genres and average ratings, helping identify which genres are most popular among viewers.

## Getting Started
Follow these instructions to view and interact with the dashboard:

### Prerequisites
- **Power BI Desktop**: [Download here](https://powerbi.microsoft.com/desktop/).
- **CSV File**: Ensure you have the `netflix_list.csv` file for data reference.

### Installation & Setup
1. Clone this repository to your local machine using:
   ```bash
   git clone https://github.com/shivangraj20/Netflix-Analysis.git
   ```

2. Open the `NETFLIX analysis.pbix` file in Power BI Desktop to view the dashboard.

### Steps Followed

#### Step 1 - Data Loading and Inspection
- Loaded the dataset into Power BI Desktop.
- Inspected column quality and distribution in Power Query Editor to identify any data issues.

#### Step 2 - Data Cleaning and Preparation
- Addressed missing or inconsistent values.
- Created calculated columns for grouping ratings and votes into categories, and standardized genre labels for accurate filtering.

#### Step 3 - Identifying Key Metrics
Key metrics identified for the analysis include:
- **Average Rating**: Indicates viewer satisfaction across titles.
- **Votes**: Reflects viewer engagement and popularity of content.
- **Genre and Country Insights**: Shows which genres and regions have the most popular titles.

#### Step 4 - Building Visualizations
- **Genre Analysis**: Created bar charts to display the average ratings and votes by genre.
- **Rating Groups**: Set up visuals to segment titles by rating groups.
- **Country-wise Analysis**: Added a map visual to show ratings and votes distribution by country.
- **Content Type Comparison**: Added visuals comparing ratings and votes across content types (e.g., movies vs. TV shows).

#### Step 5 - Setting Up Filters for Interactivity
- Added slicers for filtering data by genre, country, and rating group, allowing users to customize views.

#### Step 6 - Deriving Insights
From the visualizations and metrics, insights were derived, such as:
- **Popular Genres**: Identification of top genres based on average ratings and viewer engagement.
- **Regional Preferences**: Analysis of countries with the highest-rated content and most viewer votes.
- **Rating Trends**: Noted patterns in viewer ratings across different types of content.

#### Step 7 - Finalizing the Dashboard
- Added titles, company branding, and a clean theme to the dashboard.
- Inserted text boxes to briefly describe each visualization, ensuring clarity in insights.

## Conclusion
This Netflix Analysis Dashboard provides valuable insights into viewer preferences, helping identify popular content genres, regions with high viewer engagement, and top-rated shows and movies. The analysis can support data-driven decisions for content curation and regional marketing strategies.

## License
This project is for educational purposes and uses publicly available data.
