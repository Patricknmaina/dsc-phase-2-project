### GROUP ONE PROJECT.

**MEMBERS:**

Patrick Maina(Group leader),
Teresia Njoki,
Christine Ndungu,
George Nyandusi.

**Class:** DSFT12- Fulltime/hybrid, Phase 2

**Instuctor:** Nikita Njoroge



## Project Title

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

### Key Datasets Used:

bom.movie_gross.csv (box office revenue)

im.db (movie_basics and movie_ratings tables)

Specifically, we are working with these datasets:

bom.movie_gross.csv: Gross earnings (domestic and international).

**im.db SQLite database:**

i) movie_basics table — Contains movie title, genre, runtime, and release year.

ii) movie_ratings table — Contains average IMDb ratings and number of votes.

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

### Exploratory Data Analysis (EDA):
- Here we will do:

**Univariate Analysis (Single-Variable Analysis):**

This is examining one variable at a time to understand the distribution and characteristics of individual variables

Eg: Examined distributions of genres, budgets, ratings, and gross revenues.

**Bivariate Analysis  (Two-Variable Analysis):** 

This is examining relationships between two variables to help Identify patterns, relationships or differences between variables.

Eg: Compared genre vs gross earnings, budget vs revenue, and rating vs performance.

**Correlation Matrix:**

Checked numerical relationships between budget, ratings, and revenue.

### Visualizations: 

-Bar plots, scatterplots, pie chart and histograms were created to reveal patterns.

We visualized the relationships between different factors.

Some examples include:

Comparing  rating vs revenue.

Stating the top 5 studios.

Comparing gross revenue distribution by genre

Checking if PG-13 movies outperform R-rated ones at the box office.

### Hypothesis Testing

Conduct statistical tests to validate or reject assumptions such as:

- Do movies from major studios(eg Warner Bros,Disney)consistently earn higher box office revenue than smaller studios?

**findings:** Movies from major studios(eg Warner Bros,Disney)consistently earn higher box office revenue than smaller studios

- Do short movies (runtime < 90 minutes) have different average ratings compared to long movies (runtime ≥ 90 minutes)?

**Findings:** Yes, there is a statistically significant difference, Long movies (≥ 90 minutes) tend to have higher average ratings compared to short movies in this dataset.


### Key Insights Discovered:

### 1.Optimal Genre Selection:(choosing best genre)

**Genres that blend multiple popular themes dominate the box office.**

The top genre — Adventure, Drama, Sport — has a significantly higher average domestic gross (over $400 million) compared to others.

Other top-performing genres like Action, Adventure, Sci-Fi and Adventure, Drama, Sci-Fi also show that combining adventure with other strong themes (action, drama, sci-fi, sport) results in higher earnings.

Meanwhile, single genres like Sci-Fi and Fantasy/Romance perform well but not as highly as the multi-theme combinations

### 2.Ideal Budget Range:
Movies with a budget between $50M–$150M tend to achieve strong financial performance. Extremely high or very low budget films are riskier unless supported by a strong brand or franchise.

### 3.Best Time to Release:
Movies released during Summer (June to August) and December holiday seasons perform significantly better, likely due to school vacations and festive periods when audiences are more available.

### 4. Movies released over the years.
-The number of movies released each year increased slightly from 2010 to 2015, peaking around 390 movies in 2015.

-However, after 2015, there was a clear and sharp decline in the number of movies released each year, dropping drastically after 2017, with very few movies released in 2019.

-This suggests that after a period of steady production, something caused a major disruption or slowdown starting in 2016–2017, worsening into 2019.


## 📝 Conclusion
Through this box office analysis, we offer strategic guidance for the new studio to navigate and excel in the competitive film industry.

**Genre Focus:** Invest in producing Action, Adventure, and Family-oriented films as they are highly popular and financially rewarding.

**Smart Budgeting:** Allocate production budgets carefully to balance quality and profitability.

**Release Timing:** Schedule movie releases during peak seasons—specifically, the summer months and December—for maximum audience reach and earnings potential.

By aligning film production choices with these insights, the studio will be well-positioned to launch strong, commercially successful movies that meet market demand and achieve sustained profitability.



