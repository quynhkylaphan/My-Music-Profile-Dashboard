# Spotify Playlist Analysis: Kyla's Music Profile

A comprehensive analysis of my personal Spotify playlist, "Kyla's Music Profile," containing 350 of my favorite tracks. This project uses data extracted from Spotify to visualize listening habits, explore audio feature trends, and uncover insights into my musical taste.

The visualization was created using Tableau and is based on playlist data as of July 29, 2025.

## 📊 Dashboard Preview
<img width="2559" height="1599" alt="image" src="https://github.com/user-attachments/assets/1c68f7fa-05c1-43b4-8b21-dd34ced8a7bb" />

*A full, interactive version of the dashboard can be viewed on [Tableau Public]([https://public.tableau.com/app/profile/your-profile-here](https://public.tableau.com/app/profile/kyla.phan/viz/MySpotifyPlaylist_17537532881240/Dashboard)) 

---

## ✨ Key Insights & Findings

The dashboard reveals several key patterns in my listening habits:

* **Top Artists & Genres**: My playlist is heavily dominated by **K-Pop** and **V-Pop**.
    * **TREASURE** is the most-played artist with 26 tracks, followed closely by **Justin Bieber** (22), **Taylor Swift** (17), and **Ariana Grande** (17).
    * K-Pop supergroups like **NCT 127** and **BLACKPINK** also feature prominently.

* **Preference for Recent Music**: There's a strong bias towards modern music.
    * The vast majority of tracks were released between **2021 and 2022**, indicating a preference for recent hits over classics.

* **Album Loyalty**: I tend to listen to albums, not just singles.
    * The album with the most tracks is **`THE SECOND STEP: CHAPTER ONE`** by TREASURE (11 songs), followed by **`Purpose`** by Justin Bieber (10 songs).

* **Audio Feature Analysis (The "Mood")**:
    * **Energy & Danceability**: My music taste leans towards **high-energy** and **highly danceable** tracks. The scatter plot shows a positive correlation between loudness and danceability—louder songs tend to be more danceable.
    * **Acousticness**: I have a clear preference for non-acoustic music. The analysis shows a strong negative correlation between a song's energy and its acousticness.
    * **Popularity**: Most songs in the playlist are mainstream, with popularity scores clustering between **50 and 80**.

---

## 🛠️ Tools & Technologies

* **Data Extraction**: Playlist data (including track names, artists, and audio features) was extracted from the Spotify API using [**Exportify**](https://exportify.net/).
* **Data Cleaning & Processing**: Minor data handling was performed using Microsoft Excel.
* **Data Visualization**: The dashboard was designed and built in [**Tableau**](https://www.tableau.com/).

---

## ⚙️ How to Use

You can explore this project in the following ways:

1.  **View the Interactive Dashboard**: For the full, interactive experience, please visit the dashboard on [Tableau Public](https://public.tableau.com/app/profile/your-profile-here) (<- Add your link here!).
2.  **Explore the Data**: The raw `.csv` data is available in the `/data` directory for you to conduct your own analysis.
3.  **Open the Workbook**: Download the `.twbx` file from the `/tableau` directory and open it with [Tableau Desktop](https://www.tableau.com/products/desktop) or the free [Tableau Reader](https://www.tableau.com/products/reader).
