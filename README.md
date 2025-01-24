# Movie Recommendation System

## Description
The **Movie Recommendation System** is a Python-based project that uses Machine Learning techniques to recommend movies. This system employs collaborative filtering with cosine similarity to analyze user preferences and recommend similar movies.

---

## Features
1. **Collaborative Filtering**: Recommends movies based on user input.
2. **Text Vectorization**: Utilizes TF-IDF to process text data.
3. **Cosine Similarity**: Computes similarity between movies to generate recommendations.

---

## Prerequisites
- Python 3.7 or higher
- Required libraries:
  - `pandas`
  - `numpy`
  - `sklearn`

---

## Installation
1. Clone the repository or download the source code.
   ```bash
   git clone https://github.com/your-username/movie-recommendation-system.git
   cd movie-recommendation-system
   ```
2. Install the required libraries:
   ```bash
   pip install pandas numpy scikit-learn
   ```
3. Place the `movies.csv` dataset in the same directory as the script.

---

## Usage
1. Run the script:
   ```bash
   python movie_recommendation.py
   ```
2. When prompted, enter the name of a movie:
   ```
   Enter Movie Name: Inception
   ```
3. The system will display a list of 10 recommended movies based on the input.

---

## Dataset
- The `movies.csv` dataset should contain the following columns:
  - `title`: Movie title
  - `genres`: Genres of the movie
  - `keywords`: Keywords associated with the movie
  - `original_language`: Original language of the movie
  - `cast`: Main cast of the movie
  - `director`: Director of the movie

---

## File Structure
```
movie-recommendation-system/
├── movie_recommendation.py  # Main source code
├── movies.csv               # Dataset
├── README.md                # Documentation file
```

---

## Example
1. Input:
   ```
   Enter Movie Name: The Dark Knight
   ```
2. Output:
   ```
   The Dark Knight: Christian Bale, Heath Ledger, Aaron Eckhart
   Batman Begins: Christian Bale, Michael Caine, Liam Neeson
   Inception: Leonardo DiCaprio, Joseph Gordon-Levitt, Ellen Page
   ...
   ```

---

## Limitations
1. Recommendations are limited to the data provided in the `movies.csv` file.
2. The accuracy of recommendations depends on the quality of the dataset.

---

## Future Enhancements
- Integrate a user interface for better interaction.
- Include additional features like user ratings.
- Incorporate more advanced recommendation algorithms.

---

## Author
**Mohammed Ayaan Qureshi**
- GitHub: [AyaanQureshi1006](https://github.com/AyaanQureshi1006)
- Email: ayaanalisha59@gmail.com

