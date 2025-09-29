🎬 Netflix Movies & TV Shows Analysis (Python Data Analytics Project)
📌 Project Overview

This project analyzes the Netflix Titles Dataset to uncover insights about movies and TV shows available on the platform. Using Python (Pandas, Matplotlib, Seaborn), the data was cleaned, processed, and explored through EDA (Exploratory Data Analysis).

🔹 Key Objectives

Clean and preprocess dataset (handle missing values, duplicates, and special characters).

Analyze the distribution of Movies vs TV Shows.

Identify which category dominates Netflix’s library.

Explore trends in content by country, release year, and ratings.

Build visualizations for better understanding.

🛠️ Tools & Libraries

Python

Pandas

Matplotlib

Seaborn

Jupyter Notebook

📊 Analysis & Insights

Netflix has more Movies than TV Shows (Movies dominate).

Top contributing countries include United States, India, and UK.

Most releases happened after 2010, showing rapid content growth.

Ratings distribution shows majority content is for TV-MA (Mature Audience).

📂 Project Structure
├── netflix_titles.csv        # Dataset
├── Netflix_EDA.ipynb         # Jupyter Notebook with code
├── visuals/                  # Plots & Graphs
└── README.md                 # Project Documentation

🚀 How to Run

Clone the repository:

git clone https://github.com/YourUsername/Netflix-Data-Analysis.git


Open Jupyter Notebook:

jupyter notebook Netflix_EDA.ipynb

📬 Connect With Me

linkedin

it.divya6@gmail.com
# Detailed Explination

# Netflix_Data_Analysis_Using_Python
Exploratory Data Analysis (EDA) on Netflix dataset using Python. Cleaned and prepared data (handled missing values, duplicates, special characters). Analyzed Movies vs TV Shows, release trends, ratings, and top content-producing countries. Visualized insights with Matplotlib &amp; Seaborn to highlight patterns in Netflix’s library.

# Pandas Numpy Instllation
<img width="650" height="324" alt="Pandas Numpy Instllation" src="https://github.com/user-attachments/assets/b31f5339-8349-4217-9b33-0e2b0b553a89" />

# Data Set Head
<img width="647" height="353" alt="Head" src="https://github.com/user-attachments/assets/fb1a3c90-d6ed-484d-8190-f003c4aa84fd" />

# Remove Missing Value

<img width="576" height="324" alt="Remove Missing Value" src="https://github.com/user-attachments/assets/4b1b75d9-134e-462f-9a1a-3317ac1715d8" />
<img width="624" height="446" alt="Remove Missing Value" src="https://github.com/user-attachments/assets/216dd4ed-ab5c-4c2c-b683-816ddb2b68cd" />

Insight: Many Netflix entries do not have a listed director (almost 30% missing). This often happens for TV shows where 

multiple directors are involved, or for older regional content. Missing cast/country data may indicate less-documented 

international content.

# Titel Normlaization

<img width="624" height="446" alt="Titel Normlaization" src="https://github.com/user-attachments/assets/a0ab4360-be86-41f7-bb74-86f798f5bfe0" />
<img width="576" height="446" alt="Titel head" src="https://github.com/user-attachments/assets/5967b977-5ae4-40c4-bd00-fd6fd95120df" />

# Movies vs TV Show On Netflix
<img width="651" height="446" alt="Countploat chart" src="https://github.com/user-attachments/assets/8d8485a0-d8cc-4330-b0d1-b86c7af25e81" />

<img width="576" height="446" alt="Movies vs TV Show On Netflix" src="https://github.com/user-attachments/assets/f3a85ffa-df81-4689-94cd-453205e461f2" />

# Movies vs TV show persantage
<img width="624" height="446" alt="PIE Chart" src="https://github.com/user-attachments/assets/7219eed9-38d0-4f9b-86d8-68c26f565d9f" />
<img width="576" height="446" alt="Movies vs TV show persantage" src="https://github.com/user-attachments/assets/f90f11b5-86f8-4584-b010-2456b8e93c80" />

Insight: Netflix is movie-dominant, with about 70% movies and 30% TV shows.

TV shows are increasing over time, but movies still form the bulk of Netflix’s catalog.

This suggests Netflix focuses heavily on movies for quick consumption, while TV shows are long-term engagement drivers.


# Data Type Conversion
<img width="637" height="446" alt="Data Type Conversion" src="https://github.com/user-attachments/assets/026ba05e-97f3-455b-815c-75cb0b343024" />


# Growth of Movies vs TV Shows on Netflix (By Year)
<img width="641" height="446" alt="Line Chart (Count of Release Per Year)" src="https://github.com/user-attachments/assets/722399a0-6e24-4f6e-ae69-86ee6c1d7e83" />
<img width="626" height="526" alt="Growth of Movies vs TV Shows on Netflix (By Year)" src="https://github.com/user-attachments/assets/b7b7a026-2a45-41eb-9202-b0ff50069f85" />

Netflix saw huge growth in content production post-2015, coinciding with its global expansion strategy.

Peak growth: Around 2018–2020 (lots of Originals + international expansions).

After 2020, the growth may flatten slightly (pandemic years).

Both movies and TV shows increased, but movies consistently outnumber TV shows.

# Top 10 countries Producing Netflix Content
<img width="636" height="366" alt="Top 10 countries 1" src="https://github.com/user-attachments/assets/b1089f44-81b9-4181-843a-65279e0de21d" />
<img width="636" height="366" alt="Top 10 Countries Producing Netflix Content" src="https://github.com/user-attachments/assets/340ca7cb-1e88-40dc-a563-2c7ab7476a76" />

USA dominates Netflix content (almost 1/3rd of catalog).

India ranks 2nd → Netflix heavily invests in Bollywood/regional Indian content to expand in Asia.

UK, Japan, South Korea → known for strong entertainment industries (anime, K-dramas).

Egypt in Top 10 → shows Netflix’s push into Middle Eastern/North African content.

# Top 10 Countries Producing More Tv shows vs Movies
<img width="640" height="366" alt="Top 10 Countries Producing More Tv shows vs Movies" src="https://github.com/user-attachments/assets/b62ec029-484c-4cc4-a553-8aae1771eedc" />
<img width="636" height="366" alt="Top 10 Countries Producing More Tv shows vs Movies2" src="https://github.com/user-attachments/assets/816ca5b9-71f4-41e1-92ab-17b00e70e5fc" />

USA: Balanced, but more movies.

India: Dominated by movies (Bollywood-heavy).

Japan & South Korea: Strong TV content industries → Netflix leverages anime & K-dramas.

Canada, Spain, France: Moderate but diverse contributions.

Egypt: Mostly movies.

# Overall Insights Summary:

Movies dominate Netflix (≈70%), but TV shows are a growing segment.

Post-2015 explosion in releases → aligns with Netflix Originals and global expansions.

USA is the leader in content, followed by India, UK, Japan, and South Korea.

Regional content strategy: Netflix pushes Bollywood (India), Anime (Japan), and K-dramas (Korea).

Egypt’s presence highlights Netflix’s reach into African/MENA content markets.

Missing directors/cast info suggests many regional or older entries are less documented.
