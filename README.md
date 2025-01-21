# Chatting Application

A desktop-based chatting application implemented in **Java Swing**, featuring separate **Client** and **Server** interfaces. This project uses **socket programming** to enable real-time communication between clients and the server, providing a smooth and interactive chatting experience.

## Key Features

### Client-Side
- **Intuitive Chat UI:**
  - User-friendly interface for sending and receiving messages.
  - Dynamic chat bubbles with formatted text and timestamps.
- **Status Display:** Shows active status for the user.
- **Send Button:** Allows easy submission of messages via the chat box.

### Server-Side
- **Server Management:**
  - Displays incoming messages from connected clients.
  - Formats and displays messages dynamically.
- **Scalable Design:** Supports connections from multiple clients.

### Real-Time Communication
- **Socket Programming:** Enables seamless communication between the server and multiple clients.
- **Threaded Design:** Ensures that each client connection is handled independently.

## Technologies Used
- **Programming Language:** Java
- **Framework:** Java Swing
- **Network Communication:** Socket Programming (TCP/IP)
- **UI Design:**
  - Custom layouts and styling using `JPanel`, `JLabel`, and layout managers.
  - Dynamic chat bubbles styled with HTML-like elements.

## How to Run

### Prerequisites
- Java Development Kit (JDK) installed on your system.
- An IDE such as IntelliJ IDEA, Eclipse, or any text editor with Java support.

### Steps
1. Clone the repository:
   ```bash
   git clone <repository-link>
   ```

2. Navigate to the project directory and open it in your IDE.

3. **Server Setup:**
   - Compile and run the `Server.java` file to start the server.
   - Example command (if running via terminal):
     ```bash
     javac Server.java
     java chatting.application.Server
     ```

4. **Client Setup:**
   - Compile and run the `Client.java` file to start the client.
   - Example command (if running via terminal):
     ```bash
     javac Client.java
     java chatting.application.Client
     ```

5. **Establish Connection:**
   - Ensure the client connects to the server on the same network and port.
   - Messages sent from the client will now appear on the server and vice versa.

### Screenshots
![image](https://github.com/user-attachments/assets/d6c7e1a2-13f5-400c-b3d6-a8dc6073c7ea)

## Folder Structure
```
├── src
│   └── chatting.application
│       ├── Client.java
│       ├── Server.java
│       └── icons/ (contains the UI icons used in the project)
```

## Future Enhancements
- **Encryption:** Secure messages using encryption protocols for safe communication.
- **File Sharing:** Support for sending and receiving files between clients.
- **Message History:** Save chat history to a local or remote database.
- **UI Improvements:** Enhance the visual design for a more modern look.
- **Cross-Network Communication:** Allow connections over the internet, not just local networks.

## Contributing
Contributions are welcome! Feel free to fork this repository and submit pull requests to improve features or fix bugs.

## License
This project is open-source and available under the [MIT License](LICENSE).
