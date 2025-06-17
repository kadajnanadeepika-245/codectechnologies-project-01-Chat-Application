💬 Real-Time Chat Application\
A fully functional real-time chat application built using Java Sockets, JavaFX, and MySQL, enabling users to securely communicate through private or group conversations. Designed with a user-friendly interface and persistent message history, the app delivers a smooth and responsive chatting experience.

✨ Key Highlights
✅ Real-Time Messaging: Instant communication using Java Socket programming

✅ User Authentication: Login/signup system to ensure secure access

✅ Private & Group Chat Support: Chat one-on-one or within group conversations

✅ Persistent Message History: Store and retrieve messages from the database

✅ Modern UI: Built with JavaFX for a clean, responsive interface

🛠️ Tech Stack
Programming Language: Java

Frontend: JavaFX (GUI components)

Backend Communication: Java Sockets (Client-Server architecture)

Database: MySQL (for user credentials and chat history)


📁 Project Structure
📦 Chat Application
├── Client.java         → Client-side logic and UI controller
├── Server.java         → Server-side logic to handle multiple clients
├── LoginController.java → Handles user login and registration logic
├── ChatController.java  → Manages chat UI and messaging logic
├── DBManager.java       → Handles database connectivity and queries
├── chat.fxml           → JavaFX layout for chat window
├── login.fxml          → JavaFX layout for login/signup
└── database.sql         → SQL script to set up users and messages table

💻 How to Use
1️⃣ Clone the repository or download the project files
2️⃣ Set up the MySQL database using database.sql
3️⃣ Open the project in a Java IDE (e.g., IntelliJ, Eclipse)
4️⃣ Run Server.java to start the server
5️⃣ Run Client.java to launch the chat UI
6️⃣ Create an account or log in, and start chatting!

🔮 Future Enhancements
🔐 Password Encryption: Add hashing for secure password storage

📱 Mobile Version: Build Android support using Java/Kotlin

📁 File Sharing: Enable sending of images, documents, and other media

🔔 Notifications: Desktop alerts for new messages

🟢 User Presence Status: Show online/offline status of users
