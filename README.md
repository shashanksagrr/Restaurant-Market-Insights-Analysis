# Cognifyz Data Analysis Internship Tasks

Welcome to my submission for the **Cognifyz Data Analysis Internship**. This repository contains all the completed tasks for the internship program. Below, you will find an overview of the project structure, task details, and instructions to run the code.

## About Cognifyz

**Cognifyz Technologies** is a leading technology company specializing in data science, artificial intelligence (AI), and machine learning (ML). They deliver innovative solutions and training programs, enabling businesses to make data-driven decisions in real-time.

## Project Overview

The internship program includes tasks spanning three levels of complexity: **Level 1**, **Level 2**, and **Level 3**. This repository contains solutions for tasks across these levels. The tasks involve data cleaning, exploration, visualization, and analysis of a restaurant dataset.

### Dataset

The dataset used for this analysis includes the following columns:
- `Restaurant ID`, `Restaurant Name`, `Country Code`, `City`, `Address`, `Locality`, `Locality Verbose`
- `Longitude`, `Latitude`, `Cuisines`, `Average Cost for two`, `Currency`
- `Has Table booking`, `Has Online delivery`, `Is delivering now`, `Switch to order menu`
- `Price range`, `Aggregate rating`, `Rating color`, `Rating text`, `Votes`

The dataset file should be located at: `C:\Users\sagar\Downloads\Cognifyz Internship\Dataset .csv`

---

## Tasks Overview

### Level 1 Tasks

1. **Top Cuisines**
   - Determine the top three most common cuisines.
   - Calculate the percentage of restaurants serving each of the top cuisines.

2. **City Analysis**
   - Identify the city with the highest number of restaurants.
   - Calculate the average rating for restaurants in each city.
   - Determine the city with the highest average rating.

3. **Price Range Distribution**
   - Create a histogram or bar chart for the distribution of price ranges.
   - Calculate the percentage of restaurants in each price range.

4. **Online Delivery**
   - Determine the percentage of restaurants offering online delivery.
   - Compare the average ratings of restaurants with and without online delivery.

---

### Level 2 Tasks

1. **Restaurant Ratings**
   - Analyze the distribution of aggregate ratings.
   - Determine the most common rating range.
   - Calculate the average number of votes received by restaurants.

2. **Cuisine Combination**
   - Identify the most common combinations of cuisines.
   - Determine if certain cuisine combinations tend to have higher ratings.

3. **Geographic Analysis**
   - Plot restaurant locations on a map using longitude and latitude.
   - Identify patterns or clusters of restaurants in specific areas.

4. **Restaurant Chains**
   - Identify restaurant chains in the dataset.
   - Analyze the ratings and popularity of these chains.

---

### Level 3 Tasks

1. **Restaurant Reviews**
   - Analyze the most common positive and negative keywords in reviews.
   - Calculate the average length of reviews.
   - Explore the relationship between review length and rating.

2. **Votes Analysis**
   - Identify the restaurants with the highest and lowest votes.
   - Analyze the correlation between votes and ratings.

3. **Price Range vs. Online Delivery and Table Booking**
   - Analyze the relationship between price range and the availability of online delivery and table booking.
   - Determine if higher-priced restaurants are more likely to offer these services.

---

## Getting Started

### Prerequisites

1. Install Python 3.x
2. Install the required libraries:
   ```bash
   pip install pandas matplotlib seaborn folium sklearn
