# 🎧 Spotify Song Popularity Analysis  

<p align="center">
  <img src="https://github.com/Aartizikre150/Spotify/blob/main/Images/image.jpg" alt="Spotify Project Banner" width="100%">
</p>

---

## 🧠 Objective  
Discover **what makes a song popular on Spotify** by analyzing audio features, artist influence, and temporal trends — and predicting song performance using data analytics and machine learning.

---

## 📊 Project Overview  
This project combines **Python analytics, Power BI visualizations, and an interactive web app** (built with Anvil) to explore and forecast song popularity.  

### 🔍 Highlights
- Cleaned and preprocessed raw Spotify datasets for reliability.  
- Conducted **Exploratory Data Analysis (EDA)** using Power BI.  
- Built a **stream count prediction model** with Python.  
- Integrated results into a **web app** for real-time analysis and predictions.  

---

## 🗂️ Folder Structure  

| Folder | Description |
|---------|-------------|
| `Dashboard/` | Contains Power BI dashboard (`.pbix`) visualizing song popularity metrics |
| `Datasets/` | Includes cleaned and raw Spotify datasets used for analysis |
| `Images/` | Contains project visuals and banner images |
| `Presentation/` | Holds PowerPoint slides summarizing the analysis |
| `website/` | Submodule folder linking the deployed Anvil web app |
| `.gitmodules` | Configuration file for submodule linkage |

---

## 🧰 Tools & Technologies  

| Category | Tools |
|-----------|-------|
| Programming | Python, Jupyter Notebook |
| Visualization | Power BI |
| Web Development | Anvil |
| Data Handling | Excel |
| Collaboration | Git, GitHub |
| Presentation | PowerPoint |

---

## 📈 Key Insights  
🎵 **Danceability** and **Energy** strongly predict song success.  
📅 **Friday releases** and **September drops** dominate streaming trends.  
🎤 **Collaborative songs** outperform solo tracks by up to 25%.  
📊 High **speechiness and loudness** correlate with top 10 chart positions.

---

## 🧰 Cloning Instructions  

Since this repository includes a **Git submodule** (`website/spotifycast`), make sure to clone it properly using the command below:

```bash
# Clone the main repository along with submodules
git clone --recurse-submodules https://github.com/Aartizikre150/Spotify.git

# OR if you already cloned it without submodules
git clone https://github.com/Aartizikre150/Spotify.git
cd Spotify
git submodule update --init --recursive
