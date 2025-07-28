# Harry Potter Power BI Dashboard  


## Table of Contents

- [Overview](#overview)
- [Dataset](#dataset)
- [Process](#process)
- [Features](#features)
- [Insights](#insights)
- [Learning](#learning)

## Overview
Character dialogues for all 8 movies in the Harry Potter franchise, including additional information about each movie, its chapters, characters, places, and spells.
<img width="1521" height="814" alt="Overview" src="https://github.com/user-attachments/assets/4ad90e4f-8893-44c6-bb16-ea0d170d9dbf" />  

![Overview 1](https://github.com/user-attachments/assets/b3e87ae3-12ed-49c1-9106-38721b2c6772)  


![Overview 2](https://github.com/user-attachments/assets/e088a153-6ec2-459b-a320-3efe6ee72b41)  


## Dataset

### Name: Harry Potter Movie Scripts
**Dataset:** https://mavenanalytics.io/data-playground 

The dataset includes the following CSV files :  

### 1)Chapters:    
**Chapter ID**	Unique identifier for each chapter  
**Chapter Name**	Name of the chapter in the movie script  
**Movie ID**	Foreign key to match with Movies table  
**Movie Chapter**	Chapter number within each movie script      
  

### 2)Characters:    
**Character ID**	Unique identifier for each character  
**Character Name**	Name of the character  
**Species**	Species of the character  
**Gender**	Gender of the character  
**House**	Hogwarts house (or name of other magical school)  
**Patronus**	Patronus of the character  
**Wand (Wood)**	Type of wood for the character's wand  
**Wand (Core)**	Core for the character's wand  

### 3)Places:    
**Place ID**	Unique identifier for each place  
**Place Name**	Name of the place  
**Place Category**	Type of place  

### 4)Spells:   
**Spell ID**	Unique identifier for each spell  
**Incantation**	Words needed to conjure the spell  
**Spell Name**	Name of the spell  
**Effect**	What the spell does  
**Light**	Light the spell casts  

### 5)Dialogue:  
**Dialogue ID**	Unique identifier for each line of dialogue  
**Chapter ID**	Foreign key to match with Chapters table  
**Place ID**	Foreign key to match with Places table  
**Character ID**	Foreign key to match with Characters table  
**Dialogue**	Line of dialogue from the movie script  
	
### 6)Movies:      
**Movie ID**	Unique identifier for each movie  
**Movie Title**	Full movie name  
**Release Year**	Year the movie was released in theaters  
**Runtime**	Length of the movie in minutes  
**Budget**	Budget for the movie is US Dollars  
**Box Office**	Box office revenue for the movie in US Dollars   



## Process

Tools Used :- Microsoft Excel, Microsoft Power BI.  

Process:-   
-Familiarizing with the dataset.  
-Connecting the data to a Power BI file.    
-Performing Data Cleaning Operations.  
-Generating required Column for analysis.  
-Checking Data Module.     
-Generating Calculations where required.  
-Designing a Power BI dashboard.  
-Creating data visuals for the Power BI dashboard as per the design.  
-Formatting the Visuals.  
-Adding Slicers and other visuals.  

## Features


#### 1. **Visual Revenue Metrics**
- **Gross Revenue ($7.78bn)**: Clearly highlights the total box office performance across all movies.
- **Budget/Cost ($1.36bn)**: Summarizes the cumulative production investment.
- **Net Revenue ($6.42bn)**: Displays the profit after deducting budgets from gross revenue.
- **% Margin (474.13%)**: Provides a profitability snapshot across the film series.

#### 2. **Movie-Level Financial Performance**
- **Budget and Gross Revenue by Movie**: 
  - Each film shows its budget (circle icon) and box office gross (bar) for side-by-side comparison.
- **Net Revenue & % Margin by Movie**: 
  - Bar/line chart depicts each movie's net earnings and individual profit margin, making outliers and top performers easily identifiable.

#### 3. **Content Breakdown**
- **Chapters by Movie**: 
  - Horizontal bar chart ranks movies by the number of book chapters they adapt, facilitating a comparison of narrative depth or book coverage.
- **Characters by Place (Tree Map):**
  - Visualizes which magical locations (e.g., Hogwarts, Dwellings, Diagon Alley, Hogsmeade) feature the most characters, supporting exploration of world-building.

#### 4. **Usability Enhancements**
- **At-a-Glance Highlights**: Bold fonts and color differentiation for key statistics enable quick visual scanning.
- **Thematic Branding**: Consistent Harry Potter motifs (color palette, typeface, logo) immerse the user in the magical setting.
- **Interactive Charts (Implied by Buttons)**: Options for toggling or switching views (via ellipses or buttons) allow deeper data exploration.

#### 5. **Categorical Insights**
- **Location-Specific Analysis**: Breaks down character appearances by their corresponding magical places, enhancing understanding of story settings.
- **Movie Comparison**: Allows for detailed tracking of how each film adapts the books (chapters) and performs financially (cost vs. return).

**Summary:**
This dashboard aggregates Harry Potter movie data into an engaging visual story, supporting both high-level and granular exploration of financial, narrative, and world-building metrics. It serves as a comprehensive tool for fans, analysts, and marketers interested in the franchise's blockbuster dynamics.  


## Insights

### Insights from the Harry Potter Movie Dashboard

#### 1. **Impressive Franchise Profitability**
- The Harry Potter movies achieved a **gross revenue of $7.78bn** against a collective budget of **$1.36bn**, resulting in a remarkable **net revenue of $6.42bn** and an overall profit **margin of 474.13%**. This underscores the franchise as one of the most lucrative in film history.

#### 2. **Most and Least Profitable Movies**
- **The Chamber of Secrets** led in profitability with a **net margin of 780.3%**, followed closely by **The Deathly Hallows Part 2 (701.6%)** and **The Order of the Phoenix (528.0%)**.
- **The Half-Blood Prince** had the lowest profitability among the series, with a margin of **277.3%**, still an impressive achievement but highlighting some variation in return on investment across individual films.

#### 3. **Chapter Coverage Across Films**
- **The Chamber of Secrets** adapted the most chapters from its source book (**36 chapters**), followed by **The Philosopher's Stone (34)** and **The Prisoner of Azkaban (33)**. This suggests certain films tackled larger narrative scopes, potentially impacting their runtimes and story complexity.

#### 4. **Distribution of Characters by Magical Location**
- **Hogwarts** is the dominant setting, featuring **121 characters**, far outpacing all other locations.
- **Dwellings (e.g., homes)**, **Other Magical Locations**, **Diagon Alley**, and **Hogsmeade** follow, with 66, 46, 29, and 34 characters, respectively. This highlights the centrality of Hogwarts in the narrative and its role as the main hub for character interaction.

#### 5. **Cost vs. Earnings Dynamics by Movie**
- Several films, notably **The Philosopher’s Stone** and **The Deathly Hallows Part 2**, combined relatively modest budgets ($125M, $250M) with some of the highest gross revenues (over $1B and nearly $1.35B, respectively).
- Strong correlation exists between **higher gross revenues and higher net margins**, except in cases where exceptional budget increases (like in the later movies) slightly narrowed margins but not the overall profit.

#### 6. **Narrative and Financial Synergy**
- Films that adapted more chapters did not always generate higher profits, suggesting that **fidelity to book length doesn’t necessarily correlate with box office returns**. Instead, timing, story appeal, and marketing likely played bigger roles.

#### 7. **World-Building Strength**
- The diversity of characters by place demonstrates the Harry Potter universe’s depth, with **Hogwarts’ dominance** reaffirming its status as the story’s heart and the main draw for fans.

**Overall:**  
The dashboard reveals that the Harry Potter series was both a critical storytelling achievement (comprehensive world-building, strong narrative coverage) and an unparalleled financial success, driven by effective adaptation strategies, strong settings like Hogwarts, and efficient production-to-earning ratios.


## Learning

Data connectivity basics in Power BI.  
Data modeling basics in Power BI.  
Designing a Power BI dashboard.  
Using DAX to generate calculated fields.  
