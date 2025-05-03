# 🎬 Movie Recommendation System with Posters

## 📌 Objective:
To build a web application that recommends the top 5 similar movies based on a selected movie and displays their poster images for an enhanced user experience.

---

## ⚙️ Technologies & Tools:
- **Python**
- **Pandas & NumPy** – For data preprocessing and similarity calculation
- **Gradio** – To create an interactive web interface
- **Requests** – To fetch movie poster images via API
- **Cosine Similarity** – For recommendation logic using CountVectorizer

---

## 📊 Dataset:
- **movies.csv** – Contains movie titles, genres, keywords, and overview
- **credits.csv** – Contains information on cast and crew

📥 **Download Dataset**: [Click here to access via Google Drive](https://drive.google.com/drive/folders/1PJYK5f_KOGig7qP9GwoS6jkq6uz_7w-F?usp=drive_link)

---

## 🔍 Methodology:

🔹 **Data Cleaning**  
   - Removed null values  
   - Merged datasets on movie ID  

🔹 **Feature Engineering**  
   - Extracted relevant text features: genres, keywords, cast, and crew  

🔹 **Vectorization**  
   - Converted text data to vectors using `CountVectorizer`  

🔹 **Similarity Matrix**  
   - Calculated pairwise cosine similarity between movie vectors  

🔹 **Poster Fetching**  
   - Used TMDb API to fetch poster URLs dynamically  

🔹 **User Interface**  
   - Built an interactive front-end using Gradio  
   - Users can select a movie and view recommendations with posters  

---

## 🎯 Output:
- ✅ Recommends top 5 similar movies based on user’s input  
- ✅ Displays posters for a visually engaging recommendation experience  

---

## 🚀 Hosted On:
- **Hugging Face Spaces** – Using Gradio App  
👉 (https://huggingface.co/spaces/himanshiag8/movie-recommender)

---

## ✅ Status:
- 📦 Completed  
- 💻 Hosted and working as expected  
- 🛠️ Ready for deployment and public use  

---

## 🙋‍♀️ Author
**Himanshi Agarwal** – Data Analyst | Python & ML Enthusiast  
📫 [Connect on LinkedIn](https://www.linkedin.com/in/himanshi-agarwal-70211725b/)
