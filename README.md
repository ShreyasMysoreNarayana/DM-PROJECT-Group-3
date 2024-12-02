# Movie Recommendation System - Data Mining Project

Welcome to the Movie Recommendation System project! 🎬 

This repository contains the code and methodology to build a recommendation engine using the MovieLens dataset, providing personalized movie recommendations based on user preferences, past ratings, and collaborative insights.

🌟 **Project Overview:**

The objective of this project is to develop a recommendation engine capable of generating tailored movie recommendations. Using machine learning and data mining techniques, this system can predict which movies users may enjoy based on their previous interactions and preferences.

**Features:** <br>
•Dataset: MovieLens dataset with 20 million ratings, including metadata, genres, and user tags.<br>
•Algorithms: Collaborative filtering, content-based filtering, and hybrid models.<br>
•Evaluation: Custom similarity-based scoring for accurate recommendations.<br>

📂 **Dataset**

We’re using the MovieLens 20M Dataset, which contains:<br>
•	20 million ratings and 465,564 tag applications across 27,278 movies.<br>
•	Information on user preferences, tags, genres, and more.<br>

This rich dataset enables the application of various recommendation algorithms, each taking a unique approach to understanding and predicting user preferences.

🔍 ### **Methodology:**

1.	Data Loading and Preprocessing<br>
    o	Import datasets, merge as needed, and handle missing values.<br>
    o	Clean data and format columns for compatibility with modeling.<br>
2.	Algorithm Selection<br>
    o	Collaborative Filtering: Recommends movies based on similar users’ preferences.<br>
    o	Content-Based Filtering: Uses movie metadata (e.g., genre) to recommend similar items.<br>
    o	Hybrid Model: Combines collaborative and content-based methods for more robust recommendations.<br>
    o   Data Mining: Assosiation Rule Mining is also used for the recommendations.<br>

📊 **Project Structure:** <br>
•	Data: movie.csv, rating.csv, tag.csv, link.csv, genome_tags.csv, genome_score.csv - the main datasets used in this project.<br>
•	Scripts: Core R and Python scripts for data processing, model training, and evaluation.<br>
•	Notebooks: Contains exploratory data analysis (EDA) and model experimentation.<br>

💻 ### **Getting Started**<br>
**Prerequisites**<br>
To run this project, you’ll need:<br>
•	R (Version 4.0 or later)<br>
•	Python (Optional, for cross-verification or additional analysis)<br>
•	R Libraries: dplyr, ggplot2, recommenderlab, tidyr<br>
•	Python Libraries: pandas, numpy, scikit-learn, matplotlib<br>

**Installation:** <br>
    - Clone the repository and install necessary packages.<br>
    - bash<br>
    - Copy code<br>
    - git clone https://github.com/ShreyasMysoreNarayana/DM-PROJECT.git<br>
    - cd DM-PROJECT<br>
    - Running the Code<br>

Copy code

🚀 **Usage**
1.	Load Dataset: Load the dataset (final_df.csv) from the drive link.  
2.	Run Model: Open the app_841.R file and WWW folders with images and save in a same folder.
3.	Get Recommendations: Run the app_841.R in Rstudio and get the movie recommendations.

📈 **Results and Insights**
Explore various recommendation models and compare results:<br>
•	Collaborative Filtering: Effective for users with detailed interaction histories.<br>
•	Content-Based Filtering: Ideal for cold-start users by recommending similar items.<br>
•	Hybrid Model: Provides comprehensive recommendations by leveraging both user interactions and movie metadata.<br>

📝 **Future Improvements**
Some ideas for future development:<br>
•	Integrate additional data sources for enhanced personalization.<br>
•	Implement neural network-based methods for improved accuracy.<br>
•	Build an interactive web interface for real-time recommendations.<br>

🤝 **Contributing**
We welcome contributions! If you find a bug or have an idea to improve the recommendation engine:<br>
> 1.	Fork the repository.<br>
> 2.	Create a feature branch (git checkout -b feature/YourFeature).<br>
> 3.	Commit your changes (git commit -m 'Add your feature').<br>
> 4.	Push to the branch (git push origin feature/YourFeature).<br>
> 5.	Open a pull request.<br>

📄 **License**
This project is licensed under the MIT License.

📬 **Contact**
Feel free to reach out if you have questions or suggestions.
