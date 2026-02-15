# 🎵 Spotify Clone – Java Desktop Application

A desktop-based Spotify-inspired music player built using **Java** and **JavaFX**.  
This project demonstrates strong Object-Oriented Programming principles, event-driven architecture, and media handling using JavaFX MediaPlayer API.

---

## 📌 Project Description

The Spotify Clone is a modern music player application that allows users to:

- Play, pause, and stop songs
- Navigate between tracks (Next / Previous)
- Manage playlists
- View song progress using a dynamic progress bar
- Experience a clean and responsive UI

This project is designed to strengthen Java fundamentals and prepare for real-world software development.

---

## 🎯 Objectives

- Apply OOP principles (Encapsulation, Abstraction, Inheritance, Polymorphism)
- Build a structured and scalable project architecture
- Implement event handling using JavaFX
- Integrate JavaFX MediaPlayer for audio playback
- Create a modern and intuitive UI

---

## 🛠 Tech Stack

| Technology | Purpose |
|------------|----------|
| Java | Core Programming Language |
| JavaFX | UI Framework |
| JavaFX MediaPlayer API | Audio Playback |
| Maven / Gradle (Optional) | Dependency Management |
| IntelliJ / Eclipse / VS Code | Development Environment |

---

## 📂 Project Structure

```
SpotifyClone/
│
├── src/
│   ├── main/
│   │   ├── java/
│   │   │   ├── app/
│   │   │   │   ├── Main.java
│   │   │   │   ├── PlayerController.java
│   │   │   │   ├── PlaylistManager.java
│   │   │   │   └── Song.java
│   │   │   └── resources/
│   │   │       ├── songs/
│   │   │       └── styles.css
│
├── pom.xml / build.gradle
└── README.md
```

---

## 🚀 Features

### 🎶 Music Controls
- Play Song
- Pause / Resume
- Stop
- Next Track
- Previous Track
- Volume Control

### 📀 Playlist Management
- Create Playlist
- Add Songs
- Remove Songs
- Display Song List

### ⏱ Progress Tracking
- Real-time progress bar
- Song duration display
- Seek functionality

---

## 🧠 OOP Concepts Used

- **Encapsulation** → Song attributes with getters/setters  
- **Abstraction** → Separate controller and UI logic  
- **Inheritance** → Extend JavaFX components  
- **Polymorphism** → Event handling & overridden methods  

---

## 🔄 Application Flow

1. Application launches via `Main.java`
2. UI loads using JavaFX
3. User selects a song
4. MediaPlayer initializes the selected track
5. Event listeners manage playback controls
6. Progress bar updates in real-time

---

## 🏗 Future Enhancements

- 🔍 Search functionality  
- ❤️ Favorite songs  
- 🌙 Dark/Light theme toggle  
- 📡 Online streaming integration  
- 🔐 User authentication system  
- ☁ Cloud-based playlist storage  

---

## 📸 UI Preview (Planned Layout)

- Left Sidebar → Playlists  
- Center → Song List  
- Bottom Bar → Player Controls  

---

## 🧪 How to Run

### Option 1: Using IDE
1. Clone the repository
2. Open in IntelliJ / Eclipse / VS Code
3. Ensure JavaFX SDK is configured
4. Run `Main.java`

### Option 2: Using Maven
```
mvn clean install
mvn javafx:run
```

---

## 📈 Learning Outcomes

- Strong understanding of JavaFX
- Hands-on experience with MediaPlayer API
- Clean architecture design
- Event-driven programming mastery

---

## 👨‍💻 Author

**Sk Shanu**  
B.Tech CSE | Java Developer | Aspiring Software Engineer  

GitHub: https://github.com/shanu454  
LinkedIn: www.linkedin.com/in/sk-shanu-81-01z  

---

## 📜 License

This project is developed for educational purposes.  
Not affiliated with Spotify.

---

⭐ If you found this project useful, consider giving it a star!