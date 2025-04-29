# Project Title
## 🎬 Box Office Analysis for New Movie Studio

## Overview
With rising investments in original film material, the entertainment sector has grown significantly.  Knowing the factors that contribute to box office success is essential as our company prepares to open a new film studio.
 In order to identify trends pertaining to genres, budgets, release dates, and ratings that support strong box office returns, this study examines historical movie data.  The objective is to maximize audience engagement and profitability by directing strategic choices for film production and release.

## 💼 Business Understanding
Over the past decade, large media companies have shifted their focus towards original productions to capture and maintain viewer interest. To remain competitive, our company is launching a new movie studio targeting mainstream success.

### Business Problem:
We need to identify which factors—such as genre, budget, and release timing—significantly influence box office performance, so we can invest in the right kind of projects.

### Project Objectives:

Determine which movie genres (e.g., action, adventure, family) have historically performed best.

Identify optimal budget ranges that maximize profits across different genres.

Find the best seasons or months to release films to increase box office earnings.

Offer clear, data-driven recommendations to support film production planning and market positioning.

By achieving these objectives, the studio can minimize financial risks and make smarter investments in movie projects.

## 📁 Data Understanding and Analysis
### Data Sources:

Box Office Mojo: Box office gross revenue.

IMDb: Genre, ratings, release dates, runtime, and other movie details.

The Numbers: Budget and additional financial information.

Key Datasets Used:

bom.movie_gross.csv (box office revenue)

im.db (movie_basics and movie_ratings tables)

### Key Features Analyzed:

Movie Title

Genre(s)

Production Budget

Release Year and Date

IMDb Ratings

Domestic and Worldwide Box Office Gross

### Data Preparation and Cleaning:
Imported libraries such as Pandas, NumPy, SQLite3, and Seaborn to work with datasets.

Extracted data by unzipping .zip and .gz files.

Loaded structured data using SQLite3 (for .db files) and Pandas (for .csv files).

Cleaned datasets by handling missing values, removing duplicates, and fixing formatting issues.

Created new features where necessary (e.g., extracting months from release dates).

Exploratory Data Analysis (EDA):
Univariate Analysis: Examined distributions of genres, budgets, ratings, and gross revenues.

Bivariate Analysis: Compared genre vs gross earnings, budget vs revenue, and rating vs performance.

Correlation Matrix: Checked numerical relationships between budget, ratings, and revenue.

Visualizations: Bar plots, boxplots, scatterplots, and histograms were created to reveal patterns.

Key Insights Discovered:

Optimal Genre Selection:
Action, Adventure, and Family movies consistently generate higher box office returns compared to other genres like Drama or Horror.

Ideal Budget Range:
Movies with a budget between $50M–$150M tend to achieve strong financial performance. Extremely high or very low budget films are riskier unless supported by a strong brand or franchise.

Best Time to Release:
Movies released during Summer (June to August) and December holiday seasons perform significantly better, likely due to school vacations and festive periods when audiences are more available.

## 📝 Conclusion
This box office analysis provides clear strategies for the new movie studio to succeed in a competitive market:

Genre Focus: Invest in producing Action, Adventure, and Family-oriented films as they are highly popular and financially rewarding.

Smart Budgeting: Allocate production budgets carefully between $50M–$150M to balance quality and profitability.

Release Timing: Schedule movie releases during peak seasons—specifically, the summer months and December—for maximum audience reach and earnings potential.

By aligning film production choices with these insights, the studio will be well-positioned to launch strong, commercially successful movies that meet market demand and achieve sustained profitability.




