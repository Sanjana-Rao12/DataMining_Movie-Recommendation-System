# 🎥🍿 NEXT-FLIX: A Movie Recommendation System 🍿🎥

---
## Team Members 
•POOJITHA REDDY BOMMU
•HARSHITHA KESANI
•HARSHINI NIMMALA
•NUPOOR KUMBHAR
•LIKHITHA REDDY KESARA
•MONIKA NANJAPPA
•MUHAMMAD SAAD RAJA
•SANJANA PONAGANTI
•SUGUNA CHANDANA SIBBENA
•TASNEEM SHABBIR ATTARWALA

---
## Overview
NEXT-FLIX is an interactive movie recommendation system built using **Shiny in R**. It leverages a genre-based similarity matrix to recommend movies to users based on their selected preferences. The project combines data processing, genre analysis, and user-friendly visualization to deliver a seamless recommendation experience.

---

## Features
- **Movie Recommendation**: Get personalized movie recommendations based on genre similarity.
- **Interactive User Interface**: Built with a dark-themed Shiny UI for an immersive user experience.
- **Customizable Inputs**: Select multiple movies and choose the number of recommendations.
- **Automated Processing**: Process input data and generate outputs dynamically.
- **Evaluation Scores**: Compare predicted recommendations against actual preferences and generate evaluation scores.

---

## Technologies Used
- **Language**: R
- **Libraries**: 
  - `dplyr` and `stringr` for data manipulation.
  - `readr` for handling CSV files.
  - `DT` for interactive data tables.
  - `shiny` and `bslib` for building the user interface.
- **Tools**: Shiny app for interactive user inputs and outputs.

---

## How It Works
1. **Data Input**:
   - Load a pre-processed dataset containing movie genres and user inputs.
2. **Genre Similarity Calculation**:
   - Compute a genre-based similarity matrix using Euclidean distance.
3. **Recommendation Engine**:
   - Recommend movies based on input preferences using the similarity matrix.
4. **Interactive Interface**:
   - Users can select movies, specify the number of recommendations, and view results in a table.
5. **Evaluation**:
   - Compare predicted recommendations with actual movie preferences to compute scores.

---

## Usage Instructions
### Prerequisites
- R and RStudio installed on your system.
- Required R libraries (`dplyr`, `stringr`, `readr`, `DT`, `shiny`, `bslib`) installed.

### Steps to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/next-flix.git
   ```
2. Open the R script in RStudio.
3. Run the script to launch the Shiny app:
   Also make sure the datasets paths matches properly, since they come from your local directory.
   ```R
   shinyApp(ui = ui, server = server)
   ```
5. Select your favorite movies and explore the recommendations!

---

## File Structure
- **`data_cleaned.csv`**: Pre-processed dataset with movie genres.
- **`data_cleaned_encoded.csv`**
-   Link to access above 2 files : https://www.dropbox.com/scl/fo/f7k0iqnacfthib769csqm/AEK6a8kyEhj3Fk2QSDBCbew?rlkey=3icjot0xak57kkelraotvu1yz&st=vm7xyhho&dl=0
- **`formatted_movies.csv`**: Input file with user movie lists.
- **`recommendations_output.csv`**: Output file with predicted recommendations.
- **`y_data_comma_separated_corrected.csv`**: Actual movie preferences for evaluation.
- **`score_file.csv`**: File containing evaluation scores for recommendations.

---

## Future Scope
- Expand the dataset to include additional genres and metadata (e.g., cast, director).
- Explore advanced recommendation techniques like collaborative filtering or hybrid models.
- Enhance the evaluation metrics to capture user satisfaction more comprehensively.

---

## Acknowledgments
- Developed in collaboration with **Prof. Lucy Nwosu** for the **Data Mining 2024** course.
- Inspired by popular recommendation engines like Netflix and IMDb.


