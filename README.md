# 🎵 YouTube Song Tracker

**YouTube Song Tracker** is a lightweight web-based application that helps users keep track of the songs they discover and listen to on YouTube. With music spread across multiple genres and languages, it's often hard to remember where you heard a song or what it was called. This app solves that problem by allowing you to save and organize your favorite YouTube songs by category, along with their direct links, for easy access later.

---

## 📚 Project Overview

This app is designed for content creators, music lovers, or anyone who frequently listens to music on YouTube and wants a simple, structured way to manage songs for personal reference or content planning. You can manually input the song title and YouTube link, assign a category, and browse your personal library with search and filtering tools. It’s perfect for preparing YouTube content like playlists, recommendations, remixes, or reviews.

---

## ✨ Features

- **🎧 Manual Song Entry**  
  Enter the title and link of a song you listened to on YouTube.

- **🗂 Categorization**  
  Choose from predefined music categories:
  - English Songs
  - Bollywood Songs
  - Phonks
  - Old Hindi Songs
  - Anime / Japanese Songs

- **🔍 Search & Filter**  
  Quickly search songs by title or filter them by category.

- **📅 Date Tracking**  
  Automatically records the date a song was added.

- **📤 Export Functionality**  
  Export your full list as a CSV or JSON file to keep backups or move your data.

- **⚙️ Optional Enhancements** (Planned)
  - Automatically fetch YouTube video titles from links
  - User login and personal libraries
  - Tag system or custom categories

---

## 🛠️ Tech Stack

| Layer     | Technology     |
|-----------|----------------|
| Frontend  | HTML, CSS, JavaScript *(or React for better UX)* |
| Backend   | Node.js + Express *(or Python Flask as an option)* |
| Database  | SQLite for local storage or Firebase for cloud sync |
| Deployment| Vercel, Netlify, or Render for free hosting |

---

## 📦 Local Development Setup

```bash
# Clone the repository
git clone https://github.com/yourusername/youtube-song-tracker.git
cd youtube-song-tracker

# Install dependencies (if using Node)
npm install

# Start development server
npm start
