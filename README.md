# Netflix Exploratory Data Analysis📈
This project performs an in-depth exploratory data analysis (EDA) on a dataset of Netflix movies and TV shows to uncover key trends, patterns, and insights into the platform's content library. The analysis covers various aspects, including content distribution, temporal trends, top creators, and more, all supported by data visualizations.
![Image](attachment.jpg)
## Project Structure
The project is a single Jupyter Notebook (Exploratory_Data_Analysis_of_Netflix_Data.ipynb) that follows a clear, step-by-step process:

## Introduction: Outlines the project's objective and provides an overview of the dataset.

**Data Cleaning & Formatting:** Addresses data quality issues such as renaming columns, handling missing values, and converting data types.

**Basic EDA:** Provides a high-level summary of the dataset, including content type counts (movies vs. TV shows), top countries, and release year distributions.

**Questions & Answers (Q&A):** A detailed section with visualizations that answers specific questions about the dataset, such as:

What are the top 10 longest movies?

Which directors have the most titles?

How has the number of releases changed over the years?

What is the distribution of content ratings?

**Conclusion & Insights:** Summarizes the key findings and suggests potential next steps for further analysis.

## Key Findings
**Content Library Composition:** The Netflix catalog is predominantly composed of movies, which outnumber TV shows by a significant margin.

**Period of Growth:** The platform experienced a rapid expansion in its content library between 2016 and 2019, with a peak in new releases in 2019.

**Geographical Focus:** The United States is the leading producer of content in the dataset, followed by India and the United Kingdom, indicating a concentration on a few major markets.

**Popular Genres:** "Documentaries" and "Stand-Up Comedy" are among the most common content types, highlighting Netflix's focus on non-fiction and special-format content.

**Target Audience:** The most frequent content ratings are "TV-MA" and "TV-14," suggesting a primary focus on mature and teenage audiences.

### How to Run the Notebook
Clone the repository:
git clone <repository-url>

Navigate to the project directory:
cd <project-directory>

Ensure you have Jupyter and the necessary libraries installed:
pip install pandas numpy matplotlib seaborn

Open and run the Jupyter Notebook:
jupyter notebook
The notebook will open in your browser, and you can run the cells to reproduce the analysis.

## Future Work
*Sentiment Analysis:* Analyze the sentiment of the description text to categorize content based on emotional tone.

*Network Analysis:* Construct a network graph to visualize collaborations between directors and cast members.

*Recommendation System:* Use the insights from this analysis to develop a basic content-based recommendation system.
