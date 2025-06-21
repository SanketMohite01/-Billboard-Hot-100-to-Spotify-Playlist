# -Billboard-Hot-100-to-Spotify-Playlist

A Python project that scrapes the Billboard Hot 100 songs for a given date and automatically creates a private playlist in your Spotify account.

---

## 🔍 About the Project

This tool:
- Scrapes the top 100 songs from Billboard for a specific date (e.g., "2020-06-20")
- Matches those songs on Spotify
- Creates and fills a private playlist on your Spotify profile

---

## 💻 Tech Stack

- **Python 3**
- `requests` – to fetch Billboard data  
- `BeautifulSoup` – to parse HTML and extract song names  
- `Spotipy` – to interact with the Spotify Web API  
- `OAuth 2.0` – for secure Spotify authentication

---

## 🚀 How to Use

1. **Clone the repo**
   ```bash
   git clone https://github.com/yourusername/billboard-to-spotify.git
   cd billboard-to-spotify
Install requirements

pip install -r requirements.txt
Set up your Spotify app

Get your CLIENT_ID, CLIENT_SECRET

Set redirect URI to: http://127.0.0.1:8888/callback

Run the script
python main.py
