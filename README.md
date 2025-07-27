# 🎬 Movie Recommendation System.

This is a movie recommendation system I built using Python and Streamlit. It gives movie suggestions based on genre and user preferences.

## 🔧 What I Used
- Python
- Streamlit
- Pandas
- Scikit-learn
- Kaggle datasets (movies.csv and ratings.csv)

## 🧠 What It Does
- Suggests similar movies using content-based filtering (genre).
- Also uses collaborative filtering based on user ratings.
- Final results are a mix of both (hybrid method).


## How it looks:
[how_it_looks..pdf](https://github.com/user-attachments/files/21452469/how_it_looks.pdf)

## 🔟 Project Summary

1. This is a movie recommendation system built using Python and Streamlit.
2. It suggests movies based on user preferences using machine learning.
3. The system uses a hybrid approach — combining content-based and collaborative filtering.
4. Content-based filtering recommends movies with similar genres.
5. Collaborative filtering suggests movies based on what similar users liked.
6. Datasets (`movies.csv` and `ratings.csv`) are taken from Kaggle.
7. TF-IDF Vectorizer and cosine similarity are used to compare movie genres.
8. The app shows top 10 movie suggestions when a movie is selected.
9. The app runs using: `python -m streamlit run movieapp.py --server.port 8502`
10. This project was completed during my internship and helped me learn how to apply ML in real projects.

## 📚 What I Learned

- How to preprocess and clean real-world datasets
- How recommendation systems work (content-based and collaborative)
- Using TF-IDF and cosine similarity for measuring similarity
- Building a Streamlit web app from scratch
- Fixing bugs and errors with the help of ChatGPT

## 🧑‍💼 Internship Note

This project was developed during my internship as a practical assignment.  
It helped me turn machine learning theory into a working application.  
I gained confidence in using Python and Streamlit for real-time apps.

## 🙏 Acknowledgements

- [Kaggle](https://www.kaggle.com/) for the movie dataset
- [Streamlit](https://streamlit.io/) for the easy app framework
- [ChatGPT](https://chat.openai.com/) for debugging and learning support

## 🧪 Behind the Scenes

- Movie genres are turned into vectors using TF-IDF.
- Cosine similarity finds how close one movie is to others.
- User ratings are used to find people with similar taste.
- Both scores are combined to recommend the best matches.

## ❓ FAQ

**Q: App not starting on port 8502?**  
A: Make sure no other app is using that port or change the port in the command.

**Q: Getting module not found error?**  
A: Run `pip install -r requirements.txt` to install all dependencies.

🖼 Example:

- **Selected Movie**: `'Hellboy': The Seeds of Creation (2004)`
- **Top 5 Recommended Movies**:
  1. Space Battleship Yamato (2010)
  2. Hidden Fortress, The (1958)
  3. Ghost Rider: Spirit of Vengeance (2012)
  4. Sanjuro (Tsubaki Sanjûrô) (1962)
  5. Monsters (2010)

> The results are based on genre similarity and user preference patterns.

📸 Screenshot:
[Screenshot.pdf](https://github.com/user-attachments/files/21452501/Screenshot.pdf)

## 📅 My Steps (Day by Day)

1. 📥 **Downloaded Dataset**  
   Collected `movies.csv` and `ratings.csv` from Kaggle.

2. 🧹 **Cleaned the Data**  
   Handled missing values, formatted genres, and prepared data for analysis.

3. 🧠 **Built Content-Based Filtering**  
   Used TF-IDF and cosine similarity to find movies with similar genres.

4. 👥 **Implemented Collaborative Filtering**  
   Created a user-movie matrix to recommend movies based on user preferences.

5. 🔀 **Combined Both into a Hybrid Model**  
   Merged content-based and collaborative filtering to give better suggestions.

6. 💻 **Created a Streamlit App**  
   Built a user-friendly interface to allow movie selection and display recommendations.

7. 🐞 **Tested and Fixed Errors**  
   Used ChatGPT support to debug and improve the code.
   
## ✅ Conclusion

This project helped me understand how movie recommendation systems work in real life.  
I used both content-based and collaborative filtering to build a hybrid model.  
The Streamlit app made the project interactive and user-friendly.  
I learned how to clean data, build models, and deploy an ML app step by step.  
Overall, it was a great learning experience during my internship.



